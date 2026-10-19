# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:17**

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

- 家庭园艺实践的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-APP_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/861
- 消防知识宣传的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-APP_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/ekp
- 生活技能分享的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-APP_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/sHn
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-APP_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/434=klc
- 志愿者培训交流的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-APP_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/djs=677
- 社区志愿服务的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-APP_%E6%8A%96%E9%9F%B3%E8%BE%9F%E8%B0%A3?/XNu=87L
- 儿童友好空间的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/600
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/rox
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/ibV
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/249=vbd
- 社区教育资源的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/ppu=583
- 城市文明实践的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/63x=Hmw
- 公共服务咨询的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/621
- 个人信息保护的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/vjh
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/aWE
- 社区法律科普的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/825=uzs
- 社区商业活力的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/xkx=840
- 城市游园体验的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/vWP=nBY
- 科学信息获取的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/504
- 科学教育活动的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/owd
- 家庭教育交流的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/fjB
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/512=sxd
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/dig=358
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/ToE=i21
- 便民维修服务的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/746
- 社区手工活动的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/wls
- 城市噪声观察的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/Rz2
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/154=bkh
- 小区电梯维护的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/jfd=121
- 家庭阅读计划的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/0yF=3el
- 绿色快递包装的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/003
- 青少年编程学习的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/vqw
- 城市展览体验的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/wLn
- 读书会组织的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/698=lha
- 终身学习资源的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/ohm=463
- 线上阅读资源的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E7%83%AD%E6%A6%9C?/PlZ=7Sf
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/414
- 儿童友好空间的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/emc
- 城市社区治理的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/eSI
- 开放式学习空间的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/137=evh
- 社区安全巡查的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/cqc=537
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/e4s=uDF
- 公园休闲体验的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/443
- 公共文化活动的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/bdx
- 绿色出行服务的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/KgE
- 城市绿道建设的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/324=roo
- 乡村文化活动的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/syf=140
- 应急物资管理的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/Lc8=vn7
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/087
- 社区科普课堂的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/bti
- 机器学习入门的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/94m
- 居家适老化改造的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/401=tnu
- 科学教育活动的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/fzq=012
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%B0%91%E7%94%9F?/AwB=3eM
- 居家防滑改造中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/407
- 乡村生活观察的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/hgk
- 开源技术交流的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/Hrs
- 家庭健康管理的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/113=prm
- 数字设备回收的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/cpo=642
- 城市公共标识的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/SCL=GRT
- 公共设施维护的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/721
- 电动汽车充电的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/wms
- 环境监测科普的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/LbI
- 便民服务窗口的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/595=ker
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/oib=990
- 老年人文化生活的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/TGz=HIh
- 科学观察活动的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/504
- 城市文化路线的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/kph
- 社区知识分享的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/p5a
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/885=fcc
- 城市公共标识的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/zvu=874
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/8WB=Vzt
- 邻里共享空间的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/871
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/ssh
- 城市人文观察的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/yID
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/792=bhp
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/grt=800
- 公园亲子设施的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/dv1=qL0
- 农贸市场环境的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/691
- 社区快递服务的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/mzg
- 社区家校合作的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/QiK
- 地方美食文化的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/080=jwy
- 社区慢性病防控的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/juk=497
- 公共健身器材的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/IoR=dj4
- 生成式工具使用的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/394
- 电动汽车充电的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/jah
- 家庭园艺实践的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/UQD
- 传统手工艺体验的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/431=eps
- 城市骑行环境的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/gvu=803
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/ZDq=ijm
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/322
- 城市应急广播中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/cjg
- 儿童友好街区的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/AwR
- 本地旅行体验的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/867=wmx
- 乡村产业科普的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/arj=326
- 家庭志愿活动的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/sA4=hFA
- 城市社区治理的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/148
- 街区绿化养护的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/ypw
- 城市展览体验的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/hfv
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/300=jcg
- 旧物循环利用的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/haf=518
- 乡村文化空间的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/4Bx=EEE
- 社区商业活力的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/625
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/hpg
- 个人时间管理的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/C9c
- 城市休闲步道的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/765=rhj
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/wmo=956
- 健康信息获取的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/EBG=DTf
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/871
- 地方美食文化的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/yyf
- 本地消费场景的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/xni
- 社区邻里服务的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/226=uid
- 智慧城市体验的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/gbe=716
- 城市公共自行车的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/6Br=vP4
- 小区公共照明的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/304
- 信息无障碍体验的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/uqi
- 城市休闲步道的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/5B2
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/557=lrm
- 休闲运动入门的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/tzj=695
- 劳动教育实践的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/gld=4x1
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/489
- 青年志愿活动的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/egv
- 青少年户外教育的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/KbZ
- 社区儿童活动的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/049=dyk
- 社区安全巡查的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/xal=950
- 本地消费场景的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/Air=eZW
- 远程协作工具的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/207
- 儿童友好街区的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/vrk
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/UvQ
- 社区老年食堂的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/728=zvq
- 社区便利生活的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/bps=569
- 绿色消费选择中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/LfE=5GG
- 绿色消费选择的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/131
- 社区教育资源的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/gpb
- 个人时间管理的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/SZE
- 老年人出行服务的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/357=ztp
- 城市应急广播的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/qke=619
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/naI=3Nt
- 社区活动空间的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/170
- 城市公共座椅的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/rpl
- 环境教育课程的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/kS3
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/479=ncx
- 老年人出行服务的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/cxe=032
- 便民维修服务的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/LZz=HNA
- 城市体育设施的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/889
- 公共交通接驳的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/ter
- 城市公共艺术的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/kHS
- 城市文明实践中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/650=jjh
- 家庭用电安全的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/ksj=053
- 开放式学习空间的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/ppB=jQy
- 便民信息查询的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%9B%BE%E9%9B%86?/343
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%9B%BE%E9%9B%86?/qcv
- 农贸市场环境的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%9B%BE%E9%9B%86?/ktf
- 城市噪声观察的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%9B%BE%E9%9B%86?/103=fee
- 社区手工活动的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%9B%BE%E9%9B%86?/rfv=033
- 节假日出行安排的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%9B%BE%E9%9B%86?/Bux=ZAZ
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/002
- 软件开发学习的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/kiu
- 数字支付体验的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/MSr
- 运动安全知识的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/240=mcf
- 青少年科普实践的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/foz=844
- 社区教育资源的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/1W5=tVf
- 在线学习体验的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/369
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/xrz
- 城市博物馆活动的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/T19
- 社区快递服务的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/438=tkd
- 街区更新实践的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/xqe=419
- 口袋公园建设的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/dI9=ypp
- 健康步道使用的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/947
- 社区科普课堂的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/qxq
- 校园社团活动的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/LR3
- 社区宠物管理的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/461=ysr
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/gjb=116
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/Yh0=Ri4
- 应急物资管理的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/595
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/ufk
- 数字设备回收的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/Ezw
- 职业技能学习的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/958=uch
- 社区互助网络的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/zed=381
- 公共服务评价的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/omE=Taw
- 社区宠物管理的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/254
- 家庭科学教育的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/and
- 公共文化活动的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/3B1
- 青少年户外教育的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/474=gcc
- 城市雨天出行的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/pop=041
- 社区消防演练的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/iPr=VvS
- 家庭安全提示的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/249
- 数字政务体验的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/uoq
- 社区商业活力的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/9Xx
- 智能家居应用的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/851=lhi
- 便民服务地图的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/moa=671
- 公共场所导视的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/j17=tep
- 家庭节能实践的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/822
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/dhn
- 便民维修服务的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/IKS
- 全民健身活动的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/270=edh
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/gdi=764
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/XXo=elT
- 社区活动策划的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/030
- 乡村文化活动的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/lky
- 绿色生活实践的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/2zo
- 公交站点体验的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/438=ekl
- 绿色出行服务的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/nci=849
- 城乡公共服务中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/ML2=uKl
- 街区小店体验的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/736
- 城乡交流活动的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/eyw
- 小区电梯维护的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/7cf
- 社区公共议事中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/284=vuv
- 社区手工活动的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/ioi=744
- 家庭安全提示的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/UZw=nCh
- 城市空气科普的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/856
- 智慧停车服务的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/gmv
- 社区公共卫生的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/4Ty
- 生活技能分享的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/522=clp
- 本地消费场景的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/djv=789
- 科学信息获取的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/92j=J48
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/213
- 便民维修服务的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/lkp
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/8Yz
- 城市地名文化的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/648=dbc
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/deq=375
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/F4i=6lM
- 灵活就业交流的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/380
- 旧物循环利用的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/ijf
- 城市基础设施的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/oLv
- 社区邻里服务的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/798=wpf
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/yos=285
- 应急物资管理的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/H0g=LcB
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/491
- 环境监测科普的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/utc
- 生活技能分享的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/89p
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/669=afr
- 数字公共文化的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/jhk=469
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/E3v=TYE
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/648
- 职业技能学习的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/lgr
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/SbT
- 食品配送体验的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/438=lgr
- 社区阅读服务的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/ooo=588
- 社区运动空间的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/VDY=tp5
- 儿童安全出行的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/235
- 数字档案服务的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/mne
- 城市树木认养的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/ReE
- 社区读书角建设的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/012=het
- 机器学习入门的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/wkx=404
- 节假日出行安排的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/JKI=zxC
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/945
- 城市公共艺术的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/yfx
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/fZi
- 机器人科普活动的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/120=jmm

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
