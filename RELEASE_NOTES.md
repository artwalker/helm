# helm v0.1.1

## English

Polish update for `helm`, the Windows desktop approval layer for AI coding agents running inside WSL.

Highlights:

- Approval flow for Claude Code, Codex, and Gemini CLI
- GUI handling for `AskUserQuestion`
- Smart auto-approve for obvious low-risk reads
- Danger-priority request queue
- Minibar, tray, and global hotkey
- Built-in setup and connection repair
- Agent-aware colors, sounds, and mascot system
- One-click agent launch from the desktop panel
- Human-readable license activation and verification errors
- Product-facing purchase, activation, and update copy across the app and website
- Faster first-switch behavior for Home / History / Settings cold paths

System requirements:

- Windows 10 or 11
- WSL2
- WebView2 runtime
- Claude Code, Codex, or Gemini CLI installed inside your Linux environment

Release focus in this update:

- Approval reliability, launch flow, and product-facing clarity
- Signed Windows MSI as the default download path
- Stable public endpoints for activation, update discovery, and release notes

## 中文

`helm` 的一次 polish 更新。它是一个运行在 Windows 上的桌面审批层，用来接住 WSL 中 AI coding agent 的关键操作请求。

本版重点：

- 支持 Claude Code、Codex、Gemini CLI 的审批链路
- 支持 `AskUserQuestion` 的 GUI 回答
- 明显低风险读取操作可自动放行
- 危险请求优先排队
- 提供 minibar、tray 和全局快捷键
- 内置初始化与连接修复流程
- agent 专属颜色、音效和吉祥物系统
- 可从桌面面板一键启动 agent
- license 激活与验证错误改成人话
- 软件内、官网、购买页的文案统一收口为产品表达
- 首页 / 历史 / 设置 的首次切换冷路径进一步提速

系统要求：

- Windows 10 / 11
- WSL2
- WebView2 runtime
- 在 Linux 环境中安装 Claude Code、Codex 或 Gemini CLI

本次更新的重点：

- 审批稳定性、启动链路与产品表达的统一
- 以已签名的 Windows MSI 作为默认下载路径
- 激活、更新检查、版本说明都落到稳定的公开地址
