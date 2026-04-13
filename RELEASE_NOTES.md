# helm v0.1.0

## English

Initial public release of `helm`, a Windows desktop approval layer for AI coding agents running inside WSL.

Highlights:

- Approval flow for Claude Code, Codex, and Gemini CLI
- GUI handling for `AskUserQuestion`
- Smart auto-approve for obvious low-risk reads
- Danger-priority request queue
- Minibar, tray, and global hotkey
- Built-in setup and connection repair
- Agent-aware colors, sounds, and mascot system
- One-click agent launch from the desktop panel
- Mascot sticker pack export in `release/mascots/`
- Founding Beta Access / paid entitlement / grace-period model first pass

System requirements:

- Windows 10 or 11
- WSL2
- WebView2 runtime
- Claude Code, Codex, or Gemini CLI installed inside your Linux environment

Known gaps in this release:

- Gemini CLI still needs broader real-world validation
- Some final UI and performance polish is still in progress
- Final Windows runtime verification is still required before public release

## 中文

`helm` 的首个公开版本。它是一个运行在 Windows 上的桌面审批层，用来接住 WSL 中 AI coding agent 的关键操作请求。

本版重点：

- 支持 Claude Code、Codex、Gemini CLI 的审批链路
- 支持 `AskUserQuestion` 的 GUI 回答
- 明显低风险读取操作可自动放行
- 危险请求优先排队
- 提供 minibar、tray 和全局快捷键
- 内置初始化与连接修复流程
- agent 专属颜色、音效和吉祥物系统
- 可从桌面面板一键启动 agent
- Founding Beta Access / 正式版权益 / 宽限期 这套商业化模型第一版

系统要求：

- Windows 10 / 11
- WSL2
- WebView2 runtime
- 在 Linux 环境中安装 Claude Code、Codex 或 Gemini CLI

当前已知空缺：

- Gemini CLI 还需要更广泛的真实环境验证
- UI 和性能仍有最后一轮 polish 在进行中
- 公开发布前还需要完成一轮 Windows 实机验收
