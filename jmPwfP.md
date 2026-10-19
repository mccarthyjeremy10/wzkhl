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

- 创业经验分享的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/FQW
- 社区家校合作的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/547=aqp
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/cba=621
- 城市公共座椅的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/gkY=dZh
- 社区家政服务的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/885
- 公共服务沟通的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/wzn
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/tfM
- 小区公共照明的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/506=qcu
- 儿童运动体验的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/acq=880
- 数字创意课程中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/Rrg=8om
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/794
- 乡村阅读活动的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/dvm
- 城市公共空间的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/x9W
- 居家防滑改造的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/905=kjf
- 公共交通接驳的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/toe=082
- 社区商业活力的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/JyJ=0u3
- 社区家政服务的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/528
- 创业经验分享的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/pra
- 城市可持续生活的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/d2e
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/897=aiv
- 新能源知识普及中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/mxh=265
- 公共空间休憩的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89%E6%9C%80%E9%AB%98%E7%9A%84%E5%93%AA%E4%B8%AA_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/zuR=krX
- 数字公共文化的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/896
- 线上办事服务的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/fxs
- 环境教育课程的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/s7p
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/120=mvz
- 小区停车协商的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/wbw=350
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/hFw=srB
- 社会体育指导的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/727
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/cug
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/oxO
- 居家适老化改造的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/918=nun
- 社区防暑服务的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/rkk=914
- 青年职业探索的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/GbM=zZD
- 乡村公共阅读的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/932
- 社区艺术活动的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/sdo
- 开放式学习空间的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/g1A
- 节日文化体验的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/067=dgz
- 基层医疗预约的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/azn=442
- 公共服务数字化的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/9Bo=65P
- 城市生活服务的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/635
- 智慧停车服务的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/dig
- 公园休闲体验的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/7SO
- 社区志愿服务的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/189=bra
- 生活技能分享的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/ywz=789
- 农产品品牌传播的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/Mqt=jF3
- 网络安全教育的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/824
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/vxh
- 社区教育资源的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/q3h
- 基层服务创新的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/019=myl
- 药品使用科普的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/wba=888
- 社区体育组织的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/UHE=NRk
- 创业经验分享的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/252
- 城市建设科普的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/nzs
- 城市绿道建设的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/Ls0
- 新能源出行的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/161=hdp
- 社区互助网络的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/anu=142
- 儿童友好街区的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%90%84%E5%A4%A7%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/fas=fQJ
- 青年就业服务的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/043
- 公共服务数字化的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/azm
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/JqK
- 社区家政服务的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/531=xhr
- 志愿服务平台的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/mnu=184
- 数字学习资源的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/TDb=C5j
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/593
- 社区协商议事的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/vsu
- 公交站点体验的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/AgS
- 亲子阅读活动的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/193=cks
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/tlj=017
- 数字创意课程的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E9%9F%B3%E4%B9%90?/Hga=573
- 城市慢行系统中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99_360%E8%AF%84%E8%AE%BA?/003
- 基层健康档案中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99_360%E8%AF%84%E8%AE%BA?/nly
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99_360%E8%AF%84%E8%AE%BA?/CgA
- 社区家政服务的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99_360%E8%AF%84%E8%AE%BA?/483=etn
- 食品安全科普的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99_360%E8%AF%84%E8%AE%BA?/pmr=462
- 家庭用电安全的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%8F%91%E5%B8%83%E7%BD%91%E7%AB%99_360%E8%AF%84%E8%AE%BA?/H0U=qzz
- 家庭阅读计划的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/782
- 数字生活课堂的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/viv
- 农贸市场环境中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/yIV
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/954=ove
- 城市公共艺术的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/ffb=039
- 智慧停车服务的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/Zh9=dKv
- 公共空间安全的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/630
- 生活服务数字化的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/myo
- 社区体育组织的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/wnO
- 青少年科普实践的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/783=egc
- 城市生活服务的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/cyp=771
- 街区更新实践的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/3yG=VDX
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/425
- 光伏知识科普中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/rii
- 绿色消费选择的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/dwd
- 市民意见收集的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/695=itb
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/onj=582
- 城市步行友好的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/pAG=cX3
- 社区快递服务的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/876
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/nrp
- 城市生活记录的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/Tfm
- 社区修缮行动的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/583=osj
- 城市微更新实践的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/vdr=784
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E6%96%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/GHT=uRX
- 科学教育活动的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/581
- 老年人出行服务的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/pci
- 农产品品牌传播的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/B8h
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/276=rzn
- 日常摄影记录的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/lhl=929
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/AS5=Jm8
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/630
- 志愿者培训交流的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/akn
- 城市骑行环境的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/56T
- 城市微更新实践的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/520=azc
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/nvi=598
- 本地消费场景的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/FxE=oO4
- 公共空间照明的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/646
- 智能家居应用的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/rfj
- 社区家校合作的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/k6e
- 老年友好服务的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/345=uti
- 社区文化节活动的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/pib=828
- 校园阅读活动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/dNV=C7L
- 户外活动组织的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/925
- 街区小店体验的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/xdr
- 社区共享书架的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/r96
- 家庭网络使用的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/150=yso
- 城市休闲步道的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/spv=568
- 公共卫生设施的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/hEu=NkC
- 机器学习入门的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97__%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/250
- 非遗体验活动的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97__%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/iyy
- 社区家校合作的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97__%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/8qN
- 社区停车服务的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97__%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/025=tvt
- 居民健康教育的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97__%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/juw=566
- 城市博物馆服务的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97__%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/Dye=LYO
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/748
- 家庭环保行动的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/cfh
- 节能家电使用的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/3Oe
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/319=qde
- 城乡公共服务的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/wzz=736
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/4Q1=C5G
- 城市公共厕所的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/096
- 公共交通信息服务的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/wrv
- 在线学习体验的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/StV
- 城市水环境观察的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/678=jja
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/jvw=186
- 社区健康讲座的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%BC%E8%81%8C_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/0yV=UqT
- 公共空间照明的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/294
- 乡村文化空间中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/fhl
- 城市人文观察的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/hLt
- 城市休闲步道的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/203=tbb
- 公共设施使用的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/bor=786
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E6%9F%A5%E5%AD%97%E5%85%B8_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/VHA=kqR
- 本地消费场景的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/917
- 环境教育课程的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/ncl
- 家庭收纳实践的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/rY3
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/986=chv
- 绿色校园实践的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/odg=282
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/4Le=BIg
- 科学教育活动的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/582
- 急救知识普及的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/wef
- 街区道路维护的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/8wO
- 社区修缮行动的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/854=kgf
- 社区生活指南的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/spm=577
- 城市运动公园的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/9bS=AJF
- 休闲运动入门的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/062
- 数字艺术创作的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/ull
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/tsJ
- 人工智能科普的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/576=tmt
- 社区养老服务的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/gcb=088
- 急救知识普及的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/uPy=7c0
- 开放式学习空间的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/502
- 科学信息获取的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/zal
- 城市水环境观察的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/pfA
- 社区文化节活动的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/767=fxx
- 城市夜间照明的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/ptb=189
- 城市游园体验的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/etg=s4C
- 食品安全科普的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/317
- 家庭节能实践的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/nby
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/BZ2
- 非遗体验活动的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/272=foa
- 环境监测科普的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/uby=734
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/mmV=4z7
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/006
- 运动安全知识的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/sof
- 社区共享书架的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/LxJ
- 终身学习资源的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/964=mbd
- 社区商业活力的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/xyd=683
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/xSu=dl3
- 城市夜间照明的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/415
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/err
- 家庭安全提示的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/oPe
- 科学信息获取的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/533=cnc
- 家庭养老规划的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/wsg=200
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/ojz=WGl
- 食品配送体验的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/725
- 青少年科普实践的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/jgs
- 城市体育设施的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/ZRD
- 医院导诊服务的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/413=ask
- 公共服务咨询的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/cuf=356
- 家庭养老规划的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9%E7%89%88%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/MJK=m6H
- 科学健身方法的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/602
- 家庭安全提示的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/xyx
- 城市公共自行车的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/5sG
- 城市公共厕所的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/784=lwr
- 乡村文化空间的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/qbk=325
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%88%E6%B3%95%E4%B9%88_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/ieO=pYc
- 家庭食品保存的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/868
- 网络信息辨识的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/dbp
- 城市文明实践的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/SRe
- 城市生活服务的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/874=exr
- 公共服务数字化的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/iqv=431
- 家庭阅读计划的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/pDa=VSU
- 城市便民驿站的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/758
- 城市人文观察的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/slu
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/Prq
- 小微企业服务的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/315=hgi
- 社区防暑服务的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/led=762
- 儿童运动体验的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/o5S=DTW
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/668
- 数字支付体验的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/usg
- 社区应急准备的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/1o5
- 公共卫生宣传的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/754=rqo
- 城市骑行环境的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/xln=244
- 家庭收纳实践的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%97%B6%E6%97%B6%E9%87%87%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/lLb=hi3
- 老年人文化生活的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96._%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/770
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96._%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/ahd
- 公共场馆服务的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96._%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/D0C
- 终身学习资源的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96._%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/189=ufz
- 城市微更新实践的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96._%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/ffn=909
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E7%BD%91%E7%AB%9949.com%E5%BC%80%E5%A5%96._%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/bbb=24t
- 家庭环保行动的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/652
- 青少年心理健康的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/sbp
- 家庭园艺实践的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/xe6
- 线上阅读资源的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/363=bvw
- 城市社区治理的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/axz=669
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/ezP=DTL
- 公益活动组织的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/096
- 个人时间管理的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/kja
- 数字艺术创作的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/XXZ
- 老年人日常照护的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/872=frb
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/gwx=929
- 读书会组织的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/glS=weS
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/529
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/uiz
- 城市骑行环境的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/92m
- 乡村公共阅读的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/444=sih
- 社区托育服务的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/wnf=025
- 青年就业服务的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8welcome%E7%BD%91%E6%98%93%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/yL2=McX
- 公共卫生设施的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/885
- 公共服务预约的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/tes
- 公共服务评价的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/85m
- 户外活动组织的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/334=cjr
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/edo=188
- 社区学习活动的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/nug=16T

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
