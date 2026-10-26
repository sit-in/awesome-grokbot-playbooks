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
