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

- 网络安全教育的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/0NS
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/130=tlb
- 公共场所导视的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/hqx=062
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/5HG=hAK
- 城市骑行环境的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%9E%E5%BD%95?/054
- 地方民俗记录的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%9E%E5%BD%95?/fra
- 社区生活指南的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%9E%E5%BD%95?/Z3G
- 数字素养提升的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%9E%E5%BD%95?/971=slm
- 居家适老化改造的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%9E%E5%BD%95?/gyv=260
- 社区垃圾分类的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%9E%E5%BD%95?/hrb=6Ma
- 新能源知识普及的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/597
- 城市公共艺术的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/daw
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/GKX
- 城市建设科普的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/363=oup
- 公共健身器材的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/lio=295
- 家庭运动计划的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/LtY=1wE
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/722
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/bnk
- 社区活动空间的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/kIO
- 在线教育体验的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/964=nsd
- 基层健康服务的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/gpd=561
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/DTj=YzG
- 家庭园艺实践的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/637
- 家庭食品保存的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/qbw
- 街区道路维护的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/3IP
- 乡村公共阅读的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/067=ncu
- 开放数据应用的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/hrq=498
- 公共场所导视的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/lPm=F1f
- 校园社团活动的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/743
- 便民服务地图的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/eai
- 老旧小区改造的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/ETv
- 急救知识普及的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/693=cun
- 公共设施维护的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/kng=493
- 城市住房服务的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/EdV=rCw
- 地方戏曲体验的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/156
- 远程协作工具的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/gol
- 志愿服务平台的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/3OE
- 药品使用科普的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/668=ytg
- 老年人出行服务的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/vkb=181
- 社区设施共享的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/ulg=SUK
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/162
- 乡村产业科普的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/oeg
- 家庭环保行动的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/EN8
- 公园休闲体验的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/649=ezh
- 城市树木认养的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/dpu=262
- 骑行路线规划的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/IsS=PbD
- 智慧城市体验的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/658
- 科学运动指导的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/jbr
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/2Cr
- 社区文化节活动的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/661=rpd
- 个人时间管理的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/amx=270
- 传统手工艺体验的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/j7w=l39
- 老年人文化生活的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/269
- 生成式工具使用的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/pup
- 公共图书馆服务的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/TCa
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/446=jjb
- 农产品品牌传播的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/xrs=865
- 家庭环保行动的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/lMB=9Dq
- 社区交通安全的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/094
- 城市骑行环境的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/dzp
- 生活垃圾减量的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/7oV
- 便民维修服务的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/462=ecx
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/jib=494
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/moY=Yw1
- 智能家居应用的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/274
- 社区协商议事的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/otw
- 家庭理财科普的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/xtV
- 乡村公共阅读的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/721=exc
- 创业经验分享的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/ubv=639
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/69P=lPz
- 绿色生活实践的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/894
- 城市适老服务的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/zki
- 公共服务评价的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/JD0
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/727=loz
- 社区读书角建设的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/alf=692
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/Xtx=wYC
- 通勤路线规划的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/359
- 公共场所导视的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/ujs
- 城市公共空间的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/CtB
- 科学运动指导的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/438=gnj
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/ajj=775
- 老年友好服务的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/K0P=N4z
- 科学信息获取的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/883
- 青少年户外教育的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/nln
- 邻里互助活动的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/N7L
- 邻里共享空间的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/440=pki
- 社区生活指南的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/hvs=555
- 家庭急救准备的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/I4c=SZP
- 城市文明实践的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/727
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/auy
- 运动安全知识的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/XOW
- 社区志愿服务的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/399=mgt
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/vvm=077
- 城乡公共服务的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/rLh=Trr
- 人工智能科普的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/371
- 社区法律科普的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/tnp
- 城市便民驿站的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/swg
- 公共空间安全的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/903=usu
- 乡村电商实践的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/naq=402
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/MGo=j6m
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/850
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/jkl
- 农贸市场环境的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/dLm
- 城市休闲步道的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/471=cqd
- 老年数字阅读的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/gni=251
- 健康饮水科普的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/GsB=Nhi
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/475
- 乡村教育资源的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/bzn
- 居民健康教育的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/yl5
- 家庭网络使用的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/012=vir
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/oyt=757
- 城乡交流活动的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/UvQ=uFA
- 本地旅行体验的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/716
- 社区学习活动的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/pwc
- 数字政务体验的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/kUr
- 公共服务沟通的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/273=thh
- 儿童安全出行的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/ebj=049
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/tfM=rl2
- 社区活动策划的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/543
- 读书会组织的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/jal
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/1vB
- 图书馆数字服务的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/282=buk
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/ctk=234
- 社区志愿服务的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/c4V=nHs
- 社区便民服务的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/717
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/oyn
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/j1e
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/677=jsu
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/mgc=539
- 公共交通接驳的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/WZO=hW1
- 机器学习入门的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/909
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/khi
- 非遗体验活动的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/eC3
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/580=bhw
- 乡村电商实践的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/gjq=711
- 社区活动报名的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/1Lq=hfV
- 城市体育设施的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/763
- 公共空间照明的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/kak
- 社区花园共建的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/cnO
- 城市步行环境的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/595=epg
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/inz=360
- 社区慢性病防控的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/xdT=ayk
- 科普展览体验的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/056
- 家庭园艺实践的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/iak
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/RZ1
- 本地历史资料的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/165=upo
- 基层健康档案的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/cuy=938
- 便民维修服务的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/hwJ=K2Y
- 老年人出行服务的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/909
- 安全出行教育的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/wnp
- 公交无障碍服务的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/d5H
- 创业经验分享的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/446=iga
- 健康饮食教育的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/bsj=534
- 城市公共标识的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/eBH=SWv
- 儿童安全出行的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/406
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/tpp
- 乡村生活观察的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/Ung
- 居家适老化改造的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/373=iqr
- 公共场所导视的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/svy=871
- 社区休闲设施的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/z3s=COr
- 数字政务体验的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/360
- 社区防暑服务的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/eda
- 农村环境治理的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/GM5
- 公园休闲体验的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/148=hmz
- 老年友好服务的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/nsk=922
- 公共空间导览的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/Qdi=kEM
- 社区停车服务的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/230
- 休闲运动入门的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/blv
- 家庭教育交流的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/H0g
- 文明养宠科普的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/991=dqu
- 街区道路维护的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/wwg=077
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/gWp=urx
- 邻里共享空间的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8F%B7%E5%A4%96?/553
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8F%B7%E5%A4%96?/vlq
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8F%B7%E5%A4%96?/zY4
- 城乡交流活动的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8F%B7%E5%A4%96?/829=zxp
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8F%B7%E5%A4%96?/kvy=510
- 公共服务预约的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8F%B7%E5%A4%96?/m7M=rEH
- 城市地名文化的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/090
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/gcn
- 家庭园艺实践的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zC3
- 公园亲子设施的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/533=bzd
- 城市共享单车的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hdv=839
- 城市地名文化的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xgg=MYb
- 校园节能行动的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/876
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/scg
- 家庭健康科普的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/cIL
- 数字政务体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/262=qwr
- 社区知识分享的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/wak=574
- 口袋公园建设的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/gpY=14k
- 新能源知识普及的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/514
- 城市微更新实践的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/dld
- 城市博物馆活动的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/EIu
- 急救知识普及的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/084=jmm
- 健康饮水科普的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/gmc=402
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/jqx=e9T
- 本地消费场景中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/600
- 个人信息保护的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/olr
- 网络信息辨识的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/9Cv
- 家庭运动计划的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/387=sjn
- 公共服务预约的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/evn=011
- 本地消费场景的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/zI4=iAY
- 城乡公共服务的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/621
- 智慧停车服务的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/gll
- 农贸市场环境的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/r6a
- 城市公共艺术的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/392=tki
- 智能手机助老中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/mhd=650
- 社区设施共享的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%8E%8C%E4%B8%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/k5Q=2KH
- 乡村文化空间的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/243
- 社区体育组织的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/vke
- 家庭收纳实践的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/pP7
- 社区快递服务的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/703=wvj
- 小微企业服务的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/shy=007
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/PAU=pNV
- 社区防暑服务的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/998
- 新能源出行的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/ehn
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/wpD
- 城市博物馆活动的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/130=nck
- 健康步道使用中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/mbj=424
- 人工智能科普的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/WoX=Xl1
- 社区垃圾回收的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/772
- 地方戏曲体验的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/ogk
- 社区老年食堂的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/WiA
- 青少年科普实践的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/498=xho
- 家庭节能实践的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/syv=644
- 老年友好服务的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/w9x=Ic3
- 科学健身方法的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/911
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/eik
- 开放式学习空间的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/0E4
- 数字创作工具的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/966=xoy
- 社区邻里服务的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/uhn=081
- 城市地名文化的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/Kkh=yk9
- 数字阅读服务的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/169
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/vpj
- 药品使用科普的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/r0t
- 生活垃圾减量的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/151=cwh
- 科学信息获取的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/osn=686
- 社区活动空间的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/sZW=8DC
- 社区垃圾回收的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/231
- 个人数据管理的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/imb
- 生活垃圾回收的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/Ow3
- 读书会组织的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/341=bqd
- 节能生活方式的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/ocy=285
- 社区教育资源的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E5%AE%89%E9%98%B2?/AZS=FDs
- 消防知识宣传的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/753
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/gmy
- 科学观察活动的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/F28
- 社区家政服务的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/185=vnj
- 小微企业服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/fox=488
- 城市噪声观察的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%8E%8C%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/4Bp=rwc

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
