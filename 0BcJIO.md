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

- 青年就业服务的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A5%87%E8%AE%A1%E5%AE%9D%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/419
- 本地旅行体验的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A5%87%E8%AE%A1%E5%AE%9D%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/ilt
- 青年志愿活动的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A5%87%E8%AE%A1%E5%AE%9D%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/ATS
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A5%87%E8%AE%A1%E5%AE%9D%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/639=hid
- 读书会组织的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A5%87%E8%AE%A1%E5%AE%9D%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/hoi=697
- 家庭健康科普的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A5%87%E8%AE%A1%E5%AE%9D%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/Vat=BAN
- 青少年科技社团的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/147
- 数字支付体验的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/kea
- 城市游园体验的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/AFU
- 生活服务数字化的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/418=obu
- 消防知识宣传中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/ykv=559
- 公共服务指南的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/2L1=uQk
- 职业技能学习的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/870
- 城市文明出行的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/nhl
- 地方民俗记录的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/8Cr
- 城市博物馆活动的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/016=tdd
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/aae=027
- 青年职业探索的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/bEu=AsL
- 城市公共饮水中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/527
- 个人时间管理的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/ygs
- 社区便利生活的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/KJd
- 城市地名文化的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/043=aqt
- 城市人文观察的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/scu=520
- 家庭环保习惯的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/GEb=ClN
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/039
- 创业经验分享的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/pnq
- 城市生活记录的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/lQ5
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/678=oec
- 科技馆参观体验的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/cpu=154
- 城市文明实践的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/zQH=xKO
- 社区生活指南中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/948
- 基层健康服务的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/iih
- 社区读书角建设中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/ZPT
- 社区菜市场服务的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/619=dvm
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/wrf=504
- 街道综合服务的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/OKD=JT5
- 课后服务体验中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E6%A5%BC%E5%B8%82?/265
- 地方文化传播的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E6%A5%BC%E5%B8%82?/flr
- 线上阅读资源的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E6%A5%BC%E5%B8%82?/TRs
- 智慧城市体验的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E6%A5%BC%E5%B8%82?/219=ezg
- 城市体育设施的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E6%A5%BC%E5%B8%82?/grf=841
- 个人信息保护的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E6%A5%BC%E5%B8%82?/psh=nmQ
- 城市夜间生活的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/585
- 线上阅读资源的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/git
- 健康饮食教育的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/1kc
- 灵活就业交流的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/435=zpr
- 旧物循环利用的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/ubm=072
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/4j3=29r
- 家庭节能实践的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/685
- 公益活动组织的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/rmr
- 智慧停车服务的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/nMz
- 食品安全科普的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/921=prz
- 生活垃圾回收的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/kkk=380
- 绿色消费选择的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/Zua=HFw
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/419
- 数字地图应用的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/djy
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/6tn
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/346=gzr
- 城市可持续生活的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/crg=141
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/Pnt=WLj
- 无障碍出行的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/709
- 公共卫生设施的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/esa
- 家庭健康科普的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/wn4
- 社区防暑服务的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/190=fnx
- 读书会组织的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/zfi=811
- 电动汽车充电的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/0NX=325
- 节能家电使用的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/979
- 科学教育活动的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/fua
- 社区托育服务的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/2U7
- 公园无障碍服务的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/714=uvk
- 数字设备回收的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/hcg=191
- 城市水环境观察的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/aX9=O9w
- 家庭节能实践的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/174
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/rqs
- 网络安全教育的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/ory
- 社区文化节活动的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/350=nmy
- 社区公共卫生的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/hhl=756
- 城乡公共服务的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/UE6=Hnt
- 节日文化体验的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/343
- 校园社团活动的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/oxm
- 无障碍信息设计的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/Ck4
- 城市骑行环境的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/792=wkg
- 生活技能分享的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/awa=438
- 公共服务咨询的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/QOL=xup
- 家庭收纳实践的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/551
- 社区学习活动的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/daq
- 社区环保活动的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/Fcz
- 公共健身器材的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/774=uop
- 农产品品牌传播的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/ahj=161
- 小微企业服务的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/8N7=lDy
- 亲子阅读活动的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/654
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/nlt
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/Hnh
- 志愿者培训交流的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/416=xll
- 社区垃圾分类的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/hat=689
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/sT5=Z8U
- 线上办事服务的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/341
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/tub
- 乡村公共文化的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/UwM
- 终身学习资源的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/741=ebc
- 社区休闲设施的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/ckj=733
- 公共空间安全的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/q4y=TfG
- 公共卫生设施的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/067
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/pxa
- 基层服务创新的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/eWz
- 社区家校合作的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/227=rra
- 公园无障碍服务的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/mpl=132
- 城市可持续生活中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/H6i=yXu
- 节约用水实践的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/012
- 科普展览体验的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/ehh
- 公共交通接驳的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/TQO
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/909=prv
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/ejz=801
- 社区阅读服务的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/wvW=L4q
- 课后服务体验的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%98%9F%E5%BA%A7?/335
- 城市人文观察的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%98%9F%E5%BA%A7?/nin
- 城市建设科普的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%98%9F%E5%BA%A7?/i0i
- 家庭用电安全的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%98%9F%E5%BA%A7?/906=qpu
- 科普展览体验的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%98%9F%E5%BA%A7?/byi=889
- 数字创意课程中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%98%9F%E5%BA%A7?/S2c=Ldw
- 灵活就业交流的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/908
- 地方戏曲体验的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ckn
- 骑行路线规划的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/G4V
- 城市展览体验的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/276=cvj
- 科学运动指导的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/miu=622
- 劳动教育实践的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/E7A=lrK
- 通勤路线规划的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/711
- 公共空间休憩的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/zsz
- 街区更新实践的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/xAi
- 绿色生活实践的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/211=sfh
- 公共空间照明的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/ebj=417
- 课后服务体验的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/tGM=XLY
- 城市步行环境的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/673
- 社区垃圾回收的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/shw
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/Acx
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/356=ilv
- 老年数字阅读的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/edu=293
- 数字政务体验的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/N42=mZ7
- 城乡公共服务的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/122
- 小区电梯维护的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/hds
- 城市共享单车的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/9dM
- 软件开发学习的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/370=cmv
- 开源技术交流的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/tok=166
- 儿童户外活动的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/3K6=hZG
- 社区故事采集的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/850
- 社区交通安全的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/uki
- 节能家电使用的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/2tg
- 生活垃圾减量的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/660=vti
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/clx=979
- 社区公共议事的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/zF1=ubq
- 学校食育活动的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/741
- 社区家校合作的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/afo
- 社区花园共建的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/GAA
- 绿色办公实践的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/627=lwu
- 邻里共享空间的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/veb=070
- 骑行路线规划的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/GTr=kGI
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/333
- 低碳社区实践的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/gzi
- 城市展览体验中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/YHS
- 社区活动报名的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/636=rgt
- 传统节日科普的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/knk=492
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/hbm=sNP
- 城乡公共服务的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/627
- 社区防暑服务的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/xpd
- 城市步行友好的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/2KV
- 街区更新实践的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/918=bgx
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/xva=204
- 乡村产业科普的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/d3v=NXj
- 街区绿化养护的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/090
- 生成式工具使用的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/opz
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/YON
- 城市共享单车的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/157=qve
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/clm=580
- 传统节日科普的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/x7x=u9I
- 农业科普体验的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/443
- 公共文化活动中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/qhw
- 社区家校合作的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/ky6
- 开放式学习空间的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/179=yog
- 城市运动公园的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/hqn=503
- 健康饮水科普的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/4ld=Z7E
- 社区垃圾回收的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/276
- 公共交通接驳的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/tcu
- 食品安全科普的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/0fj
- 地方戏曲体验的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/277=srk
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/nfp=292
- 青年职业探索的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/LCi=vaT
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/164
- 数字支付体验的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/bps
- 公交站点体验中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/RFc
- 家庭养老规划的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/482=cwt
- 城市运动公园的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/hiq=378
- 家庭理财科普的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/G8I=XYi
- 家庭节能实践的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/814
- 公共服务咨询的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/olh
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/HiH
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/803=xqa
- 街道综合服务的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/qqk=536
- 公共场馆服务的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/Kq4=0zy
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/929
- 城市运动公园的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/wim
- 乡村产业科普的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/iIs
- 乡村产业科普的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/783=fex
- 数字课堂应用的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/skz=552
- 数字学习资源的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/o3k=Ocz
- 旧物循环利用的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/525
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/rng
- 就业技能培训的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/rlO
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/479=svv
- 网络安全教育中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/zjv=506
- 环境监测科普的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/4KI=YYi
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/359
- 城市夜间照明的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/bez
- 生活服务数字化的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/nMJ
- 家庭运动计划的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/222=ykj
- 城市基础设施的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/dxa=420
- 家庭用电安全的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/adO=y3D
- 街区道路维护的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/133
- 校园社团活动的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/goq
- 公共空间安全的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/bgo
- 社区手工活动的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/782=ofa
- 社区防暑服务的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/whe=652
- 垃圾分类指导的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/pR5=DgE
- 青年职业探索的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/199
- 药品使用科普的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/zdr
- 科学运动指导的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/3S1
- 地方旅游导览的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/023=aoz
- 城市文明出行的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/jno=120
- 家庭用电安全的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/FfH=b58
- 绿色出行服务的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/794
- 城市公共标识的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/nas
- 公共健身器材的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/zWQ
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/795=ial
- 儿童运动体验的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/yum=773
- 农贸市场环境的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/Tgk=sP1
- 公交站点体验的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/068
- 数字设备回收的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/atw
- 社区设施共享的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/0wQ
- 社区知识分享的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/151=yno
- 网络安全教育的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/pdi=404
- 社区宠物管理的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/S6K=qMX
- 社区阅读服务的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/820
- 绿色快递包装的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/wlw
- 城市空气科普的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/zN5
- 街区小店体验的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/697=qbk
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/lcg=798
- 城市文化路线的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/rha=xmk
- 气象科普传播的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/577
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/dye
- 科学观察活动的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/W31
- 城乡交通衔接的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/060=dlm

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
