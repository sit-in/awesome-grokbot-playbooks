<p align="center">
  <img src="assets/social-preview.png" width="720" alt="Grok Bot 中文配方库">
</p>

<h1 align="center">Awesome Grok Bot Playbooks</h1>

<p align="center"><b>Grok Bot 中文配方库：拿来就能跑的配方 + 逐条核实的生态清单</b></p>

<p align="center">
  <a href="https://github.com/sit-in/awesome-grokbot-playbooks/stargazers"><img src="https://img.shields.io/github/stars/sit-in/awesome-grokbot-playbooks?style=flat-square&color=ff7a1a" alt="Stars"></a>
  <img src="https://img.shields.io/badge/%E6%9D%A1%E7%9B%AE-84-blue?style=flat-square" alt="Entries">
  <img src="https://img.shields.io/badge/%E9%85%8D%E6%96%B9-9-blueviolet?style=flat-square" alt="Recipes">
  <img src="https://img.shields.io/badge/%E6%9C%80%E8%BF%91%E6%A0%B8%E5%AE%9E-2026--10--21-success?style=flat-square" alt="Last verified">
  <a href="https://github.com/sit-in/awesome-grokbot-playbooks/actions/workflows/link-check.yml"><img src="https://github.com/sit-in/awesome-grokbot-playbooks/actions/workflows/link-check.yml/badge.svg" alt="link-check"></a>
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs welcome"></a>
  <img src="https://img.shields.io/badge/%E9%9D%9E%E5%AE%98%E6%96%B9-lightgrey?style=flat-square" alt="Unofficial">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square" alt="MIT"></a>
</p>

<p align="center">
  <b>中文</b> · <a href="README.en.md">English</a> · <a href="docs/quickstart.md">快速上手</a> · <a href="ROADMAP.md">路线图</a> · <a href="#-参与贡献">参与贡献</a>
</p>

## ⚡ 为什么看这个仓库

| | |
|---:|---|
| **84** | 个条目，每条都用 GitHub API 或页面核过：仓库存在、还在更新、确实和 Grok Bot 相关；许可证情况写在短评里 |
| **9** | 个可抄配方，统一格式：场景 → 输入 → 步骤 → prompt → 产出 → 坑，样例全部脱敏 |
| **3 级** | 验证标记：✅ 真机跑通 · 🔍 读过文档和配置 · 无标记＝只核实过仓库。✅ 只给真跑过的 |
| **142** | 篇社区教程和 X 长文精选（[社区教程](docs/community-tutorials.md) 25 + [X 大 V 文章](docs/x-articles.md) 117），加上作者自己的连载索引，每条都核过存活、作者和发布日期 |
| **2 个 AI** | 在维护：Grok Bot 每天找料，Claude Code 核实、写短评，人只拍板。协作记录全公开在 [`.collab/`](.collab/README.md) |

