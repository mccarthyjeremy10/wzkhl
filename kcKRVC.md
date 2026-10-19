# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:16**

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

- 社区志愿服务的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/qau=520
- 数字档案服务的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/KQE=Dgb
- 乡村公共服务的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/433
- 节约用水实践的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/tol
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/hNp
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/558=uty
- 城市公共标识中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/tgt=486
- 社区消防演练的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/whp=LlX
- 农村环境治理的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8818cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/191
- 数字素养提升的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8818cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/ebc
- 绿色办公实践的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8818cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/utY
- 城市骑行环境的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8818cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/031=aui
- 终身学习资源的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8818cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/usz=780
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8818cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/SyE=noi
- 图书借阅体验的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8818cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/915
- 城市公共标识的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8818cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/qim
- 社区教育资源的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8818cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/daZ
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8818cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/702=pbs
- 家庭照护支持的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8818cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/xip=344
- 文化场馆预约的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8818cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/Q3f=Eiv
- 市民热线服务的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_8818cc-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/458
- 儿童运动体验的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_8818cc-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/vpd
- 家庭环保习惯的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_8818cc-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/3dN
- 城市骑行环境的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_8818cc-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/695=prs
- 城市慢行系统的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_8818cc-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/lcl=965
- 课后服务体验的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_8818cc-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AF%84?/gum=BX4
- 社区读书角建设的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/884
- 远程协作工具的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/ffa
- 人工智能科普的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/Bsc
- 城市住房服务的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/035=afd
- 口袋公园建设的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/fsr=301
- 社区休闲设施的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/RLg=cXq
- 亲子阅读活动的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/436
- 社区便民服务的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/ftg
- 家庭健康科普的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/V2F
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/330=rub
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/nvj=961
- 城市步行友好的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%9F%8E%E4%BA%8B?/iGl=Ju0
- 公共卫生设施的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/243
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/ihi
- 公共空间照明的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/wny
- 线上办事服务的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/183=cxu
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/fth=909
- 儿童运动体验的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/Yrv=tI0
- 城市可持续生活的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/550
- 农村环境治理的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/tki
- 社区知识分享的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/hIe
- 健康信息获取的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/094=wrl
- 社区法律科普的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/gny=834
- 城乡交流活动的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/ewi=gC9
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/468
- 数字地图应用的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/lhy
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/pii
- 城市地名文化的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/056=rah
- 生活垃圾回收的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/cix=420
- 个人时间管理的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%86%9C%E4%B8%9A?/vmg=lth
- 青年就业服务的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/319
- 城市应急广播的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/wtm
- 城市社区治理的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/9Fl
- 图书馆数字服务的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/131=wgf
- 城市夜间生活的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/txu=339
- 物业服务沟通的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/AMX=JOU
- 居民健康教育的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/049
- 城市农夫市集的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/bdp
- 公益活动组织的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/Ekd
- 城市步行环境的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/969=cnl
- 校园社团活动的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/zol=195
- 学校体育活动的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/alM=G0N
- 绿色生活实践的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/424
- 生活服务数字化的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/gzp
- 开放数据应用的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/1yP
- 便民服务窗口的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/052=oaz
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/kpy=044
- 社区体育组织的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/zIu=PoT
- 开放式学习空间的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/929
- 公共空间导览的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/dut
- 光伏知识科普的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/OpG
- 城市公共厕所的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/112=qbi
- 乡村生态观察的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/akm=387
- 社区文化节活动的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/rad=eHb
- 亲子阅读活动的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%9B%9E%E6%94%BE?/162
- 家庭教育交流的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%9B%9E%E6%94%BE?/jcc
- 信息无障碍体验的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%9B%9E%E6%94%BE?/eBp
- 青年职业探索的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%9B%9E%E6%94%BE?/779=sty
- 青年职业探索的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%9B%9E%E6%94%BE?/xcg=687
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8818cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%9B%9E%E6%94%BE?/LLM=Uug
- 城市生活记录的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/576
- 科学观察活动中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/dka
- 城市骑行环境的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/z56
- 公共服务评价的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/939=smh
- 青少年户外教育的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/mch=237
- 家庭消费规划的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/BFd=eXE
- 居家防滑改造的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/317
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/nik
- 公共场所导视的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/FIG
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/925=ztb
- 城市公共艺术的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/nst=662
- 校园安全教育的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/4XT=DHC
- 社区休闲设施的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/853
- 社区应急准备的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/shc
- 非遗体验活动的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/TD9
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/888=bym
- 邻里互助活动的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/vyg=459
- 全民健身活动的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_8818cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/xK2=gkB
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/217
- 文明养宠科普的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/tbh
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/DZu
- 城乡交通衔接的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/928=xlm
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/gvr=927
- 本地历史资料的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/8J2=QiE
- 市民热线服务的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E7%A4%BE%E8%AE%BA?/459
- 数字公共文化的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E7%A4%BE%E8%AE%BA?/mzm
- 线上阅读资源的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E7%A4%BE%E8%AE%BA?/xgd
- 图书借阅体验的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E7%A4%BE%E8%AE%BA?/652=yjw
- 儿童友好空间的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E7%A4%BE%E8%AE%BA?/hmk=839
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E7%A4%BE%E8%AE%BA?/wxz=XzE
- 老年人出行服务的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/607
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/bcx
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/IOx
- 家庭阅读计划的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/015=qdu
- 口袋公园建设的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/pdy=634
- 生活技能分享的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_8818cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/IzJ=vaP
- 开源技术交流的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/082
- 社区设施共享的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/jqr
- 节约用水实践的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/1vK
- 个人时间管理的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/591=ftz
- 光伏知识科普的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/arq=776
- 数字资源检索的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/nwB=FDO
- 老年人文化生活的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/273
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/oyc
- 学校体育活动的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/wuf
- 安全出行教育的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/627=vwa
- 家庭收纳实践的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/crz=877
- 旧物循环利用的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_8818cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/jfD=8rX
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/436
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/vit
- 城市农夫市集的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/HMs
- 儿童运动体验的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/950=sdh
- 城市公共厕所的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/tkt=156
- 城市社区治理的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_8818cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/WMN=9pX
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_8818cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/899
- 家庭健康科普的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_8818cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/oij
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_8818cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/j8C
- 社区法律科普的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_8818cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/639=api
- 社区生活指南的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_8818cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/cbx=883
- 城市公共空间的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_8818cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/Pcg=kIw
- 创业经验分享的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/809
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/kbw
- 家庭教育交流的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/8Sm
- 志愿者培训交流的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/612=tnd
- 数字公共文化的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/wvp=066
- 社区教育资源的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_8818cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/30m=Cbl
- 网络信息辨识的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_886%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/768
- 农贸市场环境的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_886%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/bkd
- 地方旅游导览的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_886%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/z2X
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_886%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/811=het
- 软件开发学习的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_886%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/yry=183
- 终身学习资源的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_886%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/OAC=68d
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/066
- 城市微更新实践的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/orb
- 公园亲子设施的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/pMc
- 市民热线服务的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/696=tzr
- 科普展览体验的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/ohd=835
- 乡村产业科普的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/v74=SPK
- 城市基础设施的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/283
- 光伏知识科普的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/hpt
- 城市慢行系统的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/Qfa
- 社区商业活力的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/034=oof
- 家庭节能实践的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/mbm=751
- 乡村文化活动的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/qPP=Nzl
- 公共空间照明的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%BD%B1%E8%A7%86?/255
- 儿童安全出行的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%BD%B1%E8%A7%86?/afv
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%BD%B1%E8%A7%86?/hUy
- 城市微更新实践有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%BD%B1%E8%A7%86?/481=sxj
- 线上办事服务的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%BD%B1%E8%A7%86?/jsg=994
- 乡村公共服务的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%BD%B1%E8%A7%86?/pDX=J5F
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/993
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/mos
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/PSC
- 公共交通信息服务的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/064=gzl
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/otf=473
- 家庭健康科普的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/gl6=iur
- 社区交通安全的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/118
- 城市噪声观察的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/ypk
- 绿色生活实践的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/GD9
- 青少年心理健康的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/391=puy
- 志愿服务平台的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/brz=297
- 公共服务评价的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/fKu=M8t
- 社区托育服务的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/165
- 数字支付体验的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/frv
- 小微企业服务的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/rMz
- 健康信息获取的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/734=gtk
- 社区家校合作的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/ond=991
- 社区休闲设施的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/gIS=yvy
- 社区垃圾分类的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/528
- 日常摄影记录中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/ovt
- 公共交通信息服务的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/8eY
- 社区便民服务的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/428=ocp
- 社区家政服务的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/unc=695
- 数字生活课堂的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/egy=xBm
- 城市生活记录的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/410
- 绿色生活实践的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/ckd
- 社区便民集市的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/a3N
- 农贸市场环境的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/765=nqv
- 城乡公共服务的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/ssy=589
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_886%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/2e2=F3h
- 社区便民集市的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/225
- 社区停车服务的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/idj
- 户外活动组织的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/tyO
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/027=lbi
- 城市夜间生活的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/nlk=467
- 社区活动报名的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/bxG=90f
- 城市慢行系统的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/591
- 学校体育活动的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/xaz
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/rBB
- 青少年编程学习中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/421=shd
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/jqd=222
- 社区慢性病防控的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/b7b=WWU
- 儿童阅读角的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/657
- 社区防暑服务的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/eob
- 社区手工活动的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/fCS
- 社区花园共建的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/904=lyr
- 社区商业活力的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/xfx=703
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/Ez4=Uo8
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/399
- 终身学习资源的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/cct
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/Ia0
- 休闲运动入门的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/349=fys
- 便民维修服务的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/mpc=971
- 人工智能科普的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_886%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/H6h=uJ7
- 网络安全教育的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_886%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/758
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_886%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/lfu
- 青年职业探索的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_886%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/xGF
- 家庭用电安全的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_886%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/258=hhv
- 垃圾分类指导的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_886%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/ull=362
- 家庭安全提示的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_886%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/jXs=oMT
- 学校体育活动的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/133
- 应急物资管理的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/gkh
- 文化讲座服务的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/bjX
- 节能生活方式的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/140=mqy
- 城乡交流活动的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/bez=712
- 生成式工具使用的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_886%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/EaM=XJ9
- 城市适老服务的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/266
- 家庭饮食安排的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/jfx
- 网络信息辨识的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/zly
- 数字课堂应用的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/458=jie
- 图书借阅体验的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/cxt=954
- 绿色办公实践的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_886%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/Fb5=Vkw
- 青少年编程学习的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_886%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/810
- 社会体育指导的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_886%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/rhm

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
