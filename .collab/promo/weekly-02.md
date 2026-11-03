# 周报 X 串帖 · 第 2 期（10-26 → 11-01）

涛哥发。Claude 起稿（11-03 补周一这期），数字截至 2026-11-01 收尾。

- 每条按「不开会员也能发」控制在约 140 个汉字以内。
- 链接 11-03 全部核过能打开。
- @ 的 5 个人都是本周收录文章的作者。

发帖节奏：
1. 先发第 1 条。
2. 2–10 条在它下面接成串。
3. 最后一条把仓库链接再放一次。
4. 配图建议用 README 首图 `assets/social-preview.png`。

---

**1/11**

Grok Bot 一周新玩法 Top 10（10.26–11.01）

开源清单 awesome-grokbot-playbooks 第二周：收录从 117 条涨到 172 条，大 V 文章从 178 篇涨到 287 篇。

挑了 10 个最值得抄的 👇

github.com/sit-in/awesome-grokbot-playbooks

**2/11**

① 新出的 Pages：给自己搭仪表盘

@AlexFinn 一段约 12 分钟的视频，演示他搭的 5 个仪表盘，其中一个专门盯用量，帮他省了不少额度。

本周收藏最多的一条，5000+
x.com/AlexFinn/status/2115596225793921048

**3/11**

② 额度到底怎么扣？15 条讲透

按干的活扣，不按消息条数。截图看视频最烧，能走连接器就别开浏览器；定时任务按唤醒次数算，每 15 分钟一次＝一周 672 次。

@leaf_sanren 的数字是实测反推，非官方
x.com/leaf_sanren/status/2115718050389610891

**4/11**

③ 把 Codex、Claude Code、Gemini 都接进 Grok Bot

五段提示词直接发给总管 bot：在云电脑上用各家 CLI 登录自己的账号，编程、生图这类活改走对应订阅的额度。验证码和 key 仍要本人输。

@KinGao476942
x.com/KinGao476942/status/2115592603605557564

**5/11**

④ 国内生活服务也能接了

瑞幸、美团跑腿、麦当劳、滴滴、高德，5 个官方 MCP / Skill 逐个给入口：点咖啡、领红包、叫车、规划行程。付款前一定要你确认。

@xiaomovps
x.com/xiaomovps/status/2116690552188260496

**6/11**

⑤ 「Hey Siri」直接开语音

快捷指令里加 Start a Voice Chat with Bot、改个名、允许锁屏运行，就能用 Siri 唤起，不用常开麦克风。

@Texas_Twins_Dad 三步搞定
x.com/Texas_Twins_Dad/status/2116748190649037285

**7/11**

⑥ 云电脑的东西，记得备份

Grok Bot Backup：人设、记忆、对话、附件导成文件加 Markdown，也有现成的备份 bot 按向导存 Google Drive。

导出的 ZIP 没密码，放私密位置。

github.com/company-notes/grok-bot-backup

**8/11**

⑦ 7500 多个现成 bot，一个目录翻完

Every Grok Bot（grokbot.rocks）：分享链接分 26 类，每条一句说明，点开就能加到自己的 Grok Bot。

也可以让 bot 读这份目录，按你的目标挑 skill。

grokbot.rocks

**9/11**

⑧ 微信私聊直接找 bot

grokbot-weixin：常驻进程经微信 iLink 接口收私信，转给 webhook routine，回复再发回微信。只认白名单里的号，群消息不理。

github.com/ericyangpan/grokbot-weixin

**10/11**

⑨ 一句话派活，本机 Claude Code 带队干

stampede：Grok Bot 经 Tailscale SSH 到你常开的 Mac，Claude Code 当组长，值得并行再加 Codex 窗格。合并、推送、花钱前都等你点头。

github.com/vib-z/stampede

**11/11**

⑩ 中文保姆级攻略，免费

26 章操作、40 套任务指令、36 条 FAQ、7 天上手计划，关键结论附官方来源，单列套餐和计费防坑。

github.com/AIPMAndy/grok-bot-handbook

每周一更新。觉得有用点个 Star ⭐
github.com/sit-in/awesome-grokbot-playbooks

---

## 备用

- **想更短**：只发 1/11 + ②④⑤⑥⑧ 五条。中文圈对「额度」「国内服务」「Siri」「备份」「微信」反应最强。
- **有 X 会员，想发单条长帖**：把 11 条合成一条，去掉每条的序号头即可。
- **作者 @**：只 @ 了 5 位 X 文章作者。仓库作者的 X 账号没核，不要猜着 @。
- **备选替换**：Grok Bot Face（Pixel 平板变 bot 动画脸，github.com/dwinter3/grokbot-face）、Groknet（不同主人的 bot 互加好友，github.com/sudoTomas/groknet）。
