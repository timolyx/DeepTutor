着急时用docker compose -f docker-compose.ghcr.yml up -d --pull never
不着急时用docker compose -f docker-compose.ghcr.yml up -d




<div align="center">

<p align="center"><img src="assets/figs/logo/color-full.png" alt="DeepTutor" width="480"></p>
<h1 align="center">DeepTutor：终身个性化辅导</h1>

<p align="center">
  <a href="https://deeptutor.info" target="_blank"><img alt="文档 — deeptutor.info" src="https://img.shields.io/badge/Docs-deeptutor.info%20%E2%86%97-0A0A0A?style=for-the-badge&labelColor=F5F5F4" height="36"></a>&nbsp;
  <a href="https://deeptutor.info/collaborate/" target="_blank"><img alt="合作 — 与我们共建" src="https://img.shields.io/badge/Collaborate-work%20with%20us%20%E2%86%97-0A0A0A?style=for-the-badge&labelColor=F5F5F4" height="36"></a>
</p>

<p align="center">
<a href="https://www.star-history.com/hkuds/deeptutor"><picture><source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;type=trending&amp;theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;type=trending" /><img alt="GitHub 单日热门仓库" src="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;type=trending" height="55" /></picture></a>&#32;<a href="https://trendshift.io/repositories/17099"><img src="https://trendshift.io/api/badge/trendshift/repositories/17099/daily" alt="HKUDS/DeepTutor | Trendshift" width="250" height="55"></a>&#32;<a href="https://www.star-history.com/hkuds/deeptutor"><picture><source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&amp;theme=dark"><source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor"><img alt="Star 历史排名" src="https://api.star-history.com/badge?repo=HKUDS/DeepTutor" width="185" height="55"></picture></a>
</p>

<p align="center">
  <a href="README.md"><img alt="简体中文" height="40" src="https://img.shields.io/badge/简体中文-BCDCF7"></a>&nbsp;
  <a href="https://github.com/HKUDS/DeepTutor/blob/main/README.md"><img alt="English" height="40" src="https://img.shields.io/badge/English-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_TW.md"><img alt="繁體中文" height="40" src="https://img.shields.io/badge/繁體中文-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_JA.md"><img alt="日本語" height="40" src="https://img.shields.io/badge/日本語-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_ES.md"><img alt="Español" height="40" src="https://img.shields.io/badge/Español-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_FR.md"><img alt="Français" height="40" src="https://img.shields.io/badge/Français-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_AR.md"><img alt="Arabic" height="40" src="https://img.shields.io/badge/Arabic-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_RU.md"><img alt="Русский" height="40" src="https://img.shields.io/badge/Русский-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_HI.md"><img alt="Hindi" height="40" src="https://img.shields.io/badge/Hindi-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_PT.md"><img alt="Português" height="40" src="https://img.shields.io/badge/Português-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_TH.md"><img alt="Thai" height="40" src="https://img.shields.io/badge/Thai-CDCFD4"></a>&nbsp;
  <a href="assets/README/README_PL.md"><img alt="Polski" height="40" src="https://img.shields.io/badge/Polski-CDCFD4"></a>
</p>

