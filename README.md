# GitHub Star 仓库聚类报告：Agent 开发相关

> 账号：littlejcai · Star 总数：274 · Agent 开发相关：149 · 更新时间：2026-09-10
>
> 条目格式：`owner/repo` ⭐ star 数 · 主要语言 — 说明
>

## 聚类总览

| 类别 | 数量 |
|---|---|
| Agent 框架 / Harness | 14 |
| 多智能体编排与协作 | 14 |
| 编码 Agent 与工具链 | 13 |
| Agent 基建：记忆 / RAG / 上下文 | 16 |
| Agent 基建：网关 / 路由 | 8 |
| MCP 生态 | 5 |
| 终端设备 Agent（Computer/Phone Use） | 6 |
| Skills / 插件生态 | 63 |
| Agent 工作台 / 人机协作 | 3 |
| 安全与评测 | 1 |
| awesome / 学习资源 | 6 |

---

## 1. Agent 框架 / Harness

- `langchain-ai/langgraph` ⭐ 41.3k · Python — 构建有韧性 Agent 的主流框架
- `agentscope-ai/agentscope` ⭐ 31.2k · Python — 可见、可理解、可信任的 multi-agent 框架（ReAct + MCP）
- `microsoft/TypeAgent` ⭐ 740 · TypeScript — 个人 Agent 架构探索（微软官方示例）
- `MervinPraison/PraisonAI` ⭐ 9k · Python — 轻量 Agent SDK，内置记忆与 RAG
- `deepseek-ai/deepseek-harness` ⭐ 217.5k · TypeScript — "Everything is a Plugin" 的插件化 harness
- `earendil-works/pi` ⭐ 103.5k · TypeScript — 统一 LLM API + agent loop + TUI 的工具包
- `agentscope-ai/QwenPaw` ⭐ 34.7k · Python — 可自部署的个人 AI 助手 harness
- `OpenBMB/StaffDeck` ⭐ 1.9k · Python — 企业级数字员工平台
- `langgenius/dify` ⭐ 155.3k · TypeScript — Agentic 工作流 + RAG 一体化平台
- `1Panel-dev/MaxKB` ⭐ 22.7k · Python — 企业级智能体开源平台
- `tinyhumansai/openhuman` ⭐ 39.6k · Rust — 本地优先记忆 + agent 编排的个人 AI
- `NousResearch/hermes-agent` ⭐ 243.9k · Python — "与你一同成长"的 AI Agent
- `HKUDS/CLI-Anything` ⭐ 49.2k · Python — 让任意软件变 Agent-Native 的 CLI
- `yc-software/qm` ⭐ 14.8k · TypeScript — 面向工作的 multiplayer agent harness

## 2. 多智能体编排与协作

- `crewAIInc/crewAI` ⭐ 58.3k · Python — 角色扮演式自主 Agent 编排
- `HKUDS/ClawTeam` ⭐ 5.5k · Python — Agent 群体智能（Swarm），一条命令全自动
- `HKUDS/Vibe-Trading` ⭐ 33.1k · Python — multi-agent + MCP 的个人交易 Agent
- `TencentCloud/Octop` ⭐ 1.5k · Python — 自托管多用户多 Agent 助手（长期记忆）
- `mateaix/mateclaw` ⭐ 1.1k · Java — Spring AI Alibaba 多 Agent 编排
- `agentscope-ai/AgentTeams` ⭐ 5.6k · Go — Multi-Agent OS，Matrix rooms 人在回路协调
- `THU-MAIC/OpenMAIC` ⭐ 34.5k · TypeScript — 多智能体互动课堂
- `yetone/cumora` ⭐ 3.5k · TypeScript — AI Agent 作为队员的团队聊天
- `yangbod/goteams` ⭐ 5 — 内置 Agent 员工的研发项目管理
- `tutti-os/tutti` ⭐ 3.7k · TypeScript — 本地优先的 multi-agent 桌面工作台
- `HKUDS/DeepTutor` ⭐ 39.1k · Python — 多智能体 + RAG 的个性化 AI 导师
- `paperclipai/paperclip` ⭐ 80.3k · TypeScript — 管理工作中 agents 的开源应用
- `pixel-agents-hq/pixel-agents` ⭐ 9.2k · TypeScript — 像素风 agent 办公室（可视化）
- `HKUDS/OpenOPC` ⭐ 1.6k · Python — 个人 AI-Native Company

## 3. 编码 Agent 与工具链

