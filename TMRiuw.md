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

- 乡村公共服务的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/zag=660
- 老年数字阅读的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/ssO=aoB
- 公益活动组织的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%89%BE%E4%B8%AA%E4%BD%A3%E9%87%91%E9%AB%98%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/198
- 软件开发学习的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%89%BE%E4%B8%AA%E4%BD%A3%E9%87%91%E9%AB%98%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/xxn
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%89%BE%E4%B8%AA%E4%BD%A3%E9%87%91%E9%AB%98%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/Y4y
- 老年人出行服务的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%89%BE%E4%B8%AA%E4%BD%A3%E9%87%91%E9%AB%98%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/549=dpv
- 家庭用电安全的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%89%BE%E4%B8%AA%E4%BD%A3%E9%87%91%E9%AB%98%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/zoo=035
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%89%BE%E4%B8%AA%E4%BD%A3%E9%87%91%E9%AB%98%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/oOL=x02
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/640
- 农业科普体验的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/mbr
- 乡村公共文化中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/XkQ
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/285=ypz
- 邻里共享空间的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/rcx=586
- 城市基础设施的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/dOQ=jxW
- 城市公共厕所的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/034
- 光伏知识科普的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/ljw
- 社区垃圾回收的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/f8a
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/767=ivw
- 环境教育课程的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/lyu=722
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/gzv=VRD
- 本地消费场景的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/957
- 公园无障碍服务的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/opa
- 街头绿植养护的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/FWq
- 数字公共文化的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/571=ysv
- 社区慢性病防控的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/aso=278
- 青年志愿活动的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/xoU=Ul4
- 乡村产业科普的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/386
- 城市人文观察的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/nip
- 环境教育课程的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/1uR
- 社区教育资源的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/098=dbh
- 本地消费场景的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/tdy=793
- 城市夜间生活的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/eet=nWd
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/025
- 生活垃圾减量的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/pni
- 公共场馆服务的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/e6O
- 市民热线服务的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/875=cqe
- 城市夜间照明的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/ajy=263
- 地方民俗记录的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/jD4=Ocu
- 个人时间管理的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/891
- 乡村公共阅读的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/kbi
- 跨代沟通活动的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/BFS
- 城市夜间生活中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/315=xyh
- 街区绿化养护的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/odl=983
- 城市公共标识的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/fqB=frn
- 人工智能科普的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/235
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/iaj
- 城乡公共服务的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/1Kx
- 社区公共餐饮的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/669=sev
- 青少年心理健康的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/kkf=111
- 休闲运动入门的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/4HV=iBr
- 数字学习资源的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/629
- 校园社团活动的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/joo
- 数字支付体验的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/2xh
- 绿色校园实践的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/036=bwk
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/xdx=848
- 应急物资管理的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/zBF=U1s
- 社区读书角建设的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/106
- 社区防暑服务的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/bel
- 数字创作工具的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/3lJ
- 数字便民地图的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/165=iat
- 数字素养提升的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/eej=249
- 通勤路线规划的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6_%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/0hV=J2R
- 在线学习体验的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/689
- 便民信息查询的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/qzo
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/nhE
- 基层健康档案的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/404=oqt
- 社区阅读服务的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/ssi=395
- 数字便民地图的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9_%E8%85%BE%E8%AE%AF%E4%BF%A1%E6%89%98?/3SH=WPR
- 城市基础设施的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/706
- 电子商务服务的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/ixv
- 社区教育资源的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/ZY5
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/251=mkj
- 社会体育指导的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/djf=746
- 城市体育设施的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/bM0=Ri3
- 城市步行友好中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/244
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/vpu
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/zxx
- 无障碍出行的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/609=ccy
- 小区公共照明的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/lgh=622
- 社区托育服务的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/dZn=qKP
- 非遗体验活动中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/960
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/rnl
- 休闲运动入门的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/aoI
- 数字阅读服务中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/867=wzf
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/fnp=446
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94_%E7%99%BE%E5%BA%A6%E6%95%99%E8%82%B2?/kde=oZl
- 新能源知识普及的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/825
- 垃圾分类指导的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/qgu
- 老旧小区改造的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/gqQ
- 创业经验分享的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/787=ryv
- 数字创意课程的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/qgt=148
- 社区运动空间的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/TZK=FGq
- 社区儿童活动的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/981
- 药品使用科普的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/wig
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/MCA
- 药品使用科普的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/464=chh
- 智能手机助老的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/nlt=058
- 学校体育活动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/d67=ar0
- 城市公共厕所的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/344
- 小区电梯维护的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/yst
- 数字支付体验的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/bnh
- 社区共享书架的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/749=xqi
- 城市绿道建设的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/nek=370
- 城市博物馆服务的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/Ktb=TGe
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/432
- 生活技能分享的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/pun
- 城市应急广播的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/IrX
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/560=iqi
- 数字创意课程的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/tmq=627
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/1q4=oww
- 健康步道使用的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/862
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/dnh
- 邻里互助活动的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/I8Y
- 绿色消费选择的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/901=gzp
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/aci=070
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/joK=Y1Z
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/174
- 居家适老化改造的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/uqm
- 家庭环保习惯的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/NOo
- 数字便民地图的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/639=zvm
- 社区家政服务的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/oiq=283
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/kG3=xBc
- 社区艺术活动的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/447
- 食品配送体验的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/xzo
- 家庭节能设备中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/Nrk
- 地方美食文化的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/131=oio
- 城市公共艺术的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/jlf=754
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/iss=IbT
- 城市公共厕所的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/244
- 社区读书角建设的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/xgy
- 城市运动公园的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/LL7
- 城市展览体验的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/436=lvi
- 社区垃圾分类的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/guj=946
- 老年运动活动的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/c1i=7b2
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%AC%E7%9B%8A?/879
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%AC%E7%9B%8A?/ewa
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%AC%E7%9B%8A?/HlY
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%AC%E7%9B%8A?/258=fjl
- 软件开发学习的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%AC%E7%9B%8A?/gbe=343
- 节假日出行安排的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%AC%E7%9B%8A?/PaD=XQ5
- 家庭收纳实践的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/814
- 小区停车协商的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/grq
- 数字公共文化的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/9GS
- 老年学习活动的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/512=rpb
- 城市可持续生活的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/jzt=291
- 社区环保活动的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/wcg=A3T
- 图书馆活动策划的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/457
- 城市建设科普的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/vlx
- 家庭安全提示的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/EfP
- 就业技能培训的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/835=buu
- 开放式学习空间的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/isi=084
- 老年友好服务的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/c4L=HcX
- 家庭教育交流的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/764
- 农村环境治理的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/wuj
- 电动汽车充电的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/EN4
- 数字创作工具的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/329=kom
- 节约用水实践的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/oxd=513
- 市民热线服务的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/rry=k3N
- 图书馆活动策划的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/262
- 药品使用科普的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/wlu
- 节气饮食文化的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/QBq
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/276=ihi
- 人工智能科普的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/raj=460
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/Bv8=rdC
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/422
- 便民信息查询的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/cpc
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/jGH
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/342=yib
- 健康饮水科普的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/tjm=958
- 全民健身活动的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/bOp=JH3
- 本地历史资料的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/848
- 家庭急救准备的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/stk
- 家庭网络使用的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/re0
- 社区手工活动的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/720=ysz
- 生活技能分享的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/erx=956
- 食品安全科普的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/hBa=WbI
- 城市绿色交通的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/525
- 公共设施使用的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/psm
- 食品安全科普的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/E0P
- 骑行路线规划的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/003=dvk
- 公共服务预约的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/jwf=544
- 周末休闲规划的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/5ZD=MF0
- 电子商务服务的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/206
- 社区科普课堂的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/rzk
- 节日文化体验的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/bQw
- 老年数字阅读的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/078=ale
- 本地历史资料的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/jmv=380
- 城市微更新实践的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/u93=UOo
- 社区文化节活动的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/924
- 社区活动策划的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/zvr
- 非遗体验活动的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/5Bz
- 便民服务地图的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/116=lsh
- 校园安全教育的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/siz=296
- 街区更新实践的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%BE%8E%E9%A3%9F?/CD4=LKK
- 城乡交通衔接的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/453
- 农村环境治理的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/qml
- 人工智能科普的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/kSL
- 数字阅读服务的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/903=glh
- 社区志愿服务的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/vkh=756
- 社区艺术活动的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/t1T=2zh
- 城市社区治理的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/922
- 城市地名文化的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/cgc
- 租房信息服务的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/pwZ
- 社区生活指南的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/321=ass
- 家庭环保行动的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/ufg=615
- 气象科普传播的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/b4N=IC6
- 绿色办公实践的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/283
- 城市共享单车的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/cpo
- 亲子科普活动的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/IhJ
- 校园社团活动的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/535=axz
- 公共交通接驳的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/ooo=271
- 城乡交流活动的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/LHS=HYX
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/985
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/cre
- 绿色办公实践的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/GJQ
- 社区邻里服务的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/157=gnk
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/klo=949
- 社区修缮行动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/UMX=1Ti
- 儿童阅读角的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/324
- 街区道路维护的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/miv
- 城市公共自行车的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/LH9
- 公共服务评价的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/790=zow
- 网络信息辨识的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/ljc=714
- 绿色出行服务的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/k3M=cG2
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/126
- 社区家校合作的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/rjm
- 老年人出行服务的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/e1t
- 社区邻里服务的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/907=rsc
- 休闲运动入门的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/nrg=461
- 城市公共空间的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/Vkb=zYm
- 志愿服务平台的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/908
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/ogr
- 节假日出行安排的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/WTx
- 小区停车协商的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/167=mdk
- 农产品消费体验的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/orp=342
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/Dp9=4cp
- 社区消防演练的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/617
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/oit
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/rMg
- 读书会组织的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/067=aju
- 环境教育课程的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/hec=861
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/yGc=r8b
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/219
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/yaw
- 社区防暑服务的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/0R4
- 城乡公共服务的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/442=rtl
- 社区环保活动的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/wzo=463
- 社区健康讲座中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/zYo=LbZ
- 全民健身活动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E9%9B%85%E8%99%8E?/814
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E9%9B%85%E8%99%8E?/air

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
