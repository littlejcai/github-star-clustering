# GitHub Star 仓库聚类报告：Agent 开发相关

> 账号：littlejcai · Star 总数：289 · Agent 开发相关：155 · 生成时间：2026-09-10

## 聚类总览

| 类别 | 数量 |
|---|---|
| Agent 框架 / Harness | 14 |
| 多智能体编排与协作 | 14 |
| 编码 Agent 与工具链 | 13 |
| Agent 基建：记忆 / RAG / 上下文 | 18 |
| Agent 基建：网关 / 路由 | 8 |
| MCP 生态 | 5 |
| 终端设备 Agent（Computer/Phone Use） | 6 |
| Skills / 插件生态 | 约 65 |
| Agent 工作台 / 人机协作 | 3 |
| 安全与评测 | 1 |
| awesome / 学习资源 | 6 |

---

## 1. Agent 框架 / Harness

- `langchain-ai/langgraph` — 构建有韧性 Agent 的主流框架
- `agentscope-ai/agentscope` — 可见、可理解、可信任的 multi-agent 框架（ReAct + MCP）
- `microsoft/TypeAgent` — 个人 Agent 架构探索（微软官方示例）
- `MervinPraison/PraisonAI` — 轻量 Agent SDK，内置记忆与 RAG
- `deepseek-ai/deepseek-harness` — "Everything is a Plugin" 的插件化 harness
- `earendil-works/pi` — 统一 LLM API + agent loop + TUI 的工具包
- `agentscope-ai/QwenPaw` — 可自部署的个人 AI 助手 harness
- `OpenBMB/StaffDeck` — 企业级数字员工平台
- `langgenius/dify` — Agentic 工作流 + RAG 一体化平台
- `1Panel-dev/MaxKB` — 企业级智能体开源平台
- `tinyhumansai/openhuman` — 本地优先记忆 + agent 编排的个人 AI
- `NousResearch/hermes-agent` — "与你一同成长"的 AI Agent
- `HKUDS/CLI-Anything` — 让任意软件变 Agent-Native 的 CLI
- `yc-software/qm` — 面向工作的 multiplayer agent harness

## 2. 多智能体编排与协作

- `crewAIInc/crewAI` — 角色扮演式自主 Agent 编排
- `HKUDS/ClawTeam` — Agent 群体智能（Swarm），一条命令全自动
- `HKUDS/Vibe-Trading` — multi-agent + MCP 的个人交易 Agent
- `TencentCloud/Octop` — 自托管多用户多 Agent 助手（长期记忆）
- `mateaix/mateclaw` — Spring AI Alibaba 多 Agent 编排
- `agentscope-ai/AgentTeams` — Multi-Agent OS，Matrix rooms 人在回路协调
- `littlejcai/OpenMAIC` / `THU-MAIC/OpenMAIC` — 多智能体互动课堂（自研 + 上游）
- `yetone/cumora` — AI Agent 作为队员的团队聊天
- `yangbod/goteams` — 内置 Agent 员工的研发项目管理
- `tutti-os/tutti` — 本地优先的 multi-agent 桌面工作台
- `HKUDS/DeepTutor` — 多智能体 + RAG 的个性化 AI 导师
- `paperclipai/paperclip` — 管理工作中 agents 的开源应用
- `pixel-agents-hq/pixel-agents` — 像素风 agent 办公室（可视化）
- `HKUDS/OpenOPC` — 个人 AI-Native Company

## 3. 编码 Agent 与工具链

- `openai/codex` — 终端轻量编码 agent
- `OpenHands/OpenHands` — AI 软件开发 Agent 平台
- `mindfold-ai/Trellis` — 面向 agentic coding 的 harness
- `esengine/DeepSeek-Reasonix` — DeepSeek 原生终端编码 agent
- `alibaba/open-code-review` — 流水线 + LLM 混合的仓库级代码评审
- `github/spec-kit` — 规格驱动开发（SDD）工具包
- `chuspeeism/dashi-taskboard` — 支持 Codex/DSH 的任务面板
- `farion1231/cc-switch` — Claude Code/Codex/OpenCode 一体化管理桌面
- `zarazhangrui/lark-coding-agent-bridge` — 飞书桥接本地 Claude Code/Codex
- `chenhg5/cc-connect` — 编码 agent 桥接飞书/钉钉/Slack 等 IM
- `uluckyXH/Chat-Codex` — Codex 接入微信/飞书远程控制
- `YishenTu/claudian` — Obsidian 中嵌入 Claude Code/Codex
- `leigest519/OpenGame` — 游戏开发方向的 Agentic Coding

## 4. Agent 基建：记忆 / RAG / 上下文

