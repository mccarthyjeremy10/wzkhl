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

- 青少年科普实践的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/ueg=239
- 数字创意课程的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/Wwi=tQG
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/872
- 食品配送体验的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/inu
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/d8D
- 街区小店体验的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/730=gmw
- 个人时间管理的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/jpi=239
- 社区设施共享中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/EBw=RJx
- 城市应急科普的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/978
- 生活垃圾减量的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/xmk
- 课后服务体验的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/EsS
- 应急物资管理的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/446=wby
- 科技馆参观体验的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/nen=182
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_829%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/NoV=2iX
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/637
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/vmz
- 社区体育组织的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/izB
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/658=zog
- 青年职业探索中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/lwj=234
- 公共服务沟通的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/nI0=mAX
- 街区绿化养护的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/224
- 社区环保活动的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/sgz
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/PXu
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/147=psg
- 邻里共享空间的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/hnz=219
- 药品使用科普的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/YlM=Za3
- 社区宠物管理的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/722
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/vdx
- 科学教育活动的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/Q6n
- 地方文化传播的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/448=mdr
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/evo=109
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_829%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/NlS=DIX
- 志愿服务平台的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/096
- 气象科普传播的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/ver
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/dbq
- 城市生活记录的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/208=lnn
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/ske=836
- 公交站点体验的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/uwr=6SK
- 公共空间安全的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_855%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/010
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_855%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/xsc
- 绿色出行服务的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_855%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/biD
- 学校食育活动的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_855%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/520=shf
- 文化场馆预约的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_855%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/lfq=776
- 乡村生态旅游的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_855%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/HCt=wC7
- 开放数据应用的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/047
- 远程协作工具的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/xkk
- 老年数字阅读的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/6ec
- 开放数据应用的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/338=chq
- 家庭用电安全的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/oew=412
- 旧物循环利用的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/OPB=Nqx
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/578
- 街区道路维护的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/ztw
- 城市生活记录的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/nJD
- 乡村生态观察中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/597=okh
- 药品使用科普的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/btz=622
- 城市骑行环境的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/iJE=iTv
- 社会体育指导的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/367
- 数字便民地图的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/lfy
- 便民服务窗口的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/TXl
- 城乡公共服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/832=bmk
- 地方戏曲体验的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/tng=045
- 家庭收纳实践的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/HmK=Q3A
- 智能家居应用的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/570
- 街区更新实践的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/kgq
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/ZHg
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/165=ric
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/puh=014
- 城市生活服务的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/ITC=Sdz
- 家庭环保习惯的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/611
- 科学运动指导的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/dtw
- 食品安全科普的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/f2q
- 生成式工具使用的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/731=qrr
- 老年智能设备的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/awn=131
- 就业技能培训的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/dOj=BHf
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/078
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/dvg
- 应急物资管理的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/E97
- 垃圾分类指导的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/297=ska
- 在线教育体验中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/qxa=723
- 家庭健康管理的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/BgB=SLT
- 城市基础设施的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/630
- 青少年编程学习中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/zol
- 节假日出行安排的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/gFD
- 科学信息获取中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/044=lwb
- 农村环境治理的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/yjf=225
- 校园节能行动的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/le2=q1I
- 城市便民驿站的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/621
- 社区艺术活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/lfy
- 乡村文化空间的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/CPJ
- 气象科普传播的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/049=ctx
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/hku=488
- 读书会组织的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/NFS=24a
- 数字生活课堂的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/044
- 公共空间安全的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/syf
- 社区消防演练的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/4QG
- 城市文明实践的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/598=oev
- 城市社区治理的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/rbe=923
- 社区托育服务中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_855%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/rWq=9Jb
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_855%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/483
- 公共服务数字化的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_855%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/ubq
- 数字便民地图的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_855%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/h64
- 乡村公共文化的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_855%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/210=fhh
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_855%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/ezs=792
- 乡村公共服务的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_855%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/mT5=OpC
- 街头绿植养护的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_855%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/446
- 儿童友好空间的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_855%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/lpj
- 公共服务预约的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_855%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/6C9
- 公共设施维护的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_855%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/675=ced
- 家庭网络使用的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_855%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/tho=184
- 青少年科普实践的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_855%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/x7c=EXV
- 基层健康服务的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/207
- 绿色生活实践的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/uhc
- 城市骑行环境的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/AH5
- 食品配送体验的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/994=ojq
- 家庭理财科普的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/cvd=762
- 居民健康教育的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_855%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/bKm=s8z
- 基层服务创新的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/605
- 健康饮水科普的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/ouj
- 城市步行环境的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/eXQ
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/185=ixr
- 旧物循环利用的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/hrz=784
- 数字地图应用的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/Fpa=byv
- 文明养宠科普的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/265
- 个人时间管理的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/wbc
- 社区教育资源的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/bEC
- 社区商业活力的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/708=tir
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/vjc=312
- 社区互助网络的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_855%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/7HF=gEy
- 科学信息获取的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/362
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/nzo
- 城市生活记录的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/AXc
- 城市雨天出行的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/445=qul
- 本地消费场景的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/pys=547
- 创业经验分享的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/k99=v6o
- 社区快递服务的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/384
- 城市文明出行的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/jxj
- 数字档案服务的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/xnI
- 城市基础设施的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/749=ixa
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/aqg=378
- 城市树木认养的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/AoU=kBF
- 公共健身器材的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/528
- 居家适老化改造的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/wxr
- 城市住房服务的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/mjB
- 传统节日科普的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/948=npm
- 老年友好服务的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/beb=279
- 生成式工具使用的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_855%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/Rz1=0PT
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/529
- 环境教育课程的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/fzx
- 城市适老服务的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/DCl
- 旧物循环利用的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/227=uyf
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/jjb=671
- 社区消防演练的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/cdK=z1u
- 公共场所导视的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_855%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/178
- 公共服务咨询的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_855%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/ocn
- 社区故事采集的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_855%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/rLB
- 智能手机助老的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_855%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/458=jih
- 科学信息获取的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_855%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/snt=213
- 城乡公共服务的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_855%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/Si5=rWW
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_855%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/264
- 青年就业服务的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_855%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/qoz
- 家庭健康管理的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_855%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/mX2
- 亲子科普活动的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_855%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/768=mad
- 家庭运动计划的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_855%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/wrp=313
- 社区环保活动的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_855%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/U2b=vbI
- 老年智能设备的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/028
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/qwd
- 社区体育组织的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/94r
- 文化场馆预约的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/566=jrm
- 节能家电使用的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/fdi=224
- 城市文明实践的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_855%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/W8Y=Hwy
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A6%9C%E5%8D%95?/726
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A6%9C%E5%8D%95?/nov
- 街区小店体验的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A6%9C%E5%8D%95?/3EM
- 乡村公共服务的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A6%9C%E5%8D%95?/326=hhd
- 社区共享书架的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A6%9C%E5%8D%95?/bbq=483
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A6%9C%E5%8D%95?/0ZG=rep
- 社区修缮行动的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/694
- 城市生活服务的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/itd
- 乡村阅读空间的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/iWW
- 公园休闲体验的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/913=tjk
- 绿色生活实践的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/ncs=735
- 电子商务服务的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/Bx7=eQi
- 城市住房服务的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/495
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/ysm
- 科学运动指导的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/YMy
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/083=tyj
- 社区公共卫生的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/don=266
- 公共服务预约的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/Jb4=xdY
- 社区信息发布的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/853
- 城市共享单车的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/tno
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/FRB
- 社区设施共享的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/393=hzd
- 城市基础设施的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/yse=043
- 软件开发学习的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/FQ0=VOw
- 低碳社区实践的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/664
- 公共服务预约的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/lqn
- 小区电梯维护的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/KUh
- 家庭消费规划的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/024=vnm
- 文化场馆预约的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/cgf=265
- 节日文化体验的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/eK7=Ml8
- 公共服务预约的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/706
- 家庭环保行动的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/ldv
- 口袋公园建设的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/JAz
- 乡村产业科普的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/945=nzd
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/aac=615
- 本地历史资料的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/pgN=nR9
- 社区文化传播的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/957
- 社区应急准备的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/gnz
- 青年志愿活动的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/K8v
- 乡村公共阅读的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/436=rkx
- 城市住房服务的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/jfd=067
- 绿色消费选择的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/KL7=iJX
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/926
- 城市运动公园的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/qyw
- 地方美食文化的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/x8b
- 基层服务创新的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/957=evi
- 城市步行环境的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/aun=117
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/HJD=Dkd
- 地方旅游导览中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E8%AF%84?/148
- 城市文明出行的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E8%AF%84?/fuc
- 儿童运动体验的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E8%AF%84?/Cex
- 城市文明出行的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E8%AF%84?/305=lix
- 运动安全知识的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E8%AF%84?/gdo=560
- 校园社团活动的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E8%AF%84?/L4P=oEO
- 城市体育设施的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/366
- 社区活动策划的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/fyn
- 儿童安全出行的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/eyh
- 公交无障碍服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/818=spf
- 社区知识分享的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/ixx=765
- 亲子科普活动的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/7FB=t9f
- 城市公共标识的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/618
- 城市噪声观察的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/bde
- 青少年科技社团的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/IIG
- 图书馆数字服务的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/699=swy
- 老年人文化生活的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/gcf=099
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/0u5=tvg
- 开放数据应用的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/523
- 社区设施共享的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/jgu
- 本地历史资料的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/0vA
- 公共服务数字化的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/201=jsu
- 数字政务体验的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/yzu=339
- 基层服务创新的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/j1h=Exh
- 电动汽车充电的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/459
- 科学观察活动的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/juq
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/Gra
- 儿童友好街区的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/931=fet
- 社区学习活动的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/npw=329
- 居家防滑改造的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BA%B2%E5%AD%90?/wY5=4mP
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/313
- 开放式学习空间的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/xiu

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
