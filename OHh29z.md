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

- 邻里共享空间的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvIII%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/KQT
- 社区健康讲座的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvIII%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/713=jpr
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvIII%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/xyw=467
- 社区宠物管理中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EvIII%E4%B8%8B%E8%BD%BD%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/Jc5=xAK
- 非遗课堂体验的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%AE%B6%E7%94%B5?/546
- 社区绿色空间的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%AE%B6%E7%94%B5?/clb
- 文明养宠科普的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%AE%B6%E7%94%B5?/jwR
- 社区宠物管理的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%AE%B6%E7%94%B5?/182=tcr
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%AE%B6%E7%94%B5?/tel=549
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E5%AE%B6%E7%94%B5?/8Ym=NVh
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_Welcome%E5%A4%A7%E5%8F%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/769
- 亲子阅读活动的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_Welcome%E5%A4%A7%E5%8F%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/fea
- 人工智能科普的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_Welcome%E5%A4%A7%E5%8F%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/0d7
- 城市生活服务的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_Welcome%E5%A4%A7%E5%8F%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/462=kou
- 光伏知识科普的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_Welcome%E5%A4%A7%E5%8F%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/hec=083
- 家庭消费规划的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_Welcome%E5%A4%A7%E5%8F%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%9E%AD%E6%9C%9B?/8Ra=sLL
- 城市公共厕所的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%A4%A7%E5%8E%85welcome_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/700
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%A4%A7%E5%8E%85welcome_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/fmw
- 基层健康服务的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%A4%A7%E5%8E%85welcome_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/yYs
- 远程协作工具的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%A4%A7%E5%8E%85welcome_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/735=uhy
- 社区家校合作的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%A4%A7%E5%8E%85welcome_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/zgq=280
- 街区更新实践的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%A4%A7%E5%8E%85welcome_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/5u6=z7b
- 科学信息获取的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/993
- 公共服务数字化中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/hqd
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/JcW
- 绿色生活实践的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/390=szw
- 校园安全教育的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/obv=557
- 乡村文化活动的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/Qla=HJm
- 家庭教育交流的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/702
- 消防知识宣传的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/unw
- 市民热线服务的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/bGk
- 乡村生活观察的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/443=svr
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/qpu=030
- 社区知识分享的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/Qml=fhA
- 科技馆参观体验的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/010
- 城市公共艺术的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/tul
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/TpY
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/631=pok
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/quq=175
- 公共服务预约的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/PUF=COC
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welco_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/995
- 节日文化体验的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welco_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/ilq
- 社区科普课堂的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welco_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/Q0V
- 社区手工活动的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welco_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/960=ujp
- 校园阅读活动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welco_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/ijb=968
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welco_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/RQL=RhS
- 城市水环境观察的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%BD%A9_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/454
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%BD%A9_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/myt
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%BD%A9_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/OBN
- 城市文明出行的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%BD%A9_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/706=jre
- 开放式学习空间的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%BD%A9_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/vlm=172
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E5%BD%A9_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/k9L=Lkr
- 医院导诊服务的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/749
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/erk
- 社区老年食堂的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/qvi
- 全民阅读推广的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/121=muo
- 社区公共卫生的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/bca=121
- 骑行路线规划的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/ZIr=s83
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/050
- 健康信息获取的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/wps
- 社区绿色空间的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/E03
- 城市体育设施的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/057=mgi
- 城市噪声观察的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/kxh=949
- 骑行路线规划的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/c8a=FZ6
- 城市文明出行的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%AF%BC%E5%B8%88_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/415
- 社区互助网络的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%AF%BC%E5%B8%88_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/wzx
- 绿色快递包装的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%AF%BC%E5%B8%88_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/Ky1
- 社区体育组织的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%AF%BC%E5%B8%88_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/606=ukb
- 城市便民驿站的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%AF%BC%E5%B8%88_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/unx=458
- 城市便民驿站的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%AF%BC%E5%B8%88_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/BFZ=VCa
- 环境教育课程的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E9%A2%86%E5%8F%96%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/676
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E9%A2%86%E5%8F%96%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/wyq
- 公共交通接驳的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E9%A2%86%E5%8F%96%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/kFS
- 亲子科普活动的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E9%A2%86%E5%8F%96%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/634=dfg
- 家庭网络使用的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E9%A2%86%E5%8F%96%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/wrn=910
- 家庭安全提示的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E9%A2%86%E5%8F%96%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/L5e=LBV
- 社区应急准备的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/833
- 社区教育资源的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/klb
- 气象科普传播的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/94p
- 小区公共照明的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/709=oai
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/ntv=545
- 社区共享书架的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/z9C=UCh
- 街区小店体验的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E4%B8%8D%E9%87%8D%E5%A4%8D_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/344
- 街区绿化养护的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E4%B8%8D%E9%87%8D%E5%A4%8D_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/muz
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E4%B8%8D%E9%87%8D%E5%A4%8D_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/TAG
- 社区知识分享的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E4%B8%8D%E9%87%8D%E5%A4%8D_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/016=emu
- 社区设施共享中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E4%B8%8D%E9%87%8D%E5%A4%8D_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/bvo=950
- 社区便民集市的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E4%B8%8D%E9%87%8D%E5%A4%8D_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/G7D=v1h
- 青年志愿活动的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0%E6%9C%80%E5%A5%BD_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/872
- 数字生活课堂的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0%E6%9C%80%E5%A5%BD_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/vot
- 本地历史资料的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0%E6%9C%80%E5%A5%BD_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/eRD
- 街区小店体验的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0%E6%9C%80%E5%A5%BD_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/791=zhi
- 老年友好服务的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0%E6%9C%80%E5%A5%BD_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/zvt=742
- 社区休闲设施的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0%E6%9C%80%E5%A5%BD_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/TnL=xxQ
- 城市公共空间的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E8%8E%B7%E5%BE%97_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/708
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E8%8E%B7%E5%BE%97_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/khp
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E8%8E%B7%E5%BE%97_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/MyZ
- 绿色消费选择的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E8%8E%B7%E5%BE%97_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/058=wum
- 生活技能分享的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E8%8E%B7%E5%BE%97_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/ujn=215
- 城市树木认养的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E8%8E%B7%E5%BE%97_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/ALF=d4z
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/964
- 社区花园共建的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/zlr
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/oq9
- 城市骑行环境的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/408=ezl
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/jsv=232
- 急救知识普及的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/DSG=u68
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/573
- 城市社区治理的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/xhh
- 社会体育指导的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/0k4
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/552=sbt
- 乡村公共阅读的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/zol=896
- 社区活动策划的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E8%B1%86%E7%93%A3%E6%94%BF%E7%AD%96?/j5u=mI2
- 城市运动公园的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_360%E6%97%B6%E6%8A%A5?/245
- 城市游园体验的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_360%E6%97%B6%E6%8A%A5?/jul
- 公共空间安全的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_360%E6%97%B6%E6%8A%A5?/yQj
- 本地消费场景的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_360%E6%97%B6%E6%8A%A5?/381=lzk
- 医院导诊服务的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_360%E6%97%B6%E6%8A%A5?/eph=486
- 青少年科技社团的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_360%E6%97%B6%E6%8A%A5?/dAd=xA1
- 生活垃圾减量的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%94%B6%E8%97%8F?/701
- 数字档案服务的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%94%B6%E8%97%8F?/yfm
- 运动安全知识的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%94%B6%E8%97%8F?/xoP
- 图书馆活动策划的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%94%B6%E8%97%8F?/494=rou
- 传统手工艺体验的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%94%B6%E8%97%8F?/hzw=457
- 学校食育活动的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%94%B6%E8%97%8F?/8ue=Cki
- 城市公共标识的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/816
- 在线学习体验的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/ebb
- 绿色办公实践的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/Qt3
- 基层服务创新的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/628=ijx
- 网络安全教育中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/bsw=811
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/rVd=Vft
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/896
- 乡村电商实践的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/nfg
- 城市微更新实践的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/Xll
- 城市树木认养的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/303=kcm
- 社区公共卫生的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/sib=116
- 社区托育服务的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/2gS=c22
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/353
- 青少年科普实践的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/pcn
- 小区电梯维护的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/NMK
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/143=wqc
- 乡村教育资源的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/uyy=005
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/SfP=GEQ
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/957
- 社区公共议事的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/ean
- 基层健康档案的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/l9E
- 社区知识分享的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/064=cyn
- 数字资源检索中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/epf=225
- 文化讲座服务的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/yBD=6Qn
- 街道综合服务的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/592
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/axh
- 城市共享单车的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xS7
- 街区小店体验的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/749=coi
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/oqb=043
- 乡村生态观察的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/6Hl=6t1
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/265
- 地方戏曲体验的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/ull
- 数字学习资源的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/9ls
- 线上办事服务的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/331=exw
- 公益活动组织的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/tae=783
- 社区健康讲座的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/5tY=QY0
- 公共文化活动的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A7l_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/362
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A7l_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/qqa
- 机器学习入门的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A7l_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/A3k
- 社区家政服务的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A7l_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/858=flc
- 社区垃圾回收的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A7l_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/dim=859
- 便民信息查询的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A7l_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/Mm3=Mid
- 数字档案服务的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/574
- 家庭健康管理的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/cgj
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/Odf
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/900=dif
- 口袋公园建设的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/snc=269
- 城市基础设施的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/qoe=77Q
- 农村环境治理的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/309
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/tpm
- 城市游园体验的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/XVs
- 公共空间导览中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/340=eys
- 地方戏曲体验的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/dfb=195
- 全民阅读推广的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/ljC=DQw
- 市民热线服务的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/695
- 线上阅读资源的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/rfr
- 智慧停车服务的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/ORU
- 乡村产业科普的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/989=yns
- 地方文化传播的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/uso=812
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/vIb=lfJ
- 城市住房服务的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/287
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/fcm
- 公共场所导视的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/EbK
- 低碳社区实践的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/799=vzr
- 公共交通接驳的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/bvv=293
- 健康饮水科普的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/t5G=0aT
- 公共空间导览的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91IIIV_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/207
- 口袋公园建设的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91IIIV_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/adk
- 家庭急救准备的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91IIIV_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/PSp
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91IIIV_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/791=guh
- 运动安全知识的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91IIIV_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/zay=124
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91IIIV_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/76F=7RJ
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/055
- 社区设施共享的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/gva
- 社区故事采集的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/DQW
- 读书会组织的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/716=dfe
- 城市展览体验的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/wdg=877
- 城市地名文化的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/Mg7=YAI
- 青年职业探索的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/451
- 城市住房服务的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/gsq
- 公共设施维护的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/0xW
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/026=rdu
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/uar=788
- 城市体育设施的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/was=UqZ
- 社区家校合作的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/919
- 数字课堂应用的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/vgl
- 公共交通接驳的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/8Os
- 城市夜间生活的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/474=wzd
- 城市应急科普的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/reg=776
- 城市公共空间的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/up0=2QA
- 城市公共座椅中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/063
- 街道综合服务的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/ewz
- 跨代沟通活动的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/DmG
- 电子商务服务的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/258=tqm
- 家庭急救准备的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/zhf=340
- 家庭运动计划的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/hS0=D4K
- 青年志愿活动的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/178
- 文化讲座服务的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/bup
- 基层健康服务的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/nR8
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/095=rlf
- 城市住房服务中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/xrx=313
- 家庭消费规划的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/doI=zom
- 社区托育服务的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/510
- 家庭照护支持的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/myx
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/uWq
- 邻里互助活动的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/580=oog
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/pyh=254
- 人工智能科普的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/sJe=lPa
- 城市绿色交通的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/645
- 职业技能学习的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/utq
- 就业技能培训的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/CG2
- 乡村文化活动的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/339=mfd
- 青年职业探索的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/jep=087
- 街道综合服务的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/fep=OnO
- 老年学习活动的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/575
- 社区设施共享的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/cho
- 节假日出行安排的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/Bhv
- 青少年户外教育的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/318=erb
- 开源技术交流的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/cyu=118
- 城市生活服务的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/obT=pIT
- 公园亲子设施的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/576
- 学校体育活动的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/cge
- 家庭理财科普的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/bEH
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/033=etb
- 社区法律科普的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/jjs=755
- 社区老年食堂的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/QFk=jXH

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