- `openai/codex` ⭐ 122.9k · Rust — 终端轻量编码 agent
- `OpenHands/OpenHands` ⭐ 87.1k · TypeScript — AI 软件开发 Agent 平台
- `mindfold-ai/Trellis` ⭐ 14.6k · TypeScript — 面向 agentic coding 的 harness
- `esengine/DeepSeek-Reasonix` ⭐ 35.5k · Go — DeepSeek 原生终端编码 agent
- `alibaba/open-code-review` ⭐ 22.2k · Go — 流水线 + LLM 混合的仓库级代码评审
- `github/spec-kit` ⭐ 134.4k · Python — 规格驱动开发（SDD）工具包
- `chuspeeism/dashi-taskboard` ⭐ 3k · JavaScript — 支持 Codex/DSH 的任务面板
- `farion1231/cc-switch` ⭐ 132k · Rust — Claude Code/Codex/OpenCode 一体化管理桌面
- `zarazhangrui/lark-coding-agent-bridge` ⭐ 2.5k · TypeScript — 飞书桥接本地 Claude Code/Codex
- `chenhg5/cc-connect` ⭐ 15.4k · Go — 编码 agent 桥接飞书/钉钉/Slack 等 IM
- `uluckyXH/Chat-Codex` ⭐ 198 · TypeScript — Codex 接入微信/飞书远程控制
- `YishenTu/claudian` ⭐ 15.2k · TypeScript — Obsidian 中嵌入 Claude Code/Codex
- `leigest519/OpenGame` ⭐ 2.9k · TypeScript — 游戏开发方向的 Agentic Coding

## 4. Agent 基建：记忆 / RAG / 上下文

- `MemTensor/MemOS` ⭐ 11.3k · TypeScript — Agent 自进化记忆操作系统
- `thedotmack/claude-mem` ⭐ 93.6k · JavaScript — 跨会话持久记忆插件
- `volcengine/OpenViking` ⭐ 36.3k · Python — 自进化上下文数据库（记忆 + RAG + Skills）
- `TencentCloud/TencentDB-Agent-Memory` ⭐ 26.2k · TypeScript — 团队级 Agent 记忆中心
- `infiniflow/ragflow` ⭐ 90.4k · Go — 开源 RAG 引擎 + Agent 能力
- `labring/FastGPT` ⭐ 29.6k · TypeScript — 知识库 + RAG + 可视化编排
- `Tencent/WeKnora` ⭐ 22k · Go — 文档 RAG + 自主推理 Agent
- `lancedb/lancedb` ⭐ 11.4k · Rust — 嵌入式多模态向量检索
- `semantica-agi/semantica` ⭐ 12.5k · Python — 图原生 agent-memory + graph-rag
- `Egonex-AI/Understand-Anything` ⭐ 81.9k · TypeScript — 代码转知识图谱，适配各编码 agent
- `firecrawl/firecrawl` ⭐ 178.4k · TypeScript — 面向 Agent 的网页抓取上下文 API
- `microsoft/markitdown` ⭐ 182.2k · Python — 文件转 Markdown 的上下文预处理
- `Benboerba620/karpathy-claude-wiki` ⭐ 67 · Python — 无向量库的 markdown 个人 wiki
- `tobi/qmd` ⭐ 29.6k · TypeScript — 本地个人文档 mini 搜索引擎
- `yyjeqhc/webcodex` ⭐ 580 · Rust — 云端 Agent 获得本地真实开发环境
- `zhu1090093659/deepseek-pp` ⭐ 1.8k · TypeScript — DeepSeek 网页版扩展（MCP + 记忆 + Skills）

## 5. Agent 基建：网关 / 路由

- `agentgateway/agentgateway` ⭐ 4.8k · Rust — 面向 Agent 与 MCP server 的 Agentic Proxy
- `musistudio/claude-code-router` ⭐ 37.2k · TypeScript — 跨模型路由 + 工具编排本地控制面
- `QuantumNous/new-api` ⭐ 47.7k · Go / `songquanpeng/one-api` ⭐ 36.8k · JavaScript — 多厂商模型 API 聚合分发
- `oomol-lab/open-connector` ⭐ 5.7k · TypeScript — 1400+ SaaS 经 MCP/HTTP 接入 Agent
- `jackwener/OpenCLI` ⭐ 29.1k · JavaScript — 把网站变 CLI，复用已登录浏览器
- `bytedance/flowgram.ai` ⭐ 8.4k · TypeScript — 可视化工作流开发框架
- `heygen-com/hyperframes` ⭐ 48.4k · TypeScript — 专为 agent 构建的 HTML 渲染视频框架

## 6. MCP 生态

- `sparfenyuk/mcp-proxy` ⭐ 2.7k · Python — Streamable HTTP ↔ stdio 传输桥接
- `alchaincyf/huashu-chrome` ⭐ 148 · JavaScript — MCP + Chrome 扩展，带登录态操控浏览器
- `tirth8205/code-review-graph` ⭐ 31.3k · Python — 本地代码智能图（MCP + CLI）
- `Graphify-Labs/graphify` ⭐ 116.4k · Python — 代码库转可查询知识图谱
- `louchi1984-coder/deepseek-claude-code-worker-mcp` ⭐ 99 · JavaScript — Codex Desktop 的 DeepSeek worker MCP

