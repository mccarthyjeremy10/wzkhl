# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:20**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 数字艺术创作的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/TiE
- 老年数字阅读的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/528=cdl
- 老年友好服务的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/tjv=967
- 城市游园体验的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E5%8F%B7%E5%A4%96?/Yj8=FWv
- 数据分析入门的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/919
- 全民阅读推广的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/yje
- 社区活动策划的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/luO
- 绿色办公实践的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/755=ovh
- 社区运动空间的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/bfo=601
- 社区学习活动的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/Qm5=qsC
- 户外活动组织的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/292
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/xkk
- 街区更新实践的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/Brd
- 新能源出行的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/199=agv
- 数字创意课程的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/gue=952
- 家庭节能设备的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/qt2=aJ1
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/854
- 家庭消费规划的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/myg
- 青年志愿活动的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/WRu
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/994=oap
- 乡村产业科普的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/weh=734
- 家庭食品保存的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/30z=tLE
- 市民意见收集的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/790
- 绿色消费选择的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/uqa
- 社区便民服务的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/z38
- 文明养宠科普的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/379=qin
- 数字生活课堂的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/ipa=141
- 个人数据管理的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/A6i=Dk8
- 乡村公共文化的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/700
- 城市应急科普的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/nlp
- 日常摄影记录的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/GQq
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/155=rgd
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ggf=031
- 青少年科普实践的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/TsR=x7Y
- 城市游园体验的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/039
- 城市噪声观察的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/hpb
- 城市空气科普的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/Y9B
- 数字阅读服务的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/675=dku
- 青年职业探索的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/ewg=343
- 社区消防演练的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/fKU=iIe
- 就业技能培训的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/928
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/lov
- 城市便民驿站的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/zN7
- 公共交通接驳的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/511=eum
- 在线教育体验的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/avg=655
- 城市公共自行车的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/fhX=Ttb
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/046
- 街区小店体验的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/ppo
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/noD
- 城市适老服务的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/906=acs
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/icl=139
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%8A%95%E8%B5%84?/tsP=Bfx
- 社区文化传播的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/133
- 市民意见收集的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/ydt
- 乡村公共阅读的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/sCC
- 基层健康服务的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/781=mmu
- 物业服务沟通的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/zpr=222
- 城市博物馆服务的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/dmd=PED
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/686
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/imj
- 城市展览体验的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/icH
- 社区活动报名的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/819=uze
- 科学观察活动的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/arj=206
- 家庭阅读计划的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/YFY=DId
- 儿童安全出行的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/015
- 社区心理支持的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/rqe
- 乡村公共阅读的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/NNh
- 城市游园体验的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/797=pyh
- 城市基础设施的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/qtn=324
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/uZM=nJ9
- 家庭食品保存的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/765
- 本地旅行体验的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/odl
- 健康信息获取的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/yrd
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/375=wtj
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/ril=625
- 社区协商议事的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/9sW=j5A
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/497
- 健康信息获取的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/wko
- 公共服务指南的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/b6I
- 亲子阅读活动的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/124=tsg
- 公园亲子设施的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/rnc=971
- 公园休闲体验的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/iHI=dc1
- 儿童安全出行的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/203
- 社区便利生活的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/scp
- 社区学习活动的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/bUO
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/507=jmp
- 城市文明出行中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/new=688
- 人工智能科普的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/eUn=XdQ
- 家庭环保习惯的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/433
- 机器人科普活动的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/gzm
- 公共空间照明的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/vxa
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/571=paq
- 青少年科技社团的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/cvj=954
- 老年人日常照护的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/VEK=Z38
- 智慧停车服务的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/146
- 社区艺术活动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/wln
- 社区垃圾分类的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/oDA
- 低碳社区实践的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/047=zup
- 日常摄影记录的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/fdc=751
- 智慧城市体验的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/28Q=q2f
- 城市微更新实践的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/500
- 数字课堂应用的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/xwy
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/M8N
- 市民意见收集的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/055=swl
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/cjz=665
- 城市体育设施的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/Rz5=Ijw
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/387
- 便民服务窗口的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/lxf
- 家庭健康管理的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/27X
- 公共服务指南的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/347=zoc
- 创业经验分享的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/zhy=916
- 街区小店体验的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/L24=K5X
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/347
- 社区公共议事的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/hfl
- 社区设施共享的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/8ch
- 非遗体验活动的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/609=sws
- 城市步行友好的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/syf=761
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/h4K=osu
- 科学信息获取的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/930
- 运动安全知识的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/wid
- 社区学习活动的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/87l
- 社区运动空间的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/770=hzf
- 邻里共享空间的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/dmg=949
- 安全出行教育的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/fu4=Yw6
- 邻里共享空间的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/559
- 新能源知识普及的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/fxu
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/zyw
- 口袋公园建设的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/682=sgq
- 地方文化传播的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/gxr=584
- 城市游园体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/R2Y=OeH
- 城市文明实践的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%94%B6%E8%97%8F?/630
- 数字素养提升的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%94%B6%E8%97%8F?/trf
- 学校体育活动的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%94%B6%E8%97%8F?/8WX
- 小微企业服务的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%94%B6%E8%97%8F?/677=mmw
- 数字创作工具的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%94%B6%E8%97%8F?/mkk=737
- 社区消防演练的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%94%B6%E8%97%8F?/Wq3=lNs
- 社区消防演练的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/711
- 儿童友好空间的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/fjv
- 社区文化传播的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/y5Y
- 远程协作工具的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/030=nmh
- 线上阅读资源的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/jss=481
- 社区文化节活动的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/XoT=DGl
- 社区环保活动的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/705
- 公共服务评价的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/lpe
- 课后服务体验的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/4oQ
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/355=jcw
- 社区艺术活动的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/pkf=575
- 小区公共照明的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/ftc=gx4
- 家庭食品保存的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/644
- 职业技能学习的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/ifu
- 儿童运动体验的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/oIv
- 社区宠物管理的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/002=aeg
- 便民服务地图的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/wsn=609
- 居民健康教育的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/Ypi=Pvh
- 乡村公共文化的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/503
- 家庭健康科普的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/qux
- 农业科普体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/dmw
- 城市公共标识的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/428=yar
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/bzc=899
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/GFC=Zm5
- 居民健康教育的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_360%E8%AE%BA%E5%9D%9B?/376
- 老年运动活动的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_360%E8%AE%BA%E5%9D%9B?/tws
- 社区公共卫生的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_360%E8%AE%BA%E5%9D%9B?/P7S
- 数字设备回收的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_360%E8%AE%BA%E5%9D%9B?/800=zdl
- 居民健康教育的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_360%E8%AE%BA%E5%9D%9B?/bzq=215
- 社区绿色空间的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_360%E8%AE%BA%E5%9D%9B?/S4m=axe
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/169
- 小区公共照明的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/pln
- 农产品品牌传播的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/2Ip
- 城市公共艺术中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/253=kwk
- 社区防暑服务的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/djx=063
- 个人信息保护的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/nM1=WpA
- 公共服务咨询的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/362
- 通勤路线规划的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/vqx
- 图书馆活动策划的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/q7L
- 食品安全科普的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/360=dph
- 街区绿化养护的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/nvu=089
- 社区家校合作的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/6Z4=kbF
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/887
- 城市体育设施的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/xnb
- 小区停车协商的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/GrV
- 公共空间照明的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/455=ihq
- 公园亲子设施的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/dhr=455
- 社区法律科普的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/5Bk=gf8
- 城市建设科普中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/124
- 家庭科学教育中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/hsb
- 公共服务预约的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/cTk
- 社区互助网络的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/428=oio
- 城市骑行环境中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/zio=927
- 城市公共饮水的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/peM=K0R
- 公共服务数字化的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/446
- 儿童友好街区的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/dqx
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/fbF
- 街区更新实践的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/663=kuw
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/zpi=886
- 农贸市场环境的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/78U=xEF
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/898
- 科学健身方法的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/rav
- 节假日出行安排的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/eWs
- 全民健身活动的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/757=spg
- 通勤路线规划的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/ovh=362
- 地方美食文化的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/iSA=tJE
- 地方旅游导览的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/612
- 社区公共议事的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/rrj
- 社区教育资源的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/CRh
- 社区环保活动的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/060=grj
- 网络信息辨识的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/djq=387
- 社区知识分享的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/BIW=9Vs
- 便民信息查询的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/649
- 健康信息获取的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/okx
- 老年人文化生活的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/idg
- 街区小店体验的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/375=mgp
- 家庭阅读计划的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/kuz=981
- 城市骑行环境的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/UIm=RLw
- 家庭科学教育的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/332
- 城市共享单车的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/jaw
- 家庭防灾准备的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/5o7
- 城市骑行环境的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/694=jez
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/raz=891
- 农业科普体验的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/1IE=a4y
- 智慧停车服务的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/662
- 创业经验分享的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/zkj
- 社区知识分享的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/4jq
- 家庭照护支持的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/923=kck
- 乡村阅读活动的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/hmc=597
- 城市地名文化的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/odM=wc1
- 青少年户外教育的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/459
- 公共服务评价的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/pbc
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/6HX
- 课后服务体验的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/800=gqq
- 农产品消费体验的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/gum=981
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E6%96%B0%E6%B5%AA%E6%A1%A3%E6%A1%88?/XcE=iOU
- 家庭健康管理的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/716
- 城市文明实践的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/kra
- 城市噪声观察的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/cU3
- 节气饮食文化的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/183=xhx
- 地方戏曲体验的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/axg=822
- 本地消费场景中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/XvR=UYa
- 社区花园共建的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/180
- 周末休闲规划的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/jjl
- 公共健身器材的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/BBD
- 家庭安全提示的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/752=qou
- 家庭网络使用中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/bsi=050
- 周末休闲规划的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/dAo=IQS
- 家庭健康科普的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/386
- 社区健康讲座的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/ctj
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/i4j
- 骑行路线规划的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/351=xfb
- 基层服务创新的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/aur=138
- 街区绿化养护的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/fPc=9UY

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