和英文生态导航 [awesome-grok-bot](https://github.com/ZeroPointRepo/awesome-grok-bot) 的分工：它覆盖面广；本仓侧重**中文一人公司、多 Bot 作战室、雷达 Routine 和可抄配方**。不拼数量，宁缺毋滥。

## 🤖 Grok Bot 是什么

Grok Bot 是 xAI 和 Cursor 在 2026-08-11 联合推出的 AI 队友（beta）。每个 bot 有名字、有岗位，共用一台一直开着的云电脑（浏览器、文件、终端都有）。你可以派活、让它定时跑 **Routine**、教它 **Skill**，也可以从 [模板市场](https://x.ai/bot/marketplace) 一键导入别人做好的 bot。

它和聊天助手 Grok、编码命令行 Grok Build 是三个不同的产品。

## 🚀 3 分钟上手

> 第一次用 Grok Bot？先看 **[快速上手](docs/quickstart.md)**：一个下午 5 步，从设安全底线到第一条不乱烧额度的 Routine。下面是已经上手的人的捷径。

1. **先补课**：读 [grokbot-field-notes](https://github.com/unicodef1wn/grokbot-field-notes) 的 `AGENTS.md` 和翻车记录，少走弯路
2. **要现成团队**：去 [botteams](https://github.com/ellelion/botteams) 挑一个 `installable` 团队，复制 installer prompt 粘进 Grok Bot
3. **要自己编排**：照 [作战室配方](examples/war-room.md) 拆角色、用文件交接、发布前加人工闸门
4. **找现成模板**：翻 [模板与目录](#-模板与目录)，几千个公开分享链接按岗位和质量分好了
5. **不想上云**：看 [自托管与平替](#-自托管与平替)

**先抄这 3 个配方**

| 配方 | 解决什么 | 适合谁 |
|---|---|---|
| [Routine 额度体检](examples/routine-budget.md) | 额度快烧光：先全停、再分级、逐条重开 | 开了很多 Routine 的人 |
| [作战室](examples/war-room.md) | 3–6 个 bot 只靠文件交接，发布前过人工闸门 | 想让多个 bot 分工的人 |
| [X 雷达](examples/x-radar.md) | 每天扫一轮 X，只推有信号的摘要，没信号不打扰 | 做内容、做出海的人 |

**图例**：每条＝`[名称](链接) - 短评。标签`；✅ 实测 · 🔍 已审；「配方：」是本仓自写，「模板：」可在 Grok Bot 里一键导入。

## 🆕 最近更新

- **10-21** 新增 [bot-team-playbook](https://github.com/doublesq97-ui/bot-team-playbook)（主管 + 专员的 bot 团队，8 套中文提示词）和中文手册 [GrokBotGuide](https://github.com/JeffShanCha/grokbotguide)；X 大 V 文章增至 117 篇
- **10-21** 新增 [Honcho 记忆插件](https://github.com/plastic-labs/honcho/tree/main/integrations/cursor)（让多个 bot 共享对你的长期记忆）
- **10-20** 新增 [dev-work-grok-bot-skill](https://github.com/FelixFangX/dev-work-grok-bot-skill)（带 20 条安全评测的研发助理 skill），新收 X 文章 Lee Robinson 的斯坦福常驻 agent 讲座

完整记录见 [README 提交历史](https://github.com/sit-in/awesome-grokbot-playbooks/commits/main/README.md)。

## 📚 目录

- [官方与 SDK](#-官方与-sdk)（5）- 官方文档、模板市场、SDK 和命令行
- [模板与目录](#-模板与目录)（10）- 模板库、bot 分享链接索引、案例站，找现成的先翻这里
- [技能与玩法](#-技能与玩法)（19）- skill、MCP、单个模板、可粘贴人设
- [多 Bot 团队](#-多-bot-团队)（19）- 作战室、总指挥、多 agent 协作
- [Routine 与摘要](#-routine-与摘要)（5）- 定时雷达、周报、额度管理
- [中文一人公司](#-中文一人公司)（4）- 出海客服、微信接入、中文配置
- [自托管与平替](#-自托管与平替)（11）- 不想上云、想用自己的模型
- [硬件](#-硬件)（2）- 给 bot 一个实体入口
- [学习资源](#-学习资源)（9）- 教程、手册、教程索引

---

## 🧰 官方与 SDK

- [xAI API Docs](https://docs.x.ai) - 官方 API 文档，模型列表、计费、工具调用都以这里为准。标签：`official` `api` `docs`
- [xai-org on GitHub](https://github.com/xai-org) - 官方开源组织，SDK 与开源模型权重入口。标签：`official` `sdk`
- [grokbot-sdk](https://github.com/adam91holt/grokbot-sdk) - 非官方 TypeScript SDK：连本机 Grok Bot 宿主的本地网关，读写名册、记忆和对话记录；宿主没开时也能直接读本地数据目录。要网关 token，只在自己机器上用。标签：`sdk` `typescript` `unofficial`
- [grok-bot-cli](https://github.com/ScriptedAlchemy/grok-bot-cli) - 非官方命令行工具 `gbot`：在终端建、改、删 bot 和群，发消息、拉对话记录、装卸 skill，还能给本机的 Claude Code 会话发消息。直接用 Grok Bot 桌面端已登录的会话，不用手动拷 token；删除类命令会作用到整个账号，先 `list` 再动手。标签：`cli` `unofficial` `skills`
- [Grok Bot 模板市场](https://x.ai/bot/marketplace) - 官方模板目录，按销售、工程、市场、设计、运营、个人分类，点 Add 导入到自己的 Grok Bot；本仓收的单个模板大多能在这里找到。标签：`official` `templates` `marketplace`

<sub>[⬆ 回到目录](#-目录)</sub>

## 📦 模板与目录

- [UseGrokBot](https://usegrokbot.com/) - 第三方案例导航站：按身份分类的模板、真实用例、Bot 团队搭法和热门文章排行，支持中英日。找灵感先翻这里。标签：`directory` `use-cases` `templates`
- [kydlikebtc/awesome-grokbot](https://github.com/kydlikebtc/awesome-grokbot) - 4600 多个 x.ai/bot 公开分享链接的索引，每天查链接是否存活，每行标注出处，有可搜索网页版和中文 README。目录 CC0、代码 MIT。社区分享质量参差，导入前自己看。标签：`awesome` `templates` `directory`
- [majiayu000/awesome-grok-bot](https://github.com/majiayu000/awesome-grok-bot) - 约 4800 个 x.ai/bot 分享链接，按质量分层上架，有可搜索网页版和双语 README；作者强调「不是提示词堆」。CC0。标签：`awesome` `templates` `directory`
- [awesome-grokbot-templates](https://github.com/cs68614-hash/awesome-grokbot-templates) - 社区模板目录，只收官方 x.ai/bot 分享链接，不转存 prompt，多语种；配套站点 grokbot-templates.com 10/19 访问报错，先看仓库。CC0。标签：`awesome` `templates` `directory`
- [mergisi/awesome-grokbot](https://github.com/mergisi/awesome-grokbot) - 50 多个可粘贴的 bot 人设和销售、工程、客服、市场、运营起步队：发一个链接给 Setup bot，它就把整队建好。CC0。标签：`profiles` `teams` `templates`
- [templatesgrokbot.com](https://github.com/templatesgrokbot/templatesgrokbot.com) - 3000+ 模板按岗位检索，可经 MCP 接入；量大质量参差，当灵感库用。标签：`templates` `catalog` `mcp`
- [botdirectory.ai](https://github.com/elie222/botdirectory.ai) - 开源 bot prompt 目录，Grok Bot、Rakazo 都能用，当灵感库翻。标签：`templates` `directory` `prompts`
- [Useful Bots](https://usefulbots.pages.dev/) - 面向创作者的免费 Grok Bot 模板目录，按视频、增长、发布等分类；个人站，质量没逐个抽检，当灵感翻。标签：`templates` `creators` `directory`
- [GrokBotDev](https://github.com/ZeroPointRepo/GrokBotDev) - grokbot.dev 的源码仓：由一组 bot 自己运营的玩法目录，Scouts 盯 X 找真实配置，Curator 决定收录，Builder 维护网站，每次改动都走 PR。插件、用例、组合包各有页面，另有 JSON API、RSS 和 MCP，可以让你的 bot 定时订阅。和本仓「AI 找料、人拍板」的思路相近，可以对照着看。代码 MIT、内容 CC BY 4.0。标签：`directory` `agent-run` `mcp`
- [GrokBot HQ](https://github.com/V-harshith/grokbothq) - grokbothq.xyz 的源码仓：4200 多个 Grok Bot 按分类列出，另有组合包、指南，以及和 Custom GPTs 等的对比。作者称每条上架前都人工打开测过，本仓没有逐条复核。代码 MIT、内容 CC BY 4.0。标签：`directory` `combos` `guides`

<sub>[⬆ 回到目录](#-目录)</sub>

## 🧩 技能与玩法

- [配方：Teach-a-Task](examples/teach-a-task.md) - 配合 Grok Bot 自带的 Teach a Task：演示前定边界，演示后整理成可审的技能卡，先干跑再放手。标签：`example` `skill` `teach-a-task`
- [grok-bot-templates](https://github.com/cobusgreyling/grok-bot-templates) - 模板工程化：规范 + Bot Ready 打分 + team / skill / routine 目录，写自己的配方前先对照它的结构。标签：`templates` `spec` `routine`
- [botskills](https://github.com/PramodDutta/botskills) - 可直接粘贴的 bot 设定，每条都声明「哪个动作必须先问你」，护栏写法值得抄。标签：`skills` `guardrails`
- [grokbot-for-gtm](https://github.com/bcharleson/grokbot-for-gtm) - 完整外呼 GTM 流程：建名单、补全、发信到处理回复，出海冷启动获客可参考。标签：`playbook` `gtm` `outbound`
- [grokbot-field-notes](https://github.com/unicodef1wn/grokbot-field-notes) - 非官方整理：xAI 团队 72 小时直播搭产品的规则、69 个角色、9 套岗位 playbook 和 40 条翻车记录，`AGENTS.md` 可直接拷。标签：`playbook` `field-notes` `agents-md`
- [grok-bot-jev](https://github.com/Bodila51/grok-bot-jev) - 在昂贵的调研/重试前加一层低成本分类决策，省调用量的思路值得抄；依赖第三方 TypeSafe 服务。标签：`skill` `cost` `decision-layer`
- [agent-cookie-sync](https://github.com/markfulton/agent-cookie-sync) - 把本机 Chrome 已登录站点交给云端 bot，不贴密码；等于把账号权限交出去，只给低敏账号用。标签：`chrome` `session` `security`
- [devspace](https://github.com/Waishnav/devspace) - 极简的 MCP 编码 harness，让 Grok Bot、Claude、ChatGPT 等通过 MCP 拿到读写代码的能力。标签：`mcp` `coding` `harness`
- [Bland 电话 MCP](https://docs.bland.ai/integrations/mcp/grok-bot) - 第三方官方文档：给 Grok Bot 接上 Bland 的 MCP，用专属号码打电话、发短信，出海外呼可用；bot 能在对话里自己付费开户，务必先设人工闸门。标签：`mcp` `voice` `outbound`
- [grokbot-imessage-skill](https://github.com/jeffhuber/grokbot-imessage-skill) - macOS 上让 Grok Bot 读、搜、分拣 iMessage，发信先预览再确认；要开完全磁盘访问权限，等于把全部聊天记录交给 bot，慎用。标签：`skill` `imessage` `macos`
- [grok-bot-skill](https://github.com/adamanz/grok-bot-skill) - 装进 Claude Code、Cursor、Codex 的技能：在终端里给 Grok Bot 队友发消息、新建 Bot，走本机已登录的 Grok Bot 桌面端。标签：`skill` `cli` `claude-code`
- [lauren-poteto-rules](https://github.com/unicodef1wn/lauren-poteto-rules) - 把工程原则做成 Grok Bot 私有技能：先看证据再下结论，在真实产品里验证，反复纠正的事写成固定约束；作者同 grokbot-field-notes。标签：`skill` `engineering` `rules`
- [web-access](https://github.com/eze-is/web-access) - 给本机 agent（Claude Code、Grok Bot 等）装联网能力：三层通道调度、浏览器 CDP、并行抓取，自动积累站点经验；作者同 eze-grokbot。README 声明 MIT，仓内没有 LICENSE 文件。标签：`skill` `browser` `cdp`
- [模板：Motion Director](https://x.ai/bot/MdpeJPD6eiY7YWUa9bfes) - 第三方模板，可一键导入：一句话（产品链接、主题或一首歌）出成片，逐镜头动画、按人声做口型、本机 GPU 放大，附分镜表和质检结果。页面没标价，导入即同意 bot 分享条款。标签：`template` `video` `creative`
- [locum](https://github.com/HarjjotSinghh/locum) - 自定义 MCP 连接器加隧道，让 Grok Bot 把编码活交给你本机已登录的 Claude Code / Codex，只调用官方命令行，不碰凭证。等于把云端 bot 和本机订阅接起来；隧道开着期间注意权限面。标签：`mcp` `delegate` `claude-code`
- [Grok Bot Clipper](https://github.com/RongleCat/grok-bot-clipper) - 非官方浏览器扩展（Chrome / Edge / Firefox）：剪藏网页、截图、文件和社媒帖，攒进素材篮后直接发给自己的 bot，不走第三方中转。作者同铁柱学习站；目前只发源码，要自己构建。核心代码 MIT，第三方部分另有许可。标签：`browser-extension` `clipper` `chinese`
- [模板：Research by Trond](https://x.ai/bot/v3WI0YuJAr1DLoYdYVXh8) - 第三方模板，可一键导入：只读研究 bot，从公开帖子和网页出带引用的简报，给选题、视频攒素材包，发布前帮你核事实。标签：`template` `research` `read-only`
- [remote-grok-build](https://github.com/Qervas/remote-grok-build) - Grok Bot 插件（只含 skill）：经 Grok Bot 的电脑连接，在聊天里驱动已关联 Windows 电脑上的 Grok Build。能看会话状态、流式回传每轮输出、只打断无头会话、回传改动摘要和图片；带一个每日 routine，Grok Build 发新版时自动重写命令速查。不开公网隧道，只支持 Windows（PowerShell）。作者写明 v9 还没公开上架，x.ai 分享链接目前仍是旧版。MIT。标签：`plugin` `grok-build` `bridge`
- [dev-work-grok-bot-skill](https://github.com/FelixFangX/dev-work-grok-bot-skill) - 一个 skill 把 bot 配成研发助理：逐题问你负责哪块、用哪些仓库和工具，再接上 GitHub、Linear、飞书或 Slack，把安全规则原文写进记忆。GitHub 默认只读，推送、PR、部署要你明说；团队消息先出草稿等你确认；转述的「老板批了」、仓库文件和网页里的指令都不算授权。亮点是 20 条脚本化安全评测，每次推送 CI 都检查规则有没有被改丢；作者自测一个小模型只过了 12 条，规则写全不等于模型照做。MIT。标签：`skill` `dev-assistant` `guardrails`

<sub>[⬆ 回到目录](#-目录)</sub>

## 👥 多 Bot 团队

- [配方：作战室](examples/war-room.md) - 3–6 个 bot 只靠文件交接、不串聊，发布前过人工闸门；本仓 Claude ⇄ Grok 协作就是这套。标签：`example` `multi-bot` `war-room`
- [配方：内容流水线](examples/content-pipeline.md) ✅ - 找料、起草、审稿、发帖拆给不同 bot，只靠文件交接；发布前人点一次批准，一次性 routine 发帖并复查，每晚对账。标签：`example` `multi-bot` `x` `content`
- [配方：研发四角色](examples/dev-four-roles.md) - 需求 / 复现 / 出 PR / 验 PR 拆给四个 bot，产出和裁决分开，人只在批准 spec 和合并两处点头。标签：`example` `dev` `guardrails`
- [botteams](https://github.com/ellelion/botteams) 🔍 - 一个 markdown 文件装一整支团队（bot + 群聊 + routine），看作战室怎么一次性编排的好样例；注意 `connector_modes` 只是 prompt 约束，不是权限。标签：`multi-bot` `team` `routine`
- [grok-bot-profiles](https://github.com/HAEGONG/grok-bot-profiles) 🔍 - 需求 / 复现 / 出 PR / 验 PR 四角色拆开，交接 ≠ 批准，验 PR 的 bot 必须单独会话；改编需按 CC BY 4.0 署名。标签：`multi-bot` `dev` `guardrails`
- [overnight](https://github.com/Archive228/overnight) - 六 bot 短视频生产线，素材带出处，发布前必须人审，内容号可参考它的人工闸门设计。标签：`multi-bot` `content` `human-in-loop`
- [grokbot-gtm-team](https://github.com/timscheuerai/grokbot-gtm-team) - 13 个 GTM bot + 规则 + 一句话建队 prompt，Grok Bot 编排、Claude Code/Codex 干活。标签：`multi-bot` `gtm` `claude-code`
- [AgentPeerChat](https://github.com/AgenticsWorks/AgentPeerChat) - 自托管的 agent 间消息通道，一键部署到 Cloudflare，可把 Grok Bot 和其他 agent 拉进同一频道。标签：`multi-bot` `messaging` `cloudflare`
- [noodle](https://github.com/pdparchitect/noodle) - Mac / iOS 多 agent 群聊客户端，复用已有订阅（Codex、Claude Code、Grok Build 等），本地组队的轻量方案。标签：`multi-bot` `macos` `desktop`
- [orca](https://github.com/stablyai/orca) - 管一整队 agent（Grok Bot、Codex 等）的工作台，桌面 / 手机 / 远程都能用，跑在你自己的订阅上；生态里体量最大的项目。标签：`multi-bot` `fleet` `desktop`
- [agentrove](https://github.com/Mng-dev-ai/agentrove) - 自托管编码工作区，把 Claude Code、Codex、Cursor、Grok 等 agent 放在一起编排，带 persona 和多 agent 工作流。标签：`multi-bot` `self-hosted` `coding`
- [reason-network](https://github.com/reason-machines/reason-network) - 每台电脑一个小守护进程，点对点互联，直连不通时走加密中继，让 Claude Code、Codex、Cursor 等编码 agent 互相发消息派活。Grok Bot 不在自动接入列表里，要在云电脑里装命令行，用 `listen` / `send` 收发；同名的 Reason 插件是把任务交给 Reason 云端 agent，和这个网络是两回事。本仓 2026-10-18 试连 Grok Bot 云电脑和本机，没打通，原因未定。引擎 MIT 或 Apache-2.0 双许可，Reason CLI 不开源。标签：`multi-bot` `p2p` `claude-code`
- [模板：Chief of Operations](https://x.ai/bot/HQh9l4duDHNmhCuSW_pn-) - 第三方模板，可一键导入：管团队共享规则，登记所有 bot 和 routine，定期做安全审计，备好事故预案，改动都要人批。和[额度体检配方](examples/routine-budget.md)配着用。标签：`template` `governance` `audit`
- [模板：T3 Code Bridge](https://x.ai/bot/_5NG_WsrOdQs2jtUhZeQH) - 第三方模板，可一键导入：让 Grok Bot 开启、指挥并盯着 T3 Code 的编码线程，完成、失败或需要输入时通知你。标签：`template` `coding` `t3-code`
- [openmeld](https://github.com/amplifthq/openmeld) - 开源的人机协作系统：人和 Codex、Claude Code、Grok Bot、Cursor 等 agent 共享上下文、分派任务、并行干活，桌面端可用；同类里星标最高之一，README 有和同类产品的许可对比。标签：`multi-agent` `collaboration` `desktop`
- [模板：Fleet Lead](https://x.ai/bot/mOunuXA9lKjg8sWImIzgy) - 第三方模板，可一键导入：当总指挥盯着其他 bot，只上报做完的活，对外动作一律等你批准，还带共享浏览器的排队锁和产出清理。标签：`template` `multi-bot` `approval`
- [a2a-bridge](https://github.com/Rladmsrl/a2a-bridge) - 把一个靠 webhook 触发的 Grok Bot routine 包装成标准 A2A（Agent2Agent）服务：外部 agent 按 A2A 协议发任务，bridge 转成 webhook 叫醒你的 routine，bot 再把进度和结果回调回来；支持流式、多轮追问和任务状态持久化。等于让别人的 agent 能正式「给你的 bot 派活」。要自己有服务器和域名，接口对公网开放，API key 和回调签名务必配好。MIT。标签：`a2a` `webhook` `interop`
- [grokbot-desk](https://github.com/realspqrk/grokbot-desk) - 给 bot 用的「老板桌」：bot 跑一条命令交上表格、图表、待决策项或待发帖子，本机弹窗让你批准、驳回或选项，结果回传给 bot；多份报告排成收件箱。把「对外动作先问人」做成了可视化审批台。Windows / macOS，beta 版，界面默认德语，设 `RS_LANG=en` 切英文。MIT。标签：`approval` `human-in-the-loop` `dashboard`
- [Honcho 记忆插件](https://github.com/plastic-labs/honcho/tree/main/integrations/cursor) - 给 Grok Bot 加跨 bot 的长期记忆：在「连接应用」里搜 Honcho 添加，对 bot 说「Set up Honcho」，它会弹登录卡片并跑初始化 skill。整个账号只装一次，每个 bot 各记各的，「你」在所有 bot 里是同一个人，偏好和进度能在 bot 之间续上。记忆存在 Honcho 托管的 MCP 服务上，等于把对话内容交给第三方保存，敏感内容别往里放。插件目录是 MIT，Honcho 主仓是 AGPL-3.0。标签：`memory` `mcp` `plugin`
- [bot-team-playbook](https://github.com/doublesq97-ui/bot-team-playbook) - 「一个人一支 bot 团队」：1 个主管 bot 加 3–4 个专员，给 8 类人设各配好一队，35 段提示词按同一个 7 段结构写好，可直接粘贴。主管拆活、写验收标准，专员把产出存进共享文件夹再回报路径，主管逐条验收后才交给你；另附交接和汇报的消息模板，以及一个按需设计团队的 skill。提示词是中文，README 有中英两版。MIT。标签：`multi-bot` `supervisor` `prompts`

<sub>[⬆ 回到目录](#-目录)</sub>

## ⏰ Routine 与摘要

- [配方：竞品雷达 routine](examples/competitor-radar.md) - 定时抓竞品公开页面，只推送有实质变化的部分；重点在先过滤时间戳等噪音。标签：`example` `routine` `radar`
- [配方：周报 routine](examples/weekly-review.md) - 每周五从 GitHub、文档、日历收痕迹出初稿，对照上周计划，每条必须带链接，人改 10 分钟就发。标签：`example` `routine` `weekly`
- [配方：X 雷达](examples/x-radar.md) - 每天扫一轮 X 公开帖，只推有实质信号的摘要，没信号就不打扰；互动一律人来。标签：`example` `routine` `x`
- [配方：Routine 额度体检](examples/routine-budget.md) - 额度快烧光时先全部暂停，再让首席 Bot 给每条 Routine 分级，人确认后逐条重开；高频 Routine 没有新内容就静默。标签：`example` `routine` `budget`
- [模板：X Post Tracker（Karol）](https://x.ai/bot/LrOzcsX5ITCY0SfXLmhJn) - 第三方模板，可一键导入：盯自己 X 帖子的浏览和互动，暴涨或到里程碑时提醒，每天一份摘要加下一步建议；说明里写明不代你发帖，导入前仍看一眼权限。标签：`template` `x` `digest`

<sub>[⬆ 回到目录](#-目录)</sub>

## 💼 中文一人公司

- [配方：一人三岗](examples/one-person-three-roles.md) - 客服 + 内容 + 调研三个 bot 用文件交接，人每天只审 30 分钟；虚构示例，可直接改。标签：`example` `solo-founder` `multi-bot`
- [配方：出海客服](examples/outbound-support.md) - 多语言工单先脱敏、再分流、只出草稿；付款、安全、法律类一律转人工，bot 不直接发信。标签：`example` `support` `i18n`
- [eze-grokbot](https://github.com/eze-is/eze-grokbot) - 中文作者公开的多 bot 配置，每个 bot 一个文件夹，看真人怎么拆角色。未声明 License，只参考结构。标签：`chinese` `profiles` `config`
- [grok-bot-wechat](https://github.com/bogao6769-netizen/grok-bot-wechat) - 微信消息触发 Grok Bot 的 webhook Routine，本地转发器把回复送回微信；只是配方不含服务，项目很新，想让国内用户在微信里找 bot 的可参考。标签：`chinese` `wechat` `routine`

<sub>[⬆ 回到目录](#-目录)</sub>

## 🏠 自托管与平替

- [XinyunOpenBot](https://github.com/dongpen-max/XinyunOpenBot) - 中文优先的开源替代，默认简中，支持 OpenAI 兼容接口与 API 中转站，国内网络环境先看它。标签：`self-hosted` `chinese` `desktop`
- [OpenGrokBot](https://github.com/wolfqing/OpenGrokBot) - 基于 OpenClaw 的自托管方案，每个 bot 一台自己的机器、模型自带，想把数据留在本地时的首选参考。标签：`self-hosted` `openclaw` `byo-model`
- [open-grok-bot](https://github.com/Anil-matcha/open-grok-bot) - FastAPI + Next.js 的本地优先工作台，动作默认拒绝、需审批并留审计记录，适合对权限敏感的场景。标签：`self-hosted` `governance` `audit`
- [xiryn](https://github.com/SouravBeraAkaSpeed/xiryn) - 每个 agent 一台 Docker 里的 Linux 桌面，模型自带 key、加密 vault、Telegram 遥控，最接近「自己的 Grok Bot」。标签：`self-hosted` `docker` `telegram`
- [DeepSeekBot](https://github.com/BotHarness/DeepSeekBot) - 基于 DeepSeek Harness 的开源平替，多 bot + 长期记忆 + 权限，中英双语 README，国内模型首选参考。标签：`self-hosted` `chinese` `deepseek`
- [lorca](https://github.com/egoist/lorca) - 「一个人的 Telegram」：端到端加密的 agent 消息面，偏个人通讯而非任务编排。GPL-3.0。标签：`self-hosted` `messaging` `e2ee`
- [guilds](https://github.com/CigaleAI/guilds) - 团队/公会形态的开源替代，早期项目，适合关注而非直接上生产。AGPL-3.0。标签：`self-hosted` `multi-bot`
- [rakazo](https://github.com/elie222/rakazo) - 开源自托管的 Grok Bot 平替，模型和沙盒都自己选，建好 bot 后像在 Grok Bot 里一样聊天管理。标签：`self-hosted` `byo-model` `alternative`
- [Codync](https://github.com/leepokai/Codync) - 开源平替：把本机的 Claude Code、Codex、Cursor、Grok Build 等 40 多种编码 agent 变成可派活的 bot，手机和电脑都能发消息。标签：`self-hosted` `multi-agent` `acp`
- [openbot（nightly-labs）](https://github.com/nightly-labs/openbot) - 本地优先的桌面工作区：Codex、Claude、Grok 各有工作区和任务队列，能从 Grok Bot 导出 agent 迁过来。和 CopilotKit/OpenBot 不是同一个项目；许可证是 PolyForm 非商用，商用要另外授权。标签：`self-hosted` `desktop` `noncommercial`
- [OpenMausBot](https://github.com/milind-soni/OpenMausBot) - 开源 Grok Bot 平替，做成聊天应用：每个 bot 底层跑你本机的 Claude、Codex 或 Grok 命令行，沿用现有登录和订阅，数据留在本地；Mac、Windows、Ubuntu 都有安装包。同类里星标最高。Apache-2.0。标签：`self-hosted` `local-first` `alternative`

<sub>[⬆ 回到目录](#-目录)</sub>

## 🔌 硬件

- [groki-bot](https://github.com/JosssphZhou/groki-bot) - M5Stack CoreS3 桌面机器人：固件 + 电脑端语音/MCP 网关，能把任务交接给 Grok Bot，想让 bot 有个实体入口时参考。标签：`hardware` `mcp` `voice`
- [grok-gadgets](https://github.com/adidshaft/grok-gadgets) - 把硬件接到 Grok Bot 的 SDK 和工具，可先用模拟器，再上 ESP32-S3 OLED 套件；作者标注 alpha，玩票为主。标签：`hardware` `esp32` `sdk`

<sub>[⬆ 回到目录](#-目录)</sub>

## 📖 学习资源

- [awesome-grok-bot](https://github.com/ZeroPointRepo/awesome-grok-bot) - 英文生态导航，找现成 skill 和工具先翻这里，别自己造轮子。标签：`awesome` `learning`
- [CNR Grok Bot 指南](https://cnrcode.com/guides/) - 英文入门四篇：功能与套餐、Routine 和 Skill 设置、额度怎么省、5 套免费模板；咨询公司官网，带营销成分。标签：`guide` `routine` `usage`
- [铁柱 Grok Bot 学习站](https://bot.tiezhu.si/) - 中文学习站，非 xAI 官方：从安装、派活、Routine 到多 Bot 协作和企业部署分四部分，附自媒体运营、仓库值守等案例；文末导流公众号和社群。标签：`chinese` `guide` `learning`
- [Grok Bot 橙皮书](https://github.com/KinGao294/grok-bot-orange-book) - 中文入门到进阶手册，约 1.6 万字：多 Bot 协作、Routine、省额度和自动化，有 PDF 和 Markdown 两版，作者建议整本喂给 bot 当上下文。写于上线头两周，细节动手前对照官方。README 声明 CC BY-NC-SA 4.0，仅限非商用。标签：`chinese` `guide` `book`
- [GrokBotGuide](https://github.com/JeffShanCha/grokbotguide) - 社区共建的 Grok Bot 实战手册，在线版 grokbotguide.ai，中英两版：学习路线、快速上手、Skill 与 Routine 进阶、角色卡和「Grok Bot × 工具」实战案例，每篇标注来源、核对日期和内容分级。非官方。代码 MIT、内容 CC BY-SA 4.0。标签：`chinese` `guide` `learning`
- [sitin 的 Grok Bot 教程索引](docs/sitin-tutorials.md) - 本仓作者的「Grok Bot 实战」连载与 X 教程，按入门 / 作战室 / Routine / Skills / 一人公司分类，只收公开链接（作者相关）。标签：`chinese` `tutorials` `author`
- [社区 Grok Bot 教程精选](docs/community-tutorials.md) - 25 篇其他博主的教程和长文，以 X 为主，也收博客、掘金、V2EX、B 站等平台上能照着做的；按入门、作战室、Routine 与额度、Skills、一人公司、合集分类；每条都核过存活和日期。标签：`chinese` `tutorials` `community`
- [X 大 V 的 Grok Bot 文章精选](docs/x-articles.md) - 117 篇 X 长文和串帖，中英文都有，按入门、作战室、Routine 与额度、Skills、一人公司分类；只收有真实互动的教程和配置分享，帖内数字为作者自述。标签：`tutorials` `x` `community`
- [配方模板](examples/_template.md) - 投稿配方前先照这个格式写：场景 / 输入 / 步骤 / prompt / 产出 / 坑。标签：`template` `learning`

<sub>[⬆ 回到目录](#-目录)</sub>

---

## ⚠️ 安全提醒

- 导入模板、装 skill、接 MCP，都等于**把权限交给 bot**。模板页写着「可能代你行动」时，先看清它能碰哪些账号
- 涉及 Cookie 同步、完全磁盘访问、SSH、隧道的条目，短评里都标了风险；只给低敏账号用，用完关掉
- 别把 key、token、账单截图贴进 prompt 或公开仓库
- 社区分享的模板和 prompt 质量参差，本仓只核实存在、许可和相关性，**不代表安全审计**

## 🤝 参与贡献

- **推荐条目**：开一个[推荐条目 issue](https://github.com/sit-in/awesome-grokbot-playbooks/issues/new/choose)，附链接和一句理由
- **投稿配方**：照 [配方模板](examples/_template.md) 写，提 PR；收录门槛和脱敏规则见 [CONTRIBUTING.md](CONTRIBUTING.md)
- **认领实测**：配方大多还没真机跑过。认领一个[实测 issue](https://github.com/sit-in/awesome-grokbot-playbooks/issues?q=is%3Aissue+label%3Aneeds-test)，在你的 Grok Bot 里跑通，配方标 ✅ 并署你的名
- **报告失效**：链接挂了或项目归档了，开「报告失效」issue

感谢每一位推荐条目、投稿配方和认领实测的朋友：

<a href="https://github.com/sit-in/awesome-grokbot-playbooks/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=sit-in/awesome-grokbot-playbooks" alt="Contributors">
</a>

## 📈 Star 趋势

觉得有用就点个 ⭐，新配方和新条目会持续更新。

<a href="https://star-history.com/#sit-in/awesome-grokbot-playbooks&Date">
  <img src="https://api.star-history.com/svg?repos=sit-in/awesome-grokbot-playbooks&type=Date" alt="Star History" width="600">
</a>

## 声明

本仓是社区整理，**不是** Grok Bot 客户端，与 xAI、Cursor 没有任何关联，也未获其认可。Grok、Grok Bot 等名称归各自所有者。条目短评是编者观点，用之前请以官方说明为准。

作者 X：[@sitinme](https://x.com/sitinme)。作者的其他项目：[hiapi.ai](https://hiapi.ai)，面向开发者与 Agent 的图片、视频、音频生成 API 聚合网关。

## License

[MIT](LICENSE) © sitin