## 7. 终端设备 Agent（Computer/Phone Use）

- `bytedance/UI-TARS-desktop` ⭐ 38.9k · TypeScript — 开源多模态 computer-use 技术栈
- `TurixAI/TuriX-CUA` ⭐ 3.2k · Python — GUI 操作 Agent
- `PhoneHarness/PhoneHarness` ⭐ 59 · Python — 混合动作手机 Agent 运行时
- `openclaw/openclaw` ⭐ 389.3k · TypeScript — "真正能做事"的跨平台个人 AI
- `imjszhang/Deepseek-Cowork` ⭐ 217 · JavaScript — DeepSeek 驱动的浏览器自动化
- `rtjowo/Openclaw-With-Apple` ⭐ 79 · Python — 无描述

## 8. Skills / 插件生态

### 平台与管理

- `HKUDS/OpenSpace` ⭐ 7.6k · Python — AI Agent 的 Skill 管理层
- `xingkongliang/skills-manager` ⭐ 4.6k · Rust — 跨 50+ 工具同步 skills 的桌面应用
- `iflytek/skillhub` ⭐ 5.1k · Java — 企业级自托管 skill 注册中心（版本化/RBAC）
- `gnipbao/dao-skill` ⭐ 241 · Python — 从混沌需求生成可进化的 Skill
- `alchaincyf/darwin-skill` ⭐ 5.9k · HTML — Skill 自主进化系统（评估→改进→回滚）
- `AdamPlatin123/dsh-plugin-radar` ⭐ 1.5k · Python — DSH 插件生态雷达

### 官方 / 名人 skill 集

- `anthropics/skills` ⭐ 175.4k · Python / `anthropics/knowledge-work-plugins` ⭐ 23.9k · Python — Anthropic 官方
- `mattpocock/skills` ⭐ 257.9k · Shell / `vinvcn/mattpocock-skills-zh-CN` ⭐ 4.1k · Shell — 原作 + 中文本地化
- `addyosmani/agent-skills` ⭐ 93.2k · JavaScript — 面向编码 Agent 的生产级工程技能
- `obra/superpowers` ⭐ 284.1k · Shell — agentic skills 框架 + 子 agent 驱动开发方法论
- `garrytan/gstack` ⭐ 132.3k · TypeScript — 复刻 Garry Tan 的 Claude Code 配置（CEO/设计/QA 等角色）
- `humanlayer/skills` ⭐ 3.7k · TypeScript / `slavingia/skills` ⭐ 10k — 无描述
- `QwenLM/Qwen-MM-Plugins` ⭐ 2.8k · Python — 多模态插件
- `OpenSenseNova/SenseNova-Skills` ⭐ 5.5k · JavaScript — 商汤办公助手 skills

### 内容创作 / 设计

- `alchaincyf/huashu-excel` ⭐ 377 · Python / `alchaincyf/huashu-design` ⭐ 24k · HTML — 数据分析、HTML 原生设计
- `oil-oil/oil-cover` ⭐ 227 · Python / `oil-oil/beautify-github-readme` ⭐ 1.7k · Python — 小红书封面、README 美化
- `JimLiu/baoyu-design` ⭐ 4k · JavaScript / `JimLiu/baoyu-skills` ⭐ 25.8k · TypeScript — Claude Design 本地化
- `isjiamu/gzh-design-skill` ⭐ 3.6k · HTML — Markdown 一键排公众号 HTML
- `pyang5166/gbro-cover-design` ⭐ 761 — 公众号/小红书封面提示词
- `zarazhangrui/frontend-slides` ⭐ 29k · JavaScript — 网页幻灯片
- `tt-a1i/archify` ⭐ 56.2k · JavaScript — 可验证架构图生成
- `oh-my-mermaid/oh-my-mermaid` ⭐ 2.3k · TypeScript — 代码库转 Mermaid 架构图
- `larashero3-dotcom/lieflat-charts` ⭐ 5.1k · HTML — 可交互 HTML 图表
- `calesthio/OpenMontage` ⭐ 56.9k · Python — agentic 视频生产系统（12 流水线/700+ skill）
- `Vincentwei1021/video-shotcraft` ⭐ 7.9k · TypeScript — Remotion 产品宣传片
- `luoluoluo22/jianying-editor-skill` ⭐ 3k · Python — 自动化剪映编辑
- `heygen-com/skills` ⭐ 432 · Shell — 数字人视频流水线
- `nexu-io/html-anything` ⭐ 8.7k · HTML — Agent 化 HTML 编辑器（75 skills × 9 输出面）
- `vickysy/wechat-article-illustrator-skill` ⭐ 7 · Python — 无描述
- `yuwen-cool/yuwen-publish-precheck` ⭐ 714 · Python — 发布前合规审查
- `Rion-Wu-tech/wechat-intelligence-hub` ⭐ 2k · Python — 微信情报系统 + Codex skills
- `eze-is/web-access` ⭐ 8.9k · JavaScript — 给 Claude Code 装联网能力
- `PleasePrompto/notebooklm-skill` ⭐ 7.8k · Python / `joeseesun/qiaomu-anything-to-notebooklm` ⭐ 6k · Python — NotebookLM 互通
- `larksuite/openclaw-lark` ⭐ 2.4k · TypeScript — 飞书官方 OpenClaw 插件
- `Nanako0129/sepia` ⭐ 2.5k · Python — De-AI 写作 skill