- `MemTensor/MemOS` — Agent 自进化记忆操作系统
- `thedotmack/claude-mem` — 跨会话持久记忆插件
- `volcengine/OpenViking` — 自进化上下文数据库（记忆 + RAG + Skills）
- `TencentCloud/TencentDB-Agent-Memory` — 团队级 Agent 记忆中心
- `infiniflow/ragflow` — 开源 RAG 引擎 + Agent 能力
- `labring/FastGPT` — 知识库 + RAG + 可视化编排
- `Tencent/WeKnora` — 文档 RAG + 自主推理 Agent
- `lancedb/lancedb` — 嵌入式多模态向量检索
- `semantica-agi/semantica` — 图原生 agent-memory + graph-rag
- `Egonex-AI/Understand-Anything` — 代码转知识图谱，适配各编码 agent
- `firecrawl/firecrawl` — 面向 Agent 的网页抓取上下文 API
- `microsoft/markitdown` — 文件转 Markdown 的上下文预处理
- `Benboerba620/karpathy-claude-wiki` — 无向量库的 markdown 个人 wiki
- `tobi/qmd` — 本地个人文档 mini 搜索引擎
- `yyjeqhc/webcodex` — 云端 Agent 获得本地真实开发环境
- `littlejcai/dsh-remote-bridge` / `littlejcai/dsh-remote-console` — 自研 DSH 远程网关
- `zhu1090093659/deepseek-pp` — DeepSeek 网页版扩展（MCP + 记忆 + Skills）

## 5. Agent 基建：网关 / 路由

- `agentgateway/agentgateway` — 面向 Agent 与 MCP server 的 Agentic Proxy
- `musistudio/claude-code-router` — 跨模型路由 + 工具编排本地控制面
- `QuantumNous/new-api` / `songquanpeng/one-api` — 多厂商模型 API 聚合分发
- `oomol-lab/open-connector` — 1400+ SaaS 经 MCP/HTTP 接入 Agent
- `jackwener/OpenCLI` — 把网站变 CLI，复用已登录浏览器
- `bytedance/flowgram.ai` — 可视化工作流开发框架
- `heygen-com/hyperframes` — 专为 agent 构建的 HTML 渲染视频框架

## 6. MCP 生态

- `sparfenyuk/mcp-proxy` — Streamable HTTP ↔ stdio 传输桥接
- `alchaincyf/huashu-chrome` — MCP + Chrome 扩展，带登录态操控浏览器
- `tirth8205/code-review-graph` — 本地代码智能图（MCP + CLI）
- `Graphify-Labs/graphify` — 代码库转可查询知识图谱
- `louchi1984-coder/deepseek-claude-code-worker-mcp` — Codex Desktop 的 DeepSeek worker MCP

## 7. 终端设备 Agent（Computer/Phone Use）

- `bytedance/UI-TARS-desktop` — 开源多模态 computer-use 技术栈
- `TurixAI/TuriX-CUA` — GUI 操作 Agent
- `PhoneHarness/PhoneHarness` — 混合动作手机 Agent 运行时
- `openclaw/openclaw` — "真正能做事"的跨平台个人 AI
- `imjszhang/Deepseek-Cowork` — DeepSeek 驱动的浏览器自动化
- `rtjowo/Openclaw-With-Apple` — 无描述

## 8. Skills / 插件生态

### 平台与管理

- `HKUDS/OpenSpace` — AI Agent 的 Skill 管理层
- `xingkongliang/skills-manager` — 跨 50+ 工具同步 skills 的桌面应用
- `littlejcai/skills-hub` / `littlejcai/pay-skills` — 自研 skill 管理平台
- `iflytek/skillhub` — 企业级自托管 skill 注册中心（版本化/RBAC）
- `gnipbao/dao-skill` — 从混沌需求生成可进化的 Skill
- `alchaincyf/darwin-skill` — Skill 自主进化系统（评估→改进→回滚）
- `AdamPlatin123/dsh-plugin-radar` — DSH 插件生态雷达

### 官方 / 名人 skill 集

- `anthropics/skills` / `anthropics/knowledge-work-plugins` — Anthropic 官方
- `mattpocock/skills` / `vinvcn/mattpocock-skills-zh-CN` — 原作 + 中文本地化
- `addyosmani/agent-skills` — 面向编码 Agent 的生产级工程技能
- `obra/superpowers` — agentic skills 框架 + 子 agent 驱动开发方法论
- `garrytan/gstack` — 复刻 Garry Tan 的 Claude Code 配置（CEO/设计/QA 等角色）
- `humanlayer/skills` / `slavingia/skills` — 无描述
- `QwenLM/Qwen-MM-Plugins` — 多模态插件
- `OpenSenseNova/SenseNova-Skills` — 商汤办公助手 skills

### 内容创作 / 设计

