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

- 青年志愿活动的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/145
- 城市文明实践的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/uys
- 城市便民驿站的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/nIZ
- 城市雨天出行中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/948=rgo
- 社区便民集市的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/gto=784
- 社区消防演练的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/a6u=lMY
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/448
- 城市绿道建设的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/quv
- 骑行路线规划的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/C8U
- 生活垃圾减量的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/483=alc
- 人工智能科普的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/jeq=209
- 基层服务创新的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/O0V=YWZ
- 数字政务体验的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/159
- 老年学习活动的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/cgo
- 线上阅读资源的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/XEA
- 城市休闲步道的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/721=ibo
- 乡村公共服务中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/icy=156
- 家庭理财科普的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E9%9D%A0%E8%B0%B1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/Lic=Kwa
- 社区应急准备的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%A5%BD%E6%AF%94%E8%BE%83%E6%AD%A3%E8%A7%84_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/261
- 传统节日科普的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%A5%BD%E6%AF%94%E8%BE%83%E6%AD%A3%E8%A7%84_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/dhb
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%A5%BD%E6%AF%94%E8%BE%83%E6%AD%A3%E8%A7%84_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/qqI
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%A5%BD%E6%AF%94%E8%BE%83%E6%AD%A3%E8%A7%84_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/924=hrh
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%A5%BD%E6%AF%94%E8%BE%83%E6%AD%A3%E8%A7%84_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/qor=319
- 基层医疗预约的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%A5%BD%E6%AF%94%E8%BE%83%E6%AD%A3%E8%A7%84_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/EwD=AAb
- 全民健身活动的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/188
- 城市文明实践的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/oty
- 社区运动空间的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/CEq
- 青年就业服务的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/339=oqy
- 公共场所导视的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/lqv=307
- 社区环保活动的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/F4a=lVY
- 社区环保活动的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/336
- 节能家电使用的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/opc
- 社会体育指导的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/3Bc
- 文化遗产保护科普的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/612=rmi
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/ykk=948
- 公共交通信息服务的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/g6e=O69
- 科普展览体验的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%8F%8C%E8%89%B2%E7%90%83_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/367
- 校园安全教育的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%8F%8C%E8%89%B2%E7%90%83_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/mbt
- 城市文明实践的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%8F%8C%E8%89%B2%E7%90%83_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/mIr
- 社区活动空间的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%8F%8C%E8%89%B2%E7%90%83_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/527=cwq
- 绿色校园实践的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%8F%8C%E8%89%B2%E7%90%83_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/uqa=824
- 社区绿色空间的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%8F%8C%E8%89%B2%E7%90%83_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/jbO=Kp1
- 社区公共卫生的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/873
- 公共设施维护的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/nfl
- 个人时间管理的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/UD3
- 全民阅读推广的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/810=dgk
- 城市公共厕所的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/zld=753
- 市民意见收集的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/Caw=yLm
- 家庭饮食安排的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/811
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/zpm
- 社区手工活动的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/zoY
- 电动汽车充电的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/539=vbw
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/lxt=586
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/ahJ=RoU
- 公共卫生设施的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/091
- 健康步道使用的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/juy
- 社区绿色空间中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/H7r
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/113=dyt
- 市民热线服务的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/lqv=776
- 社区便利生活的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8E%BF%E5%9F%9F?/uRg=9VR
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/810
- 社区信息发布的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/yls
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/5Lx
- 终身学习资源的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/343=hpc
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/yha=617
- 城市空气科普的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/7nA=XBD
- 公共交通信息服务的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A4%B4%E6%9D%A1?/038
- 读书会组织的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A4%B4%E6%9D%A1?/bxd
- 公共健身器材的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A4%B4%E6%9D%A1?/y9M
- 社区休闲设施的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A4%B4%E6%9D%A1?/411=aol
- 乡村生活观察的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A4%B4%E6%9D%A1?/fsr=304
- 农产品消费体验的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A4%B4%E6%9D%A1?/N1K=YHW
- 市民意见收集的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/164
- 绿色办公实践的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/rfr
- 智能手机助老的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/UTe
- 劳动教育实践的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/946=zmk
- 家庭急救准备的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/gbb=240
- 数字阅读服务的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/MRZ=gTv
- 社区环保活动的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/620
- 智能家居应用的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/dby
- 乡村文化活动的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/cmi
- 科学教育活动的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/751=cxd
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/sjj=312
- 亲子科普活动的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/YJ2=mMe
- 社区艺术活动的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%87%AA%E5%8A%A9%E5%94%AE%E5%8D%96%E6%9C%BA%E5%8A%A0%E7%9B%9F_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/245
- 家庭安全提示的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%87%AA%E5%8A%A9%E5%94%AE%E5%8D%96%E6%9C%BA%E5%8A%A0%E7%9B%9F_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/xdm
- 城市人文观察的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%87%AA%E5%8A%A9%E5%94%AE%E5%8D%96%E6%9C%BA%E5%8A%A0%E7%9B%9F_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/uwC
- 城市社区治理的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%87%AA%E5%8A%A9%E5%94%AE%E5%8D%96%E6%9C%BA%E5%8A%A0%E7%9B%9F_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/138=ifh
- 城市空气科普的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%87%AA%E5%8A%A9%E5%94%AE%E5%8D%96%E6%9C%BA%E5%8A%A0%E7%9B%9F_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/fcu=830
- 城市应急科普的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%87%AA%E5%8A%A9%E5%94%AE%E5%8D%96%E6%9C%BA%E5%8A%A0%E7%9B%9F_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/A34=nUI
- 社会体育指导的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/930
- 亲子阅读活动的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nyw
- 街区小店体验的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/w4s
- 新能源知识普及的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/912=xla
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lwh=826
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/KnW=Ajw
- 线上办事服务的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/880
- 急救知识普及的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/cqg
- 青少年编程学习中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/d32
- 儿童友好空间的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/307=dya
- 小微企业服务的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/ozc=150
- 劳动教育实践的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/NtM=LqJ
- 公共场所导视的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%88%8A%E7%99%BB?/524
- 社区心理支持的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%88%8A%E7%99%BB?/luq
- 公共空间导览的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%88%8A%E7%99%BB?/Ey3
- 乡村教育资源中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%88%8A%E7%99%BB?/112=tqk
- 街区绿化养护的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%88%8A%E7%99%BB?/xik=272
- 城市体育设施的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_360%E5%88%8A%E7%99%BB?/8CV=rye
- 本地消费场景的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_9767cc%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/034
- 数字创意课程的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_9767cc%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/hdp
- 青少年编程学习的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_9767cc%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/Y7g
- 急救知识普及的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_9767cc%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/048=vor
- 城市公共饮水的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_9767cc%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/wgb=369
- 城市噪声观察的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_9767cc%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/lHu=j6Y
- 生活服务数字化的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8app%E6%8E%92%E8%A1%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/916
- 社区生活指南的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8app%E6%8E%92%E8%A1%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/edw
- 城市树木认养的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8app%E6%8E%92%E8%A1%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/zah
- 健康饮水科普的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8app%E6%8E%92%E8%A1%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/695=lfb
- 传统节日科普的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8app%E6%8E%92%E8%A1%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/vii=328
- 学校食育活动的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8app%E6%8E%92%E8%A1%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/UcK=OCY
- 城市慢行系统的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/853
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/lzp
- 智慧停车服务的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/rWe
- 数字学习资源的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/772=iif
- 日常摄影记录的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/zhy=722
- 远程协作工具的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/BhG=Zsz
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/452
- 街区更新实践的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/nes
- 社区环保活动的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/clQ
- 亲子阅读活动的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/784=zdd
- 电动汽车充电的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/axa=704
- 公园亲子设施的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ce6=HwQ
- 城市社区治理的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/778
- 社区垃圾分类的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/uyd
- 数字艺术创作的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/rRR
- 垃圾分类指导的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/316=eef
- 社区活动空间的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/bni=910
- 城市休闲步道的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/QhR=XRh
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/522
- 家庭教育交流的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qcd
- 网络信息辨识的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/geR
- 社区互助网络的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/221=ruh
- 读书会组织的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mwz=264
- 公共空间休憩的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/M0g=Tmv
- 个人数据管理的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/420
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/zrp
- 老年智能设备的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/OnE
- 物业服务沟通的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/216=beq
- 城市体育设施的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/osw=145
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/46y=9Yy
- 社区老年食堂的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%8E%8B%E4%B8%AD%E7%8E%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/972
- 生活垃圾回收的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%8E%8B%E4%B8%AD%E7%8E%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/oix
- 城市绿道建设的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%8E%8B%E4%B8%AD%E7%8E%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/o8G
- 公共空间休憩的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%8E%8B%E4%B8%AD%E7%8E%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/688=nyu
- 街区更新实践的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%8E%8B%E4%B8%AD%E7%8E%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/ytt=086
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%8E%8B%E4%B8%AD%E7%8E%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/miz=cDF
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%A5%96%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/556
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%A5%96%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/bii
- 城市骑行环境的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%A5%96%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/XZ1
- 社区花园共建的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%A5%96%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/322=lme
- 户外活动组织的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%A5%96%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/fct=681
- 智慧停车服务的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%A5%96%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/BBL=VT1
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/143
- 数字素养提升的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/bhn
- 电子商务服务的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/HMv
- 便民维修服务的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/904=gnw
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/wfa=608
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/AlS=5do
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/095
- 基层服务创新的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/vxn
- 儿童友好空间的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/9Xv
- 社区学习活动的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/686=fvq
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/ihk=591
- 公共卫生宣传的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/AFA=XjP
- 城市公共厕所的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%8C%85%E8%B5%A2_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/460
- 儿童友好空间的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%8C%85%E8%B5%A2_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/uls
- 城市慢行系统的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%8C%85%E8%B5%A2_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/i1f
- 周末休闲规划的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%8C%85%E8%B5%A2_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/726=ykm
- 城市文明实践的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%8C%85%E8%B5%A2_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/pxs=253
- 城市农夫市集的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%8C%85%E8%B5%A2_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/Uvv=Z2z
- 机器人科普活动的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%8E%A9%E5%90%88%E6%B3%95%E5%90%97_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/396
- 地方文化传播的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%8E%A9%E5%90%88%E6%B3%95%E5%90%97_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/ciu
- 居家适老化改造的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%8E%A9%E5%90%88%E6%B3%95%E5%90%97_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/Rsw
- 学校食育活动的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%8E%A9%E5%90%88%E6%B3%95%E5%90%97_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/586=rcw
- 数字生活课堂的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%8E%A9%E5%90%88%E6%B3%95%E5%90%97_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/tsn=689
- 社区体育组织的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%8E%A9%E5%90%88%E6%B3%95%E5%90%97_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/xmP=M69
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%A3%8B%E7%89%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/290
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%A3%8B%E7%89%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/dwy
- 智能家居应用中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%A3%8B%E7%89%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/SbG
- 社区运动空间的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%A3%8B%E7%89%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/219=upq
- 小区停车协商的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%A3%8B%E7%89%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/dxc=073
- 在线教育体验的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%A3%8B%E7%89%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/Dhx=NXn
- 物业服务沟通的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%AC%E5%8F%B8%E5%90%8D_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/709
- 电子商务服务的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%AC%E5%8F%B8%E5%90%8D_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/myg
- 居家适老化改造的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%AC%E5%8F%B8%E5%90%8D_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/0SM
- 科学信息获取的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%AC%E5%8F%B8%E5%90%8D_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/176=pce
- 城市博物馆活动的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%AC%E5%8F%B8%E5%90%8D_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/jco=668
- 在线学习体验的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%AC%E5%8F%B8%E5%90%8D_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/ZQT=ZKC
- 家庭运动计划的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/066
- 社区家校合作中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/ydl
- 地方旅游导览的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/G3D
- 数字学习资源的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/483=qfb
- 城市应急广播的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/vje=812
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/5Tx=PM0
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/264
- 科学教育活动的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/dyx
- 校园社团活动的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/dhm
- 社区活动空间的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/673=xku
- 节日文化体验的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/qjq=963
- 数字档案服务的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/D34=HtX
- 城市地名文化的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_168%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/626
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_168%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/jik
- 环境教育课程的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_168%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/Joi
- 居家适老化改造的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_168%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/382=lmu
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_168%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/bgg=729
- 社区绿色空间的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_168%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/Xx1=ew5
- 数字地图应用的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E6%9C%80%E6%AD%A3%E8%A7%84%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/656
- 便民维修服务的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E6%9C%80%E6%AD%A3%E8%A7%84%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/ggr
- 网络安全教育的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E6%9C%80%E6%AD%A3%E8%A7%84%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/i5J
- 科学运动指导的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E6%9C%80%E6%AD%A3%E8%A7%84%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/394=gza
- 社区防暑服务的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E6%9C%80%E6%AD%A3%E8%A7%84%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/nqq=161
- 健康信息获取的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E6%9C%80%E6%AD%A3%E8%A7%84%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/69a=RCM
- 社区手工活动的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/145
- 校园社团活动的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/rkw
- 城市公共饮水的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/JSR
- 城市公共艺术中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/352=kdf
- 校园节能行动的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/hpy=858
- 城市人文观察的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/zV9=rLJ
- 非遗体验活动的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/585
- 本地旅行体验的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/hkq
- 电动汽车充电的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/Pjs
- 社区便民集市的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/717=vee
- 线上阅读资源的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/wwn=774
- 环境教育课程的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/vZI=2E7
- 地方旅游导览的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/835
- 城市噪声观察的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/aqq
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/WHq
- 旧物循环利用的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/583=kga
- 健康步道使用中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/snl=009
- 社区故事采集的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/ZEO=z5d
- 健康饮水科普的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E8%B4%AD_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/934
- 健康步道使用的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E8%B4%AD_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/znx
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E8%B4%AD_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/2PE
- 食品安全科普的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E8%B4%AD_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/619=cdy
- 邻里互助活动的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E8%B4%AD_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/jio=935
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E8%B4%AD_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/VnC=Omi
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/352
- 乡村文化空间的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/qhq
- 社区老年食堂的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/OJh
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/147=zsc

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
