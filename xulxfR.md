# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:19**

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

- 农产品品牌传播的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/832
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/olt
- 租房信息服务的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/RXD
- 科普展览体验的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/345=kkq
- 青少年户外教育的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/owr=118
- 社区共享书架的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/tko=P3K
- 家庭环保行动的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/966
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/avl
- 乡村产业科普的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/tXQ
- 学校体育活动的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/865=tbv
- 科学运动指导的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/koy=819
- 数据分析入门的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/CGG=pPh
- 城市应急广播的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/315
- 电动汽车充电的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/kvx
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/0IT
- 社区商业活力的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/374=ngh
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/kzk=485
- 数字支付体验的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/Up0=Vzx
- 家庭节能设备的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/012
- 家庭科学教育的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/sxd
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/8DQ
- 消防知识宣传的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/003=lwa
- 社区共享书架的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/rta=355
- 公共服务预约的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/xEd=goy
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/071
- 社区活动空间中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/xea
- 应急物资管理的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/z93
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/643=mnf
- 电动汽车充电的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/ydh=451
- 公交无障碍服务的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/lHS=KT8
- 读书会组织的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/228
- 数字素养提升的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/lgi
- 数字便民地图的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/Llg
- 乡村公共阅读的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/302=upj
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/ula=494
- 公共服务指南的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/nZd=5Br
- 志愿服务平台的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/588
- 校园安全教育的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/juq
- 城市共享单车的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/REk
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/205=inf
- 网络安全教育的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/zbw=300
- 课后服务体验的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/hIw=vCd
- 社区交通安全的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/114
- 环境教育课程的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/ifh
- 老年智能设备的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/g60
- 科普展览体验的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/324=ztw
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/lyf=313
- 便民服务地图的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/FLp=QqP
- 公共服务预约的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/814
- 租房信息服务的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/kjk
- 社区交通安全的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/jhJ
- 城市运动公园的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/375=maq
- 公共服务沟通的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/ccv=218
- 居民健康教育的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/qe8=cC6
- 城市雨天出行的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/469
- 城市微更新实践的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/eke
- 电子商务服务的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/ODG
- 城市公共厕所的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/613=cpb
- 公共健身器材的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/ffe=936
- 城市公共座椅中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/6Uy=YN0
- 城市微更新实践的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/038
- 软件开发学习的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/pjg
- 垃圾分类指导的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/zu2
- 农业科普体验的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/271=jej
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/aes=254
- 城市步行友好的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/wog=Zox
- 城市博物馆活动的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/638
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/qtx
- 数字政务体验的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/RCG
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/677=dai
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/pdu=639
- 科学信息获取的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/2IG=uLG
- 公交无障碍服务的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/063
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/epa
- 生成式工具使用的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/ou4
- 电动汽车充电的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/222=jis
- 街区道路维护中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/sgb=600
- 老年人文化生活的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/5PI=Ghw
- 数字艺术创作的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/781
- 节约用水实践的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/bvi
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/q7C
- 远程协作工具的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/793=jpy
- 城市慢行系统的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/eft=251
- 社区养老服务的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/L3W=nYF
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/684
- 社区教育资源的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/szz
- 城市雨天出行的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/F9k
- 校园阅读活动的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/138=cqe
- 社区托育服务的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/msd=689
- 食品配送体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/KZO=HLH
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/775
- 便民服务窗口的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/ono
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/UuC
- 图书借阅体验中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/540=evp
- 社区手工活动的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/ogp=205
- 社区互助网络的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/hMm=D6D
- 通勤路线规划的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/327
- 科学观察活动的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/ztc
- 周末休闲规划的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/KCS
- 个人时间管理的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/608=dcf
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/rxv=000
- 骑行路线规划的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/EsY=I4m
- 亲子科普活动的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/668
- 社区学习活动的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/qut
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/3FU
- 公共服务数字化的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/814=rwr
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/gmd=213
- 城市树木认养的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/aiZ=BRB
- 乡村文化活动的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/758
- 城市公共厕所的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/nso
- 公共服务指南的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/4N7
- 社区安全巡查的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/173=rmx
- 小区停车协商的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/eat=301
- 乡村生活观察的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/cli=g0f
- 城市微更新实践的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/423
- 无障碍出行的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/tqb
- 乡村文化活动的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/3Gm
- 数字生活课堂的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/502=xuk
- 小区公共照明的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/aat=058
- 校园节能行动的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/siL=gqx
- 青年志愿活动的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/074
- 节能生活方式的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/agd
- 街道综合服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/zQr
- 公共场馆服务的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/666=one
- 公共空间安全的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/nvz=308
- 乡村公共文化的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/fkt=rMa
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/880
- 城乡交流活动的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/tgz
- 社区防暑服务的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/x6x
- 青少年编程学习的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/789=jku
- 乡村教育资源的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/kro=485
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/nFv=jvp
- 公共空间照明的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/749
- 城市公共艺术的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/jna
- 人工智能科普的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/7IO
- 公共场所导视的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/801=erz
- 城市微更新实践的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/rog=950
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/Wud=l5E
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/287
- 绿色消费选择的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/kql
- 数字档案服务的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/OkZ
- 公交站点体验的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/907=jwi
- 便民维修服务中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/kdp=364
- 青少年编程学习的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/Jcb=Ss9
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/488
- 在线教育体验的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/khq
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/oGy
- 本地消费场景的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/141=fqg
- 社区手工活动的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/ikn=337
- 亲子科普活动的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/EGY=7e4
- 无障碍出行的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/056
- 城市展览体验的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/hta
- 电子商务服务的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/onP
- 城市基础设施的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/369=anf
- 城市应急科普的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/qra=725
- 公共服务数字化的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/Cit=1Io
- 文化场馆预约的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/543
- 生活垃圾回收的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/ibr
- 学校体育活动的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/z1e
- 老旧小区改造的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/093=nem
- 农村环境治理的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/szu=294
- 图书借阅体验的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/Zje=7tt
- 乡村教育资源的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/473
- 社区科普课堂的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/qaa
- 食品配送体验的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/9Ns
- 公交站点体验的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/768=ptb
- 街区小店体验的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/ngx=252
- 社区活动报名的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/1ce=XYH
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/970
- 城市应急广播的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/uva
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/ybK
- 本地旅行体验的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/920=uhe
- 城市建设科普的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/hip=334
- 绿色校园实践的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/2XQ=Xb5
- 公共场所导视的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/345
- 个人信息保护的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/gtb
- 志愿服务平台的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/jAD
- 公共服务沟通的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/496=ubx
- 生活垃圾回收的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/fvg=847
- 公共卫生设施的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/VDv=TSA
- 小区停车协商的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/860
- 城市步行友好的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/pjz
- 租房信息服务的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/wKR
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/130=isj
- 社区老年食堂的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/twq=121
- 城市文明实践中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/K13=BUm
- 街区小店体验的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/712
- 城市住房服务的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/twh
- 城市夜间生活的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/j09
- 社区科普课堂的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/767=bqd
- 光伏知识科普中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/viy=485
- 基层健康服务的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/rQD=Jb3
- 智慧停车服务的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/146
- 地方旅游导览的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/gpu
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/pqP
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/210=nln
- 数字政务体验中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/rrd=664
- 安全出行教育的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/hej=xmb
- 家庭健康科普的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E6%91%98?/725
- 读书会组织的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E6%91%98?/uuk
- 城市公共座椅的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E6%91%98?/Soh
- 校园阅读活动的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E6%91%98?/225=tst
- 基层健康档案的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E6%91%98?/uow=604
- 健康信息获取的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%96%87%E6%91%98?/tr2=hvW
- 数字便民地图的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/188
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/sbn
- 药品使用科普的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/AOP
- 城市空气科普的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/329=mim
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/vqb=023
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/uet=4pu
- 小微企业服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/906
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/kpk
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/ADT
- 乡村产业科普的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/576=zur
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/led=407
- 健康步道使用的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/QB8=6uZ
- 社区花园共建的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/553
- 非遗体验活动的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/eir
- 城市空气科普的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/voy
- 青年志愿活动的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/920=uwc
- 科学运动指导的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/jqe=738
- 社区信息发布的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/uYf=XsQ
- 居家适老化改造的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/722
- 网络安全教育的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/gpe
- 社区阅读服务的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/NsG
- 人工智能科普的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/310=ehd
- 日常摄影记录的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/cwt=947
- 社区活动策划的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/k52=E3P
- 城市公共自行车的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/499
- 公共文化活动的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/kfe
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/ETJ
- 家庭阅读计划的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/994=waw
- 街区道路维护的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/nzc=777
- 城乡交流活动的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/hcT=f1j
- 通勤路线规划的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/101
- 家庭阅读计划的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/opi
- 基层健康档案的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/kwU
- 绿色建筑理念的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/146=cxg
- 公共服务沟通的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/wae=852
- 绿色生活实践的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/2JU=BvR
- 公共服务预约的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/667
- 城市建设科普的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/ddm
- 乡村生态观察的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/j1Z
- 城市体育设施中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/099=upj
- 数字便民地图的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/cqm=435
- 食品配送体验中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/QCq=dQj
- 药品使用科普的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/603
- 软件开发学习的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/kzx
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/xKQ
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%BF%A1%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/801=rrk

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
