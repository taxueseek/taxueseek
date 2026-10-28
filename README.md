<p align="center">
  <img src="assets/readme/hero.jpg" width="100%" alt="踏雪寻仙：雪原上，「寻」字拖出一条路，通向远处的「仙」">
</p>

<div align="center">

# 踏雪寻仙 · taxueseek

> 在 AI 时代寻仙问道，把人生决策、投资研究、创作表达，做成一个个可复用的 Agent Skill。
>
> In the age of AI, I turn life decisions, investment research, and creative work into reusable Agent Skills.

[![X（Twitter）@TaXue2025](https://img.shields.io/twitter/follow/TaXue2025?style=for-the-badge&logo=x&logoColor=white&color=0f172a&labelColor=0f172a&label=X%20%40TaXue2025)](https://x.com/TaXue2025)
[![GitHub Followers](https://img.shields.io/github/followers/taxueseek?style=for-the-badge&logo=github&logoColor=white&color=38bdf8&label=Followers)](https://github.com/taxueseek?tab=followers)
[![Total Stars](https://img.shields.io/github/stars/taxueseek?style=for-the-badge&logo=github&logoColor=white&color=fbbf24&label=Total%20Stars)](https://github.com/taxueseek?tab=repositories)
[![Public Repos](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=Repositories&query=%24.public_repos&color=0ea5e9&url=https%3A%2F%2Fapi.github.com%2Fusers%2Ftaxueseek)](https://github.com/taxueseek?tab=repositories)

<p><a href="#zhongwen">中文</a> · <a href="#english">English</a></p>

</div>

---

<a id="zhongwen"></a>

我在做三件事。

## 给 Agent 用

搜索、会话、终端，都做给 Agent 直接用。

- [**argo**](https://github.com/taxueseek/argo) — 给 Agent 的多语言搜索和证据核验，不是给人看的摘要页。DeepSeek Harness 也能装
- [**dsh-files**](https://github.com/taxueseek/dsh-files) — DeepSeek Harness 里传文件、读 PDF / Word / Excel
- [**session-digger**](https://github.com/taxueseek/session-digger) — 把 Claude、Grok、Kimi、Codex 这些环境的会话变成可检索的记录

## 把问题做成 Skill

决策、写作、投资，把反复要做的判断和表达，做成能复用的 Skill。

- [**plainspoken-writing**](https://github.com/taxueseek/plainspoken-writing) — 白描写作，专业消除 AI 味：先标出哪里像机器写的，要不要改你自己说
- [**taxue-invest**](https://github.com/taxueseek/taxue-invest) — 投资分析 skill 系列：11 个方法论技能 + 17 个数据源，覆盖个股、基金、资产配置、风险管理
- [**taxueskills**](https://github.com/taxueseek/taxueskills) — 人生决策系统，把模糊的问题收成能动手的一步
- [**ime-lexicon**](https://github.com/taxueseek/ime-lexicon) — 豆包 / 微信输入法个人词库工具：识别、导出、备份、纠错优化，搜索生成行业词库

## 作品

下面分享几张作品。「道」和熊猫「晚秋」出自 [taxue-creative-style](https://github.com/taxueseek/taxue-creative-style)，节气「立春」出自 [taxue-solar-polaroid](https://github.com/taxueseek/taxue-solar-polaroid)，把一句话或一张照片做成印刷质感海报封面的工具是 [taxue-halftone](https://github.com/taxueseek/taxue-halftone)。点图可以进对应仓库。

<p align="center">
  <a href="https://github.com/taxueseek/taxue-creative-style"><img src="assets/readme/proof-calligraphy.jpg" width="32%" alt="3D 书法「道」"></a>
  <a href="https://github.com/taxueseek/taxue-creative-style"><img src="assets/readme/proof-autumn.jpg" width="32%" alt="治愈插画「晚秋」"></a>
  <a href="https://github.com/taxueseek/taxue-solar-polaroid"><img src="assets/readme/proof-lichun.jpg" width="32%" alt="节气拍立得「立春」"></a>
</p>

## DeepSeek Harness 插件

我的 DeepSeek Harness 插件矩阵，装上就能用。主打 argo，其余各管一摊。

### [argo](https://github.com/taxueseek/argo) · 给 Agent 的搜索基础设施

- 200+ 引擎自动选路：中文、英文、日韩、学术、行情、购物、代码，按领域和语言分诊，不一律扫网页
- 交付的是证据，不是链接清单：候选结果带可信度分解，Agent 能直接 fetch 复核，不撑爆上下文
- 免费引擎优先，Key 全可选；也能当 MCP 服务接进 Claude Code / Cursor

### 其他插件

| 插件 | 一句话 |
|------|--------|
| [dsh-models](https://github.com/taxueseek/dsh-models) | 模型选择 + 子代理路由 + 推理层级，三分区触发，搜索优先弹窗 |
| [dsh-files](https://github.com/taxueseek/dsh-files) | 传文件、读 PDF / Word / Excel，会话之间互相隔离 |
| [dsh-snippets](https://github.com/taxueseek/dsh-snippets) | 常用命令、网址、提示词存成片段，一条调用找回，零依赖 |
| [dsh-healthcheck](https://github.com/taxueseek/dsh-healthcheck) | 只读体检：磁盘、内存、延迟、插件是否落后，带历史基线 |
| [dsh-plugin-guard](https://github.com/taxueseek/dsh-plugin-guard) | 装前静态审计、装后哈希校验，从不执行目标插件 |
| [taxue-dsh-artisan](https://github.com/taxueseek/taxue-dsh-artisan) | 提示词反推与优化，多供应商生图，支持后台异步出图 |
| [plainspoken-writing-dsh](https://github.com/taxueseek/plainspoken-writing-dsh) | 白描写作 DSH 版：AI 味诊断、机械预清理与改写校验，默认只诊断不改 |

配套 skill：[plugin-fast-adapt](https://github.com/taxueseek/plugin-fast-adapt) — DSH 版本升级后自动适配插件破坏性变更，兼插件脚手架与宿主启动诊断；Claude Code / Agent Skills 也能装。

## 找到我

- X：[@TaXue2025](https://x.com/TaXue2025)
- 某个 Skill 不好用，或想一起做：到对应仓库开 Issue

---

<a id="english"></a>

I'm working on three things.

## For Agents

Search, sessions, and a terminal — built for agents to use directly.

- [**argo**](https://github.com/taxueseek/argo) — multilingual search and evidence checks for agents, not a summary page for humans. Also a DeepSeek Harness plugin
- [**dsh-files**](https://github.com/taxueseek/dsh-files) — send files in DeepSeek Harness; read PDF / Word / Excel
- [**session-digger**](https://github.com/taxueseek/session-digger) — turns Claude, Grok, Kimi, and Codex sessions into searchable records

## Turning problems into Skills

Decisions, writing, investing — recurring judgment, packed as reusable Skills.

- [**plainspoken-writing**](https://github.com/taxueseek/plainspoken-writing) — plainspoken writing that strips the AI flavor: it flags the machine-written parts; you decide whether to change them
- [**taxue-invest**](https://github.com/taxueseek/taxue-invest) — investment analysis skill series: 11 methodology skills + 17 data sources, covering stocks, funds, asset allocation, risk management
- [**taxueskills**](https://github.com/taxueseek/taxueskills) — a life-decision system that turns a fuzzy problem into a next step you can take
- [**ime-lexicon**](https://github.com/taxueseek/ime-lexicon) — Doubao/WeType IME lexicon toolkit: recognize, export, backup, correct, and generate industry lexicons

## Work

A few pieces below. 「道」 and the panda 「晚秋」 are from [taxue-creative-style](https://github.com/taxueseek/taxue-creative-style); the solar term 「立春」 is from [taxue-solar-polaroid](https://github.com/taxueseek/taxue-solar-polaroid); [taxue-halftone](https://github.com/taxueseek/taxue-halftone) turns a sentence or a photo into a print-textured poster cover. Click an image to open the repo.

<p align="center">
  <a href="https://github.com/taxueseek/taxue-creative-style"><img src="assets/readme/proof-calligraphy.jpg" width="32%" alt="3D calligraphy 「道」"></a>
  <a href="https://github.com/taxueseek/taxue-creative-style"><img src="assets/readme/proof-autumn.jpg" width="32%" alt="Healing illustration 「晚秋」"></a>
  <a href="https://github.com/taxueseek/taxue-solar-polaroid"><img src="assets/readme/proof-lichun.jpg" width="32%" alt="Solar-term polaroid 「立春」"></a>
</p>

## DeepSeek Harness Plugins

My plugin lineup for DeepSeek Harness — install and go. argo is the flagship; the rest each do one job.

### [argo](https://github.com/taxueseek/argo) · Search infrastructure for agents

- 200+ engines, routed by domain and language: Chinese, English, Japanese/Korean, academic, market data, shopping, code
- Delivers evidence, not link lists: ranked candidates with credibility breakdowns agents can fetch and verify
- Free engines first, keys all optional; also plugs in as an MCP server for Claude Code / Cursor

### Other plugins

| Plugin | One-liner |
|--------|-----------|
| [dsh-models](https://github.com/taxueseek/dsh-models) | Model picker + subagent routing + reasoning effort; three-zone trigger, search-first popup |
| [dsh-files](https://github.com/taxueseek/dsh-files) | Send files, read PDF / Word / Excel; sessions stay isolated |
| [dsh-snippets](https://github.com/taxueseek/dsh-snippets) | Save commands, URLs, and prompts as one-call snippets; zero dependencies |
| [dsh-healthcheck](https://github.com/taxueseek/dsh-healthcheck) | Read-only checkup: disk, memory, latency, stale plugins, with history baselines |
| [dsh-plugin-guard](https://github.com/taxueseek/dsh-plugin-guard) | Static audit before install, hash verification after; never runs the target plugin |
| [taxue-dsh-artisan](https://github.com/taxueseek/taxue-dsh-artisan) | Reverse-engineer and refine prompts; multi-provider image generation with async background rendering |
| [plainspoken-writing-dsh](https://github.com/taxueseek/plainspoken-writing-dsh) | Plainspoken writing for DSH: AI-flavor diagnosis, mechanical pre-cleanup, rewrite verification; diagnose-only by default |

Companion skill: [plugin-fast-adapt](https://github.com/taxueseek/plugin-fast-adapt) — adapts DSH plugins to breaking changes across upgrades, plus plugin scaffolding and host-boot diagnostics; also installable as a Claude Code / Agent Skills skill.

## Find me

- X: [@TaXue2025](https://x.com/TaXue2025)
- If a Skill is broken, or you want to build together: open an Issue on the repo

---

<div align="center">

> 晚来天欲雪，能饮一杯无？

<sub>用得上的话，留个 Star 就好。 / If something here is useful, a star is plenty.</sub>

</div>
