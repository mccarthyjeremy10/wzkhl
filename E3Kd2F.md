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

- 乡村公共阅读的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B0%91%E7%94%9F?/688
- 通勤路线规划的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B0%91%E7%94%9F?/vpw
- 文明养宠科普的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B0%91%E7%94%9F?/r4n
- 网络安全教育的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B0%91%E7%94%9F?/300=udx
- 城市噪声观察的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B0%91%E7%94%9F?/zij=691
- 社区科普课堂的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B0%91%E7%94%9F?/KYT=NX6
- 城市水环境观察的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/749
- 儿童安全出行的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/uka
- 家庭饮食安排的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/T94
- 健康步道使用的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/379=htd
- 家庭消费规划的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/dus=681
- 小微企业服务的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/AWK=AdE
- 城市博物馆服务的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_360%E6%99%9A%E6%8A%A5?/370
- 公共服务沟通的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_360%E6%99%9A%E6%8A%A5?/ive
- 社区便民服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_360%E6%99%9A%E6%8A%A5?/jWk
- 个人信息保护的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_360%E6%99%9A%E6%8A%A5?/108=ugc
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_360%E6%99%9A%E6%8A%A5?/jan=041
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_360%E6%99%9A%E6%8A%A5?/btJ=Kbs
- 数字资源检索的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/020
- 城市公共饮水的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/rdm
- 乡村生活观察的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/0wf
- 城市休闲步道的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/979=kjj
- 城市骑行环境的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/nsl=809
- 城市文明出行的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/BRs=Dwg
- 家庭科学教育的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/804
- 数字阅读服务的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/aub
- 社区家校合作的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/BjY
- 生活技能分享的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/856=ula
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/grj=027
- 公共卫生设施中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/5k1=KkR
- 亲子科普活动的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/535
- 机器学习入门的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/vcx
- 乡村文化活动的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/oDr
- 机器学习入门的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/713=dio
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/dga=149
- 节日文化体验的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/Fj7=35F
- 个人时间管理的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E7%A7%91%E6%8A%80?/649
- 老年人日常照护的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E7%A7%91%E6%8A%80?/nah
- 城市公共自行车的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E7%A7%91%E6%8A%80?/I7L
- 科普展览体验的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E7%A7%91%E6%8A%80?/487=tug
- 乡村阅读活动的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E7%A7%91%E6%8A%80?/jgd=288
- 数字艺术创作的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E7%A7%91%E6%8A%80?/RxI=j5i
- 开源技术交流的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/444
- 公共设施使用的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/xjo
- 儿童户外活动的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/mVH
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/719=uui
- 街区道路维护的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/iww=949
- 家庭健康科普的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/qPY=drk
- 城市公共座椅中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/367
- 绿色消费选择中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/ylc
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/7GE
- 科普展览体验的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/105=qra
- 社区消防演练的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/mly=891
- 城市公共空间的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/HPA=NnH
- 公共交通接驳的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/837
- 城市基础设施的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/bni
- 科学教育活动的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/KKw
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/390=skd
- 公共服务沟通的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/gfj=409
- 公共交通信息服务的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/jOM=4Lh
- 社区宠物管理的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/544
- 青少年科普实践的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/uta
- 城市公共饮水的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/7Jp
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/211=vca
- 街区绿化养护的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/eci=394
- 邻里共享空间的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/DwY=Q18
- 青少年科技社团的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/748
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/wuj
- 家庭运动计划的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/sxl
- 数字地图应用的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/639=wxd
- 街道综合服务的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/axu=192
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/2fE=Cjs
- 线上办事服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/032
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/urp
- 绿色办公实践中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/JHy
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/638=zxm
- 老年数字阅读的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/ait=348
- 城市微更新实践的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/uKd=I4w
- 社区环保活动的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%A8%B1%E4%B9%90?/247
- 公共卫生宣传的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%A8%B1%E4%B9%90?/riq
- 城市可持续生活的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%A8%B1%E4%B9%90?/Pr0
- 科学健身方法的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%A8%B1%E4%B9%90?/118=cuk
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%A8%B1%E4%B9%90?/tlv=561
- 城市住房服务的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%A8%B1%E4%B9%90?/oHy=3qg
- 本地消费场景的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/307
- 新能源知识普及的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/akw
- 社区科普课堂的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/bC4
- 城市慢行系统的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/537=yoh
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/uhq=255
- 本地旅行体验的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/zzW=rjg
- 绿色出行服务的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/997
- 家庭消费规划的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/ndl
- 公园亲子设施的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/W4T
- 线上办事服务的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/363=yep
- 数字支付体验的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/qac=632
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/PCp=OUQ
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/294
- 生活服务数字化的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/dom
- 城市运动公园的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/MXv
- 乡村产业科普的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/427=mad
- 小区电梯维护的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/dot=108
- 绿色出行服务的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/a7f=2t2
- 信息无障碍体验的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/508
- 儿童友好空间的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/zhv
- 亲子阅读活动的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/hIg
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/035=bla
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/flg=225
- 社区文化传播的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/S18=oOv
- 小区公共照明的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/186
- 社区活动空间的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/tti
- 科技馆参观体验的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/wJx
- 乡村生态观察的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/434=zro
- 劳动教育实践的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/tmv=848
- 基层健康服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/O2J=Goj
- 家庭用电安全的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/041
- 家庭节能实践的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/xce
- 青少年编程学习的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/Wah
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/812=khs
- 老年人出行服务的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/tsc=247
- 家庭节能设备的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/2AK=lBa
- 节假日出行安排的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/162
- 乡村公共服务中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vbg
- 城市地名文化的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/4bP
- 在线教育体验的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/261=pef
- 社区志愿服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kww=846
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tSN=2BL
- 软件开发学习的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/652
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/zcu
- 社区邻里服务中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/NkW
- 城市步行友好的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/225=lfz
- 生活垃圾减量的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/iyd=441
- 校园节能行动的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%8B%B9%E6%9E%9C%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/gUA=WCe
- 科学运动指导的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/820
- 应急物资管理的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/eig
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/3fy
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/342=afb
- 社区艺术活动的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/jsa=685
- 乡村文化空间的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/8ND=W6d
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/903
- 校园节能行动的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/idi
- 健康步道使用的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/T1P
- 社区快递服务的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/828=qxt
- 社区志愿服务的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/wbq=193
- 社区儿童活动的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/otQ=7Pa
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/827
- 本地历史资料的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/qqw
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/PYj
- 青少年户外教育的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/993=lgq
- 公共服务沟通的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/dzd=115
- 城市展览体验的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/GVf=UM9
- 环境教育课程的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/478
- 机器人科普活动的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/tvs
- 儿童安全出行的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/sGZ
- 节能家电使用的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/081=wzn
- 城市噪声观察的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/zhf=830
- 公共场馆服务的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/Ilh=Fvu
- 公共服务评价的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/227
- 社区便民服务的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/sio
- 城市文明出行的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/6iV
- 社区知识分享的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/024=eyb
- 数字艺术创作的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/awj=209
- 城市绿色交通的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/5dY=jzn
- 公共场所导视的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/101
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/ydq
- 城市公共饮水的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/JcX
- 急救知识普及的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/628=uve
- 城市文明出行的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/mep=178
- 社区安全巡查的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/5II=V4x
- 运动安全知识的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/934
- 社区手工活动的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/lyb
- 乡村公共服务的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/Lsm
- 社区知识分享的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/357=svd
- 数字阅读服务的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/yuw=629
- 邻里互助活动的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%85%AC%E7%9B%8A?/12V=R6x
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/496
- 数字支付体验的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/nby
- 气象科普传播的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/2zV
- 公益活动组织的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/142=jxk
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/onq=138
- 城市博物馆服务的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/weW=D6j
- 家庭网络使用的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E7%99%BE%E7%A7%91?/677
- 安全出行教育的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E7%99%BE%E7%A7%91?/vxo
- 青年志愿活动的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E7%99%BE%E7%A7%91?/tcb
- 在线学习体验的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E7%99%BE%E7%A7%91?/143=rwa
- 居民健康教育的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E7%99%BE%E7%A7%91?/spm=176
- 市民意见收集的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E7%99%BE%E7%A7%91?/gEj=srD
- 社区便民集市的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/867
- 数字设备回收的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/qyu
- 社区养老服务的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/6sA
- 公共服务数字化的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/579=lfl
- 公园休闲体验的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/epl=371
- 绿色校园实践的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/CRn=f06
- 药品使用科普的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/037
- 节气饮食文化的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/vtn
- 城市社区治理的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/QXE
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/437=wry
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/zmn=813
- 创业经验分享的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/Udn=Bh5
- 公共文化活动的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%83%E4%B9%90%E5%BD%A9-APP_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/555
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%83%E4%B9%90%E5%BD%A9-APP_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/oue
- 乡村教育资源的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%83%E4%B9%90%E5%BD%A9-APP_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/xi5
- 骑行路线规划的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%83%E4%B9%90%E5%BD%A9-APP_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/664=sfh
- 社区绿色空间的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%83%E4%B9%90%E5%BD%A9-APP_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/lif=108
- 青年就业服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B8%83%E4%B9%90%E5%BD%A9-APP_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/Dwn=DU9
- 乡村公共文化的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/260
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/msa
- 乡村公共文化的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/yKl
- 物业服务沟通的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/151=mih
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/vnk=449
- 智能手机助老的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%83%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/047=jMO
- 城市生活记录的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/723
- 终身学习资源的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/xlu
- 社区庭院绿化的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/tqL
- 城市便民驿站的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/082=mtg
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/lae=090
- 日常摄影记录的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/eYi=JFq
- 地方戏曲体验的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/019
- 公共场所导视的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/kny
- 地方民俗记录的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/Pby
- 数字课堂应用中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/441=fsf
- 社区环保活动的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/toa=726
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%83%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/Z5W=uZ8
- 青少年编程学习的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/189
- 家庭照护支持的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/tez
- 老年友好服务的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/pKM
- 老年智能设备的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/621=tqo
- 城市公共厕所的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/jhi=989
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/pZI=cwq
- 街区道路维护的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/234
- 软件开发学习的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/aao
- 市民热线服务的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/MKK
- 科技馆参观体验的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/258=aer
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/dwa=289
- 邻里共享空间的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/HtH=xhM
- 食品安全科普的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/554
- 社区活动空间的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/sau
- 小区电梯维护的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/UdO
- 科普展览体验的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/623=jte
- 地方美食文化的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/cvg=655
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/R6K=zOC
- 本地消费场景的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/515
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/psv
- 城市建设科普的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/iOj
- 食品配送体验的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/084=nem
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/exk=202
- 个人信息保护的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B8%83%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/FpQ=x6o
- 社区志愿服务的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/534
- 社区便利生活的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/skb
- 城市公共厕所中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/h5g
- 公益活动组织的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%83%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/981=css

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
