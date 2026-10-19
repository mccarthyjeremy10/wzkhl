# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 公交无障碍服务的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B9%90%E5%BD%A9_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/Yvs
- 家庭环保习惯的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B9%90%E5%BD%A9_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/648=gpo
- 校园安全教育的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B9%90%E5%BD%A9_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/mrm=590
- 绿色消费选择的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B9%90%E5%BD%A9_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/Jib=F0b
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3500_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/574
- 家庭健康科普的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3500_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/avm
- 公共服务数字化的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3500_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/9iZ
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3500_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/605=vwh
- 儿童安全出行的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3500_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/gdv=711
- 文化场馆预约的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3500_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/LyG=rjg
- 社区体育组织的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/103
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/ubq
- 租房信息服务的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/tFe
- 公益活动组织的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/250=bel
- 乡村阅读空间的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/xfn=065
- 青年就业服务的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/ZFP=Txa
- 社区家校合作的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/127
- 公共服务沟通的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/kel
- 物业服务沟通的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/UBY
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/455=fdf
- 地方美食文化的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/plo=504
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/1gD=Sut
- 公共场馆服务的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/485
- 家庭节能实践的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ktn
- 社区生活指南的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/30o
- 城市适老服务的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/696=eug
- 家庭食品保存的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/jbq=156
- 公益活动组织中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/jrx=rFw
- 非遗体验活动的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/686
- 社区修缮行动的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/ylb
- 无障碍出行的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/1Kv
- 家庭志愿活动的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/044=nmn
- 就业技能培训的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/uuy=141
- 周末休闲规划的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/pln=rC5
- 老年运动活动的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/203
- 家庭用电安全的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/iij
- 城乡公共服务的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/lgO
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/891=joi
- 家庭急救准备的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/yfd=869
- 家庭节能设备的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/BIG=MF1
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/166
- 社区休闲设施的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/gzt
- 基层医疗预约的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/EQT
- 科学信息获取的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/721=grh
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/nyr=381
- 节约用水实践的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/4uz=wUB
- 智慧城市体验的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/467
- 社区老年食堂的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/gts
- 社区活动策划的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/20b
- 老年人文化生活的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/703=jtt
- 城市运动公园的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/mrk=704
- 城乡交通衔接的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/669=96f
- 乡村文化空间的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD1.0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/875
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD1.0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/vgc
- 社区托育服务的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD1.0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/KXo
- 家庭照护支持的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD1.0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/282=dpp
- 儿童友好空间的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD1.0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/zfz=908
- 电动汽车充电的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD1.0_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/oMv=7R1
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/219
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/ffr
- 非遗体验活动的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/d8v
- 公共卫生设施的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/386=mqf
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/myk=263
- 街区绿化养护的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/vvu=tLc
- 社区垃圾分类的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/969
- 社区手工活动的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/fvm
- 城市生活记录的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/Nc3
- 骑行路线规划的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/412=ifb
- 新能源出行的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/yfl=278
- 老年智能设备的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/KfU=1iZ
- 文化讲座服务的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/565
- 个人时间管理的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/uyr
- 社区快递服务的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/efO
- 绿色办公实践的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/652=vkf
- 职业技能学习的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/fxo=797
- 数字政务体验的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/TwC=J3Q
- 机器人科普活动的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/914
- 周末休闲规划的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/sdx
- 小区公共照明中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/l3T
- 农业科普体验的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/264=lqw
- 小区停车协商的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/hwz=079
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/nPD=mxd
- 校园社团活动的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8vip%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/722
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8vip%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/bik
- 在线学习体验的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8vip%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/EHd
- 文化场馆预约的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8vip%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/921=wzb
- 街道综合服务的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8vip%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/gfd=443
- 城市噪声观察的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8vip%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/y1c=cEX
- 社区活动策划的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/604
- 智能家居应用的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/skt
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/sBx
- 绿色生活实践的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/874=jrg
- 老年友好服务的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/elb=501
- 家庭节能实践的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/NX9=wed
- 城市社区治理的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/631
- 公共服务数字化的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/rtj
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/Lfb
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/553=aju
- 儿童友好街区的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/arh=776
- 社区活动报名的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/B05=Hh4
- 农产品消费体验的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E5%85%AC%E7%9B%8A?/918
- 社区消防演练的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E5%85%AC%E7%9B%8A?/smc
- 社区手工活动的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E5%85%AC%E7%9B%8A?/CkS
- 本地历史资料中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E5%85%AC%E7%9B%8A?/544=aid
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E5%85%AC%E7%9B%8A?/kjc=849
- 公共场所导视的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%9F%A5%E4%B9%8E%E5%85%AC%E7%9B%8A?/GUB=nGx
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/627
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/lod
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/UC2
- 光伏知识科普的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/951=tgi
- 城市步行友好的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/yle=407
- 旧物循环利用的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%88%8A%E7%99%BB?/NMr=ucx
- 绿色快递包装的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/055
- 图书借阅体验的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/xph
- 社区防暑服务的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/69x
- 社区商业活力的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/706=rkc
- 非遗体验活动的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/lmf=436
- 公共服务评价的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/fsV=1Pl
- 安全出行教育的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/394
- 社区商业活力的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/kmy
- 文明养宠科普的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/Cyh
- 文化讲座服务的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/694=jbt
- 社区志愿服务的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/mus=623
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/XJY=EXK
- 数字课堂应用的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/768
- 食品安全科普的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/kgr
- 节日文化体验的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/AnD
- 儿童户外活动的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/041=gwf
- 城市公共艺术的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/vnl=146
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/q3p=j0U
- 街区绿化养护的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/791
- 智能手机助老的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/xlj
- 人工智能科普的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/csa
- 社区安全巡查的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/003=gxx
- 公共卫生设施的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/yhc=399
- 网络安全教育的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/Hpl=1xk
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/965
- 数字素养提升的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/pqo
- 公共场馆服务的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/Ao9
- 城市公共座椅的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/070=myc
- 家庭节能实践的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/qtk=854
- 家庭理财科普的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E4%BA%BA%E7%89%A9?/6k5=d8o
- 绿色消费选择的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/021
- 绿色生活实践的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/btr
- 社区活动策划的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/HaO
- 城市共享单车的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/158=ejl
- 健康饮水科普的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/ibg=213
- 儿童友好空间的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/RiI=m3i
- 儿童户外活动的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/491
- 老年友好服务的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/pvt
- 安全出行教育的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/b1Q
- 便民服务地图的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/622=dfx
- 城市雨天出行的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/vxf=343
- 基层医疗预约中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/IGS=1oE
- 本地消费场景的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/362
- 公共设施使用的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/mew
- 生活技能分享的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/iAs
- 全民阅读推广的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/657=vzc
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/mep=967
- 公园休闲体验的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/G4x=MIf
- 社区活动报名的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/659
- 网络信息辨识的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/axs
- 志愿服务平台的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/gSG
- 公共服务预约的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/372=bgo
- 运动安全知识的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/vip=179
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%89%B9%E7%A8%BF?/Ahq=t7g
- 网络安全教育的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/080
- 健康饮食教育的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/yor
- 电子商务服务的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/K0m
- 科学健身方法的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/065=pdv
- 本地旅行体验的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/yvq=801
- 城市人文观察的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/p4Z=C6k
- 城市共享单车的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/917
- 公共服务指南的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/opz
- 社区庭院绿化的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/qXx
- 公共空间安全的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/029=mxg
- 科普展览体验的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/gek=029
- 科学教育活动的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/Eok=D2g
- 公共设施维护的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/116
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/joq
- 科学教育活动的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/fys
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/193=fkr
- 社区文化节活动的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/gmr=954
- 社区垃圾回收的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/pxI=2md
- 家庭饮食安排的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/795
- 职业技能学习的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/qut
- 便民信息查询的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/0it
- 应急物资管理的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/545=hdp
- 智能手机助老的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/iyk=022
- 社区协商议事的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/2kF=LlX
- 科普展览体验的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/563
- 青少年户外教育的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/jrn
- 社区体育组织的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/mbB
- 本地旅行体验的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/984=vac
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/aeq=097
- 社区手工活动的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/U4W=xVO
- 家庭环保行动的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/319
- 城市公共厕所的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/xxf
- 地方戏曲体验的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/4M0
- 科学运动指导的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/705=keg
- 社区消防演练的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/uwo=734
- 科学信息获取的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/ZqX=7BZ
- 社区学习活动的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/474
- 青少年户外教育的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/ffi
- 学校食育活动的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/Awe
- 乡村教育资源中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/562=tbf
- 老年运动活动的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/syh=062
- 数字资源检索的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/4WU=1EZ
- 小微企业服务的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/583
- 青少年科普实践中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/tvm
- 街道综合服务的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/asA
- 周末休闲规划的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/492=rma
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/uzx=977
- 校园阅读活动的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/s6O=9ZQ
- 公园休闲体验的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/847
- 乡村公共文化的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/jki
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/Tdq
- 社区托育服务的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/004=miw
- 应急物资管理的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/aql=511
- 家庭照护支持的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/NN0=Yvf
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/002
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/lwj
- 个人信息保护的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/39o
- 光伏知识科普的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/417=nok
- 旧物循环利用的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/yof=336
- 城市步行友好的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/GeN=X0J
- 社区艺术活动中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/826
- 绿色校园实践的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/pjv
- 社区读书角建设的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/Vye
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/550=ffx
- 骑行路线规划中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/zjr=375
- 绿色消费选择的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/oMm=ikh
- 数字学习资源的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/424
- 城市便民驿站的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/pku
- 绿色消费选择的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/Bcy
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/994=bak
- 社区便民集市的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/ouk=311
- 街区小店体验的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/BMv=0LE
- 数字便民地图的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/384
- 绿色出行服务的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/wxh
- 社区应急准备的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/XdH
- 家庭阅读计划的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/351=xgu
- 社区交通安全的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/wnc=424
- 公共交通接驳的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/a3j=h5d
- 居民健康教育的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/395
- 公园休闲体验的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/ytt
- 数字素养提升的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/j1R
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/316=qhk
- 急救知识普及的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/xix=893
- 社区科普课堂的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/v3z=So5

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
