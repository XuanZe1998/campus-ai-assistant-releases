# 校园 AI 连接助手

本仓库仅提供安装包、SHA-256 校验文件与使用说明。下载无需登录 GitHub；使用校园 AI 服务仍需完成校园身份认证。

## 下载 0.3.4

| 系统 | 安装包 |
| --- | --- |
| Windows 10/11 x64 | [下载 EXE 安装器](https://github.com/XuanZe1998/campus-ai-assistant-releases/releases/download/assistant-v0.3.4/CampusAssistant-Setup-0.3.4-windows-x64.exe) |
| macOS 12+ · Apple 芯片 | [下载 arm64 ZIP](https://github.com/XuanZe1998/campus-ai-assistant-releases/releases/download/assistant-v0.3.4/CampusAssistant-0.3.4-macos-arm64.zip) |
| macOS 12+ · Intel | [下载 amd64 ZIP](https://github.com/XuanZe1998/campus-ai-assistant-releases/releases/download/assistant-v0.3.4/CampusAssistant-0.3.4-macos-amd64.zip) |

[全部发布文件与校验值](https://github.com/XuanZe1998/campus-ai-assistant-releases/releases/latest)

## 安装和使用

**Windows**：双击 EXE 安装，随后从桌面或开始菜单启动。无需安装开发环境，无需管理员权限。[详细说明](INSTALL-Windows.md)

**Mac**：在「关于本机」确认芯片类型，下载对应 ZIP 并解压，将 `Campus AI Assistant.app` 拖入「应用程序」，双击启动。允许访问登录钥匙串。[详细说明](INSTALL-macOS.md)

启动后点击「校园登录与设备注册」，按配对码完成校园 CAS 授权。返回助手测试连接，再将本机接入信息填写到 AI 客户端。默认连接 https://gordanshop.com。

关闭浏览器标签不会退出后台代理，请使用页面底部的「退出助手」。安装包不包含账号、API Key 或设备私钥。

## 系统提示

Windows 包尚无发布者代码签名，Mac 包尚无 Apple Developer ID 签名和公证，首次运行可能出现系统安全提示。Mac 如被阻止，请在「系统设置 → 隐私与安全性」核对来源后选择允许打开。

Mac 已通过 GitHub macOS 环境的原生测试，尚未完成真实 Mac 的 Finder 与校园授权完整流程验收。
