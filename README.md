# 👋 你好，我是金sir

简单介绍下，我是从内容生产摸进 AI 的，实习时发现重复劳动太多了，干脆自己动手搭 Agent 把这些活儿自动化掉。这个 GitHub 里放的就是这条路上做出来的东西

---

### 🔭 我做的东西

**1. [DayPilot 日航 · 带 AI 输出质量评估的效能 H5](https://github.com/jin2004-cmd/daypilot)** —— [🟢 在线体验](https://jin2004-cmd.github.io/daypilot/)

最新项目。用 AI 拆每日待办，输出经常任务超载、时长离谱，还得人工二筛——所以我给它加了一道质量门：每天只排 3-5 件事、必带优先级和预估时长、总长不超当天预算，输出先过规则校验再由模型打分（低于 7 分自动重试至多 2 次），每次调用留痕可审计。早规划、白天打卡、晚复盘、周报一天闭环，手机和电脑浏览器打开即用，免 Key 可玩全流程。这个项目是 vibecoding 完成的：需求、规则、提示词和验收是我定的，代码是 AI 编程工具写的，分工就摆在明面上。

**2. [电商爆款脚本生成智能体（千川带货版）](https://github.com/jin2004-cmd/ecom-script-agent)** —— [🟢 在线试用](https://jin2004-cmd.github.io/ecom-script-agent/)

实习时真碰到的问题：带货脚本一天要出十几条，条条得过广告法。这个 Agent 内置 19 篇真实爆款原稿库、五段式模板和合规引擎（违禁词自动替换 + 医疗品类强制校验），网页点开就一键出稿，还配了 4 个测试文件。**先交代口径免得数字像编的**：团队小范围灰度一周、3 人样本（团队周报口径），人均日产从 7-9 条提到 15-18 条，单条 8-12 分钟降到 2-3 分钟，素材过审率约 70% 提到 82%。

**3. [带货文案合规审查工具](https://github.com/jin2004-cmd/ad-compliance-checker)** —— [🟢 在线试用](https://jin2004-cmd.github.io/ad-compliance-checker/)

做第一个项目时想明白一件事：只查违禁词表会给人虚假的安全感——「缓解胃胀」合不合规不取决于词，取决于你有没有资质批文。所以另做了这个：**判断「这句话能不能发」，而不只是「有没有命中词」**。三级风险分级 + 资质判定，14 条回归用例（含防止误判的反例）全部通过，单文件零依赖，双击就能用。

**4. [OfferAgent · 秋招求职引擎](https://jin2004-cmd.github.io/ai-video-portfolio/offer-agent/)** —— [源码](https://github.com/jin2004-cmd/ai-video-portfolio/tree/main/offer-agent)

自己秋招自己用的工具：六轮追问把每条经历逼成「动作 / 做法 / 数据口径 / 结果」，然后生成一页可复制的简历，带红线检测（弱动词、估算数据、作品没链接，一律标红）和面试追问预演。**它不替你编一个字**——这是我做所有内容工具的底线。

**5. [AI 视频作品集](https://jin2004-cmd.github.io/ai-video-portfolio/)** —— [源码](https://github.com/jin2004-cmd/ai-video-portfolio)

主打片《候》是给腾讯互娱 48 小时测试做的 27 秒 AI 短片，全流程自己跑通：Seedream 三视图母版锁角色一致性 → Seedance 图生视频 → 剪映处理跳变、配乐成片。站点里还有一条《悟空》风格练习片和 5 条实习期间做的千川竖屏投流素材。

**6. [codex-practical-skills](https://github.com/jin2004-cmd/codex-practical-skills)**

我给自己写的 8 个 Codex 技能，前 4 个是秋招向（求职记忆管理、Offer 决策、作品集性能、安全发布），后 4 个是做开源项目沉淀的工程向（LLM 输出质量门、无框架网页截图、新仓库曝光打磨、vibecoding 简历话术）。用顺了脱敏后开源，里面没有任何人名、学校、公司、薪资或私聊记录。

---

### 🛠️ 工具栈

- **AI 内容生产**：豆包 / DeepSeek / 通义千问（提示词工程）、Trae、Codex、Claude Code
- **AI 绘图与视频**：Seedream、Seedance、即梦、可灵、剪映
- **能写点代码**：Python（独立写脚本 + pytest）、HTML/CSS/JS 单文件应用、Git / GitHub
- **内容基本功**：千川投放素材逻辑、广告法合规、短视频脚本、剪辑
