# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:18**

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

- 科技馆参观体验的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/611
- 家庭健康管理的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/mhr
- 全民健身活动的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/4C7
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/165=tnb
- 数据分析入门的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/ndp=800
- 城市夜间生活中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/CTj=dk2
- 日常摄影记录的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/000
- 社区家政服务的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/mfb
- 邻里共享空间的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/0OZ
- 城市树木认养的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/601=tts
- 日常摄影记录的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ldt=397
- 家庭照护支持中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/D3A=tqo
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/950
- 社区活动空间的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/lik
- 社会体育指导的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/XjY
- 个人数据管理的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/790=nee
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/eyd=039
- 数字学习资源的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9123%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/CTx=XWf
- 绿色办公实践的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/446
- 城市文明出行的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/mjm
- 公共服务数字化的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/PLm
- 个人信息保护的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/108=kvc
- 家庭节能实践的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/fnl=258
- 城市适老服务的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/1Jm=OpM
- 家庭科学教育的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/460
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/onm
- 社区艺术活动的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/rva
- 城乡交流活动的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/720=sls
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/fix=169
- 数据分析入门的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/Z5k=CEU
- 科技馆参观体验的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/585
- 机器学习入门的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/khs
- 基层健康档案的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/UTB
- 城市基础设施的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/684=vzz
- 健康步道使用的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/ciy=378
- 社区文化传播的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_9123%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/2f6=s78
- 传统手工艺体验的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_9123%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/537
- 社区心理支持的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_9123%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/bcd
- 城市生活记录的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_9123%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/UeY
- 城市文明出行的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_9123%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/848=ese
- 数字学习资源的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_9123%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/ots=804
- 健康步道使用的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_9123%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A1%A3%E6%A1%88?/ckG=OL2
- 公园休闲体验的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/778
- 乡村产业科普的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/iwc
- 社区生活指南中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/F9d
- 社区环保活动的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/657=rtf
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/myy=226
- 垃圾分类指导的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/QnR=44D
- 应急物资管理的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/021
- 学校食育活动的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/tdg
- 文化讲座服务的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/VcC
- 生成式工具使用的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/198=moq
- 社区故事采集的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gju=711
- 公交站点体验的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/kvR=51S
- 乡村文化空间的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/042
- 公共文化活动的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fqe
- 城乡交流活动的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/BZQ
- 网络安全教育的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/328=xsk
- 社区学习活动的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/axv=473
- 学校食育活动的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lRo=emf
- 乡村公共服务的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E8%BA%AB?/782
- 家庭养老规划的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E8%BA%AB?/cmz
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E8%BA%AB?/thH
- 公共空间休憩的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E8%BA%AB?/563=jih
- 地方文化传播的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E8%BA%AB?/cyi=353
- 运动安全知识的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E8%BA%AB?/mvf=OKF
- 环境教育课程的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/602
- 社区活动策划的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/ywu
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/dMI
- 软件开发学习的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/644=xyn
- 街区绿化养护的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/xum=798
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/rmh=iRE
- 智慧城市体验的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/144
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/lvz
- 基层医疗预约的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/jO8
- 职业技能学习的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/155=sdy
- 社区心理支持的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/kcc=914
- 志愿者培训交流的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/llR=bIv
- 城市应急广播的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/706
- 乡村文化活动的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/xcf
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/B5w
- 数字档案服务的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/760=jls
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/znj=564
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/cn7=OK4
- 节能生活方式的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/061
- 城市社区治理的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/xxi
- 智慧停车服务的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/lNj
- 传统节日科普的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/484=ave
- 运动安全知识的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/vzg=479
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/4uq=err
- 基层服务创新的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/790
- 校园社团活动的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/cie
- 居家防滑改造的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/CuZ
- 社区生活指南的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/102=qjn
- 跨代沟通活动的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/nuo=969
- 城市绿道建设的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/xXq=mcZ
- 便民服务地图的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%88%B7%E5%A4%96?/763
- 社区垃圾回收的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%88%B7%E5%A4%96?/mof
- 消防知识宣传的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%88%B7%E5%A4%96?/LEs
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%88%B7%E5%A4%96?/272=art
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%88%B7%E5%A4%96?/xfr=167
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%88%B7%E5%A4%96?/VVu=opB
- 老年数字阅读的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/726
- 地方旅游导览的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/wob
- 公共设施使用的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/tqV
- 健康步道使用的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/766=bvu
- 家庭照护支持的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/tqf=556
- 读书会组织的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_988cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/yQU=Zjz
- 网络安全教育的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_988cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/142
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_988cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/fmi
- 城市噪声观察的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_988cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/OYr
- 非遗课堂体验的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_988cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/348=gol
- 本地消费场景的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_988cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/mfi=190
- 城市可持续生活的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_988cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/Ias=WbV
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_988cc%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/997
- 家庭运动计划的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_988cc%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/zht
- 亲子科普活动的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_988cc%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/zY9
- 文明养宠科普的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_988cc%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/851=ywc
- 光伏知识科普中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_988cc%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/ipu=100
- 公益活动组织的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_988cc%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/bqk=wC1
- 气象科普传播的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/226
- 城市共享单车的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/zgk
- 小微企业服务中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/Hdd
- 城市地名文化的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/766=rbo
- 读书会组织的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/fqj=795
- 家庭科学教育的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_988cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/2LC=icF
- 农村环境治理的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/614
- 老年智能设备的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/udo
- 家庭理财科普的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/sS7
- 公共服务预约的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/795=ubo
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/ghl=839
- 老年智能设备的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8?/UsV=ixd
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/566
- 公交无障碍服务的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/upq
- 社区交通安全的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/6Jj
- 社区养老服务的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/261=vrr
- 数字设备回收的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/elu=886
- 数字艺术创作的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_988cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/bkA=faL
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_988cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/865
- 公共设施使用的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_988cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/quy
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_988cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/tTD
- 便民维修服务的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_988cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/647=phg
- 科普展览体验的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_988cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/bxw=501
- 小区公共照明的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_988cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%BA%93?/zOd=G78
- 绿色出行服务的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E9%97%AE%E5%8D%B7?/729
- 科学观察活动的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E9%97%AE%E5%8D%B7?/jtk
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E9%97%AE%E5%8D%B7?/YyK
- 青少年编程学习的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E9%97%AE%E5%8D%B7?/851=ycn
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E9%97%AE%E5%8D%B7?/ozm=169
- 乡村产业科普的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E9%97%AE%E5%8D%B7?/OqT=3bT
- 机器学习入门的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/805
- 口袋公园建设的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/smf
- 数字政务体验中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/Vx3
- 社区家校合作的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/605=ngw
- 街区道路维护的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/bdw=779
- 青年就业服务的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/oQr=AIF
- 城市建设科普的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/158
- 校园节能行动的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/ero
- 科学教育活动的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/D2h
- 家庭园艺实践的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/788=qqf
- 人工智能科普的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/uug=800
- 节约用水实践的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/5bB=2Nk
- 小区公共照明的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/914
- 家庭健康科普的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/dpz
- 社区交通安全的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/bgR
- 社区信息发布的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/990=egr
- 社区共享书架的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/tct=805
- 街区道路维护中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/GLA=4jV
- 城市应急科普的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/357
- 地方文化传播的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/jii
- 创业经验分享中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/xKv
- 小区公共照明的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/686=bfr
- 城市休闲步道的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/iiw=973
- 通勤路线规划的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/k5G=KAE
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/854
- 社区设施共享的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/qga
- 绿色生活实践的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/JPu
- 社区体育组织的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/696=ohm
- 家庭健康管理的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/qmd=652
- 公共服务预约的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/RmV=FqB
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/671
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/mvk
- 骑行路线规划的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/F4m
- 基层健康服务的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/475=pqb
- 社区邻里服务的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/ymi=625
- 市民热线服务的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/JIh=U9n
- 城市应急广播的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/677
- 在线教育体验的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/gxy
- 通勤路线规划的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/b95
- 居家防滑改造的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/951=wdg
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/var=822
- 数字资源检索的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/Tie=Hkh
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/148
- 生活垃圾减量的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/jnd
- 儿童友好空间的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/QDk
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/852=lso
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/qpi=885
- 公共空间休憩的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/7Fp=MGA
- 城市运动公园的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/757
- 公共服务评价的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/xwe
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/3Xm
- 城市夜间照明的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/539=nkc
- 家庭健康管理中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/slw=465
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/xFg=Q0M
- 家庭消费规划的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/662
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/ehl
- 城市步行友好的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/pY7
- 社区花园共建的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/454=bah
- 数字便民地图的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/syt=601
- 社区快递服务的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/TKF=D0q
- 社区心理支持的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/037
- 乡村电商实践的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/ybx
- 乡村文化空间的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/9f6
- 在线学习体验的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/565=lrq
- 城市微更新实践中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/qji=833
- 数字阅读服务的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/TwJ=XBt
- 电子商务服务的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/010
- 基层健康档案的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/cgj
- 安全出行教育的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/nqs
- 地方文化传播的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/613=mcl
- 数字档案服务的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/pis=242
- 基层健康服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/BoD=d5m
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/348
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/wzz
- 开放式学习空间的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/g2q
- 社区文化节活动的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/879=wdh
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/yzn=222
- 终身学习资源的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/RGQ=tbt
- 数字设备回收的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/950
- 城市公共艺术的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/cnn
- 社区交通安全的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/xqx
- 城市步行友好的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/636=fjc
- 文明养宠科普的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/nnh=650
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/yjv=Xm9
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/359
- 科学健身方法的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/asx
- 居民健康教育的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/jRb
- 健康饮食教育的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/333=bms
- 数字创意课程的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/gyq=989
- 数字公共文化的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/pRT=pTj
- 本地消费场景的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/148
- 个人信息保护的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/qua
- 信息无障碍体验的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/drU
- 基层健康服务的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/045=zlf
- 家庭用电安全的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/iix=561
- 乡村公共服务的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/Bw9=Ztl
- 地方戏曲体验的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/711
- 小区公共照明的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/fyd
- 休闲运动入门的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/UdD
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/723=mwc

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
