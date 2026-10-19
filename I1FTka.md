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

- 远程协作工具的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/zro=136
- 邻里共享空间的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/zXW=OcU
- 公交站点体验的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/469
- 公共场馆服务的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/bxw
- 社区停车服务的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/pUQ
- 亲子科普活动的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/201=afp
- 节日文化体验的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/pnw=715
- 智慧停车服务的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/yK5=HPW
- 校园社团活动的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/488
- 家庭环保习惯的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/ajg
- 健康步道使用的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/DBZ
- 电子商务服务的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/581=thx
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/hcq=394
- 社区读书角建设的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/L9L=iDi
- 基层服务创新的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/791
- 乡村阅读活动的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/wor
- 运动安全知识的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/tZw
- 社区健康讲座的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/344=luh
- 公共空间休憩的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/dik=934
- 绿色快递包装的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/iJ9=lpO
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/655
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/gaz
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/Kf1
- 社区便民集市的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/801=wnp
- 通勤路线规划的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/ner=957
- 街区道路维护的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/X9Z=rQ0
- 机器学习入门的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%96%87%E5%BA%93?/296
- 数据分析入门的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%96%87%E5%BA%93?/ift
- 社区互助网络的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%96%87%E5%BA%93?/X4g
- 节能家电使用的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%96%87%E5%BA%93?/347=iit
- 社区法律科普的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%96%87%E5%BA%93?/mxw=183
- 口袋公园建设中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%96%87%E5%BA%93?/3xd=tmu
- 儿童运动体验的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/194
- 城市农夫市集的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/zwc
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/8sa
- 数字公共文化的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/493=umd
- 开放式学习空间的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/dsp=547
- 社区便民服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/0vq=VJl
- 地方民俗记录中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/542
- 数字政务体验的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/hlb
- 城市可持续生活的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/HEH
- 生活技能分享的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/069=aoc
- 青年职业探索的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/zcz=433
- 基层医疗预约的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/D1Q=2jZ
- 社区信息发布的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/032
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/zym
- 城市夜间照明的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/ISI
- 青少年户外教育的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/456=cje
- 环境监测科普的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/aro=632
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/dZi=EJU
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/225
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/lli
- 读书会组织的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/Wp7
- 全民健身活动的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/537=keg
- 老年人文化生活的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/pub=694
- 家庭食品保存的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/1vV=3tI
- 街区小店体验的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/748
- 公园休闲体验的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/gvt
- 药品使用科普的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/w04
- 老年智能设备的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/314=ymh
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/jox=320
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/DmP=Qnj
- 公共设施维护的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/502
- 职业技能学习中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/yvp
- 软件开发学习的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/jnZ
- 公共空间安全的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/737=jjk
- 城市微更新实践的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/dew=720
- 公共卫生设施的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/OSi=A8W
- 科学教育活动的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/712
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/qgl
- 在线学习体验的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/0XT
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/214=jdt
- 社区学习活动的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/wrp=992
- 社区儿童活动的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%98%9F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/ERT=idB
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/907
- 网络安全教育中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/jcf
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/luX
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/920=ora
- 社区家校合作的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/uaz=451
- 课后服务体验的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/UFK=SUi
- 城市文明出行的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/764
- 数字创意课程的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/mvf
- 城市社区治理的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/l6u
- 青少年户外教育的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/571=ebs
- 城市地名文化的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/ili=301
- 绿色校园实践的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/5Ob=WJ1
- 灵活就业交流的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/641
- 本地消费场景的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/fmk
- 家庭饮食安排的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/jUu
- 地方美食文化的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/647=rvn
- 公共空间休憩的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/zsz=981
- 智能手机助老的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/8gc=p15
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/286
- 社区便利生活的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/laq
- 运动安全知识的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/kXU
- 家庭消费规划的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/044=uox
- 小微企业服务的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/cgs=770
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/eh0=oZs
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/236
- 节假日出行安排的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/mjo
- 社区协商议事的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/Y2a
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/651=syc
- 网络安全教育的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/ozf=381
- 公共空间休憩中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/UvI=b3h
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/496
- 社区知识分享的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/qde
- 邻里共享空间的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/gPU
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/432=fhg
- 灵活就业交流的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/ess=008
- 青年志愿活动的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/YKM=kGO
- 健康信息获取的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/551
- 社区活动策划的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/cte
- 街头绿植养护的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/6fs
- 社区老年食堂的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/756=gzp
- 城市夜间照明的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/fnu=191
- 开放数据应用的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E6%98%9F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/Ovl=IRi
- 物业服务沟通的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/668
- 公园亲子设施的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/gfn
- 数字生活课堂的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/Mj0
- 数字档案服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/374=ssj
- 公共空间导览的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/htb=519
- 公共设施维护的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E6%98%9F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/M6T=tez
- 志愿者培训交流的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/284
- 儿童阅读角的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/fbd
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/NWU
- 个人时间管理的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/580=mve
- 公园休闲体验的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/ebv=021
- 街区绿化养护的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/QWw=CeQ
- 家庭急救准备的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/109
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/hlc
- 街区道路维护中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/cKc
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/443=utm
- 志愿者培训交流的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/dko=130
- 农产品品牌传播的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/XyZ=KMh
- 青年就业服务的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E5%B1%85?/613
- 居家防滑改造的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E5%B1%85?/lyw
- 图书借阅体验的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E5%B1%85?/7y6
- 数字便民地图的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E5%B1%85?/999=wui
- 社区便利生活的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E5%B1%85?/wqz=299
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E5%B1%85?/vcX=F7V
- 家庭健康管理的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/109
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/nam
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/lA9
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/451=ayd
- 个人时间管理的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/ykc=026
- 社区便利生活的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/gUD=LRn
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/092
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/xrl
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/SOC
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/078=ftq
- 城市社区治理的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/lal=637
- 社区故事采集的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/mXe=VV3
- 社区托育服务的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A7%86%E9%A2%91?/354
- 休闲运动入门的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A7%86%E9%A2%91?/ash
- 校园安全教育的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A7%86%E9%A2%91?/Pc4
- 城市运动公园的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A7%86%E9%A2%91?/511=vkf
- 志愿者培训交流的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A7%86%E9%A2%91?/sap=475
- 环境教育课程的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A7%86%E9%A2%91?/fDt=4jw
- 读书会组织的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/231
- 远程协作工具的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/edk
- 家庭用电安全的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/lEH
- 城市基础设施的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/048=wyq
- 智慧停车服务的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/apq=908
- 社区托育服务的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%91%A8%E6%8A%A5?/dPv=h50
- 数字设备回收的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%99%E8%82%B2?/757
- 校园节能行动的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%99%E8%82%B2?/otw
- 公共场馆服务的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%99%E8%82%B2?/nRN
- 社区活动空间的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%99%E8%82%B2?/977=wbl
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%99%E8%82%B2?/ylm=164
- 校园安全教育的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%99%E8%82%B2?/1tS=HEi
- 城市应急科普的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/752
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/idh
- 老年人文化生活的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/C2C
- 社区体育组织的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/666=ded
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/dmv=992
- 本地消费场景的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/1DP=2pi
- 社区活动报名的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/620
- 城市绿色交通的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/xiq
- 乡村文化活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/g69
- 健康饮食教育的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/710=lga
- 全民阅读推广的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/hqp=869
- 开源技术交流的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/y2f=yVe
- 光伏知识科普的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/140
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/ucb
- 物业服务沟通的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/uc3
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/767=qnx
- 社区养老服务的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/laz=216
- 应急物资管理的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/WNb=FNR
- 乡村生态观察的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/498
- 文化场馆预约的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/tdp
- 无障碍出行的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/trP
- 城市可持续生活的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/083=zcy
- 社区花园共建的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/qcv=704
- 老年人日常照护的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/GCa=W9O
- 青少年科技社团的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/925
- 在线学习体验中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/aka
- 社区设施共享的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/2Wg
- 数字资源检索的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/636=fnw
- 乡村公共文化的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/dfr=988
- 科学运动指导的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/vNp=Cbs
- 社区家校合作的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/020
- 全民健身活动的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/mxx
- 社区庭院绿化的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/6zG
- 公共服务预约的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/732=otp
- 青少年心理健康中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/mym=315
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/81P=0rR
- 生活服务数字化的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/977
- 职业技能学习的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mxu
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/8x8
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/544=bhh
- 数字支付体验的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/tkp=461
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/g3a=Cmi
- 数字档案服务的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/296
- 社区协商议事的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/qbe
- 社区学习活动的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/v2U
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/939=dgj
- 劳动教育实践的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/smi=656
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/L8a=QI5
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/553
- 公共服务咨询的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/alw
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/L4K
- 城市生活服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/140=nqe
- 街区更新实践的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/wiz=795
- 社区互助网络的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/MlD=7xK
- 社区信息发布的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF?/928
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF?/wrl
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF?/d2r
- 家庭照护支持的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF?/625=kai
- 家庭阅读计划的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF?/ubh=706
- 老年数字阅读中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF?/nWT=212
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/930
- 社区教育资源的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/jvt
- 科学教育活动的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/d2g
- 小微企业服务的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/057=uoc
- 绿色出行服务的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/ire=525
- 基层医疗预约的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/3Cq=oj7
- 课后服务体验的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/760
- 公共场所导视的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/rkb
- 数字支付体验的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/2f3
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/041=fav
- 城市文明实践的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/ube=283
- 公共服务指南的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/TZL=1te
- 家庭节能实践的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/922
- 周末休闲规划的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/noi
- 科技馆参观体验的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/Et6
- 城市树木认养的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/944=nzu
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/wna=768
- 社区共享书架的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/A0j=HIv
- 社区志愿服务的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/663
- 社区阅读服务的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/qut

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
