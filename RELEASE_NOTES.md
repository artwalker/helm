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

Known gaps in this release:

- Gemini CLI still needs broader real-world validation
- Some final UI and motion polish is still in progress
- A wider real-world pass on long-running Windows sessions is still useful

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

当前已知空缺：

- Gemini CLI 还需要更广泛的真实环境验证
- UI 和动效仍有最后一轮 polish 在进行中
- 长时间 Windows 实机会话还值得继续扩大样本验证
