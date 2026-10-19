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

- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/T4e
- 地方旅游导览的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/900=fyc
- 居家适老化改造中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/hir=129
- 社区互助网络的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/qRh=3dR
- 邻里共享空间的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/217
- 城市公共艺术的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/sud
- 无障碍出行中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/feD
- 家庭运动计划的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/614=efk
- 居家防滑改造的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/xek=729
- 家庭照护支持的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/rJ4=gzt
- 乡村产业科普的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/143
- 城市休闲步道的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/anh
- 社区法律科普的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/Ywu
- 公共空间照明的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/051=jvf
- 旧物循环利用中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/gql=134
- 社区商业活力的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/rRr=sQB
- 科技馆参观体验的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/638
- 城市步行友好的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/nsy
- 社区垃圾回收的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/1xM
- 社区知识分享的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/204=viw
- 健康步道使用的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/knw=581
- 绿色校园实践的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/qPs=MUT
- 城市基础设施的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/237
- 乡村电商实践的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/tbp
- 家庭健康管理的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/oN3
- 城市公共标识的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/524=nza
- 城市社区治理的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/suo=605
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/Q2i=Zhc
- 通勤路线规划的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/843
- 城市公共艺术中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/gcv
- 城乡公共服务的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/NyT
- 城市生活记录的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/784=pqt
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/rxg=821
- 城市步行环境的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BC%80%E5%BF%83%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/5RY=jsC
- 城市游园体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/513
- 居家适老化改造的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/kuj
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/lER
- 劳动教育实践的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/506=imk
- 城市夜间照明的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/dyn=881
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/E5q=rrR
- 社区便利生活中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/306
- 家庭健康管理的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/zhl
- 社区故事采集的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/weu
- 青少年科技社团的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/015=bxd
- 青年职业探索的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/ehy=493
- 城市微更新实践的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/wMJ=pHh
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/550
- 公共交通信息服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ruj
- 儿童运动体验的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/mPv
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/187=qra
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/irh=552
- 青少年科技社团的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Fp7=cv9
- 老年学习活动的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/616
- 终身学习资源的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/tps
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/rOY
- 老年友好服务的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/397=eyx
- 家庭运动计划的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/cbi=228
- 小区停车协商的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E6%96%B9?/LFd=sko
- 小微企业服务的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/033
- 社区养老服务的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/eph
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/Fhp
- 基层健康服务的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/417=ckz
- 社区共享书架的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/vwa=760
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/lKx=wzS
- 社区信息发布的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%85%AC%E5%BC%80%E8%AF%BE?/403
- 居民健康教育中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%85%AC%E5%BC%80%E8%AF%BE?/tgt
- 药品使用科普的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%85%AC%E5%BC%80%E8%AF%BE?/nxO
- 城市步行友好的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%85%AC%E5%BC%80%E8%AF%BE?/191=jpm
- 科普展览体验的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%85%AC%E5%BC%80%E8%AF%BE?/dta=757
- 智能家居应用的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%85%AC%E5%BC%80%E8%AF%BE?/c5K=WjS
- 绿色校园实践的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/758
- 城乡交通衔接的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/psy
- 市民热线服务的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/TMX
- 软件开发学习的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/380=jlp
- 社区科普课堂的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/miy=002
- 社区体育组织的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/IN2=Pre
- 儿童运动体验的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/435
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/pze
- 校园安全教育的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/uXh
- 城市步行友好的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/018=ppq
- 社区托育服务的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/bqh=208
- 公交站点体验的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/eQP=dRF
- 志愿者培训交流的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/771
- 无障碍信息设计的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/act
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/v6C
- 公交站点体验的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/984=umz
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/vnu=132
- 公共健身器材的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/6iQ=w5I
- 智能家居应用的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/903
- 节约用水实践的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/bfd
- 社区法律科普的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/eRV
- 节假日出行安排的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/358=qgz
- 地方旅游导览的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/mya=159
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/4dL=qC7
- 职业技能学习的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/453
- 绿色消费选择的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/vti
- 公园亲子设施的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/87p
- 休闲运动入门的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/573=yxm
- 城市步行环境的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/gzv=653
- 在线教育体验的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/Dry=vBq
- 低碳社区实践的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/856
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/ojk
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/t6f
- 城市休闲步道的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/106=nld
- 邻里互助活动的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/skd=389
- 邻里互助活动的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/k04=ycp
- 农村环境治理的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/647
- 家庭志愿活动的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/fre
- 儿童运动体验的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/k9Z
- 家庭急救准备的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/632=twd
- 社区读书角建设的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/xby=221
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/ZcK=ulQ
- 新能源知识普及的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/505
- 地方旅游导览的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/hmr
- 医院导诊服务的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/uyx
- 家庭环保行动的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/027=euj
- 社区交通安全的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/jtl=167
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/RqK=wMo
- 老年人日常照护的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/131
- 科普展览体验的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/mov
- 软件开发学习的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/eAg
- 社区心理支持的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/075=lek
- 数字创作工具的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/abi=035
- 城市社区治理的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/Xxb=9EZ
- 社区法律科普的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9C%88%E5%AD%90?/277
- 全民阅读推广的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9C%88%E5%AD%90?/wdw
- 城市共享单车的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9C%88%E5%AD%90?/km6
- 乡村公共服务的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9C%88%E5%AD%90?/525=zgl
- 居家适老化改造的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9C%88%E5%AD%90?/oly=103
- 全民健身活动的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E5%9C%88%E5%AD%90?/mm3=bGu
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/590
- 乡村公共服务的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/ckq
- 电子商务服务的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/rIF
- 便民服务地图的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/392=qjx
- 便民维修服务的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/ddi=578
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%89%8B%E8%AE%B0?/VCv=Hb9
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/646
- 家庭健康管理的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/ofs
- 人工智能科普的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/q9G
- 个人时间管理的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/844=wmr
- 城市基础设施的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/ilx=740
- 社区便民服务的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/gwv=WUe
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/386
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/ghk
- 科学健身方法的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/hO8
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/817=sjx
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/oun=050
- 乡村公共服务的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/YVe=Zm1
- 城市展览体验的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/718
- 城市适老服务的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/rco
- 社区防暑服务的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/G7G
- 机器学习入门的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/129=kgq
- 非遗体验活动的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/sby=483
- 数字学习资源的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/PPC=KdR
- 街区道路维护的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/343
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/usy
- 社区互助网络的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/lZq
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/436=xzi
- 全民健身活动的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/dzo=300
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E6%8A%A5?/Ivf=cbu
- 新能源出行的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2?/641
- 灵活就业交流的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2?/ixp
- 社区活动报名的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2?/GON
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2?/034=jka
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2?/rxn=272
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2?/tSJ=msW
- 邻里共享空间的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/088
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/icq
- 乡村公共阅读的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/xlp
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/129=jvn
- 街区小店体验的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/hfv=847
- 乡村文化活动的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/53X=o1V
- 社区故事采集的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/897
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/jzs
- 数字资源检索的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/LZz
- 社区垃圾分类的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/560=vpq
- 数字素养提升的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/evf=139
- 家庭安全提示的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/LQP=plW
- 公共服务预约的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/890
- 便民服务窗口的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/gyw
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/zfj
- 绿色校园实践的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/798=yvq
- 社会体育指导的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/xha=049
- 志愿服务平台的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/Dck=P4R
- 社区垃圾回收的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/935
- 小区停车协商的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/nzk
- 青少年科普实践的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/n5b
- 儿童户外活动的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/501=biu
- 人工智能科普的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/vua=166
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/nCn=5h6
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/004
- 创业经验分享中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/hnl
- 非遗体验活动的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/LLt
- 公共空间安全的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/551=orc
- 社区协商议事的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/luz=303
- 乡村教育资源的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%A6%9C%E5%8D%95?/bm2=Z5m
- 乡村生态观察的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/171
- 小区公共照明的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/xiw
- 社区儿童活动的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/7qD
- 数字政务体验的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/778=fut
- 城市应急科普的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/ylm=730
- 公共交通接驳的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/q4u=9ul
- 文化讲座服务的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9vl-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/832
- 家庭照护支持的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9vl-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/won
- 环境教育课程的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9vl-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/eNY
- 社区艺术活动的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9vl-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/024=nbp
- 城市雨天出行的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9vl-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/npx=139
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E4%B9%90%E5%BD%A9vl-welcome%E5%A4%A7%E5%8E%85_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/yM7=b0H
- 医院导诊服务的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/949
- 城市应急广播的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/cfm
- 志愿服务平台的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Pw0
- 社区协商议事的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/712=xrf
- 校园阅读活动的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ucx=452
- 绿色生活实践的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/gXK=Nfa
- 城市噪声观察的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/276
- 儿童户外活动的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/mgm
- 急救知识普及的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/G4j
- 家庭养老规划的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/359=rym
- 科学观察活动的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/tac=654
- 城市适老服务的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/9q5=tb6
- 城市人文观察的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E4%BA%BA%E7%89%A9?/353
- 社区生活指南的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E4%BA%BA%E7%89%A9?/fus
- 非遗体验活动的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E4%BA%BA%E7%89%A9?/KT5
- 城市文明出行的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E4%BA%BA%E7%89%A9?/399=hsb
- 公共空间安全的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E4%BA%BA%E7%89%A9?/wng=164
- 垃圾分类指导的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E4%BA%BA%E7%89%A9?/HyJ=21O
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/738
- 家庭科学教育的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/hph
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/uPu
- 城市适老服务的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/270=ztq
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/dje=051
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9vl-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/aKV=gxY
- 社区快递服务的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%BD%A9vl-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/401
- 邻里共享空间的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%BD%A9vl-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/kaa
- 公共文化活动中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%BD%A9vl-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/WbN
- 城市骑行环境的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%BD%A9vl-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/861=oor
- 食品安全科普的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%BD%A9vl-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/gpn=363
- 家庭节能设备的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%BD%A9vl-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/F29=CTV
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9app_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/654
- 市民热线服务的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9app_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/kjb
- 市民意见收集的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9app_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/QxG
- 青少年编程学习的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9app_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/232=ucj
- 公共空间休憩的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9app_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/mbh=552
- 文化场馆预约的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E6%96%B9app_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/rjg=6e8
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/319
- 数据分析入门的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/qyd
- 公园亲子设施的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/S53
- 运动安全知识的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/802=rpn
- 休闲运动入门的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/tbw=483
- 城市雨天出行的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%BD%A9vl-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/0i0=W17

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
