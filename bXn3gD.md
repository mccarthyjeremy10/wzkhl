# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:17**

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

- 数字生活课堂的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/SUt
- 智能手机助老的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/216=czh
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/swf=238
- 城市公共饮水的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/fjT=EzY
- 城市博物馆活动的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/937
- 小区电梯维护的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/rsv
- 公交无障碍服务的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/JGx
- 居家防滑改造的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/931=hor
- 城市夜间照明的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/vil=783
- 公共服务数字化的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/X1s=NnD
- 社区知识分享的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/191
- 青年志愿活动的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/vfx
- 城乡交流活动的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/OpK
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/563=mkr
- 数字设备回收的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/xjf=729
- 社区商业活力的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/smT=Bzz
- 社区读书角建设的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/249
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/dbh
- 便民维修服务中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/0uc
- 家庭健康管理的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/760=nfq
- 公交站点体验的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/tey=085
- 社区快递服务的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/xKh=RGH
- 健康饮水科普的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/055
- 家庭网络使用的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/xwh
- 数字创作工具的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/lXe
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/576=sim
- 社区健康讲座中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/afq=046
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/HVa=iAb
- 绿色生活实践的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/879
- 老年人文化生活的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/sdi
- 乡村产业科普的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/bmz
- 地方美食文化的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/335=niv
- 城市应急科普的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/ktu=429
- 环境监测科普的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/IB0=lLR
- 生活垃圾回收的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/747
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/fhk
- 城市社区治理的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/v85
- 机器人科普活动的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/688=htb
- 公共服务指南的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/bwl=033
- 乡村阅读活动的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/lOc=DuU
- 农产品品牌传播的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/371
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/zey
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/071
- 乡村生活观察的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/215=kee
- 公共文化活动的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/szg=098
- 本地旅行体验的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/SM8=T9U
- 儿童友好空间的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/476
- 公交站点体验的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/bkj
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/6td
- 节日文化体验中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/366=yum
- 老年数字阅读的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/ggp=236
- 智能家居应用的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/HG4=fcF
- 绿色快递包装的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/925
- 数字设备回收的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/jyj
- 城市应急广播的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/0eW
- 校园社团活动的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/388=pxz
- 农业科普体验的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/lqs=991
- 城市文化路线的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/nEA=uLV
- 青少年心理健康的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/253
- 户外活动组织的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/ubn
- 社区文化传播中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/oSS
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/151=thn
- 智能家居应用的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/jlo=635
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/fvV=aVV
- 信息无障碍体验的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/523
- 口袋公园建设的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/omk
- 乡村公共文化的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/DEA
- 城市公共空间的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/779=lxz
- 城市地名文化中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/ydy=350
- 社区垃圾回收的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/CHQ=X2S
- 数据分析入门的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/630
- 社区设施共享的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/ble
- 公共卫生设施的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/XpZ
- 数字艺术创作的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/940=wnv
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/mur=078
- 机器学习入门的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/8ly=NJk
- 绿色建筑理念的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/952
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/tnx
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/0Jy
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/296=pko
- 社区家政服务的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/pfi=938
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/NFO=bJW
- 社区科普课堂的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/456
- 城市公共空间的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/oge
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/1mK
- 生成式工具使用的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/639=hsv
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/gkw=291
- 公园亲子设施中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/VgF=FXk
- 社区生活指南的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/767
- 职业技能学习的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/jcc
- 家庭节能实践的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/vbm
- 小区公共照明的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/616=fec
- 科学运动指导的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/ron=902
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/qt5=kcx
- 城市展览体验的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/589
- 社区设施共享的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/rdu
- 绿色建筑理念的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/s37
- 城市公共厕所的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/742=ozq
- 社区法律科普的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/dry=059
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/kN5=QTm
- 地方旅游导览的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/461
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/pvu
- 应急物资管理的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/Kuy
- 环境监测科普的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/733=onu
- 社区读书角建设的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/evj=683
- 公共场所导视中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/xZU=9dm
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/738
- 城市地名文化的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/ptz
- 城市公共座椅的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/tqi
- 社区防暑服务的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/578=lij
- 智能家居应用的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/yqv=042
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A5%A8?/bdO=LGN
- 家庭教育交流的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/511
- 家庭志愿活动的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/tkt
- 青少年户外教育的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/wkF
- 城市公共饮水的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/192=axr
- 城市公共自行车的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/ltw=820
- 健康饮食教育的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/p3V=FUB
- 家庭网络使用的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/726
- 家庭用电安全的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/jft
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/hpp
- 街区更新实践的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/165=xdp
- 公交站点体验的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/xhu=510
- 劳动教育实践的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/Uc1=IPo
- 乡村教育资源的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/884
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/mdi
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/99q
- 环境教育课程的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/826=txi
- 城市文化路线的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/ket=706
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/HWn=CBO
- 城市人文观察的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/144
- 农贸市场环境的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/kaa
- 城市博物馆活动的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/CD4
- 口袋公园建设中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/799=kos
- 绿色办公实践的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/xrd=682
- 城市慢行系统的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/oXG=2C0
- 便民服务窗口的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/264
- 软件开发学习的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/zvg
- 公共文化活动的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/2ia
- 便民服务地图的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/454=gzb
- 传统节日科普的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/ksk=723
- 小微企业服务的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/tPD=5Et
- 社区便民集市的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/628
- 家庭食品保存的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/uig
- 城市地名文化的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/HEi
- 消防知识宣传的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/218=oya
- 数字课堂应用的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/qrh=765
- 数字地图应用的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/Ik7=xbK
- 数字课堂应用的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/038
- 本地消费场景的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/fjj
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/x82
- 老年运动活动的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/141=ona
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/wjj=889
- 乡村文化空间的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/cM9=kOk
- 周末休闲规划的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/851
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/fgi
- 家庭防灾准备的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/3Mx
- 本地消费场景的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/078=fhh
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/rgz=141
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/4Zs=az8
- 社区便民集市的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/681
- 城市水环境观察的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/wax
- 智能家居应用的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/CSs
- 食品安全科普的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/319=eni
- 在线学习体验的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/sxg=558
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/9OA=BdR
- 城市社区治理的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/386
- 青年职业探索的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/kre
- 公共服务数字化的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/VKW
- 文化讲座服务的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/790=htu
- 城市公共标识的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/jhr=093
- 非遗课堂体验的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/KiY=QhR
- 光伏知识科普的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/051
- 儿童安全出行的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/von
- 社区设施共享的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/Y9j
- 城市水环境观察的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/866=sin
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/tpl=835
- 乡村电商实践的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/Qvx=5A8
- 公共服务评价中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/376
- 社区快递服务的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/rcw
- 老旧小区改造的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/5fI
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/093=kml
- 公共空间休憩的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/ihh=551
- 科技馆参观体验的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/PmA=zac
- 地方旅游导览的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/317
- 家庭消费规划的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/mvt
- 城市建设科普的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/Ag8
- 城市应急广播的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/566=bwn
- 科学健身方法的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/ixb=362
- 绿色校园实践的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/SGE=yPG
- 图书借阅体验的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/258
- 公共场馆服务的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/agu
- 老年友好服务的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/B0d
- 户外活动组织的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/131=gbs
- 地方旅游导览的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/kjt=914
- 社区体育组织的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/QCE=dc5
- 青少年户外教育的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/566
- 基层健康服务的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/bca
- 社区便利生活的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/6bU
- 气象科普传播的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/576=ebl
- 电子商务服务的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/nfi=748
- 家庭急救准备的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/wYQ=Czr
- 科技馆参观体验的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/078
- 消防知识宣传的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/bdh
- 城市社区治理的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/8iR
- 城市公共厕所的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/677=nij
- 老旧小区改造的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/xpu=659
- 城市树木认养的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/N6F=kct
- 城市住房服务的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/039
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/obb
- 数字生活课堂的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/l7s
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/587=cvn
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/nqh=029
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/RWa=KaG
- 周末休闲规划的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/093
- 农产品消费体验的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/uta
- 社区老年食堂的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/2FV
- 在线学习体验的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/355=tua
- 绿色生活实践的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/utr=666
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/3z9=NDc
- 邻里互助活动的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%8F%B8%E6%B3%95?/074
- 课后服务体验的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%8F%B8%E6%B3%95?/kny
- 灵活就业交流的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%8F%B8%E6%B3%95?/7lE
- 社区共享书架的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%8F%B8%E6%B3%95?/978=rrb
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%8F%B8%E6%B3%95?/jpr=087
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%8F%B8%E6%B3%95?/C8A=oTM
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/675
- 老年人出行服务的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/gqs
- 社区设施共享的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/MHh
- 数字档案服务的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/103=huq
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/siq=571
- 居民健康教育的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9F%8E%E4%BA%8B?/Q7B=mEb
- 城市水环境观察的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/262
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/lry
- 老年学习活动的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/rBO
- 城市公共自行车的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/409=fwl
- 数字地图应用的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/vsk=654
- 乡村阅读活动的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/5DY=kGX
- 骑行路线规划的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/089
- 社区活动空间的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/cii
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/XB8
- 家庭健康管理的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/250=wkb
- 数字设备回收的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/pmk=668
- 小微企业服务的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/iV4=mdY
- 垃圾分类指导的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/721
- 城市博物馆服务的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/cdt
- 科学健身方法的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/UA2
- 学校食育活动的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/603=rla
- 数字生活课堂的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/kby=838
- 文明养宠科普的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/RrE=JVT

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
