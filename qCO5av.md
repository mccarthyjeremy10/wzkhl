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

- 青少年心理健康的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/lpv
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/428=bmt
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/euq=797
- 租房信息服务的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/qWB=uUL
- 运动安全知识的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/155
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/lgc
- 青少年科普实践的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/yFc
- 市民意见收集的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/612=ttj
- 健康饮水科普的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/tvp=383
- 租房信息服务的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/p4Y=wqN
- 城乡公共服务的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/325
- 社区家校合作的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/sbv
- 社区交通安全的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/V1Y
- 终身学习资源的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/377=qms
- 本地旅行体验的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/tit=879
- 公共空间照明的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/vv0=SiG
- 通勤路线规划的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/070
- 社区安全巡查的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/elm
- 公共空间照明的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/89o
- 社区应急准备的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/891=wpg
- 基层服务创新的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/pvb=451
- 就业技能培训的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/4vX=BZX
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/352
- 在线学习体验的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/xvx
- 乡村阅读空间的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/KfJ
- 个人数据管理的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/551=fsl
- 城市公共座椅的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/vlu=620
- 数字创意课程的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/v0r=Szd
- 城市雨天出行的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/907
- 数字公共文化的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/bap
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/eqN
- 城市建设科普的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/105=jbr
- 数字素养提升的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/mod=288
- 科学健身方法的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/Vbo=meB
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/763
- 城市农夫市集的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/ixb
- 绿色办公实践的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/H6m
- 节日文化体验的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/900=tvw
- 城市雨天出行的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/tlw=355
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/0Qp=GGQ
- 城市应急广播的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/757
- 数字艺术创作的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/lrv
- 节气饮食文化的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/kUo
- 青年就业服务的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/941=owz
- 无障碍出行的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/kyz=908
- 城市文明出行的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/zeD=Iob
- 科学教育活动的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/292
- 食品配送体验的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/xzi
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/CkA
- 口袋公园建设的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/131=whe
- 数字公共文化的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/ovm=445
- 公共交通接驳的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/Rmn=2AP
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%BC%98%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/799
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%BC%98%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/zil
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%BC%98%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/C6L
- 健康饮食教育的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%BC%98%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/125=dyi
- 信息无障碍体验的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%BC%98%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/hpv=002
- 公交无障碍服务的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%BC%98%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/ur0=Sc4
- 家庭消费规划的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/323
- 城市建设科普的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/zvf
- 健康饮食教育的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/2mk
- 周末休闲规划的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/256=ztn
- 乡村文化活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/xls=222
- 公园亲子设施中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%BC%98%E4%B9%90%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/tar=ZKA
- 社区生活指南的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/828
- 社区休闲设施的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/dvx
- 家庭节能实践的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/fPF
- 公共空间导览的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/577=pla
- 家庭环保行动的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/jeb=450
- 街头绿植养护的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/Sbq=WX5
- 公共服务数字化的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/883
- 电动汽车充电的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/ued
- 社区快递服务的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/BKM
- 校园社团活动的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/087=hiy
- 城市水环境观察的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/jsw=441
- 城市应急广播的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/gxy=TOU
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/865
- 城市游园体验的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/kcz
- 老年智能设备的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/sxb
- 数字支付体验的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/357=rob
- 户外活动组织的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/uvo=939
- 科学健身方法的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%BC%98%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Nn0=uFM
- 地方民俗记录的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/998
- 骑行路线规划的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/ozk
- 公共设施使用的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/wZa
- 本地旅行体验的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/197=qaz
- 生成式工具使用的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/zpk=331
- 城市社区治理的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/t7B=xQO
- 社区环保活动的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/175
- 节能生活方式的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/ugr
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/yJq
- 城市步行友好的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/451=guu
- 家庭科学教育的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/mco=591
- 基层服务创新的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BC%98%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/VS4=N78
- 绿色出行服务的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/328
- 乡村文化活动的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/qqc
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/ca5
- 城市绿色交通的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/421=zmi
- 终身学习资源的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/mdi=933
- 社区协商议事的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/0Ay=AxQ
- 城市建设科普的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/704
- 城市公共艺术的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/zkc
- 街道综合服务的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/KgK
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/787=edh
- 基层健康档案的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/dtu=224
- 家庭环保习惯的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/ZTC=glC
- 公共空间安全的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/800
- 儿童友好空间的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/pah
- 青少年户外教育的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/gpx
- 城市基础设施的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/183=qjb
- 儿童户外活动的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/aes=704
- 电子商务服务的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BC%98%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/KFH=bnZ
- 数字资源检索的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/753
- 无障碍出行的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/qsg
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/Ve1
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/382=wce
- 小微企业服务的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/zex=264
- 校园社团活动的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%BC%98%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/ZWN=WK4
- 社区修缮行动的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/622
- 城市公共艺术的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/fny
- 社区文化传播的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/dGG
- 公共图书馆服务的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/225=qne
- 城市体育设施的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/ygm=677
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E4%BC%98%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/l0H=p8T
- 儿童友好街区的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/216
- 健康饮水科普中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/lfr
- 城市社区治理的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/VGm
- 城市公共标识的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/879=lex
- 公共服务预约的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/mmy=520
- 基层健康档案的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/iOq=qXN
- 无障碍信息设计的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/756
- 周末休闲规划的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/qbm
- 数字创作工具的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/01X
- 数字支付体验的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/436=htb
- 数字学习资源的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/ncg=539
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/tzw=ya8
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/882
- 家庭教育交流中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/umi
- 节气饮食文化的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/1Ck
- 城乡交流活动的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/913=gms
- 科学运动指导的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/znv=982
- 乡村文化活动的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/Yaz=Hvh
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/271
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/rhr
- 城市公共饮水的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/ybD
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/551=ouc
- 远程协作工具的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/gap=439
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/PT6=WK2
- 城市绿道建设的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/953
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/hqk
- 绿色快递包装的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/0Lz
- 城市建设科普的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/971=qla
- 地方文化传播的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/qgu=948
- 数字课堂应用的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/vjX=YmS
- 社区读书角建设的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/729
- 非遗体验活动的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/efp
- 社区心理支持的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/k0o
- 基层健康服务的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/693=cke
- 居家适老化改造的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/lao=155
- 健康步道使用的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/fz2=sIE
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/230
- 居家适老化改造的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/gkz
- 开源技术交流的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/jFz
- 数字创意课程的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/096=maa
- 老旧小区改造的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/hmr=681
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/eRK=6Eb
- 健康步道使用的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/223
- 学校体育活动的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/wdl
- 家庭节能设备的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/lEA
- 环境教育课程的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/363=sjr
- 老年友好服务的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/ktd=298
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/lxA=jsm
- 公共健身器材的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/604
- 城市公共厕所的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/pck
- 数字地图应用的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/cq0
- 城市展览体验的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/142=hvl
- 节假日出行安排的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/vrz=324
- 数字资源检索的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/WmP=Ej1
- 科学健身方法的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/702
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/bjl
- 家庭运动计划的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/0wz
- 社区艺术活动中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/465=acv
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/qmh=350
- 地方美食文化的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/2aY=4iP
- 农村环境治理的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/893
- 城市公共饮水的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/hda
- 职业技能学习中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/sQc
- 社区艺术活动的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/460=ugp
- 生活服务数字化的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/tvn=791
- 儿童友好空间的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/tQI=fIP
- 乡村生活观察的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/634
- 网络信息辨识中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/zhd
- 公交站点体验的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/oaM
- 开放数据应用的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/587=qwx
- 亲子阅读活动的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/itp=312
- 安全出行教育中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/xSa=xyu
- 基层服务创新的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/833
- 城市公共空间的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/ojr
- 文化场馆预约的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/7b9
- 青少年户外教育的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/386=qve
- 健康饮水科普的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/pcb=741
- 儿童友好空间的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/BeN=p0h
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/456
- 社区交通安全的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/sjb
- 绿色消费选择的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/4sJ
- 市民热线服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/730=sux
- 家庭照护支持的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/sss=940
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/NAt=CJL
- 文化讲座服务的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/202
- 乡村文化活动的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/qpq
- 青少年科技社团的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/Byc
- 社区垃圾分类的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/213=qtf
- 儿童户外活动的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/bqe=763
- 社区消防演练的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/wLf=iCl
- 家庭环保习惯的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/381
- 社区老年食堂的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/kph
- 社区消防演练的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/tnk
- 个人数据管理的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/528=yld
- 应急物资管理的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/zwl=923
- 城市慢行系统的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/a6Q=uP8
- 公共空间照明的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/078
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/pyj
- 城市博物馆活动的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/6LP
- 绿色办公实践的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/217=bez
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/rxz=655
- 节气饮食文化的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/Qlk=Uz8
- 绿色快递包装的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/412
- 公共文化活动中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/vwq
- 亲子科普活动的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/KMN
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/727=aja
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/lpp=558
- 老年友好服务的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/sV1=acy
- 家庭消费规划的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/462
- 公共设施使用的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/zvm
- 社区垃圾分类的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/UIj
- 个人时间管理中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/681=hxg
- 线上办事服务的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/tqt=401
- 数字设备回收的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/tMj=exg
- 校园社团活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/405
- 职业技能学习的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/dtd
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/gzx
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/259=enb
- 邻里共享空间中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/bwi=720
- 急救知识普及的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/v3K=1u5
- 街区更新实践的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/343
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/scc
- 无障碍信息设计的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/6ii
- 公共文化活动的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/121=zow
- 周末休闲规划的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/vgp=748
- 社区活动策划的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/4zc=gQk

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
