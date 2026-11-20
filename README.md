# 一一 · Yiyi

**全栈开发 & AI Agent 工具链开发者** · 在线作品集与交互舞台：[miting.me](https://miting.me/)

专注用 **原生 Web / Node.js** 与 **Python / MCP** 构建低依赖、可观测、可复现的全栈工具与多宿主 AI Agent 工程工作流。

---

## Agent 工具链与交互全景

```text
[ 需求澄清 · qiwen ] ──▶ [ 工程编码与双轴审查 · yanlu ] ──▶ [ UI 方向与视觉审计 · huishu ]
         │                                                             │
         ▼                                                             ▼
[ 本地模型路由 · codex-provider-hub ] ◀────────────────────▶ [ 实时可观测 · codex-inline-stats ]
         │
         ├──▶ [ 本地 MCP 异步剪辑引擎 · editing-workbench (剪映 / DaVinci / AE / PR) ]
         ├──▶ [ AI 影视分镜流水线 · sd ]
         └──▶ [ 个人站与 2.5D 音游舞台 · miting.me (Vanilla JS / Canvas + Node.js Range) ]
```

---

## 精选项目 · Full-Stack & AI Agent

| 项目 | 定位 | 技术栈 | 核心工程设计 |
| :--- | :--- | :--- | :--- |
| **[editing-workbench](https://github.com/buyaoqifiyiyi/editing-workbench)** | Agent 剪辑引擎 | `Python` · `MCP` · `Agent` | 面向剪映 / DaVinci / AE / PR 的本地 MCP 异步任务编排（`describe_operations` / `start_job` / `job_status` / `read_job_output`）与创作知识检索（`search_knowledge`），将长耗时渲染与主对话上下文隔离 |
| **[codex-inline-stats](https://github.com/buyaoqifiyiyi/codex-inline-stats)** | Codex 实时用量监测 | `Python` · `Node.js` · `Windows` | 提供内嵌 DOM 统计栏与独立外置桌面窗口双模式；零第三方 npm/pip 依赖，解析响应均速、累计 Token、缓存命中率与 70% 上下文交接预警 |
| **[miting.me](https://miting.me/)** | 全栈交互个人站 | `Vanilla JS` · `Canvas 2.5D` · `Web Audio` · `Node.js` | 零框架自研四季 2.5D Mesh Avatar 交互舞台、动作曲线库、音谱/口型实时同步、`FM 39.39` 双模式音游及支持 HTTP `206 Range` 的媒体服务端 |
| **[yanlu](https://github.com/buyaoqifiyiyi/yanlu)** / **[huishu](https://github.com/buyaoqifiyiyi/huishu)** / **[qiwen](https://github.com/buyaoqifiyiyi/qiwen)** | 多宿主 Agent 技能生态 | `Python` · `Agent Skills` · `Prompt Engineering` | 串联需求质询、工程方法/双轴代码审查与 UI 设计审计；通过按需模块懒加载控制上下文开销，适配多 Agent 宿主规则 |

### 延伸工具与流水线

- **[codex-provider-hub](https://github.com/buyaoqifiyiyi/codex-provider-hub)** — Codex 本地多模型连接、模型目录与子代理调度管理中心（支持 Responses / Chat Completions / Anthropic Messages / Gemini 原生接口）。
- **[sd](https://github.com/buyaoqifiyiyi/sd)** — AI 影视虚拟制片生产系统，串联剧本诊断、角色/场景设定、分镜规划与视频模型成片级 Prompt 输出。

---

## 技术栈与工程偏好

| 维度 | 核心能力 |
| :--- | :--- |
| **全栈与前端交互** | `JavaScript (ES6+)` · `Node.js` (HTTP `Range` 流媒体服务端) · `HTML5 Canvas` · `Web Audio API` · `CSS3` |
| **AI Agent 与工具链** | `Python` · `MCP (Model Context Protocol)` · 按需懒加载 Skill 架构 · 上下文预算与可观测监测 · 自动化工作流 |
| **工程习惯** | 优先零依赖或轻量模块化、可验证的边界测试（实机浏览器 / HTTP 字节范围断言）、本地隐私优先 |

---

## 公开入口

- **个人站 & 在线交互 Demo**：[https://miting.me/](https://miting.me/)
- **GitHub 主页**：[https://github.com/buyaoqifiyiyi](https://github.com/buyaoqifiyiyi)

> 本主页及关联仓库中的同人影像与交互舞台演示均用于个人技术学习与作品展示。
