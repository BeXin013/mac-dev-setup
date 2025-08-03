# mac-dev-setup
# 🍎 mac-dev-setup

> 在中国大陆使用 Mac 作为开发主力机的一键配置脚本。

本仓库用于初始化一台新 Mac，自动安装常用开发工具，并配置适配国内网络的镜像源。

## 📦 安装内容（自动）

- Homebrew（使用中科大源）
- CLI 工具：git, zsh, wget, curl, gh
- 编程语言环境：Node.js (via nvm), Python (via pyenv)
- 软件包管理器：npm, pip
- GUI 软件（部分通过 Homebrew Cask 安装）：
  - ✅ QQ / 微信 / Edge
  - ✅ Obsidian / Zotero / Typora
  - ✅ ClashX Pro / 钱迹 / Kiro / DBeaver
  - ✅ Steam 等
- 科学上网辅助：ClashX Pro（需手动导入配置）

## 🚀 快速开始

```bash
git clone https://github.com/BeXin013/mac-dev-setup.git
cd mac-dev-setup
chmod +x setup.sh
./setup.sh
🪄 未来计划
 GUI 软件列表可选择性安装

 自定义国内源配置项

 配置文件备份与同步

📝 许可
MIT License.

yaml
复制
编辑

---

## ✅ 3. 建议目录结构

```bash
mac-dev-setup/
├── setup.sh             # 主安装脚本
├── README.md            # 仓库说明文档
├── Brewfile             # Homebrew 安装清单（可选）
├── config/              # 预设配置（zshrc, gitconfig 等）
├── apps/                # 钱迹、ClashX Pro等 .dmg 安装包（可选）
