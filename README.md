<p align="center">
  <img src="assets/readme/hero.jpg" width="100%" alt="踏雪寻仙：雪原上，「寻」字拖出一条路，通向远处的「仙」">
</p>

<div align="center">

# 踏雪寻仙 · taxueseek

> 在 AI 时代寻仙问道，把人生决策、投资研究与创作表达，做成一个个可复用的 Agent Skill。
>
> In the age of AI, turning life decisions, investment research, and creative expressions into reusable Agent Skills.

[![X（Twitter）@TaXue2025](https://img.shields.io/twitter/follow/TaXue2025?style=for-the-badge&logo=x&logoColor=white&color=0f172a&labelColor=0f172a&label=X%20%40TaXue2025)](https://x.com/TaXue2025)
[![GitHub Followers](https://img.shields.io/github/followers/taxueseek?style=for-the-badge&logo=github&logoColor=white&color=38bdf8&label=Followers)](https://github.com/taxueseek?tab=followers)
[![Total Stars](https://img.shields.io/github/stars/taxueseek?style=for-the-badge&logo=github&logoColor=white&color=fbbf24&label=Total%20Stars)](https://github.com/taxueseek?tab=repositories)
[![Public Repos](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=Repositories&query=%24.public_repos&color=0ea5e9&url=https%3A%2F%2Fapi.github.com%2Fusers%2Ftaxueseek)](https://github.com/taxueseek?tab=repositories)

<p><a href="#zhongwen">中文</a> · <a href="#english">English</a></p>

</div>

---

<a id="zhongwen"></a>

## 核心支柱 · Core Pillars

### 1. 搜索基建：[argo](https://github.com/taxueseek/argo)
**专为 AI Agent 打造的轻量级开源搜索与证据核验工具**
- **200+ 引擎智能路由**：覆盖中文、英文、学术、代码、金融行情、新闻与百科，按领域自动分诊，不扫全网网页垃圾。
- **交付证据而非死链**：带可信度分解，直接向 Agent 输出高信噪比 Markdown，不挤占上下文窗口。
- **全生态即插即用**：免费源优先，API Key 全可选；原生支持 Claude Code、Cursor、MCP 服务以及 DeepSeek Harness（DSH）。

### 2. 文字创作：[plainspoken-writing](https://github.com/taxueseek/plainspoken-writing)
**专业消除 AI 味的白描写作规范与技能**
- **机械腔精准诊断**：精准识别空洞套话、过度对称排比、假大空升华与生硬转折。
- **直击筋骨，克制改写**：坚持「先诊断、后修改」原则，尊重原作者意图，还原本色表达。
- **跨平台适配**：同时提供通用的 Claude Code / Agent Skill 规范与专用的 DSH 插件版本。

### 3. 审美视觉：踏雪美学生图家族
**摆脱千篇一律的通用生图，回归有实体质感的印刷工艺与东方风物**
- [**taxue-halftone**](https://github.com/taxueseek/taxue-halftone) —— 半调海报 Skill：双色半调、Riso 印刷、蓝染与点阵解构，把一句话或一张图做成艺术封面。
- [**taxue-creative-style**](https://github.com/taxueseek/taxue-creative-style) —— 踏雪创意插画 Skill：内置 14 个风格家族、提示词七维优化与 3D 东方书法。
- [**taxue-solar-polaroid**](https://github.com/taxueseek/taxue-solar-polaroid) —— 节气拍立得 Skill：二十四节气风物、节日短句与地域记忆推演，输出可珍藏的纸本画幅。

### 4. 记忆资产：[session-digger](https://github.com/taxueseek/session-digger)
**跨环境 AI 会话历史挖掘与知识沉淀基础设施**
- 穿透 Claude、Grok、Kimi Code、Codex、WorkBuddy 与 Trae 等异构环境。
- 将散落在本地磁盘上的原始会话记录转化为结构化索引与可调用的个人经验库。

---

## 视觉画廊 · Visual Gallery

从混沌概念到实体纸本印痕。以下作品由踏雪美学家族生成，点击图片直达对应开源仓库：

<p align="center">
  <a href="https://github.com/taxueseek/taxue-creative-style"><img src="assets/readme/proof-calligraphy.jpg" width="32%" alt="3D 书法「道」"></a>
  <a href="https://github.com/taxueseek/taxue-creative-style"><img src="assets/readme/proof-autumn.jpg" width="32%" alt="治愈插画「晚秋」"></a>
  <a href="https://github.com/taxueseek/taxue-solar-polaroid"><img src="assets/readme/proof-lichun.jpg" width="32%" alt="节气拍立得「立春」"></a>
</p>

---

## 垂类决策与专业技能 · Domain Skills

把反复决策的专业方法论，沉淀为开箱即用的 Agent 能力：

- [**taxue-invest**](https://github.com/taxueseek/taxue-invest) —— 投资分析体系：11 个方法论技能与 17 个数据源（同花顺、东财、妙想、yfinance、FMP、Wind、天天基金等），覆盖个股、基金、资产配置与宏观周期。
- [**taxueskills**](https://github.com/taxueseek/taxueskills) —— 踏雪决策系统：13 个协同路由技能，将人生与职业中的模糊问题拆解为明确的第一步。
- [**ime-lexicon**](https://github.com/taxueseek/ime-lexicon) —— 微信输入法与豆包输入法个人词库工具：词库识别、导出备份、智能纠错与行业专词构建。
- [**agent-relay**](https://github.com/taxueseek/agent-relay) —— 跨产品 Agent 任务接力：多平台环境适配与无缝委派。

---

## DeepSeek Harness（DSH）生态插件 · Ecosystem Plugins

在 DSH 生态中深耕的轻量级、高稳定性工具链：

| 插件 | 功能定位与特色 |
|---|---|
| [**argo**](https://github.com/taxueseek/argo) | 全局搜索基座：200+ 引擎免 Key 聚合，交付高纯度结构化证据 |
| [**dsh-files**](https://github.com/taxueseek/dsh-files) | 原生上传管线：文件夹按钮、PDF、DOCX 与 XLSX 文档深度解析 |
| [**plugin-fast-adapt**](https://github.com/taxueseek/plugin-fast-adapt) | 宿主升级适配：破坏性变更核查、五形态插件脚手架与启动诊断 |
| [**dsh-plugin-guard**](https://github.com/taxueseek/dsh-plugin-guard) | 安全审计诊所：安装前后静态审计、哈希校验锁与机械排毒 |
| [**dsh-models**](https://github.com/taxueseek/dsh-models) | 路由控制面板：模型选择、子代理委派与推理层级三分区管理 |
| [**dsh-snippets**](https://github.com/taxueseek/dsh-snippets) | 极简片秘书箱：常用命令、网址与提示词的零依赖快速召回 |
| [**dsh-healthcheck**](https://github.com/taxueseek/dsh-healthcheck) | 环境只读体检：磁盘、内存、延迟与版本落后检测，附历史基线 |
| [**taxue-dsh-artisan**](https://github.com/taxueseek/taxue-dsh-artisan) | 一体化画师：提示词反推优化与多供应商后台异步生图 |

---

<a id="english"></a>

## Core Pillars (English)

### 1. Search Infrastructure: [argo](https://github.com/taxueseek/argo)
**Lightweight, open-source search and verification engine designed specifically for AI Agents.**
- **200+ Engines Routed Dynamically**: Academic papers, code, financial quotes, news, and encyclopedia across multiple languages without scraping noisy web pages.
- **Evidence Over Links**: Delivers clean Markdown with credibility scores directly into the agent's context.
- **Universal Integration**: Ready for Claude Code, Cursor, MCP servers, and DeepSeek Harness (DSH).

### 2. Writing & Text Creation: [plainspoken-writing](https://github.com/taxueseek/plainspoken-writing)
**Eliminate boilerplate AI flavors and restore concise, authentic human voice.**
- **Diagnostic-First**: Accurately flags fluff, hollow parallelism, synthetic excitement, and robotic transitions.
- **Non-Destructive**: Provides audit reports before changes, preserving original intent and voice.

### 3. Aesthetics & Design: The taxue Generative Suite
**Shifting from generic visual cliches to tactile print craft and Oriental aesthetics.**
- [**taxue-halftone**](https://github.com/taxueseek/taxue-halftone) — Halftone poster skill: Duo-tone, Risograph, indigo dye, and grid deconstruction.
- [**taxue-creative-style**](https://github.com/taxueseek/taxue-creative-style) — 14 family styles, 7-dimension prompt refinement, and 3D calligraphy.
- [**taxue-solar-polaroid**](https://github.com/taxueseek/taxue-solar-polaroid) — 24 solar terms and cultural archive illustrations.

### 4. Memory Infrastructure: [session-digger](https://github.com/taxueseek/session-digger)
**Cross-environment conversation mining and knowledge base for AI agents.**
- Indexes historical sessions from Claude Code, Grok, Kimi Code, Codex, WorkBuddy, and Trae.
- Transforms local raw session records into a queryable second brain.

---

## Connect & Collaborate

- **X (Twitter)**: [@TaXue2025](https://x.com/TaXue2025)
- **Feedback & Issues**: Feel free to open an issue or pull request in the respective repositories.

<div align="center">

> 晚来天欲雪，能饮一杯无？
> 
> *In the quiet before the snow falls, care to share a warm cup?*

<sub>如果这里的工具对你有所启发，欢迎点亮 Star 支持。 / If something here is useful, a Star is appreciated.</sub>

</div>