[![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/downloads/)
[![Next.js 16](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=next.js&logoColor=white)](https://nextjs.org/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=flat-square)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/HKUDS/DeepTutor?style=flat-square&color=brightgreen)](https://github.com/HKUDS/DeepTutor/releases)
[![arXiv](https://img.shields.io/badge/arXiv-2604.26962-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2604.26962)

[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/eRsjPgMU4t)
[![Feishu](https://img.shields.io/badge/Feishu-Group-00D4AA?style=flat-square&logo=feishu&logoColor=white)](./Communication.md)
[![WeChat](https://img.shields.io/badge/WeChat-Group-07C160?style=flat-square&logo=wechat&logoColor=white)](https://github.com/HKUDS/DeepTutor/issues/78)

[核心特性](#-核心特性) · [快速上手](#-快速上手) · [探索](#-探索-deeptutor) · [CLI](#%EF%B8%8F-deeptutor-cli--面向智能体的接口) · [生态](#-生态--eduhub-与技能社区) · [社区](#-社区)

</div>

---

> 🤝 **欢迎任何形式的贡献！** 在 [`Roadmap`](https://github.com/HKUDS/DeepTutor/issues/498) 为路线图条目投票或提出新条目，并参阅我们的[贡献指南](CONTRIBUTING.md)，了解分支策略、编码规范与参与方式。

### 📦 版本发布

> **[2026.10.28]** [v1.7.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.7.0) — 模块化安装、焕新的学习工作区、带 Dito 的块式笔记本、带旁白的视频课程、可续传的嵌入检查点，以及更可靠的辅导体验。

<details>
<summary><b>历史版本（一周以前）</b></summary>

> **[2026.10.19]** [v1.6.15](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.15) — 可复核的学习路径变更、分组测评、有边界的辅导记忆、可靠的会话恢复、更稳健的解析、检索对比，以及 Gemini 原生语音。

> **[2026.10.8]** [v1.6.14](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.14) — 原始出处可视化练习、可恢复的索引、统一的视频阅读、科研工具、受管插件、学习日志，以及提供方配置改进。

> **[2026.10.4]** [v1.6.13](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.13) — 阅读与听力改进、题库练习、韧性文档解析、可配置语音、工作区可见附件、波兰语界面及新增提供方。

> **[2026.9.27]** [v1.6.12](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.12) — 工作区知识库迁移、Kiwix 归档、来源图注、任务看板、德语界面与会话恢复。

> **[2026.9.24]** [v1.6.11](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.11) — 法语与乌克兰语界面、带会话内选择操作的阅读文件夹、送入视觉模型的图注、分页式 Office 预览，以及自同步知识库。

> **[2026.9.22]** [v1.6.10](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.10) — 原生 LightRAG 角色模型、记录并强制索引构建方式的已发布索引、随解析引擎而变的 PDF 附件、可见的截断提示，以及不过滤的提供方选择。

> **[2026.9.21]** [v1.6.9](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.9) — 基于文件夹的学习工作区、每日练习、重构的设置页、更清晰的流式会话、持久化用量统计，以及可恢复归档与显式永久删除。

> **[2026.9.14]** [v1.6.8](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.8) — 已删除会话的回收站、全量会话历史检索、可越过知识库范围的搜索工具，以及一批针对静默失败的修复。

> **[2026.9.11]** [v1.6.7](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.7) — 修复版：整章为空的书籍、产出为空的测验、混进正文的模型草稿、被原样打印的公式，以及无法提交的答题卡。

> **[2026.9.8]** [v1.6.6](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.6) — 修复版：无法提交的答案、说谎的复制按钮、伙伴可连接的知识库、Docker 内的 Codex 登录，以及轻了 100 KB 的首页路由。

> **[2026.9.6]** [v1.6.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.5) — 可指向任意文件夹的内容工作区、覆盖所有语言的单一 `exec` 工具、对工具设限的精通路径模式，以及会评估就绪度的设置页。

> **[2026.9.3]** [v1.6.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.4) — 更快的隔离运行时、可控的书籍生成、来源完备的精通路径与会话交接、持久化阅读、统一活动界面、可恢复会话，以及显式的逐模型 API 能力。

> **[2026.9.2]** [v1.6.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.3) — 破坏性前后端重构、严格规范路由与可恢复流，以及学员/监护人账户、有据可依的阅读、WeKnora、更广的解析支持、Python 3.14 与 DashScope 媒体能力。

> **[2026.8.31]** [v1.6.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.2) — 沉浸式 YouTube 学习、插件驱动的可视化目录、三个新的智能体外壳、更安全的阅读引用、多格式 MinerU、实时伙伴渠道状态，以及引导式更新。

> **[2026.8.30]** [v1.6.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.1) — 一个厂商密钥可关联其提供的全部服务、用于后台工作的任务模型、可搜索导航的设置页、可自行排列的侧边栏，以及第一方 **LightRAG**。

> **[2026.8.27]** [v1.6.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.6.0) — 忠实的 EPUB 阅读与批注、带小导师与提问的课程、有边界的网页来源同步、学习状态私有的共享书籍，以及 Serply/原生搜索。

> **[2026.8.25]** [v1.5.17](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.17) — 每位成员拥有私密会话与可关联聊天账户的伙伴、作为知识来源的 GitHub 仓库、**Antigravity CLI**、浏览器微信扫码登录，以及 `deeptutor doctor`。

> **[2026.8.22]** [v1.5.16](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.16) — 可连接的 **MarginNote 4** 词库及其插件写入、可再次翻页的书籍页面，以及不再在网关后面出错的工具调用 ID、嵌入与温度上限。

> **[2026.8.20]** [v1.5.15](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.15) — 可自托管的 **PageIndex OSS** 与推理式检索、终于能归档的题库、第三方工具/能力插件，以及 **Apache Tika** 解析。

> **[2026.8.19]** [v1.5.14](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.14) — **沉浸式阅读**：文档在会话旁打开，逐页引用；DeepTutor 可从对话中自行完成配置；可浏览与写入的 IMA 词库；笔记本控制台。

> **[2026.8.17]** [v1.5.13](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.13) — 书籍在编译过程中即可流式阅读、跟踪进度并导出 Markdown；确认目录前先给出成本估算；首页起始建议取自记忆。

> **[2026.8.13]** [v1.5.12](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.12) — 重建联网搜索并新增六个提供方（**Doubao**、**Bocha**、**Zhipu**、**Firecrawl**、**Qianfan**、**Aliyun IQS**）、**LiteParse** 解析引擎、凭据变更后自动重连的 MCP 服务器，以及 **CodeBuddy** 与 **OrcaRouter**。

> **[2026.8.10]** [v1.5.11](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.11) — DSML 工具调用前后的正文不再消失、被截断的回复会继续而非中断、设置页显示实时内存占用、LightRAG 索引移出事件循环。

> **[2026.8.7]** [v1.5.10](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.10) — 每个账户登录各自的 **Codex**、模型输出语言成为独立设置、空工具调用被拒绝而非重试、上传不再阻塞事件循环。

> **[2026.8.4]** [v1.5.9](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.9) — 原生端点上的 Gemini **Embedding 2**、逐模型**推理强度**控制、**Novita AI** 网关、面向查询的检索角色，以及完整保留 `data/` 的 Compose 部署。

> **[2026.8.2]** [v1.5.8](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.8) — 内存治理：开发服务器有了真正的堆上限、源码安装改用生产构建、LLM 客户端与索引缓存设界，以及针对偶发 500 的保活修复。

> **[2026.7.31]** [v1.5.7](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.7) — 按账户隔离的 **MCP 服务**库、辅导时可运行的 101 个 **CLI 应用**、移出沙箱可及范围的凭据，以及移动端布局。

> **[2026.7.29]** [v1.5.6](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.6) — 远程 **Codex** 登录可在 SSH 隧道后完成、生成文件在活动记录中有独立卡片、非中文语言不再回退成中文、书籍创建不再超时。

> **[2026.7.26]** [v1.5.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.5) — 用 ChatGPT 套餐通过 **OpenAI Codex** OAuth 登录、**Eden AI** 提供方、会报告自身内容的知识库、可追溯的 `rag` 引用，以及无需绕路的 GraphRAG 索引。

> **[2026.7.24]** [v1.5.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.4) — 维护性清理：回答后「仍在生成」的卡顿消失、IM 伙伴忠实渲染 Markdown 表格、LLM JSON 解析更稳，另有测验、创建知识库表单与数学动画修复。

> **[2026.7.24]** [v1.5.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.3) — 可换主题的代码块、我的智能体新增四个编码 CLI（Gemini、Kimi、opencode、MiMo）、Atlas Cloud LLM 提供方，以及会话、记忆、嵌入与解析的大范围可靠性整治。

> **[2026.7.19]** [v1.5.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.2) — 可配置的会话附件上限、通过智能体式工具调用跨文档推理的 PageIndex 检索、更广的 Anthropic/OpenAI 模型支持，以及更稳定的书籍、知识库与会话界面。

> **[2026.7.9]** [v1.5.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.1) — 可从知识库中移除单个解析失败的文档——即便它卡在 **error** 状态——无需删除并重建整个知识库。

> **[2026.7.4]** [v1.5.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.5.0) — LlamaIndex 摄取现在遵循你的**文档解析**引擎并支持多模态图像抽取、伙伴与 Soul 的 ID 对非拉丁名称保持 URL 安全，可选的 RAG 附属包在 Python 3.14+ 上也能顺利安装。

> **[2026.6.30]** [v1.4.15](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.15) — 为伙伴新增原生 **Mattermost** 渠道，并修复引导式学习选择题判分与零重叠分块设置不被遵循的问题。

> **[2026.6.29]** [v1.4.14](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.14) — 一键点击已指派的伙伴即可对话、深度研究会标记不完整报告、LightRAG 无需 MinerU 也能索引、FAISS 支持非 ASCII 路径，PocketBase 会话按用户隔离。

> **[2026.6.27]** [v1.4.13](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.13) — 伙伴支持非拉丁名称并可指派给用户、登录后 Logo 正常渲染（#599）、超小知识库也能稳定检索，容器可在 rootless Podman 下干净启动。

> **[2026.6.24]** [v1.4.12](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.12) — 新增 **LightRAG Server** 检索引擎、轻量级 **PyMuPDF4LLM** 解析引擎，以及让大知识库检索显著加速的 FAISS 向量后端。

> **[2026.6.23]** [v1.4.11](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.11) — 每个云端 OpenAI 兼容提供方均支持原生工具调用、重新设计的管理员用户页、测验选项中的 LaTeX、诚实的会话加载指示器，以及可配置的容器宿主绑定。

> **[2026.6.21]** [v1.4.10](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.10) — 带头像的自助**个人资料**页、单端口请求时代理的无 root 容器指南，以及对非管理员用户默认拒绝的 MCP 工具策略。

> **[2026.6.19]** [v1.4.9](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.9) — 设置页打磨：搜索只显示提供方需要的字段、连接档案可重命名并按提供方自动命名、评分后的精通路径题目会进入题库。

> **[2026.6.18]** [v1.4.8](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.8) — 在**我的智能体**下接入你自己的**伙伴**并在会话中实时请教——它们以自己的角色设定、词库与技能作答，各自拥有私密记忆。

> **[2026.6.18]** [v1.4.7](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.7) — 连接本地 **Claude Code / Codex** 并在回合中途实时请教、**我的智能体**升级为顶层 `/agents`，伙伴会话支持分支/恢复/删除并保留可回放的轨迹。

> **[2026.6.17]** [v1.4.6](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.6) — 四类界面整合：可导入**我的智能体**并含顶层记忆的 Space 学习看板、含 GraphRAG / PageIndex / LightRAG / 关联知识库 / Obsidian 的**知识中心**、更开放的设置页，以及按模型的能力开关。

> **[2026.6.14]** [v1.4.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.5) — 引导式学习基于会话智能体循环重建，带严格的按类型精通门槛与 `/learning` 看板、新的循环插件框架，以及伙伴会话的 Markdown 导出/保存到笔记本。

> **[2026.6.13]** [v1.4.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.4) — 通过 `deeptutor skill install` 从 [ClawHub](https://clawhub.ai/) 安装社区技能（经受安全闸门），并为知识库文件提供浏览器内 DOCX/XLSX 预览。

> **[2026.6.12]** [v1.4.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.3) — TutorBot 演进为生产级 IM 管道上的**伙伴**（15 个渠道、实时流式）、会话迁移到单一智能体循环、真正的按用户隔离，以及重建的可视化。

> **[2026.5.28]** [v1.4.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.2) — 稳定性与打磨：可视化与会话中解除 Gemini 2.5+ 限制、修复鉴权路由（#485）、平滑流式会话体验、最近会话侧边栏，以及 Lemonade 本地提供方支持。

> **[2026.5.27]** [v1.4.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.1) — 安全与稳定：TutorBot 工具沙箱加固、按用户资源隔离、多模态图像回退、面向 TutorBot 的 HTTP/SSE API，以及 v1.4.0 会话回归修复。

> **[2026.5.22]** [v1.4.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.0) — v1.4 正式版：自动模式、三层记忆、智能体式深度研究/解题/提问、LlamaIndex RAG 重构、可视化与动画合并，以及可重启的回合运行时。

> **[2026.5.21]** [v1.4.0-beta](https://github.com/HKUDS/DeepTutor/releases/tag/v1.4.0-beta) — 三层记忆工作台（L1/L2/L3）、所有会话能力重建于统一智能体引擎、仅 LlamaIndex 的 RAG，以及统一的设置 + 能力界面。

> **[2026.5.10]** [v1.3.10](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.10) — 远程 Docker CORS 恢复、SDK 提供方全面支持 `DISABLE_SSL_VERIFY`、更安全的代码块引用，以及可选的 Matrix E2EE 附加组件。

> **[2026.5.9]** [v1.3.9](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.9) — TutorBot 支持 Zulip 与 NVIDIA NIM、更安全的思考模型路由、`deeptutor start`、侧边栏工具提示，以及会话存储一致性。

> **[2026.5.8]** [v1.3.8](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.8) — 可选多用户部署，含隔离的用户工作区、管理员授权、鉴权路由与受限的运行时访问。

> **[2026.5.4]** [v1.3.7](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.7) — 思考模型/提供方修复、可见的知识索引历史，以及更安全的协作者清空/模板编辑。

> **[2026.5.3]** [v1.3.6](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.6) — 会话与 TutorBot 基于模型目录选择模型、更安全的 RAG 重建索引、OpenAI Responses 令牌上限修复，以及技能编辑器校验。

> **[2026.5.2]** [v1.3.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.5) — 更顺畅的本地启动设置、更安全的 RAG 查询、更干净的本地嵌入鉴权，以及设置页深色模式打磨。

> **[2026.5.1]** [v1.3.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.4) — 书籍页面会话持久化与重建流程、会话到书籍的引用、更强的语言/推理处理、RAG 文档抽取加固。

> **[2026.4.30]** [v1.3.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.3) — NVIDIA NIM 与 Gemini 嵌入支持、会话历史/技能/记忆的统一 Space 上下文、会话快照、RAG 重建索引韧性。

> **[2026.4.29]** [v1.3.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.2) — 透明的嵌入端点 URL、针对无效持久化向量的 RAG 重建韧性、思考模型输出的记忆清理、深度解题运行时修复。

> **[2026.4.28]** [v1.3.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.1) — 稳定性：更安全的 RAG 路由与嵌入校验、Docker 持久化、对输入法安全的输入框、Windows/GBK 健壮性。

> **[2026.4.27]** [v1.3.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.3.0) — 版本化知识库索引与重建流程、重建的知识工作区、带新适配器的嵌入自动发现、Space 中心。

> **[2026.4.25]** [v1.2.5](https://github.com/HKUDS/DeepTutor/releases/tag/v1.2.5) — 持久化会话附件与文件预览抽屉、感知附件的各类能力流水线、TutorBot Markdown 导出。

> **[2026.4.25]** [v1.2.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.2.4) — 文本/代码/SVG 附件、一键安装导览、Markdown 会话导出、紧凑的知识库管理界面。

> **[2026.4.24]** [v1.2.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.2.3) — 文档附件（PDF/DOCX/XLSX/PPTX）、推理思考块展示、Soul 模板编辑器、协作者保存到笔记本。

> **[2026.4.22]** [v1.2.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.2.2) — 用户自建技能系统、会话输入性能重构、TutorBot 自动启动、书库界面、可视化全屏。

> **[2026.4.21]** [v1.2.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.2.1) — 按阶段的令牌上限、所有入口均支持重新生成、RAG 与 Gemma 兼容性修复。

> **[2026.4.20]** [v1.2.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.2.0) — 书籍引擎「活书」编译器、多文档协作者、交互式 HTML 可视化、题库 @ 提及。

> **[2026.4.18]** [v1.1.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.1.2) — 模式驱动的渠道标签页、RAG 单流水线整合、外置的会话提示词。

> **[2026.4.17]** [v1.1.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.1.1) — 通用的「立即回答」、协作者滚动同步、统一设置面板、流式停止按钮。

> **[2026.4.15]** [v1.1.0](https://github.com/HKUDS/DeepTutor/releases/tag/v1.1.0) — LaTeX 块级公式重构、LLM 诊断探针、Docker 与本地 LLM 指南。

> **[2026.4.14]** [v1.1.0-beta](https://github.com/HKUDS/DeepTutor/releases/tag/v1.1.0-beta) — 可收藏的会话、Snow 主题、WebSocket 心跳与自动重连、嵌入注册表重构。

> **[2026.4.13]** [v1.0.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.0.3) — 带书签与分类的题目笔记本、可视化中的 Mermaid、嵌入不匹配检测、Qwen/vLLM 兼容、LM Studio 与 llama.cpp 支持，以及 Glass 主题。

> **[2026.4.11]** [v1.0.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.0.2) — 搜索整合与 SearXNG 回退、提供方切换修复，以及前端资源泄漏修复。

> **[2026.4.10]** [v1.0.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.0.1) — 可视化能力（Chart.js/SVG）、测验去重，以及 o4-mini 模型支持。

> **[2026.4.10]** [v1.0.0-beta.4](https://github.com/HKUDS/DeepTutor/releases/tag/v1.0.0-beta.4) — 带限流重试的嵌入进度跟踪、跨平台依赖修复，以及 MIME 校验修复。

> **[2026.4.8]** [v1.0.0-beta.3](https://github.com/HKUDS/DeepTutor/releases/tag/v1.0.0-beta.3) — 原生 OpenAI/Anthropic SDK（移除 litellm）、Windows 数学动画支持、稳健的 JSON 解析，以及完整中文本地化。

> **[2026.4.7]** [v1.0.0-beta.2](https://github.com/HKUDS/DeepTutor/releases/tag/v1.0.0-beta.2) — 设置热重载、MinerU 嵌套输出、WebSocket 修复，以及 Python 3.11+ 最低版本要求。

> **[2026.4.4]** [v1.0.0-beta.1](https://github.com/HKUDS/DeepTutor/releases/tag/v1.0.0-beta.1) — 智能体原生架构重写（约 20 万行）：工具 + 能力插件模型、CLI 与 SDK、TutorBot、协作者、引导式学习与持久化记忆。

> **[2026.1.23]** [v0.6.0](https://github.com/HKUDS/DeepTutor/releases/tag/v0.6.0) — 会话持久化、增量文档上传、灵活的 RAG 流水线导入，以及完整中文本地化。

> **[2026.1.18]** [v0.5.2](https://github.com/HKUDS/DeepTutor/releases/tag/v0.5.2) — RAG-Anything 支持 Docling、日志系统优化，以及缺陷修复。

> **[2026.1.15]** [v0.5.0](https://github.com/HKUDS/DeepTutor/releases/tag/v0.5.0) — 统一服务配置、按知识库选择 RAG 流水线、题目生成重构，以及侧边栏自定义。

> **[2026.1.9]** [v0.4.0](https://github.com/HKUDS/DeepTutor/releases/tag/v0.4.0) — 多提供方 LLM 与嵌入支持、全新首页、RAG 模块解耦，以及环境变量重构。

> **[2026.1.5]** [v0.3.0](https://github.com/HKUDS/DeepTutor/releases/tag/v0.3.0) — 统一的 PromptManager 架构、GitHub Actions CI/CD，以及 GHCR 上的预构建镜像。

> **[2026.1.2]** [v0.2.0](https://github.com/HKUDS/DeepTutor/releases/tag/v0.2.0) — Docker 部署、升级到 Next.js 16 与 React 19、WebSocket 安全加固，以及关键漏洞修复。

</details>

> ✨ **v1.7.0 已发布。** `pip install -U "deeptutor[full]"` 安装完整的 Web 应用与 CLI；仅安装 `deeptutor` 则只含核心。旧版 CLI 安装的升级步骤见下文。

### 📰 动态

- **2026-09-20** 🎉 9 个月收获 4 万星！我们会继续拓展 DeepTutor 的学习生态。
- **2026-05-22** 🌐 官方文档站上线 [**deeptutor.info**](https://deeptutor.info/) — 指南、参考与能力导览尽在一处。
- **2026-04-19** 🎉 111 天收获 2 万星！感谢大家支持真正个性化、智能化的辅导。
- **2026-04-10** 📄 我们的论文已在 arXiv 发布 — 阅读[预印本](https://arxiv.org/abs/2604.26962)了解 DeepTutor 背后的设计与思路。
- **2026-02-06** 🚀 仅 39 天收获 1 万星！衷心感谢我们出色的社区。
- **2026-01-01** 🎊 新年快乐！加入我们的 [Discord](https://discord.gg/eRsjPgMU4t)、[微信](https://github.com/HKUDS/DeepTutor/issues/78) 或 [Discussions](https://github.com/HKUDS/DeepTutor/discussions) — 一起塑造 DeepTutor。
- **2025-12-29** 🎓 DeepTutor 正式发布！

## ✨ 核心特性

DeepTutor 是一个智能体原生的学习工作区，把辅导、解题、出题、研究、可视化与精通练习连接在同一套可扩展系统里。

- **所有模式共用一个运行时** — 对话、提问、测验、研究、可视化、解题、精通路径、沉浸式阅读与音频概览共用同一套能力运行时与会话上下文，同时各自保留专用循环与流水线。
- **任务看板** — 在「待办」「进行中」「已完成」之间跟踪学习任务，支持备注、拖拽或键盘可用的移动按钮，以及可恢复的归档。卡片留在当前工作区，并遵循现有的外观与语言设置；无需配置模型。
- **连通的学习上下文** — 知识库、书籍、学习笔记本页面、收藏、题库、角色设定与记忆可在支持它们的工作流之间复用，并受账户授权与学习策略约束。
- **沉浸式视频学习** — 把 YouTube 或 Bilibili 链接加入阅读，即可原生播放、检索字幕、获得带时间戳依据的辅导、保存笔记与续播进度；YouTube 字幕与浏览可使用管理员配置的 Invidious 实例。
- **子智能体与伙伴** — 在会话中实时请教本机智能体外壳（Claude Code、Codex、Grok CLI、Antigravity、Kimi、opencode、MiMo、Hermes、OpenClaw 或 DeepSeek）或伙伴，导入历史会话，并让常驻 IM 陪伴体共用同一套大脑。
- **多引擎知识** — 版本化 RAG 库，覆盖 LlamaIndex、PageIndex、GraphRAG、LightRAG、远程 LightRAG Server、自托管 WeKnora 知识库、腾讯 IMA 或 MarginNote 4 词库、已连接的 Kiwix ZIM 归档，或关联的 Obsidian 仓库，并支持可插拔的文档解析。独立的抽取、查询与视觉设置、仅默认创建与确认后重建，见[原生 LightRAG 角色模型](deeptutor/services/rag/pipelines/lightrag/README.md)。
- **可扩展的工具与技能** — 内置工具、MCP 服务器、CLI 应用、图像/视频/语音生成模型，以及可从 EduHub 安装的社区技能。
- **可检视的记忆** — L1 痕迹、L2 各界面摘要与 L3 综合，让个性化既可见又可编辑；记忆图谱把 L2 事实连接到 L1 证据，把 L3 综合连接到贡献它的界面。

---

## 🚀 快速上手

### 让智能体帮你安装 DeepTutor

把下面这段提示词粘贴到可执行终端命令的 AI 智能体（例如 Codex 或 Claude Code）中：

```text
帮我从 https://github.com/HKUDS/DeepTutor 安装并配置当前开发版 DeepTutor。
克隆 dev 分支，或检查并复用我现有的代码检出。从
docs-for-dev/README.md 开始，然后阅读 docs-for-dev/AGENT_SETUP.md 与 SKILL.md。
按照安装指南准备环境、配置我的模型提供方、验证安装，并启动 Web 应用。
缺少提供方、模型或凭据来源信息时询问我；
不要打印 API 密钥。保留我现有的文件与设置，最后
给出访问地址和你各项检查的结果。
```

[开发者与智能体手册](docs-for-dev/README.md)是安装、架构、扩展开发、测试与排查的文档入口。其中的[智能体安装指南](docs-for-dev/AGENT_SETUP.md)覆盖完整安装流程，包括非交互式 CLI 配置。若想自己安装，从下面几种方式中选一种。

DeepTutor 提供四条安装路径，它们共用同一套运行时家目录布局：私有设置位于启动目录下的 `data/user/settings/`（或你显式指定的 `DEEPTUTOR_HOME` / `deeptutor start --home` 之下）。完整的存储布局、数据库支持与备份注意事项见[本地数据持久化](./docs-for-dev/DATA_STORAGE.md)。若需要完整应用，推荐流程是**选定运行时家目录 → 安装 → `deeptutor init` → `deeptutor start`**。

### 一条命令的 Docker 试用

如果尚未安装 Docker，请先[安装 Docker](https://docs.docker.com/get-docker/)。然后无需配置 Python 或 Node.js 即可试用完整应用：

```bash
docker run --rm --name deeptutor \
  -p 127.0.0.1:3872:3872 \
  -v deeptutor-data:/app/data \
  ghcr.io/hkuds/deeptutor:latest
```

打开 [http://127.0.0.1:3872](http://127.0.0.1:3872)，在**设置 → 提供方**中配置模型提供方，完成后按 `Ctrl+C`。名为 `deeptutor-data` 的数据卷会为下次运行保留设置与本地数据。

### 内容工作区

**内容工作区**与 DeepTutor 的私有运行时家目录相互独立。它是智能体可读取的文件夹，
生成的文件位于 `outputs/<capability>/<session>/<turn>/` 之下。自定义工作区会把会话、
学习资料、进度与缓存在私有的 `.deeptutor/data/` 目录树中隔离，文件工具无法浏览该目录。
设置、凭据与记忆仍保持在账户级别共享。

未做配置时，内容工作区为
`<runtime-home>/data/user/workspace`。通过 PyPI、CLI 与源码安装的本地部署可在
**设置 → 工作区**中选择文件夹；设置默认文件夹的命令如下：

```bash
deeptutor workspace show
deeptutor workspace set /absolute/path/to/my-folder
deeptutor workspace reset
```

各项能力通过内置的工作区工具检视其选定的工作区。模型只会收到诸如 `outputs/...` 的
相对路径；当它使用 `workspace_present` 时，界面会渲染经过鉴权、可直接打开的
快照。同样的相对路径在普通 Markdown 链接或图片中也可使用。稍后修改源文件不会改变
已经呈现过的快照。

学习空间管理资源库。在**设置 → 工作区**中，为每个工作区指派技能、MCP 服务与
知识库，或保留其现有的访问规则。已有工作区在保存选择之前保持原有访问权限。指派
只引用原始资源，不复制凭据或知识索引；工作区专属技能可以覆盖共享版本。参见
[工作区资源指派](docs-for-dev/workspaces.md)。

执行范围在 `outputs/` 之外是只读的。要把生成的文件复制到内容工作区的其他位置，
需要针对该确切来源与目标做一次显式的**允许一次**确认。系统沙箱或 Docker 运行器在
可用时会强制执行该边界；本地受限子进程回退方案在「工作区」设置中标注为**尽力而为**。

<details>
<summary><b>方式一 — 从 PyPI 安装</b> · 完整的本地 Web 应用 + CLI，无需克隆</summary>

**1.7.0 模块化安装：** Web 应用与 CLI 使用 `deeptutor[full]`，仅核心会话使用 `deeptutor`。功能模块必须与核心版本匹配；1.6.15 及更早版本使用旧的包布局。若要在当前 `dev` 上开发，请使用下方的源码说明，或构建[本地 wheel](docs-for-dev/MODULES.md)。需要 **Python 3.11–3.14** 以及 PATH 中的 **Node.js 20+** 运行时（打包好的 Next.js 独立服务器由 `deeptutor start` 拉起）。

```bash
mkdir -p my-deeptutor && cd my-deeptutor
pip install -U "deeptutor[full]"
deeptutor init     # 提示输入端口 + LLM 提供方 + 可选的嵌入/搜索
deeptutor start    # 启动后端与前端；保持终端打开
```

`deeptutor init` 会提示输入后端端口（默认 `8001`）、前端端口（默认 `3872`）、LLM 提供方 / Base URL / API 密钥 / 模型，以及面向知识库 / RAG 的可选嵌入提供方和面向联网搜索的可选搜索提供方。

**升级到 1.7.0：** 停止应用并备份运行时家目录。先执行 `python -m pip install --upgrade "deeptutor[full]==1.7.0"`，再执行 `python -m pip check` 与 `deeptutor module list`。如果安装了旧的 `deeptutor-cli` 包，请先运行 `python -m pip uninstall deeptutor-cli`，再执行升级命令（可选追加 `deeptutor-cli==1.7.0`）。旧 CLI 占用了共享的 Python 文件，与之在同一事务中升级可能删掉新的核心包。卸载该包不会影响运行时家目录中的数据。请保持相同的 `DEEPTUTOR_HOME` 与现有设置。在 1.7.0 中，直接执行 `pip install -U deeptutor` 只会选择核心；要完整应用安装请使用 `[full]`。若使用本地构建的包，请遵循[本地 wheel 升级说明](docs-for-dev/MODULES.md#upgrade-from-1615)。

执行 `deeptutor start` 后，打开终端打印的前端地址——默认是 [http://127.0.0.1:3872](http://127.0.0.1:3872)。在该终端按 `Ctrl+C` 可同时停止前后端。快速试用时可以跳过 `deeptutor init`；应用会以默认端口和空的模型设置启动，之后再到**设置 → 提供方**与**语言模型**中配置。

**浏览器麦克风转写：** OpenAI 兼容的 STT 适配器会把浏览器音频直接转发给提供方，无需本地转码。原生 DashScope 与火山引擎 STT 适配器会把浏览器的 WebM/Opus 转成 16 kHz WAV，并要求 DeepTutor 的 `PATH` 中存在可执行的 `ffmpeg`。规范的 16 kHz 单声道 PCM WAV 会跳过该转码。使用上述任一原生适配器的 Windows PyPI 安装，请先安装 FFmpeg、把其 `bin` 目录加入服务的 `PATH`，然后重启 DeepTutor。转码失败信息会显示在会话输入框下方。

</details>

<details>
<summary><b>方式二 — 从源码安装</b> · 基于代码检出进行开发</summary>

面向基于代码检出的开发。请使用 **Python 3.11–3.14** 与 **Node.js 22 LTS**，以与 CI 和 Docker 保持一致。

```bash
git clone --branch dev https://github.com/HKUDS/DeepTutor.git
cd DeepTutor

# 创建虚拟环境（macOS/Linux）。Windows PowerShell：
#   py -3.11 -m venv .venv ; .\.venv\Scripts\Activate.ps1
python3 -m venv .venv && source .venv/bin/activate
python -m pip install --upgrade pip

# 安装后端 + 前端依赖
python -m pip install -r requirements/full.txt
python -m pip install -e . --no-deps
( cd web && npm ci --legacy-peer-deps )

deeptutor init
deeptutor start --dev
```

`deeptutor start` 会为生产环境构建本地 `web/` 前端并复用构建产物；`--dev` 则以 HMR 方式运行 Next.js。配置布局、端口与 `Ctrl+C` 行为与方式一相同。

<details>
<summary><b>Conda 环境</b>（替代 <code>venv</code>）</summary>

```bash
conda create -n deeptutor python=3.11
conda activate deeptutor
python -m pip install --upgrade pip
```

</details>

<details>
<summary><b>可选安装附件</b> — RAG 引擎 / 开发 / 伙伴 / matrix / 数学动画</summary>

```bash
python scripts/install_extras.py rag-lightrag    # 内置 LightRAG 引擎（指定受支持的 SDK）
python scripts/install_extras.py graphrag        # 微软 GraphRAG 引擎（Python 3.11–3.13）
python scripts/install_extras.py dev             # 测试/静态检查工具
python scripts/install_extras.py partners        # 伙伴 IM 渠道 SDK
python scripts/install_extras.py video-learning  # 阅读/视频学习所需的字幕
python scripts/install_extras.py matrix          # 不含 E2EE/libolm 的 Matrix 渠道
python scripts/install_extras.py matrix-e2e      # Matrix E2EE；需要 libolm
python scripts/install_extras.py math-animator   # Manim 附加组件；需要 LaTeX/ffmpeg/系统库
python scripts/install_extras.py edge-tts        # 可选的免费语音提供方与视频课程旁白
```

**视频课程：** 在会话中选择「视频课程」，或运行 `deeptutor run video_lesson "解释某个概念"`。后端需要 Node.js 22+ 与 npm。首次使用会下载固定版本的 Remotion 包与一个 WebAssembly JavaScript 解释器；不需要 Docker。帧检查在该解释器内运行，不接触宿主文件系统、凭据、网络或进程 API，并受内存与执行时间限制。取消操作会终止构建进程。本地与容器部署使用同一条执行路径，没有非沙箱的回退方案。生成的课程在浏览器中播放；当可选旁白不可用时显示字幕。

</details>

<details>
<summary><b>前端依赖调整与开发服务器排障</b></summary>

**修改前端依赖：** 运行 `npm install --legacy-peer-deps` 刷新 `web/package-lock.json`，然后同时提交 `web/package.json` 与 `web/package-lock.json`。

**开发服务器卡住：** 如果 `deeptutor start --dev` 报告已有前端进程但无响应，结束它打印的 PID。若实际没有 Next.js 进程在运行，说明锁文件已失效——删除后重试：

```bash
rm -f web/.next/dev/lock web/.next/lock
deeptutor start --dev
```

</details>

</details>

<details>
<summary><b>方式三 — Docker</b> · 单个自包含容器</summary>

一个容器承载完整的 Web 应用。镜像发布在 GitHub Container Registry：

- `ghcr.io/hkuds/deeptutor:latest` — 最新稳定版
- `ghcr.io/hkuds/deeptutor:<version>` — 精确版本，去掉开头的 `v`（例如 `:1.6.3`）；预发布版只提供版本标签

> podman / rootless / 只读根文件系统部署以及完整的逐安装指南见 [CONTAINERIZATION.md](./docs-for-dev/CONTAINERIZATION.md)。

```bash
docker run --rm --name deeptutor \
  -p 127.0.0.1:3872:3872 \
  -v deeptutor-data:/app/data \
  ghcr.io/hkuds/deeptutor:latest
```

若要在容器启动时指定宿主机的内容文件夹，请把它挂载到固定的容器路径，并把 DeepTutor 锁定到该路径：

```bash
mkdir -p "$PWD/deeptutor-workspace/outputs"
docker run --rm --name deeptutor \
  -p 127.0.0.1:3872:3872 \
  -v deeptutor-data:/app/data \
  -v "$PWD/deeptutor-workspace:/workspace" \
  -e DEEPTUTOR_WORKSPACE_ROOT=/workspace \
  -e DEEPTUTOR_WORKSPACE_ALLOWED_ROOTS=/workspace \
  ghcr.io/hkuds/deeptutor:latest
```

使用 Compose 时，在执行 `python scripts/docker_compose.py up -d` 之前设置 `DEEPTUTOR_WORKSPACE_HOST=/absolute/host/folder`。省略时使用 `./data/user/workspace`。Docker 路径在启动时确定，因此在 Web 设置页中会显示为已锁定。

> **只需发布 `3872`。** 浏览器只与前端源通信；Next.js 中间件（`web/proxy.ts`）会在**容器内部**把 `/api/*` 与 `/ws/*` 转发给 FastAPI 后端。发布 `8001`（`-p 127.0.0.1:8001:8001`）是可选的——仅在用 curl 或脚本直连 API 时有用。

打开 [http://127.0.0.1:3872](http://127.0.0.1:3872)。容器首次启动时会创建 `/app/data/user/settings/*.json`；请在 Web 设置页中配置模型提供方。配置、API 密钥、日志、默认内容工作区、记忆与知识库都会持久化在 `deeptutor-data` 数据卷中。单独挂载的内容工作区则持久化在其宿主机路径。可选附件应放在部署上而不是某个 shell 里：设置 `DEEPTUTOR_EXTRAS`（系统库则用 `DEEPTUTOR_APT_PACKAGES`），由此启动的每个容器都会重新应用它们，而在 `docker exec … pip install` 中的安装会在下一次 `compose down` 时丢失。

- **更换宿主机端口：** 修改每个 `-p host:container` 映射的左侧（例如 `-p 127.0.0.1:8088:3872`）。如果你在 `/app/data/user/settings/system.json` 中改了容器侧端口，请重启并把每个映射的右侧同步改成对应值。
- **后台运行：** 加上 `-d`，随后用 `docker logs -f deeptutor` 跟进日志、`docker stop deeptutor` 停止、复用名称前先 `docker rm deeptutor`。`deeptutor-data` 数据卷会在多次重启之间保留私有运行时数据与默认内容工作区；单独挂载的内容工作区持久化在其宿主机路径。

**远程 Docker / 反向代理：** 浏览器只与前端源（`:3872`）通信；容器内的 Next.js 中间件在服务端把 `/api/*` 与 `/ws/*` 转发给后端。常见的单容器场景完全不需要配置 API 基址——只需把反向代理 / TLS 终结器指向 `:3872`。只有在**分离部署**（后端位于另一个容器/主机）时才需要 API 基址：把 `data/user/settings/system.json` 中的 `next_public_api_base` 设为前端服务器访问后端所用的内网地址（该值在服务端读取，绝不会下发到浏览器）。

```json
{
  "next_public_api_base": "http://backend:8001"
}
```

`next_public_api_base_external`（及其别名 `public_api_base`）作为优先级更低的回退被接受。CORS 使用前端**源**而非 API URL。未启用鉴权时，DeepTutor 默认允许常规的 HTTP/HTTPS 浏览器源。启用鉴权时，请精确添加前端源：

```json
{
  "cors_origins": ["https://deeptutor.example.com"]
}
```

<details>
<summary><b>在宿主机上连接 Ollama / LM Studio / llama.cpp / vLLM / Lemonade</b></summary>

在 Docker 内部，`localhost` 指的是容器自身，而不是你的宿主机。要访问运行在宿主机上的模型服务，请使用宿主网关（推荐）：

```bash
docker run --rm --name deeptutor \
  -p 127.0.0.1:3872:3872 -p 127.0.0.1:8001:8001 \
  --add-host=host.docker.internal:host-gateway \
  -v deeptutor-data:/app/data \
  ghcr.io/hkuds/deeptutor:latest
```

然后在**设置 → 提供方**中，把提供方的 Base URL 指向 `host.docker.internal`：

- Ollama LLM：`http://host.docker.internal:11434/v1`
- Ollama 嵌入：`http://host.docker.internal:11434/api/embed`
- LM Studio：`http://host.docker.internal:1234/v1`
- llama.cpp：`http://host.docker.internal:8080/v1`
- Lemonade：`http://host.docker.internal:13305/api/v1`

Docker Desktop（macOS/Windows）通常无需 `--add-host` 即可解析 `host.docker.internal`。在 Linux 上，该参数是在现代 Docker Engine 中创建此主机名的通用做法。

**Linux 备选方案 — 宿主网络：** 加上 `--network=host` 并去掉 `-p` 参数。容器直接共享宿主网络，因此打开 [http://127.0.0.1:3872](http://127.0.0.1:3872)（或 `system.json` 中的 `frontend_port`）即可，宿主服务也能用常规 localhost URL 访问，如 `http://127.0.0.1:11434/v1`。注意宿主网络会把容器端口直接暴露在宿主机上，可能与现有服务冲突——若要把它们限制在回环地址，请设置 `BACKEND_HOST=127.0.0.1` 与 `FRONTEND_HOST=127.0.0.1`（参见 [CONTAINERIZATION.md](./docs-for-dev/CONTAINERIZATION.md)）。

</details>

</details>

<details>
<summary><b>方式四 — 仅 CLI</b> · 无 Web 界面，基于源码检出</summary>

当你不需要 Web 界面时，可在此代码检出中使用 CLI，并跳过 Node/npm。源码方式暴露全部已检入的模块，需要安装它们的 Python 依赖。若采用 1.7.0 模块化发布做最小安装，请使用核心 `deeptutor` wheel，再按需单独添加功能模块。

```bash
git clone --branch dev https://github.com/HKUDS/DeepTutor.git
cd DeepTutor

# 创建虚拟环境（macOS/Linux）。Windows PowerShell：
#   py -3.11 -m venv .venv-cli ; .\.venv-cli\Scripts\Activate.ps1
python3 -m venv .venv-cli && source .venv-cli/bin/activate
python -m pip install --upgrade pip

python -m pip install -r requirements/full.txt
python -m pip install -e . --no-deps
deeptutor init --cli
deeptutor chat
```

`deeptutor init --cli` 与完整应用共用同一套 `data/user/settings/` 布局，但会跳过前后端端口提示。它仍会提供嵌入与搜索选择器（不需要时选**跳过**），写出关键的运行时文件（`system.json`、`auth.json`、`integrations.json`、`interface.json`、`model_catalog.json`、`main.yaml`、`agents.yaml`），并提示选择生效的 LLM 提供方与模型。

<details>
<summary><b>常用命令</b></summary>

```bash
deeptutor chat                                          # 交互式 REPL
deeptutor chat --capability deep_solve --kb my-kb
deeptutor run chat "解释傅里叶变换"
deeptutor run deep_solve "求解 x^2 = 4" --kb my-kb
deeptutor kb create my-kb --doc textbook.pdf
deeptutor memory show
deeptutor config show
```

</details>

此源码安装包含服务端依赖，但跳过前端配置。请保留代码检出——可编辑安装（editable install）指向它。若之后要加上 Web 界面，安装 Node.js 22 LTS，在 `web/` 中运行 `npm ci --legacy-peer-deps`，然后在项目根目录运行 `deeptutor init` 与 `deeptutor start`。

</details>

<details>
<summary><b>代码执行沙箱（办公技能）</b> · 运行模型生成的代码以产出 docx / pdf / pptx / xlsx</summary>

内置办公技能——**docx / pdf / pptx / xlsx**——的工作方式是让模型写一小段 Python 脚本
（`python-docx`、`reportlab`、`openpyxl` 等），通过单一的 `exec` 工具运行它，并呈现
已保存的工作区文件。只要沙箱后端处于激活状态，这些工具就会被挂载。DeepTutor 按
以下顺序选择已配置的最强后端：

- **Runner 边车：** `DEEPTUTOR_SANDBOX_RUNNER_URL` 把执行路由到 `Dockerfile.runner`
  加固过的、权限最小的服务。
- **Linux bubblewrap：** 可用时由 `bwrap` 隔离进程与文件。
- **受限子进程回退：** 本地与单容器安装在允许时才使用它；在 Docker 下容器本身构成
  另一层边界。

`data/user/settings/system.json` 中的 `sandbox_allow_subprocess` 设置（默认 `true`）
只控制最后一种回退方案。把它设为 `false`（或导出
`DEEPTUTOR_SANDBOX_ALLOW_SUBPROCESS=0`），可在没有 runner 或 `bwrap` 后端时拒绝子进程
执行；它不会禁用那些更强的后端。

</details>

<details>
<summary><b>配置参考</b> — <code>data/user/settings/</code> 下的配置文件（JSON/YAML）</summary>

`data/user/settings/` 下的一切都是纯 JSON/YAML。**设置**页是推荐的编辑入口；工作区注册信息单独存放在 `data/user/.runtime/workspaces.sqlite3`。

| 文件 | 用途 |
|:---|:---|
| `model_catalog.json` | 提供方连接，以及 LLM、任务、嵌入、搜索、TTS、STT、图像与视频档案、凭据和生效选择 |
| `system.json` | 前后端端口、公开 API 基址、CORS、SSL 校验、附件目录与上传/抽取上限 |
| `auth.json` | 可选的多用户鉴权开关、用户名、口令哈希、令牌/Cookie 设置 |
| `integrations.json` | 可选的 PocketBase 与边车集成设置 |
| `interface.json` | 界面与模型输出语言 / 主题 / 侧边栏偏好 |
| `document_parsing.json` | 解析引擎与图像描述模型选择、远程端点及引擎专属选项 |
| `video_learning.json` | YouTube 字幕提供方、Invidious 源与账户访问，以及转写设置 |
| `main.yaml` | 运行时行为默认值与路径注入 |
| `agents.yaml` | 各能力/工具的温度与令牌设置 |

联网搜索的引用默认会被过滤：只放行不含内嵌凭据、不使用异常端口的公开 `http`/`https` URL。部署方可在 `data/user/settings/system.json` 中追加面向教育的域名策略：

```json
{
  "web_search_source_filtering": {
    "enabled": true,
    "blocked_domains": ["spam.example"],
    "trusted_domains": ["edu.cn", "arxiv.org"]
  }
}
```

当 `trusted_domains` 非空时，引用会被限制在这些域名及其子域内；`blocked_domains` 始终优先。

项目根目录的 `.env` **不会**作为应用配置文件被读取。最小模型配置的做法是：在**设置 → 提供方**中保存 Base URL 与 API 密钥，然后在**语言模型**中添加并选择一个 LLM。只有在打算使用知识库 / RAG 功能时才需要添加嵌入档案。

对于 API Route，请在**设置 → 提供方**中选择 **API Route** 并填入 API Route 密钥。预设使用 `https://global.api-route.com/v1`；随后在**语言模型**中用其 API Route 模型 ID 添加模型。密钥与模型的配置方法见 [API Route 快速开始](https://www.api-route.com/docs/quickstart)。

当提供方支持多种选择时，LLM 与任务模型档案会显示 **API 格式**设置。常规路由与回退保持 `Auto`，或选择
`OpenAI Chat Completions`、`OpenAI Responses`、`Anthropic Messages`；强制使用 Responses 时失败即终止。持久化字段是 `api_format`（`auto`、
`openai_chat`、`openai_responses` 或 `anthropic`）；`wire_api` 是由此派生的兼容状态。逐模型的 `Auto` / `Supported` / `Not supported` 覆盖项
涵盖工具调用、图像输入、JSON 输出与推理控制。

</details>

<details>
<summary><b>卸载与清理</b></summary>

DeepTutor 把已安装的代码、私有运行时家目录与可选的内容工作区分开存放。默认情况下，运行时家目录就是你执行
`deeptutor init` / `deeptutor start` 的目录；`--home PATH` 或 `DEEPTUTOR_HOME`
可以覆盖它。私有应用状态是该家目录内的 `data` 目录，因此启动横幅中以 `Workspace:` 开头的那一行
标识了该运行时位置。如果**设置 → 工作区**指向另一个文件夹，请单独备份
或删除那个内容文件夹；卸载 DeepTutor 有意不会清除它。

1. 停止应用。在运行 `deeptutor start` 的终端中按 `Ctrl+C`，或对以 `--detach`
   启动的启动器执行 `deeptutor stop [--home PATH]`；删除数据前先停止所有运行中的伙伴
   与分离的 Docker 容器。
2. 只有在你也想清除全部本地状态时才删除运行时数据。这包括设置与 API 密钥、
   会话历史、会话、记忆、笔记本、书籍、阅读状态、技能、伙伴状态、日志、知识库、
   解析缓存、生成的产物，以及打包的前端运行时缓存。

   先从启动横幅中复制确切的 `Workspace:` 路径，确认其 `data` 子目录就是目标
   DeepTutor 数据目录。若之后可能需要，请先备份，然后把该确切目录移动到
   操作系统的废纸篓/回收站。不要对相对路径或未展开的环境变量执行递归删除
   命令。

3. 删除已安装的包。使用与发行形态匹配的命令：

   ```bash
   python -m pip uninstall deeptutor
   python -m pip uninstall deeptutor-cli
   ```

   如果该虚拟环境只为 DeepTutor 创建，请通过环境管理器移除它。对于源码安装，
   先退出（deactivate）环境，离开源码目录，并在该确切检出内运行 `git status --short`。
   只有在确认其中没有无关或未提交的改动之后，才把检出移动到废纸篓/回收站。

4. 对于 Docker 方式，删除前先核对确切的容器与命名数据卷。删除数据卷会永久
   抹除 Docker 管理的数据：

   ```bash
   docker ps -a --filter name=^/deeptutor$
   docker volume inspect deeptutor-data
   docker rm -f deeptutor
   docker volume rm deeptutor-data
   ```

</details>

## 📖 探索 DeepTutor

从一个针对某学科或项目的**工作区**开始。它的**首页**、**学习**与**资源**承载你的会话、学习活动与资料。**伙伴**与**个性化**随账户跨工作区保留。下面的导览展示这些界面如何衔接，随后是设置与多用户部署。

如果回答丢失了先前的约束、引用了薄弱证据，或与选定材料相矛盾，请先收集 [`REASONING_SAFETY_CHECKLIST.md`](./docs-for-dev/REASONING_SAFETY_CHECKLIST.md) 中的诊断信息，再提交 issue。

<div align="center">
<img src="assets/figs/web-dev/overview.png" alt="DeepTutor 首页与工作区导航" width="900">
</div>


<details>
<summary><b>🏗️ 系统架构</b></summary>

<div align="center">
<img src="assets/figs/system/system-architecture.svg" alt="DeepTutor 系统架构" width="900">
</div>

</details>

<details>
<summary><b>💬 会话 — 你真正在用的智能体循环</b></summary>

会话是默认能力，也是大多数工作的起点。单条线程既能正常对话、调用工具、以选定的知识库为依据、读取附件、生成图像、请教子智能体、写入笔记本记录，也能在多个回合之间延续同一上下文。

<div align="center">
<img src="assets/figs/web-dev/chat.png" alt="DeepTutor 会话工作区" width="900">
</div>

导师会按需调用工具，并可暂停以提出澄清问题。右上角的**自定义页面**用于选择可见模式，以及技能、MCP、伙伴、偏好与语音输入控件。在**起始提示**下，可增删改「解释」「解题」「练习」「规划」「研究」的标题与提示词。保存会应用你的账户偏好；取消放弃编辑，恢复默认则找回原始选项。

<div align="center">
<img src="assets/figs/system/chat-agent-loop.svg" alt="DeepTutor 会话智能体循环" width="900">
</div>

用户可切换的工具是 `brainstorm`、`web_search`、`paper_search`、`zotero_search`、`reason` 与 `geogebra_analysis`——配置了对应的生成模型后还会加上 `imagegen` 与 `videogen`。上下文类工具（如 `rag`、`kb_files`、`knowledge_frontier`、`read_source`、`read_memory`、`write_memory`、`read_skill`、`load_tools`、`exec`、`web_fetch`、`ask_user`、`list_favorites`、`save_favorite`、`write_note`、`search_notes`、`question_bank`、`github`、`consult_subagent`、`workspace_list`、`workspace_read`、`workspace_search`、`workspace_present`、`workspace_export`）会在回合具备相应上下文时自动挂载。

上下文分两类：**粘性会话上下文**（能力、工作区或课程、工具、知识库、角色设定、模型以及阅读/精通状态）跨回合持久保留；**一次性引用**（文件、会话历史、书籍、阅读章节、笔记本、选中的题库条目、已导入的智能体）来自 `+` 菜单，仅对单个回合有效。语音按钮只转写当前这条消息。

使用完整配置时，首页让**会话**、**提问**、**测验**、**可视化**与**视频课程**一键可达；带引用的报告用**研究**，逐步推演用**解题**，都在*更多能力*下。**学习 → 新建学习**（位于「全部学习」之上）会打开独立页面，含书籍、**精通路径**、**沉浸式阅读**与**练习**。其**自定义页面**控件可隐藏或恢复学习方法而不改变既有记录；不可用的模块仍会被排除。阅读把文档、视频与音频汇聚在一起，配有可验证的引用、已保存的笔记、基于原文段落 / 学习指导 / 词汇 / 测验 / 翻译的自然朗读，以及笔记本采集。

</details>

<details>
<summary><b>🤝 伙伴 — 同一套大脑上的常驻陪伴</b></summary>

<div align="center">
<img src="assets/figs/web-dev/partners.png" alt="DeepTutor 伙伴工作区" width="900">
</div>

伙伴是拥有各自灵魂、模型策略、词库、记忆与渠道的常驻陪伴体。它们不是另一套机器人引擎：每一条来自 Web 或 IM 的消息都会变成其私有或绑定内容工作区内的一次普通 `ChatOrchestrator` 回合。伙伴就是「一个有性格、有手机号的会话」。

<div align="center">
<img src="assets/figs/system/partners-architecture.png" alt="DeepTutor 伙伴架构" width="900">
</div>

每个伙伴都有 `SOUL.md`、模型选择、渠道、工具策略与已指派词库。其词库要么把知识库、技能与收藏集复制到 `data/partners/<id>/workspace/`，要么保持链接到某个既有工作区的文件与资源；灵魂、会话与伙伴记忆始终独立。通过鉴权的非管理员用户拥有私密的伙伴会话与关系记忆，同时伙伴以只读方式读取其个人记忆；管理员、群组与未绑定的流量则使用共享的伙伴作用域。

<div align="center">
<img src="assets/figs/web-dev/partners-channels.png" alt="逐伙伴的 IM 渠道配置" width="900">
</div>

渠道层是模式驱动的，可连接飞书、Telegram、Slack、Discord、钉钉、QQ/NapCat、企业微信、WhatsApp、Zulip、Mattermost、Matrix、Mochat 与 Microsoft Teams 等 IM 平台，具体取决于已安装的附件与已配置的凭据。伙伴也可以作为子智能体接入，并在普通会话回合中被请教——见下文**我的智能体**。

为加快配置，伙伴渠道页可直接创建飞书/Lark 应用或企业微信 AI 机器人，或扫码登录个人微信——二维码绘制在浏览器中而非打印到服务端日志。飞书/Lark 会识别账户域名，并把扫码用户保存为初始允许发送方。企业微信会保留已有的允许名单，否则默认允许所有能触达机器人的用户，并显示醒目的开放访问警告；若某提供方的扫码协议发生变化，手动渠道表单仍然可用。

</details>

<details>
<summary><b>🧑‍🚀 我的智能体 — 请教与导入其他智能体</b></summary>

<div align="center">
<img src="assets/figs/web-dev/agents.png" alt="DeepTutor 我的智能体工作区" width="900">
</div>

我的智能体把其他智能体变成 DeepTutor 的上下文，包含两件不同的事。**连接一个实时智能体**——你机器上的 Claude Code、Codex、Grok CLI、Antigravity、Kimi、opencode、MiMo Code、Hermes Agent、OpenClaw 或 DeepSeek Harness，远程 Hermes 网关，或你的某个伙伴——并在会话回合内请教它：DeepTutor 会真正*运行*另一个智能体，并通过 `consult_subagent` 工具把它的工作流式显示到活动面板。用智能体标签选择它及其轮次上限，或用 `@` 过滤同一份已连接智能体列表；该选择会附着在会话上。

**连接 Grok CLI。** 在运行 DeepTutor 后端的机器上安装 xAI 的 Grok CLI，在那里运行 `grok login`，并确认 `grok --help` 列出了
`--output-format streaming-json`。然后打开**我的智能体 → 连接**，选择
**Grok CLI**，并指定工作目录。检测只检查可执行文件的协议支持；它不会验证登录或模型访问权限。该连接器已用 Grok CLI 1.0.3 验证过；同名的无关第三方
`grok` 命令不受支持。

在**设置 → 伙伴与智能体 → Grok CLI**中，把模型与推理强度留空即使用 CLI 默认值，或填入你账户 `grok models` 输出支持的值。系统指令通过 `--rules` 传入。默认权限模式是 `dontAsk`：Grok 使用其既有规则与内置的只读处理，并拒绝需要审批的操作。这是 CLI 的权限策略，不是文件系统沙箱。可在设置中显式选择更宽的模式；高级 CLI 参数仍可通过子智能体设置 API 中的
`backends.grok.extra_args` 使用。

Grok 使用自己的鉴权与会话存储；DeepTutor 不会复制其凭据。后续请教会在同一工作目录中恢复该连接的会话。文本与工具活动实时流式输出；私密思考负载会被省略。跨会话的 Grok 记忆默认关闭。该连接器支持文本提问与 CLI 工具，不支持转发图像或导入历史 Grok 会话。在 Docker 中，需在后端容器内安装并完成 Grok 鉴权；只安装在浏览器所在电脑上的 CLI 无法访问。

<div align="center">
<img src="assets/figs/web-dev/personalization.png" alt="账户个性化：智能体、角色、技能与连接" width="900">
</div>

**导入历史会话**——把你既有的 ChatGPT、Claude Code 与 Codex 历史导入为可检索、可续接的会话。从官方 ChatGPT 数据导出中选择 `conversations.json` 可做安全且幂等的快照导入；Claude 历史可按项目 / 工作目录选择；Codex 历史可按日历日期选择。基于文件夹的智能体保持可刷新，以便所选范围能纳入新会话。在会话回合中通过 `+` → 我的智能体引用其中一条，DeepTutor 会以第三方转写的形式读取它——它始终是*它们*的会话，而不是 DeepTutor 自己的声音。

</details>

<details>
<summary><b>✍️ 学习笔记本 — 页面、来源与 Dito</b></summary>

<div align="center">
<img src="assets/figs/web-dev/co-writer.png" alt="学习笔记本页面" width="900">
</div>

学习笔记本（原协作者）把你自己写的内容组织为当前工作区内的页面、子页面与块。可导入 Word 文档、编排页面树，并把收藏中的原始记录作为证据插入。页面会持续显示保存状态，并可导出为 Markdown 或 Word；交互式内容在 Word 中变为静态内容。

<div align="center">
<img src="assets/figs/web-dev/notebook-detail.png" alt="学习笔记本块编辑器与 Dito" width="900">
</div>

与 **Dito** 讨论某段文字或某个块：请求解释、举例、改写或练习题。对话始终附着在相关页面与行上。可在接受前复核建议的改动，或把答案插入该行下方并继续写作。收藏保留来源记录；笔记本则是你构建自身理解的地方。

</details>

<details>
<summary><b>📖 书籍 — 用你的材料生成「活书」</b></summary>

<div align="center">
<img src="assets/figs/web-dev/books.png" alt="DeepTutor 书库" width="900">
</div>

书籍把选定来源变成可交互的**活书**——不是静态 PDF，而是由带类型的块搭建的阅读环境。书籍可以从知识库、收藏、题库或会话历史出发；创建流程会在生成内容之前先给出章节大纲，让你复核整体形态，而不是接受一次盲目的输出。

<p align="center">
<img src="assets/figs/web-dev/book-quiz.png" alt="书籍测验块" width="31%">
&nbsp;
<img src="assets/figs/web-dev/book-detail.png" alt="书籍大纲与章节" width="31%">
&nbsp;
<img src="assets/figs/web-dev/book-widget.png" alt="书籍交互式组件块" width="31%">
</p>

每一章都会编译成可编辑的带类型块——文本、标注、测验、单词卡、时间线、代码、图注、交互式 HTML、动画、概念图、深挖与用户笔记——并拥有自己的页面会话。可插入、移动、重新生成、改写或切换块类型；选中的段落会进入可复核的学习采集收件箱。即便管理员的书籍被共享为只读或协作编辑，阅读进度、书签、测验记录、采集与页面会话仍对每位读者保持私密；共享删除仍仅限管理员。任何书籍都可导出为 Markdown，长时间编译可暂停并续接，`deeptutor book health` / `refresh-fingerprints` 会标记来源漂移。

</details>

<details>
<summary><b>📚 知识中心 — 多引擎 RAG 库</b></summary>

<div align="center">
<img src="assets/figs/web-dev/knowledge.png" alt="DeepTutor 知识中心" width="900">
</div>

知识库是 RAG 背后的文档集合——它们为会话回合、学习笔记本编辑、书籍生成与伙伴会话提供依据。其独特之处在于**检索引擎可自选**：**LlamaIndex**（默认，向量 + BM25 混合检索，可选 cross-encoder 重排序，支持精确展平或 HNSW FAISS 索引）、**PageIndex**（带页面级引用的推理式检索，可用托管版或自托管 OSS）、**GraphRAG** 与 **LightRAG**（知识图谱检索）、**LightRAG Server**（检索卸载到你通过 HTTP 连接的外部 LightRAG 实例）、**WeKnora**（从你自托管部署中的知识库检索，无需本地索引或文档副本）、**腾讯 IMA**（你在 IMA 中整理的词库——通过其 OpenAPI 检索、浏览并回写）、**MarginNote 4**（你的 MN4 学习数据——文档、摘录、脑图卡片及其间的关联——由该应用插件推送进来，并用专用工具导航）、**Kiwix**（通过 HTTP 提供的可检索 ZIM 归档，无需本地索引），或关联的 **Obsidian** 仓库（导师就地读写）。每个知识库绑定一个引擎。

<div align="center">
<img src="assets/figs/web-dev/knowledge-create.png" alt="创建知识库" width="900">
</div>

要迁移既有的 Obsidian、Hermes 或 Markdown 词库？参见[知识迁移指南](./docs-for-dev/KNOWLEDGE_MIGRATION.md)中「关联仓库」与「索引副本」两条路径。

创建知识库时，你可以**新建**（上传并索引文档）、**关联现有**（就地复用索引），或**连接 Kiwix**（按需检索某个已提供的 ZIM 归档）。创建时选择其存储工作区；已有知识库可在预览后在工作区之间迁移，并保留指派与已保存的引用。知识库还可以跟踪 **GitHub 仓库**（仓库、分支、glob）或**文档站 URL**（限定爬取深度与页数，默认每 24 小时重新同步）；同步会用哈希差分出新增、变更与移除的内容，使被跟踪的文档保持最新而无需重新上传，**关联文件夹**也会在同步时拾取新增或变更的本地文件。重建索引会写入新的扁平 `version-N` 目录并保留既有版本，因此可用索引不会在重建中途被破坏。即使知识库处于 **error** 状态，也可以删除单个文档——丢掉解析失败的文件而无需整体删除重建。文档解析——仅文本、MinerU、Docling、Tika、markitdown、PyMuPDF4LLM 或 LiteParse——以及可选的图像描述模型在**设置 → 知识与文档**中选择，本地模型下载默认关闭。Docling 还可以**远程**模式对接 Docling Serve 服务器（无需本地安装或模型），在该页配置（`mode=remote`、服务器基址与可选 API 密钥），或使用 `DOCLING_MODE` / `DOCLING_API_BASE_URL` / `DOCLING_API_TOKEN` 环境变量。Tika 仅支持远程，指向该页配置的 Apache Tika 服务器。CLI 以 `list/info/create/connect-kiwix/add/search/eval/eval-diff/set-default/delete`、来源增删命令、`list-sources` 与 `sync` 对应同一套生命周期。

内置 LightRAG 引擎通过 `pip install 'deeptutor[rag-lightrag]'` 安装。该附件包含受支持的 LightRAG SDK，但不安装 MinerU。需要结构化解析时，请在文档解析中独立选择 MinerU，并配置其云端模式或安装其当前本地 CLI。MinerU 支持 PDF、常见位图、DOCX、PPTX 与 XLSX；旧版 `magic-pdf` 命令仍仅支持 PDF。仅文本与其他解析引擎不需要 MinerU。

原生 LightRAG 查询与增量索引依赖已发布索引记录的嵌入配置，包括模型、维度与端点标识。若该配置发生变化，请恢复原配置或用当前嵌入重建；未记录嵌入标识的索引需要重建。知识库详情页与索引版本视图会给出恢复指引，同时文件仍可查看与下载。

**给知识库打分。** 有多种引擎可选时，「哪个在这里检索效果最好」是个实证问题——`deeptutor kb eval` 正是为此而生。写一份 QA 集（每行一个 JSON 对象：`query` 加上理想检索应返回的 `gold` 段落），然后用 `deeptutor kb eval <name> --dataset qa.jsonl --top-k 5 [--mode hybrid] [--save baseline.json]` 为该知识库打分。每个用例都通过与会话回合相同的路径检索，其排序后的引用按精确文本或词法重叠与 gold 段落匹配（阈值可用 `--min-ratio` 调整；不评估语义等价性），运行结果报告 **Recall@k / Precision@k / nDCG@k / MRR / MAP / Hit@k**。指标是排序上的纯函数；没有模型来评判输出。用 `deeptutor kb eval-diff baseline.json candidate.json` 对比已保存的报告，查看逐指标与逐用例的变化。在 `kb eval` 上使用 `--rewrite off` 或 `--rewrite standalone` 可比较原始查询与改写查询；报告会保留改写来源信息。检索失败的用例（索引缺失、凭据错误）不计分并单独报告，而不会把均值拉低。PageIndex 以推理作为检索、不返回排序分块，因此被排除在外。

```jsonl
{"query": "为什么 Transformer 要对注意力做缩放？", "gold": ["缩放可以避免点积随维度增长而过大。"]}
```

</details>

<details>
<summary><b>🌐 资源与个性化 — 资料与可复用的辅助</b></summary>

<div align="center">
<img src="assets/figs/web-dev/resources.png" alt="当前工作区中的资源" width="900">
</div>

**资源**汇聚了会话历史、带可移动记录与 Markdown 导出的**收藏**、**学习日志**、知识中心，以及带答案与解析的题库。可从题库选择开始**练习**，或用**学习 → 练习**进行复习、错题跟踪与间隔重复。独立的**个性化**页承载角色设定、技能（`SKILL.md` 手册）、一键式 **MCP 服务**，以及来自 [CLI-Anything](https://github.com/HKUDS/CLI-Anything) 目录的 **CLI 应用**，每一项都配有按需查看的使用指南。**学习**汇聚书籍、精通路径、阅读集及其辅导会话；每项资产只在支持它的工作流中出现。

<div align="center">
<img src="assets/figs/web-dev/skills.png" alt="个性化技能库" width="900">
</div>

你不必自己写每一个技能——**从 EduHub 导入**可浏览社区目录，并经安全闸门把技能直接下载到你的库中（见[生态](#-生态--eduhub-与技能社区)）。

</details>

<details>
<summary><b>🧠 记忆 — 可检视的个性化</b></summary>

<div align="center">
<img src="assets/figs/web-dev/memory.png" alt="DeepTutor 记忆概览" width="900">
</div>

记忆是一套文件支撑的三层系统，可读、可整理、可审计——刻意*不是*隐藏的向量库。**L1** 是工作区镜像加上仅追加的事件痕迹（`trace/<surface>/<date>.jsonl`）；**L2** 是各界面整理后的事实（`L2/<surface>.md`），并引用 L1 实体；**L3** 是跨界面综合（`L3/<profile|recent|scope|preferences>.md`），记录贡献它的 L2 界面。

<div align="center">
<img src="assets/figs/web-dev/memory-graph.png" alt="DeepTutor 记忆图谱" width="900">
</div>

记忆图谱呈现整座金字塔——中心是 L3 综合，中间环是 L2，外围是 L1 痕迹——并带有精确的 L2 → L1 证据边与 L3 → 贡献界面的连线。记忆在 `chat`、`notebook`、`quiz`、`kb`、`book`、伙伴与 `cowriter` 各界面被跟踪；整理器的更新 / 审计 / 去重预算在**设置 → 记忆**中调整。

</details>

<details>
<summary><b>⚙️ 设置 — 单一控制平面</b></summary>

<div align="center">
<img src="assets/figs/web-dev/settings.png" alt="设置导航器" width="900">
</div>

设置是运维控制平面，打开时停在**通用**页，用于界面语言与模型输出语言。其可搜索的导航器链接到彼此独立的页面：**个人**涵盖工作区、数据迁移、外观与用量统计；**学习与会话**涵盖起始点、附件、视频学习、学员与监护人控制、学习进度与记忆；**模型与服务**涵盖提供方、语言模型、任务模型、嵌入、搜索、语音与多模态生成；**功能与集成**涵盖工具、能力参数、伙伴与智能体，以及知识与文档。**系统**包含网络、运行时状态与关于；**归档会话**可搜索、恢复或永久删除已归档对话。运行时状态包含后端健康、常驻内存，以及评估能力阻塞项、警告与建议的**就绪度**矩阵。工作区把主题文件与学习状态分开存放，并在数据迁移下提供可验证的迁移与导出。一个**提供方**保存厂商地址与凭据，供其各服务模型复用；模型页选择已保存的提供方并配置模型名称与能力。**任务模型**为后台工作（命名会话、撰写起始点）固定一个轻量快速的模型，留空时解析为生效的默认模型。语音汇聚语音合成与转写；多模态生成汇聚图像与视频模型。伙伴与智能体配置本地外壳与远程 Hermes 网关。

**小米 MiMo 语音。** 用 `https://api.xiaomimimo.com/v1` 及其 API 密钥添加小米 MiMo 提供方，然后在设置 → 语音中添加 `mimo-v2.5-tts`。选择 `mimo_default`、`冰糖` 或 `苏打` 等预设，输出选用 `wav` 或 `pcm16`，应用前先试听。语音指令控制风格与语速。该适配器只支持预设音色；音色设计与音色克隆需要另配模型，暂不支持。若此前通过通用 OpenAI 兼容适配器配置过旧的 MiMo 语音模型，请用小米 MiMo 提供方重建其语音条目，使其走 chat-completions 协议。参见[小米 MiMo 语音官方指南](https://mimo.mi.com/docs/zh-CN/quick-start/usage-guide/audio/speech-synthesis-v2.5)。

**MiniMax 语音** — 在设置 → 语音中，文本转语音选择 MiniMax 并选中 `speech-2.8-hd`。配置 MiniMax API 密钥，并显式选择一个系统音色或填入自定义音色 ID。API 基址默认为 `https://api.minimax.io/v1`；中国区请使用 `https://api.minimaxi.com/v1`。朗读与音色预览使用原生语音端点，支持 MP3、WAV、FLAC 或 PCM 输出，以及采样率、语速与语言控制。音色 ID 与账户可用性见 [MiniMax 语音 API](https://platform.minimax.io/docs/api-reference/speech-t2a-http)。


设置 → 学习与会话下的**视频学习**为阅读配置 YouTube 字幕与 Invidious 访问。要使用 Invidious，请设置由管理员维护的后端 API 源（例如 `http://127.0.0.1:3000`）与浏览器可访问的公开源，测试连接、选择 Invidious 并保存。阅读的添加材料对话框中的**浏览 Invidious** 可搜索视频并访问已连接的订阅与播放列表。YouTube 播放使用官方的隐私增强播放器；缺失字幕仍会显示，并会限制导师的证据而不阻塞原生播放。在源码检出中，运行 `python scripts/install_extras.py video-learning` 可获得默认的 YouTube 字幕加载器。既有的观看链接会迁移到阅读中，并保留会话历史、兼容的转写、笔记与进度；新的时间戳笔记即阅读批注。Bilibili 使用自己的播放与字幕路径。

<div align="center">
<img src="assets/figs/web-dev/appearance.png" alt="DeepTutor 外观设置与主题" width="900">
</div>

大多数分区采用「先草稿后应用」的流程，因此你可以先测试提供方再提交。你也可以直接在会话中提出：助手会读取当前配置、应用变更，并说明是否需要重启或重建索引——在提交前先探测新模型，因此不会把自己切到不可达的地方。API 密钥从不经过模型，模型只会为你打开对应的表单。内置四款主题——默认、奶油、深色与玻璃。项目根目录的 `.env` 文件会被有意忽略；除 `DEEPTUTOR_HOME` 或 `deeptutor start --home` 把应用指向别处外，运行时配置位于 `data/user/settings/*.json`。

**OpenAI Codex OAuth（实验性）。** 在设置 → 提供方下添加 **OpenAI Codex** 会打开浏览器登录，走你自己的 ChatGPT 套餐，因此无需 `OPENAI_API_KEY`。令牌只存放在 `data/system/user-secrets/<owner>/private/openai-codex/`——在多容器 Compose 部署中，该位置在任何 exec 沙箱可触及的目录树之外——DeepTutor 绝不读取或修改你的 `~/.codex` CLI 登录。模型列表来自该账户的实时目录；登录会发布档案，但只有在尚未配置任何 LLM 时才会成为生效模型。由于令牌授权的是某个人的套餐，该档案无法通过用户授权共享——每个账户各自登录，普通用户也一样：其登录卡片位于提供方下，由此产生的模型、目录与退出登录都只对该账户可见。

在登录与**刷新模型**时，DeepTutor 会从官方 npm 源读取 `@openai/codex` 的最新稳定版本，并作为目录请求的 `client_version`。这仅是元数据：它不会安装、下载或升级 Codex CLI，且该 npm 请求不携带任何 OAuth 凭据。发现过程有 3 秒超时与 64 KiB 响应上限。若失败，DeepTutor 使用该账户上次成功的版本，或在内无缓存时使用内置回退值。只有成功解析的实时目录才会保存新版本；校验器绝不跨版本或凭据代际复用。版本被拒绝或目录结构不兼容时允许用上一版本重试一次；鉴权、限流与 TLS 失败不会被当作版本问题重试。手动刷新失败会报错，而不会把旧的缓存目录当作已刷新呈现。

成功的版本历史会在同账户令牌续期与目录鉴权错误后继续保留，同时不会让已失效的模型数据或 ETag 重新可用。退出登录会清除该账户的本地缓存，包括版本历史。常规状态读取与推理不会查询 npm。新的目录条目不会替换你已选择的模型，也不会重启学习会话；出现在目录中并不代表完全兼容推理协议。没有后台版本更新器，也没有用户侧版本设置。

默认的本地 Docker 与 Podman 部署使用各自独立的回环网络，登录时需要一座临时桥接。具体的 Docker、Compose、Podman 与拆除命令见[临时本地 Codex OAuth 桥接指南](./docs-for-dev/CONTAINERIZATION.md#temporary-local-codex-oauth-bridge)。

对于远程部署，浏览器的 `localhost` 与服务器的 `localhost` 是两台不同的机器，因此仅靠普通反向代理无法把浏览器的 localhost 回调送到服务器。请用 SSH 隧道作为回调桥接。该隧道抵达已发布的 Web 端口；Next.js 只把确切回调路径重写到公开的回调中转服务，中转服务在路由到原始 OAuth 操作之前会校验 `state`。回调监听器仍留在后端回环上，端口 `1455` 与 `1457` 不会发布，且该路径支持默认的 Docker 桥接网络。

```bash
ssh -N -L 1455:127.0.0.1:3872 <ssh-user>@<server-host>
```

如果 DeepTutor 报告回退回调端口 `1457`，请使用：

```bash
ssh -N -L 1457:127.0.0.1:3872 <ssh-user>@<server-host>
```

只运行与实际回调端口相符的那一条命令，绝不两条都运行。`3872` 只是示例 Web 端口：它是被配置的前端/容器端口，报告为 `callback_forward_port`。该值并不保证 SSH 主机的 `127.0.0.1` 上监听的也是同一端口。若 Docker 或 Podman 发布到不同的宿主端口，或反向代理监听在别的端口，只需把右侧目标端口（上文的 `3872`）替换为 SSH 主机 `127.0.0.1` 上实际监听的 Web 端口；左侧回调端口保持 `1455` 或 `1457`。`<server-host>` 是回环地址拥有该监听端口的 SSH 主机。如果浏览器 URL 指向的是反向代理或负载均衡器，请替换为正确的 SSH 前端主机。

CLI 会打印隧道命令，然后立即尝试打开浏览器。在远程部署中，请让授权页保持打开且不要完成它，在另一个终端建立打印出的隧道，然后再继续授权。

远程拓扑检测存在 localhost 边界。如果 Web 本身是通过 SSH 或 IDE 的 localhost 转发访问的，浏览器无法分辨服务器在远端。对于当前的 Web 操作，请让其授权页保持未完成，读取该操作授权 URL 中的 `redirect_uri` 以确定回调端口是 `1455` 还是 `1457`，并从该本地端口到实际 Web 端口建立第二条隧道。另一种做法是取消该 Web 操作，改用 CLI 重新发起；CLI 的输出属于新操作，绝不能用于既有的 Web 操作。配额错误与目录故障会如实报告，绝不回退到付费提供方。此兼容路径为实验性：上游接口可能变化。

</details>

<details>
<summary><b>👥 多用户 — 共享部署</b> · 可选鉴权，按用户隔离的工作区</summary>

鉴权**默认关闭**——DeepTutor 以单用户方式运行。开启后，一份 `data/` 目录会并列承载管理员工作区、隔离的逐用户工作区与伙伴工作区：

```text
data/
├── user/                    # 管理员工作区 + 全局设置
├── users/<uid>/             # 逐用户作用域：会话历史、记忆、笔记本、知识库
├── partners/<id>/workspace/ # 伙伴（合成用户）作用域
├── cli-apps/                # 已安装的 CLI 应用，以只读方式挂入沙箱
└── system/                  # auth · grants · audit · user-secrets/<owner>（OAuth 令牌）
```

**首个注册用户成为管理员**，拥有模型目录、提供方凭据、共享知识库、技能、规范化共享书籍与逐用户授权。管理员创建的本地用户可选标准、学员或自定义。学员会锁定学习能力与材料策略，增加自适应档案，并支持可吊销、带有效期与每日限额的设备凭据；获授权的监护人可查看报告、审批材料并重置凭据。其他用户获得隔离的工作区，以及受作用域的模型、知识库、技能、伙伴与共享书籍访问权，但拿不到明文 API 密钥。若 `auth.json` 已带有 `username` + `password_hash`，该账户*就是*管理员：`/register` 保持关闭，从 `/admin/users` 创建的账户在你提升之前始终是 `role=user`。

**启用方式：** 在 `data/user/settings/auth.json` 中打开鉴权，重启 `deeptutor start`，在 `/register` 注册首个管理员，然后从 `/admin/users` 添加用户，并通过授权指派模型、知识库、技能、伙伴、工具/MCP/CLI 应用策略与代码执行权限；在各用户的**书籍访问**面板中配置共享书籍。

对于私网/公网分离的源，请把 `auth.private_login_hosts`（或 `AUTH_PRIVATE_LOGIN_HOSTS`）设为可显示口令登录与注册的私有前端主机。前端会把收到的 HTTP `Host` 作为前端主机断言转发给后端。请让你的反向代理保留浏览器的 `Host`，并让公网入口拒绝指向私有主机的请求；不要暴露接受任意 `Host` 值的裸 Next.js 端口。HTTP `Host` 可被直连客户端伪造，因此私有主机授权依赖该入口边界。后端默认只接受来自回环地址的前端主机断言。若 Web 前端从另一个容器或主机连接，请在后端进程上把 `AUTH_TRUSTED_FRONTEND_PROXY_IPS` 设为该前端代理的确切 IP 地址（多个用逗号分隔）。这会替换默认值；若本地前端连接也需要，请包含 `127.0.0.1,::1`。请保持后端 API 仅对前端代理可见，不要在该列表中包含一般客户端网段。当 `private_login_hosts` 非空时，私有源上的已登录用户可打开**个人资料 → 公网设备登录**，为某个 HTTPS 公网源创建短期、绑定主机的配对链接。公网 `/handoff` 页面在 POST 体内用一次性代码换取同样短期的 JWE 票据，票据用后即失效，并下发常规的 HttpOnly 会话 Cookie。

> PocketBase 仍是单用户集成——多用户部署请保持 `integrations.pocketbase_url` 为空，除非你已接入外部用户存储。

</details>

## ⌨️ DeepTutor CLI — 面向智能体的接口

一个 `deeptutor` 二进制，两种使用方式：面向长期在终端工作的人的交互式 **REPL**，以及面向把 DeepTutor 当作工具驱动的其他智能体的结构化 **JSON**。两种方式的能力、工具与知识库完全一致。

<details>
<summary><b>自己驱动</b></summary>

`deeptutor chat` 打开交互式 REPL，并用 `--capability` 选择模式；`deeptutor run <capability> "<message>"` 把该能力作为第一个位置参数，跑完一个回合后退出。两者都接受 `--tool`、`--kb`、`--config` 与 `--workspace` 来选择已注册的工作区。

```bash
deeptutor chat                                              # 交互式 REPL
deeptutor chat --capability deep_solve --kb my-kb
deeptutor run chat "解释傅里叶变换" --kb textbook
deeptutor run chat "找出这份材料之外的最新工作" --kb textbook
deeptutor run deep_research "调研 2026 年关于 RAG 的论文" \
  --config mode=report --config depth=standard
```

`--kb` 为自动 RAG 与知识前沿工具提供上下文；前沿功能需要知识与研究模块同时可用。`--tool` 选择用户可切换的工具。已启用的模块还会提供知识库、会话、伙伴、技能、笔记本、记忆与配置相关命令。

</details>

<details>
<summary><b>让智能体驱动</b></summary>

DeepTutor 天生适合被*另一个智能体操作*。给任意 `run` 加上 `--format json`，每个回合都会流式输出 **NDJSON——每行一个事件**（`content`、`tool_call`、`tool_result`、`done` 等），每行都带上其 `session_id`。运行是无头安全的：无 TTY 时 `ask_user` 的暂停会以空回复自动解除，而不会挂起。

```bash
# 单次执行，机器可读
deeptutor run deep_solve "求 d/dx[sin(x^2)]" --tool reason --format json

# 在同一条有状态会话中串联多个回合——取出 id 后复用
SID=$(deeptutor run deep_research "调研 2026 年关于 RAG 的论文" \
  --config mode=report --config depth=standard --format json \
  | jq -r 'select(.type=="done").session_id')
deeptutor run deep_question "就这份调研考考我" --session "$SID" --format json
```

仓库根目录提供 [`SKILL.md`](SKILL.md)——一份面向 CLI 的精简交接文档。请明确让智能体去读它；其中的[智能体安装指南](docs-for-dev/AGENT_SETUP.md)覆盖安装与配置。你也可以把 `deeptutor run` 包装成 LangChain / AutoGen 循环中的一个工具。完整配方见[智能体交接](https://deeptutor.info/docs/cli/agent-handoff/)。

</details>

<details>
<summary><b>命令参考</b></summary>

下表覆盖完整安装与可选附加组件；命令与能力需要其所在模块已启用。核心提供 `chat` 与 `ask_questions`。

| 命令 | 说明 |
|:---|:---|
| `deeptutor init [--non-interactive] [--home PATH]` | 运行安装向导，或在无提示的情况下创建缺失的默认值 |
| `deeptutor doctor [--online]` | 检查运行时是否已就绪可开会话；`--online` 还会探测已配置的模型提供方，`--format json` 打印报告 |
| `deeptutor start [--home PATH] [--dev] [--detach] [--no-browser]` | 同时启动后端与前端；可选后台运行或抑制打开浏览器 |
| `deeptutor stop [--home PATH]` | 停止以 `--detach` 启动的启动器 |
| `deeptutor serve [--port PORT]` | 只启动 FastAPI 后端 |
| `deeptutor module list/install/uninstall/enable/disable` | 查看模块，并在 DeepTutor 停止时修改它们；源码检出支持 enable/disable |
| `deeptutor workspace show/set/reset` | 查看、选择或恢复逐用户的内容工作区 |
| `deeptutor run <capability> <message>` | 运行单个能力回合（`chat`、`ask_questions`、`deep_solve`、`deep_question`、`deep_research`、`visualize`、`math_animator`、`video_lesson`、`mastery_path`、`immersive_reading`、`audio_overview`）；加 `--format json` 输出 NDJSON |
| `deeptutor chat` | 带能力、工具、知识库、笔记本与历史控制的交互式 REPL |
| `deeptutor partner list/create/start/stop` | 管理接入 IM 的伙伴 |
| `deeptutor kb list/info/create/connect-kiwix/add/search/eval/eval-diff/set-default/delete/list-sources/sync` | 管理知识库、连接 Kiwix 归档、为检索运行打分与对比，并同步已注册的 GitHub/网页来源（含来源增删命令） |
| `deeptutor skill search/install/list/remove/login/logout/publish/update` | 管理技能、从技能中心安装，并发布自己的技能（默认 `eduhub:<slug>`，见「生态」） |
| `deeptutor memory show/clear` | 查看 L2/L3 记忆文档，或清除 L1/全部记忆 |
| `deeptutor session list/show/open/rename/delete` | 管理共享会话 |
| `deeptutor notebook list/create/show/add-md/replace-md/remove-record` | 从 Markdown 文件管理笔记本 |
| `deeptutor book list/health/refresh-fingerprints` | 查看书籍并刷新来源指纹 |
| `deeptutor plugin list/info/state/search/show/install/approve/enable/disable/rollback/uninstall` | 查看工具与能力；管理经审核的插件包及其权限审批 |
| `deeptutor config show [--home PATH]` | 显示解析后的运行时配置，凭据已脱敏 |
| `deeptutor config providers` | 以 JSON 列出受支持的安装提供方及其默认值 |
| `deeptutor config apply FILE [--check] [--home PATH]` | 无提示地应用安装 JSON，或只校验而不写入设置 |
| `deeptutor provider login <provider>` | 提供方鉴权（`openai-codex` OAuth 登录；`github-copilot` GitHub 设备登录；`codebuddy` 校验 CodeBuddy SDK 鉴权并在需要时启动登录） |

GitHub Copilot 凭据属于已登录的 DeepTutor 所有者，只存放在
`<runtime-home>/data/system/user-secrets/<owner-id>/private/github-copilot/credentials.v1.json`，
位于沙箱工作区之外。CLI/管理员伙伴使用管理员的凭据；
其他用户各自登录，且 Copilot 档案无法通过模型授权共享。
外部的 nanobot/Copilot 令牌文件绝不会被导入：升级后请重新运行
`deeptutor provider login github-copilot`。

登录会用当前发现的某个模型验证推理；`init` 会验证所选
模型，失败即中止且不保存草稿配置。仅成功完成 GitHub
鉴权并不等于具备 Copilot 模型访问权（验证失败时会保留已保存的登录）。
运行时请求遵循令牌交换返回的 API 端点，
包括刷新，并尊重每个模型的 Responses/Chat Completions 端点元数据。

Copilot 专属的 Responses 兼容性在派发时应用，不会重写已存储的历史。

</details>

<details>
<summary><b>仅 CLI 发行版</b></summary>

核心 wheel 提供 CLI 与 SDK；`deeptutor-cli` 是兼容用的元包。源码方式暴露全部已检入的模块，因此使用 CLI 时请安装它们的 Python 依赖并跳过前端配置：

```bash
python -m pip install -r requirements/full.txt
python -m pip install -e . --no-deps
```

如需最小安装，请使用核心 wheel。可选发行包会贡献工具、能力、API 路由、后台服务与导航。模块共用同一个 Python 环境，且必须与核心版本匹配。`deeptutor[full]` 在安装时选择常用应用模块；个别功能之后仍可移除。

先停止 DeepTutor（在其终端按 `Ctrl+C`），然后使用同一 Python 环境与 `DEEPTUTOR_HOME`：

```bash
deeptutor module list                       # 已安装 / 已启用 / 就绪
deeptutor module disable research           # 隐藏并停用；保留代码
deeptutor module enable research            # 恢复它及所依赖的模块

# 仅适用于包安装；源码检出使用 enable / disable：
deeptutor module install solve              # 安装匹配的模块与依赖
deeptutor module uninstall solve --dry-run  # 查看计划与依赖阻塞项
deeptutor module uninstall solve            # 只移除该模块的发行包
deeptutor chat                              # 重启 CLI；已安装 Web 应用请用 start
```

示例：`solve`、`research`、`questions`、`knowledge`、`parsing`、`reading`、`mastery`、`books`、`memory`、`notebook` 与 `partners`。被依赖的模块会阻止移除；核心无法通过模块命令移除。停用或卸载会保留设置、会话、知识库与生成的文件。共享的第三方依赖会被保留。

**在浏览器中：** **设置 → 运行时状态 → 模块**会显示模块状态与对应的终端命令。包层面的变更需要先停止环境，并在 CLI 中执行。**会话 → 自定义页面**与**学习 → 新建学习 → 自定义页面**会立即改变个人页面选项；隐藏某个条目并不会卸载其模块或吊销访问权。

1.7.0 包族在核心与各功能 wheel 之间使用匹配的版本号。本地 wheel 安装时，请给 `module install` 传入 `--wheelhouse /path/to/wheels`。构建 wheel 与部署细节见[模块安装与源码开发](docs-for-dev/MODULES.md)。

</details>

## 🧩 生态 — EduHub 与技能社区

DeepTutor 技能采用开放的 **Agent-Skills** 格式——一个包含 `SKILL.md` 手册（YAML 前置元数据 + Markdown）的文件夹，外加可选的参考文件。它本身没有任何 DeepTutor 专有之处，因此任何支持该格式的注册中心都能成为你技能库的来源。DeepTutor 内置 **[EduHub](https://eduhub.deeptutor.info/)**——我们自己的教育向技能注册中心——并将其接入为默认技能中心。

<details>
<summary><b>EduHub — DeepTutor 的技能生态</b></summary>

[**EduHub**](https://eduhub.deeptutor.info/) 是 DeepTutor 为分享教学向智能体技能而推出的社区中心——苏格拉底式导师、单词卡生成器、作文批改、考试蓝图、概念讲解等。它已内建于 DeepTutor，无需配置：裸 slug 或 `eduhub:` 前缀都会解析到它。

**查找与安装** —— 在浏览器中打开**学习空间 → 技能 → 从 EduHub 导入**，浏览目录并把技能直接下载到你的库中。在终端里：

```bash
deeptutor skill search "socratic tutor"               # 搜索 EduHub（默认技能中心）
deeptutor skill install socratic-tutor                # 获取 → 校验 → 注册
deeptutor skill install eduhub:socratic-tutor@1.2.0   # 指定技能中心与版本
deeptutor skill list                                  # 本地技能及其来源中心
```

**发布你自己的技能** —— 打包一份 `SKILL.md` 并分享回社区：

```bash
deeptutor skill login                                 # 浏览器登录 EduHub
deeptutor skill publish ./my-skill                    # 交互式：选择方向 + 标签，然后上传
deeptutor skill update                                # 回滚或发布新版本
```

EduHub 同时也是一个独立的、兼容 ClawHub 的注册中心，因此非 DeepTutor 的智能体（Claude Code、Codex 等）可以通过 `eduhub` CLI 直接使用它——`npx eduhub install socratic-tutor`。

</details>

<details>
<summary><b>导入安全闸门</b></summary>

无论来源如何，每次导入在任何内容接触你的工作区之前都要通过**同一道安全闸门**：

- 首先检查注册中心的**安全判定**——被标记的包会被拒绝，除非你传入 `--allow-unverified`；
- 归档采用防御式解压，校验路径穿越、条目数、体积、压缩比、后缀与符号链接；可执行位会被剥离，无扩展名的文件仍然允许；
- 前置元数据会被规范化到 DeepTutor 的 schema，且 `always:` 会被**剥离**，因此下载来的技能永远无法把自己强塞进每条系统提示词；
- 来源信息——技能中心、版本、判定与安装时间——会写入 `.hub-lock.json`，供审计与更新使用。

在多用户部署中，浏览器导入落到已登录调用者的技能层，而 CLI 与管理控制台的安装以所有者/管理员工作区为目标；管理员技能对普通用户默认隐藏且只读，直到被授权。

</details>

<details>
<summary><b>同时兼容 ClawHub</b></summary>

由于 DeepTutor 使用开放的 Agent-Skills 格式，**[ClawHub](https://clawhub.ai/)** 也可作为一等来源——它与 EduHub 一并内置。用技能中心前缀选择它：

```bash
deeptutor skill search "git release notes" --hub clawhub
deeptutor skill install clawhub:git-release-notes@1.0.1
deeptutor skill install clawhub:udiedrichsen/stock-analysis
```

当多个发布者共用同一个 slug 时，搜索会显示每个发布者以及
完整限定的安装引用（`clawhub:<ownerHandle>/<slug>`）。

在 `data/user/settings/skill_hubs.json` 中添加更多注册中心：`type: "clawhub"` 条目指向任意兼容的 HTTP API（EduHub 与 ClawHub 都支持），`type: "command"` 包装注册中心自带的抓取 CLI，而 `"default"` 选择裸 slug 使用的技能中心。它们全部汇入同一道导入闸门。

</details>

## 🤝 开源伙伴

<p align="center">
  <a href="https://github.com/VectifyAI/PageIndex" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/figs/partners/pageindex-mark-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/figs/partners/pageindex-mark.svg">
      <img src="assets/figs/partners/pageindex-mark.svg" alt="PageIndex" height="38">
    </picture>
  </a>
</p>

<p align="center">
  使用优惠码：<b><code>DEEPTUTOR20</code></b> — 首次订阅 <a href="https://developer.pageindex.ai/">PageIndex</a> 可减免 20 美元！
</p>

## 🌐 社区

### 🔗 维护者

<table>
  <tr>
    <td align="center"><a href="https://github.com/pancacake"><img src="https://avatars.githubusercontent.com/u/150592536?v=4&s=80" width="80" height="80" alt="Bingxi Zhao"><br><strong>Bingxi Zhao</strong></a></td>
    <td align="center"><a href="https://github.com/TyrionH-is-coding"><img src="https://avatars.githubusercontent.com/u/275607548?v=4&s=80" width="80" height="80" alt="Xingyu Hou"><br><strong>Xingyu Hou</strong></a></td>
    <td align="center"><a href="https://github.com/zzhtx258"><img src="https://avatars.githubusercontent.com/u/175302980?v=4&s=80" width="80" height="80" alt="Jiahao Zhang"><br><strong>Jiahao Zhang</strong></a></td>
  </tr>
</table>

### 📮 联系方式

DeepTutor 是由 [Bingxi Zhao](https://github.com/pancacake) 在 [HKUDS](https://github.com/HKUDS) 团队内主导的开源项目，并以**完全开源的形式**迭代，与社区共同构建。迄今为止，我们**没有**任何形式的付费在线产品。欢迎通过 **bingxizhao39@gmail.com** 联系我们，讨论想法或开展合作。

### 🙏 致谢

衷心感谢香港大学数据智能实验室主任 [**Chao Huang**](https://sites.google.com/view/chaoh) 以及 HKUDS 的各位同学给予的热情支持——特别是 [**Jiahao Zhang**](https://github.com/zzhtx258)、[**Zirui Guo**](https://github.com/LarFii) 与 [**Xubin Ren**](https://github.com/Re-bin)。我们也深深感谢**开源社区**：你们的 star、issue、pull request 与讨论每天都在塑造 DeepTutor。

DeepTutor 同样站在众多优秀开源项目的肩膀上，它们既给了我们工具，也给了我们灵感：

| 项目 | 作用 / 启发 |
|:---|:---|
| [**LlamaIndex**](https://github.com/run-llama/llama_index) | RAG 流水线与文档索引的骨干 |
| [**nanobot**](https://github.com/HKUDS/nanobot) | 曾驱动初代 TutorBot 的超轻量智能体引擎 *(HKUDS)* |
| [**LightRAG**](https://github.com/HKUDS/LightRAG) | 简单而快速的 RAG *(HKUDS)* |
| [**AutoAgent**](https://github.com/HKUDS/AutoAgent) | 零代码智能体框架 *(HKUDS)* |
| [**AI-Researcher**](https://github.com/HKUDS/AI-Researcher) | 自动化研究流水线 *(HKUDS)* |
| [**OpenClaw**](https://github.com/openclaw/openclaw) | ClawHub 背后的开放智能体网关与技能生态 |
| [**Codex**](https://github.com/openai/codex) | 启发了我们 CLI 工作流的智能体原生编码 CLI |
| [**Claude Code**](https://github.com/anthropics/claude-code) | 启发了 DeepTutor 智能体循环的智能体式编码 CLI |
| [**ManimCat**](https://github.com/Wing900/ManimCat) | 为数学动画提供 AI 驱动的数学动画生成 |

### 🗺️ 路线图与贡献

我们希望 DeepTutor 持续迭代与改进——并最终成为我们回馈开源社区的一份礼物。我们的[**路线图**](https://github.com/HKUDS/DeepTutor/issues/498)会持续更新；在那里为条目投票或提出新条目。如果你想参与贡献，请参阅[**贡献指南**](CONTRIBUTING.md)，了解分支策略、编码规范与参与方式。

<div align="center">

我们希望 DeepTutor 成为给社区的一份礼物。🎁

<a href="https://github.com/HKUDS/DeepTutor/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=HKUDS/DeepTutor&max=999" alt="贡献者" />
</a>

</div>

<p align="center">
 <a href="https://www.star-history.com/hkuds/deeptutor">
  <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/badge?repo=HKUDS/DeepTutor" />
   <img alt="Star 历史排名" src="https://api.star-history.com/badge?repo=HKUDS/DeepTutor" />
  </picture>
 </a>
</p>

<div align="center">

基于 [Apache License 2.0](LICENSE) 授权。

<p>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=HKUDS.DeepTutor&style=for-the-badge&color=00d4ff" alt="访问量">
</p>

</div>
