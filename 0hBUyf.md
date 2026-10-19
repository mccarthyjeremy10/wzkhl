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

- 社会体育指导的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E8%AE%A1%E5%88%923%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/woq=900
- 乡村电商实践的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E8%AE%A1%E5%88%923%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%B8%E5%95%86?/MU0=3ZQ
- 公共场馆服务的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/211
- 基层健康档案的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/nvo
- 公共空间安全的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/iR0
- 数字资源检索的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/082=nay
- 机器学习入门的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/bql=552
- 社区志愿服务的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/mxp=GM4
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E8%B0%B1%E5%90%97%E9%9D%A0%E8%B0%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/003
- 城市人文观察的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E8%B0%B1%E5%90%97%E9%9D%A0%E8%B0%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/vmg
- 农村环境治理的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E8%B0%B1%E5%90%97%E9%9D%A0%E8%B0%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/kTW
- 数字素养提升的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E8%B0%B1%E5%90%97%E9%9D%A0%E8%B0%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/040=jut
- 家庭饮食安排的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E8%B0%B1%E5%90%97%E9%9D%A0%E8%B0%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/rvz=372
- 城市公共空间的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%9D%A0%E8%B0%B1%E5%90%97%E9%9D%A0%E8%B0%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/Ean=TTA
- 乡村生活观察的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/831
- 非遗课堂体验的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/jgu
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/WQI
- 地方美食文化的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/231=roy
- 生活垃圾减量的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/uby=153
- 城市树木认养的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/Aq0=WRS
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/601
- 生活服务数字化的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/ybp
- 本地消费场景的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/82f
- 社区设施共享的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/452=eny
- 儿童户外活动的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/bxx=402
- 数字设备回收的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/SlQ=ses
- 基层服务创新的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/358
- 应急物资管理的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/ate
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/kyT
- 家庭安全提示的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/262=hrg
- 城市骑行环境的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/uwn=990
- 社区运动空间的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E6%97%A7%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/HBM=tiG
- 亲子科普活动的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%98%8E%E4%BA%86%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/403
- 网络安全教育的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%98%8E%E4%BA%86%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/mib
- 城市休闲步道的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%98%8E%E4%BA%86%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/Fh5
- 邻里互助活动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%98%8E%E4%BA%86%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/174=yfw
- 城市慢跑路线的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%98%8E%E4%BA%86%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/hbu=003
- 乡村文化空间的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%98%8E%E4%BA%86%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/AFM=LOc
- 周末休闲规划的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/078
- 文化场馆预约的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/bpg
- 老年学习活动的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/aL8
- 日常摄影记录的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/102=tcz
- 电子商务服务的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/cpc=319
- 社区快递服务的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/6Ss=E7r
- 乡村生态观察的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/387
- 科学观察活动的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/zyr
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/GyV
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/538=vrp
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/jec=514
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/1BN=Bfs
- 志愿服务平台的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/327
- 绿色消费选择的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/fxp
- 节能生活方式的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/0yT
- 城市体育设施的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/065=ajs
- 社区安全巡查的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/qpe=442
- 社区公共卫生的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/Nqo=UJs
- 乡村生活观察中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/284
- 社区花园共建的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/sey
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/vPl
- 乡村文化空间的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/278=jwn
- 药品使用科普的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/zbr=840
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/Cov=n3f
- 家庭科学教育的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%89%E5%85%A8%E5%90%97_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/259
- 健康饮食教育的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%89%E5%85%A8%E5%90%97_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/enc
- 乡村生活观察的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%89%E5%85%A8%E5%90%97_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/y9y
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%89%E5%85%A8%E5%90%97_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/916=uet
- 公园休闲体验的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%89%E5%85%A8%E5%90%97_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/tta=786
- 节能生活方式的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%89%E5%85%A8%E5%90%97_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/9VI=7x4
- 休闲运动入门的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/131
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/dld
- 社区手工活动的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/leI
- 家庭网络使用的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/943=fla
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/hyk=346
- 社会体育指导的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/hnJ=nRt
- 本地消费场景的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E7%A8%B3%E5%90%97_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/204
- 日常摄影记录的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E7%A8%B3%E5%90%97_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/dhi
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E7%A8%B3%E5%90%97_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/kRP
- 基层医疗预约的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E7%A8%B3%E5%90%97_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/869=qyt
- 城市夜间生活的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E7%A8%B3%E5%90%97_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/vvh=352
- 城市生活记录的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E7%A8%B3%E5%90%97_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/0yv=QeY
- 家庭安全提示的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/295
- 学校体育活动的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/blr
- 科学信息获取的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/Eyl
- 家庭环保习惯的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/452=xzh
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/mdj=179
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/U6O=iJ5
- 社区艺术活动的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%AE%A1%E5%88%92qq%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/249
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%AE%A1%E5%88%92qq%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/bvg
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%AE%A1%E5%88%92qq%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/URO
- 租房信息服务的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%AE%A1%E5%88%92qq%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/290=uov
- 运动安全知识的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%AE%A1%E5%88%92qq%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/asr=364
- 口袋公园建设的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%AE%A1%E5%88%92qq%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/LEO=1qS
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/093
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/bsh
- 老年人日常照护的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/scH
- 城市地名文化的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/587=vjm
- 公园无障碍服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/fbw=129
- 便民服务地图的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/661=ZLv
- 软件开发学习的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/273
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/ezo
- 社区垃圾回收的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/Icj
- 科普展览体验的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/680=fsz
- 城市公共艺术的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/vey=316
- 社区活动策划的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/4UP=sap
- 社区活动策划的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/989
- 家庭志愿活动的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/wps
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/Q8T
- 社区法律科普的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/821=hlf
- 无障碍出行的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/kic=092
- 应急物资管理的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/prx=NvA
- 城市适老服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/590
- 家庭教育交流的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/qlk
- 劳动教育实践的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/AEx
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/411=irs
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/uno=527
- 城市农夫市集的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/9YX=MBp
- 亲子阅读活动的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_79%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/442
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_79%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/quv
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_79%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/VP8
- 数字创意课程的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_79%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/203=utk
- 小微企业服务的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_79%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/asy=881
- 光伏知识科普的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_79%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/8BD=Phc
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/995
- 文明养宠科普的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/htr
- 数字政务体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/k8w
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/819=gmn
- 生成式工具使用的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/csk=636
- 城市建设科普的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/1CC=Us8
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/988
- 地方民俗记录的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/dqd
- 家庭阅读计划的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/jRJ
- 绿色出行服务的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/286=rnc
- 家庭节能设备的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/myk=594
- 机器人科普活动从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/lr3=1ig
- 小微企业服务的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/668
- 社会体育指导的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/pzf
- 城乡交流活动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/FGz
- 乡村公共文化的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/714=dtw
- 绿色消费选择的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/rlf=380
- 老年人文化生活的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/AuX=WiR
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/759
- 传统节日科普的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/rca
- 农产品消费体验的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/O6E
- 青少年心理健康的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/601=fpz
- 乡村公共服务的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/jdz=905
- 青少年户外教育的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/cHw=GHS
- 户外活动组织的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%28%E4%B8%8D%E7%94%A8%E7%99%BB%E5%BD%95%29_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/778
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%28%E4%B8%8D%E7%94%A8%E7%99%BB%E5%BD%95%29_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/idp
- 志愿者培训交流的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%28%E4%B8%8D%E7%94%A8%E7%99%BB%E5%BD%95%29_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/SGR
- 公共服务评价的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%28%E4%B8%8D%E7%94%A8%E7%99%BB%E5%BD%95%29_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/210=qrv
- 智慧停车服务的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%28%E4%B8%8D%E7%94%A8%E7%99%BB%E5%BD%95%29_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/fhm=959
- 数字支付体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%28%E4%B8%8D%E7%94%A8%E7%99%BB%E5%BD%95%29_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/QCR=EoC
- 科学健身方法的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92-%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/549
- 街区道路维护的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92-%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zqv
- 旧物循环利用的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92-%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Chz
- 城市树木认养的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92-%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/302=dds
- 户外活动组织的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92-%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/udi=599
- 志愿者培训交流的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%9C%A3%E8%AE%A1%E5%88%92-%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/MLu=cJs
- 健康信息获取的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E8%8B%B9%E6%9E%9Capp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/432
- 全民健身活动的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E8%8B%B9%E6%9E%9Capp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/ecl
- 青少年心理健康的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E8%8B%B9%E6%9E%9Capp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/Kx8
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E8%8B%B9%E6%9E%9Capp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/397=ywz
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E8%8B%B9%E6%9E%9Capp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/qqs=077
- 城市博物馆服务的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E8%8B%B9%E6%9E%9Capp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/aE9=FOt
- 社区手工活动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/897
- 运动安全知识的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/hky
- 城市公共标识的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/DCM
- 社区儿童活动的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/585=xic
- 城市人文观察的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/fnr=710
- 便民服务窗口的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/FVC=v8r
- 就业技能培训的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/937
- 绿色办公实践的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/nlf
- 公共设施使用的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/cOG
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/557=gov
- 运动安全知识的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/zho=486
- 城市人文观察的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/FNR=VLs
- 社区便利生活的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/963
- 城市步行环境的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/szo
- 绿色消费选择的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/XUx
- 城市文明出行的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/093=qhh
- 家庭环保习惯的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/dcn=021
- 健康饮食教育的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/psD=A1X
- 公共服务数字化的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%8E%8B%E6%AD%A3%E7%89%88%E5%9B%BE%E7%BD%91%E7%BB%9C_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/798
- 个人数据管理的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%8E%8B%E6%AD%A3%E7%89%88%E5%9B%BE%E7%BD%91%E7%BB%9C_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/hbo
- 城市公共自行车的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%8E%8B%E6%AD%A3%E7%89%88%E5%9B%BE%E7%BD%91%E7%BB%9C_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/Szo
- 社区庭院绿化的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%8E%8B%E6%AD%A3%E7%89%88%E5%9B%BE%E7%BD%91%E7%BB%9C_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/662=znh
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%8E%8B%E6%AD%A3%E7%89%88%E5%9B%BE%E7%BD%91%E7%BB%9C_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/tiw=578
- 市民热线服务的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%8E%8B%E6%AD%A3%E7%89%88%E5%9B%BE%E7%BD%91%E7%BB%9C_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/6V8=04m
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/691
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/idn
- 城市体育设施的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/aMP
- 课后服务体验的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/821=dts
- 社区花园共建的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/jqr=010
- 社区便民集市中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/Xss=orD
- 传统手工艺体验的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/769
- 儿童友好空间的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/zmc
- 城市公共空间的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/nq7
- 食品配送体验的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/115=ugc
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/dlk=733
- 社区商业活力的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/hDk=ygo
- 文化场馆预约的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%98%AF%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/992
- 城市可持续生活的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%98%AF%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/psd
- 新能源出行从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%98%AF%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/iYv
- 社区活动报名的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%98%AF%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/176=xdi
- 乡村生态观察的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%98%AF%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/nck=109
- 无障碍信息设计的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%98%AF%E9%AA%97%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/MrL=Az0
- 小微企业服务的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/478
- 社区健康讲座的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/tww
- 城市体育设施的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/lky
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/916=nhi
- 城市适老服务中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/yrw=126
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/YEw=ZQ1
- 社区协商议事的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/230
- 智能手机助老的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/rxn
- 社区互助网络的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/y66
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/866=cvr
- 智能家居应用的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/mxr=233
- 租房信息服务的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/2U5=sgV
- 城市博物馆服务的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/370
- 生活技能分享的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/hhs
- 生成式工具使用的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/9Dl
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/314=nel
- 数字课堂应用的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/pjr=379
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/YGm=cEl
- 小区停车协商的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8Bapp_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/751
- 城市生活服务的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8Bapp_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/gmi
- 街区更新实践的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8Bapp_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/GAU
- 数字生活课堂的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8Bapp_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/619=vxb
- 休闲运动入门的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8Bapp_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/upo=481
- 街区道路维护的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8Bapp_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/k2n=8ej
- 城市树木认养的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_360%E5%8D%9A%E5%AE%A2?/977
- 农业科普体验的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_360%E5%8D%9A%E5%AE%A2?/jgj
- 城市地名文化的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_360%E5%8D%9A%E5%AE%A2?/DLW
- 老年智能设备的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_360%E5%8D%9A%E5%AE%A2?/854=lzz
- 社区文化传播的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_360%E5%8D%9A%E5%AE%A2?/oxh=355
- 家庭网络使用的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_360%E5%8D%9A%E5%AE%A2?/SAV=UgC
- 节约用水实践的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%98%93%E9%80%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/532
- 光伏知识科普的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%98%93%E9%80%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/xlg
- 青少年科普实践的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%98%93%E9%80%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/2Le
- 社区协商议事的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%98%93%E9%80%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/050=bcq
- 数字便民地图的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%98%93%E9%80%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/qzt=786
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E6%98%93%E9%80%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/GHI=mv8
- 社区商业活力的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%9C%A3%E6%89%8B_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/470
- 数字公共文化的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%9C%A3%E6%89%8B_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/ubg
- 城市公共饮水的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%9C%A3%E6%89%8B_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/chW
- 社区便利生活的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%9C%A3%E6%89%8B_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/541=ifb
- 社区读书角建设的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%9C%A3%E6%89%8B_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/svp=133
- 无障碍出行的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%9C%A3%E6%89%8B_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/vzK=gkE
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%90%83%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8Bapp_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/501
- 地方文化传播的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%90%83%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8Bapp_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/snz

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
