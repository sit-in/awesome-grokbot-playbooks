# 任务板

| ID | 任务 | 负责 | 状态 | 产出 |
|----|------|------|------|------|
| T1 | X 雷达：搜 X 上近 30 天 Grok Bot 新仓库 / 新玩法，每条附链接 + 一句理由 | grok | done | `inbox/candidates.md` |
| T2 | 实测 botteams、grok-bot-profiles 各一个配置，记录能否跑通与坑 | grok | done | `inbox/field-notes.md`（文档/结构审阅；未能真机跑通） |
| T3 | 作战室配方初稿：按你自己多 bot 协作的真实经验，照 `examples/_template.md` 写 | grok | done | `examples/war-room.md` |
| T4 | 周度复查：README 全部链接是否存活 / 归档 | grok | todo | `inbox/link-check.md` |
| T5 | 核实 T1 候选，写短评入 README | claude | done | README.md + README.en.md（+13 条） |
| T6 | 审 T2/T3，脱敏、改格式、合并 | claude | done（T2 记 🔍；T9 三份配方已审入 README） | README + examples |

## P0 备货（2026-10-17 → 10-19，10-19 14:00 首发，见 ROADMAP.md）

| ID | 任务 | 负责 | 状态 | 产出 |
|----|------|------|------|------|
| T7 | X 雷达改为每日 routine，候选追加到 `inbox/candidates.md` | grok | doing (@grok routine；最近跑过 2026-10-26 10:43 Asia/Shanghai) | `inbox/candidates.md` |
| T8 | 每周实测 ≥2 个配方，跑通的标 ✅ | grok | in progress（本周 2/2 结构笔记已交；真机 GUI 待补） | `inbox/field-notes.md` |
| T9 | 按 ROADMAP「配方缺口」认领 X 雷达、出海客服、Teach-a-Task 三个配方初稿 | grok | done | `examples/x-radar.md` · `examples/outbound-support.md` · `examples/teach-a-task.md`（待真机验证；顺带勾上 war-room） |
| T10 | xAI 发布 Grok Bot 更新时写速报初稿 + 英文推文初稿 | grok | todo | `inbox/news/` |
| T11 | README.en.md 与中文版同步 | claude | done | `README.en.md` |
| T12 | 每周周报：新增、star、贡献者 | claude | done (W42) | `.collab/weekly.md` |
| T13 | 条目扩到 30+，配方到 8+ | claude + grok | done（82 条 / 9 配方） | README / examples |
| T14 | Routine 额度体检配方初稿 | grok | done（Claude 已审入 README） | `examples/routine-budget.md` |
| T15 | 首发日真机实测 routine-budget 并录屏 30–60 秒（其余配方开 issue 招募） | 涛哥 | doing（10/19 11:00） | 结果交 Claude 合入，配方标 ✅ |
| T16 | 推广稿：公众号首发长文、视频号/小红书脚本 ×2、即刻帖、社群预告与首发通知、awesome-grok-bot PR 文本 | claude | done，10/20 涛哥已发 | `.collab/promo/` |
| T17 | 配方「内容流水线」初稿（选题 → 初稿 → 人审 → 发布） | grok | todo | `examples/content-pipeline.md` |
| T18 | X 英文 thread（首发用，@ 候选作者） | claude（接手 Grok） | done，10/20 涛哥已发 | `.collab/promo/x-thread.md` |
| T19 | 公开前隐私审计（工作区 + 全部 git 历史） | claude | done 首轮（涛哥选 C：历史不动、改 noreply 邮箱；10/26 复查） | `.collab/promo/privacy-audit.md` |
| T20 | 首发日数据周报：star、流量来源、外部 issue/PR，写入 `.collab/weekly.md` | claude | todo（10/21 早上） | 看 Traffic → Referrers 哪个渠道带量 |

对外动作（发帖、开 Discussions、公开仓库、给其他仓库提 PR）一律由涛哥执行。
