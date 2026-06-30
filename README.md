# Mac 新机开荒指南

> 个人 Mac 装机备忘：必备软件、系统设置、终端配置。  
> 风格参考 [ssnhd/mac](https://github.com/ssnhd/mac)，内容全部基于实际使用精选。

---

## 目录

- [开发工具](#开发工具)
- [效率工具](#效率工具)
- [浏览器 & 扩展](#浏览器--扩展)
- [系统增强](#系统增强)
- [社交通讯](#社交通讯)
- [媒体播放与下载](#媒体播放与下载)
- [办公 & 笔记](#办公--笔记)
- [实用工具](#实用工具)
- [系统设置](#系统设置)
- [终端配置](#终端配置)

---

## 开发工具

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| [Homebrew](https://brew.sh) | macOS 包管理器，装一切的前提 | 官网脚本 | ✅ 已安装 |
| [Claude Code](https://docs.anthropic.com/zh-CN/docs/claude-code/overview) | Anthropic 官方 AI CLI 编程助手 | `brew install --cask claude-code` | ✅ 已安装 |
| [CC-Switch](https://www.ccswitch.io/zh/) | Claude Code / Codex / Gemini CLI 配置管理与切换 | 官网下载 | ✅ 已安装 |
| [Ghostty](https://ghostty.org) | 新一代 GPU 加速终端模拟器 | `brew install --cask ghostty` | ✅ 已安装 |
| [Surge](https://nssurge.com) | 网络代理 + 流量调试工具 | 官网下载 | ✅ 已安装 |
| [Docker](https://www.docker.com/products/docker-desktop/) | 容器化开发环境 | 官网下载 | ✅ 已安装 |
| [VS Code](https://code.visualstudio.com) | 主力代码编辑器 | `brew install --cask visual-studio-code` | 💡 推荐 |
| [Cursor](https://cursor.sh) | AI-native 编辑器（VS Code 分支） | 官网下载 | 💡 推荐 |
| [Sublime Merge](https://www.sublimemerge.com) | Git GUI 客户端，简洁够用 | `brew install --cask sublime-merge` | 💡 推荐 |

---

## 效率工具

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| [HapiGo](https://www.hapigo.com) | 国产启动器，搜索/翻译/剪贴板/文件管理 | 官网下载 | ✅ 已安装 |
| [Bob](https://bobtranslate.com) | macOS 划词翻译天花板 | 官网下载 | ✅ 已安装 |
| [Obsidian](https://obsidian.md) | 本地优先的 Markdown 笔记 | 官网下载 | ✅ 已安装 |
| [Typora](https://typora.io) | 所见即所得 Markdown 编辑器 | 官网下载 | ✅ 已安装 |
| [CotEditor](https://coteditor.com) | 轻量纯文本/代码编辑器，秒开大文件 | App Store | ✅ 已安装 |
| [Scherlokk](https://scherlokk.com) | 文件内容全文搜索 | 官网下载 | ✅ 已安装 |
| [BuhoLaunchpad](https://apps.apple.com/app/buholaunchpad/id1625306399) | 启动台图标整理 | App Store | ✅ 已安装 |
| [Raycast](https://raycast.com) | Spotlight 替代品 + 插件生态 | `brew install --cask raycast` | 💡 推荐 |

---

## 浏览器 & 扩展

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| [Google Chrome](https://www.google.com/chrome/) | 开发调试标配 | `brew install --cask google-chrome` | ✅ 已安装 |
| [Quark](https://quark.sm.cn) | 夸克浏览器 | 官网下载 | ✅ 已安装 |
| [Noir](https://getnoir.app) | Safari 暗黑模式扩展 | App Store | ✅ 已安装 |
| [Tampermonkey](https://www.tampermonkey.net) | 浏览器脚本管理器 | 浏览器扩展商店 | ✅ 已安装 |
| [Immersive Translate](https://immersivetranslate.com) | 沉浸式双语翻译扩展 | 浏览器扩展商店 | ✅ 已安装 |
| [BewlyBewly](https://github.com/BewlyBewly/BewlyBewly) | B 站网页界面重设计扩展 | 浏览器扩展商店 | ✅ 已安装 |
| [uBlock Origin Lite](https://github.com/uBlockOrigin/uBOL-home) | 轻量广告拦截 | 浏览器扩展商店 | ✅ 已安装 |
| [Arc Browser](https://arc.net) | 颜值与空间管理最强的浏览器 | 官网下载 | 💡 推荐 |

---

## 系统增强

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| [iRightMouse（超级右键）](https://www.better365.cn/irightmouse.html) | 右键菜单增强：新建文件、复制路径、终端打开 | App Store | ✅ 已安装 |
| [Mos](https://mos.caldis.me) | 鼠标平滑滚动 + 方向控制 | 官网下载 | ✅ 已安装 |
| [Keka](https://www.keka.io) | 免费解压压缩 | `brew install --cask keka` | ✅ 已安装 |
| [App Cleaner 9](https://nektony.com/mac-app-cleaner) | 彻底卸载应用，清理残留 | 官网下载 | ✅ 已安装 |
| [Mole](https://github.com/atoms18/mole) | 菜单栏隐藏图标管理 | 官网/GitHub | ✅ 已安装 |
| [BetterDisplay](https://github.com/waydabber/BetterDisplay) | 显示器分辨率 / HiDPI / 亮度管理 | 官网下载 | ✅ 已安装 |
| [Latest](https://max.codes/latest) | 应用更新检测 | `brew install --cask latest` | ✅ 已安装 |
| [Dynamic Wallpaper](https://dynamicwallpaper.club) | 动态壁纸 | App Store | ✅ 已安装 |
| [xNTFS](https://www.ntfsformac.com) | NTFS 磁盘读写支持 | 官网下载 | ✅ 已安装 |
| [Folder Preview Pro](https://apps.apple.com/app/folder-preview/id1519269057) | 文件夹图标预览增强 | App Store | ✅ 已安装 |
| [Rectangle](https://rectangleapp.com) | 开源免费窗口管理，分屏快捷键 | `brew install --cask rectangle` | 💡 推荐 |

---

## 社交通讯

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| 微信 | 没办法，生态绑架 | App Store | ✅ 已安装 |
| QQ | 轻聊版够用 | App Store | ✅ 已安装 |
| [Telegram](https://telegram.org) | 跨平台即时通讯 | App Store | ✅ 已安装 |

---

## 媒体播放与下载

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| [IINA](https://iina.io) | macOS 最强本地播放器 | `brew install --cask iina` | ✅ 已安装 |
| [SenPlayer](https://senplayer.com) | 高颜值 HDR 播放器 | App Store | ✅ 已安装 |
| [APTV](https://apps.apple.com/cn/app/aptv/id1630403500) | IPTV 直播源播放 | App Store | ✅ 已安装 |
| [PiliPlus](https://github.com/guozhigq/pilipala) | 哔哩哔哩第三方客户端 | GitHub | ✅ 已安装 |
| [QQLive](https://v.qq.com) | 腾讯视频 | App Store | ✅ 已安装 |
| 抖音 | 抖音客户端 | App Store | ✅ 已安装 |
| [Downie 4](https://software.charliemonroe.net/downie/) | 网页视频下载神器 | 官网下载 | ✅ 已安装 |
| [Permute 4](https://software.charliemonroe.net/permute/) | 拖拽式视频/音频格式转换 | 官网下载 | ✅ 已安装 |
| [Motrix Next](https://motrix.app) | 全能下载工具（HTTP/BT/磁力） | 官网下载 | ✅ 已安装 |
| [百度网盘](https://pan.baidu.com) | 网盘备份 | 官网下载 | ✅ 已安装 |

---

## 办公 & 笔记

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| [WPS Office](https://www.wps.cn) | 国产 Office，兼容性好 | 官网下载 | ✅ 已安装 |
| [Notion](https://www.notion.so) | 全能笔记 + 协作工作空间 | 官网下载 | 💡 推荐 |

---

## 实用工具

| 软件 | 说明 | 安装方式 | 状态 |
|------|------|----------|------|
| [iShot Pro](https://www.better365.cn/ishot) | 截图 / 长截图 / 录屏 / 标注 | App Store | ✅ 已安装 |
| [iMazing](https://imazing.com) | iOS 设备备份与文件管理 | 官网下载 | ✅ 已安装 |
| [Parallels Desktop](https://www.parallels.com) | Mac 虚拟机，跑 Windows | 官网下载 | ✅ 已安装 |

---

## 系统设置

macOS 重装后必调的几个设置：

```bash
# ============================
# 触控板 & 键盘
# ============================

# 轻点来点按（触控板）
defaults write com.apple.AppleMultitouchTrackpad Clicking -bool true

# 开启三指拖移
defaults write com.apple.AppleMultitouchTrackpad TrackpadThreeFingerDrag -bool true

# 键盘重复速率调到最快
defaults write NSGlobalDomain KeyRepeat -int 2
defaults write NSGlobalDomain InitialKeyRepeat -int 15

# ============================
# 访达 Finder
# ============================

# 显示所有文件扩展名
defaults write NSGlobalDomain AppleShowAllExtensions -bool true

# 显示隐藏文件
defaults write com.apple.finder AppleShowAllFiles -bool true

# 显示路径栏
defaults write com.apple.finder ShowPathbar -bool true

# 显示状态栏
defaults write com.apple.finder ShowStatusBar -bool true

# 默认以列表视图打开
defaults write com.apple.finder FXPreferredViewStyle -string "Nlsv"

# ============================
# 程序坞 Dock
# ============================

# 自动隐藏
defaults write com.apple.dock autohide -bool true

# 隐藏已关闭应用图标
defaults write com.apple.dock show-recents -bool false

# 重启 Dock 生效
killall Dock

# ============================
# 截屏
# ============================

# 截图保存到 Downloads
defaults write com.apple.screencapture location -string "$HOME/Downloads"

# 截图格式改为 jpg（体积更小）
defaults write com.apple.screencapture type -string "jpg"

# ============================
# 安全性
# ============================

# 允许任何来源安装应用
sudo spctl --master-disable
```

#### 输入法

```bash
# 官网下载并安装豆包输入法

# 删除自带的 ABC 输入法（按需）
brew install --cask plistedit-pro
sudo open ~/Library/Preferences/com.apple.HIToolbox.plist
# 在 PlistEdit Pro 中打开 Root → AppleEnabledInputSources，
# 找到 KeyboardLayout 为 "ABC" 的整条 item 并删除

# ⚠️ 关键步骤：防止系统自动还原
open ~/Library/Preferences
# 右键 com.apple.HIToolbox.plist → 显示简介 → 勾选「锁定」

brew uninstall --cask plistedit-pro
```

---

## 终端配置

```bash
# ============================
# Oh My Zsh
# ============================
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# 推荐插件
# 编辑 ~/.zshrc
plugins=(
  git
  zsh-autosuggestions
  zsh-syntax-highlighting
  z
)

# ============================
# Git 别名
# ============================
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.lg "log --oneline --graph --decorate --all"

# ============================
# Homebrew 一次性安装
# ============================
brew install --cask \
  claude-code \
  ghostty \
  google-chrome \
  keka \
  latest \
  iina
```

---

## 补充说明

- 状态栏：`✅ 已安装` 表示当前正在使用，`💡 推荐` 表示虽未安装但值得尝试。
- 参考项目：[ssnhd/mac](https://github.com/ssnhd/mac) — 更全面的 Mac 装机指南。
- 持续更新中，每次重装系统都会回来翻。
