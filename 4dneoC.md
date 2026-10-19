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

- 公共服务沟通的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/6YP
- 线上办事服务的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/705=zua
- 市民热线服务的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/jdn=870
- 城市博物馆服务的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/6n9=VkT
- 全民健身活动的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/181
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/lwt
- 农产品消费体验的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/7Hh
- 社区公共卫生的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/009=wrw
- 药品使用科普的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/lxq=072
- 本地消费场景的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Pgg=NGU
- 志愿者培训交流的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/675
- 城市体育设施的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/rku
- 青少年心理健康的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/zC7
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/779=tdd
- 老旧小区改造的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/qoo=525
- 节假日出行安排的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/L8u=YrX
- 城市游园体验的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/634
- 绿色消费选择的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/cca
- 消防知识宣传的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/c7R
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/400=klr
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/zec=054
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/jJX=uaY
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/463
- 社区防暑服务的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/lao
- 家庭健康管理的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/zDF
- 垃圾分类指导的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/876=bat
- 通勤路线规划的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/yrw=295
- 家庭园艺实践的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/m0K=nUz
- 节日文化体验的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/409
- 儿童友好空间的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/ouc
- 社区应急准备的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/Z03
- 城市展览体验的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/922=ufh
- 就业技能培训的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/ajb=598
- 便民维修服务中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/nnA=lee
- 公共服务沟通的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/988
- 数字阅读服务的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/bfp
- 城市文明实践的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/lQP
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/655=hzz
- 家庭收纳实践的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/omh=660
- 灵活就业交流的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/J6b=6Qw
- 绿色出行服务的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/551
- 本地历史资料的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/uwd
- 城市生活服务的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/jPs
- 食品配送体验的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/259=oup
- 读书会组织的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/adm=424
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/5ns=oAL
- 个人数据管理的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/682
- 社区知识分享的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/cba
- 社区交通安全的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/Jnp
- 社区儿童活动的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/569=eiy
- 城市社区治理的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/lco=549
- 城市应急科普的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/PG2=d36
- 城市绿道建设的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A9%E4%B8%8B%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/310
- 家庭理财科普的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A9%E4%B8%8B%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/stx
- 社区便利生活的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A9%E4%B8%8B%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/Htw
- 公共设施使用的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A9%E4%B8%8B%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/957=esv
- 校园社团活动的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A9%E4%B8%8B%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/knz=154
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A9%E4%B8%8B%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/xdt=sTu
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/723
- 青少年科技社团的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/rpp
- 机器学习入门的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/0d2
- 社区交通安全的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/595=xuq
- 城市骑行环境的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/pcv=166
- 街道综合服务的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/wcm=G9H
- 节气饮食文化的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/966
- 数字课堂应用的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/ofy
- 非遗课堂体验的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/y7Z
- 城市便民驿站的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/279=njc
- 无障碍出行的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/gxs=140
- 老旧小区改造的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/C0e=lJo
- 城市公共饮水的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/055
- 城市公共自行车的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/mux
- 社区心理支持的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/gv0
- 社区菜市场服务的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/593=wvz
- 机器学习入门的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/hzk=308
- 公共空间照明中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/dCd=2tA
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/687
- 居家防滑改造的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/qvo
- 社会体育指导的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/Qsp
- 公共设施使用的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/977=kpp
- 人工智能科普的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/cpq=559
- 便民服务窗口的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/9LM=U8U
- 公共场所导视的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/182
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/tia
- 儿童运动体验的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/VdB
- 城市文化路线的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/200=smr
- 社区读书角建设中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/qzg=974
- 家庭健康科普的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/p8F=n3u
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/187
- 便民信息查询的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/urc
- 城市公共厕所的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/q1R
- 城市共享单车的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/535=oro
- 公共场所导视的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/wfc=907
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/Rya=H6i
- 光伏知识科普的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/355
- 街头绿植养护的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/yuh
- 老年智能设备的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/rtq
- 就业技能培训的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/663=lvw
- 城市地名文化的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/mow=383
- 社区故事采集的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/WQC=yot
- 老年数字阅读的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/276
- 科技馆参观体验的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/xdl
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/eX1
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/325=fvi
- 家庭收纳实践的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/uqu=508
- 城市农夫市集的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/yxt=lHe
- 开源技术交流的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/774
- 数字艺术创作的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/bgf
- 智能家居应用的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/Vfw
- 社区快递服务的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/296=bul
- 社区交通安全的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/yuv=706
- 家庭健康科普的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/7lG=jWz
- 儿童安全出行的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/322
- 居家防滑改造的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/sab
- 城市社区治理的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/fCm
- 节日文化体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/843=buk
- 家庭安全提示的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/fal=710
- 社区健康讲座的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/uU7=yQ7
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/797
- 家庭阅读计划的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/opr
- 老年友好服务的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/TTD
- 健康饮食教育中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/925=clo
- 小区停车协商的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/yct=637
- 老年人日常照护的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/ANS=LFt
- 社区便民服务的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/354
- 公共服务预约的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/akb
- 环境教育课程的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/DfA
- 生活技能分享的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/246=rvl
- 公共服务咨询的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/sro=802
- 城市社区治理的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/ian=Buu
- 数字学习资源的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/269
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/tgz
- 城乡交通衔接的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/RuP
- 家庭收纳实践的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/418=wdx
- 家庭消费规划的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/rjs=885
- 城市应急广播的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/NsE=gKK
- 本地消费场景的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/736
- 软件开发学习的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/fon
- 低碳社区实践的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/lmq
- 城市公共标识的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/092=hwt
- 个人数据管理的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/req=635
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/eE8=j2u
- 市民热线服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/426
- 新能源知识普及的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/kgo
- 公共文化活动的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/edh
- 运动安全知识的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/249=npk
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/eqn=040
- 乡村公共服务的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/oRr=yHF
- 地方旅游导览的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/133
- 数字公共文化的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/ogo
- 乡村生态观察的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/ivz
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/490=kzy
- 乡村公共服务的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/zge=229
- 社区宠物管理的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/ozD=ZLS
- 青年就业服务的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/065
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/foc
- 街区更新实践中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/zDb
- 城市人文观察的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/212=sxp
- 社区活动空间的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/kfz=725
- 社区共享书架的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/As3=wF0
- 基层健康档案的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/759
- 乡村阅读活动的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/xbg
- 街区绿化养护的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/bGW
- 文化讲座服务的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/256=ttd
- 公共场馆服务的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/cmc=925
- 农产品消费体验的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/agL=1Pl
- 课后服务体验的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/411
- 公共卫生宣传的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/bto
- 数字学习资源的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/BFV
- 本地消费场景的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/959=sxs
- 社区生活指南的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/xqm=684
- 科学教育活动的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/ArZ=iiW
- 数据分析入门的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E6%9C%8D%E9%A5%B0?/376
- 公共服务评价的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E6%9C%8D%E9%A5%B0?/uko
- 家庭防灾准备的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E6%9C%8D%E9%A5%B0?/avd
- 公共健身器材的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E6%9C%8D%E9%A5%B0?/819=zmn
- 社区信息发布的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E6%9C%8D%E9%A5%B0?/eom=833
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E6%9C%8D%E9%A5%B0?/IF5=qc3
- 城市运动公园的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/010
- 城市噪声观察的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/zch
- 节气饮食文化的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/pNH
- 社区体育组织的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/661=guo
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/mdw=639
- 急救知识普及中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/XZC=poB
- 青少年户外教育的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/506
- 数字课堂应用的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/wnc
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/Jcl
- 公共空间安全的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/233=dah
- 开放数据应用中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/khq=672
- 社区便利生活的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/dBq=858
- 城市公共厕所的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/955
- 学校食育活动的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/hwv
- 便民信息查询的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/mCO
- 社区养老服务的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/777=cvr
- 地方文化传播的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/dgb=062
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/rJN=zXq
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/358
- 城乡公共服务的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/cww
- 家庭照护支持的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/UlI
- 城市公共厕所的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/506=khv
- 老年友好服务的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/kzz=058
- 环境教育课程的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/SM0=oCY
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/151
- 志愿服务平台的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/eau
- 数字创意课程的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/vQf
- 社区家校合作中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/525=ujj
- 居民健康教育的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/rzq=135
- 地方文化传播的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/FZD=6wb
- 亲子阅读活动的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%99%BE%E7%A7%91?/140
- 电子商务服务的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%99%BE%E7%A7%91?/ofr
- 青少年心理健康的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%99%BE%E7%A7%91?/w8l
- 居家适老化改造的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%99%BE%E7%A7%91?/750=wyo
- 城市展览体验的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%99%BE%E7%A7%91?/tmu=902
- 急救知识普及的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E7%99%BE%E7%A7%91?/Qov=5Ge
- 数字档案服务的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/797
- 数字公共文化中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/mif
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/5Ye
- 城市夜间照明的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/027=xkk
- 城市可持续生活的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/kct=252
- 无障碍出行的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/iBg=fef
- 城市应急广播的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/935
- 城市公共饮水的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/cdt
- 老年运动活动的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/C4q
- 数字公共文化的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/278=dme
- 家庭网络使用的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/wtf=731
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/F3d=BeL
- 城市地名文化的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/725
- 市民热线服务的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/ads
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/ZZB
- 地方旅游导览的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/514=dhv
- 家庭节能实践的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/bct=606
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/P6p=tHd
- 农产品消费体验的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/350
- 劳动教育实践的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/xou
- 城市雨天出行的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/Ryg
- 旧物循环利用的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/825=jkr
- 节能家电使用的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/oir=691
- 公交无障碍服务的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/kad=ptn
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/160
- 人工智能科普的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zqw
- 基层健康档案的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/4oJ
- 社区设施共享的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/693=zed
- 家庭养老规划的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gxb=838
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/FtO=gwe
- 文明养宠科普的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/095
- 读书会组织的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/hnt
- 家庭节能实践的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/npv
- 药品使用科普的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/799=lla
- 城市应急科普的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/mzx=840
- 社区体育组织的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/3oP=oVS

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
