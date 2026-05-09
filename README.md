<div align="center">

# 🖱️ Cursor 教程中文版

### 让中文开发者把 Cursor 的 Agent / Plan / Tab / CLI / Cloud 五条线全栈用起来

> 💎 **不是官方文档的翻译，而是为中文新手重写的双路径教程：理解篇讲清楚 Agent / Plan / Ask / Debug / Tab 的分工，官方篇当事实手册——两条路径同时跑，不替代彼此。**

[![类型](https://img.shields.io/badge/类型-Tutorial-blue?style=for-the-badge)](https://aiworkflowtutorials.com/docs/cursor)
[![章节](https://img.shields.io/badge/章节-87_篇-brightgreen?style=for-the-badge)](https://aiworkflowtutorials.com/docs/cursor)
[![语言](https://img.shields.io/badge/语言-简体中文-DC322F?style=for-the-badge)](#)
[![出品方](https://img.shields.io/badge/出品方-Anysphere-000000?style=for-the-badge)](https://cursor.com)
[![繁体](https://img.shields.io/badge/繁体-zh--Hant-9b59b6?style=for-the-badge)](https://aiworkflowtutorials.com/docs/cursor)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)](CONTRIBUTING.md)

</div>

---

> 🎯 **Cursor 不是"另一个 VSCode 插件"，它把 Agent、Plan、Ask、Debug、Tab、CLI、Cloud 七个面拼成一个完整 IDE。中文新手第一次容易在面板间迷路，这份教程把"什么时候用哪一面"先讲清楚。**
>
> 这份教程基于 Cursor 官方文档、CLI 行为和翔宇工作流真实项目实践重写，按「中文新手 → 第一性原理 → 循序渐进」组织。
> 12 篇 **从原理到实战** 帮你建立心智模型，8 个分组的 **官方教程中文版** 覆盖入门、Agent 工作流、上下文、CLI、Cloud Agent、集成 SDK、企业治理、排障细节。
>
> 完整教程托管在翔宇工作流的中文教程站，本仓库是公开门面入口，负责发现、反馈和样章预览。

<div align="center">

[🚀 立刻开始阅读](https://aiworkflowtutorials.com/docs/cursor) · [🧠 从原理到实战](https://aiworkflowtutorials.com/docs/cursor/understanding) · [📚 官方教程中文版](https://aiworkflowtutorials.com/docs/cursor/official) · [🐛 反馈问题](https://github.com/xiangyugongzuoliu/cursor-tutorial/issues)

</div>

---

## 📖 这是什么 (What)

> 💡 **核心定位**：中文开发者的 Cursor 学习入口 —— 一站把 Agent / Plan / Tab / CLI / Cloud / Bugbot 五条核心线 × 心智模型 × 真实项目工作流全讲透。

这是《AI 编程教程中文版》里的 Cursor 主题，由 [aiworkflowtutorials.com](https://aiworkflowtutorials.com/docs/cursor) 发布完整内容。本 GitHub 仓库只放门面入口、学习路线和样章摘录。

### 📐 双路径结构

| 路径 | 适合谁 | 章节数 | 入口 |
|------|--------|:------:|------|
| 🧠 **从原理到实战** | 想理解 Cursor 为什么这样设计 Agent / Plan / Ask / Tab 的分工 | **12 篇** | [开始 →](https://aiworkflowtutorials.com/docs/cursor/understanding) |
| 📚 **官方教程中文版** | 想直接查 Agent 工作流、上下文、CLI、Cloud、SDK、企业治理 | **75 篇** | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official) |

两条路径**结构对称、互相引用**：理解篇遇到「具体怎么配」时跳官方篇，官方篇遇到「为什么要这样」时跳理解篇。

### 🎯 这份教程的不同

- 🇨🇳 **为中文新手重写**：每篇按"先讲场景再讲原理"的顺序，避免官方文档跳跃式叙述
- 🖱️ **七个面板一次讲透**：Agent / Plan / Ask / Debug / Tab / CLI / Cloud，告诉你每一面解决什么问题
- 🧱 **从迁移到真实项目**：第二章直接教你怎么从 VSCode 迁移过来，不是空讲安装
- 🔁 **简繁双语**：简体 + 繁体同时维护，海外华人开发者直接可用

---

## 🚀 怎么用 (How to Use)

> 💡 **最佳用法 · 交给 AI Agent 讲给你听**
>
> 把本仓库 clone 下来或整段贴给 **Claude Code / OpenAI Codex** 这类 AI 编程 Agent，让它读完 README 后**按你的节奏一篇一篇讲**——不懂的随时打断追问，比自己埋头通读高效得多。

### 推荐阅读顺序

1. 先读官方教程中文版的「**入门、安装与模型**」5 篇，跑通安装、迁移、模型配置
2. 再读从原理到实战 **01-05**，建立 Cursor 怎么读上下文、Agent 与 Plan / Ask / Tab 怎么分工的心智模型
3. 回到真实项目，用一个小改动练习"Plan 先想 → Agent 再写 → Tab 提速 → Bugbot 复核"的闭环
4. 最后进入 **CLI / Cloud Agent / SDK / 企业治理**，把 Cursor 沉淀成团队级生产工具

### 🧠 从原理到实战（12 篇）

| # | 章节 | 链接 |
|:-:|------|------|
| 01 | Cursor 是什么 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/01-what-is-cursor) |
| 02 | 安装、迁移和第一个项目 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/02-install-migrate-first-project) |
| 03 | Cursor Agent 如何工作 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/03-how-cursor-agent-works) |
| 04 | Agent、Plan、Ask、Debug、Tab 怎么分工 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/04-agent-plan-ask-debug-tab) |
| 05 | 上下文、索引和 Rules | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/05-context-indexing-rules) |
| 06 | MCP、工具、浏览器和终端 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/06-mcp-tools-browser-terminal) |
| 07 | Skills、Subagents、Hooks | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/07-skills-subagents-hooks) |
| 08 | Cursor CLI 与 Headless 自动化 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/08-cli-headless-automation) |
| 09 | Cloud Agent、Bugbot 和 Review | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/09-cloud-agent-bugbot-review) |
| 10 | 模型、价格和用量 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/10-models-pricing-usage) |
| 11 | Cursor 和 Codex、Claude Code、Windsurf、Copilot 怎么选 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/11-cursor-vs-codex-claude-windsurf-copilot) |
| 12 | 一个真实项目里的 Cursor 工作流 | [阅读 →](https://aiworkflowtutorials.com/docs/cursor/understanding/12-real-project-workflow) |

### 📚 官方教程中文版（8 个分组 · 75 篇）

| 分组 | 主题 | 篇数 | 入口 |
|------|------|:----:|------|
| 🟢 **入门、安装与模型** | 第一次跑通 Cursor / 从 VSCode 迁移 / 选模型 | 5 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/00-getting-started) |
| 🟦 **Agent 工作流** | Agent 模式、Plan、Ask、Debug、Tab 全套实战 | 12 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/01-agent-workflow) |
| 🟡 **上下文与定制** | 上下文索引 / Rules / 知识库 / 个性化 | 6 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/02-context-customization) |
| 🟧 **CLI 与自动化** | Cursor CLI / Headless / 脚本化 | 14 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/03-cli-automation) |
| ☁️ **云端 Agent** | Cloud Agent / Bugbot / Review 流水线 | 12 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/04-cloud-agents) |
| 🔌 **集成、API 与 SDK** | 编辑器集成 / Cursor API / SDK 自定义 | 8 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/05-integrations-sdk) |
| 🏢 **团队与企业治理** | 团队 / SSO / 审计 / 权限 / 计费 | 11 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/06-teams-enterprise) |
| 🆘 **帮助与排障** | 故障排查 / FAQ / 网络配置 | 7 | [开始 →](https://aiworkflowtutorials.com/docs/cursor/official/07-help-troubleshooting) |

### 💡 第一次在项目里用 Cursor

```text
你（对 Cursor Agent）：

  我在 ~/projects/{repo}，先用 Plan 模式列一份「项目地图」：
  README、入口模块、关键依赖、测试目录、CI 配置怎么分工。
  然后提出三个最小可改进点（每条不超过 1 行），
  我选一个之后你切到 Agent 模式写 diff，我审完再 apply。
```

> 🎯 **Cursor 的核心是「Plan 先想、Agent 再写、Tab 提速、Bugbot 复核」**——七个面板各管一段，分清楚再动手。

---

## 🤝 怎么贡献 (Contribute)

本仓库**只接受 issue 反馈**，不接受完整教程正文 PR（完整内容在私有生产仓维护）。

适合提交的 issue：

- 🐛 **错别字 / 死链 / 事实错误**：教程站任意章节
- 🔗 **官方资料链接更新**：Cursor 文档结构调整的同步
- ✨ **样章表达问题**：本仓 `samples/` 里的样章
- 💡 **学习路径建议**：哪一章顺序应该调整、哪一篇应该补案例

[🐛 提交 Issue](https://github.com/xiangyugongzuoliu/cursor-tutorial/issues) · [📜 完整贡献指南](CONTRIBUTING.md) · [🔒 版权说明](COPYRIGHT.md)

如果这份教程帮到你，给本仓库一个 ⭐ 是最直接的鼓励——也方便其他中文开发者发现它。

---

## 👋 关于翔宇 (About)

> 🚀 **翔宇 — AI Agent 工作流研究者。**
>
> 把 AI 工具变成能持续运转的生产系统，专注 Claude Code / Codex 等 AI 编程 Agent 的真实工程化用法，把「AI 怎么帮普通人解决真实问题」作为长期方向。

### 📚 公开内容矩阵

| 平台 | 内容 | 链接 |
|------|------|------|
| 🌐 **翔宇工作流官网** | AI 编程 / Agent / 自动化深度教程 | [xiangyugongzuoliu.com](https://xiangyugongzuoliu.com) |
| 📺 **YouTube 频道** | AI 编程实战、Agent 知识库实战、视频教程 | [@xiangyugongzuoliu](https://www.youtube.com/@xiangyugongzuoliu) |
| 💻 **GitHub Profile** | 公开仓库 + 个人简介 | [@xiangyugongzuoliu](https://github.com/xiangyugongzuoliu) |
| 𝕏 **X / Twitter** | 工作流碎片 + 实战记录 | [@xiangyuworkflow](https://x.com/xiangyuworkflow) |
| 💬 **微信公众号** | 应用场景引流文 + 工作流案例 | 翔宇工作流 |

### 🎯 推荐先看

- 🤖 [**AI 编程教程中文版**](https://aiworkflowtutorials.com) — 本仓库所属的教程站全集
- 🎬 [**YouTube · Agent 知识库实战**](https://www.youtube.com/@xiangyugongzuoliu) — Claude Code / Codex 真实项目录屏
- 🌐 [**翔宇工作流官网**](https://xiangyugongzuoliu.com) — 项目复盘、踩坑记录、长文工作流

### 🎓 AI 编程实操课

想系统学习 AI 编程 / Agent 工作流（Claude Code / Codex 实战），可以看翔宇的 AI 编程实操课：

- 🇨🇳 **国内版（FlowUS）**：https://flowus.cn/xiangyugongzuoliu/share/d392dcad-b537-44ee-a3e2-56ff5af02bce
- 🌍 **国际版（Buy Me a Coffee）**：[buymeacoffee.com/xiangyu](https://buymeacoffee.com/xiangyu)

> 🎁 **会员附赠**：跟着课程一起交付的实战脚手架 + Cursor Rules / CLI / Cloud Agent 模板，把"读懂"变成"装进自己的工作流"。

---

<div align="center">

### ⭐ 如果这个教程对你有用，给一个 Star 让翔宇知道

[![翔宇官网](https://img.shields.io/badge/🌐_官网-xiangyugongzuoliu.com-FF6B35?style=for-the-badge)](https://xiangyugongzuoliu.com)
[![YouTube](https://img.shields.io/badge/📺_YouTube-频道-FF0000?style=for-the-badge)](https://www.youtube.com/@xiangyugongzuoliu)
[![GitHub](https://img.shields.io/badge/💻_GitHub-Profile-181717?style=for-the-badge)](https://github.com/xiangyugongzuoliu)

> 🎯 **工具一直在变，工作流不变。**
>
> 🛠️ **普通人对抗专业壁垒的唯一武器，就是工具。**

</div>
