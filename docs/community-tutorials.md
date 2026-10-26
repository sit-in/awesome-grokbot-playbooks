# 社区 Grok Bot 教程精选

其他博主公开分享的 Grok Bot 教程和长文，按主题分类。X 上的长文以外，也收博客、dev.to、Medium、V2EX、掘金、B 站等平台上能照着做的文章和视频，非 X 的条目在作者后面标平台。每条 = 标题 + 一句短评 + 日期（北京时间）。本仓作者自己的教程见 [sitin 的教程索引](sitin-tutorials.md)。

> 收录门槛见 [CONTRIBUTING](../CONTRIBUTING.md#x-以外的社区文章社区教程精选)。收录方式：每条都在 2026-10-18 用公开只读接口核过帖子存活、作者、日期、标题。只收公开链接，不收要登录才能看的文档，不收收益截图类、代币类、引流类帖子。产品迭代很快，越早的帖子越要对照官方最新说明。

## 目录

- [入门上手](#入门上手)
- [多 Agent 作战室](#多-agent-作战室)
- [Routine 与额度](#routine-与额度)
- [Skills 与连接](#skills-与连接)
- [一人公司与内容](#一人公司与内容)
- [索引与合集](#索引与合集)

## 入门上手

- [10 条必备经验，让你的 Grok Bot 变得更好用](https://x.com/eze_is_1/status/2109850538045264151) — @eze_is_1 · X 长文：什么时候该用 Bot、怎么搭多 Bot 工作流等 10 条实测经验，中文圈引用最多的入门文之一；作者同 web-access · 2026-10-13
- [官方 Grok Bot 教程中文版](https://x.com/Mileson07/status/2108384482063688060) — @Mileson07 · 把官方英文指南整理成中文，不想读英文的从这里开始 · 2026-10-09
- [把 Grok Bot 用成同事：一份能照着做的教程](https://x.com/Remake___/status/2106996626707607818) — @Remake___ · X 长文，按官方文档一步步写，标了版本日期，注意时效 · 2026-10-05
- [Grok Bot 教程怎么选？三步走的热门教程](https://x.com/lanvjian/status/2109560084418490771) — @lanvjian · X 长文：把热门教程按入门 → 进阶 → 实战排好阅读顺序 · 2026-10-12
- [Grok Bot 20 课实操教程模板](https://x.com/SawyerMerritt/status/2103664821459685708) — @SawyerMerritt · 英文。可导入的教学模板，从对话、文件、连接应用、Routine、Skill 到团队协作，一课一练 · 2026-09-26
- [官方 1 小时工作坊要点](https://x.com/AleiahLock/status/2095924854335631840) — @AleiahLock · 英文。官方 workshop 的转述和时间轴，核心是从「派任务」转到「设岗位」 · 2026-09-05
- [像入职新员工一样配 Grok Bot：hire / train / equip](https://x.com/0xShoopy/status/2107874318244032867) — @0xShoopy · 英文。官方工作坊笔记：一个 bot 一个岗位，演示一次存成 skill，有现成连接器就先用连接器 · 2026-10-08
- [How to Grok Bot (Non-Slop)](https://x.com/im_insulting/status/2099228547760128299) — @im_insulting · 英文 X 长文：把非核心任务交给 bot 的务实做法 · 2026-09-14
- [Grok Bot 从 0 到 1｜用云电脑和插件，搭一个能干活的 X 助手](https://juejin.cn/post/7684649314158510114) — 小墨同学boy · 掘金 · 在 M 系列 Mac 上安装登录，给云电脑接 Cloudflare WARP 换出口 IP（保留内网和控制通道），再补齐 X 开发者账号、项目和 App 让 X 插件真正连上，附一条只读验证指令；X API 按量付费，按 2026-08-31 的界面写，注意时效 · 2026-09-13
- [How to tell whether a Grok Bot workflow actually works](https://www.grokbotwiki.com/guides/evaluate-a-workflow) — Grok Bot Wiki · 独立站 · 英文。上自动化之前怎么验收一条工作流：分别用正常、含糊、空输入、来源打不开四类案例去跑，按来源忠实度、完整性、权限边界、失败处理等 8 项打分，记下人工复核花的时间；附可下载的 CSV 检查表和审阅提示词。打分框架是站方自拟，不是实测成绩；站方自荐（作者相关），站内有广告位招商 · 2026-09-06

## 多 Agent 作战室

- [10 分钟搭一整支团队：Chief of Staff 做唯一入口](https://x.com/zodchiii/status/2090778823050592662) — @zodchiii · 英文。先建首席助理、粘贴描述字段，再让它去建其他岗位，步骤清楚 · 2026-08-21
- [4 分钟搭出「贾维斯」：首席 + 岗位 bot](https://x.com/Av1dlive/status/2090366905169379554) — @Av1dlive · 英文。早期爆款入门帖，口吻偏营销，当「最小团队」参考即可 · 2026-08-20
- [25+ bots：Chief of Staff + PM + QA + worker 的演示笔记](https://x.com/shirosignal/status/2110077526924317019) — @shirosignal · 英文。30 分钟演示的笔记：怎么把一个 bot 扩成有分工的团队 · 2026-10-14
- [SpaceXAI 工程师的 Chief of Staff 配置](https://x.com/0xRafy/status/2096017149999358316) — @0xRafy · 英文。转述官方工程师 10+ bot 组队、由首席掌握全局的做法，二手信息 · 2026-09-05
- [Grok Bot 当总调度，云电脑里装 Codex / Cursor / Gemini CLI 分工](https://x.com/luhuamfl0/status/2100155813528768516) — @luhuamfl0 · 写代码交给 Cursor，复杂任务交给 Codex，长上下文交给 Gemini 的编排思路 · 2026-09-16
- [AI Agent 多代理人自動化開發實作：讓 Agents 夜巡](https://www.letswrite.tw/night-patrol/) — Let's Write · 博客（dev.to 有转载）· 繁中：NightLead / Explorer / Builder / Critic 四个 bot 的设定原文和群组启动指令，凌晨 3 点开跑、每天新建工作目录，安全边界写死（不碰正式仓库、不花钱、不发布），早上交一份 Morning Report · 2026-10-01
- [【Grok Bot 仓颉实践】助手一次汇报七八条，我只批准一条往下做](https://juejin.cn/post/7693358476032213002) — 猛犸象限 · 掘金 · 项目管理 bot 只汇总有新增或修改的变更，人一次只批一条，任务开头写「已批准第 N 项」再转给对应的专长 bot，Notion 当唯一事实源；系列第二篇，作者写明还有几条没落地 · 2026-10-06

## Routine 与额度

- [Grok bot 省钱教程](https://x.com/czzzzzzJ_/status/2109600412366160101) — @czzzzzzJ_ · $20 档怎么够用：省额度的 prompt 思路。帖内的文档库要登录，本页不放链接 · 2026-10-12
- [每周让 Grok Bot 对照新功能检查你的用法](https://x.com/Michael_Fenech_/status/2108145378323542306) — @Michael_Fenech_ · 英文。一条可直接粘贴的周度 routine：比对产品更新和你的实际用法，提示该换的做法 · 2026-10-08
- [周一 routine：交给 Chief of Staff 的周度自查](https://x.com/mikepat711/status/2107130731382079767) — @mikepat711 · 英文。可以直接复制给首席助理的 routine 原文 · 2026-10-05
- [I Let Grok Bot Apply to Software Engineering Jobs While I Was Sleeping](https://dev.to/bobbyhalljr/i-let-grok-bot-apply-to-software-engineering-jobs-while-i-was-sleeping-n62) — Bobby Hall Jr · dev.to · 英文：附去掉个人信息的求职 agent 设定原文，0–100 打分、75 分以上才投、去重、拿到确认才算投递成功、敏感问题停下来问人，设成每 4 小时一次的定时任务。⚠️ 要把求职网站的登录态交给 bot；文末推作者自家产品（作者相关） · 2026-08-31
- [Grok Bot 额度两天就用完？我的两个改进](https://www.bilibili.com/video/BV1Menj62E4q) — KunKun的折腾手记 · B 站视频 · 多个 bot 都在一个经理群里，人说一句全员醒来读一遍；简介写了两招：群外另开私聊入口，汇报改成手机上看的 HTML 并写清要人决定什么 · 2026-10-19

配套配方：[Routine 额度体检](../examples/routine-budget.md)、[周报](../examples/weekly-review.md)。

## Skills 与连接

- [把 Grok Bot 和本地 Agent 打通：Webhook + GitHub Action](https://x.com/fankaishuoai/status/2111361067041673452) — @fankaishuoai · 本地 Agent 写任务文档，推到仓库后触发 Bot 的 webhook 接活 · 2026-10-17
- [用 Tailscale SSH 连接 Grok Bot 云电脑（保姆级）](https://x.com/SpringHaoAI/status/2095915259521585458) — @SpringHaoAI · X 长文：从自己电脑 SSH 进 bot 的云电脑，传文件、看日志、写脚本。⚠️ 开 SSH 等于扩大权限面，用完关掉，别暴露公网 · 2026-09-05

## 一人公司与内容

- [How To Build a One-Person Company Using Grok Bot](https://x.com/sairahul1/status/2089995692874068433) — @sairahul1 · 英文 X 长文：找线索、写外联、做图、回复、周复盘全交给 bot 团队，一人公司主题里传播最广 · 2026-08-19
- [别再让一个 AI 干所有活了：内容生产拆给 14 个机器人](https://x.com/ai_goge/status/2110331990566449273) — @ai_goge · X 长文：短推、长文、公众号、出图、核事实、数据复盘各配一个机器人的完整搭法 · 2026-10-14
- [用 Grok Bot 做开源项目宣传片](https://x.com/seekjourney/status/2110986767549739151) — @seekjourney · 从产品理解、创意、分镜、画面到视频生成一整套，附提示词 · 2026-10-16
- [我 build 了一个 Grok Bot 帮我 7x24 运营我的 pstack 中文站](https://juejin.cn/post/7694134378717986851) — 出发向未来 · 掘金 · 真实复盘：bot 拆需求，改代码交给 Cursor Cloud Agent，日常检查放进定时任务；踩坑后定下「一个 PR 一个 Cloud Agent，做完就关」「按任务类型选模型档位」等规矩，再整理成 skill 给第二个 bot 复用。作者自己的站（作者相关），没贴 skill 原文 · 2026-10-08
- [Grok Bot 保姆级做视频教程：从一句话需求到全平台成片](https://juejin.cn/post/7694287070886297610) — XiaoLei_Liu · 掘金 · 代码渲染路线：页面暴露 seek(t)，Playwright 逐帧截图，ffmpeg 合成，edge-tts 词级时间戳驱动动效；给了八步流水线、三个 Skill 分工和 4 个 prompt 模板。引用的第三方 skill 里有一份规避版权检查的文件，作者要求禁用；音效商用前先核授权 · 2026-10-09

配套配方：[一人三岗](../examples/one-person-three-roles.md)、[作战室](../examples/war-room.md)。

## 索引与合集

- [X 上 Grok Bot 必读文章合集：9 类 24 篇](https://x.com/0xlangeai/status/2111396742264742034) — @0xlangeai · X 长文，中文高阅读文章索引，按主题分好类 · 2026-10-17
- [Grok Bot 系列教程干货合集](https://x.com/KinGao476942/status/2110689770892648953) — @KinGao476942 · 作者一个多月的系列：工程师、非工程师、自媒体分别怎么用；作者同[橙皮书](https://github.com/KinGao294/grok-bot-orange-book) · 2026-10-15
- [20 个 Grok Bot 相关 GitHub 仓库](https://x.com/maestrooth/status/2105310670535184774) — @maestrooth · 英文。自托管、加工具、连应用、抄工作流的仓库清单 · 2026-09-30
- [Grok Bot 案例合集网站 usegrokbot.com 推荐帖](https://x.com/cnyzgkc/status/2095500855797748032) — @cnyzgkc · 站点本身已进 README，见 [UseGrokBot](https://usegrokbot.com/) · 2026-09-03

---

想推荐教程：开一个「推荐条目」issue，附 X 链接和一句理由。收益截图类、代币类、搬运未注明出处的不收。
