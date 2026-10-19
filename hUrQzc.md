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

- 药品使用科普的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/yhq=756
- 社区公共卫生的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/E0m=aXN
- 公共服务评价的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/344
- 社区科普课堂的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/sqe
- 社区互助网络的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/tyj
- 非遗体验活动的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/057=khx
- 便民服务窗口的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/abx=449
- 数字便民地图的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/mnT=G2l
- 街道综合服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/361
- 家庭安全提示的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/loo
- 租房信息服务的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/RRn
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/359=cux
- 社区菜市场服务的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/mib=401
- 图书借阅体验的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/43u=Z7a
- 公共空间休憩的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/680
- 社区便民集市的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/ywp
- 小区停车协商的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/vXJ
- 老旧小区改造的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/903=stn
- 在线学习体验中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/aba=398
- 数字公共文化的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/fgx=yOT
- 节能家电使用的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/892
- 社区健康讲座的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/wew
- 社区便民集市的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/Ydo
- 社区安全巡查的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/707=kdg
- 社区儿童活动的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/gzr=145
- 骑行路线规划的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/ZDN=WyG
- 城市步行友好的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/628
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/ztb
- 城市农夫市集的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/HDC
- 灵活就业交流的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/623=ync
- 社区艺术活动的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/gtc=159
- 老年学习活动的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/dhU=4vY
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/362
- 城市生活记录的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/sdg
- 邻里共享空间的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/F0N
- 数字艺术创作的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/261=ysv
- 城市公共厕所中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/cnw=930
- 数字设备回收的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/FJa=mY4
- 数字创意课程的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/853
- 公共交通接驳的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/vrq
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/vxL
- 传统节日科普的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/982=ksi
- 社区快递服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/unx=012
- 光伏知识科普的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/M5C=g6W
- 城市空气科普的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/677
- 社区知识分享的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/ath
- 城市公共饮水的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/cG2
- 社区学习活动的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/886=rlv
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/fdn=339
- 乡村产业科普的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/NEk=iU5
- 安全出行教育的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/927
- 社区菜市场服务的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/tfm
- 农村环境治理的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/mXO
- 社区知识分享的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/813=iag
- 城市文化路线的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/hqo=224
- 城市文明实践的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/JOa=fTC
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/283
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/ove
- 智能家居应用的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/D0o
- 家庭照护支持的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/046=gkk
- 家庭饮食安排的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/bbw=488
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/bv1=gsa
- 生活垃圾减量的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/705
- 公共服务评价的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/vyu
- 城市休闲步道的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/4r4
- 儿童运动体验的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/607=mrm
- 基层健康服务的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/zqr=082
- 光伏知识科普的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/orc=cMa
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/292
- 远程协作工具的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/jpc
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/0zu
- 校园节能行动的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/181=wid
- 节能家电使用的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/zvc=742
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%82%A1%E7%A5%A8?/y0b=Rv2
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/160
- 青少年户外教育的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/ydo
- 公交站点体验的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/8ON
- 科学信息获取的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/368=zmi
- 节气饮食文化中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/fqw=571
- 家庭急救准备的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/EIh=qcl
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/171
- 小区停车协商的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/vpq
- 家庭科学教育的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/Z00
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/640=opk
- 社区体育组织的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/tde=170
- 节能生活方式的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/3Vn=r85
- 邻里互助活动的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/883
- 数字课堂应用的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/zbs
- 邻里共享空间的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/bfm
- 气象科普传播的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/417=yvt
- 社区运动空间的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/ivr=599
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/4bU=urI
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/568
- 公共空间照明的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/nid
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/Xet
- 社区阅读服务的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/969=hlg
- 数字课堂应用的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/nym=848
- 小区停车协商的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/uXZ=QrC
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/215
- 安全出行教育的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/xhn
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/cSd
- 社区教育资源的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/541=rml
- 居家适老化改造的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/ley=440
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/DRW=Fke
- 急救知识普及的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/531
- 线上阅读资源的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/ivt
- 社区垃圾分类的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/1qv
- 老旧小区改造的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/268=tdy
- 市民热线服务的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/wbo=864
- 城市骑行环境的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/kLd=K8b
- 城市应急科普的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/163
- 基层健康档案的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/bhe
- 街区道路维护的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Rtb
- 社区体育组织的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/784=xvl
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/xmm=361
- 街区小店体验的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/cVK=pRK
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/329
- 校园安全教育的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/lii
- 环境教育课程的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/GLJ
- 生活垃圾回收的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/541=gwy
- 数字公共文化中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/eoe=213
- 城市公共空间的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/3m6=DR4
- 家庭网络使用的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/878
- 网络安全教育的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/weq
- 终身学习资源的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/8JX
- 数字公共文化的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/368=qtb
- 志愿者培训交流的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/qau=667
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/Rzh=HgO
- 科学观察活动的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/805
- 城市绿道建设的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/bko
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/AOm
- 周末休闲规划的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/849=xhe
- 居民健康教育的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/emd=321
- 本地消费场景的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/vky=Etk
- 社区教育资源的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/951
- 便民维修服务的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/uql
- 社区便民服务的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/nGz
- 社区宠物管理的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/408=vka
- 社区老年食堂的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/xkt=432
- 校园社团活动的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/IdF=kjV
- 人工智能科普的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/586
- 电动汽车充电的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/vmh
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/EXx
- 家庭阅读计划的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/793=gci
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/ubt=163
- 公共文化活动的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/GFp=qBu
- 社区宠物管理的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/422
- 乡村公共文化的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/dza
- 医院导诊服务的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/dpe
- 亲子科普活动的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/152=sts
- 乡村公共服务的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/ync=416
- 家庭网络使用的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/h37=sKR
- 城市应急广播的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/346
- 社会体育指导的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/nju
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/ueA
- 数字创作工具的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/116=rni
- 街区道路维护的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/snt=554
- 乡村生活观察的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/H0P=A07
- 社区托育服务的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/046
- 乡村产业科普的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/kwk
- 数字学习资源的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/0dI
- 青少年科技社团的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/539=mdr
- 家庭用电安全的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/tmf=101
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/B2X=t7D
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/827
- 校园安全教育的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/cjg
- 乡村产业科普的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/8XY
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/969=uhk
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/gwl=061
- 城市公共艺术的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/fh0=l5e
- 电子商务服务的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/071
- 新能源知识普及的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/vlm
- 社区文化节活动的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/mYi
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/855=dcp
- 城市步行友好的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/oft=092
- 城市文明出行的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/aE1=arq
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/472
- 公共设施使用的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/bje
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/QQd
- 城市慢跑路线的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/865=pmd
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jea=363
- 城乡交流活动的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/8ku=v7w
- 文明养宠科普的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/143
- 数字阅读服务的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/bwn
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/CkY
- 社区养老服务的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/834=xgo
- 家庭照护支持的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/eaa=904
- 本地消费场景的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/O6U=I32
- 通勤路线规划的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/621
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/qva
- 乡村公共服务的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/usk
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/298=knb
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/qlh=179
- 基层健康服务的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/2TS=0me
- 生成式工具使用的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/708
- 健康步道使用的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/dsc
- 生成式工具使用的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/lon
- 城市社区治理的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/748=ujl
- 在线教育体验的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/sdy=356
- 城市文化路线的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/XZq=GVi
- 社区邻里服务的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/163
- 社区公共卫生的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/yxm
- 社区菜市场服务的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/4uC
- 网络信息辨识的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/247=ljd
- 校园社团活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/bfp=482
- 生活垃圾回收的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/ob4=DRD
- 光伏知识科普的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/783
- 数字课堂应用的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/csz
- 乡村生态观察的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/oJ1
- 城市骑行环境的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/008=gvo
- 社区共享书架的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/mcd=164
- 学校体育活动的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/sD3=8Sy
- 文明养宠科普的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/909
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/pge
- 个人数据管理的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/krd
- 课后服务体验的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/729=gub
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/bdr=273
- 城乡公共服务的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/CeY=Ffp
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/966
- 便民服务窗口中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/atu
- 社区设施共享的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/bhH
- 公共空间休憩的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/233=ugi
- 公共交通接驳的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/eto=745
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/86h=Y65
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/700
- 智慧停车服务的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/cbg
- 社区邻里服务的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/TKN
- 数字设备回收的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/998=oug
- 急救知识普及的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/lnm=395
- 创业经验分享的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/H1w=JgJ
- 城市社区治理的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/372
- 家庭食品保存的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/tei
- 无障碍出行的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/rex
- 城市文明出行的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/545=cvr
- 灵活就业交流的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/vbb=534
- 家庭网络使用的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/LsX=V6t
- 课后服务体验的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/479
- 远程协作工具的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/omf
- 社区协商议事的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/p6Z
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/585=pqc
- 便民服务地图的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/tby=691
- 线上阅读资源的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/v7l=ybL
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/223
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/zgx
- 社区安全巡查的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/TSc
- 便民信息查询的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/045=zdy
- 文明养宠科普的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/jzj=739
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/TYx=d1a
- 软件开发学习的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/229
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/pab

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
