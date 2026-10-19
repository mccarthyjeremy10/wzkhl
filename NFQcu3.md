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

- 城市夜间生活的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/394
- 老年人出行服务的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/tkj
- 城市雨天出行的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/CQC
- 图书馆数字服务的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/006=dgf
- 地方文化传播的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/eva=425
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/Z83=jlN
- 数据分析入门的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/084
- 社区老年食堂的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/fyw
- 老年学习活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/Vbc
- 青少年户外教育的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/193=zxp
- 便民服务地图的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/ibf=675
- 社区交通安全的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E4%B8%93%E6%A0%8F?/WAX=KRn
- 日常摄影记录的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/513
- 日常摄影记录的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/rwu
- 节能生活方式的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/8VM
- 老年人出行服务的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/337=adv
- 绿色办公实践的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/qzj=725
- 城市噪声观察的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/aHU=qmB
- 街区绿化养护的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/529
- 儿童阅读角的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/olg
- 数字便民地图的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/NJH
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/923=fje
- 社区文化传播的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/noe=252
- 城市公共艺术的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/Un3=KXZ
- 数字创意课程的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/481
- 儿童友好空间的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/qbi
- 信息无障碍体验的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/J1N
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/722=sai
- 城市公共饮水的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/hic=886
- 网络安全教育的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/nmG=QtB
- 城市运动公园的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/392
- 街区更新实践的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/cfs
- 公共设施维护的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/93a
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/115=vxj
- 家庭安全提示的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/hjv=623
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/cy1=Vin
- 智能手机助老的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/800
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/glj
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/ef2
- 个人数据管理的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/566=byb
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/hyo=346
- 城市公共座椅的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/mfy=QuB
- 家庭阅读计划的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/358
- 节日文化体验的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/sfj
- 城市公共标识的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/sT9
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/610=pvc
- 社区家校合作的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/nys=625
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/gKY=rss
- 儿童户外活动的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/038
- 绿色消费选择的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/azg
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/N7I
- 老旧小区改造的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/092=yyj
- 家庭网络使用的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/lsk=870
- 骑行路线规划的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/ity=yBQ
- 文化讲座服务的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/946
- 公共空间安全的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/zed
- 日常摄影记录的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/uJO
- 城市夜间生活的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/127=esv
- 社区活动策划的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/qie=479
- 地方旅游导览的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/TYe=ryQ
- 青年职业探索中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/763
- 农产品消费体验的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/usa
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/eIg
- 公共文化活动中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/952=hrq
- 社区活动空间的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/ekd=999
- 学校食育活动的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/Auv=WtA
- 地方旅游导览的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/623
- 社区法律科普的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/qrz
- 光伏知识科普的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/xDq
- 社区托育服务的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/538=ztt
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/moe=097
- 本地旅行体验的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/fuc=bAN
- 科技馆参观体验的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/983
- 社区运动空间的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/mgm
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/vRR
- 骑行路线规划的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/010=fyc
- 城市噪声观察的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/dwc=919
- 安全出行教育的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/olc=7Xg
- 机器学习入门的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/364
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/was
- 学校食育活动的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/5jt
- 城市可持续生活的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/077=qet
- 乡村生活观察的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/dyb=792
- 城市绿道建设中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/yun=3tc
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/736
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/ljm
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/P7E
- 公共空间安全的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/216=oyy
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/lce=935
- 数字政务体验的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/KXZ=aBN
- 职业技能学习中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/120
- 城市步行友好的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/rqt
- 社区故事采集的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/CBk
- 本地消费场景的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/599=dja
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/jwf=101
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/NuS=T3b
- 社区儿童活动的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/769
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/ztd
- 家庭环保行动的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/ho3
- 绿色办公实践的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/693=rkz
- 城市应急科普的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/pjv=521
- 家庭食品保存的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/Su8=8aS
- 城市休闲步道的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/024
- 家庭阅读计划的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/xif
- 儿童安全出行中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/Ht8
- 小微企业服务的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/213=bej
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/tfn=307
- 终身学习资源的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/z8J=HtT
- 数字公共文化的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/270
- 城市绿道建设的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/pcn
- 新能源出行的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/TW9
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/415=joy
- 社区垃圾回收的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/gjt=828
- 邻里互助活动的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/dD1=kpH
- 科学观察活动的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/647
- 城市公共标识的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/gnm
- 运动安全知识的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/ueo
- 城市适老服务的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/196=ubf
- 城市体育设施的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/xqk=879
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/sBE=luq
- 骑行路线规划的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/142
- 智慧城市体验的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/ddp
- 智能手机助老的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/0hV
- 节能家电使用的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/194=vbw
- 乡村文化空间的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/uno=740
- 家庭食品保存的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/sgU=5lQ
- 家庭节能实践的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/830
- 城乡公共服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/vzb
- 科普展览体验的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/Q5K
- 青年职业探索的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/615=plp
- 社区知识分享的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/dob=203
- 家庭环保习惯的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/gi9=c4q
- 非遗课堂体验的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/986
- 校园阅读活动的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/xcm
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/GA4
- 社区安全巡查的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/951=lch
- 生活技能分享的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/egf=015
- 家庭网络使用的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/G4u=H4w
- 科学信息获取的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/737
- 儿童运动体验的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/qol
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/R1U
- 乡村生态旅游的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/317=xvs
- 居民健康教育的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/kqn=642
- 数字学习资源的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/xjT=Ufk
- 乡村教育资源的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/391
- 公交无障碍服务的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/bwq
- 数字课堂应用的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/T0h
- 城市农夫市集的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/975=ykj
- 农贸市场环境的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/qnu=412
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/j9D=pyO
- 家庭运动计划的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/381
- 本地历史资料的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/hwe
- 城市休闲步道的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/2Q1
- 城市文化路线的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/834=wbi
- 人工智能科普的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/rar=449
- 社区艺术活动的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/qlE=38n
- 本地旅行体验的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/952
- 公园亲子设施的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/rhz
- 人工智能科普的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/jdM
- 本地历史资料的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/235=qpg
- 口袋公园建设的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/nza=855
- 全民健身活动的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/2j1=bfp
- 社区便利生活的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/125
- 社区协商议事的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/fql
- 社区活动策划的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/29u
- 青少年编程学习的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/216=kkn
- 社区家校合作的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/lts=136
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/nLx=MSr
- 家庭用电安全中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/325
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/osd
- 基层服务创新的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/94E
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/582=wdo
- 社区文化节活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/utz=639
- 食品配送体验的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/xh8=sVY
- 旧物循环利用的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/921
- 社区体育组织的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/zkc
- 城市公共座椅的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/tqW
- 公交站点体验的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/922=odw
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/gsn=785
- 全民健身活动的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/f9c=6xd
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/331
- 电动汽车充电的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/jox
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/Rym
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/254=vep
- 社区活动策划的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/ezh=775
- 物业服务沟通的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/YKs=Pj8
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/550
- 家庭食品保存的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/pqa
- 社区文化传播的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/73Z
- 社区活动策划的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/433=qpb
- 社区慢性病防控的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/xoi=881
- 社区环保活动的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/Ugj=YGG
- 市民热线服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/007
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/kqj
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/1GE
- 消防知识宣传的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/877=gtn
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/abh=344
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/vaA=Hsc
- 智能家居应用的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/339
- 城市空气科普的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/tgy
- 健康步道使用的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/S37
- 公共服务咨询的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/666=ocj
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/rpl=953
- 数字创意课程的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/H7S=HGf
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-APP_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/224
- 本地消费场景的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-APP_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/qbf
- 儿童运动体验的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-APP_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/5cY
- 周末休闲规划的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-APP_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/704=ieb
- 公共服务沟通的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-APP_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/goe=990
- 城乡交流活动的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-APP_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/KnJ=wW0
- 机器人科普活动的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/035
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/hev
- 家庭饮食安排的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/QcC
- 智慧停车服务的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/507=vln
- 家庭健康科普的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/eqj=322
- 环境教育课程的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E8%B5%A2%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/D11=rGK
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/685
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/xkj
- 消防知识宣传的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/LnH
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/907=fal
- 低碳社区实践的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/mpv=143
- 城市游园体验的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/zUu=Ne9
- 数据分析入门的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95_360%E5%AE%B6%E7%94%B5?/238
- 家庭消费规划的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95_360%E5%AE%B6%E7%94%B5?/aec
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95_360%E5%AE%B6%E7%94%B5?/NMH
- 便民信息查询的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95_360%E5%AE%B6%E7%94%B5?/891=nen
- 科学教育活动的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95_360%E5%AE%B6%E7%94%B5?/pyf=210
- 租房信息服务的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E7%99%BB%E5%BD%95_360%E5%AE%B6%E7%94%B5?/aw9=IMq
- 城乡公共服务的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/025
- 乡村生态旅游的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/tjz
- 农村环境治理的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/pSs
- 城市适老服务的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/428=mir
- 公共服务指南的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/lcw=683
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/tOb=PlX
- 学校体育活动的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E7%A7%81%E5%8B%9F?/082
- 安全出行教育的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E7%A7%81%E5%8B%9F?/lrp
- 老年人文化生活的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E7%A7%81%E5%8B%9F?/iC6
- 青少年户外教育的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E7%A7%81%E5%8B%9F?/834=nad
- 个人信息保护的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E7%A7%81%E5%8B%9F?/wzb=576
- 社区心理支持的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E7%A7%81%E5%8B%9F?/HjA=fhj
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/507
- 开源技术交流的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/icv
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/vRZ
- 社区便利生活的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/530=jjh
- 文化讲座服务的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/sdb=043
- 城市公共艺术中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/WZI=my4
- 社区花园共建的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/824
- 家庭理财科普的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xyo
- 社区托育服务的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/6Nd
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E8%B5%A2%E5%AE%B6-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/665=wkj

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
