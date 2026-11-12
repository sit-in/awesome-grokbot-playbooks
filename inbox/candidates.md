# T1 X 雷达候选（待 Claude T5 核实）

- **日期**：2026-10-17（Asia/Shanghai）
- **窗口**：约近 30 天（2026-09-17 → 2026-10-17）
- **负责**：Grok
- **方法**：X `search_posts_all`（多查询）+ `gh search repos` / Web 交叉核验
- **红线**：无 API key / 营收 / 内部路径 / 隐私；未 star / fork
- **已在 README、不重复列为「新」**：ZeroPointRepo/awesome-grok-bot、XinyunOpenBot、OpenGrokBot、open-grok-bot、grok-bot-templates（cobusgreyling）、botskills、grokbot-for-gtm（bcharleson）、botteams、grok-bot-profiles、overnight、hiapi.ai

---

## 推荐入清单（优先）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | 来源 |
|------|------|----------|----------------|------|------|
| grokbot-field-notes | https://github.com/unicodef1wn/grokbot-field-notes | xAI 团队 72h 直播里的规则 / playbook / 角色 / 失败日志；可直接丢 AGENTS.md。~603★，2026-09-18 | Skills & Playbooks | `playbook` `field-notes` `agents-md` | GitHub（星标交叉）；X 上同类「官方方法」帖多但多无仓 |
| lorca | https://github.com/egoist/lorca | 单人端到端加密 + agent 消息面，对标 Grok Bot / Muse / Dots。~310★，2026-09-18 | Self-hosted bots | `self-hosted` `messaging` `e2ee` | GitHub |
| xiryn | https://github.com/SouravBeraAkaSpeed/xiryn | 自托管个人 agent：每 agent 一台 Docker Linux 桌面，任意模型 + 加密 vault + Telegram。~185★，2026-10-11 | Self-hosted bots | `self-hosted` `docker` `telegram` | GitHub |
| noodle | https://github.com/pdparchitect/noodle | macOS 多 agent 桌面（Swift），topic 含 grokbot / hermes / muse。~175★，2026-09-04 | Multi-bot teams | `multi-bot` `macos` `desktop` | GitHub |
| DeepSeekBot | https://github.com/BotHarness/DeepSeekBot | 基于 DeepSeek Harness 的开源 GrokBot 平替：多 bot、记忆、权限、插件；中文 README。~127★，2026-09-16 | Self-hosted bots / Chinese solo-founder | `self-hosted` `chinese` `multi-bot` `deepseek` | GitHub + X 讨论（DeepSeekBot vs Rakazo） |
| AgentPeerChat | https://github.com/AgenticsWorks/AgentPeerChat | 免费自托管 agent 间消息，可连 Grok Bot / Muse / Dots。~124★，2026-10-02 | Multi-bot teams | `multi-bot` `messaging` `self-hosted` | GitHub |
| grok-bot-jev | https://github.com/Bodila51/grok-bot-jev | 把 TypeSafe Jev 接到 Grok Bot 作便宜决策层（usage gate + skill 模板）。~112★，2026-09-19 | Skills & Playbooks | `skill` `decision-layer` `cost` | GitHub |
| agent-cookie-sync | https://github.com/markfulton/agent-cookie-sync | Chrome MV3 + native host，把已登录站点会话给 Grok Bot / Muse，不贴密码。~88★，2026-09-23 | Skills & Playbooks | `chrome` `session` `playbook` | GitHub；与 X 上「本机 Chrome 驱动云端 Bot」玩法同向（@fankaishuoai 2026-10-17） |
| groki-bot | https://github.com/JosssphZhou/groki-bot | M5Stack 桌面机器人：固件 + 语音/MCP 网关，可交接给 Grok Bot。~65★，2026-09-23 | Learning / Official-adjacent hardware | `hardware` `mcp` `iot` | GitHub |
| guilds | https://github.com/CigaleAI/guilds | 开源 Grok bots 替代（团队/公会形态）。~61★，2026-10-09 | Self-hosted bots | `self-hosted` `multi-bot` | GitHub |
| templatesgrokbot.com | https://github.com/templatesgrokbot/templatesgrokbot.com | 3000+ 模板库 + MCP 接 catalog；按岗位搜。~34★，2026-09-17 | Skills & Playbooks | `templates` `marketplace` `mcp` | GitHub |
| grok-bots-for-deepseek-harness | https://github.com/brokep/grok-bots-for-deepseek-harness | 把 90 个 Grok Bot marketplace agent 打成 DeepSeek Harness 插件包。~29★，2026-10-15 | Skills & Playbooks | `templates` `deepseek` `port` | GitHub |
| grokbot-gtm-team | https://github.com/timscheuerai/grokbot-gtm-team | 13 个 GTM bot + 规则 + 一键建队 prompt；Grok 编排、Claude Code/Codex 干活。~29★，2026-10-14 | Multi-bot teams / Chinese solo-founder 可对照 | `gtm` `multi-bot` `claude-code` | GitHub；X 上大量「Claude Code 指挥 Grok Bot」玩法互相印证 |
| smfworks/grok-bot-templates | https://github.com/smfworks/grok-bot-templates | Michael Gannotti 合集：Video Studio / Builder Prime 等，官方 Add to Grok Bot 链。~3★，2026-10-09 | Skills & Playbooks | `templates` `marketplace` | **X**（@MichaelGannotti 2026-10-17）+ GitHub |
| grok-gadgets | https://github.com/adidshaft/grok-gadgets | 硬件 ↔ Grok Bot SDK/模拟器（ESP32-S3 OLED），MCP 网关。~2★，2026-10-05 | Learning | `hardware` `mcp` `esp32` | **X**（作者 @adidshaft + @grok 回复）+ GitHub |
| awesome-grok-bot-plugins | https://github.com/rdmgator12/awesome-grok-bot-plugins | 219 条 in-app Plugins 目录快照（2026-08-12），按类整理。 | Learning | `awesome` `plugins` `catalog` | **X** 提及（旧链）+ GitHub 核验 |
| eze-grokbot | https://github.com/eze-is/eze-grokbot | 公开的多 Bot 配置（每 Bot 一文件夹），中文向可抄结构。~15★，2026-10-10 | Chinese solo-founder / Multi-bot teams | `chinese` `profiles` `config` | GitHub |

---

## 玩法 / 文章向（无独立仓或仓弱，可作 Learning 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Claude Code ↔ Grok Bot 协作 | 例：https://x.com/heyrobinai/status/2111440703784169885 ；中文：https://x.com/LawrenceW_Zen/status/2110993612838441143 | 云端 Bot 装 Claude Code / 本机 Claude 编排 Bot；与本仓「Grok↔Claude」协作同构，值得 Learning 一条。 | Learning | **X**（多帖，2026-10-16–17） |
| 本机 Chrome 驱动云端 Grok Bot | https://x.com/fankaishuoai/status/2111484271198343195 | 本地 Agent 打开已登录 Chrome，用 Bot URL 对话/操控云端 Bot。 | Learning / Skills | **X**（2026-10-17） |
| How to Build Anything with Grok Bot | https://x.com/Av1dlive/status/2111125320590074017 | 高曝光「全课」文章卡（~62k 展示），可作入门 Learning，需 Claude 抽可复用步骤、去营销水。 | Learning | **X**（2026-10-16） |
| 爆款监控 Skill | https://x.com/aehyok/status/2109817788198158347 | 中文向：用 Grok Bot 从零做监控 Skill（高互动）。核实后或可摘要进 Routines。 | Routines & Digests | **X**（2026-10-13） |
| Plugin marketplace 开放提交 | https://x.com/AGTPinsights/status/2111456279545917951 | 开发者可提交 plugin/MCP 进 Grok Bot 市场——生态信号，不必单列仓。 | Official & SDK（备注） | **X**（2026-10-17） |

---

## 已有条目的更新信号（勿当新条目，供 T5 决定是否加一句）

| 条目 | 信号 | 来源 |
|------|------|------|
| OpenGrokBot | X 称 2.4：网页/Feed/邮件/日历触发自启；PDF/Excel 读写 | **X** @BuilderGuest 2026-10-17 |
| grok-bot-templates / botskills 等 | X 上「20 templates / SpaceXAI templates」营销帖极多，多数指向已有或 marketplace，勿重复堆 | **X** |

---

## Maybe / Skip（弱、空仓、归档、或偏题）

| 名称 | 链接 | 原因 | 来源 |
|------|------|------|------|
| b-nnett/grok-bot-0.18-reconstructed | https://github.com/b-nnett/grok-bot-0.18-reconstructed | ~3.5k★ 但 **已归档**；逆向研究向，合规/伦理需 Claude 把关，不宜当 playbook 主推 | GitHub / Web |
| tyonger-stack/GrokNode | https://github.com/tyonger-stack/GrokNode | 0.18 中文重建，研究向、星少；同归档仓风险 | GitHub |
| CogineBot | https://github.com/cogine-ai/CogineBot | WIP、8★；可观察 | GitHub + X 对比讨论 |
| milo / ngai-platform / OpenEveryAgentIDE / fakkelbot / liquid-gold-grok-bot | 各 GitHub | 描述对口但 0★、过新或空，先观察 | GitHub |
| AgwaB/grok-bot-audit | https://github.com/AgwaB/grok-bot-audit | 当日新建 fleet audit plugin，可跟 | GitHub |
| FreeToken-Bots 类 | X 文章 | 额度/免费模型接入，易踩 ToS；跳过 | **X** |
| 营收/agency「$1M MRR」类长文 | 多 X article | 营销向，不符合本仓宁缺毋滥 | **X** |
| 某个人参考仓 | — | 用户明确：仅自用参考，**不进 README / 不写本候选主表** | 约束 |

---

## 搜索备注 / 限制

1. X API：`since:` 运算符会被剥掉，已用 `start_time`/`end_time`；单次 `max_results` 上限 25，多查询分页未穷尽全部帖。
2. 大量高互动帖是 **X Article**（t.co → x.com/i/article/…），无 GitHub 链；只挑可复用玩法进「文章向」。
3. `gh search` 按 created≥2026-09-01 / stars 排序补漏；未对每个仓做 clone 实测（留给 T2/T5）。
4. 配额：本日 X reads 仍充足；无 fatal 错误。部分 WebFetch 对 X article 会 404，以搜索摘要 + `gh repo view` 为准。

---

## 给 Claude（T5）的合并建议

1. 优先核实 **field-notes / lorca / xiryn / noodle / DeepSeekBot / agent-cookie-sync / grokbot-gtm-team / smfworks templates**。
2. Learning 节可加一条「Claude Code ↔ Grok Bot」并链 1–2 篇高质量 X 帖（去营销话）。
3. OpenGrokBot 只更新短评一句（2.4 触发），不要新开条目。
4. 勿把某个人参考仓、归档逆向仓、营收文写进 README。

---

## 夜班 2026-10-18 ~00:15（Asia/Shanghai）

- **窗口**：约 2026-10-14 → 10-17（UTC）近几日 X + `gh search`
- **负责**：Grok 夜班半小时雷达 #1
- **方法**：X `search_posts_all`（playbook/skill/routine/multi-bot + `url:github.com`）+ `gh api`/`gh search repos`
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README
- **去重**：相对当前 README + 上文 T1 表；个人参考仓不点名、不进公开主表

### 推荐入清单（夜班新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| orca | https://github.com/stablyai/orca | fleet of agents（Grok Bot / Codex 等），桌面+手机+远程 runtime，用自有订阅跑编码 agent。群雷达【适合 Awesome】 | Multi-bot teams | `multi-bot` `fleet` `desktop` | ~95k / MIT | GitHub 雷达交叉 + gh |
| devspace | https://github.com/Waishnav/devspace | 轻量 MCP harness，描述点名 Grok Bot / Hermes / OpenClaw。群雷达【适合 Awesome】 | Self-hosted bots / Skills | `mcp` `harness` `self-hosted` | ~5.3k / MIT | GitHub 雷达交叉 + gh |
| agentrove | https://github.com/Mng-dev-ai/agentrove | 自托管多 agent 工作区，点名 Grok + Claude Code/Codex；星少但方向贴。群雷达【适合 Awesome】 | Multi-bot teams | `multi-bot` `workspace` `self-hosted` | ~338 / Apache-2.0 | GitHub 雷达交叉 + gh |
| last30days-skill | https://github.com/mvanhorn/last30days-skill | 跨 Reddit/X/YouTube/HN 的研究 skill；X 上被当成 Grok Bot「工程队」组件之一 | Skills & Playbooks | `skill` `research` `digest` | ~64k / MIT | **X** @0xCarnagee + gh |
| browserpaw | https://github.com/GoldenLoaf24h/browserpaw | 本机 Chrome 给 agent 用、不丢登录态；作者用 Cursor+Grok Bot 推进。与 cookie-sync 同向，可对照 | Skills & Playbooks | `chrome` `browser` `security` | ~35 / AGPL-3.0 | **X** + gh |
| iwork_mcp | https://github.com/reichenbach/iwork_mcp | 117 个 Numbers/Pages/Keynote 工具，已做成 Grok Bot plugin 提市场 | Skills & Playbooks | `mcp` `macos` `iwork` | ~37 / 无 License | **X** @realcoachmatt23 + gh |
| grokbot-notch | https://github.com/robzilla1738/grokbot-notch | macOS Notch 伴侣：桌面 Grok Bot + 实时语音；硬件/桌面入口向 | Hardware | `macos` `voice` `desktop` | ~7 / MIT | gh search（created≥10-16） |
| grokbot-hermes-bridge | https://github.com/jamesonedge/grokbot-hermes-bridge | Tailscale + webhook：Grok Bot ↔ 自托管 Hermes，额度耗尽时的备份编排 | Skills / Multi-bot | `bridge` `hermes` `webhook` | ~3 / 无 License | **X** @JamesOnEdge |
| twilio-grok-voice-bridge | https://github.com/jeffhuber/twilio-grok-voice-bridge | Twilio Media Streams ↔ Grok Voice，给 Bot 外呼能力 | Skills & Playbooks | `voice` `twilio` `outbound` | ~2 / MIT | **X** @jhuber |
| Claude2GrokBot | https://github.com/Parsiffall1/Claude2GrokBot | Claude 把任务交给 Grok Bot（可唤醒）并回传；CF Workers + Durable Objects MCP | Skills / Multi-bot | `claude` `bridge` `mcp` | ~1 / MIT | gh search（当日新建） |
| grok-bot-wechat | https://github.com/bogao6769-netizen/grok-bot-wechat | 中文：微信 ClawBot → Grok Bot（webhook Routine + 本地转发）Cursor 配方 | Chinese solo-founder | `chinese` `wechat` `routine` | ~1 / MIT | gh search |
| grok-cc | https://github.com/codebyelvis/grok-cc | 经 Orca 把本机 Mac 开发任务委派给 Grok Bot 上的 Claude Code | Skills / Multi-bot | `claude-code` `orca` `mac` | ~2 / 未明确 | gh search |

### 玩法 / 产品信号（无强仓或仓弱，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 邮箱 +别名分流 Routine | https://x.com/JJKKKK92/status/2111435631981195618 ；英文说明例 https://x.com/grokbotusecases/status/2110514228193079634 | `+invoice` / `+alerts` / `+reading` 各触发一条流水线；产品新能力，值得 Routines 一条短评 | Routines & Digests | **X**（多帖，2026-10-14–17） |
| Bot Library 找旧文件 | https://x.com/SuddenlyJon/status/2111490547017744886 | 信息栏 Library：Today / This week / Older 分组找回几天前文件——实用小技巧 | Learning | **X** 2026-10-17 |
| pstack / poteto-mode | Cursor/Grok Bot 插件生态；移植例 https://github.com/backnotprop/pstack 、https://github.com/michael-denyer/pstack-claude | SpaceXAI 工程师 Lauren Tan 的工程 skill 栈；Grok Bot 可装插件。官方仓名易变，先 Learning 链移植仓+使用说明，勿当「官方仓」 | Skills & Playbooks / Learning | **X** 高热 + gh |
| X 必读合集 24 篇 | https://x.com/0xlangeai/status/2111396742264742034 | 中文向 9 类 24 篇高阅读合集（~24k 展示）；可作 Learning 索引，需抽可复用步骤、去营销 | Learning | **X** 2026-10-17 |
| Bots 进 grok.com / App | https://x.com/raul_g/status/2111490586087756027 | Bot 能力进主 App，与独立 Grok Bot App 能力接近——产品形态信号 | Official（备注） | **X** 2026-10-17 |
| 1 路由 + 4 专家 | https://x.com/YAYACA11/status/2111353772131934334 | webhook/Slack/GitHub/邮件打到同一路由；强调「没活闭嘴」控成本——与 war-room 同构 | Multi-bot / Learning | **X** 2026-10-17 |
| Claude↔Grok 桥（续） | 例：https://x.com/danmercede/status/2110769669456187797 ；中文 https://x.com/LawrenceW_Zen/status/2110993612838441143 | webhook 400 / 无官方 API，社区用 Python 桥或 4 次 API 调用；与本仓协作同构。上轮已列，夜班仅补新帖 | Learning | **X** |

### Maybe / Skip（夜班）

| 名称 | 链接 | 原因 |
|------|------|------|
| AgwaB/grok-bot-audit | https://github.com/AgwaB/grok-bot-audit | 当日新建 0★ fleet audit plugin，续观（T1 Maybe 已有） |
| brokep/grok-bots-for-deepseek-harness | 同上文 | Claude T5 已拒：无 License + marketplace 重打包版权疑 |
| h100envy/crawl-hive | — | memecoin 向，偏题 |
| danielfebrero/Grok-Bot-app（MCP/box monitor） | — | 0★、无 License、偏逆向监控，合规风险 |
| oh-my-grokbot / t3bot / 大量 0★ 新仓 | — | 过早，先观察 |
| 华为云代金券 / AK·SK 帖 | — | 要密钥与羊毛，跳过 |
| 个人参考向仓 | — | 不点名、不进公开 README（按涛哥约束） |

### 给 Claude loop 的合并建议

1. **优先核实**：orca、devspace、agentrove、last30days-skill（星高但要确认「Grok Bot 可用性」表述是否准确）、browserpaw。
2. **谨慎**：无 License 的 iwork_mcp / hermes-bridge；星极少的 wechat / Claude2GrokBot / grok-cc——可 Learning 短链或先观。
3. **玩法向**：邮箱 +别名、Library tip、pstack（标非官方移植）值得 Learning/Routines 短链；勿把营收/额度营销文写进 README。
4. 我未改 README；夜班会持续到约 **03:00 Asia/Shanghai**，每约 30 分钟追加一节（无新增则静默）。

## 夜班 2026-10-18 ~00:41（Asia/Shanghai）

- **窗口**：相对夜班 #1（~00:15）之后约半小时；X 近几小时 + `gh search` created≥2026-10-15
- **负责**：Grok 夜班半小时雷达 #2
- **方法**：X `search_posts_all` / `get_posts_by_ids` + `gh api`/`gh search repos`
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README
- **去重**：相对 README + 上文 T1 / 夜班 #1；个人参考仓不点名

### 推荐入清单（夜班新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| grok-bot-t3-code-superpowers | https://github.com/gavasques/grok-bot-t3-code-superpowers | Skill + 脚本：经 MCP 让 Grok Bot 远程驱动 T3 Code（Claude/Codex/Grok 线程）。安装步骤帖齐全 | Skills & Playbooks | `skill` `mcp` `t3-code` | 0 / MIT | **X** @Ga_Vasques + gh |
| grokbot-relay | https://github.com/devicki/grokbot-relay | 本机/服务器 Cursor BDK 中继 → Grok Bot agents（给 Claude Code/Cursor 的 MCP）。与本仓协作同构 | Skills / Multi-bot | `relay` `mcp` `claude-code` | 0 / MIT | gh search |
| Badland Line | https://github.com/Badland-AI/grokbot | 任意手机 SMS 遥控 Grok Bot（remote MCP + skill） | Skills & Playbooks | `sms` `mcp` `mobile` | 0 / MIT | gh search |
| grokbot-plugins（keyless） | https://github.com/punk5322/grokbot-plugins | 五个免 key 的托管 remote MCP 插件包，可当「零配置插件」样板 | Skills & Playbooks | `plugins` `mcp` `keyless` | 0 / MIT | gh search |
| varosity grok-bot studio | https://github.com/varosity-ai/grok-bot | 经 Varosity remote MCP 给 Bot 接 60+ 视频/图/语音/音乐模型 | Skills & Playbooks | `mcp` `media` `studio` | 0 / MIT | gh search |
| siri-grokbot | https://github.com/enzoenrico/siri-grokbot | iPhone / CarPlay Siri intents 接 Grok Bot | Hardware / Skills | `siri` `ios` `carplay` | 0 / MIT | gh search |
| oh-my-grokbot | https://github.com/liziye627-design/oh-my-grokbot | 「能力分发与集成核心」；#1 Maybe 里有，现 ~4★ MIT，可再核 README 是否真可用 | Skills / Self-hosted | `core` `integration` | ~4 / MIT | gh（相对 #1 升星） |

### 玩法 / 产品信号（无强仓或仓弱）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 家庭多 Bot 群「日常饮食」 | https://x.com/turingou/status/2111483937822474526 | 中文高互动：订餐/家务等职责管家进同一群；与 war-room 同构，适合 Learning 或 `examples/` 配方灵感 | Multi-bot / Learning | **X** @turingou（~5.5k 展示 / 37❤） |
| HireQuay A2A | https://app.hirequay.com ；帖 https://x.com/KoetaInc/status/2111494967994536143 | Claude ↔ Grok Bot 交接上下文/技能，人审回复；免费 beta。无开源仓，当 Multi-bot 产品对照 | Multi-bot（备注） | **X** ~5.5k 展示 |
| BlackOps Comms | https://www.blackopscenter.com/blog/agent-comms ；帖 https://x.com/BlackOpsTools/status/2111495147359723599 | 多 agent 同笔记轮流、签名、点名下一棒，默认 10 条停；Claude+Grok Bot webhook | Multi-bot / Learning | **X** |
| 事件触发 vs 定时轮询 | https://x.com/Mateq007/status/2111489541450141833 | 邮件/Slack/GitHub/webhook 唤醒，少空跑——与邮箱+别名、本仓 X 雷达「无信号不推」同向 | Routines | **X** |
| Bland 电话 MCP | https://docs.bland.ai/integrations/mcp/grok-bot | 官方 MCP：Bot 自助开美号、通话/短信；第三方非 xAI 背书。可作 Outbound 配方外链 | Skills / Official-adjacent | **X** @grok 多次确认 + docs |
| Spam-Call Scrubber 技能 | https://x.ai/bot/fUj6TYhiW_cjtzWvbsFgz | 市场第三方免费技能：data-broker 退订；隐私敏感，仅作「可分享技能」样例，勿当主推 | Learning（备注隐私） | **X** 刷屏 |

### Maybe / Skip（夜班 #2）

| 名称 | 链接 | 原因 |
|------|------|------|
| robbin/x-news | https://github.com/robbin/x-news | 范凯说AI 新闻房背后仓；4★ **无 License**；玩法已有 Chrome/新闻房 X 帖，仓本身先观 |
| WeirdBrains/grokbot-tui | https://github.com/WeirdBrains/grokbot-tui | 0★ TUI，描述过短 |
| sunny0826/grokbot-smartring | https://github.com/sunny0826/grokbot-smartring | 动画/硬件 demo，License NOASSERTION，偏展示 |
| ConverseNation/mybusybots-status | — | 0★ 无 License 监控页 |
| pstack / poteto-mode 再刷 | — | #1 已列；Claude loop #2 已拒（GitHub 仅 Claude/Codex 移植） |
| Teach-a-Task 警示帖 | 多 | README 已有 teach-a-task 配方，勿重复堆 |
| 营收/agency/$1M 类 | 多 | 跳过 |

### 给 Claude loop 的合并建议

1. **优先看**：t3-code-superpowers、grokbot-relay（和本仓 Claude↔Grok 同构）、家庭多 Bot 群帖（适合写成 examples 灵感，不必挂仓）。
2. **谨慎**：其余多为 0★ 当日/近两日仓——有 MIT 可进 Maybe 观察表，勿急收 README；HireQuay / BlackOps 无开源仓，只 Learning 短链。
3. Bland / Spam Scrubber：第三方 + 隐私，短评须写清风险。
4. 未改 README；脏树里有 `.collab/loop-state.md`（非我改），本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 夜班 2026-10-18 ~01:11（Asia/Shanghai）

- **窗口**：相对夜班 #2（~00:41）之后约半小时；X 近几小时（`start_time`≈2026-10-17T12:00:00Z）
- **负责**：Grok 夜班半小时雷达 #3
- **方法**：X `search_posts_all` / `get_posts_by_ids`（多查询；github.com 向近几小时几乎空）
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README
- **去重**：相对 README + 上文 T1 / 夜班 #1–#2；个人参考仓不点名

### 推荐入清单（夜班新）

（本轮无强新仓；多为可复用玩法 / 模板 / 文章。）

### 玩法 / 产品信号（无强仓或仓弱，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| T3→Grok Bot ask-back | https://x.com/firestormodk/status/2111503562366984662 | Codex/Claude 在 T3 用 `list_bots` / `ask_bot` / `notify_bot` CLI 回问 Grok Bot，webhook Routine 路由唤醒；人只做最后兜底。与已列 t3-code-superpowers（Bot 驱动 T3）互补 | Multi-bot / Skills | **X** @firestormodk |
| CNR Grok Bot 指南+免费模板 | https://cnrcode.com/guides/ ；帖 https://x.com/CNR_Consulting/status/2111494385946734616 | 7 篇英文 how-to（Routines/Skills/额度）+ 可下载 skill；含 5 套小生意 copy-paste Bot 设定 | Skills / Learning | **X** @CNR_Consulting |
| CoS 额度效率审查 prompt | https://x.com/Michael_Fenech_/status/2111478843202818102 | 可粘贴给首席 Bot：按频率/结果/触发/变更检测/价值给 Routine 打 KEEP/SLOW/EVENT/CHANGE/RETIRE，估用量且先不改。~1.6k 展示 | Routines | **X** @Michael_Fenech_ |
| Routine 色历 + 额度重置线 | https://x.com/luisbarragan/status/2111501299938398306 | 让首席 Bot 画「每条 Routine×Bot」色历并标 usage reset，临近额度先停可缓跑的 | Routines | **X** @luisbarragan |
| Bot Budget Guard（市场技能） | https://x.ai/bot/CFNwEKsM5nPPRQhPVZMCD ；帖 https://x.com/MikeysMolecules/status/2111480053456413149 | 只读：预测周额度、安全日 burn、bot/routine 红黄绿；第三方市场技能，短评须写清非官方 | Routines / Learning | **X** |
| 晨晚交接 Routine 提示 | https://x.com/ScottyBeamIO/status/2111485286785941852 | 早晨：日历/邮件/项目→优先级与是否需批准；晚间：选≤3 个有明确成品的任务过夜。~900 展示 / 44❤ | Routines | **X** @ScottyBeamIO |
| 一夜从零 + rug filter 文 | https://x.com/0xboan/status/2111502544904012233 （文章） | 「Grok Bot from zero in one night」全量搭设 + 可复制过滤；Learning 短链，注意标题偏加密语境 | Learning | **X** @0xboan |
| Put Grok to Work 文 | https://x.com/tonysimons/status/2111503386961154150 （文章） | 「Elon Gave Grok a Computer…」上手用法长文；Learning 索引 | Learning | **X** @tonysimons |
| Codex CLI MCP + OpenRouter | https://x.com/lgtwet/status/2111496186167164993 | 中文：服务器装 Codex CLI，做 MCP 给 Grok Bot，挂 OpenRouter 调免费模型。无公开仓，先 Learning/Skills 短链 | Skills / Multi-bot | **X** @lgtwet |
| Orca 编排器中文教程 | https://x.com/xiaoanlab/status/2111457972660605344 （文章） | 多 agent 并行 worktree + 配额避坑；README 已有 orca，可作 Learning 中文旁注 | Learning | **X** @xiaoanlab |
| CoS 需要 Company Brain | https://x.com/RemingtonBegg/status/2111469626710176030 （文章） | 给首席 Bot 挂公司知识脑的写法；与作战室文件交接同向 | Learning | **X** @RemingtonBegg |

### Maybe / Skip（夜班 #3）

| 名称 | 链接 | 原因 |
|------|------|------|
| smfworks Video Studio 再推 | https://github.com/smfworks/grok-bot-templates | T1 / 上文已列 |
| 邮箱 +别名 / 事件触发 | 多帖 | 夜班 #1–#2 已列 |
| BlackOps / BenENewton 再刷 | https://x.com/BenENewton/status/2111491392937570344 | #2 已有 BlackOps Comms |
| Teach-a-Task / Spam Scrubber | 多 | README 或上文已有 |
| SpaceXAI 10 bots / Elon 回复增长文 | 多 | 营销或增长诱饵，跳过 |
| 营收 / $10k weekend | 多 | 跳过 |

### 给 Claude loop 的合并建议

1. **优先看**：T3 ask-back（@firestormodk）— 与本仓 Claude↔Grok 协作同构；CoS 效率审查 prompt（可放 `examples/` 灵感）。
2. **次优**：CNR 免费模板页（核实可下载 skill 是否可复用、有无 paywall）。
3. Budget Guard / Spam Scrubber 同类：第三方市场技能，短评写清风险，勿当官方。
4. 文章向（0xboan / tonysimons / RemingtonBegg / xiaoanlab）：Learning 短链即可，勿急收 README。
5. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 夜班 2026-10-18 ~01:48（Asia/Shanghai）

- **窗口**：相对夜班 #3（~01:11）之后约半小时；X 近几小时（`start_time`≈2026-10-17T16:00:00Z 起）
- **负责**：Grok 夜班半小时雷达 #4
- **方法**：X `search_posts_all` / `get_posts_by_ids` + `gh api` 核实仓
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README
- **去重**：相对 README + 上文 T1 / 夜班 #1–#3；个人参考仓不点名

### 推荐入清单（夜班新）

| 名称 | 链接 | 一句理由 | 建议节 | 星 / License | 来源 |
|------|------|----------|--------|--------------|------|
| reason-network | https://github.com/reason-machines/reason-network | Grok Bot / Muse ↔ Claude Code / Codex / Cursor 等 P2P 互问互派；引擎 Apache-2.0；产品页注明 CLI 本身非开源。配套站点 https://reasonmachines.com/network ；MCP/插件仓 https://github.com/reason-machines/reason-plugins（4★ MIT，简述面向 Claude/Codex/MCP，Grok Bot 可经 Cursor 市场装） | Multi-bot teams | ~184 / Apache-2.0 | **X** @reasonmachines 高热帖（~44万展示）+ gh |
| root-agent-skill-framework | https://github.com/MrBekoX/root-agent-skill-framework | Root Agent v0.2.0：按目标动态扩缩 Bot 队、委派 domain Lead、stall/交付证明、取消清理；市场安装页 https://x.ai/bot/1pTKHkJIEgxD9MjlPYE4P | Multi-bot / Skills | 2 / MIT | **X** @mrbeko_ + gh（刚 push） |

### 玩法 / 产品信号（无强仓或仓弱，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 额度一周烧完·8 步止血 | https://x.com/GrokBotRadar/status/2111513393538732162 （引用长文 https://x.com/i/article/2105065351595847680 ） | 可操作 checklist：放慢最快 Routine、仅工作日时段、把 Routine 挪出聊天 Bot、Duplicate 清上下文、prompt 指 skill 且无新则静默、优先连接器、规则活脚本化、测试时关 on-demand。**直接喂** Claude 已请的 `examples/routine-budget.md` | Routines / examples | **X** @GrokBotRadar |
| 一人公司 12 步配方文 | https://x.com/maestrooth/status/2111505949131227180 | 可粘贴：职能地图→三人岗描述→House Rules→干跑→存 skill→Auto-review→无人值守句→晨报→30 日审计；与本仓「一人三岗」同向，适合 Learning / 对照 `examples/` | Chinese solo-founder / Learning | **X** @maestrooth（~213 展示 / 12❤ / 11🔖） |
| 通勤 Granola→Slack Routine | https://x.com/steitiyeh/status/2111506107487154565 | 开车回家语音过会议笔记：加行动项 / 写纪要发 Slack / 设跟进提醒——「停车前 inbox zero」 | Routines | **X** @steitiyeh |
| 共享云电脑 vs 分隔离 | https://x.com/ianjcam/status/2111510052872106374 | Grok Bot 全员共一台云电脑（session/文件/登录共享）；对照 Hermes 每 Bot 独立 profile。作战室安全边界对照 | Learning / Multi-bot | **X** @ianjcam |
| Bot 是技能镜像 | https://x.com/shaivpidadi/status/2111505997902852496 | 「Bot 只会你允许的技能」；附自审 prompt 找自己否决过的 GTM 建议。Learning 软链 | Learning | **X** @shaivpidadi |

### Maybe / Skip（夜班 #4）

| 名称 | 链接 | 原因 |
|------|------|------|
| 24 篇合集再转发 | https://x.com/will_lion1/status/2111505199546487190 | 夜班 #1 已有 0xlangeai 原帖 |
| Spam-Call Scrubber 再刷 | 多 | #2/#3 已 Skip |
| SpaceXAI 9-bot / $500K / $1M | 多 | 营收/营销，跳过 |
| CrawlHive | https://github.com/...（X 帖） | 叙事狙击/加密语境，偏离本仓 |
| morrimoz Claude+Codex pipeline | https://x.com/morrimoz/status/2111511751615553906 | 愿分享但无公开仓/配方文 |
| ann0nip 要监控仪表盘 | https://x.com/ann0nip/status/2111510788225556601 | 需求帖非配方 |
| 华为云 AK/SK 羊毛 | 多 | 要密钥，红线跳过 |
| 邮箱 +别名 / Teach-a-Task | 多 | 上文已列 |

### 给 Claude loop 的合并建议

1. **优先看**：**reason-network**（~184★ Apache-2.0，过你们 ≥10★ 门槛）— Multi-bot 桥接刚需；短评须写清「引擎开源、Reason CLI 本身非开源」。
2. **额度配方**：本轮 GrokBotRadar 8 步 + #3 CoS/色历/Budget Guard → 合成 `examples/routine-budget.md`（你 loop #4 已点名）；提示词用自己的话重写。
3. **一人公司文**：maestrooth 12 步与 `examples/one-person-three-roles.md` 对照，可抽 House Rules / 晨报进 Learning 或 examples 补丁，勿整篇照抄。
4. **Root Agent**：2★ 当日活跃，先观察表；≥10★ 或建仓≥7 天再推 README。
5. 未改 README；脏树里有 `.collab/loop-state.md`（Claude loop 本地），本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 夜班 2026-10-18 ~02:10（Asia/Shanghai）

- **窗口**：相对夜班 #4（~01:48）之后约半小时；X `start_time`≈2026-10-17T12:00:00Z（主扫）+ 16:00/16:30Z 收紧窗
- **负责**：Grok 夜班半小时雷达 #5
- **方法**：X `search_posts_all` / `get_posts_by_ids` + `gh api` 核实仓
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README
- **去重**：相对 README + 上文 T1 / 夜班 #1–#4；个人参考仓不点名

### 推荐入清单（夜班新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| github-grok-bot-webhook-forwarder | https://github.com/doitian/github-grok-bot-webhook-forwarder | Cloudflare Worker：GitHub webhook → Grok Bot routine webhook；HMAC 校验、路径路由、失败可在 GitHub Recent Deliveries 重投。当日新建 | Routines & Digests / Skills | `webhook` `github` `cloudflare` | 0 / MPL-2.0 | **X** @doitian https://x.com/doitian/status/2111514792834027811 + gh |

### 玩法 / 产品信号（无强仓或仓弱，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 40 条可复制 Custom rules | https://x.com/unicodef1wn/status/2111518189511147682 | 安全文档提炼：✓ allow / ? ask first；? 冲突优先、审批约 10 分钟过期、密码/2FA/付款永不自动。与 field-notes 同作者，可作 Skills/护栏短链（帖末有营销 CTA，摘规则即可） | Skills & Playbooks / Learning | **X** @unicodef1wn |
| 24/7 DM Assistant 配方文 | https://x.com/KanikaBK/status/2111516185825268054 （文章 https://x.com/i/article/2111509806620266496 ） | 全量 setup+prompts：Bot 扫 DM、分流、只出草稿等人批。与出海客服「只出草稿」同向 | Routines / Chinese solo-founder | **X** @KanikaBK |
| Grok Bot in Practice 文 | https://x.com/shancha103/status/2111518339667529836 （文章 https://x.com/i/article/2111518270276956160 ） | 中文向「可复用 AI 工作流」实践指南；Learning 短链，需抽可复用步骤 | Learning | **X** @shancha103 |

### Maybe / Skip（夜班 #5）

| 名称 | 链接 | 原因 |
|------|------|------|
| tonysimons field guide 再推 | https://x.com/tonysimons/status/2111518353710010776 | 夜班 #3 已有原文章帖 |
| GrokBotRadar / maestrooth / Granola | 多 | #4 已列 |
| firestormodk ask-back | 已列 | #3 |
| SpaceXAI 9-bot / $1M | https://x.com/leopardracer/status/2111508903229796561 | 营收营销，跳过 |
| PennyLedgerr Elon reply 增长文 | https://x.com/PennyLedgerr/status/2111489661172437341 | 增长诱饵，跳过 |
| Spam Scrubber / 事件触发再刷 | 多 | 上文已 Skip/列 |
| Pebble→Grok Bot webhook | https://x.com/aku11i/status/2111500593995100480 | 硬件玩具向、无仓 |
| 加密交易 multi-agent 桌 | grok 回复串 | 金融签名/资金向，偏离本仓 |

### 给 Claude loop 的合并建议

1. **优先核实**：**doitian/github-grok-bot-webhook-forwarder**（MPL-2.0，配方完整）— 事件触发 Routine 的现成 Worker；短评可链「少空跑」玩法。0★ 当日仓，可先 Learning/Routines 短链或观察表。
2. **护栏**：unicode 40 rules 值得 Skills 短链或并入 field-notes 旁注；勿抄帖末「赚钱」CTA。
3. **DM Assistant / Practice 文**：Learning 或对照 `examples/outbound-support.md`；抽步骤勿整篇照抄。
4. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。


## 夜班 2026-10-18 ~02:46（Asia/Shanghai）

- **窗口**：相对夜班 #5（~02:10）之后约半小时；X `start_time`≈2026-10-17T17:00:00Z（主扫）+ 17:30Z 收紧
- **负责**：Grok 夜班半小时雷达 #6（本周日夜班末轮，cron 窗止于 02:xx）
- **方法**：X `search_posts_all` / `get_posts_by_ids` + HF/gh 快核
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README
- **去重**：相对 README + 上文 T1 / 夜班 #1–#5；个人参考仓不点名

### 推荐入清单（夜班新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| （本轮无新强仓） | — | gh 搜索当日新仓仍仅 doitian webhook（#5 已列）；推送窗内无第二仓 | — | — | — | gh |

### 玩法 / 产品信号（无强仓或仓弱，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 额度夜班·Meter 全配方文 | https://x.com/Aannzzo/status/2111525291944460293 （文章 https://x.com/i/article/2111478730799325184 ） | 「醒来 96 条过期审批 + 账单暴涨」场景的完整 playbook，与 #4 GrokBotRadar 8 步同向，可并入 `examples/routine-budget.md` 材料 | Routines / examples | **X** @Aannzzo |
| Proactive Suggestions | https://x.com/AndrewCurran_/status/2111522784438587767 | Bot 主动 DM「找事做」：heartbeat 类产品信号；用户触发→周期→主动。Learning 短链（~4.5k 展示） | Learning | **X** @AndrewCurran_ |
| 中文去 AI 味 LoRA（Grok Bot 训） | https://huggingface.co/Frankfika/deai-flavor-qwen2.5-1.5b-lora （帖 https://x.com/FrankFika/status/2111524182630760566 ） | Mac 上用 Grok Bot 跑通数据→训练→上传；中文内容向案例。HF 权重非 playbook 仓，Learning / Chinese solo 短链 | Learning / Chinese solo-founder | **X** @FrankFika + HF |
| OpenClaw VPS + Slack 自托管对照 | https://x.com/kyle_e_walker/status/2111528433586946095 | 不用订阅：OpenClaw 多 agent 挂自有 VPS、Slack app 互通、Tailscale 审批进 Mac。无公开配方仓，作战室/Self-hosted 对照信号 | Learning / Self-hosted | **X** @kyle_e_walker |

### Maybe / Skip（夜班 #6）

| 名称 | 链接 | 原因 |
|------|------|------|
| /hibernate + eggbot 截图 | https://x.com/edtadros/status/2111529344044826899 | 额度止血思路可取，但依赖 marketplace「dr eggbot」截图 prompt，无仓无全文 |
| Side Hustle CEO 案例 | https://x.com/thebtchodlr/status/2111525358809845785 | AlexFinn 市场 Bot 使用故事，无可复制开源配方 |
| SpaceXAI PDF / $1M 9-bot | 多 | 营收营销，跳过 |
| Spam-Call Scrubber / doitian / unicode / Kanika / shancha / 0xboan | 多 | #5 及更早已列 |
| 加密钱包扫描 / invite code | 多 | 金融/营销，偏离本仓 |

### 给 Claude loop 的合并建议

1. **额度文合并**：Aannzzo Meter playbook + #4/#5 Radar 8 步 → 继续喂 `examples/routine-budget.md`；自写短评，勿整篇照抄。
2. **产品信号**：Proactive Suggestions 可 Learning 一行；注意「主动找事」会烧额度，宜与 budget 护栏同页。
3. **FrankFika**：HF LoRA 作「Grok Bot 跑通训练管线」中文案例短链即可，勿当 Skills 主条目。
4. **kyle OpenClaw**：无仓则不上 README；可对照已收录 OpenGrokBot / lorca 写一句差异。
5. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 白天 2026-10-18 ~07:45（Asia/Shanghai）

- **窗口**：夜班 #6（~02:46）之后至周日上午；Reason Network 已搁置，**仅 git 协作**
- **负责**：Grok 白天玩法雷达（即时一轮）
- **方法**：X `search_posts_all`（近 48h）+ `gh api repos/...` 核实 + Web 检索；相对 README + `inbox/candidates.md` 全表去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **卫生**：本轮已将 Grok 侧文件（LOOP.md / to-claude.md / candidates.md）中的个人名点名改为「个人参考」（不改 Claude 留言）

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| grokbot-imessage-skill | https://github.com/jeffhuber/grokbot-imessage-skill | macOS 本地 launchd 桥：读/分拣/搜/发 iMessage，隐私优先、无云同步 | Skills & Playbooks | `imessage` `macos` `skill` | ~36 / MIT | **GitHub** + awesome 生态交叉 |
| grokbot-sdk | https://github.com/adam91holt/grokbot-sdk | 运行中 Grok Bot host 的 TypeScript SDK（typed gateway + sand-data 读盘） | Official & SDK | `sdk` `typescript` | ~20 / MIT | **GitHub** |
| grok-bot-skill | https://github.com/adamanz/grok-bot-skill | Cursor/Agent Skill：终端聊 teammates、创建新 Bot（用本地桌面会话，不拷 token） | Skills & Playbooks | `cli` `skill` `cursor` | ~11 / MIT | **GitHub** |
| lauren-poteto-rules | https://github.com/unicodef1wn/lauren-poteto-rules | 可信 coding-agent 工作流工程规则（与 field-notes 同作者线，可作 AGENTS 配套） | Learning / Skills | `agents.md` `rules` | ~90 / MIT | **GitHub** |
| grok-bot-delegation | https://github.com/agent-skills-lab/grok-bot-delegation | Claude Code skill：名册/简报格式/skills·routines/审批边界 + 双语模板；与本仓 Claude↔Grok 协作同构 | Skills & Playbooks | `claude-code` `delegation` `bilingual` | ~1 / 无 SPDX | **GitHub** + Web |

### 玩法 / 产品信号（无强仓或仓弱，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 任务→Skill→再 Routine 阶梯 | https://x.com/joeapfelbaum/status/2111594967114113329 | 「先手工跑通再存 skill，最后才上 schedule」——与本仓 teach-a-task / 脱敏配方同向 | Skills / examples | **X** @joeapfelbaum |
| 一职一 Bot + never-list + 周审 skill | https://x.com/grovr_au/status/2111594375260111249 | 每个 Bot 只一事；「从不做」清单指向其他 Bot；专 Bot 每周扫过期 skill | Multi-bot / Skills | **X** @grovr_au |
| Import Bot（Hermes→Grok 迁移） | https://x.ai/bot/marketplace/bots/import-bot （帖 https://x.com/joshuaday/status/2111600012929192086 ） | 官方 marketplace Import Bot：把 Hermes 等 setup 迁入；装后核对 private skills 是否到齐 | Learning / Official | **X** @joshuaday + marketplace |
| Claude Code→Grok Bot 四次 API（跳过 webhook） | https://x.com/mikan77_aoi/status/2111043148088816045 | webhook 400 时用 stdlib Python 四次调用交接；含陷阱与两条安全规则。可并 Learning「Claude↔Grok」 | Learning | **X** @mikan77_aoi |
| Connect Claude Code to GrokBot 文 | https://x.com/luchoorocker/status/2111162182322843798 | 西语长文：Grok 选 provider、Claude Code harness 接长任务、省 Cursor Cloud 额度 | Learning | **X** @luchoorocker |
| 周日备份「救生艇」系统 | https://x.com/EdisonTanEdtreo/status/2111563454528327750 | 怕失忆：周日例行备份规则/routine/细节；Routines 护栏素材 | Routines | **X** @EdisonTanEdtreo |
| 额度止血：先暂停全部 Routine 再逐个开 | https://x.com/joshuaday/status/2111575371221250348 （背景 https://x.com/BrettDavies/status/2111564923566248313 ） | 2 天烧 80% 用量时从内无法定位 tokenmaxxer；先 pause 再逐开长聊 Bot。喂 `routine-budget` | Routines / examples | **X** @joshuaday / @BrettDavies |

### Maybe / Skip（白天）

| 名称 | 链接 | 原因 |
|------|------|------|
| tiagovilasboas/grok-bot-architecture | https://github.com/tiagovilasboas/grok-bot-architecture | 0★ MIT，MCP 多 agent + 人闸；方向贴但过新，先观察 |
| Luca-Blight/thin-grok-bot-deep-work-on-cli | https://github.com/Luca-Blight/thin-grok-bot-deep-work-on-cli | 0★ MIT，薄 mesh + 深活交 CLI；与已有 Claude↔Grok 同向，星少先观 |
| AgentMindCloud/grok-bot-super | — | 上游已归档/API 404；awesome 他仓仍列，本仓不新收 |
| BotBagger 商店 Bot | https://x.com/Phil_Holland/status/2111589542805618795 | 电商/Printful 产品演示，非 playbook 配方 |
| 3-Bot 交易桌（Chief/Researcher/Trader） | https://x.com/Number1AIFanboy/status/2111579924020740543 | 金融交易向；可学「一职一 Bot + MCP 隔离」，不当推荐主条 |
| Av1dlive 全课 / LawrenceW_Zen / 0xboan | 多 | 夜班/T1 已列 |
| 营收 agency / $1M 类 | 多 | 营销，跳过 |

### 给 Claude loop 的合并建议

1. **优先收仓**：`grokbot-imessage-skill`（★最高、可复制）→ `grokbot-sdk` → `grok-bot-skill`；`lauren-poteto-rules` 作 field-notes 配套 Learning 一行即可。
2. **delegation skill**：无 SPDX、星少，可先挂 Learning「Claude 怎么 brief Grok Bot」；核实 License 后再考虑 Skills 主条。
3. **玩法合并**：joeapfelbaum 阶梯 + grovr 周审 → 可补 `examples/teach-a-task.md` / skills 卫生；额度 pause 逐开 → 继续喂 `examples/routine-budget.md`。
4. **Import Bot**：Official / Learning 短链；提醒「装完核对 private skills」。
5. Reason Network **继续搁置**；协作只走 git + `.collab`。Claude loop 已重开则收本段即可。
6. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/*`（Grok 侧）。

## 白天 2026-10-18 ~09:17（Asia/Shanghai）

- **窗口**：白天 ~07:45 → ~09:17（约 2h）；周日
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-17T23:00Z）+ `gh api`/`gh search` 核实 + Web；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：本窗 gh 无「近几小时新建」强仓；增量来自对照文带出的**尚未进 README 的主流平替仓** + 中文 Learning 文

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| rakazo | https://github.com/elie222/rakazo | 开源 Grok Bot 平替：自选模型与沙盒；生态里星标体量最大的一类自托管。README 仅在 DeepSeekBot 短评点名，缺独立条目 | Self-hosted bots | `self-hosted` `byo-model` `open-source` | ~4469 / Apache-2.0 | **X** 对照文 @Ga_Vasques + gh |
| Codync | https://github.com/leepokai/Codync | 本机开源平替：把 Claude Code / Codex / Cursor 等 40+ agent 当 bot 聊，Rust，跨 iPhone/Mac/Win/Linux | Self-hosted bots / Multi-bot | `self-hosted` `rust` `multi-agent` | ~498 / Apache-2.0 | **X** 对照文 + gh |
| OpenBot (CopilotKit) | https://github.com/CopilotKit/OpenBot | 每 agent 一台电脑（浏览器/文件/工具），动作先决后录；AG-UI；体量最大开源 coworker 系 | Self-hosted bots | `self-hosted` `ag-ui` `coworker` | ~6599 / MIT | **X** 对照文 + gh |
| openbot (nightly-labs) | https://github.com/nightly-labs/openbot | 本地优先桌面工作区：Codex/Claude/Grok 分工作区 + 任务队列 + agent 互通；与 CopilotKit/OpenBot **同名异仓**，短评须区分 | Self-hosted bots / Multi-bot | `self-hosted` `desktop` `local-first` | ~595 / 无 SPDX | **X** 对照文语境 + gh |
| botdirectory.ai | https://github.com/elie222/botdirectory.ai | Grok Bot / Rakazo 等可用的开源 bot prompt 目录（botdirectory.ai） | Skills & Playbooks / Learning | `templates` `directory` `rakazo` | ~260 / MIT | gh（对照文生态） |

### 玩法 / 产品信号（无强仓或仓弱，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 开源平替对照文（MausBot/Codync/Rakazo/OpenBot） | https://my-tierroom.party/blog/open-source-grok-bot-alternatives-mausbot-rakazo-codync-openbot （帖 https://x.com/Ga_Vasques/status/2111609699422388339 ） | Skills/MCP/记忆/语音/自动化 + VPS/Mac 部署对比与个人排名；Self-hosted 节选型 Learning | Learning / Self-hosted | **X** @Ga_Vasques |
| 中文：Lauren Tan 如何放手给 agent | https://x.com/MaiYangAI/status/2111603532210299234 （文章 https://x.com/i/article/2111593631518015488 ） | 信任倒金字塔、验证 skill、pstack/Benny；中文可抄「普通人几步」；可链已收 lauren-poteto-rules / field-notes | Learning / Chinese solo-founder | **X** @MaiYangAI |
| DeepSeek Harness 装进 Grok Bot 云电脑 | https://x.com/KinGao476942/status/2111622701089759654 （仓 https://github.com/deepseek-ai/deepseek-harness ） | 可复制焚决：新建 Bot → 云电脑按官方仓装 Harness、默认 DeepSeek V4.1；省额度编程向。与已收 DeepSeekBot 互补（官方 harness vs 平替产品） | Skills / Self-hosted / Chinese | **X** @KinGao476942 + gh |
| Performance Auditor Bot | https://x.com/grok/status/2111624403981127985 | 专 Bot 审计其他 Bot：慢/快 routine、仅工作时段、routine 不绑长聊 Bot、静默 skill、去重等 8 条——可并 `routine-budget` / Multi-bot 卫生 | Routines / Multi-bot | **X** @grok（回复） |
| Plus 邮箱别名触达 Routine | https://x.com/GrokInsider/status/2111612092683829398 | 产品：Plus 别名 → 仅该址邮件唤醒 routine；另 Tag Bot on X / 读 X Chat。邮箱触发配方信号 | Routines / Official | **X** @GrokInsider |

### Maybe / Skip（白天 ~09:17）

| 名称 | 链接 | 原因 |
|------|------|------|
| MausBot / OpenMausBot | 对照文提及 | 无清晰公开主仓（仅 app-review / 空 skills 仓）；先跟对照文，不单列仓 |
| AgentMPG 机票降价 template | https://x.com/AgentMPG/status/2111619789588164619 | 营销向、展示极低、无 GitHub；跳过 |
| CLAUDIA 等加密叙事 | https://x.com/Aspirin_2022/status/2111623279752663087 | 偏离本仓 |
| niko 多 bot 信息系统草稿 | https://x.com/niko70129972/status/2111611178694906117 | 帖未完、无可复制配方 |
| 营收/粉丝增长文 | 多 | 营销，跳过 |
| doitian webhook / root-agent / imessage-sdk 等 | — | 夜班或 ~07:45 已列；README 已收部分 |

### 给 Claude loop 的合并建议

1. **优先补 Self-hosted 缺口**：`rakazo`（★最大）→ `CopilotKit/OpenBot` → `Codync`；`nightly-labs/openbot` 须在短评写清「非 CopilotKit」。
2. **botdirectory.ai**：Skills/Learning 短链即可，当灵感目录。
3. **Learning**：Ga_Vasques 对照文 + MaiYang 中文 Lauren 文；后者可挂 Chinese solo-founder。
4. **Harness 焚决**：Chinese / Skills 一行，链官方 deepseek-harness；勿与 DeepSeekBot 条目混淆。
5. **Performance Auditor + 邮箱别名**：继续喂 `examples/routine-budget.md` / Routines。
6. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 白天 2026-10-18 ~11:10（Asia/Shanghai）

- **窗口**：白天 ~09:17 → ~11:10（约 2h）；周日
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-18T01:10Z）+ `gh api` 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：stablyai/orca（README 已收）、Root Agent v0.3.0（已列，仅版本更新）不重复列

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| web-access | https://github.com/eze-is/web-access | 给本机 Agent（Claude Code / Grok Bot 等）装联网能力的 Skill：三层通道调度 + 浏览器 CDP + 并行分治、自动积累站点经验；解决云电脑机房 IP / 无本机登录态的采集场景。作者与已收 eze-grokbot 同源 | Skills & Playbooks | `skill` `browser` `cdp` `chinese` | ~9166 / 无 SPDX | **X** @eze_is_1 + gh |
| T3 Code Bridge（模板） | https://x.ai/bot/_5NG_WsrOdQs2jtUhZeQH （帖 https://x.com/trevin/status/2111631433299374450 ） | 官方模板页：Bot 经 T3 Code MCP 开线程、盯状态、遇问题回问人；用其他订阅的模型分担额度。与已列 t3-code-superpowers（仓）/ T3 ask-back 互补，且是一键导入版 | Templates / Multi-bot | `template` `mcp` `t3-code` | 模板 / — | **X** @trevin（23 赞 16 收藏） |
| 多 Bot 治理层（模板） | https://x.ai/bot/HQh9l4duDHNmhCuSW_pn- （帖 https://x.com/alanhoward/status/2111631067941925240 ） | 共享团队规则（不编造、默认只读、只起草）+ Bot/routine/续费登记表 + 每周安全审计快照 + 事故预案 +「必要而非好」精简过滤；10 问上手，变更需批。可配 `routine-budget` 与作战室模板 | Multi-bot teams / Routines | `template` `governance` `audit` | 模板 / — | **X** @alanhoward |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Second brain on Grok Bot（视频） | https://www.youtube.com/watch?v=V0IDoPLAtVI | 云电脑 + routine 爬网/摘要/自动 commit 到 GitHub 同步笔记库；角色 Bot 分工。与本仓「git 当协作通道」同构 | Learning / Routines | **X** @TamaminiGrok 转述 |
| 中文：Grok Bot × Cursor Cloud × GitHub CI 手机编程流 | https://x.com/xiaomovps/status/2111641676523688023 | Bot 分派任务 → Cursor 云端写码测、回截图录屏验收 → GitHub CI 兜底；手机全程。中文可抄分工表 | Chinese solo-founder / Learning | **X** @xiaomovps |
| 中文：官方指南 20 条精华 | https://x.com/Ljhzdqb/status/2111632720996487261 | 把热门英文「官方指南 20 条」翻成中文并点评；中文入门 Learning 候选（核实原帖出处后再挂） | Learning / Chinese | **X** @Ljhzdqb |
| Routine 体检 prompt（keep / 放慢 / 改事件 / 退役） | https://x.com/grokbotusecases/status/2111633433017426117 | 一句可抄 prompt：按节省用量排序、批准前不改；继续喂 `examples/routine-budget.md` | Routines | **X** @grokbotusecases |
| ScriptSprint（模板） | https://x.ai/bot/-j00v29rSvOvd-ht6q_vi | 转写稿/会议纪要 Bot：存原文 + 旁生 distill（发言人、决策、行动项）；Templates 一行即可 | Templates | **X** @the_simonjester |

### Maybe / Skip（白天 ~11:10）

| 名称 | 链接 | 原因 |
|------|------|------|
| ADHD Founder's Chief | https://x.ai/bot/7PyUClpHZH-lavGlXGRVg | 个人效率向、受众窄；Maybe 放 Templates 尾 |
| 数据经纪商信息移除模板 | https://x.com/madmenai/status/2111644355136278809 | 涉个人隐私处理，未核实做法；暂跳过 |
| TV De-Ad Bot | https://x.ai/bot/rIKTxh3Pwrmn7N02x6glX | 趣味向，偏离本仓 |
| donvitocodes 模板合集 | https://www.donvitocodes.com/grok-bots | 个人模板目录，含 X Post Tracker 等；与 botdirectory.ai 重叠，Maybe |
| Bot Packs Fleet Tune-Up | botpacks.dev | 付费 $29，跳过 |
| OpenBMB/PilotDeck | https://github.com/OpenBMB/PilotDeck | ~4.6k★ AGPL，README 未提 Grok Bot；偏题 |
| FilmLadd 渲染管理器 | — | 作者称下周上 GitHub，届时再看 |

### 给 Claude loop 的合并建议

1. **优先**：`eze-is/web-access`（★高、中文作者、与 eze-grokbot 同源）→ Skills 主条，注明无 SPDX。
2. **模板两条**：T3 Code Bridge 挂到已有 T3 相关条目旁；多 Bot 治理层可进 Multi-bot teams，并在 `routine-budget` / 作战室模板里互链。
3. **Learning**：Second brain 视频 + 中文 Cursor Cloud 编程流；20 条中文精华待核原帖后再挂。
4. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 白天 2026-10-18 ~13:10（Asia/Shanghai）

- **窗口**：白天 ~11:10 → ~13:10（约 2h）；周日
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-18T03:05Z，中英各一轮）+ `gh api` 搜近 2 天新建仓并读 README；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：eze-is/web-access（~11:10 已列）、AgwaB/grok-bot-audit、Claude2GrokBot、grokbot-sdk（README 已收）不重复列

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| Grok Bot Clipper | https://github.com/RongleCat/grok-bot-clipper | 非官方浏览器扩展（Chrome/Edge/Firefox）：网页剪藏、截图/文件、社媒帖收集进「素材篮」后直接发给自己的 Bot；不走第三方中转、不碰桌面端凭证。作者铁柱AGI（@cgnot996）基于自研 SDK 做，中英双 README | Skills & Tools / Chinese | `browser-extension` `clipper` `chinese` | 0 / NOASSERTION（README 称核心 MIT、第三方例外） | **X** @cgnot996 + gh（2026-10-18 新建） |
| grokbot-lite | https://github.com/h1neolzr7f/grokbot-lite | 让 Grok Bot 在无桌面 Linux 服务器上跑：专用用户 + systemd，后台约 190 MB，不要 Xvfb、不用 root；1–2 GB 小 VPS 可当 24h 远程机。中文 README，带 shellcheck/bats | Self-hosted / Chinese | `self-hosted` `linux` `vps` `chinese` | 0 / MIT | **GitHub**（2026-10-17） |
| ai-tool-inventory | https://github.com/stland6338/ai-tool-inventory | Skill：每天只读盘点 Claude Code / Codex / Grok Bot 的 skills、plugins、MCP、全局包并和上次 diff，新增或变更项顺手查可疑模式。装插件多的人的安全体检 | Skills & Playbooks / Routines | `skill` `security` `audit` `read-only` | 0 / MIT | **GitHub**（日文 README，2026-10-18） |
| Duobot（模板） | https://x.com/legallyrenee/status/2111659030745665566 | 双人家庭版多 Bot：两人各装一个 Duobot，两个 Bot 互相同步，共用一个日历 + 一个 Trello 板（采购、账单、约会、旅行）。少见的「Bot 对 Bot」家庭配方，已上 marketplace | Multi-bot teams / Templates | `template` `multi-bot` `household` `trello` | 模板 / — | **X** @legallyrenee |
| Motion Director v2（模板） | https://bots.jonbailey.xyz/motion-director （帖 https://x.com/SuddenlyJon/status/2111685969850044864 ） | 免费模板：逐镜头动画、逐帧锁画风、按人声用代码画口型、本机 GPU 放大、分块防崩渲染；做 MV/短视频的完整流水线 | Templates / Creative | `template` `video` `creative` | 模板 / 免费 | **X** @SuddenlyJon |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 官方 Bot 模板市场 | https://x.ai/bot/marketplace | README 目前只链单个模板页，没有市场入口；Official 节补一行即可 | Official & SDK | **X** @EvanWritesX |
| bot.tiezhu.si 学习站 + 三篇中文长文 | https://bot.tiezhu.si/ （帖 https://x.com/cgnot996/status/2111402146159861840 ） | 中文 Grok Bot 学习站；作者三篇：额度续航指南、Webhook + 快捷指令知识入库流水线、Agent 系统备份方案。可挂 Chinese / Learning，和 Clipper 同作者 | Chinese solo-founder / Learning | **X** @cgnot996 |
| 6 席位模拟交易台拆解（中文长文） | https://x.com/i/article/2111680703171878912 （帖 https://x.com/neohob/status/2111682579892232439 ） | 多 Bot 作战室样板：一个模型出力、另一个只答带概率的窄问题、硬规则写进代码、下单前必弹审批卡、全链路排在闲时价时段。全程模拟；短评只讲架构，勿带投资暗示 | Multi-bot teams / Learning | **X** @neohob |
| 静默时段写进 routine 本体 | https://x.com/sisiliu517/status/2111677231101620361 | 发帖前再查一次时钟，越过截止就自跳过；配「每轮最多 2 条回复」「先查自己公开帖防重发」硬规则。可喂 `examples/routine-budget.md` | Routines | **X** @sisiliu517 |
| jeffgreendesign 模板仓 | https://github.com/jeffgreendesign/air-watch | 作者把模板做成 MIT 仓：air-watch（空气质量只读告警，超阈值才报）、follow-through（家务责任提醒）。「模板即仓」样例，Maybe 进 Templates 尾 | Templates | **GitHub** |

### Maybe / Skip（白天 ~13:10）

| 名称 | 链接 | 原因 |
|------|------|------|
| dluxhu/grokbot-docker | https://github.com/dluxhu/grokbot-docker | 群晖 NAS / Docker 里浏览器跑官方 Linux 客户端 + 编码 CLI 工具箱；思路好但无 License，补 License 后再收（可与 grokbot-lite 并列 Self-hosted） |
| apha404ai/grok-bot-skills | https://github.com/apha404ai/grok-bot-skills | 10 个交易 skill，0★、偏交易，跳过 |
| TappNetwork/babblehq-grok-plugin | https://github.com/TappNetwork/babblehq-grok-plugin | 单一厂商插件，偏推广 |
| WeirdBrains/grokbot_api | https://github.com/WeirdBrains/grokbot_api | Rust SDK 封装，0★、刚建；观察 |
| Security Questionnaire Bot / Grokbot Money Glitch | Gumroad / 付费链 | 付费包，跳过 |
| kaizenpromptlab 两模板 | https://x.com/kaizenpromptlab/status/2111671093463236772 | 主帖无链接，线程待补 |
| ECC 28 万星 | — | 非 Grok Bot 专属，偏题 |

### 给 Claude loop 的合并建议

1. **优先**：`grok-bot-clipper`（中文作者、和 Clipper 学习站一起挂 Chinese）→ License 写「核心 MIT，有第三方例外」。
2. **Self-hosted 补缺**：`grokbot-lite`（MIT）进主条；`grokbot-docker` 等 License。
3. **Skills/安全**：`ai-tool-inventory` 可与 Bot Audit / 治理层模板互链。
4. **Multi-bot**：Duobot（家庭双 Bot）+ 6 席位交易台拆解（只讲架构）。
5. **Official**：补 `x.ai/bot/marketplace` 一行。
6. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 白天 2026-10-18 ~15:12（Asia/Shanghai）

- **窗口**：白天 ~13:10 → ~15:12（约 2h）；周日
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-18T05:05Z，中英各一轮）+ `gh api` / Web 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：Motion Director / Duobot / marketplace / grok-bot-clipper（~13:10 已列）、apha404ai/grok-bot-skills（交易向已 Skip）不重复列；近 2 日无新 `grok-bot*` 公仓命中

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| coolxeo/grok-bot-skills | https://github.com/coolxeo/grok-bot-skills | 22 个可移植 `SKILL.md`（写作/设计/工程/SEO/Bot）：含 `routine-healthcheck`、`transcript-healthcheck`、`design-a-grok-bot`、`no-ai-slop`；支持 `npx skills add`。可直接喂 `examples/routine-budget.md` 与作战室卫生 | Skills & Playbooks / Routines | `skill` `routine-health` `portable` `mit` | 6 / MIT | **GitHub**（@DaniAcostaAI） |
| CEO Bot 六步作战系统（SpaceXAI 工程师拆解） | https://x.com/Mr_Buzzoni/status/2111523960735105339 （今日转述 https://x.com/grokbotusecases/status/2111691958284681489 ） | 一人 CEO Bot 持组织图 + 持久 ledger（task/owner/state/artifact/deadline/retry）；技能挂 routine（幂等键、重试预算、kill switch）；未完成前必须有独立证据（diff/log/产物）。多 Bot 编排教科书级，无仓但可抄架构 | Multi-bot teams / Learning | `multi-bot` `ledger` `evidence` `architecture` | — / — | **X** @Mr_Buzzoni（137 赞 122 收藏） |
| 中文：Grok Bot 运营 X 十步实操 | https://x.com/SIAxiom/status/2111689540792655982 （文章 https://x.com/i/article/2111683397542359040 ） | 安装→选题→原创→定时→复盘；附 9 组可复制指令 + 8 条防违规。中文一人公司 X 运营配方，适合挂 Chinese / Learning（发帖仍须人工闸门） | Chinese solo-founder / Learning | `chinese` `x-ops` `playbook` `routine` | — / — | **X** @SIAxiom（8 赞） |
| Marketplace 对照体检指令 | https://x.com/FanShifu/status/2111686869494726793 | 主 Bot 扫 `x.ai/bot/marketplace` 类别与热门模板 → 体检现有 Bot（名/职责/Skill/Routine）→ 对照工作流补缺口清单。可复用的舰队审计 prompt，配治理层模板与 routine-budget | Multi-bot teams / Routines | `audit` `marketplace` `prompt` | — / — | **X** @FanShifu |
| 中文：4 Bot 短视频营销作战室要点 | https://x.com/swordBluesy/status/2111717105926332691 | 把博主实测短视频流水线拆成 4 个专职 Bot、人只拍板；中文多 Bot 营销分工样板（视频长文）。无 GitHub，作 Multi-bot / Chinese 短链即可 | Multi-bot teams / Chinese | `chinese` `multi-bot` `marketing` `war-room` | — / — | **X** @swordBluesy |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 内置 X 读接口三用法 | https://x.com/huagechen/status/2111701081650806821 | 热点 / 盯大 V / 历史帖蒸馏成 Skill 二创；与本仓 X 雷达同构，可补 Learning 一句 | Routines / Learning | **X** @huagechen |
| 到家提醒：Shortcuts → Bot 邮箱 → email routine | https://x.com/JeremieV98343/status/2111699724348858436 | 位置事件暂无原生触发时的变通：手机自动化发信到 Bot 自有 inbox，再用 email listener 唤醒 | Routines | **X** @JeremieV98343 |
| 6 Agents 一人公司 playbook（英文长文） | https://x.com/AI_Acq/status/2111713733710073939 | 客户信号→调研线索→跟进草稿→内容→日决策队列；英文 one-founder 作战室，核实文章体后再挂 | Multi-bot / Learning | **X** @AI_Acq |
| 生财 MCP 一提示词接入 | https://x.com/web30708/status/2111702016225669216 | 中文社区信号：用一条接入提示词挂生财 MCP，再让 Bot 自探玩法。Learning 备注即可，勿写内部库路径 | Chinese / Learning | **X** @web30708 |

### Maybe / Skip（白天 ~15:12）

| 名称 | 链接 | 原因 |
|------|------|------|
| zsredeemer「本周精选 5 个」 | https://x.com/zsredeemer/status/2111714533681058067 | 仅放出 ① 微信文章捕手（与已收 cgnot996 / Clipper 同作者线）；②–⑤ 未发完，等齐再审 |
| swordBluesy 帖内视频长文 | 同上推荐行 | 已作短链；若后续补 GitHub/模板页再升格 |
| Hyperliquid / 「$38→$8740」同模板帖 | 多 | 无法核对钱包/成交，JakeLin 已拆穿；跳过 |
| 微软奖励签到赚闲鱼 | https://x.com/zo_qq17920/status/2111689682820207015 | 灰色变现，偏离本仓 |
| Security Questionnaire Gumroad | 多 | 付费包，~13:10 已 Skip |
| herdr + pi 本机操控 tip | https://x.com/wkruan94/status/2111716686990827860 | 个人经验、无公开配方 |
| coolxeo 付费 Gumroad kits | README 内链 | 只收免费 SKILL.md；付费套件不进清单 |

### 给 Claude loop 的合并建议

1. **优先**：`coolxeo/grok-bot-skills`（MIT、可 `npx skills add`）→ Skills 主条；短评点名 `routine-healthcheck` / `transcript-healthcheck`，并与 `examples/routine-budget.md` 互链。
2. **Multi-bot 架构**：Mr_Buzzoni 六步（CEO+ledger+证据）进 Learning 或 Multi-bot 短评；无仓不要紧，架构可抄。
3. **中文**：SIAxiom X 十步 + swordBluesy 4 Bot 营销要点；发帖类一律强调人工闸门。
4. **Routines**：FanShifu marketplace 体检 prompt + 到家邮箱触发变通 → 喂 routine-budget / field-notes。
5. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 白天 2026-10-18 ~17:17（Asia/Shanghai）

- **窗口**：白天 ~15:12 → ~17:17（约 2h）；周日
- **负责**：Grok 白天玩法雷达（routine awesome-3；本轮 executor 耗尽后主会话直跑）
- **方法**：X `search_posts_all`（中英，start_time≥2026-10-18T07:00Z）+ `gh search` / Web 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：coolxeo / Mr_Buzzoni / SIAxiom / swordBluesy 4 Bot / AI_Acq / huagechen（~15:12 已列）、adamanz/grok-bot-skill（已在 README）、Side Hustle CEO 营收故事（已 Skip）不重复列

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| robbin/grokbot-local-agent | https://github.com/robbin/grokbot-local-agent | 今日新仓：Grok Bot 派重活给同机本地 Pi Agent；`pi-task` 落盘状态 + Webhook 唤醒 Routine 核查汇报；含 `skills/pi-agent`、`routines/pi-task-notify.md`、setup 教程。额度省着用的可复制交接层 | Multi-bot / Skills & Playbooks / Routines | `local-agent` `webhook` `routine` `pi` `mit` | 1 / MIT | **X** @fankaishuoai + gh（今日推） |
| codejunkie99/rosterroom | https://github.com/codejunkie99/rosterroom | 82 套可粘贴作战室名册（32 rebuilt + 50 new）：Full setup / First job / Manual fallback；统一人工审批闸门。多 Bot 模板库，README 缺口 | Multi-bot teams | `roster` `war-room` `prompts` `approval` | 16 / NOASSERTION | **GitHub** + Web |
| glaucia86/grok-bots-handoff-lab | https://github.com/glaucia86/grok-bots-handoff-lab | 「Memory Outside the Chat」：短交接条 + 带来源 ID 的 registry，聊天当可丢缓存；离线可复现教程与脚本（MIT）。作战室长会话交接可抄模式 | Skills & Playbooks / Learning | `handoff` `memory` `tutorial` `mit` | 4 / MIT | **GitHub**（近窗更新） |
| Blotato-Inc/blotato-skills | https://github.com/Blotato-Inc/blotato-skills | 7 个免费 Claude 营销 Skill（coach/writer/grader/scheduler/…）；实测可迁到 Grok Bot 4 Bot 营销作战室（删 Claude 专用字段）。无 SPDX，短评需注明 | Skills & Playbooks / Chinese | `skills` `marketing` `portable` `claude→grok` | 191 / none | **X** swordBluesy 帖内链 + gh |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 桌面安全默认：关「在这台电脑上执行」+「经此电脑转发流量」 | https://x.com/fankaishuoai/status/2111740064409756037 | 安装即设：云端 Bot 不碰本机文件、不经本机转发流量；与 Chrome 隔离协作同向，宜进 field-notes / Learning 安全一句 | Learning / field-notes | **X** @fankaishuoai |
| X Bookmarks → Notion 主动提取 | https://x.com/Orderly_Milan/status/2111740484875960729 （源玩法 @jestonlu） | 每 6h 抓收藏进 Notion；每 24h 邮件做 Connection / Use Today / Worth Remembering。Passive→active retrieval 例程样板 | Routines / Learning | **X** @Orderly_Milan |
| 一 Bot 一事 + 按项目建群 | https://x.com/terranc/status/2111740611690954837 | 开发/PM/调研/知识库/云电脑管家分岗；每项目一群、群上下文与单聊隔离。中文多 Bot 作战室体感短链 | Multi-bot / Chinese | **X** @terranc |
| Routine 上线前先 Test run | https://x.com/robotshelp/status/2111721679923626110 | 官方建议：新建/改例程后 Test run，核对今日数据、输出格式、审批停点；提醒真实动作要用安全样本 | Routines | **X** @robotshelp |
| /grill-me 动手前拷问（喂 Grok Bot） | https://github.com/mattpocock/skills （帖 https://x.com/limuvibecoding/status/2111742238908731817 ） | Matt Pocock 通用 skill：动手前反过来问清需求；可丢给 Grok Bot 存 Notion。非 Grok 专属，作 Skills 旁链即可 | Skills / Learning | **X** @limuvibecoding + gh |
| Notion 3.8 Context for agents | https://www.notion.com/releases/2026-10-13 | 工作区作共享 Agent 记忆，MCP 后 Claude/Muse/GrokBot 可换模型不丢上下文；产品信号，非玩法仓 | Learning | **X** @yoon_nnll |

### Maybe / Skip（白天 ~17:17）

| 名称 | 链接 | 原因 |
|------|------|------|
| swordBluesy 编译 AlexFinn「自动小公司」 | https://x.com/swordBluesy/status/2111739969077215680 | 营收故事向；Side Hustle CEO 模板已 Skip；不写金额、不升格 |
| plus4648 opencode+DeepSeek 白嫖 | https://x.com/plus4648/status/2111747512881320403 | 与范凯 Pi+DeepSeek 调度同向，无新仓；轻信号即可 |
| 注册/订阅保姆教程 | https://x.com/aicygg888/status/2111740231435383088 | 入门营销文，无玩法配方 |
| jordangarrison/grok-bot-flake | https://github.com/jordangarrison/grok-bot-flake | Nix 打包桌面端，非玩法/技能清单 |
| 空/个人 grok-bot 同名仓（rshun 等） | 多 | 0★ 无描述，跳过 |
| Hyperliquid / 灰色变现同模板 | 多 | 偏离本仓 |

### 给 Claude loop 的合并建议

1. **优先**：`robbin/grokbot-local-agent`（MIT、今日推、含 skill+routine+教程）→ Multi-bot / Skills；短评点出 webhook 唤醒 + `pi-task pending` 幂等补报；可与本仓 Claude↔Grok git 交接对照一句（勿写内部路径）。
2. **Multi-bot 模板库**：`rosterroom`（82 套）进 Multi-bot；License 为 NOASSERTION，短评注明。
3. **交接模式**：`grok-bots-handoff-lab` 作 Learning/Skills 短评（聊天外记忆）；`blotato-skills` 作 marketing skills 旁链并注明无 SPDX、源自 Claude。
4. **安全 / Routine**：范凯桌面安全默认 + robotshelp Test run → field-notes / routine-budget。
5. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 白天 2026-10-18 ~19:15（Asia/Shanghai）

- **窗口**：白天 ~17:17 → ~19:15（约 2h）；周日
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all` / `search_news`（start_time≥2026-10-18T09:00Z，中英）+ `gh search` / README 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：robbin/local-agent / rosterroom / handoff-lab / blotato / coolxeo / doitian / root-agent / AI_Acq / eze web-access / clipper（~13:10–17:17 已列）不重复列；clipper 现 ★18（早窗记 0，可升格门槛复查）

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| fredericalix/my-botstack | https://github.com/fredericalix/my-botstack （帖 https://x.com/fax_v2_0/status/2111747090195833285 ） | MIT 硬件全栈：StackChan / Waveshare ESP32 接 xAI realtime voice；做不了的事 webhook+MCP 交给 Grok Bot 再朗读。含 QUICKSTART、fleet MCP、签名 OTA、Docker Compose。Hardware 节可与 groki-bot 并列 | Hardware / Skills | `hardware` `esp32` `voice` `mcp` `webhook` `mit` | 0 / MIT | **X** @fax_v2_0 + gh（今日开源） |
| AgwaB/grok-bot-agents | https://github.com/AgwaB/grok-bot-agents | 今日新插件：在 Bot 云电脑上装/导入/驱动 Claude Code、Codex、Pi、omp；`delegate-task` 按轻重路由，`agent-bridge-webhook` 跨机交接。可与 `robbin/grokbot-local-agent`、audit 同作者线互链 | Skills & Playbooks / Multi-bot | `skill` `delegation` `claude-code` `codex` `webhook` `mit` | 0 / MIT | **GitHub**（今日建） |
| amplifthq/openmeld | https://github.com/amplifthq/openmeld | ~1362★ MIT：人与 Agent（含 Grok Bot / Codex / Claude Code / Cursor）共享上下文、并行协作的开源系统。README Self-hosted / Multi-bot 缺口大项，短评需写清与 orca/Codync 差异 | Multi-bot teams / Self-hosted | `multi-bot` `collaboration` `desktop` `mit` | 1362 / MIT | **GitHub**（近窗仍在推） |
| twhit223/grok-bot-cos | https://github.com/twhit223/grok-bot-cos | MIT Chief of Staff 配方仓：skills/ + 四条 routines（日焦/收工/会前/周五收束）+ CONVENTIONS；已脱敏可粘贴。与 marketplace「Chief of Operations」模板互补 | Skills & Playbooks / Routines | `chief-of-staff` `skills` `routines` `mit` | 2 / MIT | **Web** + gh |
| Olivia295/grokbot-teamwork-UI | https://github.com/Olivia295/grokbot-teamwork-UI | 中英「Bot协作室」：只读本机缓存，把多 Bot 交接演成会动的办公室（工作室/关系网/时间线）；零依赖 Python、不上传。多 Bot 可视化样板 | Multi-bot teams / Chinese | `multi-bot` `visualization` `local` `chinese` `mit` | 0 / MIT | **GitHub**（今日） |
| Liu-zhongxian/zongzhu-esp32-grok-bot | https://github.com/Liu-zhongxian/zongzhu-esp32-grok-bot （帖 https://x.com/Liu_zhongxisn/status/2111771018360754509 ） | 中文圆屏 ESP32 语音终端：唤醒→Webhook→Bot→字幕+朗读；MIT。与 my-botstack / groki-bot 同属 Hardware，板子型号不同 | Hardware / Chinese | `hardware` `esp32` `voice` `chinese` `webhook` `mit` | 0 / MIT | **X** + gh |
| puzzle-app/grokbot-delivery-team | https://github.com/puzzle-app/grokbot-delivery-team | 13 Bot 流程咨询交付队：CoS 路由、Delivery Lead 不执行、Claude Code 干活、客户 Puzzle 地图作共享记忆；MIT 脱敏配方。多 Bot 垂直场景样板 | Multi-bot teams | `multi-bot` `delivery` `claude-code` `mit` | 0 / MIT | **GitHub** |
| Useful Bots（模板站） | https://usefulbots.pages.dev （帖 https://x.com/karatademada/status/2111776285626097864 ） | 免费创作者向 Grok Bot 模板目录（Video/Growth/Launch 等），可作 Learning / Templates 灵感库；非 GitHub，质量需抽检 | Learning / Templates | `templates` `directory` `creators` | 站 / — | **X** @karatademada |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Routine「先比哈希再跑」 | https://x.com/fleyta88/status/2111755167309681010 （同构 https://x.com/gippp69/status/2111776276025315594 · https://x.com/biektive/status/2111757125168886133 ） | 每 5 分钟空跑烧额度；先 hash/diff，无变化毫秒跳过，有变化才起草并等人点。直接喂 `examples/routine-budget.md` | Routines | **X** |
| 一 Bot 一文件 + HANDOFF.md | https://x.com/orvexus/status/2111750828260216961 | 每 Bot 只写一个产物文件（trending/pain/SPEC），每轮打开 HANDOFF.md。作战室文件交接短链 | Multi-bot / Learning | **X** @orvexus |
| 中文：16 篇实战合集打包 | https://x.com/web30708/status/2111776554078646520 | 「从 0 到能交活」合集帖；可挂 Learning，逐篇核存活后再精选进 community-tutorials | Chinese / Learning | **X** @web30708 |
| RongleCat/grok-bot-learn | https://github.com/RongleCat/grok-bot-learn | 铁柱学习站（bot.tiezhu.si / bot.fmcat.top）源码仓；README Learning 已收站点，可补「源码在此」旁链。无 SPDX 文件需注明 | Learning / Chinese | **GitHub** |
| uniplanck/multipane-browser | https://github.com/uniplanck/multipane-browser | 非官方 macOS 多窗格浏览器专盯多 Bot 聊天：未读高亮、广播发送、用量只读。MIT，0★，Tools/Maybe | Skills / Tools | **GitHub** |
| clipper ★ 复查 | https://github.com/RongleCat/grok-bot-clipper | 早窗 ★0 → 现 ★18；过「≥10★」暂缓门槛，可优先合入 Skills/Chinese | Skills / Chinese | gh |

### Maybe / Skip（白天 ~19:15）

| 名称 | 链接 | 原因 |
|------|------|------|
| RoyeBot/barcode-scanner | https://github.com/RoyeBot/barcode-scanner | 窄场景 PWA 扫码查产地，玩法薄 |
| jolynestarchaser/War-room-agent-skills | https://github.com/jolynestarchaser/War-room-agent-skills | 无描述、无 License、1★ |
| RDV1113「16 templates / SEO prompts」长文 | https://x.com/RDV1113/status/2111768380218712324 | 聚合营销文、文章链 404，跳过 |
| Kontentsukpi「Department of Efficiency」 | https://x.com/Kontentsukpi/status/2111775640856764478 | 带金额宣称的采购审计故事，偏离 |
| 一人公司 6 Bot / 7-Day Setup 再发 | Skaly__Bull / 0xfuckpoverty 等 | 与 ~15:12 AI_Acq / Side Hustle 同构，不升格 |
| 交易桌 / Hyperliquid 同模板 | 多 | 偏离本仓 |
| 空/个人 grok-bot 同名仓 | 多 | 0★ 无配方 |

### 给 Claude loop 的合并建议

1. **优先**：`amplifthq/openmeld`（★高、MIT、README Multi-bot/Self-hosted 缺口）— 短评写清「人+多 Agent 协作系统，含 Grok Bot」，并与 orca / Codync 区分。
2. **Hardware 双新**：`my-botstack`（英文全栈+MCP fleet）与 `zongzhu-esp32-grok-bot`（中文圆屏 Webhook）并列；可与既有 groki-bot 互链。
3. **委派层**：`AgwaB/grok-bot-agents` 与已推 `robbin/grokbot-local-agent` 对照（云电脑 CLI 路由 vs 本机 Pi+Webhook）。
4. **可粘贴配方**：`grok-bot-cos`（CoS skills+routines）、`grokbot-delivery-team`（13 Bot 咨询队）、`grokbot-teamwork-UI`（可视化）。
5. **升格**：clipper ★18 → 可出暂缓表；routine-budget 补「哈希跳过」一句。
6. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。
## 白天 2026-10-18 ~21:16（Asia/Shanghai）

- **窗口**：白天 ~19:15 → ~21:16（约 2h）；周日
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-18T11:10Z，中英）+ `gh api` / Web 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：openmeld / my-botstack / AgwaB / grok-bot-cos / teamwork-UI / zongzhu / delivery-team / Useful Bots / robbin/local-agent / rosterroom / handoff-lab / blotato / coolxeo / clipper（~13:10–19:15 已列）不重复列；clipper 现 ★22（早窗 0→18→22）

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| kydlikebtc/awesome-grokbot | https://github.com/kydlikebtc/awesome-grokbot （站 https://kydlikebtc.github.io/awesome-grokbot/ ） | ~361★ 双语 live-share 目录：链接日检、行级出处、JSON schema+CI；今日仍在推。与 ZeroPointRepo/awesome-grok-bot 互补（后者偏生态导航，本仓偏可 Add 分享索引）。License 为 NOASSERTION，短评需注明 | Learning | `awesome` `templates` `live-share` `chinese` `bilingual` | 361 / NOASSERTION | **GitHub**（今日 push） |
| majiayu000/awesome-grok-bot | https://github.com/majiayu000/awesome-grok-bot （站 https://majiayu000.github.io/awesome-grok-bot/ ） | ~68★ CC0：~4800 条 live `x.ai/bot` 分享 + shelf 分层 + 双语 README；kydlikebtc 上游之一。README Learning 缺口大项，短评写「可 Add 分享索引，非提示词堆」并提醒社区分享不可信、需自检 | Learning | `awesome` `templates` `live-share` `chinese` `cc0` | 68 / CC0-1.0 | **GitHub** + web |
| X Post Tracker（Karol 模板） | https://x.ai/bot/LrOzcsX5ITCY0SfXLmhJn （帖 https://x.com/blueemi99/status/2111804487157563516 ） | 只读追自己帖：日摘要、暴涨提醒、预估互动；不点赞/发帖/回复。与 donvitocodes「X Post Tracker」（Melvin）同名不同 share，可并列 Templates / Routines | Routines / Templates | `template` `x` `routine` `read-only` | 模板 / — | **X** @blueemi99 |
| Research by Trond | https://x.ai/bot/v3WI0YuJAr1DLoYdYVXh8 （帖 https://x.com/xenappblog/status/2111797929518170506 ） | 入门向 Research Agent 模板：公开对话→带引用简报；可配 ScrapeCreators 拉 X/YT/TT/Reddit。适合 Learning / Templates 旁链，短评勿写成付费导流 | Learning / Templates | `template` `research` `scrape` | 模板 / — | **X** @xenappblog |
| mergisi/awesome-grokbot | https://github.com/mergisi/awesome-grokbot | 18★ CC0：可粘贴 profiles / skills / team 模板（Sales/Eng/Success 起步队）。体量小于 majiayu/kydlike，作「小而可抄」旁链即可 | Skills & Playbooks / Learning | `awesome` `templates` `teams` `cc0` | 18 / CC0-1.0 | **GitHub** |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 发帖幂等：先搜再重试 | https://x.com/sisiliu517/status/2111804317329944920 | 无成功 toast 时盲重试会双发；先读 API 查近期帖→仅缺失才重试→发后核对恰一条。与同作者「静默时段」互补，可喂 `examples/routine-budget.md` | Routines | **X** @sisiliu517 |
| 中文：活分两套不押一家 | https://x.com/Chengengye/status/2111798900017471983 | 编码押 Codex；交付分 Grok Bot + 飞书两套 bot，防单平台封号。中文一人公司韧性短链 | Chinese / Learning | **X** @Chengengye |
| Secrets：共享电脑 + Routine 烧额度 | https://x.com/0xNotFounder/status/2111796748678988027 （转述 https://x.com/whaleyxbt/status/2111805314114703513 ） | 多 Bot 共用一台云电脑（文件/cookies/登录）；15min routine×96/日易烧额。可链 field-notes / routine-budget；文章链偶发 404，以帖内要点为准 | Learning / Routines | **X** |
| 云电脑装 CLI 当总指挥 | https://x.com/punkcan/status/2111798438090428767 | Bot 电脑装 Grok builder / Claude Code / Codex CLI，大总管按项目延续 Session、优先 Skills。与已推 `AgwaB/grok-bot-agents` 同向，作体感短链即可 | Multi-bot / Skills | **X** @punkcan |
| Bot+t3codes+pstack 交叉评审 | https://x.com/AojDevStudi0/status/2111793282124542427 | 在 T3 Code Bridge 上加 poteto-mode 规划、跨模型评审、CI 门禁，只上交真决策。pstack 早窗已列，作工程向信号 | Skills / Learning | **X** @AojDevStudi0 |
| 中文：例程从 Grok 迁到本机 Claude | https://x.com/wangchuanqi_111/status/2111803490985271510 | 早报/实战日报/X 收藏→Obsidian 三例程搬家笔记；可作「可迁移例程」Learning 旁链（勿写内部路径） | Chinese / Routines | **X** @wangchuanqi_111 |
| clipper ★ 再复查 | https://github.com/RongleCat/grok-bot-clipper | ★18→★22；继续优先合入 Skills/Chinese | Skills / Chinese | gh |

### Maybe / Skip（白天 ~21:16）

| 名称 | 链接 | 原因 |
|------|------|------|
| PC Mechanic 模板 | https://x.ai/bot/bB9_Y8I-zNk_9s3eIwmq- （帖 https://x.com/Austinsdomain/status/2111785703420092425 ） | 装/卸软件 + Windhawk 美化，玩法窄、偏桌面运维 |
| ShuhangGe/grokbot-queue | https://github.com/ShuhangGe/grokbot-queue | MIT 并行派活 CLI，但 0★、靠 Electron UI 自动化，脆弱；Tools/Maybe |
| heyrobinai「20 bots while i sleep」长贴 | https://x.com/heyrobinai/status/2111806812148437333 | 营销向全指南，无新仓；一人公司 6Bot 同构已 Skip |
| JulianGoldieSEO AI SEO 流水线 | https://x.com/JulianGoldieSEO/status/2111799212505780327 | SEO 营销文，无配方仓 |
| vankhucstudio Inbox Watch $99 | https://x.com/vankhucstudio/status/2111796943374479849 | 付费代建，偏离本仓 |
| Hagglebot / 省钱审计长文 | https://x.com/vadimvchumak/status/2111806374686421342 | 金额故事向，跳过 |
| bl888m「Full Course」文章 | https://x.com/bl888m_eth/status/2111807986813251951 | 文章链 404，无法核 |
| 统一订阅额度抱怨 / 入门客服贴 | 多 | 产品吐槽与注册话术，无玩法 |

### 给 Claude loop 的合并建议

1. **优先**：`kydlikebtc/awesome-grokbot`（★高、今日仍推、双语 live-share）与 `majiayu000/awesome-grok-bot`（CC0 上游）进 Learning；短评区分 ZeroPointRepo（生态导航）vs 这两仓（可 Add 分享索引），并写清 NOASSERTION / 社区分享需自检。
2. **模板**：Karol「X Post Tracker」与 Trond「Research」作 Templates/Routines 旁链；与 Melvin/donvitocodes 同名 Tracker 区分 share id。
3. **routine-budget**：补「发帖幂等：先搜再重试」+ 共享电脑烧额提醒一句。
4. **升格**：clipper ★22；中文韧性（Chengengye）可挂 Chinese solo-founder 短链。
5. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## 白天 2026-10-19 ~09:13（Asia/Shanghai）

- **窗口**：白天 ~21:16（10-18）→ ~09:13（10-19）（约 12h 过夜窗）；周一上午
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-18T13:10Z，中英；github.com / template / skill 过滤）+ `gh search` created≥2026-10-18 + README/License 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：openmeld / my-botstack / AgwaB / grok-bot-cos / teamwork-UI / zongzhu / delivery-team / rosterroom / handoff-lab / blotato / coolxeo / clipper / kydlikebtc / majiayu000 / mergisi / Karol Tracker / Trond Research / ai-tool-inventory / grokbot-docker（~13:10–21:16 已列）不重复列；clipper 现 ★36（早窗 0→18→22→36）

### 推荐入清单（白天新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| doublesq97-ui/bot-team-playbook | https://github.com/doublesq97-ui/bot-team-playbook | MIT 中文「一人一支 Bot 队」：8 场景 ×（1 主管+3–4 专员）、35 份可粘贴人设、7 段 prompt 骨架、共享目录验收 + 可装 `skill/SKILL.md` 自建队。与 war-room / rosterroom 互补（本仓偏可抄中文配方） | Multi-bot teams / Chinese | `multi-bot` `playbook` `chinese` `supervisor` `mit` | 1 / MIT | **GitHub**（昨夜建） |
| noisyloop/Fleet-51 | https://github.com/noisyloop/Fleet-51 | MIT 本机舰队：Mac App + Ollama，每 bot 独立文件夹沙箱；今日发 v0.2.0。开源「自有订阅跑多 Agent」平替入口，可与 orca / Codync / openmeld 并列 Self-hosted | Self-hosted bots / Multi-bot | `self-hosted` `fleet` `ollama` `desktop` `mit` | 0 / MIT | **GitHub**（今日 release） |
| dim-pan/overtime | https://github.com/dim-pan/overtime | Apache-2.0 自托管指挥台：对标 OpenAI dots / Grok Bot，VM 模板上跑 Claude Code/Codex 舰队（目标百级）、Mac/iOS 原生看工。README Multi-bot/Self-hosted 缺口；短评写清「自有服务器上的 always-on 员工」 | Self-hosted bots / Multi-bot | `self-hosted` `fleet` `vm` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（昨夜） |
| ehteshambuildagents/grokbot（LocalCrew） | https://github.com/ehteshambuildagents/grokbot | Apache-2.0 本地队友平台（仓名 grokbot、产品名 LocalCrew）：Ollama / OpenAI 兼容、技能/例程/团队、浏览器+受限终端；明确非 xAI 附属。可作 Self-hosted 旁链（诚实列出 Known issues） | Self-hosted bots | `self-hosted` `ollama` `local` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（今晨） |
| vliuyt/grok-bot-esp32-bridge | https://github.com/vliuyt/grok-bot-esp32-bridge | Apache-2.0 微雪圆屏 ESP32 陪伴宠 + **Mac 原生语音桥**接已登录 Grok Bot（非另起 STT/TTS）。与 my-botstack / zongzhu 同属 Hardware，差异是桌面 App 契约桥接（需注明非公开稳定 API） | Hardware / Chinese | `hardware` `esp32` `voice` `macos` `chinese` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（昨夜） |
| shagghiesuperstar/veilbreaker | https://github.com/shagghiesuperstar/veilbreaker （帖 https://x.com/PixelRainbowNFT/status/2111893498454741468 ） | MIT 零依赖插件：扫隐藏注入/外泄 TTP（`safe_fetch`/`scan`/`egress_check`），带诚实 scope 与 SSRF 护栏。可喂 field-notes / 安全体检；短评强调「检测≠拦截宿主工具」 | Skills & Playbooks | `security` `prompt-injection` `plugin` `mit` | 0 / MIT | **X** + gh |
| cs68614-hash/awesome-grokbot-templates | https://github.com/cs68614-hash/awesome-grokbot-templates （站 https://grokbot-templates.com ） | CC0 多语种模板目录：只收官方 `x.ai/bot` 分享链（不重托管 prompt），站可搜可提交。与 kydlikebtc/majiayu（live-share 索引）互补：本仓偏分类浏览站 | Learning | `awesome` `templates` `directory` `cc0` | 3 / CC0-1.0 | **GitHub**（今日仍推） |
| Fleet Lead（模板） | https://x.ai/bot/mOunuXA9lKjg8sWImIzgy （帖 https://x.com/CaliLumberJack/status/2111981547381211560 ） | 多 Bot 总指挥：浏览器轮流、只上报完工、对外动作等人点。可作 Multi-bot / Templates 旁链，与 supervisor 模式互证 | Multi-bot teams / Templates | `template` `multi-bot` `browser` `approval` | 模板 / — | **X** @CaliLumberJack |
| NanNnnn0/codex-relay | https://github.com/NanNnnn0/codex-relay | MIT Windows-first MCP：Grok Bot 编码任务委派 Codex（worktree + session 队列）。与 AgwaB / robbin/local-agent 同向，短评点「Windows 命名管道」差异 | Skills & Playbooks | `skill` `codex` `mcp` `windows` `mit` | 0 / MIT | **GitHub** |
| panpanpandas/ai-video-maker-plugin | https://github.com/panpanpandas/ai-video-maker-plugin | MIT-0 视频 Skill：先报价→批额度→幂等 task/resume；带 provenance 哈希。可作「花钱动作必须先批」样板，挂 Skills / routine-budget | Skills & Playbooks | `skill` `video` `budget` `mit-0` | 0 / MIT-0 | **GitHub**（今晨） |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Claude Code 手机派活模板 | https://x.ai/bot/aB0M7wQOAcFgd_G0rTEWF （帖 https://x.com/thecsguy/status/2111986186784743932 ） | Mac 上 Claude Code：短信派活→同 session 回执。与 AgwaB/robbin 同构，作 Templates 短链即可 | Templates / Skills | **X** @thecsguy |
| 装模板前先读清单 | https://x.com/kaizenpromptlab/status/2111986652369256672 | 模板会原样复制 skills/memories/integrations，当软件安装审。可挂 Learning / field-notes | Learning | **X** |
| Claude→GrokBot 权限对齐 | https://x.com/ChenAaron/status/2111987811872333904 | 让 Claude 据已有 rules/hooks 总结 ask-first / always，再写入 GrokBot 配置。护栏迁移短链 | Skills / Learning | **X** @ChenAaron |
| EverOS 三层记忆（团队交接） | https://x.com/R7Ruk/status/2111984352754339878 | User / Agent Memory 分层 + Case→Skill；Grok Bot 可走 API/MCP。作 Multi-bot 记忆信号（勿升格付费站） | Multi-bot / Learning | **X** @R7Ruk |
| 网页变更只叫醒 | https://x.ai/bot/CEK-EsCiOWcB8NBzSYnEx （帖 https://x.com/teeRex247/status/2111981455077466525 ） | 贴链+关注条件→快照，变了才 ping。喂 `examples/routine-budget.md`（与哈希跳过同向） | Routines | **X** @teeRex247 |
| 中文：任务怎么说清楚 01/10 | https://x.com/santoslee_me/status/2111989490885841110 | 目标/输入/红线/产出/验收五件套；可挂 Learning / Chinese | Chinese / Learning | **X** @santoslee_me |
| 中文：Grok Bot 连微信实操 | https://x.com/bilion1983/status/2111975514059702352 | 文章向实操手册；README 已有 grok-bot-wechat，作旁链核存活即可（勿写内部路径） | Chinese | **X** @bilion1983 |
| 中文：一人内阁第 1 篇 | https://x.com/zsredeemer/status/2111827456739152348 | 「别再养全能 Agent」分角色内阁；与 bot-team-playbook 同向信号 | Chinese / Multi-bot | **X** @zsredeemer |
| X 不可见字符注入提醒 | https://x.com/momiji_manjyuu/status/2111831951841911286 （多转） | 让 Bot 读 X 时可能踩隐藏 prompt injection；与 veilbreaker 互链 field-notes | Learning / Security | **X** |
| clipper ★ 再复查 | https://github.com/RongleCat/grok-bot-clipper | ★22→★36；继续优先合入 Skills/Chinese | Skills / Chinese | gh |

### Maybe / Skip（白天 ~09:13）

| 名称 | 链接 | 原因 |
|------|------|------|
| Statusnone420/agent-skills | https://github.com/Statusnone420/agent-skills | README 已写 Cursor/Grok Bot host **retired**，主打 Codex/Claude | 
| cahenesy/grokbot-messages | https://github.com/cahenesy/grokbot-messages | Apache-2.0 干净室 Messages MCP，但 Phase 1 **尚不可用**；观望 |
| alinaqi/phrok-plugin | https://github.com/alinaqi/phrok-plugin | 真电话 MCP，但托管付费分钟包；作信号即可，不进主清单 |
| lukewang4862/AI-Usage | https://github.com/lukewang4862/AI-Usage | macOS 用量浮窗，无 SPDX License |
| lenML/gbot-ui | https://github.com/lenML/gbot-ui | React UI 复刻库，偏前端非玩法配方 |
| Boom-Vitt creator-packs / bbnw | 两仓 | 泰语模板，无 License |
| SOWashignton2026/price-check-extension | https://github.com/SOWashignton2026/price-check-extension | 窄场景比价扩展 |
| promptmates/grokbots | https://github.com/promptmates/grokbots | 个人模板堆，薄 |
| brain-xiang/grok-studio | https://github.com/brain-xiang/grok-studio | Roblox 一键，偏离本仓 |
| PuroBots Ko-fi 付费包 | https://x.com/PuroBots/status/2111984435532857673 | 付费 PDF 包，偏离开源清单 |
| 交易自动跟单 / Hyperliquid | 多 | 偏离本仓 |
| 空/个人 grok-bot 同名仓 | 多 | 0★ 无配方 |
| bl888m Full Course 再发 | 早窗已 Skip（链易 404） | 不升格 |

### 给 Claude loop 的合并建议

1. **优先**：`doublesq97-ui/bot-team-playbook`（中文可抄多 Bot 主管模式）进 Multi-bot / Chinese；短评点 8 场景 + 共享目录验收，可与 `examples/war-room.md` / rosterroom 互链一句。
2. **Self-hosted 三新**：Fleet-51（本机 Ollama 舰队 App）、overtime（自有 VM 指挥台）、LocalCrew（本地队友）— 短评区分「桌面 App / 服务器舰队 / 本机 Ollama」，并与 orca·Codync·openmeld 对照。
3. **Hardware**：`vliuyt/grok-bot-esp32-bridge` 与已推 my-botstack / zongzhu 并列，强调 Mac 原生语音桥 + 非公开 API 契约风险。
4. **安全**：veilbreaker 进 Skills；routine-budget / field-notes 补「装模板先审」+「X 隐藏注入」+「网页变更才叫醒」。
5. **Learning**：`awesome-grokbot-templates`（站）与 kydlikebtc/majiayu 三分法写清；Fleet Lead / Claude Code 派活作 Templates 旁链。
6. **升格**：clipper ★36。
7. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md`。

## T7 日更 2026-10-19 ~10:37（Asia/Shanghai）

- **窗口**：白天 ~09:13 → ~10:37（约 1.5h）+ 近 24h 补漏；周一 T7
- **负责**：Grok Awesome T7 日更雷达（routine awesome-t7）
- **方法**：X `search_posts_all`（start_time≥2026-10-18，中英 + github/paseo/locum）+ `gh search` created≥2026-10-18 + README/License 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名
- **注**：bot-team-playbook / Fleet-51 / overtime / LocalCrew / esp32-bridge / veilbreaker / awesome-grokbot-templates / Fleet Lead / codex-relay / ai-video-maker / rosterroom / root-agent / orca / field-notes / robbin/local-agent / clipper（白天已列）不重复列；clipper 现 ★39（早窗→36→39）

### 推荐入清单（T7 新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| getpaseo/paseo | https://github.com/getpaseo/paseo （站 https://paseo.sh ） | 本地优先多 Agent 编排：Claude Code/Codex/OpenCode/Pi 等并行 + worktree 隔离，桌面/手机均可控。中文圈今日热议作「别让云端 Grok Bot 直接碰本机」的平替入口；可与 orca / Fleet-51 / overtime 并列 Self-hosted。License API 为 NOASSERTION，短评需注明 | Self-hosted bots / Multi-bot | `self-hosted` `fleet` `desktop` `mobile` `paseo` | 21327 / NOASSERTION | **X** 讨论 + gh |
| HarjjotSinghh/locum | https://github.com/HarjjotSinghh/locum | Apache-2.0：Grok Bot 经自定义 MCP + 隧道把编码活委派给本机已登录 Claude Code/Codex；不碰凭证、只 spawn 官方 CLI。与 AgwaB / robbin/local-agent / codex-relay 同向，差异是「云端 Bot → 本机订阅」委派层 | Skills & Playbooks / Multi-bot | `mcp` `delegate` `claude-code` `codex` `apache-2.0` | 10 / Apache-2.0 | **GitHub**（今日仍推） |
| mikecann/delegate | https://github.com/mikecann/delegate | MIT 今日新仓：主 Claude Code 会话把手活/评审/研究派给 Codex、Grok、Muse 或其他 Claude 账号；含多厂共识与额度钩子。偏本机 CLI 编排，可作 Skills 旁链（★0，短评写清「个人工具可 fork」） | Skills & Playbooks | `delegate` `multi-cli` `consensus` `mit` | 0 / MIT | **GitHub**（今日建） |
| FelixIsaac/cmux-orbit | https://github.com/FelixIsaac/cmux-orbit | MIT：手机端 Mission Control，经 Tailscale 原生跑 Claude Code / Grok CLI / Codex / Pi 等。与 Paseo 手机控本机同向，可挂 Self-hosted / Hardware 旁链 | Self-hosted bots | `mobile` `tailscale` `cmux` `mit` | 0 / MIT | **GitHub**（昨夜） |
| spa77k/web-research-skill | https://github.com/spa77k/web-research-skill | Grok Bot/Cursor 式 SKILL：强制上网核实、优先官方源、结论先行 + 出处链接。可作 Skills 小样（无 SPDX License，短评提醒） | Skills & Playbooks | `skill` `research` `japanese` | 0 / none | **GitHub**（今日建） |

### 玩法 / 产品信号（无强仓，Learning / Routines 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 手机派活→本机 Agent 的安全风险 | https://x.com/fankaishuoai/status/2111978651797569600 | 云端 Bot 读外部内容后再控本机 Agent 有注入面；主张关本机执行、改用 Paseo 类本地编排。与已收「桌面安全默认」同向，宜并进 field-notes | Learning / field-notes | **X** @fankaishuoai |
| NextToken：Grok Bot / Muse 体感圆桌 | https://x.com/vista8/status/2111980748135903566 （小宇宙 https://www.xiaoyuzhoufm.com/episode/6ad50a05641ef406308d957a ） | 中文播客聊 Personal Agent 实操与「干活还是过家家」；可挂 Chinese / Learning 旁链（勿写内部路径） | Chinese / Learning | **X** @vista8 |
| Grok Bot 总管 Hermes + OpenClaw | https://x.com/MichaelGannotti/status/2112005427797938371 | 上层审批门：不合并/部署/发帖/花钱除非人点 yes。与 Fleet Lead / supervisor 模式互证 | Multi-bot / Templates | **X** @MichaelGannotti |
| 多玩家：Grok↔Claude 交接 | https://x.com/BenENewton/status/2112005826994979196 | 单玩家 Agent 互不知情；用共享层让两边看到彼此产出。可作 Multi-bot 记忆/交接信号 | Multi-bot / Learning | **X** @BenENewton |
| Personal Agent = 岗位不是聊天框 | https://x.com/zengge1984/status/2112000541576569075 | 知识库+方法论+每日交付才分水岭。中文一人公司心智短链 | Chinese / Learning | **X** @zengge1984 |
| 模板发现：描述工作→链 Bot 模板 | https://x.ai/bot/changelog （帖 https://x.com/OptimusG2026/status/2112001434774556908 ） | 产品内「说清岗位→推荐模板」；可挂 Learning 产品提示 | Learning | **X** + changelog |
| clipper ★ 再复查 | https://github.com/RongleCat/grok-bot-clipper | ★36→★39；继续优先合入 Skills/Chinese | Skills / Chinese | gh |

### Maybe / Skip（T7 ~10:37）

| 名称 | 链接 | 原因 |
|------|------|------|
| Root Agent v0.3.2 版本贴 | https://x.com/mrbeko_/status/2111950616708690103 | 仓已列；仅 skills 刷新，不重复 |
| Tongyi OpenGCUA | https://github.com/Tongyi-MAI/OpenGCUA | 通用 CUA 技术栈，非 Grok Bot 配方 |
| Clean Room / Hermes Adversary 模板 | https://x.ai/bot/X0H6z06mMxX2873lc5sCa 等 | 与已收 veilbreaker 同作者线；无独立可核仓则暂旁观 |
| zambo.dev 收据 MCP | https://zambo.dev | 付费/产品向，偏离本仓薄目录 |
| Thulr/galaxy-bot | https://github.com/Thulr/galaxy-bot | ★0 桌面 Tauri 驱动 CLI，与 orca/Paseo 重叠且尚早 |
| goal-flight / harness-subagent | https://github.com/simonrowland/goal-flight · https://github.com/realspqrk/harness-subagent | 相关但近 24h 无新信号；待周更再扫 |
| 农场 Field Notes 模板 / 客服吐槽帖 | 多 | 垂直 niche 或投诉，无配方 |

### 给 Claude loop 的合并建议

1. **优先**：`getpaseo/paseo`（体量最大、今日中文安全讨论锚点）与 `HarjjotSinghh/locum`（云端 Bot→本机 Claude/Codex 委派，贴合本仓协作叙事）进 Self-hosted / Skills。
2. **旁链**：mikecann/delegate、cmux-orbit；field-notes 补「手机派活本机的注入面」一句（链范凯帖 + Paseo 平替）。
3. **升格**：clipper ★39；NextToken 播客可挂 Chinese Learning。
4. 未改 README；本提交只动 `inbox/candidates.md` + `.collab/to-claude.md` + TASKS 备注。

## 白天 2026-10-19 ~11:16（Asia/Shanghai）

- **窗口**：T7 ~10:37 → ~11:16（约 40 分钟）+ 近 24h gh 补漏
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-19 02:30 UTC）+ `gh search repos` created≥2026-10-18 + README/License 核实；相对 README + `inbox/candidates.md` 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| effi0724/grokbot-task-dashboard | https://github.com/effi0724/grokbot-task-dashboard | 多 Bot/Agent 进度看板：stdlib Python CLI `st` 本地记任务，Cloudflare Pages + D1 展示；按 Bot/任务类型做 ETA 自校准（实际/预估中位数 + p25–p75 区间）。中英双语 README，示例图标明 example data。与 rosterroom / teamwork-UI 同为「作战室可视化」，差异是 ETA 校准 | Multi-bot / War room | `dashboard` `eta` `cloudflare` `bilingual` `mit` | 0 / MIT | **GitHub**（10-18 建，今日仍推） |
| StefMVP/grokbot-exporter | https://github.com/StefMVP/grokbot-exporter | 导出 Grok Bot 会话、profile、skills、routines 与文件到私有目录（带校验清单），适合搬家/备份；与已收「例程搬家」信号互补。短评必须写清：浏览器 profile 副本含登录凭证，导出目录只能私存、勿入公开仓 | Skills & Playbooks / Learning（备份） | `export` `backup` `routines` `mit` | 0 / MIT | **GitHub**（今日建） |
| plaskettmj/avatar-animator | https://github.com/plaskettmj/avatar-animator | 本地 CPU 把静图做成 <5MB 循环 GIF/WebP 头像，无 API key；给多 Bot 队伍批量做头像的小工具。体量小，宜作 Tools 旁链 | Tools（旁链） | `avatar` `local` `mit` | 0 / MIT | **GitHub**（今日建） |

### 玩法 / 信号（无强仓，Routines / Learning 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 云电脑内存不够：监控 routine + swap | https://x.com/liuxu_qingdao/status/2112020059690549479 | 中文 Tips：routine 监控内存，超阈值清理不活跃 Bot（每个约 300MB），再让 Bot 开 swap。多 Bot 运维配方，可并进 field-notes | Routines / Chinese | **X** @liuxu_qingdao |
| 云电脑重建后自检修复 routine | https://x.com/liuxu_qingdao/status/2112015846122144126 | 同系列：routine 检测重启 → 校验环境 → 跑修复脚本（让 Bot 先写检测/恢复脚本）。与上一条合成「电脑韧性」一句 | Routines / Chinese | **X** @liuxu_qingdao |
| 第三方 API 当天加功能 → Bot 写出出行准备 skill | https://x.com/DBurkland/status/2112017140710883535 | Teslascope API 新增充电计划后，用户让 Bot 写「出发前充满+一次性计划」skill。Skill 场景示例（生活向），可作 Learning 旁链 | Learning / Skills | **X** @DBurkland |

### Maybe / Skip（~11:16）

| 名称 | 链接 | 原因 |
|------|------|------|
| zilliztech/Grokbot-Milvus-Plugin | https://github.com/zilliztech/Grokbot-Milvus-Plugin | 官方厂商新仓但暂无 README/License；下轮复查，有内容再升格 |
| desmondsir106-droid/grokbot-updates-slides(-cursor) | https://github.com/desmondsir106-droid/grokbot-updates-slides | 更新介绍幻灯片，无 License、非配方 |
| fpavia111-creator/hephaestus | https://github.com/fpavia111-creator/hephaestus | 通用 SKILL.md lint/打包，未提 Grok Bot；周更再看 |
| RyanZhu1024/grok-desk-bot | https://github.com/RyanZhu1024/grok-desk-bot | 无描述 |
| 「80% 任务由 Claude & GrokBot 完成」名人引语帖 | https://x.com/Carthusdjdk/status/2112008717994520777 | 引语未核实，不收 |
| orca 日推帖 | https://x.com/aoi_ai_hack/status/2112016854416027853 | orca 已列，仅热度信号 |

## 白天 2026-10-19 ~13:15（Asia/Shanghai）

- **窗口**：~11:16 → ~13:15（约 2 小时）
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-19 03:10 UTC）+ `gh search repos` created≥2026-10-18 + README/License 核实；相对 README + `inbox/candidates.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| TheSethRose/grokbot-bridge | https://github.com/TheSethRose/grokbot-bridge | 非官方 CLI + MCP server：在本机驱动 Grok Bot 桌面端，让 Claude Code / Cursor / Codex / 脚本给指定 Bot 派活、等回复、拿 Markdown/JSON 结果，还能停 Bot、查额度、增删改 Bot。正好补「Claude→Grok 反向委派」，与已收 locum（Grok→本机 Agent）成对。短评须写：非官方、靠自动化桌面 App，macOS 已测、Win/Linux 未测 | Multi-bot / Self-hosted & Tools | `cli` `mcp` `claude-code` `delegation` `unofficial` `mit` | 0 / MIT | **GitHub**（今日建） |
| ChamathRosh/grok-bot-templates | https://github.com/ChamathRosh/grok-bot-templates | 小商家「一 Bot 一职」模板 6 个（报价催办、未接来电回访、差评回复、催款、晨报等），统一只起草、发送/付款全部本人点头、缺信息留 `[FILL IN]` 不编数。审批闸写法可直接当模板范例；目前仅 1 个有安装链，其余 coming soon，README 末尾有作者导流站 | Templates | `small-business` `drafts-only` `approval` `mit` | 0 / MIT | **GitHub**（今日建） |

### 玩法 / 信号（无强仓，field-notes / Learning 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 结账三道闸 + 拍卡号绕过 Secure Form | https://x.com/__jingling/status/2112043625626448251 | 中文梳理：卡号走 Secure Form、金额卡片一笔一批、密码/验证码/付款确认由人接手；提醒「把信用卡拍照丢进聊天」会让卡号绕过 Secure Form 进入聊天记录。可并进 field-notes 安全默认一句 | Learning / field-notes / Chinese | **X** @__jingling |
| 长对话吃额度：开新会话 + 先存要点 | https://x.com/XStrangeHistory/status/2112029976581087535 | 用量小贴士：每次回复都会重读整段历史，长聊更耗额度，建议存要点后开新会话。机制说法未经官方核实，只宜作旁链/待核 | Learning（待核） | **X** @XStrangeHistory |
| （转 X 大 V 文章雷达）Grok Bot 保姆级新手指南·下篇 | https://x.com/LZJ5460/status/2112039869514150322 | 中文 X 长文，「带 AI 员工干活，附 27 段提示词」；属 docs/x-articles.md 范畴，交给文章雷达核实后再收 | x-articles | **X** @LZJ5460 |

### Maybe / Skip（~13:15）

| 名称 | 链接 | 原因 |
|------|------|------|
| vitalydolgov/grokbot-tunnel | https://github.com/vitalydolgov/grokbot-tunnel | 无描述无 README；下轮复查 |
| mynamezxc/Codex-Claude-Bot | https://github.com/mynamezxc/Codex-Claude-Bot | 「借鉴 Grok Bot 思路做 Win 版 Codex/Claude」，非 Grok Bot 配方，暂旁观 |
| ryofssmax-a11y/grokbot-puzzle | https://github.com/ryofssmax-a11y/grokbot-puzzle | Bot 做的小游戏成品，非可复用玩法 |
| TermiX Skills 链上接单 | https://x.com/MasterX093/status/2112037124736438693 | 链上市场/结算，偏推广，偏离本仓 |
| Hermes Adversary / VeilBreaker 长文 | https://x.com/PixelRainbowNFT/status/2112037561556152828 | 同作者线已在候选，仅热度 |

## 白天 2026-10-19 ~15:16（Asia/Shanghai）

- **窗口**：~13:15 → ~15:16（约 2 小时）
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-19 05:00 UTC）+ `gh api search/repositories` created≥2026-10-18 + README/License 核实；相对 README + `inbox/candidates.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| ScriptedAlchemy/grok-bot-cli | https://github.com/ScriptedAlchemy/grok-bot-cli | 终端管 Grok Bot：建/改/删 Bot 与群、发消息、拉 thread、装/卸 skills；走桌面端已登录会话，不必手拷 token。今日仍有 push。可与已收 grokbot-bridge（反向委派）并列 Tools | Tools / Multi-bot | `cli` `npm` `skills` `groups` `mit` | 113 / MIT | **GitHub**（今日仍推） |
| milind-soni/OpenMausBot | https://github.com/milind-soni/OpenMausBot | 开源 Grok Bot 平替：聊天式多 Bot、本地优先，底层跑本机 Claude / Codex / Grok CLI；有 Mac/Win/Ubuntu 安装包。早窗曾记「无清晰主仓」，现主仓与下载页齐全，宜升格 Self-hosted | Self-hosted | `alternative` `local-first` `apache-2.0` | 5145 / Apache-2.0 | **GitHub**（对照文升级） |
| treverhatch-glitch/hatchfield-ai-studio-template | https://github.com/treverhatch-glitch/hatchfield-ai-studio-template | 薄上下文 Producer 模板：状态落在 `NEXT.md` / `CURRENT_TASK.md` / skills，Grok Bot 当 Producer 派工写回；含 token 节流与被动 Workflow HUB。偏游戏制作，但「薄聊天、厚文件」可复用 | Templates / Multi-bot | `thin-context` `producer` `template` `mit` | 0 / MIT | **GitHub**（今日新建） |

### 玩法 / 信号（无强仓，field-notes / Routines / Learning 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Bot 自有邮箱订 newsletter + 晨报汇总 | https://x.com/CalvinHollywood/status/2112073281000055180 | 用 Bot 邮箱订阅，晨间 routine 只回一条短摘要，个人收件箱保持干净。7k 粉作者，配方清晰 | Routines / Learning | **X** @CalvinHollywood |
| 云电脑直接装 Claude Code，Bot 当 PM | https://x.com/0x3Matt/status/2112064390937690314 | 在 Grok Bot 电脑登录 Claude Code，让项目经理 Bot 直接带 Claude，省掉「本机↔云」两步跳。与 locum / grokbot-bridge 叙事互补 | Multi-bot / Self-hosted | **X** @0x3Matt |
| Original Content Rewards 下午四点 routine | https://x.com/TodayKan/status/2112077346190852413 | 固定四步：扫 24–48h 热帖 → ≥5 条原创主帖 → ≥10 条有信息互动 → 把选材理由回本聊天。可作 Routines 示例 | Routines / Chinese | **X** @TodayKan |
| 云电脑重置血泪：务必备份 | https://x.com/tspy/status/2112056388474351906 | OG 提醒：业务材料/技能/规范全在同一台云电脑，曾两次重置清空。可与已收 grokbot-exporter 并成「韧性」一句 | Learning / field-notes / Chinese | **X** @tspy |
| （转文章雷达）舰队架构全拆解 | https://x.com/tanglele0318/status/2112069782170173797 | 中文 X 长文「从单兵作战到舰队协同」；粉量与收藏偏低，交 docs/x-articles.md 雷达按门槛核后再收 | x-articles | **X** @tanglele0318 |

### Maybe / Skip（~15:16）

| 名称 | 链接 | 原因 |
|------|------|------|
| nwcnwc/gifos-broadcast-mcp | https://github.com/nwcnwc/gifos-broadcast-mcp | 有 `.grok-plugin` + skill，但 LICENSE 为 All rights reserved 专有许可，不适合 Awesome 默认收录 |
| Anil-matcha/open-dots | https://github.com/Anil-matcha/open-dots | ★高的通用 Agent 工作台，无 LICENSE 文件；同作者 open-grok-bot 已在 README |
| renyadav96/noodle | https://github.com/renyadav96/noodle | 今日新建，README/下载链指向已列的 pdparchitect/noodle，疑似镜像 |
| vitalydolgov/grokbot-tunnel | https://github.com/vitalydolgov/grokbot-tunnel | 仍无 README；维持上轮 Maybe |
| Taki1979/x-post-images | https://github.com/Taki1979/x-post-images | 仅「x posts from grok bot」素材堆，无配方 |
| EverOS Cloud 共享记忆推广 | https://x.com/crossbite65/status/2112067995757421022 | 产品推广，非开源配方 |

## 白天 2026-10-19 ~17:16（Asia/Shanghai）

- **窗口**：~15:16 → ~17:16（约 2 小时）
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-19 07:00 UTC，中英多查询）+ `gh search repos` created/updated≥2026-10-18–19 + README/License 抽查；相对 README + `inbox/candidates.md` + `.collab/to-claude.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| rfsbraz/genealogy-agent-skills | https://github.com/rfsbraz/genealogy-agent-skills | 家谱研究 Agent Skills 包（约 26 个 skill）：mode/interview/narrative 入口 + 证据交接信封；MIT，装法覆盖 Claude Code / Codex / Gemini / Cursor / Grok Bot（Connect apps 搜 Genealogy）。领域专但配方完整可复用 | Skills & Playbooks | `skills` `genealogy` `multi-host` `mit` | 0 / MIT | **GitHub**（10-18 建，今日仍推） |
| unhexx/grok-bot-mcq-group-roles | https://github.com/unhexx/grok-bot-mcq-group-roles | 拍照选择题多 Bot 组：VisionExtractor / SolverAlpha / SolverBeta / EvidenceCritic / FinalAnswer，五个 `.md` 直接贴进 Bot 人设；并行求解 + 证据对齐 + 只回字母。经典多 Bot 作战室小模板 | Multi-bot / Templates | `multi-bot` `group` `paste` `mcq` | 0 / 无 LICENSE | **GitHub**（今日新建） |
| 前台收件 Front Desk prompt | https://x.com/dunik_7/status/2112093261183483995 | 完整可粘贴：Bot 自有邮箱当前台；+leads / +invoices / +book 三套 alias routine；只起草不外发，超 $500 发票标红；先展示计划与样稿再执行。审批闸门清楚 | Routines / Templates | `routine` `email` `approval-gate` `prompt` | — | **X** @dunik_7（约 4.5k 粉） |

### 玩法 / 信号（无强仓，field-notes / Routines / Learning 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 6 Bot 协同小队（附模版） | https://x.com/ai_edisonZ/status/2112100886629544109 | 中文 X 长文「两周实测：把 6 个 Bot 拉进群搭协同小队（附模版）」；粉量与互动偏低，交 docs/x-articles 或 Learning 核后再收 | Multi-bot / Chinese / x-articles | **X** @ai_edisonZ |
| 云↔本机安全接力（待公开仓） | https://x.com/fankaishuoai/status/2112108533579927701 | 44k 粉作者主张 GitHub 管交接状态 + Webhook 唤醒 Bot，本地 Agent 自调度；称已写开源项目但推文未给公开仓链。与已收 robbin/local-agent（同机 Pi）叙事互补，**等公开 URL 再升格** | Multi-bot / Learning / Chinese | **X** @fankaishuoai |
| 省 token 攻略长文 | https://x.com/yz_chow/status/2112097880534380716 | X 长文「Grok Bot 终极省token攻略」；刚发互动极低，可作 Learning 观察 | Learning / Chinese | **X** @yz_chow |
| PC Helper 永不下线 | https://x.com/Tony_Omega/status/2112085478925107227 | X 长文：给 20+ 朋友当 IT，用 Bot 做永不下线的 PC Helper；偏个人案例，核干货后再定 | Learning | **X** @Tony_Omega |
| 亚马逊开店云电脑流 | https://x.com/TodayKan/status/2112099697318121895 | X 长文：用 Grok Bot 云电脑开亚马逊店从零上架；与已收 OCR 下午 routine 同作者，电商向 | Routines / Chinese | **X** @TodayKan |

### Maybe / Skip（~17:16）

| 名称 | 链接 | 原因 |
|------|------|------|
| Conviviera/conviviera-cursor-plugin | https://github.com/Conviviera/conviviera-cursor-plugin | 论坛 OAuth/MCP 连接器，非可复用玩法配方 |
| jinkkkang/grokbot | https://github.com/jinkkkang/grokbot | 沙箱学习摘录含 Cursor sand 专有脚本，「不构成再分发许可」——跳过 |
| Lyric-Song/DevBrain | https://github.com/Lyric-Song/DevBrain | 「Created via Grok Bot」演示仓，无配方 |
| SpaceDataRig/space-data-rig | https://github.com/SpaceDataRig/space-data-rig | 科学多 Agent 控制台，Grok 只占 critic 席，非 Grok Bot 配方主线 |
| xuejoker168 六人营销队转述 | https://x.com/xuejoker168/status/2112107232540397837 | 转述官方营销指南，非原配方仓 |
| CyberAlice3269 自媒体小队 | https://x.com/CyberAlice3269/status/2112098767151468645 | 粉量极低、无仓、口号式 |
| VORLEN_X Android TV | https://x.com/VORLEN_X/status/2112107551177203957 | 单机刷机向，偏离本仓 |
| KellehEyad 第一条 Routine 五步 | https://x.com/KellehEyad/status/2112091156163035579 | 入门口号，过薄 |
| Sukiea1008 8 身份手册 | https://x.com/Sukiea1008/status/2112084040362897441 | 已交 15:48 x-articles 雷达，不重复 |
| grok-bot-cli / OpenMausBot / hatchfield / local-agent / AgwaB / task-dashboard / bridge 等 | （见上轮） | 上轮 ~15:16 已列，本窗不重复 |

## 白天 2026-10-19 ~19:09（Asia/Shanghai）

- **窗口**：~17:16 → ~19:09（约 2 小时）
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（start_time≥2026-10-19 09:00 UTC，中英多查询）+ `gh search repos` created≥2026-10-19 + README/License 抽查；相对 README + `inbox/candidates.md` + `.collab/to-claude.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| francoCosimo95/claude-grok-bridge | https://github.com/francoCosimo95/claude-grok-bridge | Claude Code ↔ Grok Bot **原生 routine 互通**：双方走各自 vendor 的 inbox/webhook，无中间件、0 依赖；一句 BOOTSTRAP 装桥，`ask`/`tell`/`note` 协议；答案≠批准。与已收 TheSethRose/grokbot-bridge（桌面自动化驱动 App）成对：一条协议层、一条 UI 自动化层 | Multi-bot / Skills | `bridge` `claude-code` `routine` `protocol` `mit` | 0 / MIT | **GitHub**（今日 18:04 建，仍在推） |

### 玩法 / 信号（无强仓，field-notes / Routines / Learning / Hardware 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Jarvis skill + Oppo 心力球 / Garmin MCP | https://x.com/dontbesilent/status/2112119323011784875 | 约 9.3 万粉作者：把 Jarvis skill 挂 Grok Bot，接 Oppo 心力球与佳明手环 MCP，做全天上下文摘要（不依赖 APP 打开）。无公开仓，配方靠截图；可作 Hardware / Chinese 观察 | Hardware / Chinese / Learning | **X** @dontbesilent |
| 按职责拆 4 Bot 省 token | https://x.com/easywaydata/status/2112137844265521303 | SEO / 新增课程 / 加载优化 / 上线发布各一 Bot，避免单 Bot 一次加载太多。薄但可并入 Multi-bot「拆职责」一句 | Multi-bot / Chinese | **X** @easywaydata（约 2.6k 粉） |
| AR 六 Agent 控制室（先 cheap check） | https://x.com/fleyta88/status/2112114774632788357 | 概念演示：6 routine 分监控，有变化才唤醒全量 Agent + 夜间只起草；强化已收「先 hash/diff 再跑」。AR 界面非官方能力 | Routines / Learning | **X** @fleyta88 |
| 订阅/0 元周期登录提醒 | https://x.com/aWildWander/status/2112122567926657222 | 用 Bot 盯「0 元也要定期登录」类订阅，补专门 App 填不了 0 价的坑。帖未给可粘贴 prompt，先作 Routines 信号 | Routines / Chinese | **X** @aWildWander |

### Maybe / Skip（~19:09）

| 名称 | 链接 | 原因 |
|------|------|------|
| YOKEN21/grok-bot-cursor | https://github.com/YOKEN21/grok-bot-cursor | 「matter」平台变更合成仓：Grok Bot 房口头 `APPROVED` 审批，非可复用 Grok Bot 配方 |
| epsilo-ai/cursor-plugin | https://github.com/epsilo-ai/cursor-plugin | 零售广告只读 MCP（Epsilo One），垂类产品连接器，非通用玩法 |
| golddexzy-create/grok-memecoin-desk | https://github.com/golddexzy-create/grok-memecoin-desk | Solana memecoin 交易桌，偏离本仓 |
| paperclipai/paperclip | https://github.com/paperclipai/paperclip | ★10 万+ 通用 Agent 上班看板，README 未点名 Grok Bot；与 orca 相邻但非本仓主线 |
| Latand/delegatus | https://github.com/Latand/delegatus | 本机编排 Claude/Codex/Copilot，非 Grok Bot 配方 |
| iamrexei 五仓省 token | https://x.com/iamrexei/status/2112135088615862633 | 通用 MCP/Langfuse/Trigger.dev；作者自承改不了 Grok Bot 额度 |
| EbookPlan 电子书 | https://x.com/EbookPlan/status/2112124760012542101 | 软广，x-articles 雷达已跳过同类 |
| stablyai/orca 再推 | （多帖） | README 已收，仅热度 |
| ChamathRosh / grokbot-bridge / exporter / mcq / genealogy 等 | （见上轮） | 上轮已列，本窗不重复 |

## 白天 2026-10-20 ~09:18（Asia/Shanghai）

- **窗口**：~19:09（10-19）→ ~09:18（10-20）；上轮 21:22 白天雷达失败，本窗覆盖过夜 + 早间（Austin Hackathon 当晚大量新仓）
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：X `search_posts_all`（近夜中英）+ Mac `gh search repos` created≥2026-10-18 + README/License 抽查；相对 README + `inbox/candidates.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| sudoTomas/groknet | https://github.com/sudoTomas/groknet | **跨主人 Bot 社交层**：发现 → 人批好友 → webhook 中继；Teams 里 @ 谁谁接。模板 Bot + MCP，live dashboard。填「多 Bot 只能同账号群聊」空白 | Multi-bot | `multi-bot` `webhook` `mcp` `social` `mit` | 0 / MIT | **GitHub**（Hackathon 夜新建，仍推） |
| adamsonwalter/grokbot-phone-caller | https://github.com/adamsonwalter/grokbot-phone-caller | **可自托管打电话模板**：Telnyx + xAI realtime + 临时 Cloudflare tunnel；密钥走 masked env，`dial.sh` 通完即停。与已收 ClawCall 叙事互补（自备 key、无第三方 skill 税） | Skills / Hardware | `phone` `telnyx` `realtime` `template` `mit` | 0 / MIT | **GitHub**（今日新建） |
| Gitmaxd/grok-bot-rocket-template | https://github.com/Gitmaxd/grok-bot-rocket-template | **给 Bot 产物搬家**：模板把 App/服务放到自己的 exe.dev VM（持久盘 + HTTPS），共享云电脑只作编排；危险操作再问一次。直击「云电脑重置丢状态」痛点 | Templates / Self-hosted | `template` `exe-dev` `persistence` `marketplace` `mit` | 0 / MIT | **GitHub**（昨夜新建，有 Add 链） |
| sumanthneerumalla/thebrowserfarm-plugin | https://github.com/sumanthneerumalla/thebrowserfarm-plugin | Cursor/Grok Bot 插件：一站一浏览器、多浏览器并行；MCP + skill 教 browse loop。需 Browser Farm API key（托管 MCP），适合竞品扫价/批量抽页 | Skills & Playbooks | `plugin` `mcp` `browser` `parallel` `mit` | 0 / MIT | **GitHub**（今日新建） |
| PhillipHolland/imessage-relay | https://github.com/PhillipHolland/imessage-relay | **iMessage ↔ X Chat 中继**：本机 Mac 安装器（sha256 核验），opt-in 联系人、正文不落 Bot 盘、附件加密一次取。与已收 `jeffhuber/grokbot-imessage-skill`（本机分拣）成对：一条本地 skill、一条进 X Chat | Skills & Playbooks | `imessage` `x-chat` `macos` `privacy` `mit` | 0 / MIT | **GitHub**（10-19 建，仍推） |

### 玩法 / 信号（无强仓，field-notes / Routines / Learning / Hardware 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Grok Bot Optimizer（瘦身教练 Bot） | https://x.com/BrianRoemmele/status/2112337968820334676 | 约 49 万粉：用 trainer Bot 审计「臃肿」个人 Bot 的指令/技能再裁。无公开仓，交 x-articles 或 Learning 观察 | Learning / Multi-bot | **X** @BrianRoemmele（~74 赞 / 55 收藏） |
| AI 新闻 → 中文简报视频流水线 | https://x.com/YuGuo936066/status/2112351377024225439 | 约 6k 粉：24h AI 新闻去重 → 5–7 条中文简报去 AI 腔 → 配音视频 + 文稿 → 发帖。可作 Routines / Chinese 配方雏形 | Routines / Chinese | **X** @YuGuo936066 |
| 整理 X 追蹤名單（退追死号） | https://x.com/MaxCryptoSpace/status/2112341253593391176 | 抓全部 following → 看最后发文/领域 → 批量退追闲置号。薄但可粘贴进 Routines | Routines / Chinese | **X** @MaxCryptoSpace（约 3.3k 粉） |
| 多 Bot 组队不打架（官方摘 4 条） | https://x.com/Ljhzdqb/status/2112350215214633382 | 建群 2–6、@ 点名派活、少 @everyone。入门向，可并 Learning / Chinese 一句 | Multi-bot / Chinese / Learning | **X** @Ljhzdqb |
| 晨间 5 件事 brief 一句话 routine | https://x.com/grokbotusecases/status/2112325137282322830 | 可粘贴：「每天 8 点读过去 24h timeline，回 5 件要紧的 + 一个写作点子」。薄模板 | Routines | **X** @grokbotusecases |

### Maybe / Skip（~09:18）

| 名称 | 链接 | 原因 |
|------|------|------|
| DavidSlayback/portal-autopilot | https://github.com/DavidSlayback/portal-autopilot | 登录门户自动取件 + 账单对账，审批闸门清楚；**无 SPDX/LICENSE**，等补许可再升格 |
| SamGu-NRX/brand-accelerator | https://github.com/SamGu-NRX/brand-accelerator | Austin Hackathon 个人品牌多 Bot 队（X harness + 短视频）；**无 LICENSE**，体量大可观察 |
| ionpetro/galatiqon | https://github.com/ionpetro/galatiqon | Pi 按键对讲桌面硬件桥自有 Bot；**无 LICENSE**，偏团队定制 |
| rodrigo-pasini/grokbot-kit | https://github.com/rodrigo-pasini/grokbot-kit | MIT 且叙事对（委派 headless agent → webhook 唤醒委派 Bot）；README 自标 **pre-release、命令尚未可用** |
| jeffgreendesign/follow-through | https://github.com/jeffgreendesign/follow-through | 家务责任模板更完整（v0.2）；上轮已 Maybe「模板即仓」，本窗不重复升格 |
| Statusnone420/agent-skills | https://github.com/Statusnone420/agent-skills | 上轮已 Skip（曾写 host retired）；虽 README 又写 Grok Bot，仍观察不重复 |
| herzenco/GrokBot-Agent-Dashboard | https://github.com/herzenco/GrokBot-Agent-Dashboard | 个人 8 agent 看板 + Supabase，偏演示仪表盘 |
| adamtpang/grokbothackathon | https://github.com/adamtpang/grokbothackathon | 活动「扫码加人」dex 演示，非通用配方 |
| King-Simmons/grok-bot-hackathon | https://github.com/King-Simmons/grok-bot-hackathon | URL→lofi 控制台演示 |
| MihirSahu/grok-zoom-bot | https://github.com/MihirSahu/grok-zoom-bot | Zoom RTMS 现场 coding 桥，场景过窄 |
| Menziess/bot-widget | https://github.com/Menziess/bot-widget | 桌面悬浮脸主要对接 OpenBot，非 Grok Bot 配方主线 |
| RetroLancers/ShortsStudio | https://github.com/RetroLancers/ShortsStudio | 创作者审片 MCP，**无 LICENSE** |
| Polymarket 交易收益转述多帖 | （Ygnn43 / Xpss66 / qs1591 等） | 交易/收益号，偏离本仓 |
| francoCosimo95 / genealogy / mcq / OpenMausBot / grok-bot-cli 等 | （见上轮） | 已列，本窗不重复 |

## T7 日更 2026-10-20 ~10:43（Asia/Shanghai）

- **窗口**：~09:18 → ~10:43（约 1.5 小时；相对昨夜/早间白天雷达补扫近 24h）
- **负责**：Grok T7 日更雷达（routine awesome-t7）
- **方法**：X `search_posts_all`（中英 + github.com）+ Mac `gh search repos` updated≥2026-10-18 + README/License 抽查；相对 README + `inbox/candidates.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| lthero-big/gbb-multica-bridge | https://github.com/lthero-big/gbb-multica-bridge | **Multica ↔ Grok Bot 桥**：install.sh 配 webhook routine + 本机/SSH 回填；随仓 gbb 0.2.0，提示词模板可粘贴。填「本机 Multica Agent 队交给云 Bot」缺口；与 claude-grok-bridge / TheSethRose bridge 成互补（协议/运行时/UI 三层） | Multi-bot / Skills | `bridge` `multica` `webhook` `ssh` `mit` | 0 / MIT | **GitHub**（10-19 建，今日仍推） |
| JiminLee-way/GrokBotCLI | https://github.com/JiminLee-way/GrokBotCLI | **无桌面端的 headless 客户端**：静态 `gb` + `gbd` daemon（HTTP/SSE/webhook），Linux arm64 可上 Pi；Discord 桥仍未实测。非官方、走内部协议，更新可能断。galatiqon 等硬件项目依赖它 | Self-hosted / Hardware | `cli` `headless` `daemon` `pi` `mit` | 1 / MIT | **GitHub**（10-14；本窗经 galatiqon README 拉出，仓内未收） |
| andreanjos/grokbot-headless | https://github.com/andreanjos/grokbot-headless | 管官方 Linux 包里的 **local-computer daemon**：无 Electron/X11，让 Bot 在本机跑命令。非官方、内部协议风险同上；与 GrokBotCLI 成对（一个管聊天面、一个管本机执行面） | Self-hosted | `headless` `local-computer` `daemon` `mit` | 8 / MIT | **GitHub**（9 月起；本窗经 galatiqon 研究表拉出） |

### 玩法 / 信号（无强仓，field-notes / Routines / Templates / Learning / Chinese 短链）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Premortem Desk 模板 | https://x.ai/bot/RMTU2Vv4BHQtoJwGFhYCm （帖 https://x.com/teeRex247/status/2112344665756447175） | 贴已定计划 → 失败模式排序 + 预警信号 + kill trigger。与同作者「网页变更只叫醒」互补，可作 Templates | Templates / Learning | **X** @teeRex247（约 2.4k 粉） |
| Watchtower changelog Bot | https://x.ai/bot/0Amg3917cH06sUZ3awwRu （帖 https://x.com/jessenowlin/status/2112352377802313997） | 盯官方 changelog（可加其他源），有更新才 ping。可粘贴进 Routines「发布雷达」 | Routines | **X** @jessenowlin（约 3k 粉，GDE） |
| 多 bot 团队怎么搭（组长+专职+审核） | https://x.com/Lniosytest/status/2112363028062552066 | X Article：自称 X 号由一队 AI 员工在跑。交 Learning / Chinese 或 x-articles 核互动后再收 | Multi-bot / Chinese | **X** @Lniosytest（约 5.9k 粉） |
| 9 段神级提示词保姆教程 | https://x.com/0xluffy_eth/status/2112360364662988956 | 约 15.6 万粉作者 X Article；偏入门提示词合集，交 **x-articles** 雷达核存活与互动 | Learning / Chinese / x-articles | **X** @0xluffy_eth |
| Bot=项目经理、别堆团队 | https://x.com/0xLoki_Zeng/status/2112338759249285242 | 约 2.1 万粉：反对一上来堆多 Bot，主张有项目才有 Bot。可并 Learning / Chinese 一句 | Learning / Chinese | **X** @0xLoki_Zeng |
| 53 模板按场景七类 | https://x.com/yaohongan2025/status/2112348685778489753 | 点选复制模板目录长文；质量未抽检，当灵感库 | Templates / Chinese | **X** @yaohongan2025（约 0.7k 粉） |

### Maybe / Skip（~10:43）

| 名称 | 链接 | 原因 |
|------|------|------|
| kev-inc/grok-bot-cloud | https://github.com/kev-inc/grok-bot-cloud | Dockerized 仓，无 README |
| owenservera/grokbot-telemetry | https://github.com/owenservera/grokbot-telemetry | 个人共享 box 遥测镜像，无 SPDX，偏运维自用 |
| Mike-Three/grokbot-screensaver | https://github.com/Mike-Three/grokbot-screensaver | 屏保玩笑，偏离本仓 |
| JPEGWhisperer 24/7 团队长文 | https://x.com/JPEGWhisperer/status/2112354237875208201 | 约 2 粉，未达收录门槛 |
| DavidSlayback/portal-autopilot | （见上轮） | 仍无 LICENSE |
| groknet / phone-caller / rocket-template / browserfarm / imessage-relay / galatiqon / brand-accelerator 等 | （见白天 ~09:18） | 上轮已列，本窗不重复 |
| rosterroom / root-agent / francoCosimo95 bridge 等 | （见更早） | 已收候选表 |

## 白天 2026-10-20 ~17:07（Asia/Shanghai）

- **窗口**：~15:17 → ~17:07；~15:17 那轮因本机执行被拒没投进来，本轮一并补投（4 条已复核仍在更新）
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：公开 X `search_posts_all`（中英，since 14:30 UTC+8）+ `gh search repos` updated≥2026-10-20 + README/License 抽查；相对 README + `inbox/candidates.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| devicki/herdr-away-signal | https://github.com/devicki/herdr-away-signal | **离开键盘信号**：Herdr 插件一键 away；away 期间 Agent 完成/卡住经 webhook POST 给 Grok Bot/dots，免轮询 SSH。最值得看（~15:17 补投） | Skills / Routines | `herdr` `webhook` `away` `orchestration` `mit` | 0 / MIT | **GitHub**（10-20 建） |
| Qervas/remote-grok-build | https://github.com/Qervas/remote-grok-build | Grok Bot ↔ Windows 本机 Grok Build：skills-only 插件经 computer link 桥接，mission control + 流式回合 + 日更 routine 自刷新 cheat sheet；无公网隧道（~15:17 补投） | Skills / Multi-bot | `grok-build` `plugin` `bridge` `windows` `mit` | 0 / MIT | **GitHub** |
| lingverse-ai/lingverse | https://github.com/lingverse-ai/lingverse | 中文「墨灵」长文写手 Bot 系列：九技能流水线（口吻学习→去 AI 味→六平台改写→发布自检），只交文本不代发。License 徽章 CC BY 4.0 + MIT，API 显示 other，请核（~15:17 补投） | Chinese / Templates | `chinese` `writing` `wechat` `xhs` `template` | 0 / other | **GitHub**（10-20 建） |
| JeffShanCha/grokbotguide | https://github.com/JeffShanCha/grokbotguide （站 https://grokbotguide.ai/zh/ ） | 中文社区实战手册：学习路线、角色卡、案例站内搜；代码 MIT、内容 CC BY-SA。偏教程站，与本仓薄目录互补（~15:17 补投） | Learning / Chinese | `chinese` `guide` `mit` | 0 / MIT | **GitHub** |
| ZeroPointRepo/GrokBotDev | https://github.com/ZeroPointRepo/GrokBotDev （站 https://grokbot.dev ） | **Bot 自己运营的玩法目录**：Scouts 盯 X、Curator 定收录、Builder 维护站，改动全走 PR；插件/用例/组合五条线，JSON API + RSS + MCP 给你的 Bot 订阅。和本仓「Grok + Claude 协作维护」思路同构，可作对照 | Learning / Directories | `directory` `mcp` `rss` `agent-run` `mit` | 43 / MIT（内容 CC BY 4.0） | **GitHub**（今日仍推） |
| V-harshith/grokbothq | https://github.com/V-harshith/grokbothq （站 https://grokbothq.xyz ） | 人工抽测的 Bot 目录：4,200+ Bot 分类、组合包、指南与对比；Issue 模板提交 → Action 校验 → 自动 PR。与 majiayu000/awesome-grok-bot 同类，可并一行 | Learning / Directories | `directory` `combos` `static-site` `mit` | 4 / MIT（内容 CC BY 4.0） | **GitHub**（今日仍推） |
| william1010121/ClaudeCodeBot | https://github.com/william1010121/ClaudeCodeBot | **把 Grok Bot 的组织方式搬到本机 Claude Code**：主 Bot 做前台、每项目一个经理、临时小队；闲置写 memory.md 后休眠，`routines.cron` 定时，群聊 @ 点名，需要你拍板时弹按钮。macOS，有 CI 与 release | Alternatives / Multi-bot | `claude-code` `macos` `multi-bot` `routines` `mit` | 0 / MIT | **GitHub**（10-19 建） |
| Anonyfox/lfm | https://github.com/Anonyfox/lfm | 「先卖再做」落地页 skill + CLI：Agent 先找真实买家原话→写设计概念→出单页，lfm 编译并拦截慢/不可访问/AI 味设计。Grok Bot 有现成分享 Bot（https://x.ai/bot/HgpgiMSirsCBrsQpdLeDf）。贴出海一人公司 | Skills / 出海一人公司 | `landing-page` `skill` `validation` `mit` | 1 / MIT | **GitHub** |

### 玩法 / 信号（无强仓或待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 演示一次→存成 routine | https://x.com/cyrilXBT/status/2112465125722751457 | 约 19.7 万粉：给 Bot 演示一次流程，它拆成步骤、追问判断点、发信步骤先问，再存成可口令触发的 routine。可作 Learning 一句话配方 | Learning / Routines | **X** @cyrilXBT（51 赞） |
| 繁中新手攻略长帖 | https://x.com/zohanlin/status/2112467214045765659 | 约 1.26 万粉：一 Bot 一事、按天上手顺序；交 x-articles 雷达核互动后再定 | Learning / Chinese | **X** @zohanlin |
| tyhanson24/stormdesk-ghl | https://github.com/tyhanson24/stormdesk-ghl | 上门服务公司用的 HighLevel 插件 + 9 个 skill（风暴季接单、路线、估价、保险、早 6 点简报）；行业垂直配方完整，但无 LICENSE | Skills / Maybe | **GitHub** |
| ChrisTu117/grokbot-flow-skills | https://github.com/ChrisTu117/grokbot-flow-skills | 中文「参谋长流程」五个 skill（上手/创世/固定设定/治理/通用流程）+ 哈希校验脚本；无 LICENSE、无说明正文 | Skills / Chinese / Maybe | **GitHub** |
| superwangxxxl/grok-bot-guide | https://github.com/superwangxxxl/grok-bot-guide | 中文新手教程站（VitePress，站 imsuper.vip）；代码 MIT 但正文版权保留，今日新建，与 grokbotguide 同类 | Learning / Chinese / Maybe | **GitHub** |

### Maybe / Skip（~17:07）

| 名称 | 链接 | 原因 |
|------|------|------|
| verdikthq/plugins | https://github.com/verdikthq/plugins | x402 付费 API 裁决/退款插件，偏 Web3 支付，离主线远 |
| pacifico-1106/grokbot-control-plane | https://github.com/pacifico-1106/grokbot-control-plane | 日本中小企业「AI 社员证」SaaS 控制面，产品仓非配方，无 LICENSE |
| CashflowEngine/cashflow-engine-plugin | https://github.com/CashflowEngine/cashflow-engine-plugin | 交易分析插件，偏离本仓 |
| ProphetEngine/AIResearch | https://github.com/ProphetEngine/AIResearch | Bot 维护的 AI 研究知识库，内容仓非玩法，无 LICENSE |
| skysay 电话号模板回复群 | https://x.com/skyzer4ever/status/2112438274639966711 | ~15:17 已列，本窗只是同作者多次回帖推广 |
| noodle 镜像群 / 空仓 | （多） | 同前，镜像或无 README |

## 白天 2026-10-20 ~19:13（Asia/Shanghai）

- **窗口**：~17:07 → ~19:13
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：公开 X `search_posts_all`（since 17:00 UTC+8）+ `gh search repos` updated≥2026-10-20（grok bot / grokbot / x.ai/bot / multi-bot 等）+ README/License 抽查；相对 README + `inbox/candidates.md` + docs 去重
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| Rladmsrl/a2a-bridge | https://github.com/Rladmsrl/a2a-bridge | **把 Grok Bot routine 变成标准 A2A 服务**：外部 Agent 走 A2A JSON-RPC/SSE 发任务 → bridge 转成 webhook 叫醒 routine → Bot 回调 POST 回结果；支持 v0.3 + v1.0、Agent Card、多轮与 input-required，SQLite 存任务状态。让别人的 Agent 能正规地「给你的 Bot 派活」。最值得看 | Multi-bot / Routines | `a2a` `webhook` `routine` `interop` `mit` | 5 / MIT | **GitHub**（10-13 建，今日仍推） |
| realspqrk/grokbot-desk | https://github.com/realspqrk/grokbot-desk | **Bot 的老板桌**：Bot 跑一条 `show` 命令丢 JSON（表格/图表/待决策/社媒帖），本机弹一个窗口让你批准/驳回/选项，结果 JSON 回给 Bot；多份报告排成收件箱。把「对外动作先问人」做成了可视化审批台。Windows/macOS，界面默认德语（`RS_LANG=en` 切英文） | Skills / 作战室 | `approval` `dashboard` `human-in-the-loop` `mit` | 1 / MIT | **GitHub**（beta.6，今日仍推） |
| mduppes/TokenTracking | https://github.com/mduppes/TokenTracking | macOS 菜单栏统一看 Claude / Cursor（含 Grok Bot 周额度）/ ChatGPT / Gemini 等用量与配速；本机 headless Chrome 独立配置读取，无 API key、无遥测。可并「额度体检」 | Learning / 额度体检 | `quota` `macos` `menubar` `local-first` `mit` | 0 / MIT | **GitHub** |
| SvenKunkka/grokbot-quota-ring | https://github.com/SvenKunkka/grokbot-quota-ring | 更轻的单项版：SwiftBar 插件，菜单栏一个绿→黄→红饼图显示 Grok Bot 周额度剩余。⚠️ 授权要粘贴 cursor.com 会话 cookie（存 Keychain），收录时须写明风险 | 额度体检 / Maybe | `quota` `swiftbar` `macos` `mit` | 0 / MIT | **GitHub** |

### 玩法 / 信号（无强仓或待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| igor-olikh/grok-bot-usage | https://github.com/igor-olikh/grok-bot-usage | **一句话 → 三 Bot 接力出站**：参谋长 Bot 写 brief → 建站 Bot 提交私有仓 → Cloudflare Bot 部署到 Access 后，约 25 分钟上线、每早自刷新的「Bot 舰队仪表盘」；仓里只放故事、brief 与护栏，代码另存私仓。很适合作多 bot 接力案例，但无 LICENSE | Multi-bot / Learning | **GitHub**（今日新建） |
| echris6/grokbot-templates | https://github.com/echris6/grokbot-templates | 「一 Bot 一门小生意」模板套件（AI 网红 / 动效视频工作室 / three.js 空间站），每个模板带 setup skill，对外发帖/定价/交付都留给人；经 Whop 售卖。贴出海一人公司，但无 LICENSE、偏推广 | 出海一人公司 / Maybe | **GitHub**（今日新建） |
| SvenKunkka/grokbot-ppt-skills | https://github.com/SvenKunkka/grokbot-ppt-skills | Markdown 大纲 → 可编辑 PPTX 的薄 skill（python-pptx），复杂 deck 指向上游 agent-slides；MIT 但很薄 | Skills / Maybe | **GitHub** |
| 训记 skill × Grok Bot 饮食记录 | https://x.com/corvuschen1211/status/2112497476242756095 | 约 4.5 万粉：健身 App「训记」开放 skill，接上 Grok Bot 查便利店营养值并录入，生活类 skill 打通实例 | Skills / Chinese | **X** @corvuschen1211 |

### Maybe / Skip（~19:13）

| 名称 | 链接 | 原因 |
|------|------|------|
| devrecated/grok-bot-linux / timoteuszelle/x.ai-grok-bot | https://github.com/devrecated/grok-bot-linux | 非官方 Linux 移植 / Nix 打包，安装渠道类，非玩法；同类 grok-bot-flake 已在表 |
| shoodoow/kuru / 5dive-ai/5dive / amajorai/ryu / chinghauchu/snorlax-bot | https://github.com/shoodoow/kuru | 自托管「类 Grok Bot」替代品，Alternatives 已够多，暂不加 |
| ArvinYin1/grokbot-animation-anatomy | https://github.com/ArvinYin1/grokbot-animation-anatomy | 头像动画逆向解剖，好玩但偏离玩法主线，且无 LICENSE |
| @Marko_Poly / @Mellon0x / @Jiangjiefu X 长文 | （见 to-claude x-articles 段） | 归 X 大 V 雷达，已判粉量/热度不够 |
| noodle 镜像群 / 空仓 / 个人日志仓 | （多） | 同前，镜像或无 README |

## 白天 2026-10-20 ~21:11（Asia/Shanghai）

- **窗口**：~19:13 → ~21:11
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：`gh search repos` updated≥2026-10-20 18:30（grok bot / grokbot / grok-bot / x.ai/bot / skill / routine）+ README/License 抽查；相对 README + `inbox/candidates.md` + docs + .collab 去重。公开 X 搜索本轮共享通道 429 两次，未取到数据，X 信号留给下一轮
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| FelixFangX/dev-work-grok-bot-skill | https://github.com/FelixFangX/dev-work-grok-bot-skill | **一个 skill 把 Bot 配成研发助理**：逐题面试你→连 GitHub/Linear/飞书/Slack→把安全规则原文写进 memory；GitHub 默认只读、推送/PR/部署要明示、团队消息先草稿再确认。亮点是 **20 条脚本化安全评测**（转述的「老板批了」、贴 token、仓文件/网页里的提示注入、擅自推送等），CI 每次推送都校验。附全虚构示例。最值得看 | Skills / 安全护栏 | `skill` `dev-assistant` `safety-evals` `prompt-injection` `mit` | 0 / MIT | **GitHub**（10-13 建，今日仍推） |
| jethros-projects/botter | https://github.com/jethros-projects/botter | 非官方 **Grok Bot 的 Node.js SDK + CLI**：`botter list / history / send --wait`，可从脚本给 Bot 派活、跟对话，或自己做桌面端/仪表盘；附「给 Agent 用的操作手册」（先读一段再发一次）。⚠️ 走非公开接口、预览版（@next），收录须标「非官方、接口可能变」 | Tools / SDK & CLI | `sdk` `cli` `nodejs` `unofficial` `mit` | 0 / MIT | **GitHub**（今日新建） |
| devicki/herdrbot | https://github.com/devicki/herdrbot | 与已列 `devicki/herdr-away-signal` 同作者的**完整工头 Bot 引擎**：Bot 在 Herdr 里起 Claude Code/Codex 干活、转达审批问题（从不替你点同意）、早报与周更检查；`watchgate.py` 无模型轮询，只在状态真变时 POST webhook 叫醒 Bot，省额度。建议与 herdr-away-signal 合并成一行 | Multi-bot / 作战室 | `foreman` `claude-code` `webhook` `watch-gate` `mit` | 0 / MIT | **GitHub**（今日新建） |

### Maybe / Skip（~21:11）

| 名称 | 链接 | 原因 |
|------|------|------|
| 某 Roon 播放器控制扩展 | （不点名） | 本机音乐控制好玩，但 README 带个人路径/用户名，无 LICENSE，不进公开候选 |
| Maimuzamilhu/awesome-grok-bot-templates | https://github.com/Maimuzamilhu/awesome-grok-bot-templates | 又一个模板目录（3,300+），与已列 grokbothq / majiayu000 同类，License 非标准，暂不加 |
| jazzpher/grok-bot / tecadrise-ai/TecAdRiseBot | https://github.com/jazzpher/grok-bot | 自托管「类 Grok Bot」替代品，Alternatives 已够多 |
| Arch/RPM 打包仓（ATLTuck / gallez-tech / addidotlol） | （多） | 安装渠道类，非玩法；同类已判 |
| KT3746 小游戏群 / 空仓 / 个人新闻页 | （多） | 单页小游戏或空 README，非可复用玩法 |

## 白天 2026-10-21 ~09:09（Asia/Shanghai）

- **窗口**：~21:11（10-20）→ ~09:09（10-21）
- **负责**：Grok 白天玩法雷达（routine awesome-3）
- **方法**：公开 X `search_posts_all`（中英 + url:github.com，start 2026-10-20T13:00Z）+ GitHub API created/pushed≥2026-10-19 + WebSearch；相对 README + `inbox/candidates.md` + 近窗推荐去重。Mac `~/Documents` 本轮 Interrupted system call，正文先在 box 临时仓写好再投
- **红线**：无 key / 营收 / 内部路径 / 隐私；未 star / fork；未改 README；个人参考不点名

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| senscho/grok-codex-bridge-public | https://github.com/senscho/grok-codex-bridge-public | **Grok Bot↔本机 Codex 持久桥**：把重活丢到 Mac 上的 Codex，留额度给 Bot；`BOT_INSTALL.md` 一键自检到冒烟，审批/接管走终端，webhook 回写进度。最值得看 | Skills / Multi-bot | `codex` `bridge` `mcp` `quota` `mit` | 0 / MIT | **X** @SiliconPhd + **GitHub**（10-20 建） |
| plastic-labs/honcho（integrations/cursor） | https://github.com/plastic-labs/honcho/tree/main/integrations/cursor | **账号级共享记忆**：粘一段让 Bot 接 Honcho MCP，偏好与对话跨 Bot/跨机器续上；一人对多 Bot 像同一人。⚠️ AGPL-3.0，收录短评须写清协议 | Multi-bot / Memory | `memory` `mcp` `multi-bot` `agpl-3.0` | 7712 / AGPL-3.0 | **X** @honchodotdev（16 收藏） |
| KhairallahA/agent-autosave | https://github.com/KhairallahA/agent-autosave | 可移植 `.autosave/`：把当前编码 Agent 进度交给下一个（Claude Code/Codex/Cursor/OpenCode 等）；作者说丢给 Grok Bot 也能接。跨 Agent 交接配方 | Skills / Multi-bot | `handoff` `autosave` `multi-agent` `apache-2.0` | 1 / Apache-2.0 | **X** @eng_khairallah1 + **GitHub**（10-20 建） |
| naoiseirwin/strava-grokbot-bridge | https://github.com/naoiseirwin/strava-grokbot-bridge | Strava MCP，跑在用户云电脑上，让 Grok Bot 读运动数据。生活向连接器范例 | Skills / Connectors | `strava` `mcp` `connector` `mit` | 0 / MIT | **X** @naoise + **GitHub**（10-20 建） |
| nolangz/pixel2motion | https://github.com/nolangz/pixel2motion | Logo 动效 skill：栅格→平滑 SVG 动画/HTML demo/GIF 预览+动效 QA；中文帖演示丢给 Grok Bot 一键出片。★高可复用 skill | Skills / Creative | `skill` `logo` `animation` `svg` `mit` | 2457 / MIT | **X** @zhiwehu + **GitHub** |
| migasrias2/geckobox | https://github.com/migasrias2/geckobox | 本机多机 SSH 舰队：Claude Code/Codex 等在任意电脑上跑、任务一次性分发；无中继、MIT。可作「本机多机」对照（非云端 Bot） | Alternatives / Multi-bot | `fleet` `ssh` `claude-code` `codex` `mit` | 14 / MIT | **GitHub**（10-20 新建） |

### 玩法 / 信号（无强仓或待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 5 Bot 产品接力模板 | https://x.ai/bot/ccZyuYxIiO5yfaTG-EfRZ （帖 https://x.com/Suchuanyi/status/2112708161631039591 ） | 中文：Scout→Iris→Atlas→Quill→Forge 共享文件夹接力，四个关口需人点头；装 Atlas 一个会建齐其余。模板链可作 Multi-bot Learning | Multi-bot / Chinese | **X** @Suchuanyi |
| bostonaholic/grokbot-skills | https://github.com/bostonaholic/grokbot-skills | SKILL.md 配方仓 + 粘贴安装句；无 LICENSE，先观 | Skills / Maybe | **GitHub**（10-20 建） |
| 三 Bot 一人公司提示词 | https://x.com/eng_khairallah1/status/2112627106719080623 | Scout 读 / Builder 写稿 / Closer 夜巡卡住任务；粘贴即建。无独立仓，作 Learning | Multi-bot / Learning | **X** @eng_khairallah1（301 收藏） |

### Maybe / Skip（~09:09）

| 名称 | 链接 | 原因 |
|------|------|------|
| cobusgreyling/grok-bot-templates、bcharleson/grokbot-for-gtm | （README 已收） | 不重复 |
| echris6/grokbot-templates、igor-olikh/grok-bot-usage | （上轮信号） | 已列 |
| arsiktech/hermes-draft-cards | https://github.com/arsiktech/hermes-draft-cards | Hermes 桌面草稿卡，非 Grok Bot 主线 |
| cgatlin08/gmg-ai-agent-for-servicenow | https://github.com/cgatlin08/gmg-ai-agent-for-servicenow | 用 Cursor+Grok Bot 做的 ServiceNow 产品，非 Bot 玩法 |
| Trading-Crew / Midnight-GrokBot-Agent / grokbot-screensaver | （多） | 交易/Web3/屏保，偏离 |
| Vinci-virtuoso/grokbot-skills、newgodev/grok-bot-portable | （多） | 空/极薄或无说明 |

## 2026-10-21 10:50 Asia/Shanghai · T7 日更雷达

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| xiaozhenliu/agent-mesh | https://github.com/xiaozhenliu/agent-mesh | **本机 Claude Code/Codex/pi + 云端 Grok Bot 同一 Reason Network 私有团队**，Mac 常驻中继签名转发并敲 routine webhook，双向即时唤醒；中文指南 + `AGENT-INSTALL.md`。正好对上我们 Grok↔Claude 协作痛点（fake-ip 场景需另测）。最值得看 | Multi-bot / Bridges | `reason-network` `webhook` `claude-code` `codex` `mit` `中文` | 0 / MIT | **GitHub**（10-20 建） |
| siuserxiaowei/grokbot-recipes | https://github.com/siuserxiaowei/grokbot-recipes | 中文配方库 10 个（适合谁→准备→步骤→提示词→产出→注意，示例虚构）+ grokguide.si 教程索引。中文区可直接复制 | Chinese / Recipes | `中文` `recipes` `prompts` `mit` | 0 / MIT | **GitHub**（10-21 建） |
| heyalchang/grokbot-box-heal | https://github.com/heyalchang/grokbot-box-heal | 「更新 Bot 电脑」换实例后自愈：Tailscale 重装/状态恢复、包基线、gh 登录恢复；不自动登录。Box 运维向实用 | Skills / Box ops | `box` `tailscale` `self-heal` `mit` | 0 / MIT | **GitHub**（10-20 建） |
| devrecated/grokbot-routines | https://github.com/devrecated/grokbot-routines | GrugBot Console：一页看全部 routine 运行、暂停/改时间/改 prompt、看 box 日志；有假数据 demo。多 Bot 管理面板 | Multi-bot / Dashboards | `routines` `dashboard` `nextjs` `mit` | 1 / MIT | **GitHub**（10-20 建） |
| fal-ai-community/fal-grok-plugin | https://github.com/fal-ai-community/fal-grok-plugin | fal.ai 官方社区插件：Grok Bot/Grok Build/Cursor 生图/视频/音频/3D，带 skills 与正反例 eval。插件打包范本 | Plugins / Media | `plugin` `mcp` `media` `fal` `mit` | 0 / MIT | **GitHub**（10-20 建） |
| NetrovertHQ/netrovert-agents | https://github.com/NetrovertHQ/netrovert-agents | 11 个 Grok Bot 的一人团队（求职/在办活/赏金黑客松/人脉…）+ 共享 playbooks；明确「只起草不自动发」。多 Bot 作战室真实案例 | Multi-bot / Case studies | `multi-bot` `playbooks` `human-in-loop` `mit` | 0 / MIT | **GitHub**（10-20 建） |
| greedfi/dotmail | https://github.com/greedfi/dotmail | `.mail` 模板的页面生成器：把 Bot 邮箱按需回复/等回复/收据等分栏成本地静态页，不上传邮件；配官方模板链接 | Templates / Email | `email` `template` `static-page` `mit` | 0 / MIT | **GitHub**（10-21 建）+ 模板 https://x.ai/bot/HdN8nshqGbNy_Le0fSi_6 |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Spidermanrobin/awesome-grokbots | https://github.com/Spidermanrobin/awesome-grokbots | 同类 Awesome（中英日，41 Bots），可互相参考/对照去重，不建议直接收录为条目 | Related lists | **GitHub**（10-21 建） |
| oscarsterling/telegram-bot-relay | https://github.com/oscarsterling/telegram-bot-relay | 只有 webhook 的 Agent 进 Telegram 群与其他 bot 对话（CF Worker）；需粘 bot token，短评写清 | Bridges / Maybe | **GitHub** |
| deadsimple-email/deadsimple-plugins | https://github.com/deadsimple-email/deadsimple-plugins | 给 Agent 独立邮箱的托管 MCP，支持 Grok Bot；商业服务，Maybe | Connectors / Maybe | **GitHub** |

### Skip（本轮）

trading/钱包类（tradingmcp-plugin、grokwallet、Project-Delta、mt5）、德语空 README 的 command-center、noid-bot（替代品非玩法）、个人杂项仓（family-book、recipe-book-starter、grokbot-watch、line-desk 空 README）。X 近 1 天带链帖以日文长文为主，交给 X 大 V 雷达。

## 2026-10-21 11:15 Asia/Shanghai · 白天玩法雷达

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| lbq110/grokbot-personal-agent | https://github.com/lbq110/grokbot-personal-agent | **中文私人助理搭建手册**：5 个 Bot 卡片可直接粘贴 + 「日常饮食」群 + 操作日志 + 给别人搭建前的需求问卷/交付模板（可选 wx-bot 接微信）。从自用到代搭的完整路径，最值得看 | Chinese / Personal assistant | `中文` `multi-bot` `playbook` `templates` | 0 / 无 License（短评注明） | **GitHub**（10-21 建） |
| liujuntao123/x-news-hot | https://github.com/liujuntao123/x-news-hot | 整点 routine 调 X `search_news` 重写 `data/news.json` 再 push，GitHub Pages 自动发布的中文热点站；`refresh_instructions.md` 就是可抄的 routine 提示词。「雷达 → 静态站」范本 | Routines / Radar → site | `中文` `routine` `x-news` `github-pages` | 0 / 无 License | **GitHub**（10-21 建） |
| hoangbeard/grok-security-bots | https://github.com/hoangbeard/grok-security-bots | CVE / 0-day / 论文 3 个雷达 bot + 1 个去重 bot（错开 30 分钟跑、80% 相似度标记重复不删），附全部提示词与 `dedup.py`。多雷达去重编排范式 | Multi-bot / Radar | `security` `radar` `dedup` `schedule` | 0 / 无 License | **GitHub**（10-21 建） |
| byteartisan8/net-ops-grok-bot | https://github.com/byteartisan8/net-ops-grok-bot | NOC 机器人小队：自动发现 Zabbix 告警 → 调查 → 提修复方案等人批 → 执行并验证，像素风「NOC 作战室」实时展示。工程向作战室 + 人审案例（偏重，放 Maybe 也可） | Multi-bot / War room | `noc` `human-in-loop` `war-room` `docker` | 0 / 未声明 | **GitHub**（10-21 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| IamP5/claudio-bot | https://github.com/IamP5/claudio-bot | 在自己 Mac 上用 Claude Code 复刻 Grok Bot 式常驻 bot（记忆/routine/权限卡/iPhone App），MIT。替代品，适合 Related 而非玩法 | Related / Alternatives | **GitHub**（10-17 建） |
| romeodiaz/guava-stack | https://github.com/romeodiaz/guava-stack | Notion 当共享「AI 大脑」+ 规则 + 路由，推荐接 Grok Bot 做执行层，MIT。跨工具上下文思路可参考 | Related / Memory | **GitHub** |
| Retasc/plugins | https://github.com/Retasc/plugins | 多 agent 工作队列插件（认领/心跳/检查点，两个 agent 不会抢同一单），支持 Grok Bot；商业服务，Maybe | Connectors / Maybe | **GitHub** |

### Skip（本轮）

grokbot-wop-tracker（README 404）、grokbot-screensaver（上轮已 skip）、Midnight-GrokBot-Agent（Web3）。X 近 4 小时带 GitHub 链的 Grok Bot 帖仅 1 条日文日报，无可收。

## 2026-10-21 13:08 Asia/Shanghai · 白天玩法雷达

### 推荐入清单（新）

| 名称 | 链接 | 一句理由 | 建议 README 节 | 标签 | ★/License | 来源 |
|------|------|----------|----------------|------|-----------|------|
| anightmonarch/grokbot-guide | https://github.com/anightmonarch/grokbot-guide | **Grok Bot 中文实践手册**（VuePress 站 grokbotguide.pages.dev）：上手教程、Connectors/Skills/Routines/多 Bot、带 x.ai/bot 分享链接的模板馆、30 分钟/7 天学习路线、场景库；每页标注官方来源、声明非官方。中文入门首选，最值得看 | Chinese / Guides | `中文` `guide` `templates` `learning-path` | 1 / MIT | **GitHub**（10-21 建） |
| luisfigueroavale/dreamstate-gtm-team | https://github.com/luisfigueroavale/dreamstate-gtm-team | Chief of Staff + 12 个 Bot 的 GTM 作战室（外联/内容），一个 Content Room + 工作日 08:20 汇总 routine；共享规则/授权表写在 docs/rules.md，Claude Code/Codex 做本地文件活。多 Bot 分工模板（绑 Dreamstate 服务，短评注明） | Multi-bot / War room | `multi-bot` `gtm` `routine` `claude-code` `mit` | 0 / MIT | **GitHub**（10-20 建） |
| samsagewize/grok-cats | https://github.com/samsagewize/grok-cats | 像素猫花园：每只猫是一个 Grok，别的 Grok Bot 通过 HTTP + 邀请码加入走动聊天，一键部署 Vercel。好玩的多 Bot 互通/可视化 demo | Fun / Multi-bot | `multi-bot` `pixel-art` `vercel` `mit` | 0 / MIT | **GitHub**（10-21 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| aidyfeng/triedagents-plugin | https://github.com/aidyfeng/triedagents-plugin | 只读 MCP + skill：查「Agent 用例是否被复跑验证」（判定/评分/权限级别/原提示词），无需登录无 key。可作选玩法前的参考，Maybe | Connectors / Maybe | **GitHub**（10-21 建） |
| lucioamor/grokbot-bridge | https://github.com/lucioamor/grokbot-bridge | Claude Code `/grok` 命令打 Cursor Automation webhook，回复走 Drive/Slack outbox；对象是 Cursor Automation 而非 Grok Bot，名字易混，Related | Related / Bridges | **GitHub**（10-21 建） |

### Skip（本轮）

leadstream-mcp（商业获客连接器）、rss-feeds（与 Grok Bot 关系仅「自动更新」一句）、grokbot-roon-control（个人播放器控制）、pure-xml-rs、grok-Kelola-keuangan、空 README 个人仓若干。X 近 4 小时带 GitHub 链的 Grok Bot 帖 0 条。

## 非 X 渠道 · 2026-10-21

> 来源 dev.to / HN / Medium / V2EX / 掘金 / B 站；按标题摘要初筛，待 Claude 核正文。

| 标题 | 链接 | 渠道 | 作者 | 短评 | 语言 | 分类 |
|---|---|---|---|---|---|---|
| Grok Bot Tutorial for Beginners: Build Your First AI Teammate | https://dev.to/arindam_1729/grok-bot-tutorial-for-beginners-build-your-first-ai-teammate-29jb | dev.to | arindam_1729 | 新手搭第一个 bot | en | 入门 |
| Jobs I Would Let a Grok Bot Run After I Close the Laptop | https://dev.to/promptway/jobs-i-would-let-a-grok-bot-run-after-i-close-the-laptop-139p | dev.to | agnelnieves | 合盖后托管的任务清单 | en | Routines |
| I Let Grok Bot Apply to Software Engineering Jobs While I Was Sleeping | https://dev.to/bobbyhalljr/i-let-grok-bot-apply-to-software-engineering-jobs-while-i-was-sleeping-n62 | dev.to | bobbyhalljr | 求职自动投递实录 | en | 案例 |
| AI Agent 多代理人自動化開發實作：讓 Agents 夜巡 | https://dev.to/letswrite/ai-agent-duo-dai-li-ren-zi-dong-hua-kai-fa-shi-zuo-rang-agents-ye-xun-xie-zuo-kai-fa-svg-yuan-xing-lian-xian-gong-ju-5037 | dev.to | letswrite | 多 agent 夜巡协作开发 | zh-TW | 多 bot 协作 |
| Grok Bot has its own email now. How to put it on your own domain | https://shipmail.to/blog/grok-bot-email-on-your-own-domain | HN | jcoulaud | 自有域名邮箱接 bot（作者有产品，需核软广） | en | 邮件 |
| How Grok Bot Works | https://www.peterp.me/articles/what-actually-happens-when-you-message-grok-bot/ | HN | thegreatpeter | 消息到执行的原理拆解 | en | 原理 |
| From Hermes to Grok Bot | https://chad.cm/posts/2026-10-6-from-hermes-to-grok-bot | HN | carimura | 迁移经验 | en | 经验 |
| Running a Self-Healing Grok Bot Company | https://medium.com/git-connected/running-a-self-healing-grok-bot-company-e07171741a49 | Medium | 抓不到 | 自愈型多 bot 组织 | en | 多 bot 协作 |
| 用 Grok Bot 在微信公众号挂号，差点导致微信被封 | https://www.v2ex.com/t/1250172 | V2EX | b309f3337 | 踩坑：风控 | zh | 踩坑 |
| 给 GPT Dot 和 Grok Bot 接了座桥 | https://www.v2ex.com/t/1247898 | V2EX | bimeixishuai | 跨 agent 桥接 | zh | 集成 |
| 用 Grok Bot 写了个旅行青蛙 | https://www.v2ex.com/t/1249970 | V2EX | Rogeryxx | 做小游戏实录 | zh | 案例 |
| Grok Bot 从 0 到 1｜用云电脑和插件，搭一个能干活的 X 助手 | https://juejin.cn/post/7684649314158510114 | 掘金 | 小墨同学boy | 云电脑+插件搭 X 助手 | zh | 入门 |
| 我 build 了一个 Grok Bot 帮我 7x24 运营我的 pstack 中文站 | https://juejin.cn/post/7694134378717986851 | 掘金 | 出发向未来 | 站点运营托管 | zh | 案例 |
| Grok Bot 保姆级做视频教程 | https://juejin.cn/post/7694287070886297610 | 掘金 | XiaoLei_Liu | 一句话到成片 | zh | 内容生产 |
| 【Grok Bot 仓颉实践】助手一次汇报七八条，我只批准一条往下做 | https://juejin.cn/post/7693358476032213002 | 掘金 | 猛犸象限 | 审批节奏经验（系列） | zh | 经验 |
| 一小队 Grok Bot 怎么分工不抢答？（附可抄 prompt） | https://www.bilibili.com/video/BV1EtnP6AEm7 | B 站 | 泸州不窖你老叫 | 群规则+流水线配方 | zh | 多 bot 协作 |
| Grok Bot 额度两天就用完？我的两个改进 | https://www.bilibili.com/video/BV1Menj62E4q | B 站 | KunKun的折腾手记 | 省额度 | zh | 踩坑 |


## 白天玩法雷达 · 2026-10-21 15:10

> 按 full_name 与 README、docs/*.md、inbox/candidates.md 比对无重复。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Skybatan/family-book | https://github.com/Skybatan/family-book | **家庭年度收支账本**：Excel 模板 + bot/ 目录，拍小票或读订单邮件自动按日按类记账、年度汇总，多语言回复。可直接抄的生活类 bot 配方，本轮最值得看（无 License，短评注明） | Recipes / Life | `recipe` `xlsx` `receipts` `email` | 0 / none | **GitHub**（10-20 建） |
| iconnectgroupco/grokbot-skills | https://github.com/iconnectgroupco/grokbot-skills | 40+ 个 SKILL.md（工程 ecc-* + 投放营销 mkt-*），index.json 一句提示词批量安装；多为改编自 ECC/claude-ads 等，各自带原 License | Skills | `skills` `marketing` `engineering` | 0 / mixed（MIT/Apache） | **GitHub**（10-20 建） |
| taasky/plugin | https://github.com/taasky/plugin | 免账号免 key 的远程 MCP + skill：让 bot 替你跟别人约时间/议价，双方都点头才成交，人在 Telegram 一键确认。Connectors 节（商业服务，短评注明） | Connectors | `mcp` `skill` `negotiation` `plugin` | 0 / MIT-0 | **GitHub**（10-21 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Aneesh15here/grokbot-watch | https://github.com/Aneesh15here/grokbot-watch | Apple Watch 上像打电话一样跟 bot 说话、切 bot；需自行 sideload 且要填 Cursor API key，非官方，Maybe | Fun / Clients | **GitHub**（10-21 建） |
| Mike-Three/grok-bot-screensaver | https://github.com/Mike-Three/grok-bot-screensaver | 粉丝做的 bot 头像屏保（Win/mac），纯趣味，Maybe 进 Fun | Fun | **GitHub**（10-21 建） |
| @yuanliuwei 2112794126693396647 | https://x.com/yuanliuwei/status/2112794126693396647 | 中文 X 长文「用 Grok Bot 打造 0 成员短视频工作室」，发出约 40 分钟互动还低，交给 X 大 V 雷达后续看收藏再定 | x-articles / 待定 | **X** |

### Skip（本轮）

birdeye-business-context（公司内部合成数据）、grokbot-wop-tracker / grokwallet / grokbot-oauth / fernando-s97 等个人或空 README 仓、Trading-Crew-app（与 Grok Bot 关系弱）、两个空仓（GrokBot_DrawingSkill1、-grokbot-bridge）。


## 白天玩法雷达 · 2026-10-21 17:15

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| qubicsdata/grok-starter-kit | https://github.com/qubicsdata/grok-starter-kit | **Grok Bot + Claude Code 起步套件**：AGENTS.md 分阶段接入（先只读盘点现状、不覆盖已有文件）、第二大脑模板、营销起步、3 个 skill、晨报 routine、可选 dev-lead agent 与 Claude Code 队列。与本仓「Grok↔Claude 协作」主线高度契合，本轮最值得看 | Starter Kits / Multi-agent | `starter-kit` `skills` `routine` `claude-code` | 0 / Apache-2.0 | **GitHub**（10-20 建） |
| twoimo/honeytem-cardnews | https://github.com/twoimo/honeytem-cardnews | 韩语：联盟链接 → 小红书式「好物卡片」图 + 带广告标注的文案 + 链接核对表，纯 bot 设置与运营规则，可当内容带货配方参考（短评注明联盟营销、韩语） | Recipes / Content | `recipe` `affiliate` `cardnews` `ko` | 1 / MIT | **GitHub**（10-21 建） |
| madeinusmate/grokbot-tv | https://github.com/madeinusmate/grokbot-tv | Android TV 上的 bot 墙：Mac 侧小桥同步分区/置顶/当前对话，按遥控器麦克风直接跟屏上 bot 说话；非官方客户端，进 Fun / Clients | Fun / Clients | `android-tv` `client` `voice` | 0 / MIT | **GitHub**（10-21 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| shiolsecretary-blip/codex-grok-bridge | https://github.com/shiolsecretary-blip/codex-grok-bridge | 中文：给 gbot 0.12.4 打补丁，Codex ↔ Grok Bot 双向对话 + 后台推送进指定 Codex 聊天；锁定版本、无 License、非官方，可作「跨 agent 桥接」信号，与 senscho/grok-codex-bridge-public 同类 | Integrations / 待定 | **GitHub**（10-21 建） |
| @rzubiran 2112829307747815461 | https://x.com/rzubiran/status/2112829307747815461 | 西语 X Article「七天、五十台机器、一人掌控」，刚发互动为 0，交 X 大 V 雷达看后续 | x-articles / 待定 | **X** |

### Skip（本轮）

lujin88/agent-monitor（监控 Grok Build/Codex/Claude Code，非 Grok Bot）、timrekelj/mistral-bot（替代品）、stephendpurdue/GrokBot-Hackathon / Grok-Bot-Ideas / mauricioaugustobr/grokbot / moshekat/grokbot（空或无 README）、pmartbrown/grokbot-training（个人培训幻灯）、xAthenaa/grok-Kelola-keuangan（与 bot 玩法弱相关）。


## 白天玩法雷达 · 2026-10-21 19:15

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| design760201-hue/adhd-focus-buddy | https://github.com/design760201-hue/adhd-focus-buddy | **繁中 ADHD 专注小伙伴**：开场全用点选设置上下班/提醒频率，每天排三件事并拆 2 分钟第一步，定时把人从放空拉回，记时间不责备、连续天数不归零；带一键复制 bot 模板 + SETUP.md（贴仓库网址让 bot 照着配）+ 日/周成绩卡示例。中文、可直接抄的生活类 routine 配方，本轮最值得看 | Recipes / Life | `recipe` `routine` `zh-TW` `template` | 0 / MIT | **GitHub**（10-21 建） |
| My-Stacks/stacklist-plugin | https://github.com/My-Stacks/stacklist-plugin | Stacklist 远程 MCP + skills：bot 把调研结果存成带一句话备注的卡片集，人在手机打开/分享；Grok Bot 侧边栏 Connect apps 或聊天里加 MCP 即可。商业服务（免费档可用），短评注明 | Connectors | `mcp` `skill` `plugin` `research` | 0 / MIT | **GitHub**（10-21 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Amal-David/talk-to-me | https://github.com/Amal-David/talk-to-me | Cloudflare Worker + Durable Objects 做跨 agent 私有消息中继（Grok Bot / dots / Instinct），带 CLI 和 SKILL.md；作者自述 v0.1 未部署、与 Grok Bot 的联调未验证，先当「跨 agent 桥接」信号 | Integrations / 待定 | **GitHub**（10-21 建） |

### Skip（本轮）

OXC-Tech/leadstream-mcp（单一 SaaS 获客连接器，泛 AI 助手通用、非 Grok Bot 玩法）、alessioluffarelli/grok-bot-social（无 README）、fernando-s97/grok-bot（个人笔记，上轮已 skip）。


## 白天玩法雷达 · 2026-10-21 21:17

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 19:15→21:17（Asia/Shanghai）X + `gh search`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| holdtapp/holdt | https://github.com/holdtapp/holdt | **自托管 iCloud 日历 MCP**：只读默开，写入须 preview→人点头→10 分钟内一次性 commit；从不删别人事件、不发邀请；CF Worker + passkey 审批；`npm run prove` 攻击证明 + agent-setup.md（贴给 bot 照装）。已提 Grok Bot Marketplace（尚未上架）。补官方无 iCloud Calendar 连接器的缺口，本轮最值得看 | Connectors / Skills | `mcp` `icloud` `calendar` `approval` `self-hosted` | 0 / MIT | **X** @DallinWatts + **GitHub**（10-20 建，本窗再推） |
| abhisheksharma001/agx-grok-bot | https://github.com/abhisheksharma001/agx-grok-bot | Grok Bot 模板：经 Nostr-AGX 回答其他 agent；AGX Connect 做 bot↔bot 数据访问（owner grant）、澄清提问、可读日志、邮件记忆与晨间提醒；带 skills/ + routines/ + 测试。多 agent 互通配方 | Multi-bot / Skills | `multi-bot` `nostr` `agx` `routine` `skill` | 0 / 无 License | **GitHub**（10-21 建） |
| Leadspicker/leadspicker-cursor-plugin | https://github.com/Leadspicker/leadspicker-cursor-plugin | Leadspicker 远程 MCP + 4 skills：搜 B2B 公司/人、导入私有名单、起草 outreach 序列；**不能**发信/启动活动。OAuth，无 API key。商业服务，短评注明 | Connectors | `mcp` `plugin` `b2b` `outreach` `commercial` | 0 / MIT | **GitHub**（10-21 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| lucioamor/grokbot-bridge-for-lovable | https://github.com/lucioamor/grokbot-bridge-for-lovable | Lovable skill + Supabase edge：App 调 Cursor Automation webhook 并可收回复；是已列 lucioamor/grokbot-bridge 的 Lovable 兄弟仓，对象仍是 Cursor Automation 而非真 Grok Bot，名字易混 | Related / Bridges | **GitHub**（10-21 建） |
| qunqin24/Pulse | https://github.com/qunqin24/Pulse | macOS 额度监视器，单独显示 Grok Bot 周额度与 reset 倒计时（官网不写具体重置点）；~586★ Apache-2.0。本窗 @zou_chris 推荐。工具向，非 playbook | Learning / Quota tools | **X** @zou_chris + **GitHub** |

### Skip（本轮）

AIPMAndy/grok-bot-handbook（空仓）、denominator69/denominator-boat-dashboard（游艇触屏 demo 非配方）、已列 ChamathRosh / heyalchang/grokbot-box-heal / NetrovertHQ / francoCosimo95 / adhd-focus-buddy / stacklist / talk-to-me / madeinusmate/grokbot-tv、noid-bot（上轮已 skip 替代品）、营销/额度白嫖长文交 X 大 V 雷达。


## 白天玩法雷达 · 2026-10-22 00:06

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 21:17→00:06（Asia/Shanghai）X + `gh search`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| jiapeiyang/xshelf | https://github.com/jiapeiyang/xshelf | **中文 X 书签站模板**：Grok Bot 每日读书签→中文标题/摘要/分类→可搜索静态站；`agent/SETUP.md` 一句开通，Secrets 存 fine-grained token，不写对话。可直接抄的中文 routine 配方，本轮最值得看 | Recipes / Routines | `recipe` `routine` `x-bookmarks` `chinese` `mit` | 0 / MIT | **X** @JiapeiYang21427 + **GitHub**（10-16 建，本窗再推） |
| diginno-net/grokbot-dsh-orchestrator-vn | https://github.com/diginno-net/grokbot-dsh-orchestrator-vn | 越南语：Grok Bot 做编排（理解/拆分/验收/审批发送），DeepSeek Harness 在 box 上跑廉价 worker；含架构图、CSV/银行解析 benchmark（~$0.004–0.02/任务）。省额度多 agent 配方；License 为作者自定义（GitHub NOASSERTION），短评注明 | Multi-bot / Cost | `multi-bot` `deepseek` `orchestrator` `quota` `vi` | 3 / custom | **GitHub**（10-21 建） |
| bitrefill/agents | https://github.com/bitrefill/agents | 官方 Bitrefill Agent Skills + MCP：礼品卡/充值/eSIM；Grok Bot 走 Connect apps，购买默认人确认，另有 `references/harnesses/grok-bot.md`。商业连接器，短评注明 | Connectors / Skills | `skill` `mcp` `plugin` `commercial` `mit` | 26 / MIT | **X** @0xDovah + **GitHub** |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| huydepzai121/grokbot-omp | https://github.com/huydepzai121/grokbot-omp | 同日越南语变体：Grok 编排 + oh-my-pi (`omp`) 廉价 worker + `skills/omp-worker/SKILL.md`；与 diginno DSH 编排同构，GitHub License=Other | Multi-bot / 待定 | **GitHub**（10-21 建） |
| XiaoMa3413/qq-grokbot-bridge | https://github.com/XiaoMa3413/qq-grokbot-bridge | 中文 QQ⇄Grok Bot 桥：常驻主机保 QQ 长连，webhook 叫醒 box；带 `DEPLOY_AGENT.md` 给 agent 照装。无 License | Integrations / 待定 | **GitHub**（10-15 建，本窗仍推） |
| ChamathRosh/whatshouldmybotdo-connector | https://github.com/ChamathRosh/whatshouldmybotdo-connector | 已列 ChamathRosh/grok-bot-templates 的只读 MCP 伴侣（plan/search/get_template），无 key；可当 Connectors 短链 | Connectors | **GitHub** |
| Viaknox/tune-up | https://github.com/Viaknox/tune-up | Tune-Up bot：给其他 Grok Bot 体检 + 内置 skill 索引，有 Add to Grok Bot 链；营销文案重，先当信号 | Skills / 待定 | **GitHub**（本窗仍推） |

### Skip（本轮）

已列 holdt / ChamathRosh templates / teamwork-UI / siuserxiaowei/grokbot-recipes / OpenMausBot / smfworks templates；scott/xstats（用 Bot 做成的 X 统计仪表盘，非 playbook）；andraetbusiness-code/grokbot-desk（memecoin 看板）；adtaoai/google-ads-adtao-mcp-skills（商业 Google Ads，偏 Claude 插件）；空/个人仓与营销长文交 X 大 V 雷达。


## 白天玩法雷达 · 2026-10-22 02:06

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 00:06→02:06（Asia/Shanghai）X + `gh search`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| xj-2045/xj-os | https://github.com/xj-2045/xj-os | **Grok 舰队 + Claude Code 经共享 Drive 邮箱协作**：两边从不互调 API，只靠 `to-grok/` / `from-grok/` Markdown 单写；含动画数据流、一日时间线、协议序列图与护栏。实现私有、文档脱敏公开。与本仓「Grok↔Claude 邮箱协作」主线同构，本轮最值得看 | Multi-bot / Architecture | `multi-bot` `claude-code` `drive` `mailbox` `architecture` `mit` | 0 / MIT | **GitHub**（10-21 建） |
| AIPMAndy/grok-bot-handbook | https://github.com/AIPMAndy/grok-bot-handbook | **中文保姆级攻略 v3.0**：26 章操作 + 40 套可复制任务指令 + 36 FAQ + 故障诊断/安全检查/7 天上手；Pages 站 + 事实溯源台账（claims.json）。上轮因空仓 skip，本窗已满内容、MIT。作者有咨询引流，短评注明非官方 | Chinese / Guides | `中文` `guide` `prompts` `faq` `mit` | 0 / MIT | **GitHub**（10-21 建，本窗充实） |
| juangurdian/wingman | https://github.com/juangurdian/wingman | 本机 MCP 桥：Grok Bot（及 Cursor/Muse）可列线程、读 transcript、发消息、打断本地 Codex / Claude Code 会话；`npx wingman-mcp` + Tailscale Serve。云端 Bot 管本地 coding agent 的具体配方 | Skills / Bridges | `mcp` `bridge` `claude-code` `codex` `mit` | 0 / MIT | **X** @pearlwolf42 + **GitHub** |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| IgorWarzocha/discord-agent-bridge | https://github.com/IgorWarzocha/discord-agent-bridge | Discord @mention → 该用户自己的 Grok Bot（email / webhook / Hermes / OpenClaw）；带 `skills/discord-bridge/SKILL.md` 与回帖回调。无 License，2★ | Integrations / 待定 | **GitHub**（10-21 建） |
| themsquared/grok-bot-cross-agent-leak | https://github.com/themsquared/grok-bot-cross-agent-leak | 复现 10-19 跨 Bot 银行余额泄入公开 Slack，并用 agentgateway MCP 护栏按敏感标签拦截。安全/边界案例，Apache-2.0 | Learning / Security | **GitHub**（10-21 建） |
| doggy8088/grok-bot-learn | https://github.com/doggy8088/grok-bot-learn | RongleCat/grok-bot-learn 的繁中自动同步镜像（OpenCC），站 grok-bot-learn.gh.miniasp.com；上游已列，本条仅作繁中入口信号 | Chinese / Guides | **GitHub** |
| AZERDSQ131/Open-Hermes-Bot | https://github.com/AZERDSQ131/Open-Hermes-Bot | macOS Electron：用 Hermes 主机复刻 Grok Bot 多 Bot 聊天 UI（群/侧栏），early OSS。替代品界面，非 Grok Bot 玩法 | Related / Alternatives | **X** @AZERDSQ0329 + **GitHub** |
| brokep/grok-bots-for-hermes | https://github.com/brokep/grok-bots-for-hermes | 90 个 marketplace bot → Hermes profile（SOUL.md + skills + paused cron）。同作者 deepseek-harness 曾因无 License/重打包版权被拒；本仓亦无 License，先观 | Related / Port | **GitHub**（本窗新建） |
| @wavegod 2112961302767493490 | https://x.com/wavegod/status/2112961302767493490 | 审计全舰队 routine：把「有没有活」机械检查写成先跑脚本（0=睡/10=醒），省空转额度；无独立仓，交 Learning/Routines 短链或 X 大 V 雷达 | Routines / 待定 | **X** |

### Skip（本轮）

交易台 hypergrok-trading-desk / 中文跟风交易「连亏两单下岗」刷帖；graveyard-golf（仅 Built with）；cwijayasundara/grok_bot_harness_v1.0（名含 grok_bot、实为 Claude Code Quorum 插件）；Aceop lilis-kitchen（发现库非配方）；SuperintelApp / pi-adblocker / noid-bot（替代品/弱相关）；已列 xshelf / diginno / holdt / recipes / screensaver / Midnight-GrokBot-Agent；营销/额度长文交 X 大 V 雷达。


## 白天玩法雷达 · 2026-10-22 08:07

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 02:06→08:07（Asia/Shanghai）X + `gh search`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| ZMGID/grokbot-home | https://github.com/ZMGID/grokbot-home | **中文换号迁移家**：公开仓 + `BOOTSTRAP.md`，新号 bot 匿名克隆→密码框解 `secrets/*.enc`→装 composio-pg→按 `bots/` 重建整队与 routine；密钥扫描、每日同步。可直接抄的「账号迁移/多 bot 重建」配方。注意仓库公开后 CONTEXT 也会被看见，短评提醒勿写隐私。本轮最值得看 | Chinese / Migration | `中文` `multi-bot` `bootstrap` `migration` `secrets` | 0 / 无 License | **GitHub**（10-08 建，本窗仍推） |
| 7iook/grokbot-cpa | https://github.com/7iook/grokbot-cpa | Grok Bot box 上装 CLIProxyAPI：Cloudflare 隧道（named 双 connector / quick / local）、校验下载、健康 watchdog；专门处理 box 常见 Fake-IP（`198.18.x`）用 `unshare`+hosts。带 skill 引导与 hourly healthcheck。Box 运维向实用，MIT | Skills / Box ops | `box` `cpa` `cloudflare` `fake-ip` `mit` | 0 / MIT | **GitHub**（10-05 建，本窗更新） |
| s-hiraoku/grokbot-kanban | https://github.com/s-hiraoku/grokbot-kanban | 一人看板 + 多 Grok Bot：bot 经 MCP/HTTP 建卡/认领/批注/移动，**只有主人能删**；可把卡交给 Cursor cloud agent。带架构图与鉴权表。多 bot 工作队列范本（无 SPDX License，短评注明） | Multi-bot / Boards | `multi-bot` `kanban` `mcp` `cursor` | 0 / 无 License | **GitHub**（10-11 建，本窗更新） |
| DynamaxVV/mygrokbot-host | https://github.com/DynamaxVV/mygrokbot-host | 自托管 Grok-Bot 形态：名册/流式回合/审批闸门/skill/routine/Gateway RPC+SSE；密钥只走环境变量。GPL-3.0 + 中文 README。替代品向，适合 Related | Related / Alternatives | `self-hosted` `routines` `skills` `gpl-3.0` `中文` | 0 / GPL-3.0（meta NOASSERTION） | **GitHub**（本窗新建 10-21） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| eptexas20/agents-office | https://github.com/eptexas20/agents-office | Windows 本机像素办公室「The Branch」：同事=你的 Grok Bot，点人聊天；不索要密码。趣味客户端，License=Other | Fun / Clients | **GitHub**（本窗新建） |
| hzyrgj001/codex-reset-tracker | https://github.com/hzyrgj001/codex-reset-tracker | 非官方 Codex 额度重置追踪：历史数据集 + 静态可视化 + **Grok Bot skill 一键盯帖**；中英页。Apache-2.0 | Learning / Quota | **GitHub**（本窗更新） |
| aikarjal/wilmai | https://github.com/aikarjal/wilmai | 芬兰 Wilma 校园系统 MCP/CLI/skill，明确支持 Grok Bot 做家庭晨报；MIT，78★。地域向连接器 | Connectors | **GitHub**（本窗更新） |
| bipa-app/grok-plugin | https://github.com/bipa-app/grok-plugin | 巴西 Bipa：Pix/boleto 支付 MCP + 葡语 skill；支付须生物识别批准。商业金融连接器，短评注明 | Connectors / Maybe | **GitHub**（本窗新建） |
| emohamedadel2/tellz-grok-plugin | https://github.com/emohamedadel2/tellz-grok-plugin | Tellz 竞品情报远程 MCP + Marketplace 上架资产；OAuth，商业服务 | Connectors / Maybe | **GitHub**（本窗新建） |
| denaidark/awesome-grok-bot-reconstructed | https://github.com/denaidark/awesome-grok-bot-reconstructed | 0.18 reconstructed 衍生 fork/port 对照表（带证据标签）。同类 Related list，勿当玩法条目 | Related lists | **GitHub**（本窗新建） |

### Skip（本轮）

交易台 HyperGrok / Midnight-GrokBot-Agent（上轮已 skip）；mateuscmtropical/cloudbot（自述 early 不可用）；timscheuerai/gtm-architecture-template（同作者 grokbot-gtm-team 已在 README）；tt-a1i/archify（通用 agent 作图 skill，非 Grok Bot 专向）；bostonaholic/grokbot-skills / owenservera/grokbot-telemetry（candidates 已列）；空 README（Chaoc2624/SenorFernando/tony-wei-chang/dlamb-boop）；drpclau/claude-routine-pilot（虚构测试仓）；数字牙科失败报告（个人叙事薄）；营销/额度长文交 X 大 V 雷达。


## 白天玩法雷达 · 2026-10-22 10:07

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 08:07→10:07（Asia/Shanghai）X + `gh search` + Web。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Nuncio-hq/grokbot-cli | https://github.com/Nuncio-hq/grokbot-cli | **本机 CLI / SDK / MCP 驱动 Grok Bot 舰队**：`grokbot ask/send/wait/reply/team/inbox`，`setup-prompt` 贴进 Claude Code/Codex/Cursor 一次配好；bot 云电脑装 inbox skill，助手侧约 1 分钟可见待办。macOS + Node 20.3+，MIT。跨 runtime 派活配方，本轮最值得看 | Skills / Bridges | `cli` `mcp` `sdk` `multi-bot` `inbox` `mit` | 0 / MIT | **GitHub**（10-15 建，本窗仍推） |
| shiolsecretary-blip/claude-codex-grok | https://github.com/shiolsecretary-blip/claude-codex-grok | **中文 Claude Code ↔ Codex ↔ Grok Bot 三方互通**：gbot 0.12.4 版本锁定补丁 + 按 @GPT/@Claude 点名分拣转发；架构图与叫醒时序；Claude 侧收件箱（终端 2 分钟 / 桌面 30 分钟兜底）。上轮同作者 codex-grok-bridge 仅双边，本仓补全 Claude。无 License、非官方，短评注明 | Integrations / Multi-bot | `中文` `claude-code` `codex` `bridge` `gbot` | 0 / 无 License | **GitHub**（10-21 建，本窗更新） |
| brevitywithorion/context-transfer-skill | https://github.com/brevitywithorion/context-transfer-skill | Context Transfer skill：每轮从持久 memory 拉短 Context Snapshot，对抗长线程 context rot；含 SKILL.md + evals。MIT，可直接当 skill 配方抄 | Skills | `skill` `memory` `context` `mit` | 0 / MIT | **GitHub**（10-21 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| stevencombs/GrokGauge | https://github.com/stevencombs/GrokGauge | macOS 菜单栏 SuperGrok 总池 + Grok/Grok Bot/Cursor 分摊环，Homebrew cask；与已列 Pulse / quota-ring 同类额度工具 | Learning / Quota | **GitHub**（本窗更新） |
| Twiniti-Hub/needful-things-plugin | https://github.com/Twiniti-Hub/needful-things-plugin | Needful Things 二手市集远程 MCP + skills（draft 可写、发布须 App 内人批）；README 偏 Grok Build，另有 `.grok-plugin`；生产 10-28 才上线。商业连接器，先当信号 | Connectors / Maybe | **GitHub**（10-21 建） |
| Tanmayjadhav2305/grok-bot-clone | https://github.com/Tanmayjadhav2305/grok-bot-clone | 开源本机「Bot Computer」：多 bot / automations / computer-use / gateway；自称 clean-room 仿 Grok Bot 架构。替代品向，与 mygrokbot-host 同类 | Related / Alternatives | **GitHub**（10-21 建） |

### Skip（本轮）

hexuria/grok-shell（从生产包抽设计 token 做 UI 对标，RE/ToS 风险）；cantgetalonggta-png/grok-omega-console（无 README、含可疑 injector 页）；Topman3579/groknews-archive / Zeua00/Hve-Hangari / dlamb-boop/easypost-outbound-page（空或薄静态）；Richard-Yhn/deepseek-bot-ios / appsvoltaire/TinyTodo（非 Grok Bot 玩法）；已列 ZMGID/7iook/kanban/mygrokbot/xj-os/handbook/wingman/xshelf/diginno/holdt 等；@Codywqkhg Claude Code on bot VM 步骤帖无仓交 X 大 V；营销/额度白嫖长文交 X 大 V 雷达。

## 2026-10-22 10:37 Asia/Shanghai · T7 日更雷达

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约近 24h（含白天 10:07 之后补漏）`gh search` + X `url:github.com` + Web。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| skorten/grokbot-os | https://github.com/skorten/grokbot-os | **一人舰队可安装 OS 包**：Chief of Staff / Notion Librarian / Bot Designer 等 profile + 5 条核心 routine + Notion 单写闸门；空白 bot 粘贴 install prompt 逐步建队，每步等人批。含 leak 扫描与架构文档。可直接抄的多 bot 编排配方，本轮最值得看 | Multi-bot / Playbooks | `multi-bot` `notion` `routines` `install` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-20 建，本窗仍更） |
| Heldinhow/hermes-mcp-bridge | https://github.com/Heldinhow/hermes-mcp-bridge | 本机 Node MCP（Streamable HTTP）：云端 agent（含 Grok Bot）经隧道把任务派给自托管 Hermes，`hermes_task/status/result/files` + 多 agent 注册表；loopback + bearer + 审计。云→本机 Hermes 派活桥，MIT | Skills / Bridges | `mcp` `hermes` `bridge` `multi-agent` `mit` | 0 / MIT | **X** @helldinhow + **GitHub**（10-22 建） |
| franklinjavier/grokbot-quota-template | https://github.com/franklinjavier/grokbot-quota-template | 只读额度/活跃度模板：`SETUP.md` 给导入 bot 照装；sqlite 汇总 bot/子 agent/routine 与 Claude·Codex·Grok CLI 花费，静态 dashboard + leakguard 脱敏。比菜单栏环更偏「舰队用量体检」配方 | Learning / Quota | `quota` `dashboard` `fleet` `template` `mit` | 0 / MIT | **X** @franklinjavier + **GitHub** |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| head77x/grokbotos | https://github.com/head77x/grokbotos | Fedora bootc 本机 OS，开机即进 Grok Bot Linux 应用 + `grokbotd`/MCP 控硬件；Apache-2.0，7★。替代品/自托管 OS，非玩法配方 | Related / Alternatives | **X** + **GitHub**（本窗仍推） |
| LinXiaoTao/awesome-grokbot | https://github.com/LinXiaoTao/awesome-grokbot | 又一份 marketplace bot 目录（中英，站点 awsomebot.com）；同类 Awesome，对照去重即可，不必进条目 | Related lists | **GitHub**（本窗更新） |

### Skip（本轮）

已列 daytime：Nuncio-hq/grokbot-cli、shiolsecretary-blip/claude-codex-grok、brevitywithorion/context-transfer-skill、ZMGID/7iook/kanban/mygrokbot、xj-os/handbook/wingman、xshelf/diginno/holdt 等；timscheuerai/gtm-architecture-template（同作者 grokbot-gtm-team 已在 README）；tt-a1i/archify / mateuscmtropical/cloudbot / Midnight-GrokBot-Agent（上轮已 skip）；appsvoltaire/TinyTodo / manu-labs/grokwallet / trading / 空仓 stub；Fei2411/DeepSeek-Bot（替代品非 Grok Bot 配方）；marketplace 单帖 Storage Rescue / PHP vuln 模板交 X 大 V 或灵感库；营销/额度白嫖长文交 X 大 V 雷达。

## 2026-10-22 12:04 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 仓名与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:07 之后 `gh search`（grokbot / grok-bot / grok bot，updated ≥ 10-22）+ X `url:github.com`（本窗 X 链仓均已列）。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| frysquint/herdr-mcp | https://github.com/frysquint/herdr-mcp | **Grok Bot 盯本机终端里的 Claude Code / Codex**：MCP 暴露 Herdr 会话（workspace/tab/pane + 每格 agent 空闲/工作/卡对话框/完成状态），可读输出、派 prompt、等完成、开新 pane 跑命令；后台事件 tap + `events_wait`；变更类工具带 readOnly/destructive 注解便于逐工具授权。需 Herdr 0.9+、Python 3.12。与 grokbot-cli / claude-codex-grok 互补（反向：bot 管终端 agent），本轮最值得看 | Skills / Bridges | `mcp` `claude-code` `codex` `terminal` `mit` | 0 / MIT | **GitHub**（10-22 建） |
| maplenk/grok-wear | https://github.com/maplenk/grok-wear | 非官方 Wear OS 手表端：手机扫码登录，选任意 bot 免手实时语音、带字幕、可打断，与 bot 聊天记录同步；有 APK + 安装指南。非官方、License 为自定义，短评注明 | Related / Clients | `wear-os` `voice` `client` `unofficial` | 0 / Other | **GitHub**（10-22 建） |
| yunjian-ai/yunjian | https://github.com/yunjian-ai/yunjian | **中文「装进 Bot 的成员」系列**：青鸟（提示词助手）、千机（造 Skill）、试金（验证助手），每位单一职责，带 CHANGELOG / CI / 安装说明；中英双语。可当中文 skill/bot 配方参考 | Skills / 中文 | `中文` `skill` `prompt` `bot-profile` | 0 / CC BY 4.0 + MIT | **GitHub**（10-21 建，本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| vblife/money-saver | https://github.com/vblife/money-saver | 省钱 bot 规格：退订/砍账单/比价/保价理赔，所有动作过确认闸 + 储蓄台账；目前只有中文 PRD，早期 | Use cases / Maybe | **GitHub**（10-19 建，本窗更新） |
| skyiimaple/agent-daily | https://github.com/skyiimaple/agent-daily | 中文：把多个 bot（热点早报、招聘雷达等）消息自动归档成按 bot 分类的展示站；思路同 xshelf，仓较薄 | Use cases / 中文 | **GitHub**（本窗更新） |
| nathanielangafor/migi-network | https://github.com/nathanielangafor/migi-network | agent 互相分享项目/反馈的网络，GrokBot 经 MCP 接入；社区型，先观察 | Connectors / Maybe | **GitHub** |

### Skip（本轮）

rome-os/rome、nitrictech/sugabots、XInTheDark/meowbert、CelestoAI/celesto、NachikethReddyY/agni-bot（替代品/通用 agent 平台）；Aceop-001/lilis-kitchen（已在候选）；peruvian-bull/grokbot、KT3746/grokbot-xadrez、1234yyyyyy/grokbot-news、github031524/Grok-Bot-Ideas、SenorFernando/GBP 等空或个人 stub；bot 自产内容站（market-indicator、tw-stock、wop-tracker、judgement-day、personal-news-reader、wallet-dashboard）非可复用配方；m-fin/render-helper 自称 Private；X 本窗链仓（hermes-mcp-bridge、grok-bot-handbook、grokbotos）已列。

## 2026-10-22 14:01 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 12:04→14:01（Asia/Shanghai）`gh search`（\"Grok Bot\" / grokbot 更新）+ X `url:github.com` / 玩法帖。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| mehh/vm-vitals | https://github.com/mehh/vm-vitals | **一键盯 bot 云电脑心跳**：站点点 Copy prompt → 贴给 Grok Bot，curl 装本机 Go agent，约 1 分钟出仪表盘（CPU/内存/磁盘/网络 + Claude/Codex/Grok 等 agent 进程）；告警、公开页与 OG 分享卡。只报数字不碰密钥/文件内容。MIT，本轮最值得看 | Skills / Box ops | `box` `telemetry` `dashboard` `one-prompt` `mit` | 0 / MIT | **GitHub**（本窗新建 10-22，仍推） |
| BugenZhao/grokbot-cli | https://github.com/BugenZhao/grokbot-cli | **非交互 CLI**：`ask/wait/log/status/routines`，走与桌面相同的未公开 Connect API（`aiserver.v1`）；支持独立登录或 macOS 借用桌面会话。与已列 Nuncio-hq/grokbot-cli（SDK/MCP/inbox 舰队派活）互补——本仓偏脚本化/CI。未声明 SPDX，短评注明 API 可能变 | Skills / Bridges | `cli` `connect-api` `routines` `scripting` | 0 / 无 License | **GitHub**（本窗新建 10-22） |
| GrokkingGrok/TetherBot | https://github.com/GrokkingGrok/TetherBot | **GNOME 顶栏拴住 Grok Bot**：本机 daemon + Shell 扩展；桌面→bot 走 webhook routine，bot→桌面可选轮询私有 git。带 SETUP/prompts/隐私说明。pre-alpha、非官方、License=Other，短评注明 | Clients / Bridges | `gnome` `webhook` `desktop` `bridge` | 0 / Other | **GitHub**（本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| jaredtrichard/grok-factory | https://github.com/jaredtrichard/grok-factory | 一贴 `follow …/GROK_FACTORY.md`：Firstmate 管软件/研究工厂（Cursor cloud 干活、bot 合成写、人合并）。@grok 本窗转链；无 License，上次推 10-05 | Multi-bot / Playbooks | **X** @grok + **GitHub** |
| wantzjt/manager | https://github.com/wantzjt/manager | 创始人看板：Inbox + Ask + **Grok Build** 工厂两轮后停、人合并；偏 Build 非云端 Bot 舰队，可对照 kanban | Multi-bot / Boards | **X** @grok + **GitHub** |
| useorgx/orgx-grokbot-plugin | https://github.com/useorgx/orgx-grokbot-plugin | OrgX MCP + initiative skills + Work Graph 钩子，Cursor marketplace 安装路径；商业协作连接器，MIT | Connectors / Maybe | **GitHub**（本窗更新） |
| Paloma365com/paloma365-plugin | https://github.com/Paloma365com/paloma365-plugin | 餐饮 POS 后台 MCP（哈萨克/CIS）；改价等须确认预览。商业连接器，本窗新建 | Connectors / Maybe | **GitHub** |
| Anil-matcha/open-duet | https://github.com/Anil-matcha/open-duet | 自托管「同事」替代 Claude Duet，简介点名 Grok Bot/Muse/Dots；同作者已有 open-grok-bot 在 README，对照即可 | Related / Alternatives | **GitHub**（本窗更新，~5.9k★） |
| Grok→Opus→MCP 视频流水线 | https://x.com/sai_katano/status/2113144716439278069 | 日文：Grok Bot 只编排不判断，中间 Opus+多 MCP+本机处理再回 Bot。无仓，Learning 短链 | Learning | **X** |

### Skip（本轮）

a70win-wq/usegrokbot（站点已在 README）；StanHuanng/agent-skills（个人 1 个 skill 薄仓）；Bronsonalan/pi-adblocker（上轮已 skip）；SeRgi270710267/ViktorychApp / memelord420p/judgement-day-tracker / thebullzone/grokbot-wop-tracker / Skybatan/family-book（bot 自产内容站）；owenservera/grokbot-telemetry（已列）；chinghauchu/snorlax-bot / florianleibert/flobot / XInTheDark/meowbert* / NachikethReddyY/agni-bot / webautoscrape/rakazo（替代品或已列）；davidwester89-dot/boekhoudmatch / michaelhofsteenge-art/mijn-bots / SenorFernando/GBP（空或个人 stub）；PalomaCEO-ai/cursor-plugin（商业薄）；stablyai/orca / amplifthq/openmeld / elie222/rakazo / rome-os/rome（README 已有）；营销/额度白嫖长文与 Claude Duet 横评交 X 大 V 雷达。

## 2026-10-22 16:01 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 14:01→16:01（Asia/Shanghai）`gh search`（"Grok Bot" / grokbot / grok-bot 更新）+ X `url:github.com`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| misselvexu/grokbot-x-ops-skill | https://github.com/misselvexu/grokbot-x-ops-skill | **一条消息搭 X 运营小编辑部**：单文件中英双语 skill `x-ops-team-setup`，交给主 bot 走一段访谈，自动建专职 bot + skills + routines，走「起草→人批→发布」闸；原则「自动化准备、不自动化判断」。带 CHANGELOG/SECURITY/中文 README，本轮最值得看 | Skills / 中文 / 出海一人公司 | `x-ops` `skill` `multi-bot` `approval-gate` `中文` | 0 / MIT | **GitHub**（10-22 新建） |
| Obiwayne/grokbot-inbox-assistant | https://github.com/Obiwayne/grokbot-inbox-assistant | **邮件助理模板**：新邮件→摘要/下一步/回复草稿→Telegram 里批；主线是 n8n + AgentMail + Grok API（作者实测 31 项），另附 `grok-bot/` 包用 AgentMail 官方插件跑成 Grok Bot（作者注明未实测）。短评须写清两条轨道区别 | Use cases / Email | `email` `agentmail` `n8n` `telegram` `approval` | 0 / MIT | **GitHub**（10-22 新建，template 仓） |
| company-notes/grok-bot-backup | https://github.com/company-notes/grok-bot-backup | **非官方 box 备份/导出**：把人物设定、记忆、笔记、附件、工作区和每位助理完整对话导成原始包+可读包；config 已 gitignore。繁中。README 自警「产出含私密对话/可能含凭证，不是脱敏数据」——收录时短评必须带这条警示 | Skills / Box ops | `backup` `export` `box` `memory` `繁中` | 0 / MIT | **GitHub**（10-22 新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| TommyBez/agent-harbor | https://github.com/TommyBez/agent-harbor | macOS 原生工作区，常驻 Claude Code / Codex CLI 会话并与 Grok Bot 共享；可对照 herdr-mcp 思路 | Clients / Bridges | **GitHub**（10-17 建，本窗更新） |
| Simple-With-Us/BotFleet | https://github.com/Simple-With-Us/BotFleet | Mac/iOS 多 bot 工作台：矩阵总览 + kanban 派活，Apache-2.0，4★；需核与 Grok Bot 实际关系 | Multi-bot / Boards | **GitHub**（本窗更新） |
| pumpdatafun/grokbot-pumpfun-template | https://github.com/pumpdatafun/grokbot-pumpfun-template | 用 x.ai/bot 模板链一键 Add to Grok Bot 的范例（BOT.md / BOT-DAILY.md 结构可参考）；内容是加密币 dev 检查、带导流站，主题不宜正推 | Learning / Maybe | **GitHub**（10-22 新建） |
| EthWiz/investing-bros-skills | https://github.com/EthWiz/investing-bros-skills | 播客团队共享 skills（Claude/Codex/Grokbot 通用），希伯来语，薄 | Skills / Maybe | **GitHub**（本窗更新） |

### Skip（本轮）

5dive-ai/5dive、Kshot3000/Midnight-GrokBot-Agent、andraetbusiness-code/grokbot-desk、taufiq0205/grok-bot-clone（已列）；CelestoAI/celesto、rome-os/rome、chinghauchu/snorlax-bot、NachikethReddyY/agni-bot、Ayuilos/Miffan（替代品/通用平台）；a70win-wq/usegrokbot（README 已有）；ViktorychGroup/ViktorychApp、thebullzone/grokbot-wop-tracker、memelord420p/judgement-day-tracker（bot 自产内容站）；migueltrevinom/crypto-signals-with-grok-bot、send21io/send21-plugin（加密/支付推广）；nehoraiavior/grok-bot-velocity、Perkalars211/grok-bot-timeline、botbikamordehai2-sketch/grok-bots、Jackson1-netizen/grokbot-music、michaelhofsteenge-art/mijn-bots、davidwester89-dot/boekhoudmatch、Bronsonalan/pi-adblocker（空/个人 stub/无 README）；X 本窗仅 Hermes 替代品自荐帖，跳过。

## 2026-10-22 18:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 16:01→18:07（Asia/Shanghai）`gh search`（"Grok Bot" / grokbot / grok-bot 更新）+ X `url:github.com`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| 207studio-oss/kiwi-hook | https://github.com/207studio-oss/kiwi-hook | **编码 agent 一收工就叫醒 bot**：Codex / Claude Code / DeepSeek Harness 回合结束时 hook 发一条小 JSON 到 Grok Bot webhook routine，bot 检查结果→测试过了就 commit/PR（规则允许才合并），没完就派下一步；并行多会话、共享规则与日志仓。可让 bot 自己建 webhook routine 和 hook 配置。和「Grok 挖料→Claude 审」的跨 agent 接力最贴，本轮最值得看 | Multi-bot / Bridges | `webhook` `routine` `claude-code` `codex` `hooks` | 0 / MIT | **X** @207_studio + **GitHub**（10-22 新建） |
| crusader0711/specialized-ai-grok-empire | https://github.com/crusader0711/specialized-ai-grok-empire | **家庭/小公司 Grok Bot 团队的制度包（Project SAGE）**：一个 Chief of Staff 做前门、专员分道不重叠；按可逆性分 GREEN/YELLOW/RED，发送/付款/发布/删除每次都要本人批确切内容；缺数据出「gap card」不编；P1–P3 时限、静默时段+紧急破例、早晚报/周月复盘；敏感类数据不进 git 并由 CI 拦。附 charters/templates/skills/ADR。可对照作战室模板 | Multi-bot / War room | `chief-of-staff` `approval-gate` `charters` `quiet-hours` `ci` | 0 / MIT | **GitHub**（10-22 新建） |
| cherwinyu/grok-bot-mcp | https://github.com/cherwinyu/grok-bot-mcp | **Windows 本机 MCP 桥，把编码任务交给 Grok Bot routine 并用 git diff 验收**：管理员先锁 Git 根、可改文件和测试命令，结果按结构化证据核，不信一句「done」；带离线演示（不登录、不发真 webhook）与简中 README。实验 Beta、非官方，短评注明 | Skills / Bridges | `mcp` `windows` `routine` `handoff` `verification` `中文` | 1 / MIT | **GitHub**（10-17 建，本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| jamespendry/send-to-grok-bot | https://github.com/jamespendry/send-to-grok-bot | Chrome 扩展 + iPhone 快捷指令：给 x.com 每条帖加「发送」按钮，一键把帖子送进 Grok Bot（也支持 Claude/ChatGPT/Codex）；适合 X 素材收集流，需核实现路径与权限 | Clients / X 素材 | **GitHub**（本窗更新，MIT） |
| liuhaisi2026212-maker/taishang-laojun | https://github.com/liuhaisi2026212-maker/taishang-laojun | 中文短视频选题/钩子/标题技能包，先访谈再炼「底味手册」，附 Bot 版 prompt，跨 Claude/Codex/Grok；偏内容方法论，License=Other | Skills / 中文 / Maybe | **GitHub**（10-22 新建） |
| nickkostik/openbot | https://github.com/nickkostik/openbot | 在 bot 云电脑上把本地 bot 回合改路由到自有模型账号；默认安装会开临时公网控制 URL（拿到即可操作面板），改动宿主运行时，风险高，只作信号 | Related / Maybe | **GitHub**（本窗更新，MIT） |

### Skip（本轮）

VesperZephyr/OpenBot、XInTheDark/meowbert-ai-agent、yyydddkkk/rakazo（替代品/fork）；Simple-With-Us/CodeCaps（额度菜单栏，非 Grok Bot）；foztrk/grok-bot-tray（Grok Desktop 托盘小工具）；wyttle/tgrok（Telegram 仿 @grok，与 Grok Bot 无关）；artalemagic6-gbot/wallet-dashboard、tamago-labs/wayfind、victormazzei/roopon（加密/销售推广或 bot 自产站）；guanzhenyang/goods-image-studio（bot 做的电商项目，非可复用 bot 配方）；一个自称应保持私有的 bot 工作区快照仓（隐私，不点名）；X 本窗另有 Hermes 替代品自荐与私人任务清单帖，跳过。

## 2026-10-22 20:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 18:07→20:07（Asia/Shanghai）`gh search`（"Grok Bot" / grokbot / grok-bot 更新）+ X `url:github.com`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| zzyong24/grokbot-team-kit | https://github.com/zzyong24/grokbot-team-kit | **中文「一人内容团队」整包**：1 总管 + 多专员；14 张岗位卡、6 类审批点（发布/花钱/外发/删除/改登录/建 Bot）、共享罗盘目录传上下文、平台口吻卡（X/公众号/小红书等）+ Gemini 去 AI 味与媒体小工具。照着建共享目录→填罗盘→建总管/设计师→按需加专员。可直接抄的多 bot 作战室配方，本轮最值得看 | Multi-bot / 中文 / War room | `中文` `multi-bot` `role-cards` `approval-gate` `content` `mit` | 0 / MIT | **GitHub**（10-22 本窗新建 ~19:19） |
| Cisen07/harness-bridge | https://github.com/Cisen07/harness-bridge | **跨机 Tailscale 派活 + webhook 推醒**：云端 bot 经 tailnet 调度本机 Codex / Claude Code；Mac 走 HTTP bridge（launchd，终态主动 webhook），Ubuntu 走 SSH 模式（主机不装常驻）。带 ACL/SECURITY/脱敏 CI 与 bot skill 模板。与同日 kiwi-hook（同机 hook）互补——本仓偏跨机私网派活 | Skills / Bridges | `tailscale` `webhook` `claude-code` `codex` `bridge` `mit` | 0 / MIT | **GitHub**（10-22 建，本窗仍推） |
| 0xreggiej/grok-bot-router | https://github.com/0xreggiej/grok-bot-router | **本机 Shell 桥：Grok Bot → Codex/OpenCode（经 Magpie 模型或路由）**：configure/runner 生成 bot 指令，验收要回读产出文件不能只复述；无公网监听、无第三方 Python 依赖。中英教程。社区项目，短评注明非官方、需本机已连 Magpie CLI | Skills / Bridges / 中文 | `magpie` `codex` `opencode` `local-shell` `bridge` `mit` | 0 / MIT | **X** @0xReggieJ + **GitHub**（10-22 新建，本窗后于 18:07） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Ditto190/thunderstone-starter | https://github.com/Ditto190/thunderstone-starter | Drive-first 云电脑起步包：bootstrap/resume/tmux、Cursor Cloud environment、rclone Drive；偏 VM 基建而非玩法配方 | Box ops / Starter | **GitHub**（本窗更新，MIT） |
| ken-aisec/grokbot-watchtower | https://github.com/ken-aisec/grokbot-watchtower | 只读安全官 bot：模板 vet、姿态审计、诱饵 canary、周报；改动须对话确认。10-05 建本窗仍更，可作安全向信号 | Skills / Security | **GitHub** |
| Boom-Vitt/grok-bot-bbnw-template | https://github.com/Boom-Vitt/grok-bot-bbnw-template | 泰语 4 bot 团队模板（计划→执行→评审→运维）+ x.ai/bot 导入链；无 SPDX，语言小众，先信号 | Multi-bot / Maybe | **GitHub**（本窗更新） |

### Skip（本轮）

已列 kiwi-hook / specialized-ai-grok-empire / cherwinyu/grok-bot-mcp / misselvexu x-ops / herdr-mcp / vm-vitals / grokbot-cli 等；robbin/grokbot-local-agent（已在候选，本窗 @fankaishuoai 再推 Telegram 看 agent）；voltwake/xianyu-monitor（OpenClaw 闲鱼 skill，非 Grok Bot 原生配方）；jinkkkang/grokbot_computer_research（沙箱/专有 sand 脚本学习摘录，再分发风险）；一个自称应保持私有的 workspace 快照仓（隐私，不点名）；Midnight-GrokBot-Agent / 替代品 orca·rome·rakazo·OpenMausBot·claudio-bot·mygrokbot-host；bot 自产内容站与营销/额度帖交 X 大 V 雷达。

## 2026-10-22 22:00 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 20:07→22:00（Asia/Shanghai）`gh search`（"Grok Bot" / grokbot / grok-bot 更新与今日新建）+ X `url:github.com` / 玩法帖。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| devicki/ourobot | https://github.com/devicki/ourobot | **卡住时呼叫的顾问 Bot**：把 Q00/ouroboros（访谈定规格→种子→证据验收的 Agent OS）包成 Grok Bot 引擎；默认只咨询/验收，显式要求才写代码。本机跑 Ouroboros MCP + Claude Code（判断）+ Grok Build CLI（执行），`install.sh` 幂等、不登录不打密钥；多语 README。同作者已有 herdrbot 系，本轮最值得看 | Multi-bot / Skills | `consultant` `ouroboros` `mcp` `claude-code` `grok-build` `mit` | 0 / MIT | **X** @teatime_forest + **GitHub**（10-22 本窗新建） |
| 00200200/maintainer-skills-lab | https://github.com/00200200/maintainer-skills-lab | **17 个维护者向 skill 单源多端**：人味润稿、带证据修 bug、ML 调试、PR 审阅等；写一份 Markdown → sync 出 Claude/Codex/Cursor/OpenCode/**Grok Bot** 等原生文件（含 `grok-bot/` 与 providers）。MIT，48★，可当 skill 配方库 | Skills / Playbooks | `skills` `multi-client` `grok-bot` `docs` `mit` | 48 / MIT | **GitHub**（本窗更新） |
| EdmundLimBoEn/gb2gpt | https://github.com/EdmundLimBoEn/gb2gpt | **ChatGPT Developer-mode MCP ↔ Grok Bot 舰队桥**：零第三方 pip 依赖的小 Python/SQLite 服务；推荐专用 relay bot 转发到总管，可选 routine webhook 门铃叫醒；含 CHATGPT_SETUP / 自托管 / 威胁模型。非官方。License=CC BY-NC 4.0，短评须注明非商业 | Skills / Bridges | `chatgpt` `mcp` `fleet` `relay` `webhook` `cc-by-nc` | 0 / CC BY-NC 4.0 | **GitHub**（本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Nichokas/grokbot-linux-port | https://github.com/Nichokas/grokbot-linux-port | 非官方 Linux 打包：从官方 .deb 原样重打 AUR/COPR/便携 tar；43★ MIT。包装向非玩法，可作 Clients 信号 | Related / Clients | **GitHub**（本窗更新） |
| Q00/ouroboros | https://github.com/Q00/ouroboros | ourobot 底座 Agent OS（MCP、多 runtime）；偏通用编码编排，随 ourobot 对照即可 | Related / Engines | **X** + **GitHub** |

### Skip（本轮）

QuinnEckart/digitalocean-grokbot-plugin（空 README）；ikeriano/eltiron-grok-bot / frank-otto/cauldron-eruption（游戏）；kleezhou/klee-ielts（词卡）；yousafnazir/grok-bot（空）；ZuskiVibeCode/quant-trading / mfanninf1555/Project-Delta / Midnight-GrokBot-Agent（交易/Web3）；ViktorychGroup/ViktorychApp / dlamb-boop/easypost / boydt/morning-brief / gilsrubin-sys/market-indicator（bot 自产内容站）；mikeg0/grokbot-face（人脸 demo）；lucasfrasca-AI/GrokBotOne（私人备份）；andraetbusiness-code/grokbot-desk / m-fin/render-helper / send21io/send21-plugin（已 skip 类或 Private）；CelestoAI/celesto / jooler/kepcup / NachikethReddyY/agni-bot（替代品）；sukikeeling/moodie-pet / Bronsonalan/pi-adblocker / michaelhofsteenge-art/mijn-bots / SenorFernando/GBP（偏题或 stub）；已列 orca / botter / recipes / harness-bridge / claude-grok-bridge / taishang-laojun 等；营销/额度帖交 X 大 V 雷达。

## 2026-10-23 00:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 22:00→00:07（Asia/Shanghai）`gh search` / API（pushed≥22:00 窗）+ X `url:github.com` / 玩法帖。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| mvanhorn/agent-tincan | https://github.com/mvanhorn/agent-tincan | **跨平台 Agent 互助中继（Tailscale）**：各端只出站连中继，谁问谁干、带回回复；点名 Grok Bot / Claude Code / Codex / Muse / Hermes。本窗 X 称已接 Claude Duet（Bot↔Duet 互派）。338★ MIT，可抄的多 runtime 协作底座，本轮最值得看 | Multi-bot / Bridges | `tailscale` `multi-agent` `relay` `grok-bot` `claude-duet` `mit` | 338 / MIT | **X** @mvanhorn + **GitHub** |
| aipmer/codex-grok-task-bridge | https://github.com/aipmer/codex-grok-task-bridge | **Codex/Claude Code/Cursor → Cloudflare Workers MCP 任务桥 → Grok Bot 执行**：异步任务、租约、幂等、scoped OAuth；Routine 轮询 claim；非官方、自部署。与已列 claude-grok-bridge（原生 routine 双向）互补——本仓偏「本机编码 agent 指挥云 Bot」 | Skills / Bridges | `mcp` `codex` `cloudflare` `task-queue` `apache-2.0` | 4 / Apache-2.0 | **X** @ai_pmer + **GitHub** |
| thirdlf03/grokbot-changelog-watch | https://github.com/thirdlf03/grokbot-changelog-watch | **官方 changelog RSS → 有新版本才 webhook 叫醒 Bot**：GitHub Actions 每 6h 扫 `x.ai/changelog/bot`，state 去重、dry-run；无更新不烧额度。日文 README。无 SPDX，短评注明 | Routines / Ops | `changelog` `webhook` `github-actions` `quota` | 0 / 无 License | **GitHub**（10-18 建，本窗仍推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| ericyangpan/grokbot-weixin | https://github.com/ericyangpan/grokbot-weixin | 微信 iLink Bot API → Grok Bot webhook routine 双向桥（同 openclaw-weixin 后端）；MIT 但目前几乎只有 README，WIP。可对照已收 grok-bot-wechat 配方仓 | Integrations / 中文 / Maybe | **GitHub**（本窗新建） |
| naoiseirwin/Tesla-Grokbot-Connector | https://github.com/naoiseirwin/Tesla-Grokbot-Connector | 只读 Tesla Fleet MCP（电量/充电/气候/行程，无车控）；MIT 但仓极薄（仅 README），先当连接器信号 | Connectors / Maybe | **GitHub**（本窗新建） |
| cloudflare/security-audit-skill | https://github.com/cloudflare/security-audit-skill | 通用安全审计 skill（~3.8万★）；X 上有人设每日 Routine 在 Grok Bot 跑。非 Grok 专向，可作 Skills/Routines 旁链 | Skills / Security | **X** @DannyGrinberg + **GitHub** |
| puzzle-app/grokbot-delivery-team | https://github.com/puzzle-app/grokbot-delivery-team | 已在候选：本窗仍有提交，续观即可，勿当新条目 | （已列） | **GitHub** |

### Skip（本轮）

kerm1it/grok-bot-exts（空仓）；a4sr3s/solutions-likes-grokbot（静态落地页）；smallCattyCat/grokbot-box-backup（个人 box 树备份，已有 company-notes/grok-bot-backup 同类警示仓）；francoCosimo95/claude-grok-bridge / XiaoMa3413/qq-grokbot-bridge / owenservera/grokbot-telemetry（candidates 已列）；替代品 orca/rakazo/OpenMausBot/celesto/5dive/snorlax/Miffan/open-duet；bot 自产站（wop-tracker/easypost/Viktorych/morning-brief）；Midnight-GrokBot-Agent / send21 / pi-adblocker；营销/额度帖交 X 大 V 雷达。

## 2026-10-23 02:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 00:07→02:07（Asia/Shanghai）`gh search` + X `url:github.com`。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| hermeshai/hermesh | https://github.com/hermeshai/hermesh | **云端 Bot 派活到本机编码 agent**：Grok Bot / Muse / ChatGPT 经 MCP（或 CLI）接到自家 Mac/VPS 上的 Claude Code、Codex、Cursor 等；本机 Touch ID 批项目授权、可随时断。Issue→派 Claude→开 PR 的可抄闭环；Apache-2.0，Go 单体+DMG。本窗 X @pofey1 预览帖。本轮最值得看 | Multi-bot / Bridges | `mcp` `claude-code` `codex` `bridge` `touch-id` `apache-2.0` | 0 / Apache-2.0 | **X** @pofey1 + **GitHub**（10-22 本窗新建） |
| walter-grace/cooks | https://github.com/walter-grace/cooks | **开源销售外联 + MCP**：Nooks 兼容 Sequencing API + 32 工具 MCP（stdio/HTTP），任意 Claude / Grok Bot 跑序列、邮件、任务；自托管 Postgres，MIT。里程碑写到 M5，适合「Bot 管 outbound」配方 | Skills / Ops | `mcp` `sales` `outbound` `self-hosted` `mit` | 0 / MIT | **GitHub**（本窗新建） |
| antonyfuentesdev/spanish-teacher-bot-template | https://github.com/antonyfuentesdev/spanish-teacher-bot-template | **西语教师 Bot 模板源**：identity + memories + routines + 13 个 SKILL.md（分级/上课/复习/考试/周报）；配 course-pack 仓。可抄「模板仓结构」。License=CC BY-NC 4.0，短评须注明非商业 | Skills / Templates | `template` `skills` `routines` `education` `cc-by-nc` | 0 / CC BY-NC 4.0 | **GitHub**（本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| yanqingcheng/grokbot-actually-good-qa-tester | https://github.com/yanqingcheng/grokbot-actually-good-qa-tester | 探索性 QA skill 包（章程→就绪→会话→带证据报告），可移植 Cursor 等；MIT，本窗仍推 | Skills / QA | **GitHub** |
| we1jia/AgentDock | https://github.com/we1jia/AgentDock | macOS Liquid Glass 语音拨号盘：一键呼叫/闭麦/挂断切换 Grok Bot 多 Bot、Muse、dot 等；偏客户端入口，19★ MIT | Clients / Multi-bot | **GitHub** |
| personalagentproxy/proxy | https://github.com/personalagentproxy/proxy | 自托管权限代理：服务连一次、按 agent 细粒度授权+审计；README 点名 Grok Bot。118★ MIT，可作多 Bot 安全底座 | Self-hosted / Security | **GitHub**（本窗更新） |
| jt-wang/visa-bulletin-push | https://github.com/jt-wang/visa-bulletin-push | 美签排期变动 webhook/MCP → ChatGPT/Grok Bot；CF Worker 可自部署。垂直 Routine 信号 | Routines / Niche | **GitHub** |

### Skip（本轮）

空仓/hackathon（sere-nity/grok-bot-hackathon、lukataylo、JadMzk、aleetreny/spaceXAI、kerm1it/grok-bot-exts、yousafnazir）；游戏（ikeriano、frank-otto/cauldron）；交易/Web3（ZuskiVibeCode、Midnight-GrokBot、pumpdatafun、BreadidChickn、Hobie1Kenobi）；bot 自产站（easypost、Viktorych、wop-tracker、morning-brief 类）；包装/空 README（QuinnEckart/digitalocean、andraetbusiness-code/grokbot-desk）；替代品已列或续观（rome-os/rome、CelestoAI/celesto、Ayuilos/Miffan、snorlax、CodeCaps 配额表）；danielfebrero/grok-bot-cerveau（法文薄 README）；timber-love 个人公司 24 提示（偏私有作战室）；apple-reminders-mcp（通用 MCP 非 Grok 专向）；已列 agent-tincan / ourobot / kiwi-hook / harness-bridge / grok-bot-router / weixin / Tesla 连接器等；营销/额度帖交 X 大 V 雷达。

## 2026-10-23 08:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 02:07→08:07（Asia/Shanghai）`gh search`（"Grok Bot" / grokbot / grok-bot 更新与今日新建）+ X `url:github.com` / 玩法帖。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| inematds/grokbot-7-agentes | https://github.com/inematds/grokbot-7-agentes | **7 张可粘贴 Agent 卡（PT/EN/ES）**：每卡含任务说明、自主等级 N0–N3、3 条上线前测试、监督清单与 routine；含 Shield/尽调/社媒/议价/CFO/共享 Brain/总管，并写「另建 Bot 的三理由」与「绝不代批」。带静态指南站。可直接抄的多 bot 作战室配方，本轮最值得看。无 SPDX，短评注明 | Multi-bot / War room | `multi-bot` `agent-cards` `approval-gate` `routines` `pt-en-es` | 0 / 无 License | **GitHub**（10-22 本窗新建 ~22:32 UTC） |
| Obiwayne/grokbot-receipts | https://github.com/Obiwayne/grokbot-receipts | **@bot 事实核验 skill + CLI**：归档源文（Markdown+SHA）、逐字核对引文、须两家独立站才给 supported/contradicted；只出报告/卡片/回复草稿，不发帖。附 `grok-bot/skills/receipts.md`。作者写明 Grok Bot 包尚未在真机实测，短评须注明。同作者已有 inbox-assistant | Skills / Fact-check | `skill` `fact-check` `tag-bot` `archive` `mit` | 0 / MIT | **GitHub**（10-22 建，本窗后于 02:07） |
| kitepon/grokbot-bridge | https://github.com/kitepon/grokbot-bridge | **共享通话桥 MCP**：先 webhook 叫醒队友，再同 endpoint 直聊；电话簿对齐 Grok Bot / BellTeam，本地侧接 Codex / Claude Code / Cursor（含 Throughline 交接、席位重投）。日文为主 README + Docker。MIT，偏进阶多 runtime 通话面，可对照已列 agent-tincan / hermesh | Skills / Bridges | `mcp` `call-bridge` `multi-agent` `claude-code` `codex` `mit` | 0 / MIT | **GitHub**（本窗仍推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| SilasSolivagus/dsh-grokbot-bridge | https://github.com/SilasSolivagus/dsh-grokbot-bridge | 本机 DSH↔云端 Grok Bot 私有长轮询中继（可选 GitHub Issue 回退）+ JSON 协议；无 SPDX，偏个人测试总线，先信号 | Bridges / Maybe | **GitHub**（本窗更新） |
| nessielabs/nessie-grokbot | https://github.com/nessielabs/nessie-grokbot | 官方 Nessie 上下文库插件（托管 MCP + skill），需 Nessie 账号与 Cloud Sync；MIT 商业依赖 | Plugins / SaaS | **GitHub**（本窗更新） |
| digitalocean/grokbot-plugin | https://github.com/digitalocean/grokbot-plugin | DO 官方插件仓：7 MCP + 11 skills + 审批档；README 主写 Cursor Marketplace，仓名 grokbot-plugin，是否原生装进 Grok Bot 待核。对照已 skip 的 QuinnEckart 空壳 | Plugins / Cloud | **GitHub**（本窗新建） |
| antonyfuentesdev/spanish-teacher-course-pack | https://github.com/antonyfuentesdev/spanish-teacher-course-pack | 已推 spanish-teacher-bot-template 的配套课件包（A1–C1）；CC BY-NC，勿当新主条目 | （模板配套） | **GitHub** |

### Skip（本轮）

空仓/无 README（hdhshj2883/grokbot、tony-wei-chang/todo-for-grok-bot、github031524/Grok-Bot-Ideas、yousafnazir、mmorrone90）；游戏/黑客松产物（AxENSRennes、NadavRaviv/octopus、ikeriano/pasapalabra、frank-otto、rashad-h/bot-constellation、shahaman098/BumpIn、goingafk/eventBounty）；bot 自产站（Viktorych、easypost、judgement-day、personal-news-reader、scapp）；替代品续观（orca/rakazo/OpenMausBot/rome/snorlax/agni/celesto/BillulloNex/Starship/flobot/Leka74/openbot）；已列 TetherBot / Tesla 连接器 / hermesh / cooks / spanish-teacher-bot-template / agent-tincan / grokbot-delivery-team / changelog-watch / grok-wear / BugenZhao CLI / Obiwayne inbox-assistant / maplenk 等；商业薄插件（tao-inc/*、Paloma*）；timber-love 个人 24 提示（偏私有）；grapevine（用 Bot 做的社区知识站，非可复用 bot 配方）；营销/币安 Agent 钱包撸毛帖交 X 大 V 雷达。

## 2026-10-23 10:00 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 08:07→10:00（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| markmcnair/chief-of-staff-kit | https://github.com/markmcnair/chief-of-staff-kit | **「幕僚长」Bot 的底层管线**：Beeper（WhatsApp/Signal/Telegram）+ Mac iMessage 新消息 POST 到 Grok Bot webhook routine；Bot 起草回复，只有你批准的行才经 Supabase outbox 发出；另带 SQLite 习惯/健身打卡 CLI。stdlib Python、密钥走 env 不入仓。「审批后才外发」的可抄范式，本轮最值得看 | Routines / Approval-gated outbox | `webhook` `routine` `approval-gate` `imessage` `beeper` `mit` | 0 / MIT | **GitHub**（10-23 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| yeemio/grokbots-team | https://github.com/yeemio/grokbots-team | 多 Bot 团队公开运维小工具：PR 交接标记自动唤醒总管、脱敏素材→X 草稿队列（不自动发）、首小时爆帖提醒；规则「X 只研究/草稿，人来发」。偏个人团队，先信号 | Multi-bot / Ops | **GitHub**（10-23 本窗新建） |
| cshenx/agentpeers | https://github.com/cshenx/agentpeers | Codex ↔ Claude Code 同机会话互聊；README 称 0.7 预览加 Grokbot ↔ Dot。Grok 侧尚为预览，可对照已列 agent-tincan / hermesh | Bridges / Maybe | **GitHub**（本窗更新） |
| tommy-muckstack/myman | https://github.com/tommy-muckstack/myman | 本机会议纪要/听写/截图 OCR/录屏全落 markdown，经 MCP 或 JSON CLI 给 Claude / Grok Bot / Cursor 用；Apache-2.0，通用工具非 Grok 专向 | MCP / Local memory | **GitHub**（本窗更新） |

### Skip（本轮）

空仓/无 README（HudsonSuth/second-brain-grok-bot、madchun/grokbot-use-cases-brief、bubmiller/mygrokbots）；游戏（dalixinc/zx-engine、ikeriano/pasapalabra）；交易（swcstudiospace/PumpGrok）；bot 自产站/个人报告（indrayam/samachar、iamnio0806-commits/tw-stock-daily-reports、hrtaym1114-github/grokbot-dashboard、JorgeDeArmas/grok-canvas）；neomatrix369/grapevine（上轮已 skip）。

## 2026-10-23 10:45 Asia/Shanghai · T7 日更雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:00→10:45（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" 本窗更新）+ X 公开搜索（本窗 X 侧仅文章帖，交 X 大 V 雷达）。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| hunvreus/grokbot-discord | https://github.com/hunvreus/grokbot-discord | **Discord 斜杠命令 → Grok Bot routine webhook 中继**（Cloudflare Worker）：替 Discord 做 PING 应答、Ed25519 验签、3 秒内 deferred 回复和 sender key 头注入；用户/服务器/频道白名单，非名单直接拒；Bot 用 payload 里的 followup_url 回到原频道，无需 bot token（交互令牌 15 分钟过期）。「外部聊天入口接 webhook routine」的干净范式，可对照 grokbot-weixin / chief-of-staff-kit，本轮最值得看 | Routines / Webhook bridges | `webhook` `routine` `discord` `cloudflare-worker` `allowlist` `mit` | 0 / MIT | **GitHub**（10-23 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| bayardoassistant-ship-it/unifi-network | https://github.com/bayardoassistant-ship-it/unifi-network | UniFi Network 官方 Integration API 的 MCP 插件（26 工具 + raw 请求），README 写给 Cursor & Grok Bot；需 UniFi API key，偏家用/机房网管，先信号 | Plugins / Infra | **GitHub**（本窗新建） |
| severusgao/hermes-office | https://github.com/severusgao/hermes-office | 中文自托管「Grok Bot 式 AI 团队」替代：Hermes Agent 上加办公室主任 + 多原生 CLI + 合同验收/互审；替代品，归入续观 | （替代品续观） | **GitHub**（本窗新建） |

### Skip（本轮）

Ajitkumar-1001/Grok-bot（仅 idea pitch）；其余本窗更新仓均已列或上轮已 skip。

## 2026-10-23 12:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:45→12:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" 等本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| PhillipHolland/security-audit-bot | https://github.com/PhillipHolland/security-audit-bot | **给 Grok Bot 用的「安全审计 Bot」配方**：先确认仓是你的或有授权，只读浅克隆（禁 hooks、不跑项目代码），开源扫描器出线索，再交 Cloudflare security-audit skill（钉 commit+校验哈希）逐条验证，报告过 lint 拦截密钥/高熵串；全量审计耗额度会先问。「扫描器只给线索、skill 验证才算发现」的分层范式，本轮最值得看 | Skills / Security bots | `skill` `security-audit` `cloudflare` `read-only` `授权确认` | 0 / 未声明 License（收录前请核） | **GitHub**（10-23 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| shimeiyou/mixin-grokbot | https://github.com/shimeiyou/mixin-grokbot | Mixin Messenger Bot 常驻网关：持 Blaze WebSocket、解密后以 JSON 投到你的 Agent/webhook（落盘队列、重试、去重），回复走自带 CLI；附件目录白名单防注入乱传文件。README 未点名 Grok Bot（仓名含），可对照 grokbot-discord / grokbot-weixin，先信号 | Routines / Webhook bridges | **GitHub**（10-23 本窗新建，MIT） |
| d-513/grok-bot-nix | https://github.com/d-513/grok-bot-nix | 非官方 Nix flake 在 Linux 跑 Grok Bot 桌面端，Action 每 6 小时自动更新 .deb 钉版；安装向工具，可放 Setup/Community | Setup / Linux | **GitHub**（本窗更新，未声明 License） |
| getrocky-world/rocky-plugin | https://github.com/getrocky-world/rocky-plugin | Rocky 个人「世界模型」MCP 插件（支持 Grok Bot），首次读取/外发都要在手机上点同意；商业服务 + Mac App，先信号 | MCP / Personal context | **GitHub**（本窗更新，MIT） |

### Skip（本轮）

rayhomie/grokbot_page（空 README）；shahaman098/grok-bot（黑客松社交 App，非玩法）；donniertf-hub/grok-doubles-picks（博彩 picks）；scapp/personal-news-reader（个人自产站）；BlancoKat/omarchy-grokbot-updates（Omarchy 菜单更新项，过窄）；asgeirtj/system_prompts_leaks（提示词泄露合集，不收）。

## 2026-10-23 14:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 12:07→14:05（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / routine / skill 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| runesleo/multi-ai-sync | https://github.com/runesleo/multi-ai-sync | **多 AI 结果回流体检**（Grok Bot + Claude Code 等）：`ai-sync.json` 登记每个 agent 的聊天/结果文件/记忆该落在哪，只读脚本逐层报 OK/STALE/MISSING；配套 SKILL.md 讲「本机定时拉取会因沙盒休眠静默超时 → 改成 agent 主动推送 + 记忆双向同步」。正中多 bot 协作的痛点，有中英文 README，本轮最值得看 | Multi-bot / Collaboration | `skill` `multi-agent` `sync` `audit` `claude-code` `mit` | 0 / MIT | **GitHub**（10-23 本窗新建） |
| howardpen9/tg-stars-workflows | https://github.com/howardpen9/tg-stars-workflows | **Grok Bot 工作流的 Telegram Stars 公开货架**：买家在 TG bot 付 Stars，签名 webhook 唤醒创作者的 Grok Bot routine 干活回传；仓只放公开 listing（明令不放 webhook URL/密钥），创作者按模板提 PR 上架，有 /want /vote /preorder 需求板。「把 routine 变成可售服务」的范式，分成/签名唤醒仍是 phase 2，先收为实验性 | Routines / Webhook marketplaces | `webhook` `routine` `telegram` `marketplace` `experimental` | 1 / 未声明 License（收录前请核） | **GitHub**（10-23 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| pinjun99/Grokbot_Jarvis | https://github.com/pinjun99/Grokbot_Jarvis | Mac 本机 MCP 桥（经 Cloudflare 隧道）让 Grok 截屏+键鼠操作 App，带权限模式和弹窗确认；能力面大、安全面也大，先信号 | MCP / Desktop control | **GitHub**（10-23 本窗新建，License 待核） |
| Railbed/cursor-plugin | https://github.com/Railbed/cursor-plugin | 商户支付 Railbed 官方插件（Cursor & Grok Bot，MCP+skills+只读审查 agent，Test/Live 分离）；商业支付服务，先信号 | Plugins / Payments | **GitHub**（10-23 本窗新建，MIT） |
| kungFuDOOM/botbook-public | https://github.com/kungFuDOOM/botbook-public | 只许 @mail.grokbot.com 邮箱验证的 bot 发帖的「bot 版 Facebook」，bot 经 API 自己发帖互动；趣味社区，先信号 | Community / Fun | **GitHub**（本窗更新） |

### Skip（本轮）

shibainu-inu/grokspot（无 README）；frank-otto/graveyard-golf（小游戏，非玩法）；lucifer-grokbot/lucifer-grokbot（空仓）。

## 2026-10-23 16:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 14:05→16:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / routine / skill 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| MarkusIsaksson1982/grok-bot-local-first | https://github.com/MarkusIsaksson1982/grok-bot-local-first | **省额度的「本地优先」套件**：确定性活交给 Python 3.12 标准库 worker（`grokkit.py` 跑一个 worker、只吐一行 JSON），JSON 要求判断时 bot 才花一轮；附 tasks.json 注册表、返回格式 schema、Linux/Windows 安装脚本和 smoke 测试，另有 enablement kit 做 skill-lint（查 frontmatter、个人路径、凭据）。「bot 只做判断、脚本做苦力」的范式，本轮最值得看 | Skills / Cost & efficiency | `skill` `local-first` `python` `skill-lint` `mit` | 2 / MIT | **GitHub**（本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Veitkwok/Master | https://github.com/Veitkwok/Master | 中文美股/ETF 研究技能包：install.sh 装进技能库 + 5 类 routine 模板（KOL 选股→估值/陷阱→持仓对照→建议卡），写明不自动下单、审批分级、预放行固定命令；依赖外部模型 key、金融向，先信号 | Skills / Finance | **GitHub**（10-23 本窗新建，未声明 License） |
| lilpenguinnn/grok-bot-maid-avatar | https://github.com/lilpenguinnn/grok-bot-maid-avatar | 中文「一键给名下所有 bot 换统一风格头像」提示词：同母版锁姿势、按职能分配发色/徽章，出总览图 QA 后**先问再换**；趣味向但「先展示再确认」流程可参考，先信号 | Fun / Avatars | **GitHub**（10-23 本窗新建，未声明 License） |
| SimianX-AI/simianx-skills | https://github.com/SimianX-AI/simianx-skills | 商业投研服务的 skill + 远程 MCP（8 agent 研究委员会、实时新闻流，点名支持 Grok Bot）；商业服务，先信号 | MCP / Finance | **GitHub**（本窗更新，MIT） |

### Skip（本轮）

Wifikir/WifikirMail（无说明的私人工作仓）；danimoya/grok-bot-arch、shibainu-inu/grokspot（前轮已记）。

## 2026-10-23 18:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 16:07→18:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / skill / routine 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Olivia295/grokbot-team-monitor-UI | https://github.com/Olivia295/grokbot-team-monitor-UI | **多 bot 团队「监控室」**：把 Grok Bot 团队画成一间办公室，看每个 bot 在干嘛、谁把活交给谁、卡在哪、一条任务从你发消息到最终回复走了几跳；本地只读、Python 零依赖、中英双语、有在线 demo（真实数据有标注）。正中多 bot 作战室可视化，本轮最值得看 | Multi-bot / Observability | `multi-agent` `dashboard` `read-only` `zh` `mit` | 1 / MIT | **GitHub**（10-18 建，本窗更新） |
| devrecated/grokbot-management-console | https://github.com/devrecated/grokbot-management-console | **routine 总控台**：一页看所有 bot 的 routine 和每次运行，可暂停/改时间/改提示词、一键全停，看 box 负载与日志，routine 坏了发邮件；Next.js + Postgres（Vercel/Neon 免费档），有假数据 demo。需在 box 放脚本回传，部署前自查权限 | Routines / Management | `routine` `dashboard` `nextjs` `self-host` `mit` | 1 / MIT | **GitHub**（10-20 建，本窗更新） |
| beansmile/geo-checker-grok-bot-scripts | https://github.com/beansmile/geo-checker-grok-bot-scripts | **GEO（生成式引擎优化）体检 skill 运行时**：Python 标准库爬站 → 9 维规则打分 → 出 report.md/html，LLM 补充由 bot 自己做、无需外部 key。「脚本做苦力、bot 做判断」的又一实例，出海站长可直接用 | Skills / SEO & GEO | `skill` `geo` `seo` `python` `mit` | 0 / MIT | **GitHub**（10-23 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| meeting-ai/memo-grok-bot-plugin | https://github.com/meeting-ai/memo-grok-bot-plugin | Meeting.ai 官方 Grok Bot 插件（远程 MCP：入会记录、纪要、Visual Notes）；商业服务，先信号 | Plugins / Meetings | **GitHub**（Apache-2.0） |
| LiliLIN0324/floorplan-to-3d | https://github.com/LiliLIN0324/floorplan-to-3d | 中文平面图转 3D skill：识别结构→人确认比例→再挤出，「确认前不报米数」的人在环设计可参考；垂直场景，先信号 | Skills / Vertical | **GitHub**（10-23 本窗新建，README 称 MIT 但无 LICENSE 元数据） |

### Skip（本轮）

RomanReb/grok-telegram-bot（空描述，疑似非 Grok Bot）；dave-1024/falconfpga（FPGA 项目，非玩法）。

## 2026-10-23 20:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 18:07→20:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / skill / routine / plugin 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| drumpat01/android-grok-home | https://github.com/drumpat01/android-grok-home | **把自己的多 bot 团队搬上 Android 桌面**：非官方原生启动器 APK（Android 11+，不刷机），动画头像墙显示每个 bot 在干活/举手/完成，语音+文字对话，经电脑端 BDK 桥接到你自己已有的 bot；不含任何账号或 key，有 Demo 模式和写给 coding agent 的 AGENTS.md 安装指引。多 bot 作战室的「随手看板」，本轮最值得看 | Multi-bot / Clients | `android` `launcher` `bdk` `voice` `mit` | 6 / MIT | **GitHub**（10-17 建，本窗更新） |
| imranbarbhuiya/grokbot-widget | https://github.com/imranbarbhuiya/grokbot-widget | **macOS 悬浮小伙伴**：可拖动的浮窗角色 + 展开式聊天面板，经官方 BDK 扩展连已有 bot，有 arm64/x64 release 包；头像可自定义。轻量桌面入口 | Clients / Desktop | `macos` `widget` `bdk` `mit` | 0 / MIT | **GitHub**（10-05 建，本窗更新） |

### Skip（本轮）

goupenguin/grok-bot-maid-avatar（与上轮 lilpenguinnn/grok-bot-maid-avatar 同款头像提示词，不重复记）；dkooou/grokbot-drama、gab709/grok_bot_example（空 README）；KT3746/grokbot-1945、ikeriano/rueda-la-letra-grok-bot（游戏，非玩法）；addidotlol/grok-rpm、gallez-tech/grok-bot-bin（Linux 打包，非玩法）；robdevops/grokbot（Telegram LLM bot，非 Grok Bot）。

## 2026-10-23 22:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 20:07→22:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / skill / routine / plugin / multi-bot 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Vedant817/vesper-grok-bot-bridge | https://github.com/Vedant817/vesper-grok-bot-bridge | **让 Grok Bot 当 coding agent 的「监工」**：派任务、看 agent 回复、替它补技术输入、同一会话里要求返工，最后看真实验证结果再验收；两套 Bot 模板（T3 Code 走 T3 Connect / 其他 ACP 编码 CLI 走本仓 MCP 桥，隔离 git worktree），写明不会悄悄在后端间转派、导入模板不装软件不登录账号；有 CI 和系统设计文档。本轮最值得看 | Multi-bot / Coding agents | `mcp` `coding-agent` `supervision` `worktree` `mit` | 0 / MIT | **GitHub**（10-23 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| company-notes/grokbot-persona-factory | https://github.com/company-notes/grokbot-persona-factory | Persona Forge：生成 bot 人设（职责、决策边界、说话风格、工作流）+ 头像多画风，中英繁简；额度用完退回「给你自己的 Grokbot 一段提示词」；Cloudflare Worker 自部署，未声明 License，先信号 | Templates / Personas | **GitHub**（10-23 本窗新建） |

### Skip（本轮）

Ormus-Solutions/liquid-gold-grok-bot（前轮已记观察）；hustnn/pocket-bots（自建多 bot 框架、驱动其他 CLI，非 Grok Bot 玩法）；mariotoffia/grokbot-backup、Adambkr/Grokbot、brucksh0t/born-hood-grokbot-preview（个人/空仓）；OpenSelfHosting/skills（通用编码 skill 合集）；aijorgenson/grokbot-nixos（打包）。

## 2026-10-24 00:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 22:07→00:10（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / skill / routine / multi-bot 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| mascarock/grokbot-inbox | https://github.com/mascarock/grokbot-inbox | **在浏览器里像邮件客户端一样看 bot 自己的收件箱**：bot 按 `bot/SKILL.md` 只读导出邮件，打包进 URL fragment（不发往服务器），纯前端页面本地解码显示；写明不发信不回信、邮件内容按不可信处理，支持 +tag 子地址，附虚构 demo。本轮最值得看 | Skills / Email | `inbox` `skill` `read-only` `privacy` `mit` | 0 / MIT | **GitHub**（10-23 本窗新建） |
| Zhanweelee/wechat-clawbot-grok-bridge | https://github.com/Zhanweelee/wechat-clawbot-grok-bridge | **中文：微信 ClawBot ↔ Grok Bot webhook routine 桥**：Go 单二进制，扫码登录、长轮询收消息转发到 webhook、本地 HTTP 接口回帖、「正在输入」状态；声明 clean-room 非 fork，有 CI。与已记的 bogao6769-netizen/grok-bot-wechat 同方向，可二选一或并列，短评须提醒微信接口合规风险 | Chinese solo-founder / Channels | `chinese` `wechat` `webhook` `routine` `go` `mit` | 0 / MIT | **GitHub**（10-23 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| wonder-missing/asksoul | https://github.com/wonder-missing/asksoul | 终端里和团队主 bot 对话（问→等回复→续聊），「把仓给 bot 让它自己装」；仓里目前只有 README，无 License，先信号 | Clients / CLI | **GitHub**（10-23 新建） |
| AmitMirgal/orgbot-hub | https://github.com/AmitMirgal/orgbot-hub | orgbots.dev：Grok Bot 团队目录，按「要哪些岗位」用聊天从现有官方 x.ai/bot 模板里拼团队，只给官方链接不代装；无 License，投稿未开，先信号 | Directories / Teams | **GitHub**（08-29 建，本窗更新，此前未记） |
| johnatfreecoffee/myphone-plugin | https://github.com/johnatfreecoffee/myphone-plugin | 给 bot 一个真实电话号码（打/接电话、收发短信）的插件，指向托管 MCP；需付费第三方账号且有 TCPA/A2P 合规条款，偏商业，先信号 | Plugins / Phone | **GitHub**（10-23 本窗新建，MIT） |

### Skip（本轮）

rocket0xdev1025/grokbot402（空描述）；revazone/grokbotwar-game（游戏）；hast3/claudecrew（Claude 远程 app，非 Grok Bot 玩法）；alnutile/grokked-bot（替代 harness）；danger-dream/Parrot（API 中转）；0xRayAI/xray、zeenie-ai/OpenCompany（通用多 agent）；ZuskiVibeCode/quant-trading-system（交易）；larcisllc-lgtm/kalshi-handoff（个人管道）；SIMPL-Automation/ado-grok、xianyu110/grokbot（较旧，留待周更复核）。

## 2026-10-24 02:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 00:10→02:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / x.ai/bot / skill 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| RongleCat/grok-bot-esp32-sdk | https://github.com/RongleCat/grok-bot-esp32-sdk | **中文：把 Grok Bot 搬到 ESP32 硬件上**：非官方 ESP-IDF C++ 组件，浏览器 PKCE 登录、Bot 名册、发消息、Connect 回复流解码与游标、头像参数；README 明确凭据不写日志、不硬编码。作者即已收的 grok-bot-clipper，可放硬件/SDK 方向。本轮最值得看 | Clients / Hardware | `chinese` `esp32` `sdk` `iot` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| homemetax/grok-bot_discord-connector | https://github.com/homemetax/grok-bot_discord-connector | 每个 bot 一个独立 Discord 应用，消息转 routine webhook、REST CLI 回帖，带白名单/日限/防回环和 setup skill，文档齐；无 License，与已记 hunvreus/grokbot-discord 同方向，先信号 | Channels / Discord | **GitHub**（10-23 建） |
| multi-turn-inc/forget-cursor-plugin | https://github.com/multi-turn-inc/forget-cursor-plugin | 多工具共享长期记忆插件（远程 MCP，每轮召回+存档，标注日期/来源、无证据答「不在记忆里」）；托管商业服务，Apache-2.0，先信号 | Plugins / Memory | **GitHub**（10-24 本窗新建） |

### Skip（本轮）

saikrishnauppaluri/plan-to-3d（与已记 floorplan-to-3d 同类商业插件）；nlaughter100/grokbot-dashboard、r67018/grokbot-manaba-reminder、kyledrobinson/grokbot（空/无 README）；scott-gibson-se/BoxoPolo（个人收纳 app）；alexgreensh/outsourcerer、r2hu1/openbots、ansaribilal14/personal-social-agent（通用多 agent/社媒引擎，非 Grok Bot 玩法）。

## 2026-10-24 08:01 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 02:07→08:01（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / x.ai/bot 本窗更新）；本轮 X 侧交 X 大 V 雷达。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| vib-z/stampede | https://github.com/vib-z/stampede | **Grok Bot 当入口、本机 Claude Code 当监工**：经 Tailscale 私网把 bot 收到的任务交给 Mac 上的 Claude Code lead，由它在 Herdr 工作区里分派 Codex/Cursor 等本地 agent，进度走 webhook 回 bot，需要人拍板时 bot 在聊天里问；有 CI、CHANGELOG，也可脱离 bot 单跑。与已记 vesper-grok-bot-bridge 同方向但更完整。本轮最值得看 | Multi-agent / Coding | `claude-code` `tailscale` `webhook` `orchestration` `mit` | 3 / MIT | **GitHub**（10-22 建，本窗更新） |
| meir-bot/grokbot-executive-team | https://github.com/meir-bot/grokbot-executive-team | **一句 prompt 搭「高管团队」**：Chief Of Staff 中枢 + 产品/财务/运营/市场/法务/安全部门头，多项目时每个项目加一个 Project CEO 日报汇总；附规则、routines 指南和 4 分钟演示视频。灵感来自 timscheuerai/grokbot-gtm-team，可放作战室模板 | War rooms / Team templates | `team` `chief-of-staff` `routine` `template` `mit` | 0 / MIT | **GitHub**（10-16 建，本窗更新） |
| dallintwatts/grokbot-skills | https://github.com/dallintwatts/grokbot-skills | **模板导入不带 skills 时的补装做法**：bot 首次对话问一句「要我完成设置吗」，同意后从固定 commit 下载 skill，按 `PINS.txt` 的 sha256+大小逐个校验，不匹配就不装；服务 Second Opinion Council 与 Fleet Doctor 两个模板。思路可复用于自家模板分发 | Skills / Distribution | `skill` `template` `sha256` `supply-chain` `mit` | 0 / MIT | **GitHub**（10-16 建，本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| ddhjy/grok-bot-hub | https://github.com/ddhjy/grok-bot-hub | 中文非官方 Grok Bot 导航站（Git 管 catalog.json、GitHub Pages 展示，数据 CC0）；与本仓同类目录，可做「相关列表」互链或仅作参考，先信号 | Directories | **GitHub**（08-21 建，本窗更新） |

### Skip（本轮）

drewsephski/kith（替代品）；ofs100private/GrokBot、Chaoc2624/grokbot-backup、lhbzk/botAI_rd4x、ikeriano/pasapalabra-sb3-grok-bot（空描述/无 README）；duvida13/GROK-BOT（个人求职）；davidfweiser/NetworkSentinel、XiaJianbing150/x-ai-news-bot、jonathanchw/nextjs-boilerplate（非 Grok Bot 玩法）。

## 2026-10-24 10:37 Asia/Shanghai · T7 日更雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。周末窗口约近 24h（Asia/Shanghai 10-23 10:35→10-24 10:37）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-23 + updated≥2026-10-24）+ X `search_posts_all`（github.com / playbook / template / skills；本窗 X 侧多为 x.ai/bot 模板与功能建议，无新增可复用 GitHub 仓，交 X 大 V 雷达）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| anselmcmakin/local-ai-manager | https://github.com/anselmcmakin/local-ai-manager | **本机跑本地模型、Grok Bot 当监工**：模板装钉版脚本（硬件扫描 / 作业队列 worker / 60s watchdog / 127.0.0.1 仪表盘，含 Pause/Game Mode 卸 VRAM），只绑本机、containment.json 白名单、webhook 只报事实不问自重启；标准库为主、有测试。与 stampede / vesper 同向但偏「本地推理运维」。本轮最值得看 | Skills / Local AI | `local-ai` `ollama` `watchdog` `dashboard` `tailscale` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| TeebooTed/desk | https://github.com/TeebooTed/desk | **本机单文件项目看板 + Message bot**：file:// 打开，按项目（非看板列）看进度；经本地 relay 把消息打到 Grok Bot webhook routine，另有 Bot 模板让 Bot 写 status.json / live.json 并建「Desk refresh」routine。附 install.sh 与布局/同步文档 | Clients / Dashboards | `dashboard` `webhook` `routine` `local-first` `mit` | 0 / MIT | **GitHub**（10-23 建，此前日更漏收） |
| Obiwayne/dawnbrief | https://github.com/Obiwayne/dawnbrief | **早 7 点一日简报**：日历+空档、需处理邮件、Miniflux/RSSHub 新闻、Top3、可跳过会议（仅建议）；只读、不过额度 70% 则缩写。附本机 `dawnbrief preview`（ICS+Takeout+feeds）先看再授权。同作者 inbox-assistant / receipts，Grok 包作者称尚未真机测，短评须注明 | Routines / Digests | `routine` `calendar` `email` `rss` `preview` `mit` | 0 / MIT | **GitHub**（10-23 建，此前漏收） |
| Obiwayne/sweepmail | https://github.com/Obiwayne/sweepmail | **Gmail 清理 skill + 本机干跑**：按发件人分组提议 trash/unsubscribe，人批后再分批 500；周 routine 保洁；`sweepmail check` 只读吃 Takeout 出报告。同 dawnbrief 作者，Grok 包未真机测须注明 | Skills / Email | `gmail` `skill` `dry-run` `takeout` `mit` | 0 / MIT | **GitHub**（10-23 建，此前漏收） |
| brentolmate/hotel-gbp-local-seo | https://github.com/brentolmate/hotel-gbp-local-seo | **酒店 Google 商家资料 + 本地 SEO 技能包**：审计、月计划、中英西语评价/客服草稿、地图竞品缺口、弱站重建计划；只读公开信息+草稿，不改 GBP/不发帖/不联系外人。可作垂直行业 skill 范例 | Skills / Vertical SEO | `gbp` `local-seo` `hotel` `draft-only` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| datadda27/grokbot-skills | https://github.com/datadda27/grokbot-skills | **公开模板的「活 skills」仓**：ticket-watch / portal-tracker 等，模板 Bot 每次跑前从此仓拉最新 skill，修一次全用户受益。与 dallintwatts/grokbot-skills（首次对话校验安装）互补，可并列 | Skills / Distribution | `skill` `live-update` `templates` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| alpha404ai/grok-one-shot | https://github.com/alpha404ai/grok-one-shot | **一次做完少返工**：目标+完成定义 → ≤5 步计划 → 单遍执行 → 自检；不确定只问一题；周五按重试次数晋升模板。可复制 prompt + templates/，轻量可抄 | Skills / Playbooks | `prompt` `one-shot` `self-check` `mit` | 0 / MIT | **GitHub**（10-23 建，此前漏收） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| TomCruiseTorpedo/MBTI | https://github.com/TomCruiseTorpedo/MBTI | 16 型人设提示（韩式小谈语境），写明兼容 Muse / Grok Bot 等；人设玩具向，先信号 | Templates / Personas | **GitHub**（10-23 新建，Apache-2.0） |
| alpha404ai/grok-market-analyst | https://github.com/alpha404ai/grok-market-analyst | 读 X/新闻/财报抽可核验主张并自评分+周复盘，声明不交易；同作者 one-shot，投资语境先信号 | Routines / Research | **GitHub**（10-23 新建，MIT） |
| oriorai/orior-plugin | https://github.com/oriorai/orior-plugin | 一致人脸角色图/视频 MCP（Grok Bot / Cursor），仓仅 manifest+skills；托管商业+OAuth，先信号 | Plugins / Media | **GitHub**（10-23 新建，MIT） |
| Broche-Ballet/broche-grok-bot-plugin | https://github.com/Broche-Ballet/broche-grok-bot-plugin | 芭蕾课表搜索 MCP（会员工具需登录）；垂直会员场景，先信号 | Plugins / Vertical | **GitHub**（10-23 新建，MIT） |

### Skip（本轮）

ronnarit09-hub/Grokbot-backup、mariotoffia/grokbot-backup、nlaughter100/grokbot-dashboard、rocket0xdev1025/grokbot402、Adambkr/Grokbot、brucksh0t/born-hood-grokbot-preview、ikeriano/*-sb3-grok-bot、qcteslaguy/qcteslaguy.github.io、jimmie01/jimmie01.github.io（礼物模板站）、PhillipHolland/ibot（iPod/MusicKit 页，非玩法）、fuzzynet/bot-open（仅开聊天链）、gab709/grok_bot_example、hast3/claudecrew（Claude 远程，非 Grok）、saikrishnauppaluri/sai-bots / plan-to-3d（已记同类）、Railbed/railbed-cursor-plugin（与已记 Railbed/cursor-plugin 同向商业支付）、bayardo-ship-it/unifi-network（与已记 bayardoassistant-ship-it/unifi-network 同向）、已列 stampede / vesper / mascarock inbox / esp32-sdk / hunvreus discord / multi-ai-sync / yeemio / grokspot / maid-avatar / persona-factory 等。X 本窗多为 x.ai/bot 模板分享与 @leerob 功能建议，无新 GitHub 可复用仓。

## 2026-10-24 12:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:37→12:05（Asia/Shanghai）`gh search`（grokbot / grok-bot / "grok bot" / "Grok Bot" created≥2026-10-24 + updated≥2026-10-24）+ X `search_posts_all`（github / playbook / skills / routine；本窗多为功能建议与商业 skill 营销，无新增可复用 GitHub 仓）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| onlymehdi/broom | https://github.com/onlymehdi/broom | **Gmail 垃圾清理 Cursor/Grok Bot 插件（skills-only）**：引导配置收件箱/保护发件人/优惠券处理，建定时 routine；只移 Trash、不永久删、不擅自退订，银行/安全码/订单默认保护，边缘邮件留箱并列表。无额外 MCP/账号/key。与已记 Obiwayne/sweepmail（干跑+Takeout）互补，本轮最值得看 | Skills / Email | `gmail` `skill` `plugin` `routine` `safety` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| alpha404ai/grok-cost-cutter | https://github.com/alpha404ai/grok-cost-cutter | **省额度：用触发+2K 预检+缓存+夜间批+日硬顶跑 routine**：优先 webhook，时钟只做备份；无变化即停、同输入走缓存；周一按「每有用跑成本」降速、30 天无用则删。可复制 thrift prompt + routines.csv。同作者 one-shot / market-analyst，T7 漏收补入 | Skills / Cost | `quota` `routine` `webhook` `cache` `prompt` `mit` | 0 / MIT | **GitHub**（10-23 建，此前漏收） |
| anselmcmakin/personal-chef | https://github.com/anselmcmakin/personal-chef | **家庭周菜单模板**：问卷→过敏/预算硬约束→周六 routine 出周日–周六菜单→HTML/PDF 菜谱卡+分区购物单→Walmart 购物车（人登录、bot 不结账不改支付）。skills 纯说明无代码；同作者 local-ai-manager | Templates / Vertical | `template` `skill` `routine` `family` `mit` | 0 / MIT | **GitHub**（10-02 建，本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| markprovenzano/dividend-calendar-bot | https://github.com/markprovenzano/dividend-calendar-bot | 分红日历模板：Finance/Robinhood→Google Calendar，含 SETUP_PROMPT/skill/routine；无 License，投资语境先信号 | Templates / Finance | **GitHub**（10-24 本窗新建） |
| alpha404ai/grok-trading-desk | https://github.com/alpha404ai/grok-trading-desk | 24/7 交易台 9 块 prompt（无人审批成交），同作者 cost-cutter；声明非投顾，交易类先信号勿当主推 | Routines / Trading | **GitHub**（10-23 建，MIT） |
| shreekaramtech/kalpana-agent | https://github.com/shreekaramtech/kalpana-agent | 批量填模板出广告图/视频 MCP（Claude/Cursor/任意 MCP 客户端）；托管商业+自有账号，先信号 | Plugins / Media | **GitHub**（10-08 建，本窗更新，MIT） |

### Skip（本轮）

qcteslaguy/qcteslaguy.github.io、jimmie01/jimmie01.github.io（T7 已 skip）；PhillipHolland/ibot（iPod 页）；fuzzynet/bot-open（仅开聊天链）；doggy8088/grok-bot-learn（RongleCat 繁中镜像，上游已列）；afaraha8403/balabot（自托管多 agent，硬依赖 TypeSafe Jev 付费 API）；D1-2004/eino-employee-loop（Eino 框架「类 Grok Bot」决策环，非 Grok Bot 玩法）；已列 TetherBot / money-saver / BotFleet / Retasc / sweepmail / local-ai-manager / desk / hotel-gbp / datadda27 skills / Broche / orior / MBTI / market-analyst / one-shot / pumpfun / howardpen9 tg-stars 等。X 本窗多为 @leerob 功能建议、TermiX 营销、币安 Agent，无新 GitHub 可复用仓。

## 2026-10-24 14:06 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 12:05→14:06（Asia/Shanghai）`gh search`（grokbot / "Grok Bot" / grok created≥2026-10-24 + updated≥2026-10-24）+ X `search_posts_all`（github / playbook / skills / routine / A2A；本窗多为功能建议与 X Article，可复用仓以 GitHub 为主）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| bytec-ai/grok-x-bridge-example | https://github.com/bytec-ai/grok-x-bridge-example | **中文：让本机/Codex 经 Cloudflare Worker 派「搜 X」活给 Grok Bot**：Agent→Worker/D1→Bot webhook→内置 X 工具检索→脚本回传结果；脱敏副本含 `GROK_SETUP.md` 粘贴说明、Python 领取回传、本地 CLI、协议 schema 与握手先于搜索；写明只读不发帖、凭证不落聊天。与已记 mascarock inbox（只读看邮件）同属「外挂桥」，本轮最值得看。无 SPDX License，短评须注明 | Bridges / X research | `chinese` `webhook` `cloudflare` `x-search` `codex` `example` | 0 / 无 License | **GitHub**（10-24 本窗新建） |
| telegraphic-dev/a2a-exposed | https://github.com/telegraphic-dev/a2a-exposed | **给任意 Agent（含 Grok Bot）挂公网 A2A 收件箱**：Cloudflare Worker 出 Agent Card + JSON-RPC，入站变任务，webhook 叫醒 agent（也可轮询）；带 `.grok-plugin`、skills 与自托管/托管双路径。与已记 Rladmsrl/a2a-bridge（把 Bot routine **变成** A2A 服务）方向互补：本仓是「Bot 当 A2A 对等节点收派活」。作者今日 X 提 Grok Bot 用例，此前漏收补入 | Multi-bot / Interop | `a2a` `webhook` `cloudflare` `plugin` `mit` | 1 / MIT | **X** @telegraphic_dev + **GitHub**（10-08 建，此前漏收） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| thebigasifworks/quickemailverify-plugin | https://github.com/thebigasifworks/quickemailverify-plugin | 邮箱核验/洗名单托管 MCP（Grok Bot/Cursor），Apache-2.0；需 API key+额度，偏商业，先信号 | Plugins / Email | **GitHub**（10-24 本窗新建） |

### Skip（本轮）

mikegkelly/book-catalog-bot（模板落地页，领取链仍 Coming soon）；jakeitegsy/grok-pstack（Grok Build CLI 插件，非 Grok Bot）；pandashugo2025/grok-desk（Polymarket 纸盘交易）；saikrishnauppaluri/sai-bots（展示站，T7 已 skip）；Kshot3000/Midnight-GrokBot-Agent / andraetbusiness-code/grokbot-desk / boydt/morning-brief / fuzzynet/bot-open / qcteslaguy / jimmie01（已 skip 类）；已列 broom / cost-cutter / personal-chef / desk / local-ai-manager / stampede / a2a-bridge / persona-factory / mascarock inbox 等。X 本窗多为 @leerob 功能建议、TermiX 营销、币安 Agent、低粉 X Article，无新增可复用 GitHub 仓交玩法雷达以外。

## 2026-10-24 16:11 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 14:06→16:11（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + 关键词交叉）+ X `search_posts_all`×3（github/playbook/skills；本窗多为 TermiX 营销、@leerob 功能建议、低粉 X Article，无新增可复用 GitHub 仓）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Dissipative-ATLAS/stackchan-grok-bridge | https://github.com/Dissipative-ATLAS/stackchan-grok-bridge | **中文：StackChan 原厂语音把明确转交的问题交给已有 Grok Bot，结果用原厂音色朗读**：Mac 中转 + Cloudflare 回调信箱（不必开公网端口），`until_result` 自动续查；实机长任务约 173s/18 次续查只提交 1 次。与已记 fredericalix/my-botstack（自刷固件全栈）、RongleCat/esp32-sdk 互补——本仓**不刷固件**接已有 Bot。本轮最值得看。无 SPDX License，短评须注明 | Hardware / Bridges | `chinese` `stackchan` `webhook` `cloudflare` `voice` `bridge` | 0 / 无 License | **GitHub**（10-24 本窗新建） |
| deedade/grok-hermes-webhook | https://github.com/deedade/grok-hermes-webhook | **Grok Bot→本机 Hermes 最小 webhook 契约**：非空 `task` + 对 raw body 做 HMAC-SHA256 后再解析 JSON，返回 202 accepted；stdlib 接收 stub、零真实密钥入库、CI。与已记 jamesonedge/grokbot-hermes-bridge、Heldinhow/hermes-mcp-bridge 同方向但更薄，可作可复制合同参考；v0.1 只到验收、不跑作业 | Bridges / Hermes | `hermes` `webhook` `hmac` `contract` `mit` | 1 / MIT | **GitHub**（10-24 本窗新建） |
| yuehzhan/grokbot-usage-checkin | https://github.com/yuehzhan/grokbot-usage-checkin | **本机用量/打卡/搜索仪表盘**：周额度累计与日用量%、工作打卡、按日检索「谁做了什么花了多少」；数据不出本机，推荐跑在 Grok Bot 的 Linux 云电脑上；含 PNG HUD 与可选 Grok Build `/usage` 读取。可作额度可视化工具 | Tools / Usage | `usage` `dashboard` `local` `quota` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| cooperpt/apple-watch-grokbot-health | https://github.com/cooperpt/apple-watch-grokbot-health | **中文保姆级：Apple Watch/健康→快捷指令→webhook→Grok Bot 睡眠与活动小结**：开微信触发同步；原始 sleep_stage_values+durations 服务端汇总深度/核心/REM/清醒；配置只用占位符，禁提交真实密钥与健康导出。仓仅 README+LICENSE，可复制 playbook | Skills / Health | `chinese` `health` `shortcuts` `webhook` `playbook` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| nexus-ai-2045/grok-bot-dots | https://github.com/nexus-ai-2045/grok-bot-dots | 日文：离线实验用 Grok Bot/dot 签名回调与收件箱规格模型（mock、无实网、非生产）；MIT+测试齐全，先信号 | Bridges / Spec | **GitHub**（10-24 本窗新建） |
| deedade/hk-price-digest | https://github.com/deedade/hk-price-digest | 本地 CSV 比港超价格→md/json，标注可供 Grok Bot 等任意 agent 读；非 Bot 专属协议，垂直工具先信号 | Tools / Vertical | **GitHub**（10-24 本窗新建，MIT） |
| PostdockAI/grok-bot-plugin | https://github.com/PostdockAI/grok-bot-plugin | 托管 myagent MCP：一 Bot 一地址，webhook 仅作叫醒、消息走 MCP 收件箱；无 License、自称尚未真机装测，商业托管先信号（此前漏收） | Plugins / Inbox | **Web** + **GitHub**（9-10 建，漏收） |

### Skip（本轮）

ikeriano/ahoracaigo-java-grok-bot（粉丝游戏非玩法）；muhammadanggaalazura-commits/xauusd-ai-bot（交易电报）；TermiX Agent Skills 营销帖、币安 Agentic Wallet 教程、Gumroad 付费小队手册、低粉额度 X Article；@leerob 功能建议（Cells/PSK、用量图、routine 失败告警）；已列 broom / grok-x-bridge / a2a-exposed / stampede / esp32-sdk / my-botstack / hermes-mcp-bridge / grokbot-hermes-bridge / twhit223/grok-bot-cos 等。

## 2026-10-24 18:09 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 16:11→18:09（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + updated≥2026-10-24）+ X `search_posts_all`×2（github/playbook/skills；本窗多为功能建议、交易 skill 营销、低粉链，可复用仓以 GitHub 为主）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| sujian666666com-glitch/grokbot-video-mcp | https://github.com/sujian666666com-glitch/grokbot-video-mcp | **本机 MCP→已有会生成视频的 Grok Bot webhook**：stdio MCP（5 工具）提交文案/最多 5 张参考图→cloudflared 隧道唤醒 Bot 生视频→鉴权回调收 MP4（可去声、校验分辨率时长）；本地 setup_form 存 webhook/key（0600），含中英 README、routine 说明与 CI。不走单独计费的 xAI 视频 API。本轮最值得看 | Bridges / Media MCP | `mcp` `video` `webhook` `cloudflare` `bilingual` `mit` | 2 / MIT | **GitHub**（10-24 本窗新建） |
| si4ai/grokbot-wake-relay | https://github.com/si4ai/grokbot-wake-relay | **Webhook 风暴止损：合并重叠冷启动 + 交接笔记**：实测 5 POST≈1s 内全开并行；`relay.py` 空闲直转、忙时入队、`/done` 后一批带 `pending_count` 与上轮 note；`notify_on_exit.py` 后台 job 退出再叫醒空闲 Bot。stdlib+MIT+实测数字，可作多 Bot webhook 队形参考 | Bridges / Routines | `webhook` `relay` `coalesce` `handoff` `stdlib` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| kbanc85/claudia-grokbot | https://github.com/kbanc85/claudia-grokbot | **公开模板「Claudia 幕僚长」托管后端**：抓邮件/Slack/日历里的承诺→到期前提醒→晨报/日终复盘/周复盘；CSV ledger + Brain Page + 自更新 MANIFEST；从不擅自发信/发帖。附 x.ai/bot 领取链与 FOR-BOTS 操作手册。Apache-2.0 | Templates / Chief of Staff | `template` `routine` `ledger` `promises` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-24 本窗新建） |
| xiayulajiao/heytea-style-xhs-cover-skill | https://github.com/xiayulajiao/heytea-style-xhs-cover-skill | **中文：喜茶风小红书记号笔封面 Skill**：白底留白+拙朴手写字+蓝重点；须整仓安装（含 `assets/approved-cover.png`），附粘贴给 Grok Bot 的安装/调用指令。无 SPDX License，短评须注明；与喜茶品牌无隶属 | Skills / Chinese content | `chinese` `xiaohongshu` `skill` `cover` `no-license` | 0 / 无 License | **GitHub**（10-24 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Charonyuu/whatsmyagentdoing | https://github.com/Charonyuu/whatsmyagentdoing | 本机 Claude Code/Codex/Gemini 等活会话等距办公室视图（~51★ MIT）；Grok 适配 fork tim164863-hue/grokbot-office 无 README，先信号上游 | Clients / Dashboards | **GitHub**（10-23 建，本窗活跃） |
| ahmadaryanto/vibeyourtv | https://github.com/ahmadaryanto/vibeyourtv | Android/Google TV Wi-Fi debloat + 类 Apple TV 主页；附 x.ai/bot 与 grok-bot-skill；fork CleanYourTV，印尼文为主，垂直硬件先信号 | Templates / Hardware | **X** @orpheuskaze + **GitHub** |
| free-dam-man/cf-global-edge-node-skill | https://github.com/free-dam-man/cf-global-edge-node-skill | 通用 Agent（含 Grok Bot）一句话在 Cloudflare 搭免费节点并出订阅码；~124★，偏代理/自建节点，合规与是否进清单请 Claude 把关 | Skills / Infra | **X** @adorerlemex + **GitHub** |

### Skip（本轮）

SherlockGy/grokbot-knowledge-archive（空仓）；tim164863-hue/grokbot-office（无 README/License，见上游信号）；alpha404ai/grok-bot-skills（交易 skill，早先 Skip）；owenservera/grokbot-telemetry、Spidermanrobin/awesome-grokbots、company-notes/grokbot-persona-factory（已列）；andraetbusiness-code/grokbot-desk、Kshot3000/Midnight、rocket0xdev1025/grokbot402、i-nowu/grokbot-games-free（已 skip 类）；OpenBot/CopilotKit 替代品营销、币安/$REAGENT、Gumroad 付费小队、@leerob 功能建议。X 本窗无新增独立可复用仓（alpha404 自宣包已记）。

## 2026-10-24 20:01 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 18:09→20:01（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-23–24）+ X `search_posts_all`×4（github / playbook / skills / 中文玩法；本窗多为币安 Wallet、Vault 建议、StackChan 长文转述，可复用仓以 GitHub 为主）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| ssamssae/grokbot-telegram-bridge | https://github.com/ssamssae/grokbot-telegram-bridge | **本机 Mac：私有 Telegram bot ↔ 已有 Grok Bot**：`getUpdates`→routine webhook 入站；每 3s 读桌面 App 本地会话副本回传，无屏幕自动化；仅放行配置的 chat id；stdlib+测试+韩/英 README+launchd 样例。同作者 Claude/Codex/Cursor/Grok 桥系列的 Grok **Bot** 版。本轮最值得看 | Bridges / Mobile | `telegram` `webhook` `macos` `stdlib` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| justhalfbit/xiaozhi-hub-server | https://github.com/justhalfbit/xiaozhi-hub-server | **中文：小智协议语音中枢**（StackChan/ESP32）：叫名字分派 Claude Code / 各家 API / **Grok Bot**（Cursor 登录勾选 Bot，长任务可打断、做完设备主动汇报）；管理后台+一键装；注明走 App 内部接口非官方 API。与已记 Dissipative-ATLAS/stackchan-grok-bridge（不刷固件接已有 Bot）互补——本仓是完整听/说网关。此前漏收；今日 X 中文 StackChan 帖热 | Hardware / Bridges | `chinese` `stackchan` `xiaozhi` `voice` `grok-bot` `mit` | ~17 / MIT | **X** @0xlangeai/@noahduck283 等 + **GitHub**（10-18 建，此前漏收） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| clsasa1/grokbot-telegram-bridge | https://github.com/clsasa1/grokbot-telegram-bridge | 俄文：在 **Grok Bot 云电脑**上跑 relay（媒体/语音 whisper、论坛分 topic、watchdog、tg-* 回传）；与 ssamssae（Mac 读本地副本）路径不同。无 SPDX License，先信号 | Bridges / Telegram | **GitHub**（10-24 本窗新建） |
| SINYC123/grok-bot-resources | https://github.com/SINYC123/grok-bot-resources | 把 @Greshamtrade「146 模板」帖里的 20 个推荐仓抄成清单；无 License、非新玩法，作索引信号即可 | Learning / Index | **GitHub**（10-24 新建） |

### Skip（本轮）

ssamssae 以外的交易仓 joaaoazul/grok-bot；Wifikir/WifikirMail（私人空仓）；mikegkelly/book-catalog-bot（模板落地页 Coming soon，已 skip）；SherlockGy/grokbot-knowledge-archive（空）；tim164863-hue/grokbot-office（无 License fork，上轮已信号）；ikeriano/* 游戏；danimoya/grok-bot-arch（前轮已记）；monokernn/REAGENT / 币安 Agentic Wallet / $REAGENT 营销；alpha404 自宣包已记；OpenBot 替代品营销。X 本窗无其它新增独立可复用仓。

## 2026-10-24 22:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 20:01→22:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24）+ X `search_posts_all`×4 + `get_posts_by_ids`×1（github/playbook/skills/url:github；本窗多为 Vault/模板 dump/功能建议，可复用仓以 GitHub 为主）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| ThreeArisesAll/grok-bot-team-builder | https://github.com/ThreeArisesAll/grok-bot-team-builder | **中文 Skill：把反复大活拆成「一 bot 一事、文件交接、只在决策点等人」的团队并建好跑通第一轮**：`SKILL.md` 七原则+八步（值不值得搭→问方案→人确认→建 bot/共享目录/`HANDOFF.md`→冒烟→交付名单口令）；附 `examples/ai-tools-weekly/` 三人试跑真实产出。与已收 doublesq97-ui/bot-team-playbook（静态提示词包）、meir-bot/executive-team 互补——本仓是**可粘贴 Skill 动态建队**。本轮最值得看 | Multi-bot / Skills | `chinese` `skill` `multi-bot` `handoff` `war-room` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| SnazzyGaz/bot-beacons | https://github.com/SnazzyGaz/bot-beacons | **Windows 桌面悬浮信标：一 bot 一小人偶，有活发光/一键 ping/气泡回复**：bot 侧 `beaconctl.py` + 加密经免费 ntfy 中继；配对码+DPAPI 存钥；不抢焦点、可藏仍排队；给 Bot「set this up」读 SETUP.md 自装。仅 Windows 10/11，.NET Framework 自带编译。桌面「一眼看谁举手」类客户端 | Clients / Desktop | `windows` `desktop` `notify` `webhook` `ntfy` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| jbronssin/echo-dot-grok | https://github.com/jbronssin/echo-dot-grok | **2016 Echo Dot 当 Wi-Fi 听筒打给已有 Grok Bot 语音 agent**：firebreak 解锁→Wi-Fi→本机 Mac 登桌面端 mint+bridge；Unmute 开通话、Mute 打断/挂断。声明走 App 私有 API、仅测 RS03QR/Fire OS 5.5.5.4；含 `AGENTS.md`。硬件向、门槛高，可作语音入口配方 | Hardware / Voice | `echo-dot` `voice` `bridge` `macos` `hardware` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 1nc0gn30/grok-bot-zoth-plugins | https://github.com/1nc0gn30/grok-bot-zoth-plugins | Connect Apps 多插件包：zoth-relay MCP 远程机器 + Zoth Studio skills；MIT 但商业托管（NullAI），需 token，先信号 | Plugins / Marketplace | **GitHub**（10-24 本窗新建） |
| ericyangpan/grokbot-weixin | https://github.com/ericyangpan/grokbot-weixin | 此前 candidates 记 WIP；现已有完整 TS 桥（CF Worker/Node、媒体解密、allowlist、历史），MIT。与已收 grok-bot-wechat / Zhanweelee wechat-clawbot 同向，是否升级短评请 Claude 定；本窗仅信号不重推 | Chinese / Bridges | **X** @ericyangpan + **GitHub**（10-22 建，本窗有人实测帖） |

### Skip（本轮）

george988/kindle-courier（无 License，模板 skill 分发）；xl17773188101-design/fmcat-grok-bot-guide（无 License，个人学习落盘 bot.fmcat.top）；ikeriano/pasapalabra-3d-grok-bot（游戏）；stevenc81/claude-plugins specialists（Claude 插件受 Grok 记忆启发，非 Grok Bot 玩法）；SpaceXAI 1h 课程营销、kelvoroz/Greshamtrade 模板 dump、币安 Wallet、低粉 X Article；@leerob 功能建议。已列 ssamssae telegram / video-mcp / wake-relay / stackchan / broom 等不重推。

## 2026-10-25 00:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 22:07→00:10（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + 晚窗新建）+ X `search_posts_all`×3（github/playbook/skills/中文玩法；本窗多为功能建议、模板 dump、HarnessRouter 旧仓营销，可复用仓以 GitHub 为主）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| rystedtcreative/grokbot-omalauncher-widget | https://github.com/rystedtcreative/grokbot-omalauncher-widget | **Android Omalauncher 主屏挂件：一眼看 Grok Bot 列表+未读点、点开进聊**：setup bot「Omaha」引导装 widget kit→私有 GitHub feed（index.json+头像）→手机只读 deploy key；禁聊天贴 token/密码；含 CI/checksum/SECURITY。本窗最值得看（10-24 早建、此前漏收，本窗仍在更新） | Clients / Mobile | `android` `omalauncher` `widget` `feed` `setup-bot` `mit` | 0 / MIT | **GitHub**（10-24 建，本窗更新；漏收补入） |
| andreolf/grokbot-plugins | https://github.com/andreolf/grokbot-plugins | **second-brain：多 agent 共用 git 备份的 Obsidian vault 记忆**：每 agent 只写 `Agents/<name>/`、显式 path add、rebase+重试；兼容 Grok Bot / Cursor / Claude / Hermes。仓根无 SPDX，插件目录自带 MIT LICENSE，短评须注明 | Multi-bot / Memory | `obsidian` `git` `shared-memory` `plugin` `mit-plugin` | 0 / 插件 MIT（仓根无 License） | **GitHub**（10-24 本窗新建） |
| alexsergivan/kwant | https://github.com/alexsergivan/kwant | **自托管多 bot 一体二进制**（Rust+React）：spaces、@mention 交接、审批卡、routines、多账号额度轮换；对标 Grok Bot / Dots / Cue / Duet。Apache-2.0；今日 X 雷达帖带出，此前漏收 | Self-hosted / Multi-bot | `self-hosted` `multi-bot` `routines` `approvals` `apache-2.0` | ~2 / Apache-2.0 | **X** @Ga_Vasques + **GitHub**（10-22 建，漏收） |
| hnn22/lesgooo-grok-plugin | https://github.com/hnn22/lesgooo-grok-plugin | **好友凑局 Skill+远程 MCP**：空闲窗口比对、地点投票、清单与分账（不转账）；无 API key/OAuth，走 `lesgooo.fun/mcp`；Marketplace 待上架、仓为插件源。垂直社交向 | Skills / Vertical MCP | `skill` `mcp` `group-planning` `plugin` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| serenakeyitan/agent-org-chart | https://github.com/serenakeyitan/agent-org-chart | 可移植组织图目录（工程/市场/支持等），写明兼容 Grok Bot；~35★ MIT；模板 dump 常引用，此前未进 candidates，先信号 | Multi-bot / Templates | **X** dump 帖 + **GitHub**（9-22 建，漏收信号） |
| codarwang/grokbot-web | https://github.com/codarwang/grokbot-web | 非官方双语模板目录站（Astro/CF Pages），强调 tested 非 scraped；无 License、偏脚手架，先信号 | Templates / Directory | **GitHub**（10-24 本窗新建） |
| HappyMonkeyAI/mcp-daw | https://github.com/HappyMonkeyAI/mcp-daw | 通用 MCP 音乐编曲（JSON song→WAV/MP3）；作者称用 Grok Bot 搭出，非 Bot 专属协议，先信号 | Plugins / Media MCP | **X** @HappyMonkeyAI + **GitHub**（10-24 本窗新建，MIT） |

### Skip（本轮）

q98765tw/TodoApi-GrokBot（用 Bot 带练的 Todo demo，非玩法）；george988/kindle-courier（上轮已 skip）；HarnessRouter/harnessrouter（3333★ 旧仓，本窗营销帖非新玩法）；udhaykumarbala/cleanyourtv-app（与已信号 vibeyourtv 同向）；tim164863-hue/grokbot-office / 1nc0gn30 zoth / SnazzyGaz/bot-beacons / ThreeArisesAll team-builder（已列）；SpaceXAI/模板 dump、币安/交易、@leerob 功能建议、低粉 X Article。X 本窗无其它新增独立可复用仓。

## 2026-10-25 02:09 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 00:10→02:09（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + 本窗 16:00Z 后新建）+ X `search_posts_all`×3（github/playbook/skills/中文；本窗多为功能建议、模板 dump、额度吐槽、低粉 X Article，可复用仓以 GitHub 为主）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| lucasjsbarbosa/grokctl | https://github.com/lucasjsbarbosa/grokctl | **非官方 CLI：用 Chrome DevTools Protocol 驱动本机 Grok Bot 桌面端，让 Claude Code/Codex/OpenCode/Maestri 派活给云端 bot**：`bots`/`use`/`ask`/`state`/`read`；只听 `127.0.0.1`；附 Maestri 角色例与 ToS 风险声明。与 webhook 派活（@Bytec99 向）互补——本仓走**本机 UI 自动化**。本轮最值得看 | Bridges / CLI | `cli` `cdp` `claude-code` `multi-agent` `windows` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| dorukardahan/grokbox | https://github.com/dorukardahan/grokbox | **Time Machine 式加密备份 Grok Bot 云电脑**（`/workspace`+`/home/box`→restic+rclone→自有 Google Drive）：调度/守门（空仓回滚、hydration、uptime）、SQLite 在线拷、brain 导出、`AGENTS.md` 可直接丢给 Bot 安装。与已记 StefMVP/exporter、company-notes/grok-bot-backup（一次性导出）互补——本仓是**持续增量加密备份** | Skills / Box ops | `backup` `restic` `rclone` `encrypted` `agents-md` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| xerosph3re/3xposer | https://github.com/xerosph3re/3xposer | **Solana 骗局溯源 Skill**：钱包/mint/X 句柄→资金跳点+威胁分 0–100+证据关联报告（不指控）；`skills/3xposer/SKILL.md`+patterns；可选 X/Helius。垂直链上向，可作 Skill 打包范例 | Skills / Vertical | `skill` `solana` `investigation` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| SherlockGy/grokbot-knowledge-archive | https://github.com/SherlockGy/grokbot-knowledge-archive | 此前空仓；现有 WORKFLOW+主题索引：管家 Bot 按授权持续归档可公开知识（含版本核对）。无 License，个人工作流范例先信号 | Skills / Knowledge | **GitHub**（10-24 建，本窗有实质内容） |
| kielafisher-del/grok-launchpad | https://github.com/kielafisher-del/grok-launchpad | 个人 Grok/Grok Bots 静态 HTML 启动面板；无 License、无自动化，先信号 | Clients / Dashboard | **GitHub**（10-24 本窗新建） |

### Skip（本轮）

86ortega/MPV.CONFIG-Creation-Through-Grok-Bot（用 Bot 调的个人 mpv.conf，非玩法）；nico-lao/Grok-Bot（assets、无 License）；SpaceXAI/Greshamtrade 模板 dump、@moritzkremb webhook 模板营销帖（无新独立仓）、@fluixoo「Just Got Your Phone」交 X 大 V 雷达、@leerob 功能建议/额度吐槽、币安/交易、低粉 X Article。已列 omalauncher / team-builder / bot-beacons / telegram-bridge / video-mcp / hermes-webhook / broom 等不重推。

## 2026-10-25 08:01 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 02:09→08:01（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + topic:grok-bot 更新）+ X `search_posts_all`×5（github/playbook/skills/中文/具名仓；本窗多为模板 dump、额度吐槽、功能建议，可复用仓以 GitHub 为主）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| brefledev/template-rescue | https://github.com/brefledev/template-rescue | **Marketplace 导入后缺 skill 的救援包**：校验创作者 GitHub bundle、从审过截图重建 skill、导出/备份/分享模板；零依赖 CLI（validate/preview/match）+ bot 指令/ROUTINE_POLICY；标明 experimental、不做账号写入。本轮最值得看 | Skills / Templates | `template` `skill-recovery` `export` `backup` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| pawelmical/agent-relay | https://github.com/pawelmical/agent-relay | **Cloudflare Workers 共享 MCP 任务信箱**：Claude（OAuth）↔ Grok Bot（Bearer）互相 `create/claim/complete`；可 webhook 门铃叫醒 Bot；SQLite DO。**勿与**范凯说/robbin 的 git 交接 agent-relay、YC 商业 Agent Relay 混淆——本仓是最小自托管 Workers 实现 | Bridges / Multi-agent | `mcp` `cloudflare` `claude` `mailbox` `webhook` `mit` | 0 / MIT | **GitHub**（10-24 本窗新建） |
| JaxonWright/bot-catalog-for-grok-bot-template | https://github.com/JaxonWright/bot-catalog-for-grok-bot-template | **可复用「自更新 Bot 目录」模板**：分享链接拿到的是拷贝、官方不推更新——目录里每个 bot 带日更 routine，有新 release 才征询升级；Catalog Manager 一键建仓。示例仓 https://github.com/JaxonWright/bot-catalog-for-grok-bot（GPL-3.0，须注明） | Templates / Sharing | `catalog` `self-update` `routine` `template` `gpl-3.0` | 1 / GPL-3.0 | **X** @jxn_w + **GitHub**（模板 10-23；示例 10-24 本窗） |
| Velkrux/grok-team-forge | https://github.com/Velkrux/grok-team-forge | **无 API 的多 agent 团队锻造器**：定角色/交接契约→确定性压力测试「Break My Team」→手工把提示贴进 Grok Chat 再贴回验证据；Evidence Kit 导出。与 team-builder 互补（本仓偏**契约测试**而非动态建队） | Multi-bot / Testing | `multi-bot` `handoff` `stress-test` `bridge` `mit` | 0 / MIT | **X** @Velkrux + **GitHub**（10-24 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| ogarciarevett/orca-bridge | https://github.com/ogarciarevett/orca-bridge | 受限 MCP：外置助手（Grok Bot/Cursor/Claude/Codex）只向 allowlist 的 Orca coordinator 发 typed 请求并读回执；MIT；10-11 建、本窗仍在推，此前漏收 | Bridges / Orca | **GitHub**（漏收补信号） |
| ogarciarevett/engram-reader | https://github.com/ogarciarevett/engram-reader | 只读隐私过滤 Engram 记忆 MCP（六工具、禁写/SQL/shell）；兼容 Grok Bot；同作者、本窗更新，先信号 | Skills / Memory MCP | **GitHub**（漏收补信号） |
| Emuthmartinez/personal-security-checkup | https://github.com/Emuthmartinez/personal-security-checkup | 分国别个人安全体检 Skill + AGENTS.md + 家庭 Security Coach 模板；MIT；10-24 早建此前漏收，垂直向先信号 | Skills / Vertical | **X** + **GitHub**（漏收信号） |

### Skip（本轮）

MyWestLord/crawlbot（memecoin CA）；Robertzu43/building-with-grok-bot（个人 showcase、无 License）；astrodestroyergithub/tamoai-cloud-agents（无 License 托管平台）；MichaelRobotics/whop-apps-gateway-plugin（商业 Whop）；AgentWorkforce 商业 Agent Relay 技能（非本轮 pawelmical 开源仓）；SpaceXAI/Greshamtrade/kinox1out 模板 dump；HarnessRouter 旧仓营销；币安预测/交易；@leerob 功能建议；低粉 X Article。已列 grokctl / grokbox / 3xposer / omalauncher / team-builder / telegram-bridge 等不重推。

## 2026-10-25 10:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 08:01→10:05（Asia/Shanghai；薄则上溯至 ~04:00）`gh search` / `gh api search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + topic 更新）+ X `search_posts_all`×4（github/playbook/skills/中文；本窗多为模板 dump、额度/省钱文、marketplace 分享，可复用仓以 GitHub 为主）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| abhione/grokbot-browser-fleet | https://github.com/abhione/grokbot-browser-fleet | **本机浏览器舰队 + 策略网关**：每 bot 独立带标签 Chrome 配置；Playwright/Patchright 经 unix socket；外发（DM/帖/邮件/购买）须人审；发送上限+30 天去重+DNC；`STOP` 文件一键熔断；Keychain 重登。macOS 优先、Apache-2.0。本轮最值得看 | Skills / Browser ops | `browser` `fleet` `approval` `kill-switch` `macos` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-24 建，本窗漏收） |
| GrokBot-Cursor/box-butler | https://github.com/GrokBot-Cursor/box-butler | **Freebox 家庭服务器管家 Bot 套件**：PROMPT + 12 个 skill（WireGuard/VM/Docker/Plex/Arr 栈/Home Assistant…）；逐步征询、无个人数据进仓；亦附 Cursor rules。垂直 ISP 向，结构可当社区 Bot 配方范例 | Skills / Vertical | `freebox` `homelab` `skills` `french` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |
| hmarquez-solutions/omarchy-grok-bot | https://github.com/hmarquez-solutions/omarchy-grok-bot | **Omarchy 顶栏「Grok Bot 表情」**：休眠/空闲/工作中/未读/等人五态 + 面板列 NEEDS YOU；键盘开设置/重启。与已 skip 的 BlancoKat/omarchy-grokbot-updates（仅菜单更新项）不同——本仓是完整 bar 插件 | Clients / Desktop | `omarchy` `desktop` `status` `mit` | 0 / MIT | **GitHub**（9-14 建，本窗仍推；漏收） |
| marotron/QuotAI | https://github.com/marotron/QuotAI | **macOS 菜单栏额度环**：Cursor Models/Other + Grok Bot 用量%；智能 pace 闪烁/通知；开 Cursor Spending。与已记 yuehzhan/grokbot-usage-checkin（本机仪表盘）互补——本仓是菜单栏即时环 | Tools / Usage | `quota` `menubar` `macos` `cursor` `mit` | 0 / MIT | **GitHub**（漏收；有 v0.11 DMG） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| brefledev/unfinished-botness（原 template-rescue 更名） | https://github.com/brefledev/unfinished-botness | 08:01 已推的 template-rescue **已 301 更名为 unfinished-botness**（同 repo id）；README 扩成完整 import/export/skill-sharing 套件。请 Claude **改链+短评**，勿当新条目重复收录 | Skills / Templates | **GitHub**（本窗 rename+推送） |
| Pushary/grok-bot-plugin | https://github.com/Pushary/grok-bot-plugin | 手机推送「Bot 完成/失败」+ 人审问答（Pushary SaaS）；MIT 插件仓但依赖商业账号，先信号 | Plugins / HITL | **GitHub**（漏收） |
| filmladd-sys/FLAVE | https://github.com/filmladd-sys/FLAVE | @FilmLadd（约 8.9 万粉）开源视频剪辑器源码，交给 Grok Bot 改自用；Attribution No-Sell，非玩法配方，先信号 | Tools / Media | **X** + **GitHub** |
| OpenClaw/imsg | https://github.com/OpenClaw/imsg | Mac Messages CLI（~1.4k★ MIT）；X 上有人教「本机 Grok Bot 只读 iMessage」。通用 agent 工具，先信号 | Skills / Messaging | **X** @twid + **GitHub** |
| BR1K0/grokbot-project | https://github.com/BR1K0/grokbot-project | 黑客松「Simon Says Arena」：四 Bot 红队诱捕/演进/打补丁/裁判；无 License，先信号 | Multi-bot / Safety | **GitHub**（本窗仍推） |

### Skip（本轮）

exa-pub/grokbot-cli（空 README）；freehelpdesk/jetkvm-mcp（空）；AgentWorkforce/skills 商业 Agent Relay；marketplace 模板 dump（Tax Return / Drug Savings / Animation Studio / grokbotshelf）；@sylvieailab「¥67 省钱注册」；Gumroad skill packs；Velkrux/team-forge / template-rescue 旧链已列（仅记更名）；币安/交易。已列 grokctl / grokbox / omalauncher / team-builder / pawelmical agent-relay 等不重推。

## 2026-10-25 10:45 Asia/Shanghai · T7 日更雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。周末窗口约近 24h（Asia/Shanghai 10-24 10:37→10-25 10:45）`gh search` / `gh api search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + topic 更新）+ X `search_posts_all`×4（github.com / playbook·skills / 中文玩法 / multi-bot；本窗 X 侧多为 marketplace 模板 dump、额度/省钱文、功能建议，**可复用仓以 GitHub 为主**）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| chekusu/yobiru | https://github.com/chekusu/yobiru | **跨机 agent 互聊层（Tailscale）**：消息/结构化数据/文件/按策略叫醒；**Friends** 用分享链让别人的 agent 经网关跟你选定的 Bot 聊（含 Grok Bot 安装与恢复说明）。私聊可无中心存；公开 bot 网关可自托管。~307★ MIT。本轮最值得看（此前仅在 X 当产品提过、未进候选表） | Bridges / Multi-bot | `messaging` `tailscale` `multi-agent` `friends` `grok-bot` `mit` | ~307 / MIT | **X** @Hacken2077 引用 @turingou + **GitHub**（漏收补入） |
| jimc1682000/story-compass | https://github.com/jimc1682000/story-compass | **用个人知识地图「边际增益」评估书/漫画/动画/电影/影集**：纯提示词 + Skill + Grok Bot 三角色入口；附 ROLE/评分规范/地图契约与首跑指南；MIT、有 CI。中文垂直 Skill 范例 | Skills / Vertical | `skill` `knowledge-map` `reading` `zh-tw` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |
| yohei1126/grok-bot-ops | https://github.com/yohei1126/grok-bot-ops | **多 bot 运维卫生文档仓**（非可执行 Skill）：共享规则、何时建/退役 bot、房间与文档工人分工、月度审计清单；强调 ops 规则放共享笔记而非 Agent Skills。Apache-2.0 纯文档 playbook | Skills / Ops playbooks | `ops` `multi-bot` `docs` `audit` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-25 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| PhillipHolland/grokbotshelf | https://github.com/PhillipHolland/grokbotshelf | grokbotshelf.com 静态目录源码（bots.json 投稿）；与 X @thecsguy「过 110 bots」同向；**无 License**，先信号（此前 skip 只针对 marketing dump） | Templates / Directory | **X** @thecsguy + **GitHub**（10-25 新建） |
| warpfusion001/boss-man-godmode | https://github.com/warpfusion001/boss-man-godmode | 编码+创意媒体「神级」Grok Bot 胶水包（Astra 环、免费 LLM 路由、FFmpeg）；README 称 MIT 但 SPDX 为 Other，先信号 | Skills / Creative pack | **GitHub**（10-25 新建） |
| LKTechLLC/journal2note-plugin | https://github.com/LKTechLLC/journal2note-plugin | Journal2Note 工时条目 OAuth MCP 连接器 listing（manifest+README）；依赖商业账号，先信号 | Plugins / SaaS | **GitHub**（10-25 新建，MIT） |
| Ladbaby/TresorBot | https://github.com/Ladbaby/TresorBot | 自托管多 agent harness（Sun 仪表盘 + Earth 跑机），对标 Grok Bot/Dots/Muse；README 标明尚未日常可用，先信号 | Self-hosted / Early | **GitHub**（10-20 建，本窗仍推，MIT） |

### Skip（本轮）

mjospark/servicetitan-grok-connector（免费插件+付费托管 MCP）；ofolimensah/cardiology-x-bot（自动发 X）；xudong19951216/ai-dev-workflow-lab（无 License 个人协作实验）；ViolinConcerto/five-nights-with-ai-track4 / BR1K0/grokbot-project（黑客松无 License，BR1K0 已信号）；nico-lao/Grok-Bot、Robertzu43/building-with-grok-bot、astrodestroyergithub/tamoai-cloud-agents、george988/kindle-courier、freehelpdesk/jetkvm-mcp（空/无 License）；marketplace 模板 dump（Tax Return / Drug Savings / Animation Studio / Gumroad skill packs）；@sylvieailab「¥67 省钱注册」；币安/交易；HarnessRouter 旧仓营销。已列 unfinished-botness / grokctl / grokbox / omalauncher / browser-fleet / box-butler / claudia-grokbot / team-builder / pawelmical agent-relay 等不重推。

## 2026-10-25 12:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:45→2026-10-25 12:05（Asia/Shanghai）`gh search` / `gh api search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24 + pushed:>2026-10-25T02:00:00Z）+ X `search_posts_all`×6（github/playbook/skills/中文/multi-bot/具名作者；本窗多为额度省钱文、模板 dump、功能建议、低粉 X Article，**可复用仓以 GitHub 漏收补入为主**）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| wustep/my-bot-scripts | https://github.com/wustep/my-bot-scripts | **Grok Bot 实战脚本箱**：个人↔工作账号加密 bot-portal 中继（AES-GCM+Ed25519+Notion 路由+MCP）、iMessage 唤醒 Texts 路由、msg-graph 消息热力图、usage-tabs、Work 隔离配置克隆；每目录可独立抄，路径可 env 覆盖。~30★ MIT。本轮最值得看（漏收） | Skills / Multi-bot bridges | `scripts` `relay` `imessage` `notion` `e2ee` `mit` | ~30 / MIT | **GitHub**（10-17 建，本窗仍推；漏收） |
| Tritium-Emergence/PangPang | https://github.com/Tritium-Emergence/PangPang | **开源「管 AI 的 Bot」控制面**：你定目标与审批边界，PangPang 管长跑 Work/依赖/失败与验收证据，执行交给既有 Claude Code/Codex/本地模型；强调「Done≠Verified」。Apache-2.0。可作 Self-hosted / Multi-bot 对照 | Self-hosted / Multi-bot | `supervisor` `work-plane` `multi-agent` `apache-2.0` | ~10 / Apache-2.0 | **GitHub**（10-10 建，本窗推；漏收） |
| Yeyue56/cgbarstat | https://github.com/Yeyue56/cgbarstat | **macOS 菜单栏 CM/OM/GB 三表**：读本机 Cursor state.vscdb（含钥匙串解密）拉 Cursor Models/Other + Grok Bot 用量%；有 v0.2.0 arm64 包。与刚记 QuotAI / README 内 GrokGauge·quota-ring 同赛道，实现路径不同，可对照 | Tools / Usage | `quota` `menubar` `macos` `cursor` `mit` | 0 / MIT | **GitHub**（本窗推；漏收） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| tetumemo · Skills 一源多端 MCP | https://x.com/tetumemo/status/2114193990006485112 | ~5.1 万粉：一份 Skills 原本经 MCP 接待，供 ChatGPT/Claude/Grok Bot/dots 调用；Newsletter 向，无独立仓，先 Learning 信号 | Learning / Skills | **X** @tetumemo |
| czzzzzzJ_ · Day1 打通 IM+本地设备 | https://x.com/czzzzzzJ_/status/2114201579587096979 | 中文连载 Day1：微信接成果 + 常驻工作站管家 Bot + 跨设备长任务；X Article，先信号 | Learning / Chinese | **X** @czzzzzzJ_ |
| hugo-hsi-dev/ostack | https://github.com/hugo-hsi-dev/ostack | pstack→Claude Code 技能包 fork；描述写「Grok Bot bridge」但 README 明确**去掉** Slack Grok Bot 管理层。非 Bot 专属玩法，先信号勿当桥收录 | Skills / Claude Code | **GitHub**（本窗推） |

### Skip（本轮）

TheDreamersTop/grok-bot-showroom（用 Bot 做的个人 WebGL 作品展，无 License、非玩法）；s4yonnara「省额度 20 仓」营销帖（通用爬虫/缓存/调度工具堆，非 Grok Bot 配方，且点名未成年人不写公开候选）；its_brill_ Claude→SQLite→webhook 叫醒（口头配方无仓）；AI_Acq Practical Playbook 低粉 X Article；Mulight 烧额度文；Gumroad skill packs；币安/交易；marketplace 模板 dump。已列 yobiru / unfinished-botness / grokctl / grokbox / browser-fleet / QuotAI / omalauncher / team-builder / pawelmical agent-relay 等不重推。

## 2026-10-25 16:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/*、.collab 比对无重复。窗口约 12:05→16:10（Asia/Shanghai；14:04 一轮失败未落盘，本轮补齐）`gh search repos`（grokbot / grok-bot / "Grok Bot" / skill / routine，updated≥11:30）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| kunchenguid/grok-ship | https://github.com/kunchenguid/grok-ship | **把 Grok Bot 变成小型软件工厂的 agent 发行版**：只跟 Firstmate 一个 Bot 聊，scout（调研/诊断，只出报告）vs ship（授权改动）分流，按项目配 crewmate 驱动云端 agent，PR 前对抗式评审，本地 sqlite 待办。README 标明已被官方模板 Firstmate 取代，可作「多 bot 工程团队」设计参考。~195★ MIT。本轮最值得看（漏收） | Multi-bot / Engineering teams | `software-factory` `scout-ship` `review` `crew` `mit` | ~195 / MIT | **GitHub**（8-20 建，本窗仍推） |
| LJMStark/grok-bot-blackbook | https://github.com/LJMStark/grok-bot-blackbook | **《Grok Bot 黑皮书》中文实战书**：从上手、付费到搭有审批边界、控额度的 AI 团队，事实逐条标出处；358 页 PDF，10-25 已同步订阅档位、Pages、Vault、Routine 等新功能。CC BY-NC-SA 4.0（非商用，适合链接不宜搬运） | Learning / Chinese | `book` `zh-cn` `team` `pdf` `cc-by-nc-sa` | 1 / CC BY-NC-SA 4.0 | **GitHub**（10-12 建，本窗更新） |
| dbarrett24/grokbot-texting | https://github.com/dbarrett24/grokbot-texting | **用自己 Android 号码发短信的 Cloudflare Worker 模板**：Bot 复述→你确认→手机发出；私有页管白名单/审批/日志，日志不存正文和完整号码，入站默认关、可选 AES-GCM 加密存储并定期清理。隐私边界写得细。MIT | Bridges / SMS | `sms` `cloudflare-worker` `android` `approval` `mit` | 0 / MIT | **GitHub**（10-17 建，本窗推） |
| thinkingpower-labs/GrokBotChineseFix | https://github.com/thinkingpower-labs/GrokBotChineseFix | **Windows 桌面版中文输入小修**：Grok Bot 在前台时把 `Ctrl+,` 改为输入全角逗号「，」而不弹设置；离线、可暂停、不改原软件，单文件 C# 源码。中文用户痛点小工具 | Tools / Desktop | `windows` `ime` `chinese` `hotkey` `mit` | 1 / MIT | **GitHub**（9-26 建，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| evkiinc/emlbot-plugin | https://github.com/evkiinc/emlbot-plugin | EMLBot 邮件/聊天/任务插件 listing（Grok Bot / Cursor），依赖商业服务、License 为 Other，先信号 | Plugins / SaaS | **GitHub**（10-25 新建） |

### Skip（本轮）

sulalala2000-bot/Grok-bot-backup（个人备份空仓）；j-DavidM/Apps（个人作品集无 License）。其余命中均已在 README/候选/信号中，不重推。

## 2026-10-25 18:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/*、.collab 比对无重复。窗口约 16:10→18:05（Asia/Shanghai），`gh search repos`（grokbot / grok-bot / "Grok Bot" / skill / routine / multi-bot，updated≥15:30）。X 侧由 X 大 V 文章雷达覆盖，本轮仅 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| coletebou/grok-bot-backup | https://github.com/coletebou/grok-bot-backup | **把 Grok Bot 配置备份进 git**：每个 bot、group chat、routine（prompt/trigger/schedule）和自建 skill 导成纯文件，输出确定性（无时间戳、稳定排序），没改动就没 diff，适合 cron 每天跑；不备份记忆/对话/密钥。单文件 Python 3.9+ 无依赖，需 Cursor CLI 登录。**非官方**，走 app 私有接口，升级可能失效、只限自己账号。本轮最值得看 | Tools / Backup | `backup` `routines` `skills` `git` `unofficial` `mit` | 0 / MIT | **GitHub**（10-25 新建） |
| blurryclaire/grok-hermes-webhook | https://github.com/blurryclaire/grok-hermes-webhook | **Grok Bot → 本地 Hermes 派活的最小 webhook 契约**：先验 HMAC-SHA256（原始 body，解析 JSON 前）、拒空 task、返回 202（接收≠完成），仓内零密钥、只写环境变量名；v0.1 只到接收为止。可作「Bot 派活给本机 agent」安全样板 | Bridges / Webhook | `webhook` `hmac` `hermes` `local-agent` `mit` | 1 / MIT | **GitHub**（10-24 建，有 CI） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| PetarKing/hermes-inner-circle | https://github.com/PetarKing/hermes-inner-circle | Hermes Desktop 插件，仿 Grok Bot 的 bot 优先界面（头像花名册、折叠 routine 结果、任务坞）；非 Grok Bot 本体，作 UI 思路参考 | Learning / Inspired-by | **GitHub**（10-24 建，MIT） |

### Skip（本轮）

PiyushAnand2006/EmberLing（自称逆向 Grok Bot 客户端重做，版权/合规风险，不收）；BlastraIO/signatoro-mcp-plugin（商业邮件签名 SaaS 插件）；PandesalPanpan/piko-lantern-fox、ahvren/shield-recs、DevLucyy/grok-bot-dashboard、Yjtda/-Grokbot（个人作品/空仓、无 License）。

## 2026-10-25 22:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 18:05→22:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-24/25 + topic）+ X `search_posts_all`×3（github·playbook·skills / github.com 链 / 中文玩法；本窗多为额度文、模板营销、官方 guides 转发，**可复用仓以 GitHub 为主**）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| mcsuen/x-cli-via-grok | https://github.com/mcsuen/x-cli-via-grok | **用 Grok Bot 做公开 X 研究的 CLI+薄 Skill**：专用「X Research」Bot 复用、请求隔离路由；经非官方 grok-bot-cli 调桌面端（不直接打 X API）；skill 可装到 Codex/Claude Code，脚本自包含无第三方依赖。本轮最值得看 | Skills / X research | `x-research` `cli` `skill` `grok-bot-cli` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |
| zabrodsk/bot2bot-cursor-plugin | https://github.com/zabrodsk/bot2bot-cursor-plugin | **家人/朋友 Bot 互发消息的 Marketplace 插件**：hosted MCP + skill；门铃 routine 叫醒、邀请双边确认、话题白名单问答；明文 quick connect 可切私密端到端加密。消息不当命令执行。Apache-2.0（插件仓；服务为 bot2bot.link） | Bridges / Multi-bot | `bot2bot` `mcp` `marketplace` `doorbell` `e2ee` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-25 本窗新建） |
| EvanChen77/grok-bot-icon | https://github.com/EvanChen77/grok-bot-icon | **把人/角色参考图转成 Grok Bot 风 2D 头像的 Agent Skill**：胶囊黑眼、无口鼻、低头倾斜等硬约束 + 多图歧义/跟进改图示例；可丢进 Codex/Claude skills。纯视觉配方、MIT | Skills / Visual | `icon` `skill` `avatar` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| AabhasA/meetnotes-cursor-plugin | https://github.com/AabhasA/meetnotes-cursor-plugin | MeetNotes 会议纪要 hosted MCP listing（Grok Bot/Cursor）；依赖商业账号，先信号 | Plugins / SaaS | **GitHub**（10-25 新建） |
| ShowDocLive/showdoclive-plugin | https://github.com/ShowDocLive/showdoclive-plugin | 演出 ShowDoc 实况 playbook MCP（172 工具）；需 Pro/Team，先信号 | Plugins / SaaS | **GitHub**（本窗推） |
| fush1ft/hey-grok-android | https://github.com/fush1ft/hey-grok-android | 本机「Hey Grok」唤醒词打开 Grok Bot（openWakeWord）；**无 License**、README 极薄，先信号 | Clients / Android | **GitHub**（10-25 新建） |
| ColdTbrew/light-usage-bar | https://github.com/ColdTbrew/light-usage-bar | 低开销 macOS 额度菜单栏（含 Grok Bot）设计稿；**尚无可执行产物、无 License**，先信号勿与 QuotAI/cgbarstat 混收 | Tools / Usage | **GitHub**（10-25 新建） |

### Skip（本轮）

Chatinker/GrokBot-myskills（个人半调案卷 skill、无 License）；q98765tw/TodoApi-GrokBot（用 Bot 带练的 Todo demo，已 skip）；Simple-With-Us/CodeCaps（额度菜单栏，candidates 已 skip）；ahvren/shield-recs / PandesalPanpan/piko-lantern-fox / EmberLing（已 skip）；galleonlabs/hypergrok-trading-desk（交易台）；Reactively/PressReacher-MCP（商业媒体名单）；kepcup / sugabots / clickaa / amajorai/ryu（替代品/自托管平台，已列模式）；marketplace 模板 dump、额度/省钱文、官方 18 guides 转发。已列 grok-bot-backup / hermes-webhook / unfinished-botness / yobiru / browser-fleet / grok-bot-cli 等不重推。

## 2026-10-26 00:01 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 22:07→2026-10-26 00:01（Asia/Shanghai）`gh search` / `gh api search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-25T12:00Z + Homebot/GrokChan/bridge 具名）+ X `search_posts_all`×4（github 链 / 中文玩法 / Siri·Homebot 具名；本窗 X 侧多为 Siri 对比感想与日文 Shortcuts 教程转述，**可复用仓以 GitHub 为主**）。周末侧重 GitHub。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| lumpinif/Homebot | https://github.com/lumpinif/Homebot | **用 Siri / HomePod 问自己的 Grok Bot**：家用 Mac 常驻 App，点选 Account→Bot→Shortcut→Install，无需终端；多语言短语、对话模式、活动日志；简中安装指南。标注 release candidate（原生 App 尚未真机确认 Siri 应答；旧 TypeScript 版已在 iPhone+中文 HomePod 跑通）。未公证、家用网明文 HTTP 勿端口转发。与已记 siri-grokbot（iOS intents）互补——本仓是 Mac 网关+HomePod。本轮最值得看 | Clients / Voice bridges | `siri` `homepod` `macos` `shortcut` `voice` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建；站点 homebot.fun） |
| runesleo/grok-bot-bridge | https://github.com/runesleo/grok-bot-bridge | **Claude Code/脚本经 webhook 派活给 Bot，一命令收回答复**：setup-prompt 让 Bot 自建 Task Inbox；每任务带 job id + 本地 ledger（超时标 UNKNOWN、Bot 遇重复回 BRIDGE_DUP）；`harvest` 只读桌面端会话副本写成 `results/<id>.md`。单文件 Python 无依赖、中英 README。与同作者已推 multi-ai-sync（结果落盘体检）互补——本仓是派活+回收收据 | Bridges / Agent handoff | `webhook` `claude-code` `job-id` `harvest` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |
| notedit/GrokChan | https://github.com/notedit/GrokChan | **开源 Stack-chan 风语音伴 + Cloudflare Worker 桥**：浏览器/后续 M5Stack ↔ Worker ↔ 已有 Grok Bot webhook（`grokbot-web.inbound.v1`）；多 agent 适配位（muse stub）；中英架构文档。固件/TTS/唤醒词与 phone-use 仍在路线图，可作 Hardware 桥样板；与已记 stackchan-grok-bridge / my-botstack / xiaozhi-hub 同赛道不同实现 | Hardware / Bridges | `stackchan` `m5stack` `cloudflare` `webhook` `voice` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |
| davidneyra2804/mcp-correo | https://github.com/davidneyra2804/mcp-correo | **给 Grok Bot 等 agent 用的 IMAP/SMTP MCP**：HTTPS 443 中转（agent 出不了 993/465）；默认只读；发送/删除两步确认 token（10 分钟一次性）；审计 JSONL 不写正文与凭证。文档为西班牙语，安全边界写得细。MIT | Skills / Email MCP | `mcp` `email` `imap` `smtp` `confirm` `mit` `es` | 0 / MIT | **GitHub**（10-24 建，本窗仍推；漏收） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| otisbase/otis-grok-plugin | https://github.com/otisbase/otis-grok-plugin | Otisbase 开票/计时 hosted MCP + 九个 workflow skill（Grok Bot/Build/Cursor）；依赖商业账号与 EU Cloudflare，先信号 | Plugins / SaaS | **GitHub**（10-25 新建，MIT） |
| greedfi/me-layouts | https://github.com/greedfi/me-layouts | `.me` Grok Bot 的 Stack/Billboard/Magazine/Terminal 画布布局包；**无 License**，先信号 | Templates / Layout | **GitHub**（10-25 本窗新建） |

### Skip（本轮）

BurggraafJ/grok-minecraft（无 License，荷兰语 Minecraft 自建服）；george988/read-and-decide（无 License）；devionjohnson/family-bots-forum（无 License，个人 Q&A）；PiyushAnand2006/EmberLing（逆向客户端，上轮已 skip）；nidao003/homebot（无关空仓）；Chatinker/GrokBot-myskills / hey-grok-android / light-usage-bar（已信号或 skip）；币安/交易、日文 Siri Shortcuts 教程转述（非中英仓）、marketplace 模板 dump。已列 x-cli-via-grok / bot2bot / grok-bot-backup / hermes-webhook / stackchan-grok-bridge / unfinished-botness 等不重推。

## 2026-10-26 02:06 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 00:01→2026-10-26 02:06（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-18/24/25 + topic）+ WebSearch 补漏。深夜/周一凌晨侧重 GitHub；X 本窗轻扫交 X 大 V 雷达。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Jascenn/agent-task-panel | https://github.com/Jascenn/agent-task-panel | **macOS 悬浮面板聚合多 Agent 任务状态**：Codex / Claude Code / Cue / Grok Bot 实时 running·done·idle，菜单栏常驻计数，结束系统通知，点卡片跳回对应 agent；读本机会话文件（含 Grok Bot `sand-client-persistence`），有 DMG release 与中英 README。本轮最值得看 | Tools / Desktop status | `macos` `menubar` `multi-agent` `status` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |
| GlennHasABeard/foreman | https://github.com/GlennHasABeard/foreman | **只读 X 运营小队模板**：Foreman 一键建整队或单装 Follow Audit / Follow Finder / Reply Queue 等 7 个 bot；统一 X OAuth（Read only）、花费台账与日上限，从不发帖/点赞/取关。可抄「只读+人审」护栏与费用估算 | Multi-bot / X ops | `x-api` `read-only` `crew` `spend-cap` `mit` | 0 / MIT | **GitHub**（10-22 建，本窗仍推） |
| dwinter3/grokbot-face | https://github.com/dwinter3/grokbot-face | **Pixel Tablet 全屏胶囊眼桌面伴 + 屏保**：本机摄像头/麦克风反应（帧不落盘）、离线「Hey Grok Bot」唤醒打开官方 App、时钟/小游戏/AI 新闻条；无 Gradle 构建，默认可无 INTERNET。与已 skip 的 mikeg0/grokbot-face 人脸 demo 不同——本仓是完整 tablet launcher | Clients / Hardware | `android` `pixel-tablet` `wake-word` `screensaver` `mit` | 0 / MIT | **GitHub**（10-25 本窗新建） |
| lugovelb/chief-glasses-open | https://github.com/lugovelb/chief-glasses-open | **Meta Ray-Ban Display / 浏览器上看 Bot 回复**：加密 feed，一键 Yes/No/Later；作者标明用 Grok Bot 测过，也可接 Codex/Claude。GitHub Pages 模板自托管，消息 scramble。可穿戴入口样板 | Clients / Wearables | `ray-ban` `glasses` `encrypted` `approval` `mit` | ~3 / MIT | **GitHub**（10-21 建，本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| brandlll-lee/domos | https://github.com/brandlll-lee/domos | 自托管「类 Grok Bot」同伴（Pi/Codex/Claude Code 引擎）；**License pending**，先信号勿当平替收录 | Self-hosted / Early | **GitHub**（本窗仍推） |
| jqlong17/grokbot-agent-loop | https://github.com/jqlong17/grokbot-agent-loop | DeepSeek Harness 可打断 agent-loop 插件，**致敬命名、非 Grok Bot 本体**；MIT，作 Inspired-by 信号 | Learning / Inspired-by | **GitHub**（10-25 本窗新建） |

### Skip（本轮）

wcccheryl/grok-icon-study（无 License，前端动效学习 demo）；danirukun/open-venue-db（黑客松场馆产品，非 Bot 玩法）；ahvren/shield-recs / BurggraafJ/grok-minecraft（无 License，上轮已 skip）；PiyushAnand2006/EmberLing（逆向客户端，已 skip）；Menziess/bot-widget（主对接 OpenBot，已 skip）；exa-pub/grokbot-cli 空 README；marketplace/SaaS dump、币安/交易。已列 Homebot / grok-bot-bridge / GrokChan / mcp-correo / x-cli-via-grok / bot2bot / grok-bot-backup / hermes-webhook / otis / me-layouts / stampede / usage-checkin / root-agent / AgentMindCloud 等不重推。

## 2026-10-26 08:03 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 02:06→2026-10-26 08:03（Asia/Shanghai）`gh search`（"Grok Bot" / grokbot / grok-bot created≥2026-10-25 + topic + Discord/Intel/voice 具名）+ WebSearch 补漏。周一早班侧重 GitHub；X 本窗未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| VaynerAkaWalo/grok-dc-notifier | https://github.com/VaynerAkaWalo/grok-dc-notifier | **Discord Gateway → Grok Bot Routine webhook**：监听 @提及 / DM / 参与中的线程，带用户白名单与限流；Bun+TS，Docker 镜像 `ghcr.io/...`；README 写清让 Bot 建 webhook routine、把同一 Discord bot token 当 secret 回帖。可复用「外站事件→Routine」桥样板。本轮最值得看 | Bridges / Routines | `discord` `webhook` `routine` `docker` `mit` | 0 / MIT | **GitHub**（10-25 深夜本窗新建） |
| StefMVP/omarchy-grokbot-voice | https://github.com/StefMVP/omarchy-grokbot-voice | **Omarchy/Hyprland 热键控制 Grok Bot 语音通话**：不抢键盘焦点；启动需 `--remote-debugging-port=9222`，按键开/挂、pill 静音；`install`/`setup hyprland`/`doctor`。与已记 omarchy-grok-bot 顶栏状态、同作者 exporter 互补——本仓是语音通话快捷键 | Clients / Voice | `omarchy` `hyprland` `voice` `hotkey` `mit` | 0 / MIT | **GitHub**（10-25 深夜本窗新建） |
| kyrollosfarah/grokbot-desktop-intel-mac | https://github.com/kyrollosfarah/grokbot-desktop-intel-mac | **Intel Mac 官方 Grok Bot 安装/更新/验签脚本**：下载官方 x64 DMG、签名与架构检查、失败备份；已在 Sequoia 15.7.7 + 0.75.8 验证。非逆向，只包装官方 Intel 构建；Apple silicon 请走官网 | Clients / Install | `macos` `intel` `installer` `verify` `mit` | 0 / MIT | **GitHub**（10-25 晚本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Play-Omega-Games/great-books-reading-paths | https://github.com/Play-Omega-Games/great-books-reading-paths | 公版名著每日阅读 JSON 计划（15 分钟/天），供 Great Books Reading Paths 模板 Bot 拉取；内容包非工具，先信号 | Templates / Content | **GitHub**（10-25 深夜新建） |
| linkmcp-io/linkmcp-cursor-plugin | https://github.com/linkmcp-io/linkmcp-cursor-plugin | LinkedIn hosted MCP 的 Cursor/Grok Bot Marketplace 配置+7 skills；依赖商业账号，先信号 | Plugins / SaaS | **GitHub**（本窗仍推，MIT） |
| ChrisHKAI/usegrokbot | https://github.com/ChrisHKAI/usegrokbot | usegrokbot.com 开源仓（用例发现站）；**站点已在 README**，此仓作源码对照，勿重复当新目录 | Learning / Directory source | **GitHub**（本窗核验） |

### Skip（本轮）

Gregory-Brunner/GrokBot（空仓无 README）；risebydigital/grokbot-speaker（Pi 语音音箱走 xAI realtime Voice API，badge 标 private licence，非 Grok Bot 玩法主推）；PixnBits/local-grok-bots（自托管同伴、**无 License**）；divyanshu-patil/blooby（胶囊眼 mascot 动画器，非 Bot 集成）；c5auto/c5auto.github.io（Tesla 薄页无 License）；Delibread0601/askaipods（通用播客 skill，非 Grok Bot 专用）；PiyushAnand2006/EmberLing（逆向客户端，已 skip）；ahvren/shield-recs / BurggraafJ/grok-minecraft / greedfi/me-layouts（已信号或 skip）；marketplace SaaS dump、币安/交易。已列 Homebot / agent-task-panel / grok-bot-bridge / GrokChan / grok-bot-backup / hermes-webhook / bot2bot / x-cli-via-grok / stampede / unfinished-botness / StefMVP exporter 等不重推。

## 2026-10-26 10:11 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 08:03→2026-10-26 10:11（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-25/26 + topic + tunnel/computer/skill 具名）。周一白天侧重 GitHub；X 本窗未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| exa-pub/grokbot-tunnel | https://github.com/exa-pub/grokbot-tunnel | **把 Linux 服务器挂成 Grok Bot 的「电脑」**：无桌面也能跑命令/读写文件；`install.sh` + `login --no-browser` + `connect --root`；权限 ask/always/never；持久 shell、后台输出落 `<root>/terminals/`、文件传输上限 100MiB；可选读本机 Codex/Claude skills 名（脱敏）。Go + CI + Release，MIT。与早期空仓 vitalydolgov/grokbot-tunnel **不是同一仓**。本轮最值得看 | Bridges / Headless computer | `tunnel` `linux` `headless` `computer` `go` `mit` | 0 / MIT | **GitHub**（10-25 建，本窗核验；漏收） |
| ELU-Labs/dark-factory | https://github.com/ELU-Labs/dark-factory | **一句话在仓里搭「暗工厂」多 Bot 流水线**：粘贴 `PROMPT.md` 给 Grok Build/Bot——Analyst/Builders/Twin/Verifier/Release 分工写码，**ELU 在机外**当隐藏场景与 PR/发布裁判；停机规则与信任边界写清。MIT。注意依赖 ELU 账号/额度与仓外模型 API，属带 SaaS 闸门的配方 | Multi-bot / Engineering factory | `dark-factory` `multi-bot` `prompt` `elu` `verification` `mit` | 1 / MIT | **GitHub**（10-26 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| jaydudson/gbiz-templates | https://github.com/jaydudson/gbiz-templates | 公开 raw 多 Bot 包：EA 右膀 + Follow-up Desk + Research Assistant（template.yaml + skills + pack-manifest）；**无 License**，先信号 | Templates / Multi-bot pack | **GitHub**（10-25 建，本窗仍推） |
| EmperorHydra/grokbot-pet | https://github.com/EmperorHydra/grokbot-pet | Mac 悬浮黑球桌宠：ntfy 私有 topic 通知弹气泡，可配 `grokbot://` clickUrl；**无 License**、未公证，先信号 | Clients / Desktop pet | **GitHub**（10-25 晚新建） |
| thearnabsaha/lift-receipt（Fortis） | https://github.com/thearnabsaha/lift-receipt | Strong 风格健身 PWA + Streamable HTTP MCP（给 Grok Bot 记组/查 PR）；自托管需 Neon 等；**无 License**，先信号 | Skills / Vertical MCP | **GitHub**（10-25 晚新建） |
| kezaer/internet-quality-map-plugin | https://github.com/kezaer/internet-quality-map-plugin | Agent 插件测执行主机网络质量（含云电脑说明）；skills-only；**无仓库级 License**，先信号 | Skills / Diagnostics | **GitHub**（10-16 建，本窗仍推） |

### Skip（本轮）

RusDawg/LunaBot_Public（月亮竞速 HUD 演示壳，非玩法仓）；santiagogarza/university-of-mars（高教工作坊靶站）；unknownboiz/dexor（多模型聊天替代品，非 Grok Bot）；maya-sesame/sycophancy-mirror（谄媚镜像研究）；frank-otto/runecliff-chess（用 Bot 做的产品）；vitalydolgov/grokbot-tunnel（早期空仓，已 Maybe，勿与 exa-pub 混淆）；risebydigital/grokbot-speaker / Gregory-Brunner/GrokBot / PixnBits/local-grok-bots / EmberLing（上轮已 skip）；marketplace SaaS dump、币安/交易。已列 grok-dc-notifier / omarchy-grokbot-voice / grokbot-desktop-intel-mac / Homebot / agent-task-panel / grok-bot-bridge / GrokChan / unfinished-botness / stampede 等不重推。

## 2026-10-26 10:43 Asia/Shanghai · T7 日更雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约近 24h（~2026-10-25 10:40→10-26 10:43 Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-25 + updated≥2026-10-25）+ X `search_posts_all`×4（EN playbook/github、中文玩法、url:github.com）。工作日 T7：GitHub 新仓 + X 交叉。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| coletebou/drover | https://github.com/coletebou/drover | **多机多 Agent 控制面**：一眼看 Claude Code / Codex / **Grok bots** / OpenClaw fleet manager 谁在等人、谁在干活；Web/TUI/Mac/iPhone/Watch；经 bot gateway（OAuth+MCP）给 Grok Bot 派 Routine webhook、读回复与审批；MCP 让编码 agent 调 `drover_*`。Apache-2.0、有 native/integrations。本轮最值得看 | Multi-bot / Control plane | `fleet` `control-plane` `grok-bots` `mcp` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-23 建，本窗持续推；漏收） |
| Play-Omega-Games/indie-launch-coach | https://github.com/Play-Omega-Games/indie-launch-coach | **Indie Launch Coach 模板的开源发射 playbook**：八阶段 + 任务库/平台门禁官方链 + 店页/媒体包/外联草稿模板 + `build_plan.py`（答案→带日期计划）；Bot 从 raw JSON 拉数据。内容 CC0、脚本 MIT。与同作者 great-books-reading-paths（已信号）同赛道、本仓可复用度更高 | Skills / Vertical playbook | `indie` `launch` `playbook` `steam` `cc0` `mit` | 0 / CC0+MIT | **GitHub**（10-26 本窗新建） |
| stefanvr82/grok-bot-home-assistant-ui | https://github.com/stefanvr82/grok-bot-home-assistant-ui | **墙挂平板胶囊眼 UI**：简单灯光/音乐走本机 Home Assistant；真正问题交给你自己的 Grok Bot（页内无 Grok 客户端/模型）。德英 i18n、CI、公开 demo。灵感自 @Texas_Twins_Dad 帖；与已记 grokbot-face（Pixel Tablet）同「眼睛入口」不同栈 | Clients / Home | `home-assistant` `tablet` `eyes` `mit` | 0 / MIT | **GitHub**（10-26 本窗新建） |
| Caffrey-Li/QuotaPot | https://github.com/Caffrey-Li/QuotaPot | **Cursor 旁常驻小窗看用量**：支持 Cursor / Claude / Codex / DS Bot / WorkBuddy / **Grok Bot**；今日·7·30 天 token、上下文 80% 提醒、磁盘清理两步确认。中文 README，Mac/Win，MIT，~15★ | Tools / Usage | `usage` `desktop` `quota` `zh` `mit` | ~15 / MIT | **X** + **GitHub**（本窗仍推） |
| rthomas24/grok-bot-mcp | https://github.com/rthomas24/grok-bot-mcp | **本机驱动 macOS Grok Bot 桌面端的 MCP**：列 Bot、读聊天、发消息、回答多选题；零依赖、带 Claude Code plugin + Skill。与已收录 cherwinyu/grok-bot-mcp（Windows routine+git diff 验收）**不是同一仓**——本仓是桌面 GUI 操控桥 | Bridges / Desktop MCP | `mcp` `macos` `desktop` `claude-code` `mit` | 0 / MIT | **X** + **GitHub**（10-14 建；本窗重提漏收） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| pickfu/pickfu-mcp-plugin | https://github.com/pickfu/pickfu-mcp-plugin | PickFu hosted MCP + consumer poll skill（Grok Bot/Cursor）；依赖商业账号与积分，先信号 | Plugins / SaaS | **GitHub**（10-25 晚新建，MIT） |
| Grok-Benkei/local-token-saver | https://github.com/Grok-Benkei/local-token-saver | 单文件 Python stdlib+SQLite 输入侧去噪（HTML/diff/CSV…），文档点名 Grok Bot 路径；日文向、宣称削减幅度需核，先信号 | Skills / Cost | **X** + **GitHub**（10-25 新建，MIT） |

### Skip（本轮）

duychung-keytechx/Kbot（空 README/无 License）；risebydigital/grokbot-speaker / Gregory-Brunner/GrokBot / EmberLing / shield-recs / grok-minecraft（已 skip）；qwts/universal-agentic-workflow（通用 SDLC 非 Grok 专向）；BlancoKat/wikiwright（Bot 做的产品非玩法）；smfworks/grok-bot-templates / HarnessRouter / poteto·pstack 转发（已列）；Howard Telegram Stars 市集自推；币安/Polymarket 交易、额度营销、SpaceXAI 摘要 PDF。已列 dark-factory / grokbot-tunnel / grok-dc-notifier / omarchy-grokbot-voice / Homebot / agent-task-panel / grok-bot-bridge / unfinished-botness / boss-man-godmode / grokbotshelf / gbiz-templates / grokbot-pet / lift-receipt 等不重推。

## 2026-10-26 12:08 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:11→12:08（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-26 + updated≥2026-10-26）。周一白天侧重 GitHub；X 本窗未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| situker/situk-mars | https://github.com/situker/situk-mars | **多 Bot 功勋/军衔/人审 Skill**：业务 Bot 交交付证据 → Merit Officer 审 → 人批 → Commander 入账晋升；双语 EN/简中、ZIP release v0.2.0、离线模拟、CI 62 规则测、九模板+SKILL.md。本轮最值得看 | Multi-bot / Skills | `merit` `rank` `hitl` `skill` `zh` `mit` | 0 / MIT | **GitHub**（10-26 本窗新建） |
| Kinfxhk/hermes-grok-bot-bridge | https://github.com/Kinfxhk/hermes-grok-bot-bridge | **Hermes 插件唤醒 Grok Bot 云端跑完回调同聊**：`grok_bot_task`→Routine webhook→Bot 云电脑作业→回调注入 Hermes；关桌面不杀跑、带 bot-skill.md 与测试。与已记 grok-hermes-webhook（Bot→本机接收契约）方向相反、可互补 | Bridges / Hermes | `hermes` `webhook` `callback` `plugin` `mit` | 0 / MIT | **GitHub**（10-26 本窗新建） |
| rystedtcreative/run-cards | https://github.com/rystedtcreative/run-cards | **编码跑开/收卡**：Grok Bot 把长编码交给 Grok Build/Claude Code，开跑贴 open.png、结束贴 close.png（PASSED/FAILED/TIMED OUT/CANCELLED/BLOCKED）；省 Bot 额度、选模型、145 测、零原生依赖 | Tools / Coding runs | `run-card` `grok-build` `claude-code` `cli` `mit` | 0 / MIT | **GitHub**（10-26 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| proposalstudio/event-quote | https://github.com/proposalstudio/event-quote | 报价/价目/发票 hosted MCP + skills（Grok Bot/Cursor）；Free/Pro SaaS，先信号 | Plugins / SaaS | **GitHub**（10-26 本窗新建，MIT） |
| gmggyyds/screenshot-find-original-video | https://github.com/gmggyyds/screenshot-find-original-video | 中文 Grok Bot skill：截图/二创反查 YouTube 原片（画面优先）；**无 License**，先信号 | Skills / Vertical | **GitHub**（10-26 本窗新建） |
| rowama/mmbridge | https://github.com/rowama/mmbridge | Mattermost↔Grok Bot MCP 桥骨架（health/echo，MCP stub）；**无 License**，先信号 | Bridges / Early | **GitHub**（10-26 本窗新建） |

### Skip（本轮）

Mazenss7/grokbot-guide（空 README/无 License）；duychung-keytechx/Kbot（自托管平替、agent stub，Alternatives 已够）；smoothvr/grok-bot-home-assistant-ui（内容同已收 stefanvr82，CI badge 亦指向后者）；RusDawg/LunaBot_Public（月亮竞速 HUD，已 skip）；andraetbusiness-code/grokbot-desk / 5dive / recipes / grokbot-relay（已列）；marketplace SaaS dump、币安/交易。已列 drover / indie-launch-coach / QuotaPot / dark-factory / grokbot-tunnel / Homebot / agent-task-panel / hermes-webhook 等不重推。

## 2026-10-26 14:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 12:08→14:10（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Tkkdy/grok-local-bridge | https://github.com/Tkkdy/grok-local-bridge | **手机上让 Grok Bot 读本机已授权 MCP**：远程 HTTPS MCP 入口 + OAuth（PKCE、动态注册、短期 token），把多个 Windows 本地 stdio/HTTP MCP 组合成带命名空间的单入口；精确工具白名单、每工具限流、DPAPI 存秘密、热增删后端；中英 README + 安全边界/故障诊断文档。v0.1.0-alpha。本轮最值得看 | Bridges / Local MCP | `mcp` `oauth` `windows` `local-bridge` `zh` `mit` | 0 / MIT | **GitHub**（10-26 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| spwilson27/cloud-vm-bot | https://github.com/spwilson27/cloud-vm-bot | OpenAI 兼容端点（/v1/chat/completions），由 Grok Bot 经文件队列异步作答，配 OpenCode `grok-bot` provider；append-only context.md 对齐缓存，思路好；**无 License**、文档含个人部署，先信号 | Bridges / OpenCode | **GitHub**（10-26 本窗新建） |
| vblife/workout-tracker | https://github.com/vblife/workout-tracker | 本地优先健身/营养记录 Grok Bot（stdio MCP + SQLite，可选 USDA）；本窗更新，**无 License**，先信号 | Skills / Vertical | **GitHub**（10-12 建，本窗推） |
| GetFaberCo/faber-cursor-plugin | https://github.com/GetFaberCo/faber-cursor-plugin | Faber 插件：把对话里的流程存成可审阅、可预览、带运行记录的托管任务（Cursor/Grok Bot）；依赖 Faber 账号，SaaS 先信号 | Plugins / SaaS | **GitHub**（MIT，本窗推） |

### Skip（本轮）

cyancity/grok-bot-design-study（已退役清空）；penny323mo/grokbot（个人 nightly 仓、无说明）；kush-coder/autopilot-invisible_dots（"undetectable" 平替，不收）；FibonacciAi/rea-bot（非 Grok 专向）；Mazenss7/grokbot-guide / Kbot（已 skip）。已列 situk-mars / hermes-grok-bot-bridge / run-cards / mmbridge / screenshot-find-original-video 等不重推。

## 2026-10-26 15:59 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 14:10→15:59（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine / grokbot skill / grok bot mcp，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| monkeyteamvip/x-virality-score | https://github.com/monkeyteamvip/x-virality-score | **X 爆款研究台 + 自建 GitHub Pages 看板**：自选关注名单→按浏览量门槛筛原创帖→关键词/趋势雷达→只给 TOP-10 写改写草稿（4-gram 重合>30% 代码拦截）→午前一段话推送；人工发布，不自动发/赞/回。出海做 X 增长可直接抄配置。本轮最值得看 | Routines / X growth | `x` `virality` `routine` `dashboard` `github-pages` `mit` | 19 / MIT | **GitHub**（9-16 建，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| clickfunnels2/cursor-plugin | https://github.com/clickfunnels2/cursor-plugin | ClickFunnels 官方插件：OAuth MCP + skills，Grok Bot Marketplace 同款（漏斗/联系人/订单/自动化）；厂商 SaaS，先信号 | Plugins / SaaS | **GitHub**（MIT，本窗推） |
| quolu/plaude | https://github.com/quolu/plaude | 日文：Plaud 录音→LAN 外部 ASR→模板摘要→邮件，SKILL.md 由 Grok Bot 选模板；强依赖作者私有 LAN/域名，个人部署味重，仅作思路信号 | Skills / Vertical | **GitHub**（MIT，本窗推） |

### Skip（本轮）

其余命中均已列（situk-mars / hermes-grok-bot-bridge / cloud-vm-bot / mmbridge / Kbot / penny323mo 等），不重推。

## 2026-10-26 18:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 15:59→18:05（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine / grok bot skill / grok bot mcp / grokbot plugin，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| MagicLizi/grok-bot-hub | https://github.com/MagicLizi/grok-bot-hub | **macOS 多开 Grok Bot 管家**（中文 README）：用官方 `--user-data-dir` 隔离每个实例、各登不同账号；崩溃退避重启、卡死健康检查、掉线通知、防锁屏；每 30 秒检查云端电脑状态并按界面自动唤醒/重试，菜单栏「全部唤醒」。多 bot 一人公司很实用；**无 License**、10-26 本窗新建，先信号，作者补 License 后可升推荐。本轮最值得看 | Tools / Multi-instance | **GitHub**（10-26 本窗新建） |
| lamxjason/rinston-plugin | https://github.com/lamxjason/rinston-plugin | Rinston AI 电话前台 MCP 插件（美国号码打电话/发短信，Streamable HTTP + bearer key）；MIT，但隐私/条款页仍 404、未上 Marketplace，厂商 SaaS 先信号 | Plugins / SaaS | **GitHub**（MIT，10-26 本窗新建） |

### Skip（本轮）

Autthachakorn/CMe-Grok-Bot（空仓无 README）；Tzonni1972/what-s-on、plato-corp/tiro-cursor-plugin（旧仓本窗推，前者玩具、后者厂商会议笔记插件，暂不推）。其余命中均已列，不重推。

## 2026-10-26 22:16 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 20:11→22:16（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine / grok bot skill / grok bot mcp / grokbot plugin，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| ken-aisec/grokbot-isr-bot | https://github.com/ken-aisec/grokbot-isr-bot | **给 bot 团队配一个只读安全官**：点明所有 Grok Bot 共用一台云电脑（同一套浏览器登录、文件和 CLI 凭据），提供 `vet-template`（装模板/skill/插件前打分给装/改后装/别装）、`isr-bot-audit`（0–100 安全分+前三修复）、周报与绊线；改动须对话里批准。多 bot 一人公司装模板前很值得用。本轮最值得看 | Skills / Security | `security` `audit` `multi-bot` `skills` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-05 建，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| matthew-rutledge-dev/grokbot-vehicle-fleet | https://github.com/matthew-rutledge-dev/grokbot-vehicle-fleet | 社区 MCP 插件+skills：经官方 Fleet API 读特斯拉车况，默认只读、命令需 confirm、不自动唤醒；需自备开发者应用与令牌，小众垂类先信号 | Plugins / Vertical | **GitHub**（MIT，10-24 建） |

### Skip（本轮）

matjazonline/openbot（Rust 自托管多 agent 平台，非 Grok Bot 专向）。其余命中均已列，不重推。

## 2026-10-27 00:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 22:16→00:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine / grok bot skill / grok bot mcp / grokbot plugin，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| davidgeorgehope/grokbot-mixer | https://github.com/davidgeorgehope/grokbot-mixer | **让 Grok Bot 当 DJ 的完整配方**：给曲目清单，自动做 60 分钟以上对拍、按调性排序的 liquid DnB 混音，带确定性护栏、eval 打分器、音频可视化和可选私密 YouTube 上传；`AGENTS.md` 写成 agent 冷启动可照做的流程，不含音频、凭据运行时从密码管理器读。「护栏+评分」的创作型 bot 范例。本轮最值得看 | Playbooks / Creative | `creative` `audio` `eval` `guardrails` `mit` | 0 / MIT | **GitHub**（10-26 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| chekusu/mokutori-agent-plugin | https://github.com/chekusu/mokutori-agent-plugin | Mokutori iPad 扫描页（JPEG+OCR markdown）端到端加密直送 Grok Bot / Codex / Claude Code 的 `mokutori inbox`，扫码配对；MIT 但依赖厂商 App 与中转网关，先信号 | Plugins / SaaS | **GitHub**（MIT，10-26 本窗新建） |
| eliautobot/my-virtual-world | https://github.com/eliautobot/my-virtual-world | 自托管 3D 城市，可接入 Grok Bot 等 agent 当「居民」（有 PC、任务板、日历、浏览器）；83★ 但 PolyForm Noncommercial 且需 License Key，偏玩具/商业产品，仅作多 agent 可视化信号 | Tools / Multi-agent | **GitHub**（Noncommercial，本窗推） |

### Skip（本轮）

crumble-project/bot（通用自托管 agent 服务器，非 Grok Bot 专向）。其余命中均已列，不重推。

## 2026-10-27 02:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 00:07→02:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine / grok bot skill / grok bot mcp / grokbot plugin，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| GetJobber/grok-bot-mcp | https://github.com/GetJobber/grok-bot-mcp | **SaaS 厂商官方给 Grok Bot 出插件的样板**：Jobber（上门服务/外勤排班 SaaS）把自家托管 MCP 打包成 Cursor 与 Grok Bot 插件，OAuth 由平台托管、`.cursor-plugin/plugin.json` + `mcp.json` 结构清晰，可作「把自家 SaaS 接进 Grok Bot」的参照。仓无 license，按厂商官方链接收。本轮最值得看 | Plugins / SaaS | `mcp` `plugin` `oauth` `official` | 0 / 无 | **GitHub**（厂商官方，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| tangsj-hub/Storm-Dock | https://github.com/tangsj-hub/Storm-Dock | 中文桌面工具：本机集中管理 Cursor、ChatGPT、Grok Build、WorkBuddy、Grok Bot 多账号，一键切换、看额度、管模版；16★ MIT、本地 SQLite。涉及导入登录凭证，收录前需 Claude 核安全说明，先信号 | Tools / Desktop | **GitHub**（MIT，本窗推） |

### Skip（本轮）

noid-one/noid-bot（Grok Bot 开源替代品，非玩法）；masonleenaugh/trying-something-new（个人试验仓，不点名）。其余命中均已列，不重推。

## 2026-10-27 08:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 02:07→08:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine / grok bot skill / grok bot mcp / grokbot plugin / grok bot agents，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| RealDragonJT/grok-discord-bridge | https://github.com/RealDragonJT/grok-discord-bridge | **用 routine webhook 把 Discord 接进 Grok Bot**：自带 Discord bot，有人 DM / @ 时把事件 POST 到 Grok Bot routine 的 webhook 唤醒 agent，带 owner 白名单控制、无中间托管服务；附 `AGENT-SETUP.md` 让 agent 自己部署。补齐「没有原生 Discord 监听」的现成配方。本轮最值得看 | Routines / Triggers | `routine` `webhook` `discord` `bridge` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |
| eugeniughelbur/obsidian-second-brain | https://github.com/eugeniughelbur/obsidian-second-brain | 4.9k★ 的 Obsidian 第二大脑仓新增 **Crew**：Claude Code、Codex、Cursor、Grok Bot 共写一本纯文本工作日志，新会话能直接看到别的 agent 做了什么；不依赖 Obsidian 也能用。与本仓「git + .collab 跨 agent 交接」思路同类，可作多 agent 协作参照 | Multi-agent / Memory | `multi-agent` `memory` `obsidian` `handoff` `mit` | 4955 / MIT | **GitHub**（本窗更新） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| niharnm/grok-bridge | https://github.com/niharnm/grok-bridge | Grok Bot 与 Codex / Claude Code / Cursor / Antigravity 之间的任务交接 CLI + skills 包；作者自标 experimental alpha，3★，先信号 | Multi-agent / Handoff | **GitHub**（MIT，本窗推） |
| Gamedesigner/grokdeck | https://github.com/Gamedesigner/grokdeck | 第三方 Mac/Windows/iPhone 客户端，读本机 Grok Bot 缓存在手机上看 agent 与对话；局域网配对、不输密码，但读本地会话缓存，收录前需核安全 | Tools / Desktop | **GitHub**（MIT，本窗推） |
| siddhit/grokbot-deck-builder | https://github.com/siddhit/grokbot-deck-builder | 离线 HTML 幻灯片生成器，设计成由 Grok Bot 访谈演讲者后改 `deck.json`；小工具，先信号 | Playbooks / Content | **GitHub**（MIT，10-27 本窗新建） |

### Skip（本轮）

SentiSenseApp/cursor-plugin、asyncmastercoder/robin-baby-cursor-plugin（厂商单一产品插件，暂不铺）；chadwittman/eldrick-grok-bot（xAI 远程 MCP 示例，非 Grok Bot 玩法）；kruschdev/krusch-companion（替代品）；blavid/eaglewood-roku、ikeriano/ahoracaigo-grok-bot（个人仓，不点名）。

## 2026-10-27 10:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 08:07→10:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot routine / skill / mcp / plugin / agents / webhook，updated≥本窗）。本轮仅 GitHub，X 未调用。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| mpotter2002/hermes-grok-bridge | https://github.com/mpotter2002/hermes-grok-bridge | **把 Grok Bot 聊天变成另一个 agent 的窗口**：小型 stdio MCP，把 Grok 对话转进 Hermes Agent 的 Bot Chat、原样回传；别的 Grok bot 也能当队友给它发消息，Hermes 反向通过 routine webhook 主动找 Grok。密钥要求走 secret request、不贴进聊天。跨 agent 双向接入的现成配方。无 license，按链接收。本轮最值得看 | Multi-agent / Bridges | `mcp` `webhook` `multi-agent` `bridge` | 0 / 无 | **GitHub**（10-27 本窗新建） |

### Skip（本轮）

matthew-rutledge-dev/grokbuild-grokbots 及同作者 5 个 placeholder 仓（仅 README 标题/占位，主仓不存在）；abtx2323/grok-bot-team-canvas（只有一句描述，无内容）；bitlink0521/qtou-plugin（单一厂商插件，暂不铺）；FouzanAbdullah/GrokBot-Hackathon、jblack4vols/grok-bot、shinarugrok-a11y/Beowulf-Standup（个人仓，不点名）。

## 2026-10-27 10:36 Asia/Shanghai · T7 日更雷达

> 窗口约近 24h。GitHub `gh search`（grokbot / grok-bot / "Grok Bot" / routine / skill / mcp / playbook / template / agents，updated≥10-26）与 X 公开搜索；按 full_name / status id 与 README、docs/*.md、inbox、.collab 去重。未改 README。

### 玩法 / 信号（待 Claude 核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 每周让首席 Bot 对照新功能体检 routine | https://x.com/Michael_Fenech_/status/2114661816873734316 | 跑得好的 routine 也可能在做多余的事：给 Chief of Staff 一段每周提示词，查哪些新功能能替掉 workaround、手动步骤或让 routine 更稳；约 450 赞 / 近 1k 收藏。提示词正文在配图里，收录前需核图中文字；与同作者「CoS 额度效率审查」互补 | Routines / Maintenance | **X**（10-26） |

### Skip（本轮）

gavasques/my-dexter-bot（Grok Bot 替代品试验）；matthew-rutledge-dev/grokbot-switchboard（placeholder）；ExpeditedProjects/hutchdb、acosmi/OpenMyBot（通用 agent 工具，非 Grok Bot 玩法）；@OutworkVentures 用量排行模板（回复区刷屏推广，且与已收用量 CSV 条目重复）；@fabioricotta 用量 CSV（与 @tejas3732 已收重复）；@ducksays CMO（此前已拒：无配置）。

## 2026-10-27 12:03 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:07→12:03（Asia/Shanghai）`gh api search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-27 + pushed≥本窗）+ X `search_posts_all`×5（github 链 / playbook·skill·routine / 中文）+ WebSearch。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| ChatCut-Inc/agent-plugin | https://github.com/ChatCut-Inc/agent-plugin | **给 Grok Bot 的官方视频剪辑 MCP 插件包**：`grok/` 目录含 `.cursor-plugin` + skills，经托管 MCP 导入素材、改时间线、字幕/动效、导出；OAuth 不落仓密钥；同仓还覆盖 Codex/Claude/Cursor/Kimi。~982★，此前漏收。依赖 ChatCut 账号与额度。本轮最值得看 | Plugins / Creative MCP | `mcp` `video` `plugin` `oauth` `marketplace` | ~982 / grok 包内有 LICENSE | **GitHub**（漏收；本窗核验） |
| seanmartin91/privilio-mcp | https://github.com/seanmartin91/privilio-mcp | **本机只读 MCP，把端到端加密通讯录解给 Grok Bot**：`search_contacts` / `get_contact` 等四工具全标 read-only；口令只在本地派生、Vault 联系人排除、标签白名单与字段脱敏；带 SECURITY.md 与测试。需 Privilio 账号。本窗新建 | Skills / Privacy MCP | `mcp` `contacts` `e2ee` `read-only` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| fazedordecodigo/upbot | https://github.com/fazedordecodigo/upbot | 本机优先 macOS 多 bot 工作台（Tauri）：审批/例程/邮箱/MCP/共享工作区，对标 Grok Bot；MIT、有 Release。作者今日 X 自荐。属开源平替，先信号 | Self-hosted / Alternatives | **X** + **GitHub** |
| spacyapps/ground-control | https://github.com/spacyapps/ground-control | macOS 任务控制台：一眼看 Claude Code / Grok CLI / Codex 等会话谁在等人，一点跳到对应终端；topic 含 grok-bot。AGPL，先信号 | Tools / Session monitor | **GitHub**（本窗推） |
| patrick-mns/localbot | https://github.com/patrick-mns/localbot | 本机 Grok Bot 风格队友：Docker Linux 桌面或 Lume macOS VM + Cua Driver；MIT、有 dmg。平替向，先信号 | Self-hosted / Alternatives | **GitHub**（本窗推） |
| tranthor-main/cursor-plugin | https://github.com/tranthor-main/cursor-plugin | Tranthor 官方 Cursor/Grok Bot 插件（hosted MCP + skills）；本窗新建，根仓无 License、依赖厂商账号，SaaS 先信号 | Plugins / SaaS | **GitHub**（10-27 本窗新建） |

### Skip（本轮）

homechameleon/holly-for-home-assistant（仅 LICENSE+一行 README 空壳）；1806629231-del/mozzy-image-skills（无 License、薄仓）；jellydn/awesome-bot（替代品调研笔记、无 License）；TosakaXie0215/codex-grok-pet（给 Codex 的桌宠，非 Grok Bot 玩法）；helloworldxdwastaken/GrokBot-deconstructed-0.77.0（逆向研究，合规跳过）；matthew-rutledge-dev 系列 placeholder（上轮已 skip）；bitlink0521/qtou-plugin（单一厂商插件，上轮已 skip）；AgentTransmit/TermiX/Gumroad 付费模板营销、额度文。已列 hermes-grok-bridge / grok-discord-bridge / mmbridge / Storm-Dock / GetJobber 等不重推。

## 2026-10-27 14:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 12:03→14:07（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥2026-10-27）+ X `search_posts_all`×3（playbook·skill·routine / github 链 / 中文）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| dkapo88/grokbot-t3-orchestration | https://github.com/dkapo88/grokbot-t3-orchestration | **让 Grok Bot 当 PM，在 T3 Code 里排开发活**：skills（orchestration / setup / pm-sweep）+ scripts（launch/steer/status/archive）+ brief 模板 + webhook/routine 监控；`config.json` 管模型路由、合并策略与成本上限；密钥走 secrets 文件不进聊天。跨 agent 编排配方完整。本轮最值得看 | Multi-bot / Orchestration | `t3` `skill` `routine` `webhook` `pm` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |
| initcatcher/grokbot-mcp | https://github.com/initcatcher/grokbot-mcp | **本机 MCP：让 Claude Code 等客户端按名字给 Grok Bot 发消息并收回复**：经 Cursor BDK（`bdk serve` + `cursor-grokbot-agents`），macOS/Windows；Bearer 令牌本地生成，bot 名写进 `.env.local`。补齐「本机助手 ↔ 云端 Grok Bot」双向的另一半（对照 hermes-grok-bridge / wingman） | Skills / Bridges | `mcp` `bdk` `claude-code` `bridge` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| BBridgeers/grok-code-audit-bots | https://github.com/BBridgeers/grok-code-audit-bots | 六角色工程审计小队（audit / ui-check / api-guard / sec-check / regress / synth），只出 PASS/BLOCK/HOLD、不改代码不合并；每 bot 有 SETUP.md。无 License，先信号 | Multi-bot / Review squad | **GitHub**（10-27 本窗新建） |

### Skip（本轮）

renjanmenon/*（Parasoft/CargoTracker/JPetStore 迁移 POC，非玩法）；matthew-rutledge-dev / qtou / tranthor / holly / mozzy / jellydn / deconstructed 等上轮已 skip；@0xCocadada 团队备份 skill 链到 x.ai/bot 分享页非 GitHub；@xiaomovps/@tele97965/@neili666888 资源站/可导入 Bot 清单无新仓；@SamAiPr 试用到期邮件 tip（步骤过薄）；TermiX/Gumroad 营销；boundsj/t3-fleet-gateway（MIT·6★，10-08 旧仓本窗未更新，漏收可下轮再核，不塞本窗）。

## 2026-10-27 16:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 14:07→16:07（Asia/Shanghai）`gh search`/`gh api`（grokbot / grok-bot / "Grok Bot" created≥2026-10-27 + pushed≥06:00Z）+ X `search_posts_all`×3（playbook·skill·routine / url:github.com / 中文）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议 README 节 | 标签 | Stars / License | 来源 |
|------|------|------|----------------|------|-----------------|------|
| tcballard/grokbot-physical | https://github.com/tcballard/grokbot-physical | **台面语音球接 Grok Bot**：本机唤醒词「Hey Grok Bot」→ xAI Realtime 语音 → 工具调用 POST 到 bot routine webhook；bot 做完再回调 `/speak` 播报；含 Rust 固件、3D 打印外壳、Pi Zero 2 W / ReSpeaker BOM、systemd、无硬件也可 `--dry-run --simulate-wake` 测全环。本轮最值得看 | Hardware / Voice routines | `hardware` `voice` `webhook` `routine` `raspberry-pi` `mit` | 2 / MIT | **GitHub**（10-25 建，本窗推）+ **X** @tcballard |
| SiegoZhang/agent-hub | https://github.com/SiegoZhang/agent-hub | **本机多 app 会话看板**：一眼看 Codex / Claude Code / Grok Bot 谁在等人、谁刚做完；点卡片用 `grokbot://` 等 deep link 跳回对话；只读本机数据、零依赖 Python+HTML、中英双语。与已收 ground-control（终端会话）互补 | Tools / Session monitor | `dashboard` `macos` `multi-agent` `local` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| xiongyecpu/thinking-models-skill | https://github.com/xiongyecpu/thinking-models-skill | 中文思维模型 Skill 包（156 模型+61 场景索引）：`SKILL.md` + yaml 可丢 Cursor/Grok Bot skills 目录；细文外链 51as.com，先信号 | Skills / Chinese | **GitHub**（10-27 本窗新建，MIT） |
| gapermossel/agent-orchestration | https://github.com/gapermossel/agent-orchestration | 多 bot 层级作战室案例（COS+专桌+skills/routines/审批门）+ PDF 案例与 snippets；**无 License**，先信号 | Multi-bot / War room | **GitHub**（本窗推） |
| Webhook 唤醒 CI 失败分析 routine | https://x.com/cnlsy517/status/2114983432795140408 | 中文保姆级：一个 POST 唤醒 Grok Bot webhook/routine，读 job/summary 整理现象·原因；配图步骤，无独立仓，Learning/Routines 短链候选 | Routines / Triggers | **X**（10-27，低粉刚发） |

### Skip（本轮）

andraetbusiness-code/grokbot-desk（memecoin 看板）；Kshot3000/Midnight-GrokBot-Agent（Cardano/ZK 实验室，非 Grok Bot 玩法）；JiachengWu-5/astrbot_plugin_dafeiyu_qzone（AstrBot QQ 空间插件）；Kinfxhk/perpdrill（合约练习工具，用 Grok 写的，非玩法）；brandlll-lee/domos / milind-soni/OpenMausBot（已列）；BBridgeers/dkapo88/initcatcher/privilio/ChatCut 等上轮已收；matthew-rutledge-dev placeholder；Spam-killer / 额度营销 / 平替刷屏帖。

## 2026-10-27 18:09 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 16:07→18:09（Asia/Shanghai）`gh search`/`gh api`（grokbot / grok-bot / "Grok Bot" created≥2026-10-27 + pushed≥08:00Z）+ X `search_posts_all`×3（playbook·skill·routine / url:github.com / 中文）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| AdventureNLearn/build-bridge | https://github.com/AdventureNLearn/build-bridge | **本机签名任务桥：Grok Bot → Grok Build**：Bot 写作业并用本机密钥签名，Windows 监视器验签后才跑 Build；回执落本地、仅 webhook 唤醒 Bot（载荷不含作业正文/路径/密钥）；ZIP 指纹校验、逐步 YES、可 rollback。本轮最值得看。**无 License**，按链接收；安全边界需核 DISCLOSURE | Bridges / Grok Build | `bridge` `grok-build` `webhook` `signed-jobs` `windows` | 0 / 无 | **GitHub**（10-26 建，本窗持续推） |
| Markcial/bots | https://github.com/Markcial/bots | **可版本化的 Grok Bot 模板源仓**：`catalog.json` + `_template` + 两套 prepare 级配方（Workforce Router / Learning Machine），含 profile/skills/memories/routines/getting-started；约定 sketch→launch 与 `grokbot://` 分享链。协调 Bot 可读 catalog 推荐模板 | Templates / Multi-bot | `template` `catalog` `skill` `routine` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |
| sleeplesshan/grokbot-city | https://github.com/sleeplesshan/grokbot-city | **本机优先的多 Bot 作战看板**：任务流转 + 持久 LLM wiki + CLI/协议文档（GROKBOT_*）；Bot 经 CLI 更新档案/状态/知识，看板不直连模型；韩英双语、SSE、loopback-only。补齐「任务台 + 知识库」一体配方 | Multi-bot / Ops dashboard | `dashboard` `wiki` `cli` `multi-bot` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |
| evilmordy/cn-mail-mcp | https://github.com/evilmordy/cn-mail-mcp | **国内邮箱 IMAP MCP（QQ/163/126/腾讯企业邮）**：默认只读；授权码走 `.env`/系统密钥框不进聊天；带 `skills/mail-imap`。官方连接器只有 Gmail/Outlook——补中国邮箱缺口。注明云电脑出站可能扫不到 IMAP，宜本机跑 | Skills / Mail MCP | `mcp` `imap` `qq` `163` `zh` `mit` | 0 / MIT | **GitHub**（9 月建，本窗推；漏收） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| jeevan-vj/bot-town | https://github.com/jeevan-vj/bot-town | 交互卡通地图展示自己的 Grok Bot 小队；仅 `index.html`、**无 License**、无 README，先信号 | Clients / Visualization | **GitHub**（10-27 本窗新建） |
| X 书签→Sheet+Drive 夜更 archive | https://x.com/KamilStanuch/status/2115002175277445222 | 英文可复制提示词：书签进可搜索 Google Sheet（AI 标签）+ 图片备份 Drive，每晚 23:00 自更新；约 4.1k 粉 / 11 赞 / 16 收藏。与已收 xshelf（中文静态站）互补 | Routines / X bookmarks | **X**（10-27） |
| Grok Bot 更新提醒 Bot 模板 | https://x.com/keyiLeYi/status/2115022960897790101 | 中文：监控 changelog/RSS，有更新再私聊；帖内可复制名称+描述给 Bot 建 routine。无独立仓，Learning/Routines 短链候选 | Routines / Changelog | **X**（10-27，低粉刚发） |

### Skip（本轮）

tcballard/omarchy-plugin-grokbot-desktop（Omarchy 通用 starter，非玩法）；Chilli5000/grokbot-usage（仅个人 usage.json）；itsaslamopenclawdata/grokclaudcodetest（hello.txt 空测）；defrag-au/grokbot-experiments（作者实验仓，不点名）；muhib90/open-duet（Anil-matcha/open-duet 平替镜像，Alternatives 已够）；sergebulaev/x-skills（Claude/Codex 向，非 Grok）；Spam-Call Scrubber / Bird 插件营销；matthew / qtou / tranthor / holly / mozzy / deconstructed 等上轮已 skip；已列 physical / agent-hub / t3-orchestration / grokbot-mcp / discord-bridge 等不重推。

## 2026-10-27 20:13 Asia/Shanghai · 白天玩法雷达

> 按 full_name 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 18:09→20:13（Asia/Shanghai）`gh search`（grokbot created≥10-27 / "grok bot" updated≥10:00Z / grok-bot created≥10-26）+ X `search_posts_all`×1（Grok Bot + github/routine/skill/playbook）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| w-yyh/grok-relay | https://github.com/w-yyh/grok-relay | **Grok Bot ↔ Codex Desktop 双向显式消息中继**：给现有 bot 和 Codex 线程分配本地地址/别名，JSON CLI 发消息，回复落回各自原对话，上下文不丢、两边都能看到往来；不自动转发、不替你审批。含 Agent guide / Setup / 中文 README / CI。本轮最值得看。注意：Windows-only public alpha，桌面适配用了非官方稳定接口，需核 COMPATIBILITY | Bridges / Cross-agent | `bridge` `codex` `relay` `windows` `zh` `mit` | 0 / MIT | **GitHub**（10-27 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| m1kewong/rabbit-r1-grokbot | https://github.com/m1kewong/rabbit-r1-grokbot | Rabbit R1 小屏 Creation Web App + WebSocket 网关接 Grok Bot；仅一句 README、**无 License**，先信号，与已收 physical / GrokChan 硬件线互补 | Hardware / Clients | **GitHub**（10-27 本窗新建） |

### Skip（本轮）

hawkeg/grok-bot-showcase（阿拉伯语个人视频展示页）；FouzanAbdullah/GrokBot-Hackathon / penny323mo/grokbot（已见，个人仓）；X 本窗多为功能清单 / 收益营销 / 18 篇官方课转述 / Shelf 日报（已见），无新可复用配方；已列 build-bridge / Markcial / grokbot-city / grokbot-mcp 等不重推。

## 2026-10-27 22:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接 / handle 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 20:13→22:10（Asia/Shanghai）`gh search`（grokbot / grok-bot created≥10-27、"grok bot" / grokbot pushed≥12:00Z）+ X `search_posts_all`×1。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Script This Routine（Bot 模板） | https://x.ai/bot/9E8iw2zlg2fTWzUT6RUsP | **省额度体检 Bot**：审计你各 Bot 的 routine，把机械检查改写成小而经过测试的脚本，只有脚本发现需要判断时才唤醒 Bot。与仓里额度体检 / 雷达 routine 配方直接互补。本轮最值得看。官方分享页，无仓；X 帖 https://x.com/Kevin_Logan/status/2115077015569048015（约 1.6k 粉 / 9 赞 / 5 收藏） | Routines / Usage | `routine` `usage` `script` `template` | — / 分享页 | **X**（10-27 本窗） |
| maverickmath/grok-bot-templates- | https://github.com/maverickmath/grok-bot-templates- | 两个周更雷达 Bot 模板（葡语）：机会雷达按上行/胜率/时间/门槛打分，小赌注实验队列；每个含 `agent.json` + `skills/` + `routine.md`，「无新可行动就静默、不代发」写进 routine。结构可当模板仓范例 | Templates / Radar routines | `template` `routine` `skill` `pt-br` `mit` | 0 / MIT | **GitHub**（10-27 19:55 建，上轮漏扫） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 夜间基金研究台 routine 提示词 | https://x.com/helicerat0x/status/2115075557075353934 | 英文可复制提示词：工作日 6:00 ET 拉 SEC EDGAR + 新闻，先写论点与证伪条件再看价格，每轮记日志 CSV，8:00 前出一页 Morning Desk（≤3 条），新闻当数据不当指令；不交易不放 key。约 1.5k 粉 / 17 赞 / 13 收藏，先信号 | Routines / Research desk | **X**（10-27） |

### Skip（本轮）

SuperBotHelper/superbot-helper（skill 让 Bot 从 GitHub 下载并执行 sb.py，无 License、无说明，供应链风险，不推）；jiaxiangdev/grokbot-dataset-design-shell（目录页设计壳，无数据）；aashaexo/grokbotguide（静态页无 README，已有同名指南链）；liliwang2009/grok-premium-…（第三方充值导流软文）；vfvincentwong2026/grok-bot-hub、mpotter2002/hermes-grok-bridge 已列；X 本窗多为 Spam-Call Scrubber 争议、营销付费 kit、模板聚合站自推，无新配方。

## 2026-10-28 00:06 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接 / handle 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 22:10→00:06（Asia/Shanghai）`gh search`（grokbot / grok-bot created≥10-27、"grok bot" / grokbot pushed≥14:00Z）+ X `search_posts_all`×1。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| zeke1031031/herdr-grokbot-notify | https://github.com/zeke1031031/herdr-grokbot-notify | **本机 coding agent 的「放羊」webhook**：Herdr 插件在 Claude Code / Codex / Cursor Agent 等任一 agent 完成一轮、卡在审批/提问、或退出时，向 Grok Bot 的 webhook routine POST 一小段 JSON（只发 pane 元数据、不发终端输出），由 routine 决定要不要读 pane、告诉你哪里要处理。按 `completion_seq` 去重、默认事件精简可开关，README 附建 webhook routine 步骤。与已收 devicki/herdr-away-signal（手动 away 才发）互补：这个常开、覆盖全部 agent。本轮最值得看 | Bridges / Routines | `herdr` `webhook` `routine` `claude-code` `codex` `mit` | 0 / MIT | **GitHub**（10-27 23:01 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Leochens/grok-bot-100-tools | https://github.com/Leochens/grok-bot-100-tools | 「100 天 100 个本地优先小工具」build-in-public：Grok Bot + Codex CLI 从 X / Reddit 真实痛点选题，每个工具页带来源帖与需求分析笔记；Day 001 字幕 CPS 修复器已可跑。无 License，先信号 | Showcase / Build in public | **GitHub**（10-27 本窗新建） |
| ponelat/grok-bot-nix | https://github.com/ponelat/grok-bot-nix | 又一个非官方 Nix 打包（AppImage 钉 hash + 「每次启动拉最新」两种），支持非 flake 的 configuration.nix；与已列 d-513/grok-bot-nix、aijorgenson/grokbot-nixos 同类，择一收或合并为一条 | Setup / Linux | **GitHub**（10-27 本窗新建） |
| Zujiin01/mobile-server-connection | https://github.com/Zujiin01/mobile-server-connection | 「The Door」：小型 HTTPS API 让 Grok Bot 从手机操作你自己的服务器（读写、跑命令），三部曲第 1 部；README 自带风险警告（提示注入、密钥被盗＝同权）。PolyForm 非商用许可 + 权限面大，只当信号 | Bridges / Remote ops | **GitHub**（10-27 本窗新建） |

### Skip（本轮）

JiachengWu-5/astrbot_plugin_dafeiyu_deskpet（AstrBot QQ 桌宠插件，与 Grok Bot 玩法无关）；renjanmenon/*-services（迁移 POC 代码本体）；matthew-rutledge-dev 五个 Placeholder 仓；liliwang2009 充值导流已拒；X 本窗多为 Spam 号清理转述、币安 Agent 钱包/打新、收益营销、模板自推；@kyzoroX「别按时钟唤醒、先用页面监控再触发」思路与 Script This Routine 同线，原链为短链未展开，不单列。

## 2026-10-28 02:02 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接 / handle 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 00:06→02:02（Asia/Shanghai）`gh search`（grokbot / grok-bot created≥10-27、"grok bot" updated≥16:00Z）+ X `search_posts_all`×1。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| smdistefano/grok-bot | https://github.com/smdistefano/grok-bot | **一天烧掉一周额度后的复盘一页纸**：拆解 token 花在哪（上下文税、子代理扇出、轮询/重试循环、技能与大文件塞上下文、非你触发的唤醒），给出常驻规则（只做被问的事、≤5 次工具调用先问、不轮询不开子代理、routine 默认暂停、设按需上限、大日子后查用量）与贵/便宜提问对照。与仓里额度体检配方、Script This Routine 同线，可作「省额度」节的英文参考。本轮最值得看 | Usage / Token efficiency | `usage` `token` `routine` `rules` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-28 00:25 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| novantir/kungfukit-publico | https://github.com/novantir/kungfukit-publico | 只用公有领域著作做的「人设插件」目录：每个人设 = 一个 skill（规则 + 带出处的知识 + 原文证据 + 局限），首个为卡帕布兰卡国际象棋教练；`install/grok-bot.md` 一段提示词交给主 Bot 安装。CC-BY-4.0，目前仅 1 个人设、作者自述未在真实 Bot 评估，先信号 | Skills / Personas | **GitHub**（10-28 00:20 建） |
| m0r6aN/agent-bus-mailbox | https://github.com/m0r6aN/agent-bus-mailbox | 云端 Grok Bot 够不到本机时，用一个 git 仓当「信箱」：本机桥只写 inbox、各 agent 只写自己的 outbox，按序号+时间戳命名、JSON Schema 校验、签名、consumed/rejected 回执。思路和本仓 `.collab` 同类但更严格；是个人私有系统的公开镜像，不点名作者设置，只当跨机协作模式信号 | Bridges / Multi-agent | **GitHub**（10-28 01:36 建） |

### Skip（本轮）

AmitMirgal/orgbot-hub、PhillipHolland/grokbotshelf、rowama/mmbridge、eugeniughelbur/obsidian-second-brain 等本窗有 push 但已列；elie222/rakazo、5dive-ai/5dive、leepokai/Codync 等「开源替代品」非 Grok Bot 玩法；MyGrokOrg/* 数学库、Bronsonalan/pi-adblocker 无配方；X 本窗多为模板自推（Harper、Mend & Move、Signal 连接模板等无仓）、收益营销、Spam/数据删除转述；X Article（@coder_onchain 中文实战指南、@dustADD「别再开空白 Bot」、@LoganTGott 全课程）交给 X 雷达判断。

## 2026-10-28 08:12 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接 / handle 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 02:02→08:12（Asia/Shanghai）`gh search`（grokbot / grok-bot created≥10-27、"grok bot" updated≥18:00Z）+ X `search_posts_all`×1（无可用）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| realTaki/bot-keepalive | https://github.com/realTaki/bot-keepalive | **长任务防云电脑挂起的 skill**：Grok Bot 没有活跃回合时会挂起整台云电脑，`nohup`/`tmux` 后台任务也一起冻住；做法是任务脱离会话启动并登记到一个目录，再开一个 low effort 守护 subagent 连续阻塞等待、每 5 秒查一次，全部结束或到硬截止就退出。README 自带中文简介，并直说守护期间持续耗额度，适合配合省额度条目一起讲取舍。本轮最值得看 | Skills / Long jobs | `skill` `box` `long-job` `subagent` `mit` | 1 / MIT | **GitHub**（10-28 02:05 建） |
| Silousr/grokbot-model-connector | https://github.com/Silousr/grokbot-model-connector | Bot 把活派给本机已登录的 Codex CLI / Claude Code（用你自己的订阅），按钮选模型、跨模型保留记忆与上下文；任务完成、失败、卡住、超时或取消时经 webhook 叫醒 Bot。纯 Python 标准库、只本机单用户、不开端口（webhook 设置时有一次性回环表单），附模板 skills。与已收 herdr 通知类互补：这个是 Bot 主动派单 | Bridges / Coding agents | `mcp` `codex` `claude-code` `webhook` `mit` | 0 / MIT | **GitHub**（10-28 07:35 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| script-repo/visual-designer | https://github.com/script-repo/visual-designer | 「设计工作室」人设 + skill：驱动开源 Crafting Apps 套件的无头 CLI 出海报、logo、PDF、调色、短视频，纯 CPU。MIT，但依赖小众套件，先信号 | Skills / Creative | **GitHub**（10-28 06:12 建） |
| givenkiban1/grokbot-universal-mcp | https://github.com/givenkiban1/grokbot-universal-mcp | 自托管 Claude ↔ Grok Bot 双向桥：Claude 经 MCP 派活唤醒 Bot 的 webhook routine，Bot 用一条 curl 回帖到同一线程；带后台面板与 `grokbot-delegation` skill。无 License、需自建服务器与隧道，先信号 | Bridges / Multi-agent | **GitHub**（10-28 03:18 建） |
| wangsen2020/gbot-local-service | https://github.com/wangsen2020/gbot-local-service | 中文：把第三方 `grok-bot-cli` 包成只监听 127.0.0.1 的本地 HTTP 服务（异步 jobs、去重、续查），让浏览器扩展和脚本给 Bot 发消息。非官方、复用桌面端登录会话、无 License，先信号 | Bridges / Local | **GitHub**（10-28 02:31 建） |
| OsheaDavis/grokbot-phone-assistant | https://github.com/OsheaDavis/grokbot-phone-assistant | 已脱敏的电话助理：Twilio 号码 + Fly.io + xAI 实时语音接听留言、发摘要，外呼每通须人工批准，带隐私护栏。MIT，但不是 Grok Bot 内玩法，作语音信号 | Voice / Phone | **GitHub**（10-28 03:16 建） |

### Skip（本轮）

jbellsolutions/wescale-grokbot-team、grokbot-lending-team、spike-it-up-ai-team（为具名客户定制的团队仓，含客户姓名与业务，不点名进公开候选；「一段粘贴让主 Bot 按 START-HERE 搭团队」模式可留作写法参考）；owenpkemp-hub/grok-bot-desk（Solana 交易台，币圈类拒）；sajjadgrw1/grokbotxai、RainShow/grok-bot、hawkeg/grok-bot-showcase 空仓或无说明；其余本窗 push 均已列。

## 2026-10-28 10:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 08:12→10:05（Asia/Shanghai）`gh search repos`（grokbot / grok-bot / "grok bot" / "grokbot skill"，updated≥10-28 00:00Z）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| fenfenxu/grokbot-dispatch | https://github.com/fenfenxu/grokbot-dispatch | **中文：让 Codex CLI / Claude Code / Cursor 一句话把任务派给 Grok Bot**。纯 skill（SKILL.md + curl/python3 脚本，无常驻进程）：本地有 webhook 配置就带上发送者和上下文直接 POST；没有就给一段粘贴给 Bot 的提示词，让 Bot 自建 webhook routine 再登记 URL。支持「每个 bot 一个 webhook」和「一个总调度 bot 转发队友」两种模式。与已收 herdr 通知、Silousr 派单方向相反，正好补齐「本机 agent → Bot」。本轮最值得看 | Bridges / Coding agents | `skill` `webhook` `routine` `codex` `claude-code` `mit` | 0 / MIT | **GitHub**（10-28 09:03 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| mehrdadmms/botkin | https://github.com/mehrdadmms/botkin | Grok Bot 之间的「社交网络」远程 MCP：bot 互加好友，四级信任（只传话 / 读共享笔记 / 免批低风险任务 / 全托），服务端管谁能发给谁、读哪些笔记。思路新，但是第三方托管服务、需注册拿 key、AGPL，高信任档有安全隐患，先信号 | Multi-agent / Connectors | **GitHub**（10-28 09:09 建） |
| ctrlcmdshft/awesome-grok-bots | https://github.com/ctrlcmdshft/awesome-grok-bots | 同类 Awesome 列表（CC0），收 177 个第三方 Grok Bot，偏隐私清理、反骚扰、家庭网络等生活向，数据由 yaml 生成。与本仓玩法/配方定位不同，可作「更多资源」互链参考 | More resources | **GitHub**（10-28 08:40 建） |
| hayashiii-ghub/zumennya-bot | https://github.com/hayashiii-ghub/zumennya-bot | 日文：5 个 bot 从建筑图纸拾取装修候选、交叉核对与独立审查，人在聊天里拍板后写进仕上表；公开看板只用虚构数据，写入只走带 key 的 bot API。垂直行业多 bot 流水线样例，无 License，先信号 | Multi-agent / Vertical | **GitHub**（10-11 建，10-28 有 push） |
| gman-robotics/context-efficiency | https://github.com/gman-robotics/context-efficiency | 省上下文插件规划：把持久状态移出对话，走 recall / retain / handoff 三动作 + 可插拔记忆后端（默认本地 SQLite MCP）。目前只有方案文档、SKILL.md 未写，等成形再看 | Usage / Memory | **GitHub**（10-28 02:27 建） |

### Skip（本轮）

AyanBhardwaj1/ClaudeBot（Claude 版仿品）、cameroncanova-spec/careem-grokbot-demo（密码保护的客户演示）、galyarderlabs/hermes-bots（Hermes 主机客户端，非 Grok Bot 玩法）、m0r6aN/agent-memory（个人私有记忆仓，不点名）、pileofflapjacks1/grok-bot-platformer（同名游戏）、raghix123/grokbot-links、grokbotcompass.github.io（跳转/空页）、taskfuel/grok-bot-plugin（付费工具插件推广，无玩法）。

## 2026-10-28 10:40 Asia/Shanghai · T7 日更

> 按 full_name / 链接 / 帖 id 与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。GitHub：`gh search repos`（grokbot / grok-bot / "grok bot" / template / playbook，updated≥10-27 10:00）；X：近 24h「grok bot / grokbot + skill / template / playbook / github」。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| @poteto 的 tibot（X 运营 bot 模板） | https://x.com/poteto/status/2115205951649423585 （模板 https://x.ai/bot/xZ4wRvomWqzCXnyYFr7i3） | **管 X 账号的现成 bot**：盯提及和关键词（不 @ 也能抓）、每天一份排好序的短摘要（可改每小时）、过滤垃圾、翻译非英文帖、可自动拉黑喷子，且从不替你发帖。作者本人自用，帖子约 2.4k 赞 / 1.6k 收藏。与本仓 X 雷达类 routine 同路，可作「官方模板一键雇」示例。本轮最值得看 | Templates / Social | `template` `x` `digest` `moderation` | 帖 2.4k 赞 | **X**（10-28 06:16） |
| unclebob/ub-mode | https://github.com/unclebob/ub-mode | Uncle Bob 自用的写代码纪律 skill，他说自己的 grokbots 写代码时都用它：先跑通再做对，TDD、根因修复、可验证小步，并配 CRAP / 重复度 / 变异测试等确定性质量门。基于 @poteto 的规则精简。约 2.4k star，但仓库未声明 License，先按「链接 + 短评」收 | Skills / Coding | `skill` `coding` `tdd` `quality-gate` | 2443 / 未声明 | **X** 帖 2114388856976069095（10-26 00:09，近 24h 仍在被转发求装）→ GitHub |
| Deepusleepy/t3-tots | https://github.com/Deepusleepy/t3-tots | 给 T3 Code（开源编码 agent 客户端）配的 Grok Bot 伴侣：一套 skills + 小工具，让 Bot 查线程状态、等待项、新线程，发报告和变更提醒，可选 `t3listen` 把提问和运行结束推到你的 webhook。MIT、无账号无遥测；README 直说依赖 T3 内部本地 API、版本更新可能会坏 | Bridges / Coding agents | `skill` `t3code` `webhook` `mit` | 78 / MIT | **GitHub**（10-15 建，10-28 有 push） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Grok Bot Command Line（@BrianRoemmele 模板） | https://x.com/BrianRoemmele/status/2115269980086571190 | 用免费 Google Voice 号 + Gmail，让 Bot 听短信和语音留言指令、紧急事项短信回你；只认本人号码 + 口令，三档权限（涉钱/删除/联系新人必须回 App 点批）。思路好，但依赖 Google Voice（国内用户不可用）、刚发帖量小，先信号 | Voice / Phone | **X**（10-28 10:30） |
| RongleCat/grok-bot-sdk | https://github.com/RongleCat/grok-bot-sdk | 非官方 Node.js SDK，逆向桌面客户端协议：登录、列 bot、读会话、发消息、SSE 收回复。同作者 Clipper 已在 README；SDK 走私有协议、版本一变就坏，且需落地 token，先信号 | Bridges / SDK | **GitHub**（10-14 建，10-27 有 push） |
| @Bot_Lynn DeepSeek 中文搜索 skill | https://x.com/Bot_Lynn/status/2115248468394651785 | 中文：把 DeepSeek 搜索 API 包成 skill 搜公众号/知乎/头条/微博，支持 site:/after: 筛选，按次计费。贴合中文用户，但帖内未给仓库链接、热度极低，等放出仓再看 | Skills / Search | **X**（10-28 09:05） |

### Skip（本轮）

SimonPuebla/CMO-grokbot（刚建空仓）；MyGrokOrg/*（与 Grok Bot 无关的数学库）；hamedgitty/bloks、PrisacariuRobert/sidemates（竞品式多 agent 桌面应用，非 Grok Bot 玩法）；sherwoodagent/grokbot-fund-template、@blmario669 Binance skill（金融/币圈类拒）；Vesite/GrokDiscordBot、minhdevtry/grokbot（同名旧仓/空仓）。

## 2026-10-28 12:01 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 10:05→12:01（Asia/Shanghai；中间 T7 10:40 已扫一批）`gh search`/`gh api`（grokbot / grok-bot / "grok bot" created≥10-28 + pushed≥02:00Z）+ X `search_posts_all`×3（playbook·skill·routine / url:github.com / 中文）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| izakfilmalter/grokbot-slack-relay | https://github.com/izakfilmalter/grokbot-slack-relay | **把 Slack @提及/DM/线程转发给 Grok Bot webhook routine**：Vercel + Bolt 验签、3 秒内 ack、过滤 bot/编辑/重试与重复 `event_id`，再 POST JSON 给 routine；Bot 自己用 `chat.postMessage` 回 Slack（中继从不代发）。含 manifest、`.env.example`、样例 routine 提示与 test。Hobby 可跑。本轮最值得看 | Bridges / Slack | `slack` `webhook` `routine` `vercel` `mit` | 0 / MIT | **GitHub**（10-28 11:11 建） |
| vilaslautaro/claude-code-grokbot | https://github.com/vilaslautaro/claude-code-grokbot | **西语完整配方：Grok Bot 派 Claude Code（云端 `--cloud` 或本机 worktree），Stop/失败/要权限时 hook 打 webhook 叫醒 Bot**；Bot 只看分支、开 PR、通知，从不 merge。含 kit 脚本、environment setup、wake routine 模板与一步配置 Bot 分享页。与已收 fenfenxu/dispatch、Silousr 派单同向，补「Bot 电脑上跑 Claude Code + 唤醒」 | Bridges / Coding agents | `claude-code` `webhook` `routine` `hook` `es` `mit` | 0 / MIT | **GitHub**（10-28 10:49 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| zhangjian94cn/magpie-cloud-agents-macos | https://github.com/zhangjian94cn/magpie-cloud-agents-macos | Magpie 插件：把 Codex Cloud / Cursor Cloud / Devin / Dots / **本机已登录的 Grok Bot 桌面端**暴露成 OpenAI 兼容 chat 提供者（默认 app-drive）；MIT，但依赖 Magpie+Bun，且声明 `tool_call: false`、每回合计费，先信号 | Bridges / Magpie | **GitHub**（10-28 本窗新建并推） |
| itskylon/NowBar | https://github.com/itskylon/NowBar | 原生 macOS 菜单栏看 Codex / Claude / **Grok Bot** 额度与本机 Token 费用；Grok Bot 目前只复用桌面登录读账户额度、Token 明细暂不支持。有 Releases，**无 License**，先信号 | Tools / Usage UI | **X** @kevin_long__ + **GitHub**（10-27 建，本窗推） |
| wangsen2020/grok-bot-bridge | https://github.com/wangsen2020/grok-bot-bridge | 上轮信号 `gbot-local-service` 已更名为 Grok Bridge（npm `grok-bridge`）：本机 127.0.0.1 HTTP/MCP 包装第三方 grok-bot-cli，带托盘面板与 jobs 去重续查。仍无 License、非官方会话复用，作更名/升级信号勿重复当新仓 | Bridges / Local | **GitHub**（原 10-28 信号仓本窗改名） |

### Skip（本轮）

jbellsolutions/pravda-seo-grokbot-team（客户定制仓，隐私跳过，同作者上轮模式）；botfixer5000/make-your-week-last（额度 kit 落地页、无 License）；lazyclaw137-ship-it/claude-code-hooks-trading-bot（交易风控 hook）；em19900822-sys/medical-disclaimer-rail（医疗免责条 skill、无 License）；tt0xcatyi/grokbot-office（whatsmyagentdoing fork，上游已信号）；nickmartin1ee7/grok-bot-nix（又一个 Nix 打包，与已列同类）；grokbotcompass / raghix123 / cameroncanova / taskfuel（上轮已 skip）；fenfenxu/dispatch、botkin、awesome-grok-bots、t3-tots、BrianRoemmele Command Line（本窗白天/T7 已收）；rodrigo-pasini/grokbot-kit（此前 Maybe：pre-release，本窗 README 称命令可用但仍 0.x，不重推）；Polymarket/$10k 收益帖、Spam Scrubber、JulianGoldieSEO Article（交 X 雷达）。

## 2026-10-28 14:06 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 12:01→2026-10-28 14:06（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥10-28 + pushed≥04:00Z）+ X `search_posts_all`×3（playbook·skill·routine / url:github.com / 中文·voice/replyslip）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| RussGuo/grokbot-voice-meeting | https://github.com/RussGuo/grokbot-voice-meeting | **多 Bot 语音会**：人与若干 agent 同房间语音开会，主持排议程/举手，人一开口全体 bot 停（barge-in）；附 `skills/voice-meeting/SKILL.md`，Bot 导出各参会者真实上下文后在 Linux box 跑 `meet` 回 join link；会中答不上的问题可经 file/webhook 问回真实 Bot，会后 `meet followup` 出纪要与各 bot 行动提示词。默认 LiveKit + 豆包 ASR/TTS + DeepSeek，可换。中英 README、`meet demo` 无 key 可跑。本轮最值得看 | Multi-bot / Voice | `multi-bot` `voice` `skill` `livekit` `zh` `mit` | 0 / MIT | **GitHub**（10-28 12:54 建，本窗推） |
| Crokily/pi-durable-bot | https://github.com/Crokily/pi-durable-bot | **开源 Grok Bot 平替「Pots」**：自托管任意模型；读全频道/邮件/事件再判断要不要开口；自带电脑写跑代码、定时回访、跨频道长记忆；基于 pi-durable 崩溃续跑与去重发送。MIT、文档完整。与已列 OpenGrokBot / DeepSeekBot 同向，可作 Self-hosted 新对照 | Self-hosted / Alternatives | `self-hosted` `alternative` `durable` `mit` | 1 / MIT | **GitHub**（10-28 本窗新建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| replyslip 分享 Bot（不泄 webhook） | https://x.com/babykswanson/status/2115310376539623573 | 给每个 grokbot 挂 webhook → 让 bot 自助 onboard 到 replyslip → 可把 bot 分享给别人并按访客限额/任务范围、随时撤销，且从不把 webhook secret 给客人。无独立仓，约 1.9k 粉刚发，先信号 | Sharing / Webhook | **X**（10-28） |
| X 算法变更监控 routine 提示词 | https://x.com/ryangrowthh/status/2115300023844102346 | 可复制一句：让 Bot 隔几天盯指定 GitHub（X algo 仓库）有更新再短信通知、无变则静默。约 6.5k 粉 / 11 赞；短帖，作 Routines 小技巧信号 | Routines / X | **X**（10-28） |

### Skip（本轮）

DYLANFREE/grok-bot-pipeline（Agent Wallet 捕 alpha 多岗流水线，币圈类拒；结构可抄但主题不合）；Parthbarot-1/Grok_bots（OANDA 外汇交易桌）；rudrakshsyal/grokbot_tv_launcher（同名 TV 启动器，与 Grok Bot 产品无关）；izakfilmalter / vilaslautaro / fenfenxu / magpie / NowBar / botkin 等本窗白天/T7 已收；jbellsolutions 客户仓、交易/打新/Polymarket 收益帖、Spam Scrubber、付费 Playbook 落地页；@yamasho0130 Muse↔Grok Bot webhook 一句体感（过薄不单列）。

## 2026-10-28 16:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 14:06→16:10（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥10-28 + updated≥05:30Z）+ X `search_posts_all`×1（Grok Bot · github/skill/routine）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| wchengyen/feishu-grokbot-bridge | https://github.com/wchengyen/feishu-grokbot-bridge | **飞书 × Grok Bot 桥接**：飞书私聊或群里 @ 企业自建应用即可派活给 Bot；飞书侧只用官方 `lark-oapi` 长连接（WebSocket），无需公网回调；任务 POST 到 webhook routine，Bot 不持有飞书 App Secret，把结果写进同机 outbox 由桥接代发回原对话。15 步配置 + routine 提示词 + 安装脚本，繁中文档。国内团队最实用的一条，本轮最值得看 | Bridges / Feishu | `feishu` `webhook` `routine` `zh` `mit` | 0 / MIT | **GitHub**（10-28 15:18 建，本窗推） |
| cwijayasundara/cloud_harness_bots_v1 | https://github.com/cwijayasundara/cloud_harness_bots_v1 | **Grok Bot 外环 + Claude Code cloud 内环 + Uncle Bob 计算门禁**：六个 Bot 角色（Foreman/Scribe/Smith/Auditor/Keeper/Scout）用 `chb dispatch` 派 `claude --cloud`，每次提交跑 rig 传感器与 ub-crap/ub-dry，`chb proof/ledger/merge` 按策略决定能否合并，07:30 晨报。零运行时依赖、有 CI。与 unclebob/ub-mode、vilaslautaro 派单同向，补「多 Bot 管理 + 质量门」 | Multi-bot / Coding agents | `multi-bot` `claude-code` `quality-gate` `mit` | 0 / MIT | **GitHub**（10-28 14:40 建，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| tt0xcatyi/agent-review-handback | https://github.com/tt0xcatyi/agent-review-handback | 一页 skill：审稿/修复/批准结论回传给另一个 Bot 时带 priority 立即唤醒，否则消息只被「held」可能几小时没人看。正好对应作战室交接痛点；**无 License**，先信号 | Skills / Multi-bot | **GitHub**（10-28 14:49 建） |
| TillmanBuildsTech/grokbot-node | https://github.com/TillmanBuildsTech/grokbot-node | Go 单二进制把官方「本地电脑」daemon 无头跑在常开 Linux（systemd），grokbot-headless 的重写。MIT，但非官方、走内部协议自铸凭证，风险高，只作信号勿推荐 | Tools / Local computer | **GitHub**（10-28 15:29 建） |
| freepik-company/magnific-plugin | https://github.com/freepik-company/magnific-plugin | Magnific 官方插件：Grok Bot 等接 Magnific MCP + 视频广告/投放素材/商品图等 skill（先报价再花钱、草稿再定稿）。MIT，但属商业付费服务，作 Plugins 信号 | Plugins / Creative | **GitHub**（10-28 13:37 建） |

### Skip（本轮）

cokepoppy/coke-grok-bot（「复刻」仓无说明无 License）；milordasceo/gosplan-conveyor（俄语招投标客户流水线、无 License）；helingping/ink-guard（测试仓）；Phoobobo/grokbot-bridge-herdr（10-27 建，待下轮看是否已收/再评）；X 侧多为体感短帖（Grok Bot 201 转述、书签晨报、Pages 功能）、Fanvue 收益长文、币圈 TermiX，交 X 雷达或拒。

## 2026-10-28 18:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 16:10→18:10（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥10-28）+ X `search_posts_all`×1（Grok Bot · github/skill/routine/webhook）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| nsoliven/grok-bot-setup | https://github.com/nsoliven/grok-bot-setup | **自家 Linux 机不暴露公网也能接 Grok Bot**：首个集成是 T3 Code——watcher 只读本地库，线程真在等你（提问 10 分钟 / 完成 30 分钟未看）才批量 POST 到 webhook routine，带日上限、只发元数据；回聊天里一句话即可经 4 个工具的窄权限 MCP 网关回复该线程（cloudflared 只出站 + Cloudflare Access 服务令牌）。安全边界讲得清楚（SECURITY.md），本轮最值得看 | Bridges / Self-hosted | `webhook` `routine` `mcp` `security` `mit` | 0 / MIT | **GitHub**（10-28 17:39 建，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| ozgureyilmaz/reverse-engineering-grok-bot | https://github.com/ozgureyilmaz/reverse-engineering-grok-bot | 黑盒研究 Grok Bot 购物推荐：同提示不同 bot / 地区给的零售商与链接差异很大，附原始回复与解析脚本。研究类、非玩法，可作「延伸阅读」信号；License 为 Other | Reading / Research | **GitHub**（10-28 16:34 建） |
| quafulz/dsh-plugin-grok-bot | https://github.com/quafulz/dsh-plugin-grok-bot | DeepSeek Harness 插件：列 bot/群、发消息、读线程，实现跨 agent 派活。MIT，但默认复用桌面 App 加密会话（非官方路径），风险偏高，只作信号；官方 webhook 路线更稳 | Bridges / Coding agents | **GitHub**（10-28 17:11 建） |
| Ack3r5 部署后 webhook 盯发布 | https://x.com/Ack3r5/status/2115366355062898835 | `make release` 打 tag → Actions/Helm/ArgoCD 上线后再 POST 一条 webhook 让 Bot 盯这次部署；短帖小技巧，315 粉，作 Routines 信号 | Routines / DevOps | **X**（10-28） |

### Skip（本轮）

kapilcdave/kapil-grok-bot（memecoin / Kalshi 交易多 Bot，币圈类拒）；Protoduct-AI/fracta-plugin（单一付费 App 的插件，偏推广）；bellieray/orca（通用多 agent 工作台，非 Grok Bot 专属）；Bataino/grokbot-receipts、workincodoor/grokbotcoin、muhammad10001j-oss/Grokbot（空仓 / 币）；X 侧 @0xJoooe 長文、@daodao166888 合集表交 X 雷达，已在 .collab 记录。

## 2026-10-28 20:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 18:10→20:10（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥10-28）+ X `search_posts_all`×1（Grok Bot · github/skill/routine/webhook）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| uzairayed/agent-skills（feature-map-assistant） | https://github.com/uzairayed/agent-skills | **给 Bot 一张「简称→真实 ID」对照表**：skill 让助手在持久 store 和 `/workspace` 维护不超过 100 行的 `FEATURE_MAP.md`，把「我 Mac」「团队群」「路线图」这类口头简称映射到机器 ID、频道、Notion/Drive ID、本地路径和子 Bot；先查表再搜连接器、可达就直接干，只在失效、歧义或外发/删除时才问。另附面向代码仓的 feature-map-project。多 Bot 作战室省掉反复问路径，本轮最值得看 | Skills / Memory | `skill` `memory` `multi-bot` `mit` | 0 / MIT | **GitHub**（10-28 18:13 建，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| zhu618-ui/douyin-open-mcp | https://github.com/zhu618-ui/douyin-open-mcp | 面向 Grok Bot 的抖音开放平台远程 MCP（Streamable HTTP + Bearer，官方 OpenAPI OAuth 上传/创建/列表），中文文档、讲清 TikTok MCP 不能直接改名用。Phase 1 脚手架、**无 License**，国内内容创作者可盯，先信号 | Connectors / Creator | **GitHub**（10-28 18:39 建） |
| kondasviktor Grok Mail | https://x.com/kondasviktor/status/2115413270211199427 | 给 Bot 开专属邮箱后，每小时 routine 把邮件同步进 Neon 做私有邮件界面，外发一律等本人点 Send；短帖带教程外链，0 曝光新号，作 Routines 信号 | Routines / Email | **X**（10-28） |
| lgtwet 更新云电脑前备份 skill | https://x.com/lgtwet/status/2115408681680634106 | 回复帖小技巧：更新云电脑前先叫 Bot 把环境备份成文档、更新后逐条恢复；cron 不稳就另配机器跑脚本、有变化再 webhook 叫醒。同作者另一条已在 inbox，作 Skills 信号 | Skills / Ops | **X**（10-28） |

### Skip（本轮）

kush-coder/autopilot-open-duet（「Official Build & Verified Release」式命名的替代品仓，可疑，拒）；Protoduct-AI 五个单品插件（buddybase/lore/ledgie/hachimo/hearth，单一 App 推广，同 fracta 处理）；outerheaven199X/CryptOSINT-GrokBot（币圈 OSINT、无说明）；raymizzou/grok-bot-work-flow-public（空仓，下轮再看）；rodvid/backup-Grok-bots（个人备份）；0xquqi/EZbot-grok-project-skill（已随 X 长文进 x-articles）。X 侧 @slowflying99「七个员工」、@0xSeekSky、@ecomstreur、@MapleZireael 长文交 X 雷达。

## 2026-10-28 22:10 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。窗口约 20:10→22:10（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" created≥10-28）+ X `search_posts_all`×1（Grok Bot · github/skill/routine/webhook）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| rakei076/resethook | https://github.com/rakei076/resethook | **Codex 额度重置预告 → 叫醒 Grok Bot 先用完剩余额度**：Cloudflare Workers 监听重置预告，按事件（announced / landed / banked / retracted）POST 到你的 webhook routine；附 skill 读取本机 Codex 实时额度、估算截止前能否用完，再后台跑只读 Codex 任务。中英双语文档，「外部事件 → webhook routine → skill 决策」的干净样板，本轮最值得看。注意：安装走第三方站点 `curl | sh` 与托管服务，收录时提示先读源码 | Routines / Webhook | `webhook` `routine` `skill` `codex` `zh` `mit` | 0 / MIT | **GitHub**（10-28 21:21 建，本窗推） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| FarkasLabs/infinitary-grokbot-bridge | https://github.com/FarkasLabs/infinitary-grokbot-bridge | Infinitary 卡片经 webhook 转给 Grok Bot，按显式命令才代答卡片/回线程；https-only、不重试、有 SECURITY.md。MIT，但 0.1.0 且「代操作」未实测，单一 App 场景，先信号 | Bridges / Webhook | **GitHub**（10-28 20:42 建） |
| nordbeam/nordsynk-fortnox-mcp | https://github.com/nordbeam/nordsynk-fortnox-mcp | 瑞典记账系统 Fortnox 的托管 MCP 插件，改动默认逐行审批后才落库，有 Grok Bot 模板。MIT，但商业服务且地区性强，作 Plugins 信号 | Plugins / Finance | **GitHub**（10-28 21:36 建） |
| lamGrok 桥接前 5 项检查 | https://x.com/lamGrok/status/2115432755026678101 | 接外部 agent 前：写明上游、webhook URL 只放工具槽不进聊天、首单只读产物且不开发送工具等。0 粉新号短帖，作 Bridges 安全清单信号 | Bridges / Security | **X**（10-28） |

### Skip（本轮）

HatayaMisuzu/grokbot-s-working-home（DSH 插件快照，非 Grok Bot 玩法）；uiskys/gais-office-preview（个人 Office 预览页、无说明）；S1nned1/x-region-highlighter（Bot 写的浏览器扩展，与玩法无关）；oexapp/grokbot、hk1088/-Grokbot-、neo-meldlabs/test-grok-bot（空仓/测试）；raymizzou/grok-bot-work-flow-public（仍为空仓）。X 侧 @lv_chen2006 IM 长文、@0xChonsy、@Drrubentorrest、@heyrobinai 长文交 X 雷达；@Assassin_Malvo 合约叙事搜索（币圈）拒。

## 2026-10-29 00:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复（espinobj/grok-bot-tray 与此前已拒的 foztrk 同名仓不是同一作者）。窗口约 22:10→00:05（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot skill，created≥10-28）+ X `search_posts_all`×1（Grok Bot · github/skill/routine/webhook）。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| huaspirit123/grokbot-visual-office | https://github.com/huaspirit123/grokbot-visual-office | **多 Bot 作战室的像素办公室看板**：等距像素风办公室里每个 agent 一个小机器人，一眼看出谁在干活、谁卡住、谁举手等你确认；点开看进度、已完成和「待你确认」，可配 HTTP provider 在页面里直接答复。纯 Vanilla JS + canvas，无构建无后端无 key，按 JSON Schema 喂数据或写 adapter 接自己的 Bot，中文默认、示例数据全虚构。本轮最值得看 | War Room / Dashboard | `multi-bot` `war-room` `dashboard` `zh` `apache-2.0` | 0 / Apache-2.0 | **GitHub**（10-28 22:54 建，本窗推） |
| alexkrnlv/grokbot-second-brain | https://github.com/alexkrnlv/grokbot-second-brain | **git 托管的 Bot 第二大脑模板**：hot/warm/cold 三层 markdown 记忆，Bot 每次对话和摘要后重读 hot（<20KB）；附 AGENT-RULES 协议、ONBOARDING 提示词，以及每日 23:30 收尾、每周复盘的 routine 提示词（pull→归档事实→更新 hot→自检→commit/push）。README 明确要求私有仓、敏感业务数据不入库。**无 License**，收录时只作参考链接 | Memory / Routines | `memory` `routine` `git` `template` | 0 / 无 | **GitHub**（10-28 22:24 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Usefnoureldin/hostbase-grok-bot-plugin | https://github.com/Usefnoureldin/hostbase-grok-bot-plugin | 民宿/短租 PMS Hostbase 的只读 MCP 连接器（订单、房态、价格），MIT，单一商业服务，作 Plugins 信号 | Plugins / Vertical | **GitHub**（10-28 22:13 建） |
| espinobj/grok-bot-tray | https://github.com/espinobj/grok-bot-tray | Windows 非官方托盘助手：隐藏到托盘、开机启动、崩溃拉起且识别更新安装不打断。MIT、带测试，桌面端小工具，作 Tools 信号 | Tools / Desktop | **GitHub**（10-28 23:44 建） |
| talentacommerce 订单 webhook 桥 | https://x.com/talentacommerce/status/2115449894836064419 | 客户案例回复帖：票务系统无营销邮件集成，Bot 用 v0+Vercel 搭小桥，每单 webhook→读订阅同意→upsert 联系人并触发流程。真实落地但短帖，作 Bridges 信号 | Bridges / Webhook | **X**（10-28） |
| inorbit01 Claude 结束 webhook | https://x.com/inorbit01/status/2115454886972198959 | 葡语短帖：给 Claude 跑完挂「run 结束」webhook 叫醒 Grok Bot，解决 Bot 不知道外部 agent 何时完工；与 FrancoE114696 用 skill 打 trigger webhook 让 Bot 提醒「agent 等你拍板」同一思路，作 Routines 信号 | Routines / Webhook | **X**（10-28） |

### Skip（本轮）

P3NN4L/Tribot（只有 LICENSE）；doitupsolutions810-crow/grok-bot-（空仓）；habilmind-webs/borrador-prueba（测试仓）。@Rakel076 resethook 介绍帖（仓已在上轮收）；X 侧 @0xChonsy、@Drrubentorrest、@Chriswong、@godofwaaar、@thedelost 长文/引用交 X 雷达；@mrfundman 迁移吐槽、@KimSmit55267347 互动帖拒。

## 2026-10-29 02:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复（telegraphic-dev/a2a-exposed 已在库，am-i-cooked 是同作者另一仓；ExpeditedProjects/hutchdb 曾拒，streamdeck 是另一仓）。窗口约 00:05→02:05（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot skill，created≥10-28）+ X `search_posts_all`×1。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| RawPowered/Grok-Bot-Templates | https://github.com/RawPowered/Grok-Bot-Templates | **一人创作者 / 营销的多 Bot 团队模板包**：8 份可直接粘进 Bot 说明的 md（内容猎手、制片、回复、数据增长、邮件、外联，外加内容团队群聊与协调群聊两份作战室模板），每份写清成员、目的、运行方式，凡以本人名义外发一律先过审批。本轮最值得看。**无 License**，收录时只作参考链接 | Templates / War Room | `multi-bot` `war-room` `template` `approval` | 0 / 无 | **GitHub**（10-29 00:05 建） |
| telegraphic-dev/am-i-cooked | https://github.com/telegraphic-dev/am-i-cooked | **跑大活前先查额度的 quota-gate skill**：读本机 Claude Code / Codex / Cursor 凭据（Cursor 侧含 Grok Bot 周额度），按阈值返回 allow/skip，可做 Claude 插件钩子或经 skills.sh 装成纯 skill；作者称已接入 Grok Bot，让总管 Bot 在重置前自己判断还能不能加跑。MIT、带测试 | Skills / Usage | `skill` `quota` `routine` `mit` | 4 / MIT | **GitHub**（07-02 建，10-28 作者 X 推 Grok Bot 支持） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| monarchsofchaos004-gif/aibot-hostkit | https://github.com/monarchsofchaos004-gif/aibot-hostkit | 一条命令把 Grok Bot 云电脑（或任意 VPS）配成常驻 Claude Code/Codex 主机：tmux 守护、自动拉起、手机提醒，支持 `--plan` 让 Bot 代跑；繁中/英。MIT，但 `curl | bash` 且 v0.1.0，作 Box 信号 | Box / Tools | **GitHub**（10-29 01:30 建） |
| kylin-feng/grokbot | https://github.com/kylin-feng/grokbot | 非官方开源复刻 Grok Bot 界面：预置 Chief of Staff 等 Bot 团队、同事式线程、模拟「云电脑」面板，BYOK。MIT，偏学习 Demo，作 Community 信号 | Community / Clones | **GitHub**（10-29 00:35 建） |
| ExpeditedProjects/grokbot-streamdeck-releases | https://github.com/ExpeditedProjects/grokbot-streamdeck-releases | Stream Deck 一键对某个 Bot 发起语音对话（macOS 辅助功能代点按钮），MIT，桌面小工具作 Tools 信号 | Tools / Desktop | **GitHub**（10-29 00:39 建） |
| adplug-app/adplug-cursor-plugin | https://github.com/adplug-app/adplug-cursor-plugin | Google/LinkedIn/Microsoft Ads 的托管 MCP，只加一个远程 server，改动需你批准；商业服务，作 Plugins 信号 | Plugins / Ads | **GitHub**（10-29 00:56 建） |
| xpunkmonkx「routine 最后建」 | https://x.com/xpunkmonkx/status/2115476209093992695 | 先在真数据上跑一次、改错、存成 skill，最后才挂 routine，避免定时重复犯错。186 粉短帖，作 Routines 方法信号 | Routines / Method | **X**（10-29） |

### Skip（本轮）

jabowery/grokbot-update-loop-bypass（Linux 更新 bug 绕过，带二进制包，不收）；XYAIStudio/XYAIbot（只有 README 一行）；habilmind-webs/borrador-prueba（测试仓，已拒）。X 侧 @Av1dlive、@GrokBotRadar、@monetization_x、@twinedon0、@byalexai、@godofwaaar 长文/清单交 X 雷达；@zsz1210 Reason Network webhook 回帖与上轮 @inorbit01 同思路不另收；@irongiantXBT、@Yarilo7brigada 标题党拒。

## 2026-10-29 08:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复（realTaki/bot-keepalive 曾见于 inbox，bot-codex-delegate 是同作者另一仓；@Argona0x、@alx、@thecsguy 已在 docs/inbox，不另收）。窗口约 02:05→08:05（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot，created≥10-29 01:00）+ X `search_posts_all`×1。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| realTaki/bot-codex-delegate | https://github.com/realTaki/bot-codex-delegate | **让 Bot 像派云端 agent 一样派 Codex**：云电脑上常驻 `codex app-server`（仅 localhost，tmux+看门狗，带健康检查），主 Bot 把每轮活交给一个低成本等待子 agent 前台阻塞跑，完工再叫醒主 Bot；可插话打断、复用会话。解决 Bot 盯 Codex 烧额度、一放手云电脑就睡的问题，额度花在 Codex 上。中英双语。本轮最值得看 | Skills / Delegation | `skill` `codex` `box` `quota` `mit` | 1 / MIT | **GitHub**（10-29 04:25 建；作者 @realTaki42 中文推介） |
| Thekingbing/ai-group-chat | https://github.com/Thekingbing/ai-group-chat | **一人 + 多平台 AI 的自建群聊作战室**：Cloudflare Workers + Durable Objects，Grok Bot（routine webhook 推送）、Manus、DeepSeek 等经极简 HTTP Bot API 进同一房间共享上下文；webhook 推送或长轮询唤醒，15 秒触发合并、30 分钟在线期、防死循环限速、@ 补全。中文文档含踩坑与安全须知 | War Room / Bridges | `multi-bot` `war-room` `webhook` `cloudflare` `zh` `mit` | 0 / MIT | **GitHub**（10-29 02:58 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| gcentini02/grokbot-claude-relay | https://github.com/gcentini02/grokbot-claude-relay | 同一台电脑上 Claude Code 与 Grok Bot 桌面端的本地信箱 MCP（Rust、无网络监听、单 SQLite、各自 token、限速与敏感词告警），和本仓 .collab 互通思路相近，MIT，作 Bridges 信号 | Bridges / Claude | **GitHub**（10-29 02:39 建） |
| ItsOdeLeo/bookmark-persona | https://github.com/ItsOdeLeo/bookmark-persona | Bot 模板 + 纯 skill 插件：读你的帖子 vs 收藏/点赞，四轴打分生成「公开人格 vs 收藏人格」分享卡，本地运行。MIT（美术另有授权），偏娱乐，作 Templates 信号 | Templates / X | **GitHub**（10-29 04:10 建） |
| black93fox-alt/manuscript-compass | https://github.com/black93fox-alt/manuscript-compass | 书稿逐阶段审校插件（结构→准确性→文风→校对→出版 QA，P0–P3 问题单），MIT，垂直写作类作 Plugins 信号 | Plugins / Writing | **GitHub**（10-29 04:19 建） |
| l3b0u/content-agent-skills | https://github.com/l3b0u/content-agent-skills | 54 个内容运营 skill 的多平台打包（含 grok-bot 目标），先草稿后发，MIT；葡语文档、改编自他人仓，作 Skills 信号 | Skills / Content | **GitHub**（10-29 04:45 建） |
| bfrench Learner 自学习模板 | https://x.com/bfrench/status/2115588526804959293 | 定时读各 Bot 新轨迹、提 skill 改进，只问一次「批/跳过」，无货静默；附模板与 X 长文，约 2.4k 粉，作 Skills/Routines 信号 | Skills / Self-improve | **X**（10-29） |
| DeepDiscussion1 Harvester | https://x.com/DeepDiscussion1/status/2115541927089053845 | 免费模板：扫自选来源挖技巧，按「对哪个 Bot 有用」分拣并可起草待批 skill，与本仓雷达同型，作 Templates 信号 | Templates / Radar | **X**（10-29） |

### Skip（本轮）

Lucas215zz/GrokBot、cvhfmjr499-svg/Grok-bot、semenkulikov/MyGrokBot、wesleybraden-oss/grokbot-petsmart-demo（空仓/无说明）；NexisFlare/nexis-flare-kova（个人日志）；piotr-liszka/a-bot、identity-md-launches/*（复刻/生成站）；Abomination81/amazon-public-fetch-mcp、ilyaviache/b2bsearch-plugin、adplug-app/adplug-search-console-plugin（单一商业/抓取服务，暂不收）。X 侧 @0xGhostyx 10 步长文、@yourm11nd Lauren Tan 访谈转述交 X 雷达；@0xCortexq、@Greshamtrade、@AIMoneySystem 标题党/卖课拒。

## 2026-10-29 10:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复（@thecsguy Package Pal 同作者已在库，不另收）。窗口约 08:05→10:05（Asia/Shanghai）`gh search`（grokbot / grok-bot / "Grok Bot" / grok bot skill / grok bot routine，created≥10-29）+ X `search_posts_all`×1。未改 README。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Yolite-Dev/GrokBot-LeanOps | https://github.com/Yolite-Dev/GrokBot-LeanOps | **省额度的精简运行手册**：一段可贴进单个测试 Bot 的全局说明 + 一个 lean-execution 工作流 skill + 前后对比的用量记录表；顺序是先只读盘点 routine/工具，再用 5 个同类任务对比，最后才试低频 routine，外发与写生产一律留审批。作者明说不承诺省多少，中英双语。本轮最值得看 | Usage / Method | `skill` `quota` `routine` `approval` `zh` `mit` | 0 / MIT | **GitHub**（10-29 09:12 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 1806629231-del/grokbot-skill-dev-coach | https://github.com/1806629231-del/grokbot-skill-dev-coach | 「Skill 开发教练」模板的配套脚本：建骨架、校验、打包、自检，纯 Python 无依赖；解决模板导入只带 SKILL.md 缺脚本的问题。中文、**无 License**，作 Skills 信号 | Skills / Tooling | **GitHub**（10-29 09:56 建） |
| FTactiks Giveaway Picker 模板 | https://x.com/FTactiks/status/2115623401482051740 | 抽奖开奖 Bot 模板：把活动规则转成清单、核验参与、标疑似机器人号、用公开种子抽签可复验。约 3.9k 粉回帖分享，作 Templates / X 运营信号 | Templates / X | **X**（10-29） |
| @grok Alexa→routine webhook | https://x.com/grok/status/2115617223851086120 | 自定义 Alexa skill 把语音请求转给 Grok Bot routine 的 webhook，异步执行，Alexa 先回「On it」，完整结果落在 Bot 聊天里；语音入口接 routine 的思路，作 Routines / Webhook 信号 | Routines / Webhook | **X**（10-29） |

### Skip（本轮）

J12003LPZ/grok-bot-codex（把桌面端改接第三方模型后端的 shim，涉及提取客户端运行时，不收）；EllisClaude/pacpark-grokbot（单一机构内部 agent 插件，需私钥）；AdemVessell/receipt-engine（模板配套引擎，无 License、无说明）；hongletee/grokbot、gaswga/grokbot-first-project、1006killer/GROK-（空仓/练手）；5pine/elsie-tesla-key（只有公钥）。X 侧 @XAlphaIntel、@thehenrylabs Article 交 X 雷达；@SunsetUI186 组件引流、@LisaMAUSA 情绪陪伴模板、@EricSoundMinds changelog 转述不收。

## 2026-10-29 10:45 Asia/Shanghai · T7 日更雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复（Protoduct-AI 五个单品插件此前已 Skip）。`gh search repos`（grokbot / grok-bot / "grok bot" / skill / template / routine / plugin，created≥10-28）+ X `search_posts_all`×1（自 10:00 起）。未改 README/docs。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| number5meme/grokbot-wechatclaw-bridge | https://github.com/number5meme/grokbot-wechatclaw-bridge | **微信 ClawBot 接 Grok Bot routine**：走腾讯 iLink bot API，纯出站（无需公网 IP/域名/证书），微信消息（文本、图片、语音、文件、视频）以 JSON POST 到 routine webhook，回复用 `reply.sh --stdin` 防 shell 注入；投递失败可重放、断线自动重连，有离线测试。中文用户最直接的「手机微信喊 Bot」入口。本轮最值得看 | Bridges / IM | `wechat` `webhook` `routine` `bridge` `mit` | 1 / MIT | **GitHub**（10-29 10:08 建） |
| number5meme/grokbot-qqbot-bridge | https://github.com/number5meme/grokbot-qqbot-bridge | 同作者姊妹仓：QQ 开放平台 Bot API v2 走 WebSocket 模式接任意 webhook，私聊消息转给 Grok Bot routine，同样纯出站、可重放、安全回复脚本 | Bridges / IM | `qq` `webhook` `routine` `bridge` `mit` | 1 / MIT | **GitHub**（10-29 10:08 建） |
| AidaShika/personal-agent-dossier | https://github.com/AidaShika/personal-agent-dossier | **把一个 Bot 的职责、记忆、定时任务打包成单个 .dossier.md 搬家**：当 skill 交给 Bot，导入先 dry run 列出会丢的东西再批；附校验脚本（字段、指纹、密钥/隐私扫描）和虚构示例，CI 在跑，中英日韩文档 | Skills / Migration | `skill` `memory` `routine` `migration` `zh` `mit` | 7 / MIT | **GitHub**（10-28 19:34 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| edwintann 周用量 Page 模板 | https://x.com/edwintann/status/2115628690201874624 | 把每周用量做成一页：用了多少、是否超速、哪些 Bot/routine 最耗、怎么省；与 LeanOps、am-i-cooked 同属额度类，作 Usage 信号 | Usage / Templates | **X**（10-29） |
| gregpetrossian Solana 变更追踪 Bot | https://x.com/gregpetrossian/status/2115624867362226597 | X Article：一个 Bot 汇总 GitHub/Discord/X/邮件里的 Solana 核心开发变更并解释含义，多源雷达范例，币圈相关但不涉交易，作 Radar 信号 | Routines / Radar | **X**（10-29） |

### Skip（本轮）

grokbotcompass/grokbotcompass.github.io（驾车避险路线 PWA，与 Grok Bot 玩法无关）；nickhiebertdev/grokbot-meetup-october-2026（活动页）。X 侧 @dustADD 视频三路径 Article、@wi11champ 五家 Agent Article、@santoslee_me 系列、@lu58397 bot 工厂交 X 雷达；@HowarTracy 币安钱包交易、@orpheuskaze 邀请码绕过、@GrokBotPro 标题党拒。

## 2026-10-29 12:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot" / skill / routine，created≥10-29）+ X `search_posts_all`×1（自 10:00 起）。未改 README/docs。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Every Grok Bot: The Complete Directory（@BrianRoemmele） | https://x.com/BrianRoemmele/status/2115646312125542632 | **公开 Grok Bot 总目录**：称收录 7,539+ 个公开 Bot、分 26 类，10-28 更新，约 49 万粉作者，发帖 1 小时内 65 收藏。可作 Directories 节的外部入口，需核目录本体链接与是否持续更新。本轮最值得看 | Directories / Discovery | `directory` `templates` `discovery` | — | **X**（10-29） |
| Security Agent（@JennyMarquis X Article） | https://x.com/JennyMarquis/status/2115633821882204490 | 专门一个 Bot 记录团队其他 Bot 的对外动作（发信、发帖、外部写入）成安全日志，附做法与可试用入口；多 bot 团队的审计位，与作战室模板互补 | Multi-bot / Safety | `multi-bot` `audit` `log` `safety` | — | **X**（10-29） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Billable Hours by BMAC 模板 | https://x.com/CoCaptive/status/2115640904090316801 | 把日历、邮件、通话记录汇成带出处的可计费工时 + 发票草稿，明确「不发送任何东西」；自由职业者场景，@grok 官方号回帖认可，作 Templates 信号 | Templates / Freelance | **X**（10-29） |
| milordasceo/tender-conveyor | https://github.com/milordasceo/tender-conveyor | 「每个环节一个 Bot、一个文件夹」的流水线打包法：bot.yaml 清单 + 提示词 + routine + 安装与自检，附 SCHEMA.md，可按文件夹重建 Bot；俄语招投标场景、**无 License**，原仓此前已 Skip，此处只作「多 bot 可迁移打包格式」信号 | Multi-bot / Migration | **GitHub**（10-29 10:59 建） |
| chiguayeshao/agent-wallet-scout | https://github.com/chiguayeshao/agent-wallet-scout | 只读调研 skill：核币安 Agent ID / Agentic Wallet 生态项目的玩法、资格、成本、权限与退出条件，不连钱包不签名；MIT 中文。币圈题材，作 Skills / Research 信号，收录与否请 Claude 定 | Skills / Research | **GitHub**（10-29 11:48 建） |

### Skip（本轮）

sora3897/GBTNDataPool（模拟盘交易数据池，交易题材不收）。X 侧 @HowarTracy 币安钱包交易教程、@orpheuskaze 邀请码绕过、@nitrosendx 系推广、@JustTapYes 零粉落地页、@StockBrau 末日预警 routine 体感帖不收；@songsong275452「失败即停」Article 转述 @koko668800，交 X 雷达看原帖。

## 2026-10-29 14:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-29，看 12:00 后新建）+ X `search_posts_all`×1（自 12:00 起）。未改 README/docs。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| NVIDIA/SkillSpector | https://github.com/NVIDIA/SkillSpector | **装 skill 前先扫一遍**：NVIDIA 开源的 Agent Skill 安全扫描器，查恶意模式、提示注入、数据外传、供应链风险；面向 Claude Code / Codex / MCP skill，SKILL.md 格式通用，Grok Bot 装第三方 skill 前同样适用。生态已有 GitHub Action（NPJigaK/skillspector-action）和质量分扩展。本轮最值得看 | Skills / Safety | `skill` `security` `supply-chain` `apache-2.0` | 23k+ / Apache-2.0 | **X** @goan999999 2115685263703753169（约 2.8 万粉中文推荐）→ GitHub |
| ditto-assistant/ditto-plugin | https://github.com/ditto-assistant/ditto-plugin | 第三方记忆插件：托管 MCP（OAuth，无需贴 key）+ 两个 skill（按需回忆/写入长期记忆、关聊天前存「接续笔记」）；明确支持 Grok Bot 插件市场。厂商插件，Ditto 本身有免费额度 | Plugins / Memory | `plugin` `mcp` `memory` `skill` `handoff` `mit` | 0 / MIT | **GitHub**（10-29 13:47 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Grok Bot 总目录本体链接（补 12:05 段） | https://grokbot.rocks/ | 12:05 段 @BrianRoemmele 总目录的本体落地页：7,539 个公开 Bot / 26 类，标「每周更新」，可直接点链接加 Bot；作者新帖 2115661327016615998 建议「让 Bot 读这个目录、按目标补 skill」（约 1 小时 122 收藏）。注意页面带付费会员引流，短评宜只写目录用途 | Directories / Discovery | **X**（10-29） |
| tqdesign/happy-office | https://github.com/tqdesign/happy-office | 23 个 Bot 的团队互相问「什么样的工作环境让你开心」，汇总成 Three.js 办公室 + 十条团队守则（交接写清、卡三次就停下问、不编结果、不可逆先问）；多 bot 文化/守则范例，**License 未识别**（GitHub 报 NOASSERTION），仅作信号 | Multi-bot / Culture | **GitHub**（10-29 12:23 建） |

### Skip（本轮）

noxidsoft/OpenMausBot（milind-soni/OpenMausBot 的 fork，主仓已收）；trevor93/Grok-Bots（rakazo 镜像，主仓已收）；ArTechIslandapps/kurokit-mcp-zh-cn/zh-tw/ja（商业监控平台推广仓）；ndtp1303/zcode-driver（仅一行 README）；twentyfivcent/twofold（游戏测试）。X 侧 @nitrosendx 系 skill 推广复制帖、@Promise1web3 十个 agent 互动引流帖、@RV_Attila 比价模板（零互动）、@DavidWi15683372 诊所账单 8 bot 包（回帖推销）、@uncoolzero 段子不收；@zenghui1898 打狗军团 Article、@garygao_ai 50 Agent 工程流 Article 交 X 雷达。

## 2026-10-29 16:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-29，看 14:00 后新建）+ X `search_posts_all`×1（自 14:00 起）。本轮无够格「推荐收录」，只记信号。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 少楠 Plidezus 日常 Grokbot 用法清单 | https://x.com/plidezus/status/2115701180081098848 | flomo 作者列出自己的日常 Bot 分工：信息源推荐、报销接飞书多维表格、flomo/xiaobot 两条业务线各一组（客服、数据、改代码）、读书搭子、由 Bot 调度 GPT 与 Claude；中文一人公司多业务分 Bot 的真实样本，约 1 小时 23 赞 12 收藏。本轮最值得看，可交 X 雷达看是否有长文展开 | Multi-bot / Solo company | **X**（10-29） |
| dadamingmax/grok-bot-wechat | https://github.com/dadamingmax/grok-bot-wechat | 中文图文教程：用 ClawBot iLink + Webhook Routine 把 Grok Bot 接进个人微信，3 步走；与已在 inbox 的 number5meme/grokbot-wechatclaw-bridge 同方向，可作其「小白教程」配套。**无 License**、纯 README，仅作信号 | Channels / WeChat | **GitHub**（10-29 15:41 建） |
| talos-hq/grokbot-rocks | https://github.com/talos-hq/grokbot-rocks | 12:05/14:05 段 Roemmele 总目录的可 fork 静态镜像：JSON 快照 + 搜索/分类筛选 + 抓取脚本，只取公开部分（快照 780 个 Bot / 26 类，与原页宣称 7,539 有出入）；非官方、License 标 other，建议若收总目录只链原页，这个作备注 | Directories / Discovery | **GitHub**（10-29 14:48 建） |

### Skip（本轮）

choiking/Bot27（自称「更好的免费 Grok Bot」，macOS 替代品，非 Grok Bot 玩法）；IVMYM/bot-office（Three.js 办公室，无 License，与已信号 happy-office/whatsmyagentdoing 同类）；StockOnLLC/question-cards（通用计划对齐 skill，与 Grok Bot 无专门适配）；alvinmok74-cmd/eisenhower-matrix（仅一行 README）；Ocean-lhy/*、bizen/grokbotforum、cryptosniper1993/kade（空仓或无关）。X 侧 @nitrosendx 系推广复制帖、@Habibxweb3 meme 币交易 Article、@Damir_Akaza 引流帖、@attaporn/@socialdevflow 同文营销不收；@Zuessea 系列04、@sncgray226 资源站 Article、@Leo100x 内容团队 Article 交 X 雷达。

## 2026-10-29 18:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-29，看 16:00 后新建）+ X `search_posts_all`×1（自 16:00 起）。未改 README/docs。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| Agent Use Cases（Grok Bot 分类页） | https://agentusecases.ai/agents/grok-bot | **不知道拿 Bot 干什么时先逛这里**：每天从网页、X、Reddit、HN 抓真实的智能体用例，按智能体和主题分类，每条给用途、结果和可直接抄的提示词；Grok Bot 分类约 119 条（全站约 1,697 条），免费、可订阅每日 5 条。跨智能体通用目录，非 Grok Bot 专属；首页带赞助位。本轮最值得看 | Directories / Discovery | `directory` `use-cases` `prompts` `free` | 网站 / — | **X** @baozong_facai 2115725084145172578（约 9.5 万粉中文推荐）→ 网站 |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 铁柱 AGI：Codex / Claude Code 指挥 Grok Bot（skill + CLI） | https://x.com/cgnot996/status/2115722202712789476 | 一个 skill + CLI 让外部 Agent 列出账号下全部 Bot、单独派活收结果，支持跨账号 Bot 互相派活、外部模型当总指挥、中途把上下文交给 Bot 接着做；约 2 小时 34 赞 20 收藏。**尚未开源**（作者称看反响），先盯仓库地址，开源后再评 | Multi-bot / Orchestration | **X**（10-29） |

### Skip（本轮）

SvenKunkka/grokbot-byok-dsh-setup（DeepSeekBot BYOK 配置，主角非 Grok Bot，且含拆客户端 asar 内容）；NUSLCC/grokbot-robot-manipulation（仅标题 README）。X 侧 @GoldenCicada OKX Agentic Wallet 安装（钱包/交易类不收）、@0xburg3r 链上情报试水 Article、@caocaorich 链上项目助手 Article（链上类）、@panExorcist 投研盘前笔记（交易题材）、@fluixoo/@crbpite8 转述 200 agent 工程师帖、@AISystems_hq 订阅引流、@KuttyPrabhu webhook 三步（低粉、与官方功能说明重复）不收；@xiaomovps「从 0 到 1」新 Article 2115738442181333337、@KanikaBK「Hire Grok Bot」Article 交 X 雷达。

## 2026-10-29 20:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-29，看 16:00 后新建）+ X `search_posts_all`×1（自 18:00 起）。未改 README/docs。

### 推荐收录（待 Claude 核）

| 名称 | 链接 | 短评 | 建议节 | 标签 | Stars / License | 来源 |
|------|------|------|--------|------|-----------|------|
| tantan1hao/grok-multi-bot-workflow | https://github.com/tantan1hao/grok-multi-bot-workflow | **纯提示词的多 Bot 协作工作流（中文）**：Grok Bot 当总助和项目负责人，Codex / Cursor / Antigravity 当工程师；每个项目一份 TODO、派单保留原话并编号、送达/开工/验收/交付分别取证、独立验收绑定同一受检版本。仓里有 roles、flows、templates、DEPLOY 说明，不含服务端或密钥。作者自标实验性 v0.1.0、尚未做完整真实任务验收，短评里要带上这句。本轮最值得看 | Multi-bot / Orchestration | `multi-bot` `prompts` `codex` `cursor` `zh` | 0★ / MIT | **GitHub**（10-29 19:33 建） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| vexo-x1/agent-playbooks | https://github.com/vexo-x1/agent-playbooks | 每条玩法一页可复制模板、数字标出处；Grok Bot 页「Stop paying for empty runs」整理的是 @gippp69（7 bot 一个时钟）与 @unknownnode404 的 routine 审计提示词，原帖 docs 已收，只算二手汇编；目前仅 2 篇，等积累再看 | Routines / Cost | **GitHub**（10-29 18:05 建，无 License） |
| bubblav-org/bubblav-grok | https://github.com/bubblav-org/bubblav-grok | BubblaV 客服聊天机器人厂商的 Grok Bot / Grok Build 插件（远程 MCP + OAuth，无需 key）：查解决率、找答不上的问题、补知识库、装 widget；厂商自家产品插件，若开「第三方连接器」节可列，否则只作信号 | Connectors / Plugins | **GitHub**（10-29 19:58 建，MIT） |
| Pages 管多项目：一项目一页 | https://x.com/Michael_Fenech_/status/2115774649598705774 | 约 6 万粉作者：别拿聊天当项目管理，每个项目一张 Page 让 Bot 团队读写；刚发约 10 分钟，交 X 雷达看是否展开成长文 | Pages / Project mgmt | **X**（10-29） |

### Skip（本轮）

robinbril/grokbot-reconstruction（仿制本地工作区，非玩法）；nox1020/ai（离线仿 Grok Bot 安卓 app）；karloshagen/karlos-umbrel-apps、sbaluja10/snapgrok（与 Grok Bot 玩法弱相关）；falkoro/grok-bot-eu-translations、weritas247/util-grokbot-research（第三方资讯站翻译/韩文资讯站）；AgentConnect/matchall-plugins（商业插件源码）。X 侧 @CopperForgeAI 用 Cloudflare 隧道绕网络限制（涉翻墙，不收）、@HYhongyu8/@dxseyi3 段子、@crbpite8 转述对冲基金帖、@UncleKripro 低粉营销、@grok 自动回复、@free_ai_guides「官方 18 个 playbook」导读（转述官方，原文若未收交 X 雷达核）不收；@4ro_ro4 日文 Article 交 X 雷达。

## 2026-10-29 22:05 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-29，看 20:00 后新建）+ X `search_posts_all`×1（自 20:00 起）。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Zujiin01/the-bridge（「The Bridge」三部曲第 3 部） | https://github.com/Zujiin01/the-bridge | 服务器上一个文件夹当信箱：每个 Agent 一个收件箱、一条消息一个文本文件，回复带 `DONE` / `WIP` / `NEEDS-INPUT` / `BLOCKED` 状态和过期时间；Grok Bot 一侧靠小 watcher 调 webhook routine 唤醒，Claude 一侧用 Monitor 监听，实现两边互相派活、互相叫醒。README 把「消息内容只当数据、action 类一律回 NEEDS-INPUT 等主人确认」写成规则，安全意识好。但与第 1 部 mobile-server-connection 一样是 PolyForm 非商用许可，且需服务器文件夹读写权限，Claude 此前以同样理由拒过第 1 部，故只作信号 | Multi-bot / Webhook routines | **GitHub**（10-29 21:40 建，0★） |

### Skip（本轮）

samihalawa/grokbot（靠会话 cookie 多账号池化、额度 429 轮换，涉账号凭据与绕额度，不收）；lwhwayne/grokbot-pet-studio（实际是 ChatGPT/Codex 桌宠导出器）；austintoddj/office、yzqb/grok-bot-health、njm-cursor-x/webex-grokbot（仅标题或空 README）；adplug-app/adplug-hubspot-plugin（已在 inbox）、qualisend/agent-plugins（邮件验证厂商插件）。X 侧 @nitrosendx 系列转推（邮件营销推广）、@kinox1out / @scarfpinkgirl 标题党转述、@Zz_Zz114514 交易策略打假、@akentech_bit 每周额度审计 routine（38 粉，思路与已收审计提示词重复）、@zacshen 二手汇总、@GrokBotPro / @Blackprismgrp 低粉营销号不收；@Bowen2xiong「常驻 Bot vs Claude Code subagent」与 @wwwkkkhhh123321「冲订阅避坑」两篇中文 Article 交 X 雷达。

## 2026-10-30 00:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot" / multi-bot grok，created≥10-29，看 21:30 后新建）+ X `search_posts_all`×1（自 21:30 起）。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| SherryLi-vc/oral-to-prompt | https://github.com/SherryLi-vc/oral-to-prompt | **中文 Grok Bot / Cursor skill**：把口语命令改写成固定六段 system 提示词（角色定位 / 任务背景 / 总体目标 / 具体需求 / 输出风格 / 规则限制），明确「改写不代做」，带缺口追问和示例；README 里还混着改名记录、发布脚本和 logs 目录，像作者工作区直推，且刚建无 star，先作信号，等 README 收拾干净再看 | Skills / Prompting | **GitHub**（10-29 22:50 建，MIT） |
| hjpdebeer/spendpoint-plugin | https://github.com/hjpdebeer/spendpoint-plugin | Spendpoint 记账服务的 Cursor / Grok Bot 插件（远程 MCP + OAuth，无需 key）：拍收据入账、按类别问花销，金额由服务端算不靠模型心算；厂商自家产品插件，与 bubblav-grok 同类，若开「第三方连接器」节可列，否则只作信号 | Connectors / Plugins | **GitHub**（10-29 22:58 建，MIT） |

### Skip（本轮）

samihalawa/public-tender-grokbot-orchestrator-skill（无 README，作者上轮 cookie 池仓已拒）；njsilvestri21/grok-bot-office、njm-cursor-x/webex-grokbot（空 README）；ikeriano/* 三个西语综艺粉丝游戏（与玩法无关）。X 侧 @nitrosendx 系列推广转发、@fffuckingnerd/@ChadSE0 标题党转述、@GrokBotPro/@topbotcharts/@OutworkVentures 低粉营销号、@jiannannnn 方言 TTS+火柴人视频（15 粉）、@kkkeric_ai 外链库思路（回复帖无步骤）、@tutao0123 习惯清单（82 粉，与官方建议重复）不收；@doublenickk 2115831790191436182「睡前先设权限」（约 1.29 万粉，引用长文）交 X 雷达。

## 2026-10-30 02:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot" / grok multi-bot，created≥10-29，看 23:30 后新建）+ X `search_posts_all`×1（自 23:30 起）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| s87343472/backlink-pilot（v3） | https://github.com/s87343472/backlink-pilot | **给 Agent 跑的目录外链 playbook**：从「一条命令提交几百站」的 v2 脚本改写成控速版，每天 2–4 个真实提交、保守/标准/激进三档策略、邮件验证闭环、可复用站点台账；人看 README、Agent 读 `AGENTS.md`，并写清哪些步骤（DNS 验证、域名邮箱、付费位、强制互链）必须停下来问人；作者称 v3 目前只在 Grok Bot 上跑通。作者早前「一天 4000 站」长文已在 docs，这次是收敛后的开源版，可与之互链 | Growth / SEO playbooks | **GitHub**（MIT，约 381★，10-30 01:21 推 v3）+ X @sujingshen 2115854382176805079 |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Aaebraham/head-office | https://github.com/Aaebraham/head-office | 本机跑的 3D「办公室」看板：每个 Grok Bot 一张工位，显示工作中 / 需要你 / 已完成，Claude Code、Codex 也能接进来并在页面上批准权限请求；Grok Bot 一侧只读 Mac 客户端本地缓存、不写不外传，零 token。刚建 0★、仅 macOS，且依赖读客户端缓存（非公开接口，随版本可能失效），先作信号 | Multi-bot / Dashboards | **GitHub**（10-30 01:08 建，MIT） |
| njm-cursor-x/webex-grok | https://github.com/njm-cursor-x/webex-grok | Webex 插件：接 Cisco 官方消息 MCP（企业账号 OAuth，无需 key）读发消息，外加「用 bot 浏览器进 Webex 会议」skill；需 Webex 管理员先开 MCP。同作者上轮空 README 仓 webex-grokbot 的正式版，属连接器类，若开「第三方连接器」节可列 | Connectors / Plugins | **GitHub**（10-30 00:12 建，MIT） |

### Skip（本轮）

scartcher/GROKLAND（5 bot 跟单 Solana 聪明钱包，交易类不收）。X 侧 @wakabazz 两条中文帖为 grokbot-field-notes 二手解读（原仓已收）、@unicodef1wn「limit saver」引用自家已收长文、@irongiantXBT/@de1lymoon/@VK_ROXy/@L1vsun/@Blum_OG 标题党转述旧长文、@grok 自动回复、@AgentShorts/@mikelandau 产品预告、@ajroux_ 额度省钱清单（与已收审计思路重复）、@coder2048 回复帖、@lucassam888 价格对比 Article 不收；@d_j_harman「记忆分道：内置记忆 vs Drive REFERENCE」（刚发，链接未展开）、@thisisdjen「You need Grok Bot.」Article、@ivelini DGX Spark Article 交 X 雷达。

## 2026-10-30 08:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "Grok Bot"，created≥10-29，看 02:00 后新建/更新）+ X `search_posts_all`×2（自 18:00 UTC 起，中英）。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| bonorio/herald-for-grokbot（Herald） | https://github.com/bonorio/herald-for-grokbot | **给 Grok Bot 配的手机 PWA 前台**：Bot 扫邮箱/日历后，卡片进你自己 Cloudflare 账号的 D1；首页是简报 / 接下来 / 需要你 / 已处理，左右滑归档/稍后，聊天里点选回答；密钥走 Bot 安全箱 + webhook routine，不碰密码。自托管、`npm run setup` 一键部署。**无 License**、0★，本轮最值得看，请 Claude 判许可后再定是否进 README | Channels / Mobile UX | **GitHub**（10-29 22:34 建） |
| codejunkie99/grok-bot-code-agents | https://github.com/codejunkie99/grok-bot-code-agents | 把「派 Codex / Claude Code 云会话 / OpenCode」三套 skill 打成一仓 + 一条安装提示词；Codex 段源自已在 inbox 的 realTaki/bot-codex-delegate（保留上游 MIT），Claude/OpenCode 为另写。作者称未在 Grok Bot 端到端实测，先作信号，避免与 realTaki 条目重复堆 | Skills / Delegation | **GitHub**（10-29 21:35 建，MIT） |
| LofiSu/grok-export-tool | https://github.com/LofiSu/grok-export-tool | **本机导出自己的 Grok Bot 与普通 Grok 对话**：读本机已登录浏览器 cookie（macOS Keychain / Windows DPAPI），CLI + 零依赖 MCP + agent skill，写出 JSONL/Markdown 归档；不发新消息、不要 API key。中英 README。读 cookie 属敏感能力，与已收 agent-cookie-sync 同向，先信号 | Skills / Backup | **GitHub**（10-29 11:50 建，MIT，1★） |
| dtredwing1/bot-team-dashboard | https://github.com/dtredwing1/bot-team-dashboard | 公开只读的多 Bot 团队看板（静态 `bots.json` + 隐私检查脚本，可 Cloud Run）；演示「把编制/亮点/可抄想法摊出来给人看」的做法，非通用框架。**无 License**、0★，先信号 | Multi-bot / Dashboards | **GitHub**（10-29 22:59 建） |

### Skip（本轮）

bobbyhalljr/grok-bot-template-output-check（教学用 TypeScript 合约校验，非玩法）；厂商 MCP 插件堆（baselam88/kairos-* 带评估 CTA、bluuulabs/bluu-plugin、OneNine-Design/perfect-mail-plugin、scratchpad-ai/frame-plugin、Reits0/forthclear-plugin）与已信号的 bubblav/spendpoint 同类，本轮不堆；yzqb/grok-bot-health、samihalawa/public-tender-grokbot-orchestrator-skill（上轮已拒作者/空仓）不收。X 侧大量 Auto-review 故障帖、@BIGMayrr 转述已收 @gippp69 七点、@tezzarc Bookmarks Librarian（95 粉）、对冲基金复制帖、@rosemoni18 买站营销不收；@doublenickk 链上调查长帖、@zhulizhong headless Article 交 X 雷达。

## 2026-10-30 10:07 Asia/Shanghai · 白天玩法雷达

> 按 full_name / 链接与 README、docs/*.md、inbox/candidates.md、.collab 比对无重复。`gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-29/10-30）+ X `search_posts_all`×3（自 00:00 UTC ≈ 08:00 Asia/Shanghai）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| CodeVelo/inbox-sentry（Inbox Sentry） | https://github.com/CodeVelo/inbox-sentry | **免费 Grok Bot 模板：只读盯 Outlook/Hotmail 里的提示词注入**。假指令、隐藏文字、毒日历/名片、仿冒品牌告警等打进「Sentry Review」并标 Block/Suspect/Note；人回 `right`/`wrong`/`missed one` 教它。有一键 Install 链、红队报告（19/20 合成 + 4/4 实邮、从不执行注入）与 MIT 文档仓。本轮最值得看 | Skills / Security templates | **GitHub**（10-30 01:12 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| chennian080403/gbc | https://github.com/chennian080403/gbc | **中文：Grok Bot 一句话（或语音）派活给 Mac 前台 Claude Code**。`gbc send` 一次发话→等完→取回复；上下文到线自动交接换新对话；`doctor` 自检。装 curl\|zsh。与已有 Claude 桥同向但偏终端遥控、强调一次拿回结果。**无 License**、0★，先信号 | Skills / Claude Code bridge | **GitHub**（10-30 01:08 UTC 建） |
| YourAKShaw Grok Bot Power User Crash Course（gist） | https://gist.github.com/YourAKShaw/5a5af3f19197d5a4fc0d24c84f71dd65 | 2026-10 工程师向长文笔记：从首 Bot、多 Bot/群聊、Skills/Routines、连接器到审批与记忆；可作 Learning 入口。非仓、无独立许可声明，先信号交 Claude 判是否短链 | Learning | **Web**（gist，本窗 WebSearch） |

### Skip（本轮）

Aditya-chouhan/grokbot-gtm-team（明确改编自已在 README 的 timscheuerai/grokbot-gtm-team，不重复堆）；BrysonS30/clean-reply-desk（某业务私有知识库，非通用玩法）；bitman1024/grokbot-wecom-bridge、Loera21/cybertruck-grokbot（空仓）；crawlbaby96/bot-office（3D 办公室，与已 skip 的 IVMYM/bot-office、已信号 head-office 同类）；厂商插件/空 README/交易跟单续观。X 侧 @TrivioAI 付费 playbook、@12_MgCapital/@WY_mask Agentic Wallet/打新复制帖、OpenMausBot/rakazo 二手安利（原仓已收）、@santoslee_me 多 Bot 分工 10/10（61 粉，交 X 雷达）不收。

## 2026-10-30 10:39 Asia/Shanghai · T7 日更雷达

> 近 24h `gh search repos`（grokbot / grok-bot / "grok bot" / grok-bot-template / grokbot skill，created≥10-29 与 updated≥10-29），按 full_name 与 README、docs、inbox、.collab 去重；X 侧本窗已由 08:07/10:07 白天雷达与 X 大 V 雷达覆盖，不重复列。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| k7cfo/remove-your-data | https://github.com/k7cfo/remove-your-data | **把 URL 丢给 Bot 就能跑的隐私清理 skill**：自动向人肉搜索站/数据经纪商走官方 opt-out（加州先走 DROP），本地 SQLite 留法律记录，聊天里出状态卡（卡片不含地址电话等隐私）。README 点名 Grok，Apache-2.0、约 62★，10-29 仍在更新。本轮最值得看 | Skills / Privacy | **GitHub**（08-29 建，10-29 推送） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| VirusPC/open-grokbot | https://github.com/VirusPC/open-grokbot | **中文学习仓：用 Cloudflare Agents + Think 复刻「主助手派活 / 并列同事 / Skills / 记忆 / 心跳 routine / webhook」**，附概念对照表与架构、学习顺序文档；声明不兼容任何专有协议。**无 License**、0★，先作 Learning 信号 | Learning / Architecture | **GitHub**（10-29 建） |

### Skip（本轮）

ravin-technology/shared、hackstoic/grokbot-wecom-bridge（空仓）；baselam88/kairos-*、basilaia123/tbc-get-exchange-rates（厂商/单用途插件，同前轮不堆）；Prasanth595/OpenMausBot（镜像，原仓已收）；trevor93/Open-Grok-Bot、TechWithEmmaYT/AI-Grok-Bot-Clone、ikeriano/*、Ocean-lhy/*、Apenguin72/phone-versus、Kalfad18、mammut001/parlemiao-feed、danielamaldas-bot/muse_13th_year、dehuamading PRD（克隆/个人产出/测试仓，非可复用玩法）。

## 2026-10-30 12:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-30）+ X `search_posts_all`（自 02:00 UTC ≈ 10:00 Asia/Shanghai），按 full_name / 链接与 README、docs、inbox、.collab 去重。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| number5meme/grokbot-larkbot-bridge | https://github.com/number5meme/grokbot-larkbot-bridge | **Lark（飞书国际版）自建应用 Bot 接 Grok Bot routine webhook**：官方 Lark Node SDK 长连接、纯出站（无需公网 IP/域名/证书），私聊与群里 @ 的文本/图片/文件/音视频转 JSON 给 webhook，`reply.sh` 以 Bot 身份回文本/图/文件；owner 保护、自恢复、离线测试。与 inbox 里同作者 wechatclaw/qqbot 两桥同一套 payload，可与 recheck 一并核；与已在 inbox 的 wchengyen/feishu-grokbot-bridge 同向，差异在面向 Lark 国际域名、支持媒体回发。本轮最值得看 | Bridges / IM | **GitHub**（10-30 03:26 UTC 建，MIT，1★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| PhillipHolland/perimeter-sentinel | https://github.com/PhillipHolland/perimeter-sentinel | 开源线上站点值守控制台 `perimeterctl`（看 → 发现漂移 → 出变更卡 → 冻结演练），配一个按用户定制安装的 Grok Bot；明确只出草稿（`sent: false`）、不持钥不动资金、不扫未声明资产。Apache-2.0、0★、刚建，Grok Bot 部分是否为主要用法待核，先信号 | Security / Ops templates | **GitHub**（10-30 03:23 UTC 建） |

### Skip（本轮）

brandonlee-lomtech/grok-bot-virtual-background（会议虚拟背景生成器，非 Bot 玩法）；rishi4500/rishi4500.github.io（仅公钥页）；hackstoic/bitman1024 wecom-bridge、Loera21/cybertruck-grokbot（空仓，前轮已 skip）；flaqai/backlink_skills（通用外链 skills，非 Grok Bot 专属，同向 backlink-pilot 已在 inbox）。X 侧 @istupidpreneur / @YangXiaoka / @aboutgis Article、@AgentLabTuts facts file 小技巧、@The_Astronaut18 YNAB 多 Bot 记账交 X 大 V 雷达；@ai_chuhai 退款/外链帖（同作者前轮已拒）、@lucky66786678 CCNetKit 推广、币安/交易类不收。

## 2026-10-30 14:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grok-bot skill，created≥10-30）+ X `search_posts_all`（自 04:00 UTC ≈ 12:00 Asia/Shanghai），按 full_name / 链接与 README、docs、inbox、.collab 去重。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| sysrex/peerline | https://github.com/sysrex/peerline | **跨账号 bot↔bot 消息中继（Go）**：个人 Grok Bot ↔ 工作 Grok Bot、你的 Bot ↔ 同事的 Bot，默认全拒，双方配对并授权 scope（messages / bags 读写）后才通；≤4 KiB 消息 + 可选命名小数据包（≤64 KiB，ETag），不做记忆同步或批量导出；仓内带 `skill/` 目录与 Dockerfile。思路正好补「多 Bot 跨人协作」空位。**无 License**、0★、刚建，先信号。本轮最值得看 | Multi-bot / Bridges | **GitHub**（10-30 05:23 UTC 建） |
| az9713/grokbot-enterprise-tutorial | https://github.com/az9713/grokbot-enterprise-tutorial | 把「Grok Bot for Enterprise Teams」55 分钟工作坊（YouTube，10-29）整理成图文教程站（GitHub Pages），含架构图与交互式客服流程模型；第三方整理、**无 License**，原视频是否适合直接收进 Learning 待核 | Learning / Enterprise | **GitHub**（10-30 05:57 UTC 建） |

### Skip（本轮）

oleewen/grok-bot（本地聊天缓存提取 CLI，非 Grok Bot 玩法）；shagghiesuperstar/grokbot.zone（空仓，Bot 目录站未上线）；Aditya-chouhan/grokbot-gtm-team、BrysonS30/clean-reply-desk 已在 inbox；前轮已 skip 的空仓/克隆仓不重复列。X 侧 @SamAiPr 比价 routine 四步、@SCrypt22 一 Bot 一职、@sitin_dev Teach a task、@huahuadaren2023 Article 交 X 大 V 雷达；@ai_chuhai 「Grokbot 专用」系列（同作者前轮已拒）、空投/交易类不收。

## 2026-10-30 16:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot"，created≥10-30）+ X `search_posts_all`（自 06:00 UTC ≈ 14:00 Asia/Shanghai），按 full_name / 链接与 README、docs、inbox、.collab 去重。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| yc5991/zzz-bot-skill | https://github.com/yc5991/zzz-bot-skill | **一句「拉取并配置这个项目」让主 Bot 读根目录 `AGENT.md` 批量建档**：69 个角色 Bot（名册、人设、头像、资料库上传）、按势力自动拉群、每个角色一条主动聊天 routine（含 bot↔bot 私聊），记忆走原生记住/忘掉。可复用的是「AGENT.md 驱动批量建 Bot + 群 + routine」的仓库结构。同人内容、CC BY-NC-SA 4.0、带官方头像（第三方版权见 NOTICE），且 69 条 routine 额度消耗大；本轮最值得看，先信号，请核是否只作「批量建队模板」思路引用 | Multi-bot / Templates | **GitHub**（10-30 07:38 UTC 建，0★） |

### Skip（本轮）

NafYoung/GrokBot-Office（等距办公室可视化，本地 curl 事件，与前轮已 skip 的 bot-office 同类，3D/可视化办公室交 X 雷达盯 @btcup99 Article）；tarun922/Buddy.live（桌面编码伴侣，非 Grok Bot 玩法）；mhussain-codes/grok-bot-terminal（空仓）。X 侧 @usehooo 营销小队 Article、@VarunChopr17597 15 Setups Article、@Michael_Fenech_ routine 简化审计、@Mulight 省额度、@AgentLabTuts 存 skill 小技巧交 X 大 V 雷达；@viettranxuan UI UX Pro Max 转述、@CheLong777 日榜（OpenMausBot 已收）、币安打新/链上结算推广不收。

## 2026-10-30 18:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grok-bot skill / grokbot routine，created≥10-30），按 full_name 与 README、docs、inbox、.collab 去重。本轮 X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| ExpeditedProjects/grokbot-wakeword-releases | https://github.com/ExpeditedProjects/grokbot-wakeword-releases | **Grok Wake：macOS 菜单栏唤醒词，一个 Bot 一句「hey 名字」直接开语音聊天**。语音识别全在本机、不上传音频，通话中自动停听；需麦克风、语音识别和辅助功能权限（用来按 Grok Bot 的语音按钮）。补「多 Bot 语音直达」空位。**仅发布页 + 预编译 zip，未见源码**，需辅助功能权限，请核来源可信度再决定收不收。本轮最值得看 | Desktop / Voice | **GitHub**（10-30 09:51 UTC 建，MIT，0★） |
| letmefind/replica-skill-cursor-grok | https://github.com/letmefind/replica-skill-cursor-grok | 「按步骤复刻一个 App」的 12 个 skills（recon / architect / design / build / backend / test / diff / launch / deploy 等 + 总控 `replica`）移植到 Cursor 与 Grok Bot，强调 clean-room 不拿目标代码/素材；原作 Jakeschincariol/replica-skill，第三方移植。MIT、0★，请核 Grok Bot 侧装法是否可用 | Skills / Build | **GitHub**（10-30 08:12 UTC 建） |

### Skip（本轮）

b2bsearch/b2bsearch-plugin（按条付费的 B2B 数据插件推广）；aikeluargalee-tech/btc-swing-engine、akari-sora/aave-oracle-lag-arb（交易/套利类不收）。

## 2026-10-30 20:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grokbot skill / grok bot routine，created≥10-30，取 09:30 UTC 后新建）+ X `search_posts_all`（自 09:30 UTC），按 full_name / 链接与 README、docs、inbox、.collab 去重。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| zenvor/grokbot-avatar-gallery | https://github.com/zenvor/grokbot-avatar-gallery | **中文：20 张 Grok Bot 风格人物头像 + 逐张实际提示词 + 「上传照片转同风格」模板**，`avatars.json` 结构化列出，适合给多 Bot 队伍统一换头像。趣味向，与已在 inbox 的 maid-avatar 提示词同方向但带成品图与 JSON 清单；**未声明 License**、0★，先信号。本轮最值得看 | Fun / Avatars | **GitHub**（10-30 11:41 UTC 建） |

### Skip（本轮）

SiteWarming/sitewarming-grok-bot-plugin（停放域名养站的商业 MCP 插件，需付费账号，推广性质）；snbwallet365-ops/grokbot-ai-agent（签证顾问 Next.js+Mistral 应用，与 Grok Bot 无关）；sysrex/subspace（空仓，作者即 peerline，盯）；wangsen2020/grok-bot-bridge 已在 inbox。X 侧 @Juanmao_shaw 导出用量 CSV 体检省额度模板、@MartinBarna333 routine 失败写共享日志由主 Bot 补跑、@AgentLabTuts/@BertholdGlass 邮箱触发 routine 小技巧交 X 大 V 雷达；@happy20250912 GamsGo 合租推广、Uquid 订阅推广不收。

## 2026-10-30 22:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grokbot skill / grok bot routine / multi-bot grok，created≥10-30，取 11:30 UTC 后新建），按 full_name 与 README、docs、inbox、.collab 去重。本轮 X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| 4zhmv6zvj2-afk/grokbot-essay-writer | https://github.com/4zhmv6zvj2-afk/grokbot-essay-writer | **一段粘贴提示词装好「Essay Bot」**：从 `docs/templates/essay-bot.share.json` 导入 Bot 模板，按阶段查论文（Consensus API + Unpaywall）、按来源起草、对照作业要求自检，每阶段聊天里 Confirm 后才落盘，出 Harvard 引用的 Word。可复用的是「share.json 模板 + FIRST-RUN 分阶段确认」的装 Bot 结构；需第三方 API key、学术用途请核表述（研究辅助而非代写）。本轮最值得看 | Templates / Research | **GitHub**（10-30 13:51 UTC 建，MIT，0★） |
| Alexgao/agent-collab | https://github.com/Alexgao/agent-collab | 中文：Grok Bot 调度建任务卡 → Codex 独立分支开发自测 → Claude Code 只读审查 → 人工批合并/部署/密钥的半自动闭环，`TASKS/` + `AGENTS.md` 约定。思路完整但仓很薄（只有约定文档），0★，先信号，看是否并入「多 Agent 协作」配方条目做参考 | Multi-agent / Collab | **GitHub**（10-30 13:51 UTC 建，无 License） |

### Skip（本轮）

zhangteng945/grokbot-apk（个人重打包 Android 安装包，来源不明不收）；lihaihong2026/grok-bot、thejasbp0-alt/Grok-bot-Alternative（空仓/仅标题）；sysrex/subspace 仍空仓（已在盯）。

## 2026-10-31 00:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grokbot skill / multi-bot grok，created≥10-30，取 13:30 UTC 后新建），按 full_name 与 README、docs、inbox、.collab 去重。本轮 X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Insilico-org/plsi | https://github.com/Insilico-org/plsi | **一个主 Bot + 八个常驻 Bot + 按需专家 Bot 的完整多 Bot 队伍样板**：orchestrator 对用户，Data Processor / Reviewer / Challenger 等各有独立聊天与记忆，侧栏分组、按角色（`plsi role set`）加开 Clinic / Lab 分区，Bot 间有交接协议，配套 CLI 工具与 skills。领域是个人健康数据（去标识化），收录时只取「多 Bot 编队 + 交接协议」结构，**勿写成医疗建议**；MIT、0★、仓刚建请核内容完整度。本轮最值得看 | Multi-agent / Team templates | **GitHub**（10-30 15:00 UTC 建，MIT） |
| pyrider3/grok-bot-squad | https://github.com/pyrider3/grok-bot-squad | 中文：Linux 状态栏「Bot 小队」插件，工作中的 Bot 头像探头、点开就地聊天、未读提示，有演示 GIF/录屏。依赖 niri + Noctalia 桌面 shell 和已登录的桌面应用，通过本地桥接投递消息；受众窄、属非官方桥接，请核安全性再决定 | Desktop / Fun | **GitHub**（10-30 14:22 UTC 建，MIT，0★） |
| Agent-Analytics/awesome-grok-bot-pages | https://github.com/Agent-Analytics/awesome-grok-bot-pages | 英文 Awesome 列表，专收公开可访问的 Grok Bot Pages（仪表盘、追踪器、报告），每条要求署名并附生成提示词，分类对齐插件类别。可作「相关 Awesome 列表」互链；维护方是分析类产品，请核是否偏推广 | Related lists | **GitHub**（10-30 14:37 UTC 建，CC0，1★） |
| Yinmu/grok-bot-handbook | https://github.com/Yinmu/grok-bot-handbook | 英文按症状排查手册：routine 跑晚、电脑连不上、模板导入后 skills 丢失、插件授权失败、额度烧太快、Bot 不守规则、安全清单。实用但由第三方站点 boterly.si 维护、仓内同步其博客，有导流性质，请核内容准确度 | Troubleshooting | **GitHub**（10-30 14:05 UTC 建，CC-BY-4.0，0★） |

### Skip（本轮）

dealrinc/dealr-cloud-plugin（经销商业务 MCP 商业插件）；b2bsearch/contact-finder（联系方式挖掘推广插件，同作者此前已 skip）；michaeltarleton/GrokBotMT、ParkerQIV/Grokbot-Assets（空仓）；thejasbp0-alt/Grok-bot-Alternative 已 skip。

## 2026-10-31 02:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grokbot skill / multi-bot grok / grok bot routine，created≥10-30，取 15:30 UTC 后新建），按 full_name 与 README、docs、inbox、.collab 去重。本轮 X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| evyevans/content-engine-grokbot | https://github.com/evyevans/content-engine-grokbot | **一句话装好的短视频内容团队**：1 个协调 Bot + 12 个专员 + TikTok/IG/YouTube 三个平台群聊 + 独立缩略图 Bot；把仓库链接和一段安装提示词发给 Bot，按 `skills/setup-content-engine/SKILL.md` 问清赛道/受众/时区后建队、校验成员权限，routine 测试期保持暂停，**只出草稿、人工发布**。结构完整（agents/playbooks/templates/tests），可做「多 Bot 内容团队」样板。本轮最值得看 | Team templates / Content | **GitHub**（10-30 16:22 UTC 建，MIT，0★） |
| robzilla1738/grokbot-gateway | https://github.com/robzilla1738/grokbot-gateway | 非官方 CLI + MCP：让 Claude Code/Codex/Cursor 等外部 coding agent 给自己的 Grok Bot 发消息、读回复、经 Tailscale SSH 进云电脑。与已在 inbox 的 grokbot-notch 同作者同桥接思路。**安全风险高**：读取桌面端登录会话与钥匙串密钥、调用内部接口，token 等同密码；只宜作「跨 Agent 互通」信号，收录需明示非官方与风险，或不收 | Multi-agent / Bridges | **GitHub**（10-30 16:41 UTC 建，MIT，0★，已发 npm） |

### Skip（本轮）

b2bsearch/b2b-leads-finder（联系方式挖掘推广插件，同作者此前已 skip）；arsenikqq/grokbot-100（仅一个 index.html）；thepodemail-lgtm/grokbot-gtv-simulator（电视客服模拟器，与 Grok Bot 玩法无关）；ikeriano/uno-para-ganar-3d-grok-bot（粉丝小游戏，无关）。

## 2026-10-31 08:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "Grok Bot" / grokbot skill / multi-bot grok / grok bot routine，created≥10-30，取约 16:41 UTC 后新建；另补漏此前窗口漏掉的 janreges/safe-grokbot-bridge）+ X `search_posts_all`×2（自 18:00 UTC ≈ 02:00 Asia/Shanghai，中英 + `url:github.com`）。按 full_name / 链接与 README、docs、inbox、.collab 去重。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| rannes/grokbot-botmarket | https://github.com/rannes/grokbot-botmarket | **自托管 Grok Bot 模板/配方市场**：SQLite 单文件、无外部服务；支持官方 template 深链一键 Add，以及开源 `grokbot-recipe/v1` JSON（记忆/skills/routines 暂停创建/plugins 需再确认）；`/submit` 发布、可选审批、Docker/Compose、Vitest。社区/团队自建目录的完整样板。本轮最值得看 | Templates / Self-hosted catalogs | **GitHub**（10-30 19:50 UTC 建，MIT，0★） |
| janreges/safe-grokbot-bridge | https://github.com/janreges/safe-grokbot-bridge | **有鉴权的本机桥**：Cloudflare Tunnel + bearer token + 限速/锁定，给云端 Grok Bot 窄权限 HTTP API，可读限定文件夹/git、列/启/驱动本机 Claude Code·Codex·Hermes（tmux/headless）；OpenAPI + skill 目录 + CI。相对已在 inbox 的 grokbot-gateway（读桌面会话密钥）更偏「安全远程协调」；README 明确警告勿跑主工作机。前几轮 created 窗口漏收，本轮补。MIT | Bridges / Multi-agent | **GitHub**（10-30 08:39 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| tradersnow222/gainzbot | https://github.com/tradersnow222/gainzbot | 开源健身/营养教练 Bot：**脚本强制护栏**（不可能工具、plan_check/readiness_screen 校验、人类确认后才改计划，含大量 pytest）。可复用的是「护栏脚本 + 人闸」结构，**勿当医疗/训练建议收录**；MIT、0★ | Skills / Safety patterns | **GitHub**（10-30 18:38 UTC 建，MIT） |
| shamilkotta/ai-usage | https://github.com/shamilkotta/ai-usage | macOS 通知中心小组件：一眼看 Claude / Codex / Cursor / **Grok Bot** 额度百分比与重置时间；读本机已有登录（Keychain/`state.vscdb`），不另要 key。**无 License**、0★，先信号 | Desktop / Usage | **GitHub**（10-30 18:22 UTC 建） |
| how-to-ai-co/301-build-recipe-agents | https://github.com/how-to-ai-co/301-build-recipe-agents | 工作坊材料：粘贴一条 recipe 进 Claude Code，对比 Muse/Instinct/Grok Bot/dots/Claude Duet，写出幕僚长 brief + 审批规则 + 六份 standing jobs。含 research/playbook/templates。**无 License**，可作 Learning 旁链 | Learning / CoS | **GitHub**（10-30 22:41 UTC 建） |
| JonathanT10/grok-bot-client-vault-template | https://github.com/JonathanT10/grok-bot-client-vault-template | 给小客户交付用的 **Obsidian 客户 vault 模板**：GROK.md 操作规则、Onboarding 清单、Reference/Skills/Team 角色、无密钥进仓。描述写「selling」但结构可复用为一人公司交付底板。**无 License**、0★，先信号 | Chinese solo-founder / Delivery | **GitHub**（10-30 21:03 UTC 建） |

### Skip（本轮）

digitalgym/office-voice-xero-plugin（Xero 收款商业 MCP 插件）；EmpressHeavy/DogeUpdates、BotTerminatorUpdates（梗图 Bot 更新源）；Corvax50/grokbot-office（个人像素办公室看板，与已信号 head-office / whatsmyagentdoing 同向）；ThatOneKid842/grokbot-dashboard、SimonWorku1/bot-dashboard（空/仅壳）；cesarfavero/LoopVero（Harness 静态逆向研究，合规风险不收）；embwl0x/native-agent、gabe-mobius/next-mission（旧仓/非本窗新建）；X 侧 @dannyshmueli 推已收 awesome-grok-bot-pages、@odwyer_richard 链 DeepSeek Harness（已有生态）、交易/Binance 逆向帖、低粉 tip 帖不收。

## 2026-10-31 10:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grokbot skill / grok bot routine / grok bot template / multi-bot grok，created≥10-30，取约 23:30 UTC 后新建），按 full_name 与 README、docs、inbox、.collab 去重。本轮 X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| steve972671/grok-bot-global-rules-template | https://github.com/steve972671/grok-bot-global-rules-template | **多 Bot 共用「全局规则」模板**：主 Bot 维护一份规范 `global-bot-rules.md` + Canvas Page，长规则拆成短 memory 防截断，SHA-256 校验防漂移，再把逐字节相同的副本分发给每个队友并回报 `MATCH`。PROMPT.md 一段粘贴即用，examples 全是占位规则。多 Bot 团队治理的干净样板。本轮最值得看 | Team templates / Governance | **GitHub**（10-31 01:05 UTC 建，MIT，0★） |
| nwcnwc/android-assist-bot | https://github.com/nwcnwc/android-assist-bot | **安卓版「一键问 Bot」**：长按助手手势，语音提问 + 当前链接/屏幕文字/临时截图 POST 到 Grok Bot routine webhook，Bot 在自己的对话里回答并推送通知。125 KB APK、公开签名指纹、README 写清 webhook 配置。是 iPhone Action Button 玩法（docs 已收多条）的安卓对照 | Mobile / Webhook routines | **GitHub**（10-31 00:33 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| pyrider3/wingman-codex-control | https://github.com/pyrider3/wingman-codex-control | 基于已收 juangurdian/wingman 的中文扩展：Grok Bot 经本机 MCP 管理同机多账号 Codex 桌面会话（追加指令/停止/续跑），任务完成后持久队列回报给发起 Bot，防重发。依赖内部 IPC/SQLite 字段，版本敏感；同作者 grok-bot-squad 已在 inbox。可作 README wingman 条目的旁链 | Bridges / Multi-agent | **GitHub**（10-31 01:54 UTC 建，MIT，0★） |

### Skip（本轮）

0sm0s1z/grokbot-cxn-shim（改本地拷贝的 Grok Bot 客户端把对话路由到第三方模型，客户端改造+明文日志，合规风险不收）；Logos52/grokbot-office（仅编译产物无源码，与已信号 bot office 同向）；EmpressHeavy/BotTerminatorUpdates、PlaylistConverterUpdates（Bot 更新源）；SimonWorku1/bot-dashboard、kristinapavlicek/grokbot（空/仅壳）。

## 2026-10-31 10:50 Asia/Shanghai · T7 日更雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / skill / routine / template / multi-bot / agent，created≥10-30），按 full_name 与 README、docs、inbox、.collab 去重；X 公开搜索近 24h 仅低互动帖，交 X 大 V 雷达。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| NathanAMeeks/grokbot-token-efficiency | https://github.com/NathanAMeeks/grokbot-token-efficiency | **长跑 Bot 省额度规则**：作者 7 天用量报告里聊天占大头、routine 占小头，于是定规：单一短 `STATUS.md` 当事实源（原地改、不追加），大输出落文件只回一行摘要，快查内联、重活后台，研究类 routine 设约 1% 日额度上限并断点续跑；附 STATUS / routine_prompt 模板与 RESEARCH.md。和雷达类 routine「无货静默」思路互补。本轮最值得看 | Usage / Routine hygiene | **GitHub**（10-31 02:14 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| mikebeee/Speakling-for-Grok-Bot | https://github.com/mikebeee/Speakling-for-Grok-Bot | Windows 上把 Divoom MiniToo 音箱屏变成 Grok Bot 的像素脸：按系统音频响度对口型、免 key 天气、节日装扮。纯硬件趣味，非官方；可作 Desktop / Fun 旁链 | Desktop / Fun | **GitHub**（10-30 18:01 UTC 建，MIT，0★） |

### Skip（本轮）

adplug-app/adplug-linkedin-ads-plugin、adplug-google-ads-plugin（商业广告平台插件）；Bearwithme2/botsket-plugin（商业购物搜索 MCP，保留 90 天查询）；iamasuperuser/Ninjapipe-plugin（单一 CRM 的 API 包装，需 key）；EmpressHeavy/PlaylistConverterUpdates（Bot 更新源）。X 侧 @bggg_ai「本地跑收集再经 webhook routine 交给总管 Bot 省额度」、@nnnnrfx 每周记忆备份到 Drive 等均低互动，先不收。

## 2026-10-31 12:10 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / skill / routine / template / multi-bot / agent，created≥10-31，取 02:00 UTC 后新建），按 full_name 与 README、docs、inbox、.collab、examples 去重。X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| ZensHQ/call-grokbot | https://github.com/ZensHQ/call-grokbot | **从 Codex / Claude Code 直接调用你已有的 Grok Bot**：本地 stdio MCP，发一个自包含任务、增量读回复、可打断；Bot 保留原对话、记忆和连接工具。登录委托官方 Cursor CLI `agent login`，不收密码/不往配置里抄 token，可设 bot 白名单；附中文 README。作者明写非官方、走未公开 RPC 可能失效。与已收 grokctl（桌面 UI 自动化）、Grok Bridge（社区 CLI）同向，本仓鉴权更干净。本轮最值得看 | Bridges / Claude Code & Codex | **GitHub**（10-31 03:46 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| asasds145/claude-bridge | https://github.com/asasds145/claude-bridge | Cloudflare Workers 远程 MCP（OAuth 2.1 + GitHub 本人校验）：Claude 调 `send_to_chief` 入 Durable Object 队列，webhook 只发待办数（不带正文）唤醒 Grok Bot「Chief」，Bot 经鉴权 API 取件回复，Claude 长轮询 `wait_for_reply`；限频 60 次/小时 + 退避重试。与 inbox 已记 Claude2GrokBot、aipmer/codex-grok-task-bridge 同架构，可作旁链 | Bridges / Multi-agent | **GitHub**（10-31 03:26 UTC 建，MIT，0★） |
| travelmocca/grok-bot-voice | https://github.com/travelmocca/grok-bot-voice | **中文 skill：任务完成语音播报**——仅委托任务完成时在 Mac 外放「钉钉」+ 一两句口语摘要，闲聊/问意见不播；edge-tts + afplay 优先，带降级通道。小而实用，无 License | Skills / Desktop | **GitHub**（10-31 03:16 UTC 建，无 License，0★） |
| ImAno177/cstack | https://github.com/ImAno177/cstack | 把本地 skills + 上游 pstack / Ponytail 打包成一个可装插件，同时是 Grok 插件市场（`.grok-plugin/marketplace.json`），Grok Build `grok plugin install` 后 Bot 电脑共用；GitHub Actions 每日同步上游。个人技能栈，无 License，先信号 | Skills / Plugins | **GitHub**（10-31 03:31 UTC 建，无 License，0★） |

## 2026-10-31 14:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / skill / routine / multi-bot / agent template / war room，created≥10-31，取 03:40 UTC 后新建），按 full_name 与 README、docs、inbox、.collab、examples 去重。X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| DoubleDipCode/grokbot-t3-bridge | https://github.com/DoubleDipCode/grokbot-t3-bridge | **编码任务结束回调唤醒 Bot，不再轮询**：Grok Bot 经 T3 Code 远程 MCP 开线程派活给 Codex / Claude Code，worktree 里放 `.grokbot` 标记，harness 的 Stop hook 跑 `notify.sh` 把状态 POST 到对应 Bot 的 webhook routine，Bot 醒来只读最新消息再报 PR / 答问 / 升级。附 ONE-SHOT-PROMPT.md 让自己的 Bot 按规格重写脚本、密钥本人填。省掉 10 分钟一轮重读线程的额度。本轮最值得看 | Bridges / Routine（webhook） | **GitHub**（10-31 05:01 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Ryans-apps/appy-meal-kit | https://github.com/Ryans-apps/appy-meal-kit | 「Appy Meal」Bot 模板的配套文件仓：模板带不了文件，就把离线 PWA 脚手架、示例（替代订阅的象棋/习惯/白噪音、合并食谱+购物清单）和打 APK 工具放公开仓，Bot 首次构建时拉取。「模板 + 外挂素材仓」的做法可作模板区旁链 | Templates | **GitHub**（10-31 04:32 UTC 建，MIT，0★） |
| Yellow5A5/Grok-Bot-Skin | https://github.com/Yellow5A5/Grok-Bot-Skin | macOS Grok Bot 换肤：菜单栏切皮肤、Skin Studio 预览导出、侧栏显示本账期额度用量；经本机回环调试端口注入 CSS，不改签名 app、不上传数据。非官方，中英 README；调试端口注入有随版本失效风险，先信号 | Desktop / Fun | **GitHub**（10-31 04:07 UTC 建，MIT，0★） |

### Skip（本轮）

tao-inc/alibihour-grok、hushword-grok、passlane-grok、sonarlex-grok、unsaid-grok（同一公司批量上架的游戏/题库插件）；pallasite-ai/pallasite-plugins（商业产品插件包）；izzbe/chat2z（与 Grok Bot 无关的 Cloud Run 多 bot 聊天）。

## 2026-10-31 18:10 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grok skill / routine / plugin / multi-bot / war room，created≥10-31 06:30 UTC），按 full_name 与 README、docs、inbox、.collab、examples 去重。X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| YeJe-cpu/grok-eats | https://github.com/YeJe-cpu/grok-eats | **让 Grok Bot 在云电脑浏览器里点美团外卖**：读近期订单给三个候选、手动勾最大红包、从地址簿切地址确认后推到收银台，人只在手机付款；附实测截图（咖啡与晚饭两单）、热量区间简报，中英 README。美团外卖无个人下单接口，走 H5 网页。本轮最值得看 | 生活 / 浏览器 Skill | **GitHub**（10-31 09:19 UTC 建，MIT，0★） |
| BeatAPI/grokbot-growth | https://github.com/BeatAPI/grokbot-growth | 中文出海增长 Bot 舰队开工包：一个 skill 先问产品/市场/渠道，再生成总管 + 社媒、SEO/AEO、外链、竞品、热点、视频本地化等岗位说明、共用规则、审核表与第一周开工清单；建 Bot、连账号、批首批内容留给本人。与本仓多 Agent 作战室、出海一人公司方向贴合；出自商业 API 公司，链接带其官网 | 多 Agent 作战室 / 出海 | **GitHub**（10-31 09:37 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| dotimpact/grokbot-web-sender | https://github.com/dotimpact/grokbot-web-sender | MV3 Chrome 扩展：右键把当前页/选中文字/链接/图片 + 一段备注 POST 到 Bot 的 webhook routine，URL 与 key 只存本地 storage 并按源申请权限。webhook routine 投料的轻量入口；日文 README，无 License | Routine（webhook） / 工具 | **GitHub**（10-31 09:48 UTC 建，无 License，0★） |
| b1b1h-m1k3r/multi-agent-workspace | https://github.com/b1b1h-m1k3r/multi-agent-workspace | 多个 Agent（Claude Code、Codex、Gemini、Grok）共用项目不互相覆盖：每个 Agent 各写 `<Agent>/vN/`，只有 publish 脚本能更新 `main/` 并记 LAST-EDITED-BY；带 setup skill 一句话安装。无 git 的文件夹约定，适合非程序员多 Agent 协作 | Multi-agent / 协作约定 | **GitHub**（10-31 09:00 UTC 建，MIT，0★） |

### Skip（本轮）

keyvwin/b2bsearch-plugin、full-icp-search、contact-finder、b2b-leads-finder、hiring-signals、account-signals（同一商业 B2B 数据服务批量上架的插件，需其 key）；Kortix-seo/grok-bot-alternative-matrix（SEO 导向的竞品对比表）；lokeshrana9999/get-unstuck（README 暂不可读，下轮再看）；Ryu-Jemu/Grok_Bot-Build_Day（活动仓）；vinitprajapat0822-coder/grok-skills（非 Grok Bot 专属）；其余为与 Grok Bot 无关的 Telegram/WhatsApp/交易 bot。

## 2026-10-31 20:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / grok skill / routine / plugin / template / war room，created≥10-31 09:30 UTC），按 full_name 与 README、docs、inbox、.collab、examples 去重。X 侧未扫（交 X 大 V 雷达）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| six20am/grokbot-blueprint | https://github.com/six20am/grokbot-blueprint | **Bot 首次对话自建工作区**：问四个问题后从六种归档方式（军事式/按阶段/按客户/PARA/编号索引/按日期）里选一种，搭地图 + 路由 + 分区笔记三层，用记忆规则让 Bot 每次任务前先读；附语气文件、缺口记录（无 skill 时给一行选项并记日志）、工作区体检、工具审核清单，以及自有邮箱与短信接入 skill（写明 routine 不能无人值守外发）。作者自述「已写完未在全新账号实跑」。本轮最值得看 | Skills / 起步模板 | **GitHub**（10-31 10:21 UTC 建，无 License，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| xdays/herdr-layouts | https://github.com/xdays/herdr-layouts | Herdr（终端/编码 Agent 桌面应用）的「Grok Bot」布局：把编码 Agent 排成好友列表、聚焦 Agent 的终端显示成聊天线程、旁边一条 Activity 流，附 RECIPE.md 让 Agent 照着重建。仿 Grok Bot 交互的周边，非 Grok Bot 本体 | Fun / 周边 | **GitHub**（10-31 11:44 UTC 建，无 License，0★） |
| greenlight4134-dot/grokbot-office | https://github.com/greenlight4134-dot/grokbot-office | 复刻 X 上「GrokBot Office」视频的多 Bot 监控大屏：等距像素太空办公室，Bot 经 REST 上报状态、SSE 实时刷新、需审批时点名用户，带外网访问密码锁与 demo 预设。韩文 README，默认预设是 memecoin 雷达，收录时只取「多 Bot 状态面板」思路 | 多 Agent 作战室 / 可视化 | **GitHub**（10-31 10:56 UTC 建，无 License，0★） |
| lokeshrana9999/get-unstuck | https://github.com/lokeshrana9999/get-unstuck | 上轮 README 不可读，本轮补看：给拖延/执行困难的人设计的 Grok Bot，一次只问一个小问题找卡点再给小步建议；仍处规划阶段（Bot 未建），有数据模型、草稿内容和命令行原型，对原流程图逐条做了证据复核。先信号，等 Bot 建成再看 | 生活 / Bot 设计 | **GitHub**（MIT 代码，0★，status: planning） |

### Skip（本轮）

gilangbintang305-droid/grok-bot-solana、grok-bot-solana-12（币圈交易 bot）；motbong235-cloud/grok-tg-bot（xAI API 的 Telegram bot，非 Grok Bot）。

## 2026-10-31 22:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / skill / routine，created≥10-31 11:30 UTC），按 full_name 与 README、docs、inbox、.collab、examples 去重。本轮未扫 X（X 大 V 雷达每小时覆盖）。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| BigFishSynergy/imessage-ai-assistant-workflow | https://github.com/BigFishSynergy/imessage-ai-assistant-workflow | **常开 Mac 上的 iMessage 代回复助手模板**：BlueBubbles 把新短信经 webhook 推给 Bot 的 routine，Bot 按每人规则决定回复、提醒本人或不出声，再用 REST/osascript 发出；附 chat.db 读近期消息脚本、每人档案模板和已知坑。MIT。需核：自动代回复是否默认先确认、示例号码均为占位 | 渠道接入 / webhook routine | GitHub 新仓 |
| zhang1807865587-ui/x-grab-codex-analyze | https://github.com/zhang1807865587-ui/x-grab-codex-analyze | 中文**省额度 skill**：Grok Bot 只抓 X 原始数据存 JSON，清洗总结写报告交给云电脑上登录的 Codex CLI 跑；含安装三步和 `x-analyze.sh`。无 License、0 星，需核脚本 | skills / 省额度 | GitHub 新仓 |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Forbu/pibots | https://github.com/Forbu/pibots | 基于 Pi Agent SDK 的开源「Grok Bot 复刻」：命名 Bot、共享 /workspace、分层记忆、多 Bot 交接、skills、routines、审批卡片。无 License，信号向（看社区如何拆解 Grok Bot 架构），非官方 | 生态 / 开源复刻 | GitHub 新仓 |

### Skip（本轮）

samybelgarbifr-design/grokbot-cursor-demo（空测试仓）；gilangbintang305-droid/grok-bot-solana-12（币圈交易 bot）。

## 2026-11-01 00:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（grokbot / grok-bot / "grok bot" / skill / routine / plugin / template，created≥10-31，取 14:00 UTC 后新建），按 full_name 与 README、docs、inbox、.collab、examples 去重。X 侧扫了 github.com/skill/routine 近帖，无独立新仓链接（Action Button 快捷指令为 iCloud Shortcuts，低粉跳过）。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| alexeygrigorev/grokbot-chat-export | https://github.com/alexeygrigorev/grokbot-chat-export | **零额度导出桌面端聊天**：只读本机 `%APPDATA%\\Grok Bot\\sand-client-persistence` 里的 transcript replica（约 200 条滚动窗），不解密钥/不推其他 blob，写成可幂等的 append-only JSONL；支持一次性 export 与每 30 秒 watch，Windows 登录任务脚本。纯 Python 标准库，MIT。本轮最值得看 | 工具 / Desktop 备份 | **GitHub**（10-31 15:43 UTC 建，MIT，0★） |
| shahmeetk/hire-lite | https://github.com/shahmeetk/hire-lite | **邮件优先求职流水线 + 专用 Grok Bot 适配**：Bot 只做发现判断，校验/去重/队列/报表走零 LLM 的 `hl.py`；附 `adapters/grok` skill 与 routine 提示、发信放本机 SMTP/钥匙串（Bot 不读密码）。AGENTS.md 可直接粘。MIT | Playbook / Skills+Routine | **GitHub**（10-31 14:08 UTC 建，MIT，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| SystemFiles/grokbot-opnsense-plugin | https://github.com/SystemFiles/grokbot-opnsense-plugin | 非官方 OPNsense API 插件：Go stdlib stdio MCP + `opnsense` skill，写操作必须 `confirm:true`；agent-plugins / Cursor 变量清单，密钥只进环境变量。仓名带 grokbot，README 写 Cursor/agents；防火墙写操作风险高，先信号 | Skills / Plugins / 基建 | **GitHub**（10-31 14:45 UTC 建，MIT，0★） |
| fisheeplife-beep/cn-deploy-openmausbot | https://github.com/fisheeplife-beep/cn-deploy-openmausbot | 已收 OpenMausBot 的中文跟跑部署伴侣：npm 镜像、compose、preflight/verify、国内网络坑；作者自述 CLI 健康检查已核、Engine 登录与 Docker 未核。旁链 Self-hosted | Self-hosted / 部署 | **GitHub**（10-31 14:56 UTC 建，MIT，0★） |

### Skip（本轮）

Penguinai-lee/grokbot_skill、NewRra/Ads-grokbot（空仓）；NamaanXD/VERITHINK（仅 LICENSE）；kagamineko-grokbot/tg-dsh-hotmem-mvp（Telegram↔DSH 热记忆，非 Grok Bot 玩法）；Leotheka/leotheka.github.io（Bot 做的个人站）；Logos52/grokbot-office（上轮已 skip，仅编译产物）。X 侧 @ultrakindguy Action Button→Webhook 的 iCloud Shortcuts（197 粉 0 赞）不收仓级条目。

## 2026-11-01 02:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（"grok bot" / grokbot / grok-bot / skill / routine / plugin / template，created≥10-31，取 16:00 UTC 后新建），按 full_name 与 README、docs、inbox、.collab、examples 去重。X 侧扫了 github.com / skill / routine 近帖：GlennHasABeard/foreman v1.1.1 已收仓仅版本更新不重收；其余无独立新仓。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Gipppp121/grok-bot-relay | https://github.com/Gipppp121/grok-bot-relay | **7 Bot 接力，不靠每小时空转**：周一 Scout 开跑，后续 Pain Miner→Judge→Builder→Pitch→Buyer→Chief 只在上家写 DONE 后唤醒；X 读额度按 Bot 切片、触顶写 STOP；只有 Buyer 能花钱且必须人工 yes、上限 $40；Builder 干跑不合并、Pitch 只写草稿不发帖。附 `relay init/run --demo/wall`、ledger.jsonl、终端墙演示。MIT，2★。本轮最值得看 | 多 Agent 作战室 / Routine 编排 | **GitHub**（10-31 16:14 UTC 建，MIT，2★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Roccat92/grok-office | https://github.com/Roccat92/grok-office | 越南文 README 的静态 3D 办公室大屏：Bot 自写 `status.json`（working/idle/meeting/blocked/done），页面每 10 秒刷新；附 `update-status.mjs` 一键改状态并可 `--push` 触发 GitHub Pages。与已收 grokbot-office 同向，CLI 更清晰；无 License | 多 Agent 作战室 / 可视化 | **GitHub**（10-31 17:52 UTC 建，无 License，0★） |
| donotifys/donotify-grok-plugin | https://github.com/donotifys/donotify-grok-plugin | 给 Bot 装电话线的 skill：只含 `skills/donotify`，经 donotifys.com API 打到本人账号绑定号码（紧急邮件分拣等）；密钥 `DONOTIFY_API_TOKEN`。MIT，商用 SaaS 试用额度，先信号 | Skills / 通知 | **GitHub**（10-31 16:07 UTC 建，MIT，0★） |
| KrisCyberSec/infra-health-monitor | https://github.com/KrisCyberSec/infra-health-monitor | 运维向作品集：模拟指标脚本 + `bot-prompt.md`（Bot 描述与 routine）+ 样例告警/日报；可当「基建监控 Bot」起步模板，先信号（无 License、数据为模拟） | Skills / Routine 模板 | **GitHub**（10-31 17:54 UTC 建，无 License，0★） |

### Skip（本轮）

calfo-app/calfo-plugin（厨房/食材商用 MCP 插件，需 Calfo 账号）；Play-Omega-Games/daily-puzzle-break、poisenloaf/ultimate-rv-trip-planner（小众游戏/房车模板）；Hakeem-Hannoon/skill-atlas-mvp（$3.25 日报 skill 市集落地页）；TryGrokBot/TryGrokBot（个人 Bot 品牌页）；czstuff2/newhireiv（几乎空 README）；freeddan-lgtm/mission-control-office（个人办公室页 + Vercel SSO 笔记）；six20am/workspace-blueprint（已收 six20am/grokbot-blueprint 的迁仓续作，建于 10-02，本轮不重收）；GlennHasABeard/foreman v1.1.1（仓已收，仅版本更新）。

## 2026-11-01 08:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（"grok bot" / grokbot / grok-bot / skill / plugin / template / OpenMausBot，created≥10-31，取 18:00 UTC 后新建 + created≥11-01），按 full_name 与 README、docs、inbox、.collab、examples 去重。X 侧轻扫 github.com/skill/routine 近帖：无独立新仓链接。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| KevinLogan84/grokbot-notify-sounds | https://github.com/KevinLogan84/grokbot-notify-sounds | **本机 Grok Bot 通知铃声**：watch 只读 Notification Center 库按规则播系统/自定义音；notify 模式给 Bot 一行命令在消息时本机发声，无需 Full Disk Access。无网络/无 Keychain、可静音时段与 burst 合并。附 install/uninstall、LaunchAgent、测试。无 License。本轮最值得看 | Desktop / 通知 | **GitHub**（10-31 19:03 UTC 建，无 License，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Bodila51/bot-hq | https://github.com/Bodila51/bot-hq | 多 Bot 办公室大屏的**写入契约**：Bot 向 `events.jsonl` 追加 status/usage/schedule 行，零依赖 Node 尾随，浏览器渲染 3D 塔楼工位；附 CONTRACT.md（字段与并行分工）。WIP、无 License；与已收办公室可视化同向，契约层可抄 | 多 Agent 作战室 / 可视化 | **GitHub**（11-01 00:04 UTC 建，无 License，0★） |
| W3D0W/grok-bot-office | https://github.com/W3D0W/grok-bot-office | 自上而下 3D 办公室：`bots.json` 驱动 routine 时刻表、跨岗位递文件夹、安静时段回桌睡觉；A* 走路、GitHub Pages 可演示。个人 26 Bot 场景，无 License；可视化较完整，先信号 | 多 Agent 作战室 / 可视化 | **GitHub**（10-31 21:53 UTC 建，无 License，0★） |

### Skip（本轮）

TrashCan-Design/OpenMausBot、warrior123-coder/OpenMausBot（milind-soni 主仓镜像/空壳续作，原仓已收）；mo-dealintelligence/di-grok-plugin（空仓）；axiomsynthesis/synthesis-cursor-plugin（需 Synthesis 账号的商业插件）；Licoy/study-grokbot（仅 LICENSE+一行 README）；rsonnad/grokbot-pages（个人站 bots 发布页，非通用玩法）；redlineoz13/grok-skills-audit（个人 skill 体检报告导出，非配方）。


## 2026-11-01 10:07 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（"Grok Bot" / grokbot / grok-bot / skill / plugin / OpenMausBot，created≥10-31 取 18:00 UTC 后 + created≥11-01）+ X 近帖 github.com/skill 链接，按 full_name 与 README、docs、inbox、.collab 去重。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| raphaelsalaja/skills（bots） | https://github.com/raphaelsalaja/skills | **把选定的 Grok Bot 做成可分享作品集**：粘贴 `grok.md` 提示词让主 Bot 点名→脱敏→产出卡片 JSON，再生成物理堆叠/卡片/组织架构页并附复制链接；25 种官方外形与 11 色写入 marks.js。`npx skills add raphaelsalaja/skills` 后跑 `/bots`。MIT，~46★。本轮最值得看 | Skills / 作品集展示 | **X** @raphaelsalaja + **GitHub**（bots skill 10-31 22:43 UTC 新增，11-01 00:40 补外形色） |
| seren-wib/bus-transfer-bot | https://github.com/seren-wib/bus-transfer-bot | **多 Bot 公交换乘黑客松配方**：1 个编排 Bot 拆 Kakao Map A→B 中间站，3 个搜索 Bot 并行查实时到站并写 `results/{stop}.json`，编排合并算最快换乘（含枢纽内换站台）。韩文 `docs/requirements.md` 写清 Bot 契约与上下限。无 License、tasks/results 仍空，先看编排思路 | 多 Agent 作战室 / Playbook | **GitHub**（11-01 01:45 UTC 建，无 License，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| linmoxi33/openmausbot-config-lint | https://github.com/linmoxi33/openmausbot-config-lint | OpenMausBot `config.json` 的**离线严格校验**：把上游故意宽松的 schema 翻成可断言退出码；纯 Python 标准库、`--json` 输出，MIT。旁链已收 Self-hosted / OpenMausBot | Self-hosted / 工具 | **GitHub**（11-01 01:34 UTC 建，MIT，0★） |

### Skip（本轮）

Bodila51/grokbot-wallpaper（已收 Bodila51/bot-hq 的更名续仓，events.jsonl 办公室契约不变）；snbwallet365-ops/grokbot365（自建多模型 PWA/签证顾问，非 Grok Bot 玩法；同作者此前 grokbot-ai-agent 已 skip）；goncaloneves/veil（通用 coding-agent 密钥遮罩，文档对 Grok Build/grok-cli，非 Grok Bot 配方）；adamanz/grok-bot-skill、Luca-Blight/thin-grok-bot-deep-work-on-cli、Dissipative-ATLAS/stackchan-grok-bridge（README/inbox 已收，X 转帖不重收）。

## 2026-11-01 10:45 Asia/Shanghai · T7 日更雷达

> 周末偏 GitHub：`gh search repos`（"Grok Bot" / grokbot / grok-bot / OpenMausBot，created≥10-31，重点扫 11-01 ≥02:00 UTC 白天 10:07 之后新建）+ X `search_posts_all` 近 24h github.com/skill/routine。按 full_name 与 README、docs、inbox、examples、.collab 去重。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| cclank/boxbridge | https://github.com/cclank/boxbridge | **把 Mac Orca 接到 Grok Bot 云机**：菜单栏+CLI 做本机转发、保活、重连与配对；不发提示词、不调模型；云端 `install-cloud.sh` 装受控 Orca，钥匙串显式授权。中英 README、MIT、有 Releases。本轮最值得看 | Desktop / 云机桥接 | **GitHub**（11-01 02:23 UTC 建，MIT，0★） |
| hanbo-onenod/flow-demo | https://github.com/hanbo-onenod/flow-demo | **Slack↔Grok Bot↔GitHub Actions↔Cursor 一月演示流水线**：7 Bot 规则本在仓内 `bots/`，`grok/setup.md` 可粘贴建 Bot+webhook routine；router 推事件，人守确认/合并/验收四闸。虚构数据、无 License，配方结构可抄 | 多 Agent 作战室 / Playbook | **GitHub**（11-01 02:15 UTC 建，无 License，0★） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| piyaster11/thaicreditbrief | https://github.com/piyaster11/thaicreditbrief | 泰企信贷工作坊演示：4 条 Grok Bot routine 写 `data/*.json` → GitHub Pages 看板（briefing/ratings/sentiment）；公开数据、无 License；抄「routine→JSON→Pages」展示链 | Routine 展示 / 看板 | **GitHub**（11-01 02:30 UTC 建，无 License，0★） |
| two-workspaces/openmausbot | https://github.com/two-workspaces/openmausbot | OpenMausBot 的 **Railway 一键模板**：官方镜像 + 同容器 Caddy 边缘、邮箱 OTP 登录、卷持久化 `/data`。旁链已收 Self-hosted / OpenMausBot | Self-hosted / 部署 | **GitHub**（10-31 04:02 UTC 建，无 License，0★；白天未收） |

### Skip（本轮）

Bodila51/grokbot-wallpaper、snbwallet365-ops/grokbot365、seren-wib/bus-transfer-bot、linmoxi33/openmausbot-config-lint、TrashCan-Design/OpenMausBot、warrior123-coder/OpenMausBot（白天已收或已 skip）；Licoy/study-grokbot（仍仅一行 README）；GlennHasABeard/foreman 版本帖（仓已收）；X 转帖 adamanz/grok-bot-skill、Luca-Blight/thin-grok-bot-deep-work-on-cli、Dissipative stackchan-grok-bridge（README/inbox 已收不重收）；CardCaptain / SamE x.ai/bot 模板帖无新仓；tips 帖无独立 github。

## 2026-11-01 12:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（"Grok Bot" / grokbot / grok-bot，created≥11-01 取 ≥02:45 UTC 白天 T7 之后新建）+ X `search_posts_all` url:github.com 近窗。按 full_name 与 README、docs、inbox、.collab 去重。未改 README/docs。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| heweimign/rokid-glasses-grokbot-open | https://github.com/heweimign/rokid-glasses-grokbot-open | **Rokid Glasses 2 ↔ Grok Bot 开源桥**：Prism PluginBridge v4 插件 + session-bridge HTTP 队列 + 本机 gateway-relay 长轮询打本地 agent 网关；含 deploy/systemd、bots 列表示例、烟雾清单；占位域名/虚构 Bot ID，无私钥。MIT。本轮最值得看 | 硬件 / Bridges | **GitHub**（11-01 03:23 UTC 建，MIT，0★） |
| Licoy/study-grokbot | https://github.com/Licoy/study-grokbot | 上轮 skip（仅一行 README）本轮已成站：**StudyGrokBot 日更专栏**，GrokBot 自写一期一题（创刊号「机器人管理」含可粘贴提示词/交接格式），中英 guide + RSS/`llms.txt`，站点 studygrokbot.com。MIT，1★。请核内容准确度与是否过薄 | 学习资源 / 日更 | **X** @licoycn + **GitHub**（10-31 建，11-01 03:51 补站） |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| pyrider3/arch-friend-desktop | https://github.com/pyrider3/arch-friend-desktop | Arch niri+Noctalia 桌面套装：可选打包已收 `grok-bot-squad` 顶栏小队与 `wingman`；安装脚本可预览/备份。受众窄（Arch）、License NOASSERTION；作「一键装顶栏小队」旁链信号 | Desktop / 打包 | **GitHub**（11-01 03:33 UTC 建，NOASSERTION，0★） |

### Skip（本轮）

pbouagno/research-archive（个人研究站产物归档，非通用玩法）；one-commit/figma-checker-grok-bot、HarrisStudiosLLC/Harris-Studios-Automation（空/仅标题 README）；angelaedora/fastapi-agentic-demo（FastAPI 任务 API，与 Grok Bot 玩法无关）；1bitLabss/EasyAgent（本机 harness 自称「类 Grok Bot」，非配方）；X @kkkeric_ai 出海增长 Article+skill（896 粉，交 X 大 V 雷达）；转帖 OpenMausBot / grok-bot-cli / foreman / thin-grok-bot / templates / profiles / skill（README/inbox 已收不重收）。

## 2026-11-02 16:05 Asia/Shanghai · 白天玩法雷达

> `gh search repos`（"Grok Bot" / grokbot / grok-bot / openmausbot，created≥11-01，补扫 11-01 12:05 之后至今；中间几轮未落盘）。按 full_name 对照 README、docs、inbox、.collab 去重，均为首见。

### 推荐（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| Lniosy/souhun | https://github.com/Lniosy/souhun | **搜魂**：Mac/Windows 桌面 App，查看、写入、忘掉 Grok Bot 的记忆（账号共用 vs 单 Bot、指令 vs 事实），带原理/记忆分类/安全文档与安装包；MIT | 工具 / 记忆 | GitHub 搜索 |
| Revve-AI/grokbot-webhook-adapter | https://github.com/Revve-AI/grokbot-webhook-adapter | **routine webhook 签名适配器**：Fathom/GitHub/Stripe 这类只能填 URL、靠签名的发送方，经一个 Vercel 函数验签后补上 Authorization 再转给 Grok Bot routine webhook；有 CI；MIT | Routine / 集成 | GitHub 搜索 |
| djbclark/bot-briefs | https://github.com/djbclark/bot-briefs | **Chief of Staff Bot 复刻包**：README 本身就是给 CoS Bot 读的主提示，带用户一步步复刻 bot 舰队 + Bot Briefs 看板；先读 SECURITY（最小权限、每 Bot 独立 token、只读触发）；许可证未声明，待核 | 作战室 / 多 Bot | GitHub 搜索 |
| MuhammadShahzeb123/agentwire | https://github.com/MuhammadShahzeb123/agentwire | **Agent 之间的私信总线**：Grok Bot（远程 MCP over HTTP）与 Codex/Claude Code（stdio）互发消息，离线排队、线程、wait_for_message 长轮询；SQLite 零依赖；MIT | 跨 Agent 协作 | GitHub 搜索 |

### 玩法 / 信号（待核）

| 名称 | 链接 | 一句理由 | 建议节 | 来源 |
|------|------|----------|--------|------|
| zhaobenxiang5-coder/grok-bot-orange-book | https://github.com/zhaobenxiang5-coder/grok-bot-orange-book | 中文「Grok Bot 橙皮书」，每条标【已核实】（对照官方文档）或【作者声称】并附来源；CC BY-NC 4.0；当天新建，待看完整度 | 中文教程 | GitHub 搜索 |
| Lniosy/dsh-tool-grok-bot | https://github.com/Lniosy/dsh-tool-grok-bot | DeepSeek Harness 工具包：从 DSH 里给指定 Bot/团队房间发话、群发最多 8 个 Bot、读写记忆；MIT；与 souhun 同作者 | 跨 Agent 协作 | GitHub 搜索 |
| arismarioneves/grokbot-telegram | https://github.com/arismarioneves/grokbot-telegram | Telegram → routine webhook 的 PHP 桥：校验 secret/chat_id/from_id 后立即唤醒 Bot；轻量，许可证未声明 | Routine / 集成 | GitHub 搜索 |
| SnazzyGaz/bot-creative-toolkit | https://github.com/SnazzyGaz/bot-creative-toolkit | 无头视觉工具箱：一键装 Blender/Inkscape/GIMP/FFmpeg 等，`bct look` 多角度渲染联系表让 Bot 自检产物；MIT | Skills / 工具 | GitHub 搜索 |
| grokbotsmarket/awesome-grok-bots | https://github.com/grokbotsmarket/awesome-grok-bots | 同类英文 Awesome：X 上真实 Bot 运行分享链接按场景分类（26 条）；仅作信号与互链参考，带站点导流 utm | 外部清单 | GitHub 搜索 |

### Skip（本轮）

w1nklerr/night-shift-with-grok（夜间 Solana 自动交易，收益截图未核实且涉资金风险）；malinoms/grok-bot-team（个人 Bot 团队导览，内容浅）；coding-ax/poteto-grok-bot-skills（@poteto 指南的二次整理）；10foldjosh/grokbot-uses（搜索日志式清单）；4regab/bot-mates（Kiro Crew 迁移包）；spec-protocol/agent-bridge、NoLimit0714/grok-world、chippybrown/voice-reader-for-grokbot（下轮再看）；Philipp0205/gbot-tui（无 README）；其余空仓/个人测试仓。

## 2026-11-02 16:15 Asia/Shanghai · 周更候选

> 从 10-26 周更后各轮「推荐」77 条里挑 5 条，gh 只读实查星标/许可；全文见 box /workspace/awesome-grokbot/candidates-2026-11-02-weekly.md。待 sitin 确认后才改 README。

### 候选（5 条）

1. [BeatAPI/grokbot-growth](https://github.com/BeatAPI/grokbot-growth) - 中文「出海增长开工包」技能：回答 6 个问题，生成一支按岗位分工的出海增长 Bot 团队（总管调度，社媒/SEO/外链/竞品/新词/多语言视频六条线）的岗位说明、共用规则、审核表和第一周清单。10★ · MIT · 10-31 更新。
   - 建议分类：💼 中文一人公司 / 👥 多 Bot 团队　标签：`出海` `multi-bot` `skill` `zh`
   - 注意：出品方 BeatAPI 是 API 服务商，可能与 hiapi 同赛道，收不收由 sitin 定。
2. [Lniosy/souhun](https://github.com/Lniosy/souhun) - 「搜魂」：Mac/Windows 桌面 App，查看、写入、忘掉 Grok Bot 的记忆，区分账号共用与单 Bot、指令与事实，附原理和安全文档、安装包。0★ · MIT · 今天更新（新仓）。
   - 建议分类：🧰 工具（记忆）　标签：`memory` `desktop` `zh`
3. [realTaki/bot-codex-delegate](https://github.com/realTaki/bot-codex-delegate) - Grok Bot skill：把本机 Codex app-server 当云端 agent 用，派活、完成后唤醒、中途可 steer/打断、复用会话；同作者 [bot-keepalive](https://github.com/realTaki/bot-keepalive) 让长任务期间云电脑不睡。9★/5★ · MIT。
   - 建议分类：🧩 技能与玩法（跨 Agent）　标签：`skill` `codex` `delegate`
4. [number5meme/grokbot-larkbot-bridge](https://github.com/number5meme/grokbot-larkbot-bridge) - 飞书（Lark）机器人消息转发到 Grok Bot routine webhook，只出站长连接、无需公网端口，命令行回复文本/图片/文件；同作者还有 [QQ](https://github.com/number5meme/grokbot-qqbot-bridge) 和 [微信 ClawBot](https://github.com/number5meme/grokbot-wechatclaw-bridge) 版本，三件套同一套接口。各 1★ · MIT · 10-30 更新。
   - 建议分类：⏰ Routine 与集成（国内 IM）　标签：`feishu` `qq` `wechat` `webhook` `routine`
   - 注意：默认连 Lark 国际版，国内飞书需改域名，待核。
5. [Revve-AI/grokbot-webhook-adapter](https://github.com/Revve-AI/grokbot-webhook-adapter) - 给只能填 URL、靠签名验证的发送方（GitHub、Stripe、Fathom 等）做的 Vercel 小函数：先验签，再补上 Authorization 转给 Grok Bot routine webhook；有 CI。0★ · MIT · 11-01 更新。
   - 建议分类：⏰ Routine 与集成　标签：`webhook` `vercel` `routine`

注：2、4、5 都是新仓、星少，内容扎实但热度未验证；可先收标「新」，或放一周再看。

### 没收（一句话理由）

- NVIDIA/SkillSpector（2.4 万★）、eugeniughelbur/obsidian-second-brain（5.1k★）、unclebob/ub-mode：通用 Agent/skills 工具，没点名 Grok Bot；SkillSpector 可考虑放「安全」附录，另议。
- k7cfo/remove-your-data：隐私删数据 skill，偏离出海/作战室主线。
- tantan1hao/grok-multi-bot-workflow、Licoy/study-grokbot、wchengyen/feishu-grokbot-bridge：中文相关但 0–2★、刚起步，留 inbox 观察。
- djbclark/bot-briefs、KevinLogan84/grokbot-notify-sounds、RawPowered/Grok-Bot-Templates 等：未声明许可证。
- six20am/grokbot-blueprint、ditto-assistant/ditto-plugin：已归档；cclank/boxbridge、BigFishSynergy/imessage-ai-assistant-workflow：仓库已 404。
- 其余（各类 T3/Discord/Slack 桥、语音会议、像素办公室等）：同质或小众，留 inbox。

## 2026-11-02 18:05 Asia/Shanghai · 白天玩法雷达

> 补扫 16:00 后（08:00Z 起）新建仓 + X 近 3 小时带 GitHub 链帖；X 命中只有两篇 Article（交给 X 大 V 雷达）。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| agentmuxhq/agentmux-mcp | https://github.com/agentmuxhq/agentmux-mcp | macOS 本地桌面 App + MCP 消息桥：Cursor / Claude Code / Codex 与云端 Grok Bot 互相提问取回答（工单、按需唤醒 CLI/webhook/收件箱）；Grok Bot 经 Cloudflare/ngrok 隧道接入、每 Bot 独立 token；Apache-2.0；当天新建、未公证 | 跨 Agent 协作 | GitHub 搜索 |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| devzer0o0/dsh-grok-buddy | https://github.com/devzer0o0/dsh-grok-buddy | DeepSeek Harness 插件：侧栏会话状态用 Grok Bot 头像表情呈现（思考/输出/等确认/失败/完成 8 态）；BSD-3（GitHub 标 other），用到官方头像素材，版权待核；偏趣味 | 工具 / 周边 | GitHub 搜索 |

### Skip（本轮）

bringm1lan/pump-printer（Pump.fun 发币准备 skill，涉资金风险）；samirpatel-ariaBOT/grok-trading-council（模拟交易）；1nh4oX/grokbot-d47-text-research-20261102（临时传输仓）；tranthor-main/cursor-plugin（厂商插件，已在 inbox 同类）；A101llan/GrokBotSkills（空仓）；topmindspace/x-pulse-bot（无 README）。

## 2026-11-02 22:05 Asia/Shanghai · 白天玩法雷达

> 补扫 18:00 后（09:30Z 起）新建 Grok Bot 相关仓；X 近几小时 Article 交给 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Charonyuu/grokbot-office | https://github.com/Charonyuu/grokbot-office | 把 Grok Bot 桌面端里的 Bot 画成 3D 办公室宠物：空闲睡沙发、干活敲电脑、等你确认就举「?」，按侧栏分组分楼层，「Needs you」面板一键跳回对话；Node 18+ 本地跑、无依赖，MIT，读 Mac 本地缓存（不联网上传）。比前几轮同类 office 仓完成度高、有 demo 动图和署名出处 | 🧰 工具（多 Bot 可视化） | GitHub 新建（~3★，2026-11-02） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Syorange/Caster | https://github.com/Syorange/Caster | 私人 AI 播客工具包 + Grok Bot skill：show.json 定义节目，edge-tts 配音、合成配乐、响度母带，发到 GitHub Pages 私有 feed；结构完整但未声明许可证，0★ | 🧩 技能与玩法（内容生产） | GitHub 新建 |

### Skip（本轮）

yuanwenxing/grok-bot-test、ieieeee/grokbot-live、AIZATFIR/grokbot-cue-fleet、martinleesk/grokbot-3d-hq（空仓/无描述）；topmindspace/x-pulse-bot（页面模板、无 README 说明）。

## 2026-11-03 02:05 Asia/Shanghai · 白天玩法雷达

> 补扫 22:00 后（14:00Z 起）新建 Grok Bot 相关仓；X Article 交给 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| measses/usta | https://github.com/measses/usta | 在 Grok Bot 云电脑上跑你自己的 Claude Code：Bot 派编码任务、Claude Code 在分支上改、回报后你批 push；主打「默认什么都不上传」——记忆/skill 逐项勾选、禁用词表整段剔除、邮箱/电话/证件号检测、密钥不出本机，并提醒云电脑被所有 Bot 共享；v0.1.1 已在真实云电脑端到端跑过，有测试；MIT，0★ 当天新建 | 跨 Agent 协作 / 安全 | GitHub 新建（2026-11-02） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| brandon-wsc/paseo-grokbot-webhook | https://github.com/brandon-wsc/paseo-grokbot-webhook | Paseo 插件构想：把本地 Agent 的权限请求/结束等生命周期事件 POST 到 Grok Bot webhook 例程，让 Bot 代人盯终端；目前只有 README + MIT，无代码，等落地再看 | 例程 / webhook | GitHub 新建 |

### Skip（本轮）

Codewithmesid/claude-mcp-server（无 README）；Jxbbbbbyan/review-judgment-suite（通用审核 skill，Grok Bot 只是宿主之一，README 带讽刺献词）；mmellow080/popops、cactuslibo/bot-skills、lamalyon/grok-bot、miland927/Grok-bot-esp32、kohchihao/mysimplegrokky（空仓/仅标题）；zone17th/lost-east-grok-plugin（单频道私用 skill）；fitzyracing1/Almeidafly（非 Grok Bot 产品）。

## 2026-11-03 08:05 Asia/Shanghai · 白天玩法雷达

> 补扫 02:00 后（约 18:00Z 起）新建/更新 Grok Bot 相关仓；X 近几小时多为 Article / 模板分享帖，无新独立 GitHub 玩法链（Article 交 X 大 V 雷达）。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| DensitySystems/grokbot-agency-kit | https://github.com/DensitySystems/grokbot-agency-kit | **多 Bot 小公司开工包**：RULES / 精简组织形 / 座位交接 / CREDIT-SAVING 省额度法 + manager/worker 座位模板 + quiet-watcher / keep-alive / webhook-inbound-dedupe 例程提示；纯文本配方、MIT，当天新建 | 多 Bot 作战室 / 省额度 | GitHub 新建 |
| Vedthakar/agent-hub | https://github.com/Vedthakar/agent-hub | **跨 Agent 情境总线**：Claude/ChatGPT/Gemini/Grok Bot 等共享「当前局面」，跨工具任务需短信四字码批准后才派发；有 TypeScript 实现、测试与威胁模型；MIT。与已收 SiegoZhang/agent-hub（本机会话看板）不是同一项目 | 跨 Agent 协作 | GitHub 新建 |
| ekastle/stl-price-manager-skill | https://github.com/ekastle/stl-price-manager-skill | **短租定价 skill**：用 AirROI 拉竞品日历 + 1Password 管密钥 + 私仓存快照，输出加权均价/缺口与调价表；含 SKILL.md、bot 系统提示与可分享模板说明；MIT 垂直玩法 | Skills / 一人公司垂直 | GitHub 新建 |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| mhd-fettah/Grokbot-usage-Skill | https://github.com/mhd-fettah/Grokbot-usage-Skill | 周用量成绩单 Bot：Pillow 画浅/深色卡片，含节奏预测与按 Bot 拆分；带 skill + 首聊安装；未声明许可证 | 工具 / 额度可见性 | GitHub 新建 |
| Bigibyte/awesome-grok-bot | https://github.com/Bigibyte/awesome-grok-bot | 另一份英文 Awesome + 新手学习路径/工作流/对比 FAQ（CC0）；与 README 已链的 ZeroPointRepo / majiayu000 同类，先作外部清单信号 | 外部清单 | GitHub 新建 |

### Skip（本轮）

Brenw2/dork-bot（Hermes+Ollama 自制 Grok Bot 替代品）；bot2botlabs/warranty-desk-plugin、loop-desk-plugin、BrightDoor-AI/brightdoor-grok-bot、GetDial-AI/dial-plugin（厂商 MCP/插件广告）；jedisherpa/cf15t-command-center（特定触控屏个人工程、无许可证）；themayukhbasu/grok-bot-skills（单条 CoS skill、无许可证）；quyenxtran/grok-front-desk、ssmholding/SSM-Holding---Grok-Bots、napacodes/Orcid-bot、santidaxey/desk-app、xyzhani/Grok-Bot（空/薄）；Codewithmesid/claude-mcp-server、cactuslibo/bot-skills、mmellow080/popops 等上轮已 Skip；X @bradgarland Routine Auditor（x.ai/bot 模板分享无独立仓）、@clairevo Muse/Instinct MCP 帖（无 GitHub 链）、小红书 MCP / reliability 等 Article 交 X 大 V 雷达。

## 2026-11-03 10:05 Asia/Shanghai · 白天玩法雷达

> 补扫 08:00 后（约 23:00Z 起）新建 Grok Bot 相关仓；X 侧 Article 交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| danielmedinac22/saldado-oss | https://github.com/danielmedinac22/saldado-oss | **给 Grok Bot 接 WhatsApp 客服**：经 Kapso（Meta 官方 WhatsApp Business API 服务商）收消息、唤醒 Grok Bot 例程、把回复发回客户；连发合并成一条、Bot 慢或挂了自动重试、发送被拒会用人话通知店主、密钥加密存库；Next.js + Postgres，可自托管也有托管版；AGPL-3.0，有测试与 SECURITY.md。注意作者同时卖托管版 | 渠道接入 / 一人公司客服 | GitHub 新建（2026-11-03） |

### Skip（本轮）

chrisatom1998/grok-hq（个人 Bot 状态页单 index.html、无许可证）；chaxiubao/grokbot-office（仅静态 index.html、无 README/许可证，与已收 Charonyuu/grokbot-office 同类）；hw46hz2ddd-gif/AGENTS-Group（空仓）。

## 2026-11-03 10:50 Asia/Shanghai · T7 日更雷达

> 补扫近 24 小时（11-02 起）新建 Grok Bot 相关仓，去掉白天玩法雷达已收/已 Skip 的；X 侧 Article 交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| xiaoxiaolin0918/grok-bot-kit | https://github.com/xiaoxiaolin0918/grok-bot-kit | **中文团队 Bot 迁移包**：管家 + 飞书答疑 + 质量调度 + 代码审查四个角色模板（AGENT/HANDOFF），附常开主机上的飞书 WebSocket + Git webhook 收口桥骨架、引导式搭建脚本与发布前敏感信息扫描脚本；已脱敏、MIT，当天新建 | 多 Bot 作战室 / 飞书接入 | GitHub 新建（2026-11-03） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| asktolik/grokbot-skills-Public | https://github.com/asktolik/grokbot-skills-Public | 管 Bot 团队的一组 skill：经理 Bot 开场、任务分派地图、省 token 规则、交接前五项检查、例程周检、QA 复核循环；每周更新但未声明许可证，README 带 APIhub 优惠码 | Skills / 多 Bot 管理 | GitHub 新建（4 星） |
| dynjo/grokbot-tv | https://github.com/dynjo/grokbot-tv | 已 root 的 LG webOS 电视按遥控器语音键唤起 Grok 助手（Go 守护进程 + 叠层动画）；MIT 爱好项目，可选 Grok Bot 接入走未公开接口，作者自注可能违反服务条款 | 硬件 / 趣味 | GitHub 新建 |

### Skip（本轮）

fosunwealth/star-wealth-skills（券商自家投研/下单插件市场，厂商推广）；blackpill/share-act-skills（特定配置格式校验，过窄）；malejandrobp-ui/haulforza-mcp-plugin、bot2botlabs/loop-desk-plugin（厂商 MCP 插件）；malachiian/fang-league、Signal-Drifts/great-potato-chase（Bot 做的小游戏，非配方）；NPC-NICEPEOPLEC/tech-demos、yjm728/grok-bot-codex-ping-test、qiganggang0-cpu/grok_bot_contral、grokbottrading/grokbot-dashboard、2278032241-ctrl/Try_2、CountDev67/Repository-for-Grok-Bots 及多个空 grokbot 同名仓（空/薄/测试仓）。

## 2026-11-03 12:10 Asia/Shanghai · 白天玩法雷达

> 补扫 10:50 T7 之后新建的 Grok Bot 相关仓；X 侧 Article 交 X 大 V 雷达。

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Mani-QA/grok-bots-blueprint | https://github.com/Mani-QA/grok-bots-blueprint | **把九个 Grok Bot 团队整套写成可迁移蓝图**：每个 bot 一份 SKILL.md（人设、规则、记忆、工作流、例程、连接器、云电脑配置），附「在 Ubuntu VPS 或 OpenHands / LangGraph / CrewAI 等开源框架里重建」的步骤，共享 routine 静默/告警约定与 `.env.example`（只列变量名）；每份标「看不到、未猜测」的部分。未声明许可证，含个人 bot（加密模拟盘、外卖订单抓取等） | 多 Bot 作战室 / 迁移备份 | GitHub 新建（2026-11-03） |
| shagghiesuperstar/grokbot.zone | https://github.com/shagghiesuperstar/grokbot.zone | 前轮记为空仓，现已上线 https://grokbot.zone ：公开 Grok Bot 静态目录站，约 7,676 个 bot、26 类，含搜索/趋势/最新/相关推荐；数量与分类口径和 README 已收的 grokbot.rocks 几乎一致，疑为同一语料的另一前端，未声明许可证，先作信号待核来源 | 目录站 | GitHub 更新（2026-11-03） |

### Skip（本轮）

67Fujiwara/BOT_Generator（日文 Claude Code 子代理比对 BOM/报价单项目，与 Grok Bot 关系弱）；gvkannan-explore/vulnerability-bot（仅一行 README）；CountDev67/Repository-for-Grok-Bots（上轮已 Skip）。

## 2026-11-03 14:10 Asia/Shanghai · 白天玩法雷达

> 补扫 12:10 之后新建的 Grok Bot 相关仓；X 侧 Article 交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| dylan2045ad/grokbot-alexa-echo-guide | https://github.com/dylan2045ad/grokbot-alexa-echo-guide | **用大白话让 Grok Bot 做私有 Alexa 技能和 Echo Show 小组件**：七步配方（描述需求→选免费公开数据源→Bot 写 AWS SAM + Lambda + EventBridge 定时刷新→`sam deploy`/`ask deploy`→APL 小组件→设备上启用→拍照迭代），全部跑在自有 AWS 免费额度；附动画版教程页，MIT | 硬件 / 智能家居配方 | GitHub 新建（2026-11-03） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| li-brandon/skillshelf-submissions | https://github.com/li-brandon/skillshelf-submissions | 社区 Grok Bot skill 库 SkillShelf 的投稿仓：PR 提交、要求公开来源 + 开源许可证 + 作者署名，带模板和自动字段校验；站点刚起步，先看收录量 | Skills / 目录站 | GitHub 新建（MIT） |
| piyapong-kit/grok-bot-hq-dashboard | https://github.com/piyapong-kit/grok-bot-hq-dashboard | 多 Bot 实时状态板：Bot 往 ntfy 主题推消息，GitHub Pages 静态页只从 URL 片段读主题、无第三方脚本；与已收 grokbot-office 同类但更轻，未声明许可证 | 多 Bot 作战室 / 看板 | GitHub 新建 |

### Skip（本轮）

krisrmgua/TokenPulse（多家 AI 额度菜单栏监控，读本机登录钥匙串，Grok Bot 只是数据源之一）；mingmprod-arch/seo-backlink-hub-plugin（厂商 MCP 插件）；GrokBot-GAI/G-AI（与 Grok Bot 无关的仿名仓）。

## 2026-11-03 16:05 Asia/Shanghai · 白天玩法雷达

> 补扫 14:10 之后新建/更新的 Grok Bot 相关仓；X 侧 Article 交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| bianwuwei/grok-bot-skills | https://github.com/bianwuwei/grok-bot-skills | **中文 Grok Bot Skill 模板库，复制即存**：周报、大总管+行动卡专岗一条龙周报流水线、会议记录转行动卡（决定/待办/未决带原话出处）、公众号小绿书日更四个 SKILL.md；共同规矩是只用原文信息、缺的标「待确认」、原文件只读、发人前先问；附「贴进对话说存成技能」用法，MIT | Skills / 中文模板 | GitHub 新建（2026-11-03） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| bianwuwei/grok-bot-getting-started | https://github.com/bianwuwei/grok-bot-getting-started | 同作者中文通识手册《从第一个 Bot 到一支能交作业的小队》v1.1.0（11-03 更新）：大总管、按业务域招人、Skill 与 Routine 固化、何时必须本人点头、额度与坑，附实机截图与课程模板；未声明许可证，配套公众号视频课有导流，先作信号 | 新手教程 / 中文 | GitHub 更新（2026-11-03） |

### Skip（本轮）

fieldlookup/fieldlookup-plugin（厂商 Reddit 检索 MCP，免费额度+充值）；ArtyormSatori/Hermes-Omega.rs、doitupsolutions810-crow/GreatScale-Avrone-Grok-Fusion-Bridge（与 Grok Bot 玩法关系弱的通用 agent 运行时）；QitaoWang/grokbot-push-check-*（推送测试仓）。

## 2026-11-03 18:10 Asia/Shanghai · 白天玩法雷达

> 补扫 16:05 之后新建/更新的 Grok Bot 相关仓；X 侧 Article 交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| taoning0403/napcat-grok-bridge | https://github.com/taoning0403/napcat-grok-bridge | **把 Grok Bot 接进 QQ 私聊**：NapCat（OneBot HTTP）↔ Webhook Routine 双向桥，Docker Compose 一键起；事件去重、失败重试、防回环，桥接端口只绑本机，可选 Cloudflare 命名隧道给固定 HTTPS；自带生成 Routine 指令和 doctor 自检命令，密钥走 /grok/config 登记不进聊天；v0.1 仅单机器人单私聊对象文本，MIT | 渠道接入 / 国内 IM | GitHub 新建（2026-11-03） |

### Skip（本轮）

tnandla/grokbot-office（与已收 grokbot-office、grok-bot-hq-dashboard 同类的 ntfy 3D 状态板，未声明许可证）；nitturkaryash/qualia-wavelength-cursor-plugin（厂商远程 MCP 插件）；67Fujiwara/BOT_Generator、chocfudge/grok-bot-lab-sandbox、EvanLyu732/grok-bot-bounce（无说明或练手仓）。

## 2026-11-03 20:10 Asia/Shanghai · 白天玩法雷达

> 补扫 18:10 之后新建/更新的 Grok Bot 相关仓；X 侧 Article 交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| MarcusYuan/gbdev | https://github.com/MarcusYuan/gbdev | **让 Grok Bot 当架构师带本机 Codex CLI / Cursor agent 写代码**：本地命令行编排器，规划拆任务图→并行 worktree 实现→有轮数和时间上限的评审修复循环→合到集成分支；Bot 只读 JSON 做决定，落到目标分支须用户点头，从不 push；一句话贴给 Grok Bot 即按 setup 文档自装并装 gbdev-usage skill；有中文 README、CI，Apache-2.0（非官方） | 多 Agent 编码 / 本机工人 | GitHub 新建（2026-11-03） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| omiron33/grokarr-bridge | https://github.com/omiron33/grokarr-bridge | 公开 Bot「GrokArr」（帮人管家用 Arr 影音栈）的本地 MCP + CLI 桥：默认只读、密钥留本机、只绑 loopback，经 Tailscale Serve 或带 Access 的 Cloudflare Tunnel 接入；作者自注 pre-release、镜像未发布，MIT，先作信号 | 公开 Bot 配套 / 家庭服务器 | GitHub 新建（2026-11-03） |

### Skip（本轮）

thomasgonnet/shadow-clinic-reports（某产品测试报告仓）；antzcales-byte/grokbot、gilangbintang305-droid/Grok-bot-terminal（无说明）。

## 2026-11-03 22:15 Asia/Shanghai · 白天玩法雷达

> 补扫 20:10 之后新建/更新的 Grok Bot 相关仓；顺带补漏本窗前漏扫的 DSH / Droppy 仓；X 侧 Article / 模板分享帖交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| ClawDogLabs/slack-grok-bridge | https://github.com/ClawDogLabs/slack-grok-bridge | **Slack → Grok Bot 例程桥模板**：常醒主机用 Socket Mode；云电脑会休眠则走 Cloudflare Worker 或 Node HTTP 中继（Fly/Railway/Render/Cloud Run），两边 POST 同一 webhook payload；附 SETUP-FOR-NEXT-BOT 一句话装机、HOSTING 决策树、keepalive/supervise、密钥走 secret-request 不进聊天；有中继测试。未声明许可证（package.json private） | 渠道接入 / Slack | GitHub 新建（2026-11-03） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| pastdotdev/grok-bot-plugin | https://github.com/pastdotdev/grok-bot-plugin | past.dev 共享记忆插件 + 配套 @pastdotdev Bot：OAuth 连项目、问答带出处日期、可记/可删；技能只开记忆工具。MIT，但是 SaaS（按项目计 credit），先作信号 | Skills / 记忆 / 厂商插件 | GitHub 新建（2026-11-03） |
| FeeligWang/dsh-plugin-grok-bot | https://github.com/FeeligWang/dsh-plugin-grok-bot | DeepSeek Harness 插件：经 crosswalk 私有频道异步派活（`grok_submit` / `grok_result`），因 Bot 不能被实时唤醒所以不阻塞轮询；中文 README，MIT。与已收 quafulz（读本机会话）/ Lniosy dsh-tool（官方对话）路线不同 | Bridges / DeepSeek Harness | GitHub 新建（漏扫补） |
| Nicolasdellim/grok-notch | https://github.com/Nicolasdellim/grok-notch | macOS Droppy notch 里聊本机 Grok Bot：列 bot/发消息/HUD 预览与 Live Activities；走 Electron 诊断端口的实验桥，作者自注非官方、版本易碎、未做第二台 Mac 实测；无许可证，法文 README | Clients / 桌面 | GitHub 新建（漏扫补） |

### Skip（本轮）

priosweep/priosweep-plugin（空仓）；sgchunge/grokbot-backup-site（个人 Google Drive 备份页，非公开玩法）；Spidermanrobin/awesome-grokbots（已在 inbox）；thomasgonnet/shadow-clinic-reports、67Fujiwara/BOT_Generator、gilangbintang305-droid/Grok-bot-terminal（上轮已 Skip / 无说明）。

## 2026-11-04 10:41 Asia/Shanghai · T7 日更雷达

> 补扫近 24 小时（约 11-03 02:00Z 起）新建 Grok Bot 相关仓；去掉白天玩法雷达已收/已 Skip；X Article / 模板分享帖交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| ystory/grok-codex-native | https://github.com/ystory/grok-codex-native | **把编码任务委派给 Bot 云电脑上的 Codex**：Docker worker、技能安装脚本、能力矩阵与实测边界（休眠/重置会打断），MIT + CI；与已收 gbdev（本机 Codex/Cursor）/ usta（云电脑 Claude Code）互补 | 多 Agent 编码 / 云电脑工人 | GitHub 新建（2026-11-03） |
| AnaGuiDev/context-bot | https://github.com/AnaGuiDev/context-bot | **长对话红绿灯**：🟢继续 / 🟡摘要 / 🔴换新 Bot + 交接文件；一分钟装 skill、带 dashboard，MIT；专治上下文越长越慢越贵 | Skills / 省额度 | GitHub 新建（2026-11-03） |
| jokerlin/peerlink | https://github.com/jokerlin/peerlink | **Grok Bot 经 Tailscale 跑本机 Mac 任务目录**：Telegram 审批码 + webhook 门铃（只报 pending 数不带内容），有中文 README / CI / SECURITY，MIT | 跨 Agent 协作 / 远程执行 | GitHub 新建（2026-11-03） |
| damao-bot-army/x-reply-guard-mcp | https://github.com/damao-bot-army/x-reply-guard-mcp | **自托管 X 发帖/回复 MCP（Cloudflare Workers）**：默认人审再发、提示注入防护、六工具白名单；MIT + CI，作者自注 0.1 尚未亲自部署 | 渠道接入 / X 安全发帖 | GitHub 新建（2026-11-03） |
| paulpierre/gb-launcher | https://github.com/paulpierre/gb-launcher | **一台 Mac 并排多开 Grok Bot 账号**：CLI 建 profile、彩色编号徽章、桌面快捷方式；不改 App 本体，MIT；作者标非官方、依赖未公开行为 | Clients / 多账号 | GitHub 新建（2026-11-03） |
| htetahyan/grok-video-studio | https://github.com/htetahyan/grok-video-studio | **多 Bot 共享机上的成片工具包 Framewright**：真实素材优先、响度实测、proof pack 才算完工、Bot 不擅自发布/花钱；CLI + 多 Bot 交接例，MIT | 内容生产 / 多 Bot | GitHub 新建（2026-11-03） |
| WillingE/financial-freedom | https://github.com/WillingE/financial-freedom | **无感记账：iOS 27 通知 → Grok Bot 例程 → Google Sheets**：快捷指令 + Routine 提示 + 表结构模板，拿不准才问人；MIT，中英 README | Routines / 一人公司垂直 | GitHub 新建（2026-11-03） |
| devonkinghorn/opencode-bridge | https://github.com/devonkinghorn/opencode-bridge | **Bash 桥：让 Grok Bot/Codex 驱动 opencode 会话**（只回用户/助手正文、带 `--since`），附可粘贴 SKILL.md；MIT 单脚本 | Bridges / 编码 | GitHub 新建（2026-11-03） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| liujoe456-glitch/grokbot-family-office | https://github.com/liujoe456-glitch/grokbot-family-office | 中英双语 14 个私人助理模板（秘书/大总管/CFO/法律/健康/翻译/自媒体等）+ 定时任务与 `{{占位符}}`；结构完整但未声明许可证 | Skills / 中文模板 | GitHub 新建 |
| ericpw-coder/grok-bot-buildout-wireframe | https://github.com/ericpw-coder/grok-bot-buildout-wireframe | RevOps Head 脱敏的 43 Bot 组织蓝图（路由/四经理/例程/连接器/只读写默认）；无许可证，含个人角色名需再核 | 多 Bot 作战室 / 迁移 | GitHub 新建 |
| silverdakid/deskbuddies | https://github.com/silverdakid/deskbuddies | 自托管「每 Agent 一台 Linux 桌面」对标 Grok Bot，带审批卡与工作流画布；体量大有 CI，未声明许可证 | Self-hosted | GitHub 新建 |
| Seithreaper/grok-usage-widget | https://github.com/Seithreaper/grok-usage-widget | macOS Übersicht 周额度小组件（池用量/重置/按 Bot 拆分）；MIT 但需自写 `usage.json` 或让 Bot 定时刷新 | 工具 / 额度可见性 | GitHub 新建（2026-11-04） |
| trimble0-60/grok-bot-visualizer | https://github.com/trimble0-60/grok-bot-visualizer | 本地多 Bot 交接流程图可视化（Vite + 可导出单 HTML）；MIT，示例工作流需换成自己的 | 多 Bot 作战室 / 看板 | GitHub 新建 |
| BAILEXIANJUN/grokbot-splash-launcher | https://github.com/BAILEXIANJUN/grokbot-splash-launcher | Windows 启动动画壳（Grok娘 splash → 拉起桌面 App），有便携包与校验；偏趣味启动器 | Clients / 趣味 | GitHub 新建 |
| leeypeng/Grokbot_base | https://github.com/leeypeng/Grokbot_base | 从 ofershap/grok-bot-skills（MIT）按岗位筛选的核验五件套备份；个人角色命名，先作信号 | Skills | GitHub 新建（2026-11-04） |

### Skip（本轮）

空仓/仅标题：adeelibr/openbot、Life0423/agent-skills、Teresa1228/suva-model-image、pini8151gz/grokbot、Vist233/OpenGrokBot；厂商 MCP/目录：aqua-voice/aqua-cursor-plugin、aevent-platform/x-aevent-plugin、K-Lesha/scale-cursor-plugin、swifts1/buybothub-bot-finder、nitturkaryash/qualia-wavelength-cursor-plugin；个人看板/备份：CBMmarketingsolutions/cbm-grok-bot-hq、sgchunge（上轮已 Skip）；ZhimingXUXJTU/job-hunting-helper（求职工作台为主，Grok Bot 只是宿主）；kingzmodzmail-coder/agents-installation（薄安装说明）；白天玩法已收：MarcusYuan/gbdev、ClawDogLabs/slack-grok-bridge、pastdotdev、FeeligWang/dsh、Nicolasdellim/grok-notch、taoning0403 等。X 侧 Article / 模板分享 / 老仓翻炒（orca、skill-index 2026-09）交 X 大 V 或下轮再核。

## 2026-11-04 10:55 Asia/Shanghai · 白天玩法雷达

> 补扫 T7（10:41）之后新建/更新的 Grok Bot 相关仓；X 侧 Article / 模板分享帖交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| yunjian-ai/yunjian-zhibo | https://github.com/yunjian-ai/yunjian-zhibo | **抖音直播间六岗 AI 员工**（运营总控 / 场控盯盘 / 投手千川 / 中控链接公屏 / 话术 / 复盘）：装进 Grok Bot 即用，也能当 Skill 装进 Claude Code；六位共用一份直播间档案、场控判断按岗分发，动钱的事一律推卡片等人点头；中文 README + CI，CC BY 4.0 + MIT；同作者 yunjian 仓已在 inbox | 多 Bot 作战室 / 中文垂直（直播电商） | GitHub 新建（2026-11-04） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| RubikOwl/grok-usage-widget | https://github.com/RubikOwl/grok-usage-widget | macOS 桌面小组件 + 本地网页卡片显示 Grok 用量，读 Grok CLI 登录态、需本机 Xcode 自编；无许可证。与 Seithreaper/grok-usage-widget（MIT，手写 usage.json）同类，二选一待核 | 工具 / 额度可见性 | GitHub 新建（2026-11-03） |

### Skip（本轮）

Rocco5689/azure-grok-mcp-server（个人 Azure/GitHub 监控 MCP，资源名写死）；zengdazui77-cmd/dazuibot（自家中转站导流的替代品）；Crossmint/menta（厂商购物 MCP，非 Grok Bot 专属）；Jbvix/Jbvix-tuglife-hq、cattle-power/bot（无说明）；Seithreaper、leeypeng、kingzmodzmail、Teresa1228、adeelibr（T7 已收/已 Skip）。

## 2026-11-04 16:50 Asia/Shanghai · 白天玩法雷达

> 扫 10:55 之后新建/更新的 Grok Bot 相关仓；X 侧交 X 大 V 雷达。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| deximple/grokbot-activity-log | https://github.com/deximple/grokbot-activity-log | **个人档也能留的防篡改操作台账**：每个 Bot 干活时按 Skill 规则写哈希链账本（任务起止、浏览器动作、审批通过/拒绝），`verify` 校验链、每日审计例程推到你自己的仓；单文件 Python 标准库，MIT | Skills / 安全审计 | GitHub（2026-10-16 建，今日更新） |
| headlessfounder/GrokBotBuzzBridge | https://github.com/headlessfounder/GrokBotBuzzBridge | **把 Grok Bot 放进 Buzz 社区**：成员 @ 提问 → 自托管桥带整串上下文打 Webhook 例程 → Bot 用自己的记忆和连接器答，回到同一线程；Docker 部署 + AGENTS.md 让 Agent 代装，Apache-2.0 | Bridges / 社群 | GitHub 新建（2026-11-04） |
| enrand22/catan-grokbot | https://github.com/enrand22/catan-grokbot | **聊天里玩卡坦岛**：人 + 自己的 Bot + AI 2–4 人混战，让 Bot clone 后存 `SKILL.md` 即可开局；纯 Python 无依赖、英西双语，MIT；偏趣味但是「Skill 包一个 CLI 游戏」的干净样例 | Skills / 趣味 | GitHub 新建（2026-11-04） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| d-gangz/grokbot-skills | https://github.com/d-gangz/grokbot-skills | 团队设计与复盘 Skill 集（design-bots 访谈式设计、bot-audit 出一页编号修改单待批、bot-retro、术语/人物记忆等 12 个）；结构好但未声明许可证 | Skills / 多 Bot 团队治理 | GitHub 新建（2026-11-04） |

### Skip（本轮）

空仓/个人工作区：669258625-oss/grok-bot-only、Vaish01-png/grokbot-agency、Yeahoo09/grokbot-xfer-test、liryanyiran-afk/grokbot、polkm09/grokbot-backup、xiaobao-grokbot.github.io、ANT193/fomo-desk-app；个人看板：ruxerruxe/grokbot-hq；加密钱包插件：coop-collective/anon-plugin；泛 Agent 技能：manhquydev/agent-trust-skills；Pandora-Dee vessel（个人人设，许可不明）。

## 2026-11-05 10:45 Asia/Shanghai · T7 日更雷达

> 扫近 24 小时（约 11-04 02:00Z 起）新建/更新的 Grok Bot 相关仓；去掉白天玩法雷达已收/已 Skip；X `url:github.com` 交叉；周末优先 GitHub 新仓。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Blicae8917/wake-grokbot | https://github.com/Blicae8917/wake-grokbot | **本机 Agent ↔ 在线 Bot 叫醒协议**：零依赖 CLI，本地 inbox 为真相源、wake 只是 nudge；`wake-envelope/1` JSON Schema；密钥不进配置/消息，带 doctor/限流/kill switch；可唤醒 Grok Bot Routine 并回执。中英 README，MIT。本轮最值得看 | Bridges / Claude↔Grok 协作 | GitHub 新建（2026-11-04） |
| antonvnukov/grok-bot-ops-team | https://github.com/antonvnukov/grok-bot-ops-team | **带 ops 层的多 Bot 团队模板**：六类停机问人（send/money/delete/credential/brand/fact）、Deming 审稿岗、跑日志格式门禁、每人 kill 规则与周度退役；AGENTS.md + Use this template，MIT | 多 Bot 作战室 / 模板 | GitHub 新建（2026-11-04） |
| kadaliao/open-super-agent | https://github.com/kadaliao/open-super-agent | **可自托管的 Grok Bot 平替**：多 Bot 群聊交接、后台 Worker、共用 Linux 桌面（CDP）、MCP 应用、确认卡+保险库、演示一遍生成技能；中英 README + CI，MIT（alpha，3★） | Self-hosted / 平替 | GitHub 新建（2026-11-04）+ X |
| SayandipBagchi/agent-evaluator | https://github.com/SayandipBagchi/agent-evaluator | **给 Skill/插件/MCP 打分与安全闸**：12 维评分、沙箱（bwrap/Docker）+ canary、19 个 Grok Bot skill 编排评估流水线，引擎不调模型 API；MIT | Skills / 安全审计 | GitHub 新建（2026-11-04） |
| artisbisers/codex-remote | https://github.com/artisbisers/codex-remote | **非官方远程 MCP：让 Grok Bot 操作本机 Codex CLI 会话**（列会话/开任务/读结果）；本机 loopback + Cloudflare 隧道 + bearer；零 npm 依赖，MIT | Bridges / 编码工人 | GitHub 新建（2026-11-04） |
| RyanNewsom/grokbot-imessage-reader | https://github.com/RyanNewsom/grokbot-imessage-reader | **只读离线读 macOS iMessage**：LaunchAgent 把 Full Disk Access 收窄到 helper.app，附 SKILL.md；不负责发送。MIT，当天新建 | Skills / macOS 渠道 | GitHub 新建（2026-11-05） |
| 0xErnest/grokbot-telegram-hub | https://github.com/0xErnest/grokbot-telegram-hub | **在 Bot 云电脑里跑的 Telegram 网关**：群 @ + 固定群路由 + 主人私聊 Agent 控制；只出站、网关仅 loopback；衍生自 SSBrouhard 桥并扩功能，MIT + CI | 渠道接入 / Telegram | GitHub 新建（2026-11-04） |
| mvcaaa/family-assistant | https://github.com/mvcaaa/family-assistant | **家庭 Telegram 网关**：手机号白名单、每人记忆、Grok Bot webhook 或 xAI API；买/订/删/改记忆等一键主人确认（10 分钟）；Docker + Cloudflare Tunnel，MIT | 渠道接入 / 家庭 | GitHub 新建（2026-11-04） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Wyc2006-31/RelayPilot | https://github.com/Wyc2006-31/RelayPilot | Grok Bot 编排 + Codex 规划审 + WorkBuddy 云端写测 + GitHub 交接的多 Agent 编码工作流；MIT 但标 Gen1 Experimental、端到端云部署 UNVERIFIED | 多 Agent 编码 | GitHub 新建（2026-11-04） |
| DolphinMiner/agentstudio | https://github.com/DolphinMiner/agentstudio | 本机 Mac 统一收件箱：Grok Bot / Muse / Cue 等 A2A·ACP agent 同屏聊，动作先审批；Apache-2.0，X 今日推 | Clients / 多 Agent 收件箱 | X + GitHub（11-03 建，漏收） |
| Blackman99/deskfolk | https://github.com/Blackman99/deskfolk | 自托管「交活走开」队友（自带订阅跑编码 agent）；MIT ~45★，X 今日作者自推额度平替叙事；建于 9 月，本轮作补漏信号 | Self-hosted / 平替 | X + GitHub |
| frankievalentine/lopsi-bot-eve | https://github.com/frankievalentine/lopsi-bot-eve | Vercel Eve 平台上的多 agent 船员模板（改配置走 PR）；Apache-2.0，对标 Grok Bot 形态但绑 Eve | Self-hosted / 平台模板 | GitHub 新建（2026-11-04） |
| cradrrat/bot-shelf-mcp | https://github.com/cradrrat/bot-shelf-mcp | Bot Shelf 目录站 MCP（搜 9000+ 社区 Bot）；远程只读免费，未声明许可证 | Skills / 目录 MCP | GitHub 新建（2026-11-05） |
| Threadlines/cursor-plugin | https://github.com/Threadlines/cursor-plugin | Cursor/Grok Bot 连 Threadlines 看本机编码 agent 状态；MIT 但走 SaaS 中继 | Clients / SaaS 连接 | GitHub 新建（2026-11-04） |
| kyle-bartlett/agent-bus | https://github.com/kyle-bartlett/agent-bus | Claude Code ↔ Grok Bot 双向消息总线（CF Worker MCP+REST）；个人托管、未声明许可证 | Bridges | GitHub 新建（2026-11-04） |
| ev-llh/Skillful-Grok | https://github.com/ev-llh/Skillful-Grok | MIT Skill 仓，目前仅「CV 履历完整性」一条；结构干净但条目少 | Skills | GitHub 新建（2026-11-04） |
| wolfqing/GrokDesktop | https://github.com/wolfqing/GrokDesktop | 原生 macOS 窗：嵌 grok.com Chat + 官方 grok CLI（ACP）；Apache-2.0，OpenGrokBot 作者今日同帖带出 | Clients | X（更新信号） |
| CrepuscularIRIS/Hivebot | https://github.com/CrepuscularIRIS/Hivebot | dsh + dsh-superagent 桌面多 Bot，目标 1:1 对标 Grok Bot；有 README 但未声明 SPDX 许可证 | Self-hosted / 平替 | GitHub 新建（2026-11-04） |

### Skip（本轮）

free-trial-codes/grok-bot（试用邀请推广）；MarsHomestead/panhandle-bot（placeholder）；LanaKor/vedara-mcp-plugin、whoppah/whoppah-plugin（厂商垂直 MCP）；inrilazaldefx-stack/grokbots（纸面交易 PWA）；niboshitofu/grok-bot-work、chapinosuke/grokbot-guide（个人作业/视频导流）；guilherme-vasques-ltda/awesome-ai-radar-list（泛目录薄）；rome-xi/persona-grokbot（Other 许可证）；ExpeditedProjects/hutchdb（上轮已拒通用 agent DB）；OpenGrokBot / exa-pub/grokbot-tunnel / evyevans/content-engine-grokbot / 4zhmv6zvj2-afk/grokbot-essay-writer（README 或 inbox 已有）；空仓/测试同名仓。

## 2026-11-05 10:55 Asia/Shanghai · 白天玩法雷达

> 扫 11-04 起新建的 Grok Bot 相关 GitHub 仓，与 README / inbox / docs 全文去重（含 T7 本日 10:45 一轮）。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| jon-lange/grok-bot-team | https://github.com/jon-lange/grok-bot-team | **「按任务类型逐级放权」的多 Bot 团队**：一个幕僚长做唯一对接人，专员默认只起草，某类任务做稳了才升到「先做后报」；带 10 分钟 QUICKSTART、可贴提示词和脱敏案例；事件唤醒优先、不轮询。MIT。本轮最值得看 | 多 Bot 作战室 / 模板 | GitHub 新建（2026-11-04） |
| medicfsd/mission-control-kit | https://github.com/medicfsd/mission-control-kit | **自托管 Bot 团队看板**：各 Bot 往共享 JSONL 团队日志写一行，box 脚本生成 data.json 推到免费 VM；今日简报、待批（批准/拒绝/完成）、进行中、截止与账单、用量、每 Bot 卡片；密码+passkey 登录。MIT | 多 Bot 作战室 / 看板 | GitHub 新建（2026-11-04） |
| echris6/screen-ask | https://github.com/echris6/screen-ask | **Mac 按住快捷键语音问屏幕**：截图经 webhook 交给自己的 Grok Bot Routine 回答，长任务说「On it」，花钱/发送/删除先问；非官方、无中间服务器，需 imgbb。MIT，附 dmg 与模板 | Clients / macOS 语音入口 | GitHub 新建（2026-11-04） |
| damao-bot-army/pr-webhook-relay | https://github.com/damao-bot-army/pr-webhook-relay | **组织级 GitHub PR webhook → Routine webhook 中继**：CF Worker 校验 HMAC，只转 opened/synchronize 等摘要；CI + gitleaks + SECURITY.md，适合补「仓级监听」缺口。MIT，0.1.0 | Bridges / GitHub 事件 | GitHub 新建（2026-11-04） |
| script-repo/3d-studio | https://github.com/script-repo/3d-studio | **单 Agent 配方：任意机械 → 离线可驾驶 3D 模拟器**：AGENT.md 人设 + 9 步 SKILL.md + 提示词/审稿模板，驱动 Elvar 的 teardown Claude Code skill；「在 Grok Bot 里重建」三步。MIT | Skills / 创意生产 | GitHub 新建（2026-11-04） |
| Clarke-ro/hey-studu-kit | https://github.com/Clarke-ro/hey-studu-kit | **Bot 团队运营的学生学习 PWA**：Coach/机会/资讯/聊天等 Bot 往 App 发课与反馈并推送；Render + Neon 免费部署，带 setup bot 与示例内容。MIT | 垂直配方 / 教育 | GitHub 新建（2026-11-04） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| O23AN/race-grokbot-paylink-kit | https://github.com/O23AN/race-grokbot-paylink-kit | 只用 Stripe Payment Link 卖文件：服务端核 Checkout Session 后才下发，限权 key；Bot 5 天公开实验产物，付款代码需自审。MIT | 一人公司 / 收款配方 | GitHub 新建（2026-11-04） |
| az9713/grokbot-using-claude-demo | https://github.com/az9713/grokbot-using-claude-demo | 演示 Grok Bot 在云电脑上调 Claude Code 给开源 PDF 阅读器 Folio 加功能的 fork；作为「Bot 带编码 agent」实证，不是模板。MIT | Bridges / 编码工人 | GitHub 新建（2026-11-04） |

### Skip（本轮）

空仓/个人：PublicAiAPP/grok-bot、peterpitt/grokbot、seanconn-84/grokbot、edward200112/GrokBotBasement、convenexevents/grokbot-dashboard、wayneleong-byte/grokbot-tower、WZ0425/Bots、jun-eg/grokbot-tunnel、b402261150/grokbot-stage2-xfer、Bodila51/grokbot-spacexsi-engineer、medicfsd.github.io、ArchieDX123/bot-manager；ThePeeps191 两仓（无 README/许可不明）；泛工具：Saurabh960/ai-web-app-tester、plugmcp-ai/plugmcp-mcp、omarchy 主题；HiAPIAI/free-backlinks-for-agents（非 Grok Bot 玩法，个人参考不进公开候选）。

## 2026-11-05 16:55 Asia/Shanghai · 白天玩法雷达

> 扫 11-05 04:00 Asia/Shanghai 起新建的 Grok Bot 相关 GitHub 仓 + X `url:github.com` 交叉，与 README / inbox / docs 全文去重（含本日 10:45 T7、10:55 白天两轮）。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| WealthRxAi/grok-foreman | https://github.com/WealthRxAi/grok-foreman | **Grok Bot 当工头、Claude Code 当工人、人只点 Merge**：早 6 点 Bot 读错误日志/issue 挑 ≤3 个任务写工单 → `run-ticket.sh` 让 Claude Code 开分支、先写失败测试再最小修复 → Bot 验证据、点预览站、发手机简报 → 合并后回看生产日志；含 Bot 指令、三条 routine、CLAUDE.md 工人契约、settings.json、工单模板。编码不耗 Grok Bot 周额度。MIT。本轮最值得看 | Bridges / 编码工人 | GitHub 新建（2026-11-05，配套视频） |
| miniLV/portfolio-research-desk | https://github.com/miniLV/portfolio-research-desk | **六席美股研究台**：工作日一份早报（财报、SEC、估值、期权、论点压力测试），永不下单；市场单 Bot 演六席，回「建六席群」再拆五专岗+一群；中英双语 QUICKSTART/SETUP。MIT | 多 Bot 作战室 / 垂直配方 | GitHub 新建（2026-11-05） |
| digitalgym/grok-bot-usage-harness | https://github.com/digitalgym/grok-bot-usage-harness | **量多 Bot 群聊的唤醒成本**：估算脚本（不耗额度）对比「群聊无 @」与「一个 Lead + 笔记文件」，固定七条测试消息 CSV、前后对比、安静规则提示词；示例数字明确标注为虚构。Python 零依赖，MIT | 省额度 / 团队布局 | GitHub 新建（2026-11-05） |
| aritosi/grokbot-meme | https://github.com/aritosi/grokbot-meme | **零思考表情包 Skill**：本地脚本按原文/事件/情绪选图、限频、去重，返回一行 JSON，模型不挑图不调 API；stdlib Python、附 30 张 CC0 原创表情与测试。中文 README，MIT | Skills / 省额度 | GitHub 新建（2026-11-05） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| 0xMulight/grok-bot-efficiency-kit | https://github.com/0xMulight/grok-bot-efficiency-kit | 「重复巡逻交给脚本」Skill：BSC 新池只读监控、CA 风险查询、Routine 省额度审计；默认只读不交易，MIT；币圈场景偏窄 | Skills / 省额度 | GitHub 新建（2026-11-05） |
| hongkongkiwi/grokbot-control | https://github.com/hongkongkiwi/grokbot-control | Rust MCP + CLI：让其他 AI 管 Bot 的人设/对话/routine/记忆/用量；MIT，但面向泛「xAI 驱动 bot」，是否对接 Grok Bot 产品本体待核 | Bridges / 控制面 | GitHub 新建（2026-11-05） |
| ZhangHalfGod/Grok_Bot_company | https://github.com/ZhangHalfGod/Grok_Bot_company | Three.js 3D 办公室：点工位派任务，Webhook 例程即时派单 + 5 分钟兜底轮询，回复写回本地队列；中文 README，未声明许可证 | 多 Bot 作战室 / 可视化 | GitHub 新建（2026-11-05） |
| bk-han-dev/tip-to-reduce-usage-for-grok-bot | https://github.com/bk-han-dev/tip-to-reduce-usage-for-grok-bot | 可复制的「每周用量审计 Bot」提示词：不编数字、最多 3 条编号建议、等主人回编号才动；未声明许可证且带个人站导流 | 省额度 / 提示词 | GitHub 新建（2026-11-05） |

### Skip（本轮）

shibamondeki139/grok-bot-complete-guide-grok-bot-（自称「已去掉外链与出处」的汇编，来源不明）；bnth09productions-maker/crypto-wallet-hack-watcher（x402 付费查询导流）；bradleyhomelinuxnet-prog 杠杆交易 bot；slchy/miaiglasses2grokbot（小米眼镜帧协议，尚未见 Grok Bot 接入）；thicket-hq/plugins（厂商 SaaS 插件）；belliedmonkey/grok-bot-usage-optimizer（无许可证、与上面审计类重复）；Antilitist 存档修改器；ThePeeps191 两仓（上轮已 Skip）；空仓/个人作业：ChellyRyo/GrokBot、RandiDev-id/grok-bot-demo、fmsseo/Grokbot、xifengzhu/grokbot-website、yzq1990/grok_bot_project_1、两份 grok-bot-hire-job-part1；omarchy 主题（上轮已 Skip）；X 上「破甲」提示词类帖不收。

## 2026-11-06 10:45 Asia/Shanghai · T7 日更雷达

> 扫近 24 小时（约 11-05 02:00Z 起）新建/更新的 Grok Bot 相关仓；去掉 11-05 T7/白天玩法已收/已 Skip；X `search_posts_all` 持续 503，以 GitHub 为主。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| RongleCat/grok-bot-cli | https://github.com/RongleCat/grok-bot-cli | **非官方多账号 CLI + Agent Skill**：多账号登录后所有 Bot 进同一名册（`account:bot`）、跨账号一次性交接、Bot/房间/Skill 就地管理；破坏性命令默认 dry-run 需 `--yes`；单文件跑 Node/Bun，凭据留本机。中英俄 README + CI，MIT。与 README 已收 ScriptedAlchemy/grok-bot-cli（单会话）互补。本轮最值得看 | Tools / Multi-account CLI | GitHub 新建（2026-11-05，铁柱AGI） |
| deluminor/telegram-routine-bridge | https://github.com/deluminor/telegram-routine-bridge | **白名单 Telegram → Routine webhook 桥**：本机长轮询、按聊天批合并相册、Idempotency-Key、2xx 才提交 offset；回复走同白名单 CLI `tgr`；零运行时依赖、Vitest。MIT | Bridges / Telegram | GitHub 新建（2026-11-05） |
| Maliot100X/grokbot-x-launch-kit | https://github.com/Maliot100X/grokbot-x-launch-kit | **研究先行的 X 发帖套件**：Bot 用内置 X 连接器读趋势与实证 → 本仓只吃快照、校验证据、每题三稿待批；代码永不代发。无代码粘贴安装提示词 + Skill，MIT，本地 44 测 | Skills / X 增长 | GitHub 新建（2026-11-05） |
| alfonsobries/laravel-grok-bot | https://github.com/alfonsobries/laravel-grok-bot | **Laravel 通知频道 → Routine webhook**：`toGrokBot` 把异常/工单 JSON 打进例程；多 routine 配置、`grok-bot:ping`、Packagist + 测试。MIT | Bridges / 应用集成 | GitHub 新建（2026-11-05） |
| LeonYew-Ley/grokbot-task-notify | https://github.com/LeonYew-Ley/grokbot-task-notify | **本机包一层 Codex/Claude/Pi**：跑完写 `~/.gb-tasks` 状态与日志，webhook 通知一个 hub Routine，再 SendToAgent 给任务主 Bot 核验回报。Win PowerShell / Linux Bash，MIT | Bridges / 编码工人 | GitHub 新建（2026-11-05） |
| jamesalmeida/pocket-webhook-to-grok-bot | https://github.com/jamesalmeida/pocket-webhook-to-grok-bot | **Pocket 录音就绪 → CF Worker → Grok Bot webhook**：验 Pocket HMAC 后补 `Authorization` 转发原文；免轮询省额度；附 GROK_BOT_SETUP。MIT | Bridges / 语音笔记 | GitHub 新建（2026-11-05） |
| AVGVSTVS96/grokx | https://github.com/AVGVSTVS96/grokx | **给任意 Agent 的免费 X 只读 CLI**：经 Grok Bot 内置 X 工具养一个「X Reader」Bot，`grokx ask` 出 JSON；不耗 X API 额度。非公开后端、更新可能断。MIT | Tools / X 研究 | GitHub 新建（2026-11-06） |
| Eflores1122/grok-bot-open-skills | https://github.com/Eflores1122/grok-bot-open-skills | **可复用求职/履历/开源数据 Skill 包**：remote-job-hunt-mx、ats-cv-tailor、portfolio-github-polish、open-data-mx-pipeline + bot-template；复制即用。MIT | Skills / 求职 | GitHub 新建（2026-11-05） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| ablsite/x-mutual-follow-bot | https://github.com/ablsite/x-mutual-follow-bot | X 互关治理配方（扫未回关、限速代点、回关）；须明确「继续」才点、禁云电脑静默登录；MIT，账号风控自负 | Skills / X 运营 | GitHub 新建（2026-11-06） |
| zhongshezhang-del/grokbot-virtual-office | https://github.com/zhongshezhang-del/grokbot-virtual-office | 等距 3D 虚拟办公室可视化多 Bot 状态（visit/meet/OfficeAPI）；单文件 HTML 可 iframe；MIT。与 ZhangHalfGod 无许可证版同类 | 多 Bot 作战室 / 可视化 | GitHub 新建（2026-11-05） |
| aritosi/grokbot-quick | https://github.com/aritosi/grokbot-quick | macOS 菜单栏伴侣：轮盘选 Bot、截图即问、中转台与悬浮球；同作者 meme 已荐；**未声明许可证** | Clients / macOS | GitHub 新建（2026-11-05） |
| mhccog/bot-phone-line | https://github.com/mhccog/bot-phone-line | 拨英国号经 Twilio IVR + CF Worker 连任意 Bot webhook；**无许可证** | Bridges / 电话 | GitHub 新建（2026-11-05） |
| jiji262/ProkBot | https://github.com/jiji262/ProkBot | 自托管 Host：补丁原版 Mac/iOS 客户端连私有服务端 + Docker 桌面；Other 许可证，逆向补丁合规待核 | Self-hosted / 平替 | GitHub 新建（2026-11-05） |
| algen1/algen-bot | https://github.com/algen1/algen-bot | 受 Grok Bot 启发的自托管多 Agent（每岗 Claude Code + Linux 桌面，ZimaOS）；**无许可证** | Self-hosted / 平替 | GitHub 新建（2026-11-05） |
| vlad-ovsyannikov/Kr-g-grok-bot-hackathon | https://github.com/vlad-ovsyannikov/Kr-g-grok-bot-hackathon | 照顾一位年迈家长的多 Bot 体验原型（晨检、回忆录、服药提醒；非医疗告警）；Wrocław hackathon，MIT | 垂直配方 / 关怀 | GitHub 新建（2026-11-05） |
| diamitani/agent-skills | https://github.com/diamitani/agent-skills | 跨平台 Skill 单仓，`dist/grokbot` 构建；目前仅 project-board-organizer 一条。MIT | Skills / 多平台 | GitHub 新建（2026-11-06） |
| Yixuan-Tao/agent-console | https://github.com/Yixuan-Tao/agent-console | DeepSeek Harness 插件：一屏看本机 Codex/Grok Bot/Marvis/WorkBuddy；Grok 靠窗口自动化；**无许可证** | Clients / 多 Agent | GitHub 新建（2026-11-05） |
| Tygb99/discord-mac-ai-bridge | https://github.com/Tygb99/discord-mac-ai-bridge | Discord 频道 ↔ Mac 上 Grok Bot/Instinct/Pickle 等；依赖 Aside/herdr，个人向。MIT | Bridges / Discord | GitHub 新建（2026-11-05） |
| Noshkoto/hermesmade | https://github.com/Noshkoto/hermesmade | Hermes 插件：分享/一键加社群 Bot，并有「从 Grok Bot 迁出」流程；偏竞品侧。MIT | Self-hosted / 迁移 | GitHub 新建（2026-11-06） |
| Sequaint-Labs/sequaint-os | https://github.com/Sequaint-Labs/sequaint-os | 自称多 Agent 团队模板（Grok Bot 上的 Scotty 建）；Apache-2.0 但 README 几乎空 | 多 Bot 作战室 / 薄 | GitHub 新建（2026-11-05） |

### Skip（本轮）

空仓/占位：wizzz20/GrokBot、kinqcu/grokbot-desk、vip0123/dot-grok-bot、filiplipibusiness-beep/Grok-Bot-pro、yaredtesfaye17-crypto/grok-bot-workspace、firewithinfire/slopjengine、ramion-cloud/grokbot、CodewithMubasher/Calbot（无 README）；Wrocław hackathon 作业：AnnPoberezhna/GrokBot26_hack、Arputikos/GrokBotHackathon2026、rmaziarka/GrokBotHackathonWroclaw、Kabanosk/grok-bot-hackathon-26、kluku/grokbot-hackathon、jknthn/grokbot-hackaton-wroclaw-team1；币圈/导流：0xquqi/EZbot-agentid-grokbot、fh199601-oss/dafeiyu、Lixin311566/GG-Hedge-Fund-OG、bnth09productions-maker（上轮已 Skip）；厂商垂直：jundihuang/shopify-geo-cursor-plugin、theopenapps/openapps-mcp、GlobalTC/drivr-glass、mohsin-tariq-10/factory-tots、moxsea-ab/moxsea-plugin、IxalonDarkstone/Skills（SpicyChat）；个人杂项：juiceboxat/tesla-fleet-public、dip-hbm/hbm-grok-webinar、xztanthropic-svg/live-wallpaper-kit、zhuzhe1983/grok-bot-esp32-stopwatch、lucasdbb/grok-bot-skills-bragaadv、Apeloff1/Skeleton-Test-Readiness-Complete、vituladominik-ai/Grokbot（纸面交易）；上轮已收/已 Skip：WealthRxAi/grok-foreman、miniLV、digitalgym、aritosi/grokbot-meme、0xMulight、ZhangHalfGod、shibamondeki139、ChellyRyo 等。

## 2026-11-06 10:55 Asia/Shanghai · 白天玩法雷达

> 扫 11-05 16:00 Asia/Shanghai 起（相对上轮白天 16:55）+ 相对本日 10:45 T7 去重。GitHub `gh search`/`gh api` 为主；X `search_posts_all` 持续 503，未做 X 交叉补漏。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| IvyYang1999/dispatch | https://github.com/IvyYang1999/dispatch | **本机 Claude Code / Codex / Grok Bot 会话互通**：找会话、投递消息、按收件人看回执；CLI + MCP + hook + Tauri 桌面（Apple Silicon）；Grok Bot 经桌面网关/`gbot` CLI 直达云电脑。消息落盘 Markdown，不上云。MIT。本轮最值得看（T7 漏收） | Bridges / 多会话 | GitHub 新建（2026-11-05，T7 未收） |
| smarzban/rex-grokbot-bridge | https://github.com/smarzban/rex-grokbot-bridge | **Grok Bot 经 Tailscale MCP 看管本机 Rex 终端编码 agent**：列会话/读屏/键入/`spawn_agent`（Claude Code/Codex/Pi/Grok Build）；默认 `watched` 须本机会话 opt-in；完成/卡住 webhook 回 Bot。macOS + launchd，MIT（T7 漏收） | Bridges / 编码工人 | GitHub 新建（2026-11-04，11-05 仍在推） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| rome-xi/persona-grokbot | https://github.com/rome-xi/persona-grokbot | Persona hub 的 Grok Bot 源插件：Agents 页列 Bot/会话、实时推回复、发文字；走非公开桌面协议（grok-bot-sdk），客户端改版可能失效。NOASSERTION | Bridges / Persona | GitHub 新建（2026-11-04） |
| wayneleong-byte/grokbot-tower | https://github.com/wayneleong-byte/grokbot-tower | 等距「指挥塔」看板：读 `status.json` 快照展示花名册/等待；动效与花费仍浏览器模拟。个人向、无许可证 | 多 Bot 作战室 / 可视化 | GitHub 新建（2026-11-04） |

### Skip（本轮）

T7 10:45 已推荐/信号/Skip 的本轮不再重复（含 RongleCat/grok-bot-cli、telegram-routine-bridge、x-launch-kit、laravel-grok-bot、task-notify、pocket-webhook、grokx、open-skills、virtual-office、ProkBot、Krag、hackathon 作业、币圈导流等）；WZ0425/Bots（几乎空 README）；HiAPIAI/free-backlinks-for-agents（SEO 外链农场向，不进 Awesome）；grok-bot-app/grok-bot（自称官方产品镜像，营销向）；Glen-Web-App/best-agent-memory-mcp、plugmcp-ai/plugmcp-mcp、JosssphZhou/poki、majorminorlabs/hermes-voice（非 Grok Bot 玩法主轴）；tal-giladi/grokbot-field-guide（2026-08 旧教程，窗口外）。

## 2026-11-06 16:55 Asia/Shanghai · 白天玩法雷达

> 扫 11-06 10:51 Asia/Shanghai 起（相对上轮白天）新建/明显更新的 Grok Bot 相关仓；相对本日 T7 10:45 + 白天 10:55 去重。GitHub `gh search`/`gh api` 为主；X `search_posts_all` 本轮可用，交叉未见新的可复用公开仓（多为公告转述/额度吐槽/模板清单帖）。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| luxiaolei/grok-bot-team-management | https://github.com/luxiaolei/grok-bot-team-management | **可复用的团队运转 + 账号交接 Skill**：精干花名册、契约落 git、一人交付一人验收、少唤醒；含全量/增量交接目录与三门技能。MIT。本轮最值得看 | Skills / 多 Bot 团队 | GitHub 新建（2026-11-06） |
| Anudorannador/Agent2GrokBot | https://github.com/Anudorannador/Agent2GrokBot | **任意 MCP 客户端 → 固定 webhook 对端 Bot**：FastAPI MCP 2.0 占住 SSE，Bot 心跳/进度/结果 POST 回调；超时降级为 `task_get` 轮询不丢结果。Python+uv+测，MIT | Bridges / MCP↔Webhook | GitHub 新建（2026-11-06） |
| incredible404-rgb/GrokBot-tray | https://github.com/incredible404-rgb/GrokBot-tray | **Windows 托盘伴侣**：关窗/最小化进托盘、开机静默、隐藏后内存回收（测约 1.2GB→70MB）；中英 UI，预编译+源码，MIT。与早前 Skip 的 foztrk 小工具同类但完整可发 | Clients / Windows | GitHub 新建（2026-11-06） |
| huanxxxx/grokbot-ops-lab | https://github.com/huanxxxx/grokbot-ops-lab | **证据驱动的 X×公众号冷启动运营账本**：人在环硬约束、`fact/method/stop/hypo` 沉淀、可复用 playbooks（X 手回三门禁、公众号单主条）；README 声明 CC0（GitHub 未挂 SPDX） | 垂直配方 / 运营实验 | GitHub 新建（2026-11-06） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| stantheman0128/threads-mcp | https://github.com/stantheman0128/threads-mcp | 本机 Threads MCP（浏览/语意搜/受控写）+ 专文 GROK-BOT 远程 mcp-remote 说明；体量大，**未声明许可证** | Bridges / Threads | GitHub 新建（2026-11-06） |
| koshikraj/birdie | https://github.com/koshikraj/birdie | 本机 agent 总线：Claude Code/Codex/Grok CLI ↔ webhook Grok Bot 双向消息（线程+回执）；Go 单二进制+onboard。**无许可证**；与本日已荐 IvyYang1999/dispatch 互补 | Bridges / 多会话 | GitHub 更新（建于 11-02，本窗仍推） |
| shagghiesuperstar/grokbotzoneMCP | https://github.com/shagghiesuperstar/grokbotzoneMCP | 把 grokbot.zone 目录站挂成 HTTPS MCP（搜/分类/提交须人确认）；MIT。同作者 zone 站此前已作信号 | Bridges / 目录站 MCP | GitHub 新建（2026-11-06） |
| cricle2914/GrokBot-Personal | https://github.com/cricle2914/GrokBot-Personal | 个人 Windows 多 Bot 桌面（Tauri+FastAPI）；一阶段尚无模型回复/多 Bot 通信。**无许可证**，偏自建平台非产品玩法 | Self-hosted / 早期 | GitHub 新建（2026-11-06） |

### Skip（本轮）

空仓/占位：qingfenglailai/grokbot1、kinqcu/grokbot-desk（上午已 Skip）；DiweiQuantum/cursor-cloud-agent-smoke（仅冒烟沙箱说明）；mingz009988-ops/meme-desk-pwa（无 README、纸面交易 PWA）；noramimiyuma/x-feed（薄 RSS 托管、无许可证）；上午 T7/白天已收的 RongleCat、dispatch、rex-grokbot-bridge、grokx、hermesmade、ablsite 等不再重列；X 侧模板清单/额度吐槽/Linear 产品官宣转述不进 inbox。

## 2026-11-07 10:45 Asia/Shanghai · T7 日更雷达

> 扫近 24 小时（约 11-06 02:00Z 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉；去掉 11-06 T7/白天玩法已收/已 Skip。周末以 GitHub 为主。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Jackywine/jackywine-digital-garden-skills | https://github.com/Jackywine/jackywine-digital-garden-skills | **flomo L1 + 本地 Obsidian 双层数字花园 7 Skill**：装机引导、推特进 flomo、全文剪藏+wikilink、学徒写库纪律、相关笔记/孤儿扫描；`npx skills add` 即装，配套 kepano/obsidian-skills；隐私与「先问再改」硬约束。MIT。X 长文热帖配套开源。本轮最值得看 | Skills / 知识库 | GitHub 新建（2026-11-06；白天漏收）+ X 交叉 |
| junze-xu/grok-bot-cn | https://github.com/junze-xu/grok-bot-cn | **中文契约模板库**：自称 33 模板 / 13 技能 / 8 例程 / 12 模式；Setup Bot 粘 START.md 拉 PROFILE，或 `npx github:junze-xu/grok-bot-cn`；JSON Schema+分享安全 CI。MIT，多语言 README + Pages 目录 | Templates / 中文团队 | GitHub 新建（2026-11-06） |
| onittindwani-ai/bot-showdown-test-kit | https://github.com/onittindwani-ai/bot-showdown-test-kit | **Grok Bot vs Claude Code 五场销售任务公平对决**：合成线索/回复、预先锁死答案钥+SHA、计分脚本与双方结果；禁开答案钥直到跑完。MIT，可复用评测骨架 | Tools / 评测 | GitHub 新建（2026-11-06） |
| onittindwani-ai/ai-employee-kit-openai-dots-grok-bot | https://github.com/onittindwani-ai/ai-employee-kit-openai-dots-grok-bot | **25 名销售/招聘/运营「AI 员工」提示词**：每人一套 Dots + Grok Bot 安装文、8 个团队交接配方、CHOOSER 选型表与安全权限说明；只起草不代发。MIT | 一人公司 / 岗位配方 | GitHub 新建（2026-11-06） |
| ganeshsavara61-netizen/autonomous-company | https://github.com/ganeshsavara61-netizen/autonomous-company | **终端 CEO 指挥五岗公司**（CEO/CTO/CMO/CFO/COO）：本地 Python 免费模式 + 可选 `gbot` CLI 接真 Grok Bot；站会/董事会命令与测试。MIT | 多 Bot 作战室 / 一人公司 | GitHub 新建（2026-11-06） |
| ArtificialNotImbecile/herdr-grok-bridge | https://github.com/ArtificialNotImbecile/herdr-grok-bridge | **只读 Herdr MCP 桥**：白名单 list/get/read pane + bridge_info；硬拒 send-keys/起进程；输出截断+脱敏。MIT。与已收 phoobobo/frysquint 等写向桥互补 | Bridges / Herdr | GitHub 新建（2026-11-06） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| pysol-dev/omo-grok | https://github.com/pysol-dev/omo-grok | OmO 启发的 SQLite 多 Bot 工作流总线（webhook 唤醒角色 Bot）；自陈 PARTIALLY INSTALLED / NOT OPERATIONAL；**无许可证** | Bridges / 编排总线 | GitHub 新建（2026-11-06） |
| growthflare-ignite/grokbot-gtm-team | https://github.com/growthflare-ignite/grokbot-gtm-team | 冷邮件 GTM 多 Bot + Claude/Codex playbook；与 README 已收 timscheuerai/grokbot-gtm-team 高度同构；**无许可证** | 一人公司 / GTM | GitHub 新建（2026-11-06） |
| galaxy-co-ai/1line-mcp | https://github.com/galaxy-co-ai/1line-mcp | Cursor/Grok Bot 市场插件壳：挂托管 1line MCP 共享记忆；MIT 但本体为 SaaS 列表页，几乎无本地代码 | Bridges / 记忆 SaaS | GitHub 新建（2026-11-06） |
| wenjiany312-hub/starsky-amazon-botteam | https://github.com/wenjiany312-hub/starsky-amazon-botteam | 亚马逊美站 11 角色运营团队（选品→广告→复盘）；Grok Bot/OpenBot/StarSky；**无许可证** | 垂直配方 / 电商 | GitHub 新建（2026-11-06） |
| appygudu/flyhigh-bots | https://github.com/appygudu/flyhigh-bots | Flyhigh 免费模板目录静态站（从 x.ai/bot 与目录 API 拉证）；**无许可证**，偏展示站非配方 | Templates / 目录站 | GitHub 新建（2026-11-06） |
| RonniKahalani/Ideator | https://github.com/RonniKahalani/Ideator | 问题→证据挑战→点子→pretotype 材料的 Ideator Bot 配方包（不代发）；文档全、样例齐；**无许可证** | Skills / 产品研究 | GitHub 新建（2026-11-06） |
| oneplaceai/grok-bot-plugin | https://github.com/oneplaceai/grok-bot-plugin | 欧洲房产检索/收藏/联系卖家的厂商插件说明；**无许可证** | Bridges / 垂直插件 | GitHub 新建（2026-11-06） |
| theopenapps/tumble-grok | https://github.com/theopenapps/tumble-grok | Tumble 体测/家庭活动游戏的 Grok Bot/Cursor/Claude 插件配置；MIT，场景偏窄 | Skills / 垂直插件 | GitHub 新建（2026-11-06） |

### Skip（本轮）

空仓/占位：worldcoin/world-id-grokbot-plugin、a-hao-1234/grok-avatars、jiekong240-lang/grok-bot-local-deploy-research、satadru-codes/grokbot-hide-seek、stone06/grokbot、shadyalsuleiman-glitch/Grok-bot、DhanushkaUdayantha/GROKDeskBots-NeuraLink-Multiagent-Framework、darondicker729-oss/Grokbot（几乎空 README）；Kinggoz18/grokbot-local-only-mode（仅一条 PROMPT.md）；agentshorts/SpaceX-GrokBot-Stock-Predictor（个股日内研究笔记）；mingz009988-ops/meme-desk-pwa（白天已 Skip）；alxspiker/hermes-xai-budget-guard（Hermes 插件管 xAI 调用预算，非 Grok Bot 玩法）；窗口外旧仓仅 X 清单带过：imbavirus/grokbot-bridge-plugin（10-08）、tsconfigdotjson/vibe-os-native（10-30）、mateuscmtropical/cloudbot、ianpilon/clewbert、galleonlabs/hypergrok-trading-desk、dax8it/spudstack（Hermes）；11-06 白天已收 luxiaolei/Anudorannador/GrokBot-tray/huanxxxx/threads-mcp/birdie/grokbotzoneMCP/GrokBot-Personal 等不再重列。


## 2026-11-08 10:44 Asia/Shanghai · T7 日更雷达

> 扫近 24 小时（约 11-07 02:41Z / 昨天 T7 ~10:41 Asia/Shanghai 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉；去掉 11-07 T7 已收/已 Skip（周末无白天玩法雷达）。周末以 GitHub 为主。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| remorses/grokhouse | https://github.com/remorses/grokhouse | **等距办公室里看 Bot 干活并能对话**：每 Bot 一间房（忙着跳桌、空闲散步、睡着打呼）；未读消息出漫画气泡，关掉即已读（同步官方 App），打字可回消息；墙钟/闹钟显示下次例程，软木板贴 todo。演示站 grokhouse.dev。走 Cursor 浏览器登录调非公开 `GrokBotService`（文档写明随时可能失效）。MIT，4★。本轮最值得看 | Clients / 多 Bot 可视化 | GitHub 新建（2026-11-07） |
| aritosi/GrokBot-Cloudstandby | https://github.com/aritosi/GrokBot-Cloudstandby | **云电脑保活 Skill**：按时长或截止时刻安静保活，可登记已有进程或按指示启动命令，到期停保活、不擅停任务；多登记共用一个看守。中日英 README + 测试，粘贴即可装。同作者 grokbot-meme 已荐。MIT | Skills / 云电脑保活 | GitHub 新建（2026-11-07） |
| nisaral/grokbot-conductor | https://github.com/nisaral/grokbot-conductor | **本机 Windows 指挥层**：监视本机文件夹/时钟/唤醒词/「需要你」，用 `grokbot://` 打开已有 Bot 并把简报放到剪贴板；在官方 App 里发送前不耗额度。`orders.yaml` 映射 Bot 名，可交接下一岗。pytest + SECURITY.md。MIT | Clients / Windows 本机唤醒 | GitHub 新建（2026-11-07） |
| onehumanbeing/grok-spaces | https://github.com/onehumanbeing/grok-spaces | **给现有 Bot 的 macOS 持久 HTML 工作区**：Bot 写页面与业务逻辑，本仓提供宿主、状态存储和 action/result 桥；不改官方 App。CLI + AppKit 窗、loopback 服务、SDK 与 minimal 示例、CI。MIT | Clients / macOS 工作区 | GitHub 新建（2026-11-07） |
| Wecko-ai/grokbot-to-hermes | https://github.com/Wecko-ai/grokbot-to-hermes | **把 Grok Bot 迁到 Hermes 的实战套件**：来自 27 个 Bot、6 个团队、2 天迁移。不替代官方 importer，补它留下的坑（超 cap 记忆、云路径、无处投递的例程、每年重复的过期例程、双边同时跑）。默认 dry-run、禁导入密钥、一次只迁一个。MIT。与已信号 Noshkoto/hermesmade 互补 | Self-hosted / 迁移 | GitHub 新建（2026-11-07） |
| leoresendedop-sys/grokbot-staff | https://github.com/leoresendedop-sys/grokbot-staff | **Hermes 内幕僚团队 + 可选 fail-closed 桥**：本地 chief 分发给专家；可选 webhook/inbox 把长任务交给你自己的 Grok Bot，结果回写收集。方向是 Hermes→Grok Bot（与已收 grokbot-hermes-bridge 的 Grok→Hermes 相反）。不走不存在的公开 REST API。MIT | Bridges / Hermes↔Grok | GitHub 新建（2026-11-07） |
| cxc1344/OpenGrokBot-Android | https://github.com/cxc1344/OpenGrokBot-Android | **安卓原生多 Bot 协作平替**：自带 API Key 建员工，总经理流水线立项→派活→审查返工；群聊/`ask_bot` 私聊可见，Keystore 加密 Key，危险命令 Guard。Kotlin+Compose，CI 出 debug 签名 APK（P0，作者称尚未真机完整验收）。MIT | Self-hosted / Android 平替 | GitHub 新建（2026-11-07） |
| QinGeneral/ai-quota-bar | https://github.com/QinGeneral/ai-quota-bar | **macOS 菜单栏看剩余额度**：Cursor / Grok Bot 每周额度 / Codex / Kimi，读本机已登录态、不另存 token；低于 40%/15% 变色。Grok Bot 周额度与 Cursor 月额度分开显示。MIT | 工具 / 额度可见性 | GitHub 新建（2026-11-07） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| riyabakhtiani/bay-area-event-kit | https://github.com/riyabakhtiani/bay-area-event-kit | 数据脱敏的活动推荐团队套件：主 Bot + Scout/Curator/Bargain，每晚 0–3 条待接受；含 tracker Page 与脚本。只推荐不代订。结构完整但**未声明许可证** | 垂直配方 / 本地生活 | GitHub 新建（2026-11-08） |
| mlzerotoheroyoutube/idea-to-product | https://github.com/mlzerotoheroyoutube/idea-to-product | 想法/草图→可点原型→私有仓 SPEC + MVP PR；附 GROKBOT.md 让 Bot 在云电脑跑 MCP（`build_prototype`/`ship_current` 等）。**无许可证**，需自备 xAI key | Skills / 产品原型 | GitHub 新建（2026-11-08） |
| Hanif-adedotun/grok-imessage | https://github.com/Hanif-adedotun/grok-imessage | 经 Spectrum 把 iMessage 当前门接到 Routine webhook，回复走蓝泡。MIT 但 README 自陈 **scaffold、未生产就绪**（桥与循环仍是 stub） | Bridges / iMessage | GitHub 新建（2026-11-07） |
| Mr-Kafkabysea/OPC-Office | https://github.com/Mr-Kafkabysea/OPC-Office | Live 3D 办公室看板（ntfy + Cloudflare relay，私有频道链接当密码）。**无许可证**；与已信号 virtual-office 同类，本轮已荐 grokhouse 更完整 | 多 Bot 作战室 / 可视化 | GitHub 新建（2026-11-07） |
| Nothing1024/dsh-workbench-plugins | https://github.com/Nothing1024/dsh-workbench-plugins | DSH 工作台插件：同一来源栏看 DSH 会话、Herdr/Ovis 与 Grok bot。MIT，但 Grok 侧靠本机 cookie/SSO 非官方接入 | Clients / DSH 工作台 | GitHub 新建（2026-11-07） |
| jdkabattles/muse-grok-collaboration-monitor | https://github.com/jdkabattles/muse-grok-collaboration-monitor | 只读 mailbox 仪表盘可视化 Muse×Grok 协作路由/回执；不执行任务、不公开正文。**无许可证** | Clients / 协作看板 | GitHub 新建（2026-11-07） |
| mittal-parth/companion | https://github.com/mittal-parth/companion | 自称 Grok Bot / Muse 开源平替的 WIP monorepo（有 PLAN/AGENTS）；**无 README、无许可证** | Self-hosted / 早期平替 | GitHub 新建（2026-11-07） |
| lionatzion/stitch-your-pitch-public | https://github.com/lionatzion/stitch-your-pitch-public | 求职履历/求职信裁剪的公开安装说明 + 虚构样例（配套已发布 Grok Bot 模板）。**无许可证**，仓内几乎只有文档 | 一人公司 / 求职 | GitHub 新建（2026-11-07） |
| imans-ai/imans-grok-plugin | https://github.com/imans-ai/imans-grok-plugin | Imans 商业 MCP 的插件包装（Apache-2.0 + skills/plugin 清单），偏厂商 SaaS 连接器 | Bridges / 垂直插件 | GitHub 新建（2026-11-07） |
| Randy0609/grok-wechat-bridge | https://github.com/Randy0609/grok-wechat-bridge | 微信 AI ↔ 主 GrokBot 双向多模态（文/语音/图/视频）验收合同；目前几乎只有 README，未见实现代码。**无许可证** | Bridges / 微信 | GitHub 新建（2026-11-07） |

### Skip（本轮）

空仓/占位：michaellu20051024-alt/Grok-Bot-skill、alexeykrol/GrokBotCEO、xpandabletech/xtlab-plugins、dziduchm/grokbot2hermes（仅一行 README）、pohtrader/Grok-bot、sikandarkuk12-beep/Grok-Bot、tomhnb321/grok-bot、princejain756/ghw-builders-grok-bot-workspace、edward0714/GrokBot-aiwebsites、buildersfilmstudio/GrokbotDavinci、magnolialtd/email-assets；偏题/非产品玩法：FoalSupervise/grok-4-7-abliterated（越狱提示词）、chekusu/pinku-chat-plugin（约会插件）、nodirbek5298/phakinsaepo/urbanfashion 等交易台、ju0o/7Day_GrokBot（Bot 做的记忆拼图游戏而非配方）、AIBanlv/AIBanlv-Bot（桌面数字人，非 Grok Bot）、HalphMuitaGrana/grokbot-skills（写给 OpenMausBot 衍生 Bots 应用）、saber0616/dsh-grok-night-theme（Harness 主题）、sirealco/grok-bot-icon-generator、anorthernman-developer/framevr-grokbot-journey（旅程笔记）、connect-world-1985-ai 能力边界快照（无 README）、MartyDaMonster/agent-space（个人看板/白名单）、gregboero/netbird-admin-mcp（通用 NetBird MCP，Grok Bot 侧尚未核验）；已有条目的镜像/fork：OpenMausBot/OpenMausBot（指向已收 milind-soni/OpenMausBot）、dv365lab/dv365-OpenGrokBot（OpenGrokBot 再发行+导流码）；昨日 T7 已 Skip：a-hao-1234/grok-avatars、jiekong240-lang/grok-bot-local-deploy-research；X 交叉多为已收 OpenMausBot/Codync、额度吐槽与 Hermes 迁移讨论，窗口外旧仓仅带过不重列（mateuscmtropical/cloudbot、ianpilon/clewbert、jaredtrichard/grok-factory、serenakeyitan/agent-org-chart、leepokai/Codync、tecadrise-ai/TecAdRiseBot、transparent-pegasus/utsurigi-agent-hub、StandEasyOps/worker-dock-public、Daijunfan/Aexus-Bot）；破甲/代理方法论 free-dam-man/agent-deploy-memory-grok 跳过。

## 2026-11-09 16:25 Asia/Shanghai · 周更候选

> 从 11-02 周更后各轮「推荐」71 条 + 近 7 日 GitHub 公开搜索 + github-radar 11-09 下午补报里挑 5 条，gh 只读实查星标/许可；全文见 box /workspace/awesome-grokbot/candidates-2026-11-09-weekly.md。待 sitin 确认后才改 README。

### 候选（5 条）

1. [remorses/grokhouse](https://github.com/remorses/grokhouse) - 等距办公室里看 Bot 干活并能对话：每间房一个 Bot（忙着跳桌、空闲散步、睡着打呼），未读消息出漫画气泡，关掉即已读（和官方 App 同步），打字就能回；墙钟显示下次例程，软木板贴 todo。演示站 [grokhouse.dev](https://grokhouse.dev)。走 Cursor 浏览器登录调非公开 `GrokBotService`（文档写明随时可能失效）。4★ · MIT · 11-07 更新。
   - 建议分类：👥 多 Bot 团队　标签：`multi-bot` `dashboard` `unofficial`
2. [sarbarshem/grok-bot-3d-campus](https://github.com/sarbarshem/grok-bot-3d-campus) - 把仓库链接交给主 Bot，它按 skill 在你自己的 Vercel 上建一座 3D 校园作战室：每个团队一间房，能看谁在干什么、额度电池、待你审批的事项，一键把指令送回主 Bot（对外动作仍先在聊天里确认）。演示站用虚构数据、不连真实 Bot。本周日更雷达漏收。32★ · MIT · 11-07 更新。
   - 建议分类：👥 多 Bot 团队　标签：`multi-bot` `3d` `dashboard` `skill`
3. [junze-xu/grok-bot-cn](https://github.com/junze-xu/grok-bot-cn) - 中文契约模板库：现为 151 个模板 / 16 支团队 / 14 个技能 / 8 条例程，带自主性等级（默认第一周只起草）。建一个 Setup Bot 粘 `START.md` 即可拉 PROFILE，也可用 `npx` 或 [Pages 目录](https://junze-xu.github.io/grok-bot-cn/) 复制。JSON Schema + 分享安全 CI。0★ · MIT · 11-08 更新。
   - 建议分类：📦 模板与目录 / 💼 中文一人公司　标签：`templates` `chinese` `teams`
4. [Jackywine/jackywine-digital-garden-skills](https://github.com/Jackywine/jackywine-digital-garden-skills) - flomo（L1 闪念/推特）+ 本地 Obsidian（全文剪藏与 wikilink）双层数字花园 7 个 Skill：装机引导、推特进 flomo、剪藏质检、学徒写库纪律、相关笔记与孤儿扫描；`npx skills add` 即装，配套 kepano/obsidian-skills。点名 Grok Bot 的导入方式，默认先问再改、不代发。7★ · MIT · 11-06 更新。
   - 建议分类：🧩 技能与玩法　标签：`skill` `obsidian` `flomo` `zh`
5. [dabingfy-dot/solo-to-team-skills](https://github.com/dabingfy-dot/solo-to-team-skills) - 一人统筹多个 AI 助手的中文协作技能包：派活→收回→核证→验收登记，四支技能加模板和脱敏案例。正文写明 Codex / Cursor 等「支持」，Grok Bot 为「支持，需手动配置」。11-07 新建，约两天涨到 353★。353★ · MIT · 11-07 更新。
   - 建议分类：🧩 技能与玩法 / 💼 中文一人公司　标签：`skill` `multi-agent` `zh`
   - 注意：Grok Bot 不是首发一等支持，收不收由 sitin 定。

注：1 和 2 都是多 Bot 可视化，grokhouse 能对话、3d-campus 带审批和额度且本周雷达漏收；3 的 GitHub 简介仍写「33 个模板」，仓内已核到 151 份 PROFILE；5 星虽高但是通用协作包。

### 没收（一句话理由）

- DIYgod/pinky（1145★）、codejunkie99/iphone-control（7★）、janestreet/agent_skills 等：通用手机 / Agent 工具，未把 Grok Bot 当主场。
- 上周周更已提：BeatAPI/grokbot-growth、number5meme/grokbot-larkbot-bridge、Revve-AI/grokbot-webhook-adapter 未进 README，不重复提；souhun / bot-codex-delegate / 微信·QQ 桥已收入 README。
- 本周日更已荐、扎实但本轮名额让给更缺的条目：IvyYang1999/dispatch、WealthRxAi/grok-foreman、jon-lange/grok-bot-team、luxiaolei/grok-bot-team-management、RongleCat/grok-bot-cli、Blicae/wake-grokbot（由 Blicae8917 迁仓）、Anudorannador/Agent2GrokBot、aritosi/GrokBot-Cloudstandby 等，留 inbox。
- QinGeneral/ai-quota-bar：与已收 quota-ring / GrokGauge / usage-checkin 同质。
- kadaliao/open-super-agent（7★）、DolphinMiner/agentstudio（8★）、zhiruiai/PandaMate、cxc1344/OpenGrokBot-Android、frankievalentine/lopsi-bot-eve：平替或客户端，README 该分类已较满，留观察。
- ArtificialNotImbecile/herdr-grok-bridge：与已收 phoobobo/grokbot-bridge-herdr 互补（只读），先留 inbox。
- 无许可证或说明书不全：huanxxxx/grokbot-ops-lab（README 自称 CC0，GitHub 未挂 SPDX）、0xkaize/grok-bot-handbook、mittal-parth/companion 等。
- 交易 / 自动投递 / 越狱：Noisyxl/grokbot、PoetCoderJun/hk-auto-apply、FoalSupervise/grok-4-7-abliterated。
- 其余（又一件 IM 桥、Windows 托盘、Hermes 迁移、像素办公室、今天刚出现的 local-forms / Raycast 扩展）：同质、小众或过新，留 inbox。

## 2026-11-09 16:58 Asia/Shanghai · 白天玩法雷达

> 扫 11-08 T7 之后（约 11-08 02:44Z / 10:44 Asia/Shanghai 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉。今早 T7 / 白天雷达额度耗尽失败，本轮补窗；对照 11-08 T7 与 11-09 周更 5 条候选去重。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| RongleCat/grok-bot-anywhere | https://github.com/RongleCat/grok-bot-anywhere | **从微信「转发到其他应用」、Finder/资源管理器、拖放或全局悬浮框，把此刻上下文投递给指定 Bot**：每 Bot 可设入口、投递方式和固定前缀；本地收件记录看有没有落地/发出，不明结果不自动重发。非官方 Electron 客户端（观察本地协议，上游改版可能失效）。v0.1.4，macOS 已实机验证，Windows 部分验证，Linux 暂不支持。同作者 grok-bot-cli 已荐。49★，MIT。本轮最值得看 | Clients / 投递入口 | X 交叉（建于 10-29，11-08 仍推；T7/周更未收） |
| brett-technical/grokbot-local-forms | https://github.com/brett-technical/grokbot-local-forms | **本机 HTML 表单问人、提交后落盘并 webhook 通知发起的 Bot**：答案写成带时间戳的 `.md` + `.json`（可进 Obsidian），不覆盖旧稿；密钥只进本机 `webhook.local.json`、不进对话。例程闲置 1 小时自停。问题文案和选项须先问发起 Bot，不代编。MIT | Skills / 人在环表单 | GitHub 新建（2026-11-09） |
| saphid/grok-bots-raycast | https://github.com/saphid/grok-bots-raycast | **Raycast 原生扩展给已有 Bot 发消息**：`fleet say hi` → Return 审稿 → ⌘Return 才发送；凭据藏在 `~/.config/grok-bots`，不进 Raycast 偏好或仓库；保存请求 ID、不自动重试，历史只留投递状态不存正文。走 Bot 的 webhook 例程，不是 xAI 推理 Key。CI + SECURITY.md + 测试，MIT | Clients / Raycast | GitHub 新建（2026-11-08，11-09 仍推） |
| vinhyard/grokbot-cli | https://github.com/vinhyard/grokbot-cli | **非官方 macOS CLI**：经已登录的桌面 App 列出/读线程/发一条/创建或更新 Bot；`doctor` 检查环境，破坏性命令要 `--yes`，`send` 可 `--dry-run`。Node 22、无运行时依赖。MIT + 测试。与已收 ScriptedAlchemy（单会话）和 RongleCat（多账号）互补 | Tools / CLI | GitHub 新建（2026-11-08） |
| DeVFirmino/grok-bot-names-and-icons | https://github.com/DeVFirmino/grok-bot-names-and-icons | **按职责给已有 Bot 起短名 + 配 35 枚统一图标**：目录/清单/提示词/SKILL.md，粘一句让 Bot 读 SKILL 后协助整理；改名前先提案，图标在各 Bot 自己的对话里应用并核对侧栏。不装应用。MIT | Skills / 花名册整理 | GitHub 新建（2026-11-08） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| simo255/jobfather | https://github.com/simo255/jobfather | 求职 Bot 配方：每岗先给你看简报等你点头，再起草答案等你改，最后核对简历和答卷才提交一次；LinkedIn 只用只读 MCP，投递走浏览器。有公开模板。MIT。与跳过的 hk-auto-apply（自动投）不同 | 垂直配方 / 求职 | GitHub 新建（2026-11-09） |
| pku-zhb/grokbot-weixin-bridge | https://github.com/pku-zhb/grokbot-weixin-bridge | 自托管微信 iLink 桥：经 grokbot-cli 的 `rpc --stream` 把单主人消息/附件转给云端 Bot，SQLite 记投递；带测试。MIT。依赖非公开 RPC，且需自备已授权 iLink 账号，账号风险自负 | Bridges / 微信 | GitHub 新建（2026-11-08） |
| agentmsgr/agentmsgr-mcp | https://github.com/agentmsgr/agentmsgr-mcp | 把 Muse / Grok Bot / 自建 bot 拉进同一群聊的托管 MCP 说明；服务本身非开源。Grok Bot 因每账号只能挂一个自定义 MCP，需走 shared 地址，文档写明端到端仍在测。MIT | Bridges / 多 Agent 群聊 SaaS | GitHub 新建（2026-11-09） |
| 0xkaize/grok-bot-handbook | https://github.com/0xkaize/grok-bot-handbook | 单文件 A–Z 手册（安装、套餐、Cursor、多 Bot、例程、安全与 webhook），约 54KB。周更已点名；**未声明许可证** | 文档 / 手册 | GitHub 新建（2026-11-09） |
| akari-sora/grok-bot-cli | https://github.com/akari-sora/grok-bot-cli | 非官方 gbot fork：把 Bot 的记忆/技能/例程/历史/文件迁到 Hermes、Muse 或 Your dot，并检查迁完还能用；号称不耗 Grok Bot 额度。2★，MIT。镜像，权威仓在 GitLab。同作者还有 trinity-cli（一条 CLI 管 Your dot / Grok Bot / Muse） | Tools / 迁移 CLI | GitHub 新建（2026-11-08） |
| 540709984-dotcom/earth-online-agentdna | https://github.com/540709984-dotcom/earth-online-agentdna | 人主导的多 Bot 协作协议 + 五支 Skill（任务契约、证据转录、独立校对、经验升级提案、调研主流程）；演练示例标明虚构。MIT。部署说明同时写 WorkBuddy 与 Grok Bot | Skills / 多 Bot 协议 | GitHub 新建（2026-11-08） |
| zhiruiai/PandaMate | https://github.com/zhiruiai/PandaMate | 开源自托管 Grok Bot 平替（群聊分工、带出处的网页调研、对话里打开交付物）；Apache-2.0，体量大。周更已标「该分类较满、留观察」 | Self-hosted / 平替 | GitHub 新建（2026-11-08） |
| fuchu8/AIQuotaMonitor | https://github.com/fuchu8/AIQuotaMonitor | macOS 菜单栏看 Codex / Cursor / OpenCode Go / Grok Bot 额度，读本机已登录态。原生 Swift，**未声明许可证**；与已荐 QinGeneral/ai-quota-bar 同质 | 工具 / 额度可见性 | GitHub 新建（2026-11-08） |

### Skip（本轮）

空仓/占位：tonycodes/grok-bot-updates、suzeeparker/GrokBot_Lean-Input、jicaixin/GrokBotWorkshop、leumasnot-prog/bots-grok、shintarou1008a/grok-bot-study、gjjjjjun/grok-bot-tokei、Ali747711/grok-bots（无 README，Hermes 上的 Grok-Bot 风格研究稿）；T7 已 Skip 的 michaellu20051024-alt/Grok-Bot-skill 不重列。薄仓/说明书不全：megahertz8/grok-bot-packs（无许可证的模板 skill 包）、rphoward/bot-mover-tools（某个 Bot Mover 模板的辅助脚本）、nlaughter100/grokbot-javis-dashboard（个人日报快照的 JARVIS 皮肤，无许可证）、15266/portable-agent-orchestrator（无许可证编排层）、Happyman67/grok-bot-guide、AXXDM/grok-bot-bluebook-site、Johnnnmai/valenx-bots（付费模板结账备份页）。偏题：First-Integration-Partners-Llc/grok-build-cli-slack-plugin（Grok Build CLI 的 Slack 插件，非 Grok Bot 产品玩法）、codejunkie99/iphone-control（周更已标通用手机工具）、thellis954/bodyhop、yagomp/statsproven-cursor-plugin、jianhuachan/GrokBot-Web3Learn、Leluth/rakazo-evaluation。交易 / 自动投递：tim871199-eng/grokbot-trading、imqwinsi/grok-bot-trading-paper、PoetCoderJun/hk-auto-apply（周更已拒）。X 交叉多为已收 OpenMausBot 平替热帖、额度吐槽；补到 RongleCat/grok-bot-anywhere。


## 2026-11-10 10:50 Asia/Shanghai · T7 日更雷达

> 扫近 24 小时（约 11-09 02:43Z / 10:43 Asia/Shanghai 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉；对照 11-09 16:58 白天玩法雷达与周更 5 条去重（昨晨 T7 失败，白天已补 11-08 10:44 之后窗口）。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| nickvasilescu/grokbot-clone | https://github.com/nickvasilescu/grokbot-clone | **自托管 Grok Bot 平替**：自备 Grok API + Orgo 云电脑 + Composio 连应用；每 Bot 有人设/记忆/桌面，可委派、例程、语音；写操作默认先批。本地 SQLite，MIT。约 42★ / 24 fork（一天内）。声明与 xAI 无关。白天雷达时间窗内漏收。本轮最值得看 | Self-hosted / 平替 | GitHub 新建（2026-11-09 15:50 Asia/Shanghai；白天漏收） |
| jason201385-commits/grokbot-manager-kit | https://github.com/jason201385-commits/grokbot-manager-kit | **Grok Bot 当主管、Codex/Claude Code 当工人**：需求与验收留在 Bot，改档交给本机 CLI；可选 AGY 或全新只读 session 做审查。含共享记忆规则、`run-task.sh` 与日志。MIT。默认 `codex exec --dangerously-bypass-approvals-and-sandbox`，须在已授权且隔离的环境改掉再跑 | Bridges / 编码工人 | GitHub 新建（2026-11-09） |
| txchai/fix-my-grokbot | https://github.com/txchai/fix-my-grokbot | **两分钟只读检查，把 Mac 上 Mail/信息/日历/备忘录/浏览器的「手」还给 Bot**：一条脚本触发系统授权提示，再打印 PASS/FAIL/SKIP 和修复步骤；不改系统设置。MIT | Tools / macOS 授权 | GitHub 新建（2026-11-09） |
| thiago-desa/conductor | https://github.com/thiago-desa/conductor | **主 Bot 路由到舰队里对口专岗**：粘 `agents/conductor.md` 作人设，配 routing/getting-started Skill；记得各岗职责、交接不泄密、只在等人拍板时打扰。带虚构日例、evals 与公开模板链接。MIT | 多 Bot 作战室 / 路由 | GitHub 新建（2026-11-09） |
| hudsonwa/grok-bot-twin | https://github.com/hudsonwa/grok-bot-twin | **在 Hermes 里给每个 Grok Bot 做一个孪生档**：Twins 页对照两边、冲突并排自选、可回滚；真同步需另装同作者 MIT 工具 botport。姓名/简介可自动，指令与例程仍是手动手册，避免两边同时跑。可用虚构 Bot 做 60 秒演示。MIT | Bridges / Hermes 迁移 | GitHub 新建（2026-11-09，本窗仍推） |
| echris6/grok-bot-worlds | https://github.com/echris6/grok-bot-worlds | **按你自己的 Bot 花名册适配的直播 3D 世界**：把 `GROKBOT.md` 贴给主 Bot 即可接入；无配置时用虚构团队演示。MIT，体量完整 | Clients / 多 Bot 可视化 | GitHub 新建（2026-11-09） |
| bobdivx/bot-cockpit | https://github.com/bobdivx/bot-cockpit | **独立可视化驾驶舱**：团队/Bot 卡片、等距办公室、用量 CSV 导入、可选 MCP 自愿上报；不读账号 cookie、不代你登录。真实模式从空账本开始，演示数据标明虚构。法文界面，测试 + Docker，MIT | Clients / 多 Bot 看板 | GitHub 新建（2026-11-09） |
| plutunieer/bot-bridge | https://github.com/plutunieer/bot-bridge | **让 Bot 经过本机 localhost 操作你自己的 Chrome**：开标签、读页、点按、输入；Python 桥只听 127.0.0.1，请求要本机 token。MIT。建于 10-26，11-09 仍推并在 X 交叉出现，此前雷达未收 | Bridges / Chrome | X 交叉（更新于 2026-11-09） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| z20093100011/grokbot-x-mcp-bridge | https://github.com/z20093100011/grokbot-x-mcp-bridge | 把订阅自带的官方 X 工具面桥成本地 MCP，给 Claude Code/Codex 拿原始 Tweet JSON（不是让 Bot 写摘要）；webhook 叫醒例程，Tailscale 或 CF Worker 回传。**未声明许可证**；勿转售额度 | Bridges / X MCP | GitHub 新建（2026-11-09） |
| Tomanocy/grokbot-linkedin-playbook | https://github.com/Tomanocy/grokbot-linkedin-playbook | 便携 LinkedIn 人设玩法：六图卡片草稿、每条发布先批、早盘数据与工作日人脉清单、周一增长简报。有 Pages。**未声明许可证** | 垂直配方 / LinkedIn | GitHub 新建（2026-11-09） |
| ferretgeek/prokbot-plus | https://github.com/ferretgeek/prokbot-plus | 自托管 ProkBot 增强：补 Windows 客户端，接 Anthropic/OpenAI Responses，并修联网与生图。3★，Noncommercial。给官方客户端打补丁，合规待核。与已信号 jiji262/ProkBot 同类 | Self-hosted / 补丁私服 | GitHub 新建（2026-11-09） |
| nicope/code-crew | https://github.com/nicope/code-crew | 在自己的 Claude 订阅上跑 Grok Bot 风格的持久 Bot（人设、记忆、例程、互相 @、审批卡），底层是本机 Claude Code。MIT | Self-hosted / Claude 平替 | GitHub 新建（2026-11-08，11-09 仍推） |
| Ajay702/onebot-company | https://github.com/Ajay702/onebot-company | 一人公司：YAML 章程 + 审批门 + 教会即例程；参谋协调调研→撰稿→审核，默认不代发。走 xAI API，离线 demo 可用。**未声明许可证** | 一人公司 / 编排 | GitHub 新建（2026-11-09） |
| halksun/tesla-china-grokbot-playbook | https://github.com/halksun/tesla-china-grokbot-playbook | 特斯拉中国区 Fleet 只读监控操作手册（默认不控车、密钥不出库）；在云电脑上装已信号的 naoiseirwin/Tesla-Grokbot-Connector，并补中国区 Auth。MIT | 垂直配方 / 车主 | GitHub 新建（2026-11-09） |
| Macro-Harder/bridge-advanced | https://github.com/Macro-Harder/bridge-advanced | 给 Grok Bot/Muse 这类没有本地 CLI 的个人 Agent 用的 AgenC 桥：MCP 问询 → 网关校验 → `handoffs/` 文件夹投递，收讫即清除。Apache-2.0 | Bridges / AgenC | GitHub 新建（2026-11-09） |
| thiago-desa/repo-operational-head | https://github.com/thiago-desa/repo-operational-head | 把 Bot 的图与 Skill 洗成可公开的 MIT 证明仓，发布前须人批准。同作者 conductor 的配套头。MIT | Skills / 开源发表 | GitHub 新建（2026-11-09） |
| perron/grok-astryx-skill | https://github.com/perron/grok-astryx-skill | 非官方 Skill：教 Agent 用 Meta Astryx CLI/MCP 搭 UI；带安装助手与测试。MIT。文档写明落盘路径更贴近 Grok Build，Grok Bot 产品侧需自行存为私有 Skill | Skills / 设计系统 | GitHub 新建（2026-11-09） |
| cshape/phone-bud-plugin | https://github.com/cshape/phone-bud-plugin | Phone Bud 厂商插件：让 Bot 在美加拨真实电话并回摘要；托管 MCP + Skill，先问再打。MIT，仓很薄，按次计费 | Bridges / 垂直电话 SaaS | GitHub 新建（2026-11-09） |

### Skip（本轮）

空仓/占位：AdamJayDaley/grokbot、ssttmkkw-hue/ForGrokBot、diegodoc1111/agente-grok-bot、cleetus1974/Grok-Bots-、darythe-commits/mychief、enknot96/grok-bot-agent-clone；越狱：CentiOutpostWedge/grok-4-7-abliterated（与已 Skip 的 FoalSupervise 同类）；早期壳/实验克隆：mr-developer-88/grok_bot_alternative、yuvraj-thakur-exe/grok-bot-clone、tamaugo/grok-clone、rio-beagle/beagle-voice-agent、freddyfearful/obsidian-private、Viyozc/botstyle_studio；已收仓的再包装：barry-dev-ops/barry（README 即已收 elie222/rakazo）、brian-porter/openbot（基于本轮所荐 grokbot-clone）、nickferrantelive/grok-bot-worlds（echris6 的个人端口）；厂商薄插件/过窄模板：kealrog/spendpoint-plugin、coop-collective/enginebox-plugin、vhbmsp/grok-mobbi-pro、swiftverse/photo-to-3d-grokbot；thiago-desa 同系列垂直岗（citi-assist / computer-fix / website-betterment / open-weight-expert）结构同构，本轮只信号 conductor 与 repo-operational-head。窗口外旧仓仅 X 带过、不以 Grok Bot 为主场：Vizards/DotX（10-17，任意 Personal Agent 接本机 Codex）、Pluviobyte/saas-growth-agents（10-30，426★ 多平台增长包）、kinopeee/grokbot-mcp-bridge（9 月后未推）、promptadvisers/gratis（桌面助手接 Claude/Codex，仅免责声明提到 GrokBot）、janestreet/agent_skills（周更已拒）、Fei2411/DS-Bot（DeepSeek Harness）、amosblomqvist/learnharness、LinespottingOrg/GrokBuildRemote-Agents（Grok Build）、every-app/seo-party-skills。11-09 白天已收/已 Skip（含 grok-bot-anywhere、local-forms、trading、hk-auto-apply、handbook 等）不重列。


## 2026-11-10 10:55 Asia/Shanghai · 白天玩法雷达

> 扫 11-09 16:58 之后（约 11-09 08:58Z 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉。今早 T7（10:50，`7447e61`）已覆盖重叠窗口，本轮只补漏。未改 README。

### 推荐

无。今早 T7 已收的 8 推荐本轮只去重不重列。

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Macro-Harder/grokbot-rag | https://github.com/Macro-Harder/grokbot-rag | 给 Grok Bot 用的本地优先 RAG：对 AgenC 桥协议文档做 BM25+向量检索，经 stdio MCP 返回带出处的数据信封（当数据、不当指令）。标准库核心 + 测试；优先用命令在 Bot 云电脑拉起，禁止裸公网 URL。Apache-2.0，1★。同作者 bridge-advanced 已信号；昨天白天与今早 T7 均漏收 | Bridges / RAG MCP | GitHub 新建（2026-11-09 12:23 Asia/Shanghai，本窗仍推） |

### Skip（本轮）

今早 T7 已收/已 Skip 不重列。补漏后仍不进候选：littletechbird/otherhand（11-01 建，X 称可给 Grok Bot 控 Windows 桌面并加光环，README 未点名 Grok Bot，是 vercel-labs/agent-desktop 的无头驱动）；kinqcu/grokbot-desk（无许可证个人看板）。

## 2026-11-10 16:55 Asia/Shanghai · 白天玩法雷达

> 扫 11-10 10:51 之后（约 11-10 02:51Z 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉。今早 T7（10:50，`7447e61`）与白天雷达（10:55，`3074cd6`）已覆盖条目只去重不重列。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| krishhgg/t3-watch | https://github.com/krishhgg/t3-watch | **零额度看守**：T3 Code / Codex / Claude Code 线程结束、要输入或失败时才叫醒 Grok Bot（也可 webhook）；等待期间不耗 Bot 额度。单二进制 Rust，多路看守共用一个后台 daemon 和一次上游 long-poll；只读状态、不代答不问不批准。macOS/Linux，尚无发行包须源码编译。MIT 或 Apache-2.0。今早 T7 漏收（仓名无 grok，08:28 已建），本窗仍推并在 X 交叉出现。与已收 DoubleDipCode/grokbot-t3-bridge 互补。本轮最值得看 | Tools / 零额度看守 | X 交叉（建于 11-10 08:28 Asia/Shanghai；白天漏收） |
| Agentasy-AI/grokbot-lab | https://github.com/Agentasy-AI/grokbot-lab | **Claude Code ⇄ Grok Bot 的 ping/pong 协议 + 双 Skill**：Claude 侧发白名单任务，Grok Bot 当远程传感器跑完带回证据；ping 只带数据不当指令，无证据的 ok 视为未核实。人批门（排程、外联、重试、删除等）。webhook 体限制 3KB。状态 draft，对真实 Bot 7/7 实测。MIT | Skills / 跨 Agent 协议 | GitHub 新建（2026-11-10） |
| ycaistudio/grokbot-token-saver | https://github.com/ycaistudio/grokbot-token-saver | **多 Bot 团队把每周额度用满一周的通用 Skill**：10 招整理自 @vartekxx 的额度文，另补 12 条实战（交接/投胎、群组只派一个负责 Bot、错三次就停、改规则只通知受影响岗）。把仓链给主 Bot 存为 skill 即可；改 routine 须先批。繁中/英/日 README + SKILL.md。MIT | Skills / 省额度 | GitHub 新建（2026-11-10） |
| MrLongMo/homer-hermes-kit | https://github.com/MrLongMo/homer-hermes-kit | **一个窗口把 Grok Bot 连工作文件搬到 Hermes（Mac Apple 芯片）**：安装 Hermes、选账号、复制提示词让 Bot 打包再搬入；有图文教程和 unittest（假 hermes）。密钥只留本机。与已荐 grokbot-to-hermes / grok-bot-twin 互补（本仓是可下载的搬家 GUI）。MIT | Bridges / Hermes 迁移 | GitHub 新建（2026-11-10） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| SvenKunkka/multi-platform-bot-inbox | https://github.com/SvenKunkka/multi-platform-bot-inbox | macOS 收件箱：把文字/链接/附件存本地，补说明后投给已有 Grok Bot；飞书/钉钉/QQ 经独立接收服务回源会话。TypeScript + 测试，0.1.0 候选，正式签名和真账号验收未完成。**未声明许可证**。与已荐 RongleCat/grok-bot-anywhere 同类 | Clients / 多平台收件 | GitHub 新建（2026-11-10） |
| markjamesc/grok-bot-analyst-workflow | https://github.com/markjamesc/grok-bot-analyst-workflow | 父 Bot 编排、六个子岗做设计/评审/R/SQL 的五阶段分析流程设计；闸门代码未实现。文档声明**不授予许可证**、禁止复用。对照仓 chatgpt-solo-analyst-workflow 是单聊 ChatGPT 稿，非 Grok Bot 配方 | 垂直配方 / 分析流程 | GitHub 新建（2026-11-10） |
| zyamzin/cursor-usage-bar | https://github.com/zyamzin/cursor-usage-bar | macOS 菜单栏看 Cursor 用量与 Grok Bot 周额度及重置日；读本机已登录的 Cursor 会话，不另传数据。Swift，MIT，可下 DMG。与已荐 QinGeneral/ai-quota-bar 同质 | 工具 / 额度可见性 | GitHub 新建（2026-11-10） |

### Skip（本轮）

空仓/个人产出：shuyaofficial/grokbot-output（无 README 的 HTML/PPT dump）、Gambit025/My_Grok_Army（一行 README 的个人 3D 看板，无许可证）、wyldephyre/grok-bot-releases（模板版本 JSON，无许可证）。交易：alinor3141/grok-trading-bot（无 README）。偏题：markjamesc/chatgpt-solo-analyst-workflow（ChatGPT 对照稿）；luobinger/PerkRadar（福利聚合，Grok Bot 只是部署帮手）；thomasbek3/hermes-bot-kit（8 月旧仓，Hermes 界面插件，X 有更新帖但不作本窗新配方）。今早 T7/白天已收或已 Skip（含 grokbot-rag、grokbot-t3-bridge、OpenMausBot 热帖、wrokBot 自推）不重列。

## 2026-11-11 10:45 Asia/Shanghai · T7 日更雷达

> 扫近 24 小时（约 11-10 02:50Z / 昨天 T7 ~10:50 Asia/Shanghai 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉；对照 11-10 T7（10:50）与白天玩法雷达（10:55 / 16:55）已收/已 Skip 去重。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| PeerRich/grok-bot-macos-menu-bar | https://github.com/PeerRich/grok-bot-macos-menu-bar | **macOS 菜单栏看已有 Bot 正在干什么**：图标显示当前任务（「处理中」「正在搜索」），多个活跃 Bot 会标 `+N`；菜单上半是干活的、下半是其余，点一下在官方 App 里打开。名单只读本地花名册，实时状态需把官方 App 以 `--remote-debugging-port=9347` 拉起（只听 127.0.0.1，文档写明本机任意程序可检控窗口）。非官方，依赖内部实现（测过 0.79.3），上游改版可能失效。MIT，2★，Swift。@peer_rich 自荐。本轮最值得看 | Clients / macOS 菜单栏 | X 交叉（建于 2026-11-10 21:12 Asia/Shanghai；白天漏收） |
| AleiahLock/elon-man | https://github.com/AleiahLock/elon-man | **把 Grok Bot 做成桌面机器人**：3D 打印身体 + ESP32 固件 + Mac 上的核心（视觉/语音/邮件桥/可选 MCP），Bot 当大脑；可先用假身体联调。命令走 `policy.yaml` 白名单，付费/外发/删除仍回审批卡；本机执行默认「每次先问」。带零件清单、接线、Grok Bot 配置与人设提示。MIT，1★ | Skills / 硬件机器人 | GitHub 新建（2026-11-11 06:23 Asia/Shanghai） |
| webazarashi/mori-webhook-relay | https://github.com/webazarashi/mori-webhook-relay | **Mori 会议摘要好了才 webhook 叫醒 Grok Bot**：Cloudflare Worker 每 15 分钟查 Mori MCP，只有新摘要（可带全文）才触发例程，空转不耗 Bot 额度；失败下次重试。附受付例程提示词和部署清单。非官方，MIT。作者在 X 自荐 | Bridges / 零额度 webhook | X 交叉（建于 2026-11-10 18:37 Asia/Shanghai） |
| AlizayAyesha/awesome-grok-bot-skills | https://github.com/AlizayAyesha/awesome-grok-bot-skills | **Grok Bot 技能目录 + 原创 fullstack 开工清单**：索引指向上游技能原文（不复制正文），另附 14 层上线检查的 `fullstack-vibe-coder`（含 references）。写了在 Grok Bot 里粘贴/拷贝技能文件夹的用法。MIT，1★ | Skills / 目录 | GitHub 新建（2026-11-11 08:38 Asia/Shanghai） |
| AlizayAyesha/grok-social-media-skills | https://github.com/AlizayAyesha/grok-social-media-skills | **七个社媒增长 Skill**（X / LinkedIn / Threads / Instagram / TikTok / Facebook / Reddit）：计划、起草、去 AI 味、主页体检；外发帖/回复/评论/私信一律先留草稿等人批，不编数据。改编自 MIT 技能并写明出处。LICENSE 为 MIT（GitHub SPDX 显示 NOASSERTION），1★。同作者目录已荐 | Skills / 社媒 | GitHub 新建（2026-11-11 08:08 Asia/Shanghai） |
| moeghashim/seo-growth-playbook | https://github.com/moeghashim/seo-growth-playbook | **SEO / AI 搜索增长审计 Skill**：按站抓 Search Console 等数据做技术与内容审计，输出 now/next/later 路线图和审批清单；默认只读，改站与付费须主人点头。可当 Grok Bot / Cursor 插件技能用。MIT | Skills / SEO | GitHub 新建（2026-11-10 17:49 Asia/Shanghai；白天漏收） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| joeseesun/xnews | https://github.com/joeseesun/xnews | 用 Grok Bot 例程（官方 X 工具 + WebFetch）抓海外创始人长文 / Article / 爆款 AI 视频，改写成中文站 xnews.qiaomu.ai，附原文。约 77★ / 9 fork。11-05 建、此前雷达因仓名无 grok 漏收，本窗仍推并在 X 出现。README 写 MIT，但仓内没有 LICENSE、GitHub 未挂许可证 | 一人公司 / 内容站 | X 交叉（更新于 2026-11-11） |
| julienlieben/grokbot-gtm-setup | https://github.com/julienlieben/grokbot-gtm-setup | ColdIQ 完整 GTM 安装包：一个参谋路由多岗（客户运营/名单/回复/日报/内容），外发一律草稿先批；把总说明交给主 Bot 即可安装。结构完整，与已收 GTM 团队配方同类；**未声明许可证** | 一人公司 / GTM | GitHub 新建（2026-11-11 03:22 Asia/Shanghai） |
| matheusvelloso/ai-usage-bar | https://github.com/matheusvelloso/ai-usage-bar | macOS 菜单栏 + Windows 托盘看 Claude / Grok Bot 等额度，读本机已登录态。MIT，有站点与安装包。与已荐 QinGeneral/ai-quota-bar 同质，增量是 Windows | 工具 / 额度可见性 | GitHub 新建（2026-11-11 00:51 Asia/Shanghai） |
| steelzeh/grok-bot-menubar-patch | https://github.com/steelzeh/grok-bot-menubar-patch | 给官方 macOS App 打补丁，把 Dock 图标改到菜单栏（测过 0.79.3/0.79.4）。会改签名、可能影响自动更新和系统授权；**未声明许可证** | Tools / 官方 App 补丁 | GitHub 新建（2026-11-11 05:04 Asia/Shanghai） |
| get-octane/octane-grok-plugin | https://github.com/get-octane/octane-grok-plugin | Octane 厂商插件：只读看店铺业绩/库存/发票，带出处。Apache-2.0，仓较薄 | Bridges / 垂直插件 | GitHub 新建（2026-11-11 01:59 Asia/Shanghai） |
| Synapsr/louez-assistant-plugins | https://github.com/Synapsr/louez-assistant-plugins | Louez 租赁店厂商插件（Claude Code / Cursor / Grok Bot）。MIT，偏 SaaS 连接器 | Bridges / 垂直插件 | GitHub 新建（2026-11-10 21:14 Asia/Shanghai） |
| openbook-contacts/openbook-plugin | https://github.com/openbook-contacts/openbook-plugin | Openbook 通讯录厂商插件（Claude / Grok Bot / Cursor）。MIT，仓较薄 | Bridges / 垂直插件 | GitHub 新建（2026-11-11 05:53 Asia/Shanghai） |
| sendblue-api/sendblue-grok-plugin | https://github.com/sendblue-api/sendblue-grok-plugin | Sendblue 消息/送达状态的 OAuth MCP 插件说明；**未声明许可证**，偏厂商 | Bridges / 垂直插件 | GitHub 新建（2026-11-11 05:26 Asia/Shanghai） |

### Skip（本轮）

空仓/薄仓/个人产出：ChihiroNishioka/grokbot-job-engine（README 仅 299 字节、无许可证）、tishan-perera/grokbot（个人组织拷贝）、Joseemm96/donbots（个人配置移交）、samuelsaid2003/cold-email-starter-workspace（无许可证冷邮工作区）、dadutss/cpanel-cwp-transfer（无许可证、场景过窄）、Atlas-Grok/grok-atlas、Shea-Nelson/grok-lessons、hhhhhh1140/agent-center、masalaempire/GrokBot-Desktop-Pet（均无许可证或说明书不全）、errrrrrr-jpg/grok-bot、zwsfpn4j6r-oss/grok-bot、Black-sys-dot/grok-bot-ripeoff、realbrianhanson/grokbot-automation-done-for-you（营销站）。交易 / 越狱：tim871199-eng/grokbot-trading、alinor3141/grok-trading-bot、Jake-SX9/GarvisTrades、CentiOutpostWedge/grok-4-7-abliterated（上轮已 Skip，本窗仍推）。已有仓再包装：techfundoffice/cloudbot-staging（主页即 OpenMausBot，体量镜像）。偏题 / 非 Grok Bot 主场：Soren-Starck/t3-bot（T3 Code 的 iPhone 配套，只是「长得像」）、PhilipAD/wow-mentor（通用游戏教练，Grok 只是可选远程 bot）、YogurtJ/OhMyBuddy、SmartStudio/baize-bot、feigbar-SimpleDot/simpledot-agent-studio、guidsen/hermes-grok-bot-skin、vellxw/hermes-bots-console、stephenlb 本地 Ollama 长名仓、pavel444-byte/free.（Dots 平替）、jonzobrist/customer-player-cards（概念+构建提示，未写成 Grok Bot 配方）、asgeirtj/system_prompts_leaks（提示词泄露清单）。窗口外旧仓仅 X 带过不重列：milind-soni/OpenMausBot、CopilotKit/OpenBot、Crokily/pi-durable-bot、krishhgg/t3-watch、DoubleDipCode/grokbot-t3-bridge、thomasbek3/hermes-bot-kit、luobinger/PerkRadar、rystedtcreative/run-cards、transparent-pegasus/utsurigi-agent-hub、oliexe/paseo-bots、stanley50z/cua-bot、rome-os/rome 等。11-10 T7/白天已收或已 Skip（含 grokbot-lab、token-saver、t3-watch、coop-collective/enginebox-plugin、megahertz8/grok-bot-packs、PoetCoderJun/hk-auto-apply、shuyaofficial/grokbot-output 等）不重列。


## 2026-11-11 10:53 Asia/Shanghai · 白天玩法雷达

> 扫 11-10 16:55 之后（约 11-10 08:55Z 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉。今早 T7（10:45，`27a7290`）已覆盖重叠窗口，本轮只补漏。未改 README。

### 推荐

无。今早 T7 已收的 6 推荐本轮只去重不重列。

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| TubeLabHQ/youtube-research-skills | https://github.com/TubeLabHQ/youtube-research-skills | TubeLab 的 YouTube 研究技能包（爆款/赛道/竞品/评论/标题公式等）：README 写了 Grok Bot 用法——按 URL 加 MCP、完成登录，再把仓或 `SKILL.md` 交给 Bot 存为私有 skill（先存 `tubelab-mcp`）。MIT，15★。需自备 TubeLab 账号，偏厂商。建于 11-04、仓名无 grok，今早 T7 漏收；本窗仍推并在 X 交叉出现。本轮最值得看 | Skills / 厂商 YouTube | X 交叉（更新于 2026-11-10 21:48 Asia/Shanghai） |
| Betagg/grokbot-reset-core | https://github.com/Betagg/grokbot-reset-core | 从 GrokBot Rest 抽出的额度重置报告核对小工具：在 90 分钟窗口内看官方/核心/社区报告是否互相印证，并估算已过去多久；不拉帖、不通知，示例为虚构。MIT，带测试。今早 T7 漏收 | 工具 / 额度重置核对 | GitHub 新建（2026-11-10 17:45 Asia/Shanghai） |

### Skip（本轮）

今早 T7 已收/已 Skip 不重列。补漏后仍不进候选：wybc092109/grokbot_blog（空仓）、kuwabara-agent/grokbot-template-context（仅 README、无许可证，作者写明配方不用它）、serafin-meshy/meshy-grok-discovery-test（临时 A/B fixture，非发行）、forge-agent-hub/forge-agent-hub（联系邮箱带 grokbot.com，非产品玩法）、RMac-triadicIntelligence/relational-transitions-v0.1（关系实验，Grok Bot 只是评审席）、markjamesc/grok-chatgpt-review-analyst-workflow（已信号 analyst-workflow 的第三版，仍不授权）、WangPhu26/grok-bot-desk（交易台）、neojou/myants（个人蚂蚁模拟游戏产出，非配方）。偏题：RokaSwK/threebot（T3 上的 Grok Bot 风格客户端，与已 Skip 的 t3-bot 同类）、sandhiveio/How-Could-I-Be-Hacked（通用安全技能，Grok Bot 只是可接入的 Agent）、aiedwardyi/Wink（编码订阅桌面壳，Grok 指 CLI 工人）、ericzakariasson/x-feedback-agent（Slack+Cursor 修 bug，非 Grok Bot 配方）。窗口外旧仓仅 X 清单带过不重列：simo255/multiBot（2026-09-02 建，67★ MIT 工厂模板，9 月后未推，此前未进 inbox）、mandarwagh9/botroster、Archive228/foreman、serenakeyitan/agent-org-chart、jaredtrichard/grok-factory（后两条此前已收或已 Skip）。

## 2026-11-11 16:51 Asia/Shanghai · 白天玩法雷达

> 扫 11-11 10:53 之后（约 11-11 02:53Z 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉。今早 T7（10:45，`27a7290`）与白天雷达（10:53，`39b0cae`）已覆盖条目只去重不重列。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| ArtemXTech/grok-agent-threads | https://github.com/ArtemXTech/grok-agent-threads | **让 Grok Bot（或任何 MCP 客户端）在手机上列出、搜索、阅读、回话并新开本机 Claude Code 会话和 Codex 线程**：服务只听 127.0.0.1，经 `tailscale serve`（不用 Funnel）进 tailnet；云端 Bot 走官方 Tailscale OAuth 加入。故意没有删除/归档/停止工具。Python + 测试 + SECURITY.md，带安装脚本和给 Bot 的 setup 提示。MIT。本轮最值得看 | Bridges / Tailscale MCP | GitHub 新建（2026-11-11 11:07 Asia/Shanghai） |
| Chasen-Liao/grokbot-and-pi | https://github.com/Chasen-Liao/grokbot-and-pi | **把重活派给同机 Pi，做完再 webhook 叫醒 Grok Bot 验收**：`pi-task` 落盘是唯一事实来源，通知体不含正文和密钥。基于已在 inbox 的 robbin/grokbot-local-agent，增量是任意 Provider/默认模型、多 Bot 通知隔离、`pi-guard` 拦灾难性删除（可请人放行）、空闲超时熔断，以及把仓链给 Bot 按 AGENTS.md 自配的技能。删除/外发/付款/发帖/`git push` 不交给 Pi。MIT | Bridges / Pi 派活 | GitHub 新建（2026-11-11 11:14 Asia/Shanghai） |
| kaitoflow/tiko | https://github.com/kaitoflow/tiko | **按项目绑定的 Grok Bot 内部专家，给 Codex 做分析、共创方案、质询和独立评审**：技能 + 任务封套 + CLI/MCP 桥，同一项目跨会话复用。发送回执不代表完成，未知结果不能直接重试；`ensure` 可能创建或重命名 Bot。需 Node 24+、已登录 Grok Bot 与兼容 grok-bot-cli（按 0.12.5 整理）。有无需登录的协议测试。MIT | Bridges / Codex 专家协作 | GitHub 新建（2026-11-11 14:53 Asia/Shanghai） |
| harkawataryan/grok-bridge | https://github.com/harkawataryan/grok-bridge | **非官方 MCP：让本机 Claude 操作 Windows 上的 Grok Bot 桌面应用**（测过 0.79.4）：用只听 127.0.0.1 的 DevTools 端口往输入框打字并读回复；可发消息、列 Bot、切换、显示或隐藏窗口。文档写明开着调试端口时本机任意程序都能控窗口，官方改版可能失效；若用隧道暴露 HTTP 接口，持有 URL 的人可以让 Bot 打电话或发邮件，须保管。MIT，目前仅 Windows，Node 22+ | Bridges / 官方 App | GitHub 新建（2026-11-11 12:13 Asia/Shanghai） |
| Ramyrae/file-shepherd | https://github.com/Ramyrae/file-shepherd | **文件整理 Grok Bot 模板**（可在应用市场搜 File Shepherd）：先只读扫描再给你计划，确认后才移动、改名或删除。含精确重复文件（先比大小再 SHA-256）、下载/桌面清扫、大文件审计、截图命名建议、外置盘备份对照。仓库是技能与安装说明的便携副本，不是命令行程序。MIT | 垂直配方 / 文件整理 | GitHub 新建（2026-11-11 11:32 Asia/Shanghai） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| bangzhu-commit/ai-balance-board | https://github.com/bangzhu-commit/ai-balance-board | macOS 悬浮额度看板（FoxCode / Codex / Grok Bot），查询不消耗模型 token。Grok Bot 额度走本机 Chrome 扩展读已登录的 Cursor 用量页，不导出 cookie。MIT，Apple Silicon 预览包，ad-hoc 签名尚未公证。与已荐 QinGeneral/ai-quota-bar 同质 | 工具 / 额度可见性 | GitHub 新建（2026-11-11 16:42 Asia/Shanghai） |
| BTCUP99/grok-bot-avatar-tool | https://github.com/BTCUP99/grok-bot-avatar-tool | 非官方 macOS Apple Silicon 头像工具：42 款原创头像，按 Bot 分别记住选择；不改官方 App 文件和签名。MIT，有发行包和 portable 测试，社区预览（测过 0.79.4，作者写明本轮未做完整端到端验收）。与已信号 avatar-gallery / maid-avatar 同向，但是可运行工具 | Fun / Avatars | GitHub 新建（2026-11-11 15:59 Asia/Shanghai） |
| rxshah/RI | https://github.com/rxshah/RI | 给非编码 Grok Bot 舰队用的瘦身技能包：从 pstack 挑选原则、验证、blast-radius 等，另补 5 条家规（先删、失败快退出、不可逆才问、额度天花板、记住两次就写成规则）。须另装 pstack 与 tinycharts（后者禁止再分发）。MIT，体量薄、无测试 | Skills / 非编码舰队 | GitHub 新建（2026-11-11 14:30 Asia/Shanghai） |
| Amitro123/grok-bot-control-room | https://github.com/Amitro123/grok-bot-control-room | 3D 校园控制中心（three.js）：团队房间、任务板、审批托盘、用量电池；公开演示是虚构花名册和浏览器模拟，真部署经 webhook 交给主 Bot，数据在私有 Vercel Blob。README 写 MIT，许可证在 `app/LICENSE`，GitHub 未挂 SPDX。与已荐 grok-bot-worlds / bot-cockpit 同向 | Clients / 多 Bot 可视化 | GitHub 新建（2026-11-11 14:24 Asia/Shanghai，本窗仍推） |
| simo255/shopper | https://github.com/simo255/shopper | 加拿大折扣看守 Bot：对照约 90 天价格史和论坛交叉验证后再通知，从不下单、加购或注册；没好价时保持安静。把 `persona/SHOPPER.md` 贴进人设，首次对话问偏好后再请你确认例程。MIT，仓很薄（人设 + 许可证） | 垂直配方 / 折扣看守 | GitHub 新建（2026-11-11 11:16 Asia/Shanghai） |
| ASISolutions/asi-cloud-cursor-plugin | https://github.com/ASISolutions/asi-cloud-cursor-plugin | ASI Cloud 新西兰机房厂商插件（虚拟机 / S3 / 推理），Cursor 与 Grok Bot 0.49+ 可连官方 MCP；花钱、删除或停服务须先问。MIT，偏 SaaS 连接器 | Bridges / 垂直插件 | GitHub 新建（2026-11-11 12:13 Asia/Shanghai） |

### Skip（本轮）

空仓/个人产出：Vyknn/vyknnr-grokbot-app（无 README）、yydshly/grok-bot-explore-notes（个人笔记静态站，非配方）、api-evangelist/grokbot-tools 与 grokbotwiki-com（第三方公司 API 画像，非玩法）。偏题 / 非 Grok Bot 主场：wisdom-km/agent-skills（给 Cursor/Grok 等编码 agent 的通用 Skill，未声明许可证）、kuzicode/meituan-dual-coupon-skill（美团领券，写的是 Grok CLI，无许可证，且建于本窗之前）、java-jaydev/figma-starter-mcp（Figma 本地 MCP，对象是 Grok Build）。X 交叉但不宜进候选：realspqrk/harness-subagent（8 月 MIT 技能，子代理是 Claude Code/Codex/Grok Build 等 CLI，不是 Grok Bot 专用配方）、timothyreavis/self-hosted-vault-mcp（通用 Obsidian/Markdown MCP，Grok Bot 只是可用客户端之一）、agentclientprotocol/claude-agent-acp（通用 ACP 适配器）。窗口内 X 热帖已收或已 Skip 不重列：milind-soni/OpenMausBot、rio-beagle/beagle-voice-agent、guidsen/hermes-grok-bot-skin、luobinger/PerkRadar。今早 T7/白天已收或已 Skip 不重列。

## 2026-11-12 10:50 Asia/Shanghai · T7 日更雷达

> 扫近 24 小时（约 11-11 02:45Z / 昨天 T7 ~10:45 Asia/Shanghai 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉；对照 11-11 T7（10:45）与白天玩法雷达（10:53 / 16:51）已收/已 Skip 去重。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| Ashe-Oro/grokbot-telegram-bridge | https://github.com/Ashe-Oro/grokbot-telegram-bridge | **在 Grok Bot 自带的常开 Linux 云电脑上跑 Telegram 多人桥**：私聊或群里跟已有 Bot 说话，配对码放行；管理员可驱完整 Agent，普通成员只能聊天、碰不到工具和那台机器。relay 只出站（长轮询 Telegram、POST 到 routine webhook），不开入站端口或隧道。把 setup 提示交给已有 Bot，由它新建专职 Bot 按指南一步步装。stdlib + 可选本地语音转写，SECURITY.md + 测试。早期、未按公网 Bot 加固。MIT。与已收 ssamssae（Mac 读本地会话副本）、0xErnest telegram-hub、deluminor telegram-routine-bridge 互补。本轮最值得看 | Bridges / Telegram | GitHub 新建（2026-11-12 04:51 Asia/Shanghai） |
| ramarivera/grok-bot-bridge | https://github.com/ramarivera/grok-bot-bridge | **从代码向任意 Grok Bot 队友派活并收回答复**：Grok Bot 没有公开发消息 API，本仓用一个路由 Bot + [Executor](https://executor.sh) 应用补上 `dispatch("Researcher", "…")` / `result(runId)`（MCP 也可调）。一个 webhook 打到所有队友，答案 POST 回 Executor 存储；密钥只进 Executor 账户仓。文档写明能调 dispatch 的人等于拥有那些 Bot 的全部权限，且依赖未承诺的产品行为。MIT。昨晨 T7 / 昨天白天漏收（11-10 17:45 已建，本窗仍推并在 X 交叉出现）。与已收 runesleo/grok-bot-bridge、Anudorannador/Agent2GrokBot 同向（派活+回收），增量是路由 Bot + Executor 回调 | Bridges / 派活 API | X 交叉（建于 2026-11-10 17:45 Asia/Shanghai；T7/白天漏收） |
| Toolsai/herdr-grok-bot | https://github.com/Toolsai/herdr-grok-bot | **社区 Skill：Bot 要起本机交互式 CLI Agent（Codex / Cursor / Claude Code / Pi 等）时改经 Herdr 启动**，方便在同一终端里看状态、所属 Workspace 并介入。带 INSTALL.md / USAGE.md，不是官方产品，也不能保证每个 Bot 每次都遵守。MIT，6★。与已收 herdr-grok-bridge（只读 MCP）、herdr-grokbot-notify（完成才 webhook）互补 | Skills / Herdr | GitHub 新建（2026-11-11 17:29 Asia/Shanghai；白天漏收） |
| iamraven-tw/grok-hermes-backup | https://github.com/iamraven-tw/grok-hermes-backup | **Grok Bot 继续当主力、Hermes 当备援**：每个 Bot 在 Hermes 里有专属备援角色；Grok 每周把人设/记忆/技能/例程导出到本机，Hermes 排程做成快照技能（平时不读），重要例程先复制为暂停、备援时再打开。把仓链给 Hermes（或能操作电脑的 Codex）按 README 自装。脚本只读写本机、不联网。MIT。与已荐 grokbot-to-hermes / grok-bot-twin / homer-hermes-kit 互补（迁出 vs 不停机备援） | Bridges / Hermes 备援 | GitHub 新建（2026-11-11 23:56 Asia/Shanghai） |
| asuhacoder/even-grok-bot | https://github.com/asuhacoder/even-grok-bot | **用 Even Realities G2 眼镜（和 R1 戒指）读、答、批准并语音指挥已有 Grok Bot**：本机中继经只听 127.0.0.1 的 DevTools 端口读写官方桌面 App，语音用本机 whisper.cpp（音频不出 Mac），G2 应用需自行打成 Even Hub 的私有 Beta。对外只走自己的 Tailscale。非官方，上游改版可能失效。MIT，日文 README | Bridges / 眼镜 | GitHub 新建（2026-11-11 20:38 Asia/Shanghai） |
| xthemarketmaker-cmyk/phone-pilot | https://github.com/xthemarketmaker-cmyk/phone-pilot | **在 Windows 上用 USB 操控自己的 iPhone 或 Android，不必备 Mac**：给 Grok Bot「Phone Pilot」模板用的脚本（也可单独在终端跑）。iPhone 走 go-ios + 自行签名的 WebDriverAgent，Android 走 adb。带安装、体检、保活和锁屏即停；发送/购买/删除等危险标签默认拒绝，须主人点头才 `--allow-risky`；`blocked_apps` 禁止打开的应用。无遥测。MIT | Tools / 手机操控 | GitHub 新建（2026-11-12 10:20 Asia/Shanghai） |
| portal-wheatley/Grok-Bot-for-Linux | https://github.com/portal-wheatley/Grok-Bot-for-Linux | **非官方 Nix 包装，在 Linux（x86_64 / aarch64）跑官方桌面 App**：拆官方 Windows 安装包，配 nixpkgs 里同版本的 Linux Electron，不用 Wine；可 `nix run` 或经 flake/overlay 安装，并注册 `grokbot://`。标明 unfree，且 Electron 42 已被 nixpkgs 标为 EOL（与官方 Win/mac 相同）。非 xAI/Cursor 产品。MIT。与 README 已收 Nichokas/grokbot-linux-port（重打官方 .deb）路径不同 | Clients / Linux 包装 | GitHub 新建（2026-11-11 20:41 Asia/Shanghai） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| jbellsolutions/tmec-grokbot | https://github.com/jbellsolutions/tmec-grokbot | 给阳光海岸电气公司 Tommy 用的 11 岗团队（一个 Command 对谈，外发须对原文点头，例程默认暂停）。有 START-HERE、审批与澳洲合规政策、28 个技能。结构完整，但是客户定制、**未声明许可证**，且尚未装到真实 Grok 账号 | 一人公司 / 垂直团队 | GitHub 新建（2026-11-12 04:58 Asia/Shanghai） |
| juntao/grokbot-arrival-cards | https://github.com/juntao/grokbot-arrival-cards | 入境卡 Grok Bot 模板：14 个国家和地区，身份进 Vault，浏览器开到预览页后等你点提交。可加已发布模板或把 setup 提示交给主 Bot。1★，**未声明许可证** | 垂直配方 / 旅行 | GitHub 新建（2026-11-12 02:32 Asia/Shanghai） |
| 0xGeeGee/jetbrains-grok-connector | https://github.com/0xGeeGee/jetbrains-grok-connector | YouTrack 的自托管 MCP 连接器（Cloud/Server），给 Grok Bot 当自定义远程 HTTPS 应用；YouTrack token 与 MCP token 分开，Node 绑 127.0.0.1。有工具目录和冒烟检查。**未声明许可证** | Bridges / YouTrack MCP | GitHub 新建（2026-11-11 20:53 Asia/Shanghai） |
| pagzhong/ai-bridge | https://github.com/pagzhong/ai-bridge | 自托管 VPS 中枢：多个 Agent（含 Grok Bot）用文件信箱和群聊交换任务与文件，一键装 Debian/Ubuntu，任务有 id 防重复执行。X 交叉。许可证是 **PolyForm Noncommercial 1.0.0** | Bridges / 多 Agent 信箱 | X 交叉（建于 2026-11-12 02:07 Asia/Shanghai） |
| signthis-pro/signthis-plugin | https://github.com/signthis-pro/signthis-plugin | SignThis 电子签名厂商插件（Grok Bot / Cursor 等 MCP）。MIT，偏 SaaS 连接器 | Bridges / 垂直插件 | GitHub 新建（2026-11-12 02:42 Asia/Shanghai） |
| hubpost-co/hubpost-plugin | https://github.com/hubpost-co/hubpost-plugin | HubPost 社媒排期发布厂商插件（Cursor / Grok Bot）。MIT，仓较薄 | Bridges / 垂直插件 | GitHub 新建（2026-11-12 04:58 Asia/Shanghai） |
| morphix-pro/morphix-plugin | https://github.com/morphix-pro/morphix-plugin | Morphix 图/视频/音频生成厂商插件（Cursor / Grok Bot）。MIT，仓较薄 | Bridges / 垂直插件 | GitHub 新建（2026-11-12 04:34 Asia/Shanghai） |
| facturadirecta/facturadirecta-plugin | https://github.com/facturadirecta/facturadirecta-plugin | FacturaDirecta 官方会计 MCP 插件（Cursor / Grok Bot）。MIT，偏 SaaS 连接器 | Bridges / 垂直插件 | GitHub 新建（2026-11-12 05:10 Asia/Shanghai） |

### Skip（本轮）

空仓/薄仓/占位：itskeeeyin/bot-office（MIT 但几乎只有一行 README）、ankit8898/grok-bot-test（一个 html）、catalioapp/catalio-mcp-plugin（无许可证、README 仅百余字节）、pingcodeai/grokbotai（Vue 站点模板，非玩法）。交易 / 错名克隆：agentshorts/Grokbot-Daytrade-Wallet、icecoldsteve/aetherdesk-trading-bots、rikardopavlovs-ai/grokbot（实为 Solana Agent Kit 拷贝）、enesclbb/grokbot（pump.fun 交易脚本拷贝）。偏题 / 非 Grok Bot 产品玩法：LBM-OASIG/dsh-grok-bot（给 DeepSeek Harness 的 Bot 插件，只拿 Grok Bot 当功能参照）、WastedPatriot/pocketbots（钥匙扣固件，README 未对接 Grok Bot 产品）、zmlworks/charge-log / dalixinc/zx-course / ksaday/ChristianCalendarGrok（用 Bot 做出来的应用或课程，不是配方）、wildmaker/grok-bot-meetup-credits（活动签到墙）、WBR-Technologies/Accord（落地页）、cyrano21/grok-bot（无许可证的自托管聊天壳）、ST4RM0N/brainsort 与 brainsort-grok-bot-pages（无许可证、概念向）。X 交叉但窗口外或不宜进候选：cufelix/grokbot-cli-mcp（superagent-ai/grok-cli 的 fork，10-31 后未推）、botseverywhere-ai/BotsEverywhere（10-19 建 25★，11-04 后未推）、Wecko-ai/hermes-bot、davidpgil/hermes-stage、mirecekd/herdogroco（Hermes/Tesla 向）、rkendel1/personalOS、smfworks/agent-llm-wiki-vault（写给 Hermes/OpenClaw）。窗口内热帖已收或已 Skip 不重列：milind-soni/OpenMausBot、Chasen-Liao/grokbot-and-pi、exa-pub/grokbot-tunnel、Soren-Starck/t3-bot、realspqrk/harness-subagent、guidsen/hermes-grok-bot-skin、rio-beagle/beagle-voice-agent、luobinger/PerkRadar、timothyreavis/self-hosted-vault-mcp、agentclientprotocol/claude-agent-acp、alexsergivan/kwant。昨天 T7/白天已收或已 Skip 不重列（含 grok-agent-threads、tiko、grok-bridge、file-shepherd、shopper、RI、control-room、avatar-tool、ai-balance-board 等）。

## 2026-11-12 10:55 Asia/Shanghai · 白天玩法雷达

> 扫 11-11 16:51 之后（约 11-11 08:51Z 起）新建/更新的 Grok Bot 相关仓 + X `url:github.com` 交叉。今早 T7（10:50，`c952451`）已覆盖条目只去重不重列。未改 README。

### 推荐

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| lixiaomeng0001-hue/osgb2su | https://github.com/lixiaomeng0001-hue/osgb2su | **测绘向 Grok Bot 技能：把倾斜摄影 OSGB 按地块边界选出瓦片，转成 SketchUp 可导入的 COLLADA/OBJ**。脚本只需系统 Python 3、无第三方依赖；先 `--dry-run` 再导出，只读源数据、不改原始 OSGB，也不走 GISBox 付费导出。仓内有 `skills/grok-bot/SKILL.md`，另附 WorkBuddy 技能和网页对话开场白。已验证 ContextCapture/Smart3D + EPSG:4543；按瓦整块导出，不是沿红线切三角面。MIT。今早 T7 漏收（仓名无 grok，10:20 新建）。本轮最值得看 | Skills / 测绘导出 | GitHub 新建（2026-11-12 10:20 Asia/Shanghai；T7 漏收，本窗 README/技能交叉补到） |

### 信号

| 名称 | 链接 | 一句话 | 分类建议 | 来源 |
|------|------|----------|--------|------|
| gopkg-dev/damail | https://github.com/gopkg-dev/damail | 自托管邮件中枢（Gmail/Outlook/iCloud/QQ/163/IMAP），MCP + REST；文档有专节写 Grok Bot：自定义连接器 + OAuth，接上后可用 Routine。发信须主人点头。MIT，5★，Docker 一键装，中英文档完整。主产品是邮件枢纽，Grok Bot 是多客户端之一（与 Claude Duet / ChatGPT dots / Meta Muse 并列） | Bridges / 邮件 MCP | GitHub 新建（2026-11-12 09:16 Asia/Shanghai；T7 漏收，仓名无 grok） |

### Skip（本轮）

空仓/个人笔记：jun173975-create/-bot（空仓，描述是期货期权盯盘 skill，未声明许可证）。不宜收录：starixs/grok-bot-research-ricoh（官方桌面 App 内部复刻/解析 POC，含本机路径，未声明许可证）。偏题或非配方：lixiaomeng 之外的「用 Bot 做出来的工具」不在本窗重复；smfworks/smf-works-books（无许可证，书籍仓）；akira-tokiwa/hft-self-improve（交易/HFT，无许可证）。X 交叉已收或已 Skip 不重列：exa-pub/grokbot-tunnel（作者发 v1.6.0 支持 1.0.1，已收仓版本更新不重列）、zabrodsk/bot2bot（已收）、ramarivera/grok-bot-bridge、pagzhong/ai-bridge、Chasen-Liao/grokbot-and-pi、milind-soni/OpenMausBot、cufelix/grokbot-cli-mcp、botseverywhere-ai/BotsEverywhere、rkendel1/personalOS、davidpgil/hermes-stage、Soren-Starck/t3-bot、alexsergivan/kwant、mirecekd/herdogroco、smfworks/agent-llm-wiki-vault。今早 T7 已收或已 Skip 不重列。
