<h1 align="center">Hi, I'm lst016 👋</h1>

<p align="center">
  用 React、TypeScript 和 Electron 构建 AI Agent 桌面应用，也把环境配置经验整理成可复用的 Skill。<br />
  Building desktop experiences for AI agents with React, TypeScript, and Electron, and turning environment setup workflows into reusable skills.
</p>

## tech-cc-hub

**桌面 AI Agent 工作台 · A desktop workspace for AI agents**

我正在构建 tech-cc-hub，将会话、任务、浏览器工具、模型路由和执行轨迹整合到同一个桌面应用中，让任务执行与结果查看更清晰。

I'm building tech-cc-hub to bring conversations, tasks, browser tools, model routing, and execution traces into one desktop app, making it easier to follow agent runs and review their results.

**[▶ 观看宣传片 · Watch the demo](https://tech-cc-hub-film.lst01.chatgpt.site)** &nbsp; · &nbsp; **[查看源码 · Explore the code](https://github.com/lst016/tech-cc-hub)** &nbsp; · &nbsp; **[快速开始 · Getting started](https://github.com/lst016/tech-cc-hub#快速启动)**

[![tech-cc-hub 桌面工作台 · Desktop workspace](https://raw.githubusercontent.com/lst016/tech-cc-hub/main/doc/assets/readme/app-workbench.png)](https://tech-cc-hub-film.lst01.chatgpt.site)

<p align="center"><sub>点击工作台预览图观看宣传片 · Click the workspace preview to watch the demo</sub></p>

### 功能亮点 · Highlights

- **任务与工作区 · Tasks & workspaces**  
  为任务绑定独立工作区，集中查看执行记录与产物。  
  Assign dedicated workspaces to tasks and keep execution records and outputs together.

- **模型路由 · Model routing**  
  分别配置主模型、专家模型、后台模型、Prompt 分析模型和图像处理模型。  
  Configure models for primary tasks, expert assistance, background work, prompt analysis, and image processing.

- **浏览器与执行追踪 · Browser tools & execution tracing**  
  使用内置浏览器进行截图和页面检查，通过时间线查看工具调用与执行过程。  
  Capture screenshots and inspect pages with the built-in browser, then review tool calls and agent activity in the execution timeline.

### 技术栈 · Built with

`Electron` · `React` · `TypeScript` · `Claude Agent SDK` · `MCP` · `SQLite`

## claude-environment-skill

**Claude 环境配置：真实 UI 图文 Skill · An illustrated skill for Claude environment setup**

把 kookeey、Clash、BitBrowser 与 Claude Code 的配置步骤整理成可复用的 Skill。通过真实界面截图、安装说明和只读检查脚本，帮助新电脑完成配置，也方便已有环境排障；可安装到 Codex 和 Claude Code。

A reusable skill that documents setup workflows across kookeey, Clash, BitBrowser, and Claude Code. Real UI screenshots, installation guides, and read-only checks help with new-machine setup and troubleshooting existing environments. Installable in both Codex and Claude Code.

**[查看项目 · Explore the project](https://github.com/lst016/claude-environment-skill)** &nbsp; · &nbsp; **[图文教程 · Illustrated guide](https://github.com/lst016/claude-environment-skill/blob/main/skills/claude-environment-setup/references/illustrated-guide.md)** &nbsp; · &nbsp; **[安装说明 · Installation](https://github.com/lst016/claude-environment-skill/blob/main/skills/claude-environment-setup/references/install.md)**

- **真实界面 · Real UI**：说明在哪里点、填什么、如何判断结果。 / Shows where to click, what to enter, and how to check the result.
- **复用与排障 · Reuse & troubleshooting**：优先复用已有配置，提供只读环境检查。 / Reuses existing setup where possible and provides read-only environment checks.
- **适用范围 · Platform scope**：主流程面向 macOS；Windows 提供安装入口和差异说明，尚未实机验收。 / Primarily for macOS; Windows installation notes are included, but have not been validated on a Windows machine.

## science-lab

**理化实验室：初中物理与化学 3D 互动实验 · Interactive 3D physics & chemistry labs for middle school**

从书库选一本教材，翻开立体书，调整参数、触发实验操作，观察装置与读数变化。覆盖人教版初中物理三册、化学两册共 181 项教材活动，每项附操作步骤、器材、结论、教材来源页和模型说明。

Pick a textbook from the library, open the pop-up book, adjust parameters, run the experiment, and watch the apparatus and readings change. Covers 181 activities from five PEP middle-school physics and chemistry textbooks, each with steps, equipment, conclusions, source pages, and model notes.

**[在线体验 · Try it online](https://lst016.github.io/science-lab/)** &nbsp; · &nbsp; **[查看源码 · Explore the code](https://github.com/lst016/science-lab)**

- **立体书交互 · Pop-up book UI**：翻页、目录搜索、近看/全景切换，支持键盘与触控。 / Page turning, searchable contents, close-up/overview camera, keyboard and touch support.
- **教学公式 · Teaching formulas**：光学、电学、密度、压强、浮力、杠杆等按教学公式计算读数；化学反应与微观过程以定性示意呈现。 / Optics, circuits, density, pressure, buoyancy, and levers use textbook formulas; chemical reactions and particle motion are shown qualitatively.
- **多端适配 · Responsive**：手机竖屏、横屏与桌面均可使用，WebGL 不可用时提供文字与读数。 / Works on portrait and landscape phones and on desktop, with a text fallback when WebGL is unavailable.

`Vite` · `React` · `TypeScript` · `Three.js` · `GitHub Pages`
