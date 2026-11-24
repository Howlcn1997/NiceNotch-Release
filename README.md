# NiceNotch

NiceNotch 是一款 macOS 刘海工具：在刘海里查看待办、笔记、剪贴板、音乐播放和 AI 助手的完成提示。

这个仓库只用于发布安装包，源码不在这里。

## 下载

在 [Releases](https://github.com/Howlcn1997/NiceNotch-Release/releases/latest) 下载最新的 `NiceNotch-X.Y.Z-universal.dmg`，打开后将 `NiceNotch.app` 拖入 `Applications`。

- 同一安装包支持 Apple Silicon 和 Intel Mac，需要 macOS 14 或更新版本。
- 安装包使用 ad-hoc 签名，尚未经过 Apple 公证。首次打开被拦截时，请阅读安装包内的「安装说明.txt」，或在「系统设置 → 隐私与安全性」中选择「仍要打开」。
- `.sha256` 文件用于验证 DMG 的 SHA-256 校验值。

## 更新

从 0.1.11 起，可以在「设置 → 通用 → 关于」点击「检查更新」，在应用内安装新版本。应用会验证更新清单和安装包的签名。