- `alchaincyf/huashu-excel` / `alchaincyf/huashu-design` — 数据分析、HTML 原生设计
- `oil-oil/oil-cover` / `oil-oil/beautify-github-readme` — 小红书封面、README 美化
- `JimLiu/baoyu-design` / `JimLiu/baoyu-skills` — Claude Design 本地化
- `isjiamu/gzh-design-skill` — Markdown 一键排公众号 HTML
- `pyang5166/gbro-cover-design` — 公众号/小红书封面提示词
- `zarazhangrui/frontend-slides` — 网页幻灯片
- `tt-a1i/archify` — 可验证架构图生成
- `oh-my-mermaid/oh-my-mermaid` — 代码库转 Mermaid 架构图
- `larashero3-dotcom/lieflat-charts` — 可交互 HTML 图表
- `calesthio/OpenMontage` — agentic 视频生产系统（12 流水线/700+ skill）
- `Vincentwei1021/video-shotcraft` — Remotion 产品宣传片
- `luoluoluo22/jianying-editor-skill` — 自动化剪映编辑
- `heygen-com/skills` — 数字人视频流水线
- `nexu-io/html-anything` — Agent 化 HTML 编辑器（75 skills × 9 输出面）
- `vickysy/wechat-article-illustrator-skill` — 无描述
- `yuwen-cool/yuwen-publish-precheck` — 发布前合规审查
- `Rion-Wu-tech/wechat-intelligence-hub` — 微信情报系统 + Codex skills
- `eze-is/web-access` — 给 Claude Code 装联网能力
- `PleasePrompto/notebooklm-skill` / `joeseesun/qiaomu-anything-to-notebooklm` — NotebookLM 互通
- `larksuite/openclaw-lark` — 飞书官方 OpenClaw 插件
- `Nanako0129/sepia` — De-AI 写作 skill

### 知识管理（Obsidian 系）

- `kepano/obsidian-skills` / `logancyang/obsidian-copilot` / `Lapis0x0/obsidian-yolo`
- `ballred/obsidian-claude-pkm` / `AgriciDaniel/claude-obsidian` — PKM / 第二大脑

### 垂直领域

- `JuneYaooo/nihaisha-nishi-tcm` — 中医课程资料
- `handsomestWei/patent-disclosure-skill` — 专利交底书
- `wzyn20051216/solidworks-automation-skill` / `earthtojake/text-to-cad` — CAD 自动化
- `jeecgboot/skills` — 低代码全套工件生成
- `vickysy/english-retell-coach` — 英语复述训练
- `darrenli6/JJKoubo` — 口播视频剪辑
- `neilsonnn/image-blaster` — image-to-world 技能集
- `shengjidaguai-china/personal-homepage-skill` — 个人主页生成
- `KKKKhazix/khazix-skills` — 卡兹克开源合集（适配 40+ agents）
- `ConardLi/garden-skills` — 网页设计/知识检索/图像生成合集
- `DietrichGebert/ponytail` — 让 agent 像"最懒的资深工程师"思考

### 蒸馏 / 生成 skill 的 skill

- `alchaincyf/nuwa-skill` — 蒸馏任何人的思维方式
- `kangarooking/cangjie-skill` — 书籍/长视频/播客蒸馏为 skill
- `Leonxlnx/taste-skill` — 提升 AI 输出品味
- `vickysy/thought-prism-skill` — 思维棱镜

## 9. Agent 工作台 / 人机协作

- `tabtin-ai/TabTin` — 人与多 agent 协同桌面 workspace
- `cloudflare/cloudflare-os` — Workers 上的 Agent workspace
- `Devin-AXIS/iPolloWork` — 多引擎统一的企业级本地 Agent Workbench

## 10. 安全与评测

- `Tencent/AI-Infra-Guard` — AI 红队平台（Agent/Skills/MCP 扫描 + 越狱评估）

## 11. awesome / 学习资源

- `fleurytian/awesome-claude-skills` — Claude Skills 合集
- `nuwa-skills/awesome-nuwa` — 女娲.skill 合集
- `AlephAITech/WorkBuddyGuide` — WorkBuddy 实战蓝皮书（Skills/MCP/多智能体）
- `datawhalechina/easy-vibe` — vibe coding 101 课程
- `VoltAgent/awesome-design-md` / `Meliwat/awesome-ios-design-md` — 给编码 Agent 用的设计系统集合

---

## 观察

- Star 明显偏向 **Skills 生态**（占 40%+），其次是 Agent 记忆/RAG 基建——与自研的 `skills-hub`、`dsh-remote-bridge`、`OpenMAIC` 方向高度一致
- 编码 Agent 方向覆盖了"本地 CLI → IM 桥接 → 远程控制 → 代码评审"的完整链路
- 多智能体方向集中在国内团队（HKUDS、agentscope、Tencent）+ crewAI