### 知识管理（Obsidian 系）

- `kepano/obsidian-skills` ⭐ 48.1k / `logancyang/obsidian-copilot` ⭐ 7.7k · TypeScript / `Lapis0x0/obsidian-yolo` ⭐ 1.3k · TypeScript
- `ballred/obsidian-claude-pkm` ⭐ 1.9k · Shell / `AgriciDaniel/claude-obsidian` ⭐ 14.8k · Python — PKM / 第二大脑

### 垂直领域

- `JuneYaooo/nihaisha-nishi-tcm` ⭐ 2.1k · Python — 中医课程资料
- `handsomestWei/patent-disclosure-skill` ⭐ 9k · Python — 专利交底书
- `wzyn20051216/solidworks-automation-skill` ⭐ 873 · Python / `earthtojake/text-to-cad` ⭐ 15.1k · Python — CAD 自动化
- `jeecgboot/skills` ⭐ 229 · Python — 低代码全套工件生成
- `vickysy/english-retell-coach` ⭐ 5 — 英语复述训练
- `darrenli6/JJKoubo` ⭐ 23 · JavaScript — 口播视频剪辑
- `neilsonnn/image-blaster` ⭐ 4.9k · TypeScript — image-to-world 技能集
- `shengjidaguai-china/personal-homepage-skill` ⭐ 315 · TypeScript — 个人主页生成
- `KKKKhazix/khazix-skills` ⭐ 20.6k · Python — 卡兹克开源合集（适配 40+ agents）
- `ConardLi/garden-skills` ⭐ 12.3k · CSS — 网页设计/知识检索/图像生成合集
- `DietrichGebert/ponytail` ⭐ 133.5k · JavaScript — 让 agent 像"最懒的资深工程师"思考

### 蒸馏 / 生成 skill 的 skill

- `alchaincyf/nuwa-skill` ⭐ 32.3k · Python — 蒸馏任何人的思维方式
- `kangarooking/cangjie-skill` ⭐ 9.8k · Python — 书籍/长视频/播客蒸馏为 skill
- `Leonxlnx/taste-skill` ⭐ 85.8k · JavaScript — 提升 AI 输出品味
- `vickysy/thought-prism-skill` ⭐ 14 — 思维棱镜

## 9. Agent 工作台 / 人机协作

- `tabtin-ai/TabTin` ⭐ 343 · TypeScript — 人与多 agent 协同桌面 workspace
- `cloudflare/cloudflare-os` ⭐ 9.8k · TypeScript — Workers 上的 Agent workspace
- `Devin-AXIS/iPolloWork` ⭐ 5.7k · TypeScript — 多引擎统一的企业级本地 Agent Workbench

## 10. 安全与评测

- `Tencent/AI-Infra-Guard` ⭐ 6.2k · Python — AI 红队平台（Agent/Skills/MCP 扫描 + 越狱评估）

## 11. awesome / 学习资源

- `fleurytian/awesome-claude-skills` ⭐ 317 · Python — Claude Skills 合集
- `nuwa-skills/awesome-nuwa` ⭐ 361 · Ruby — 女娲.skill 合集
- `AlephAITech/WorkBuddyGuide` ⭐ 2.9k · TypeScript — WorkBuddy 实战蓝皮书（Skills/MCP/多智能体）
- `datawhalechina/easy-vibe` ⭐ 19.3k · JavaScript — vibe coding 101 课程
- `VoltAgent/awesome-design-md` ⭐ 115.1k / `Meliwat/awesome-ios-design-md` ⭐ 520 — 给编码 Agent 用的设计系统集合

---

## 观察

- Star 明显偏向 **Skills 生态**（占 40%+），其次是 Agent 记忆/RAG 基建——与自研的 `skills-hub`、`dsh-remote-bridge`、`OpenMAIC` 方向高度一致
- 编码 Agent 方向覆盖了"本地 CLI → IM 桥接 → 远程控制 → 代码评审"的完整链路
- 多智能体方向集中在国内团队（HKUDS、agentscope、Tencent）+ crewAI
