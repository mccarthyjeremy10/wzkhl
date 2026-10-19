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

- 小区电梯维护的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/441
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/zoc
- 乡村生态旅游的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/Noy
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/211=ijv
- 社区互助网络的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/vjd=448
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/V3b=qCK
- 公共空间照明的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/826
- 社区托育服务的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/bbw
- 社区邻里服务的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/laL
- 校园安全教育的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/628=gmj
- 居家适老化改造的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/flm=885
- 社区知识分享的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/EtE=XIl
- 家庭节能实践的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/711
- 图书馆数字服务的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/mlv
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/xw4
- 城市适老服务的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/063=cbg
- 社区协商议事的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/mbb=087
- 农业科普体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/nMv=CWi
- 城市便民驿站的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/275
- 社区设施共享中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/tlk
- 气象科普传播的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/XbH
- 儿童运动体验的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/300=nxb
- 城市社区治理的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/edk=429
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/8ip=hAa
- 图书馆数字服务的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/795
- 社区老年食堂的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/dwp
- 社区生活指南的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/Cp7
- 社区家政服务的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/755=vkr
- 社区托育服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vzf=375
- 乡村公共阅读的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/74m=TN6
- 社区活动空间的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/399
- 城市绿色交通的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/jya
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/ddl
- 社区教育资源的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/506=asl
- 社区应急准备的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/euu=949
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/13R=bv2
- 地方美食文化的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/519
- 开源技术交流的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/kkn
- 社区停车服务的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/2ly
- 青少年户外教育的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/346=jkt
- 社区商业活力中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/kab=623
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/vW1=hvT
- 公共场所导视的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/873
- 科学教育活动的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/sat
- 本地历史资料的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/Dnq
- 社区体育组织的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/404=rxb
- 小微企业服务中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/qpy=322
- 节约用水实践的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/duC=W7l
- 劳动教育实践的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/146
- 在线学习体验的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/anv
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/C0q
- 农贸市场环境的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/163=oig
- 公园亲子设施的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/rkx=394
- 本地消费场景的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/woe=ClL
- 社区修缮行动的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/894
- 社会体育指导的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/rpy
- 数字素养提升的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/1K1
- 城乡公共服务的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/575=sim
- 基层健康档案的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/blk=881
- 社区健康讲座的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/Z2b=rT1
- 地方旅游导览的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/225
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/qgo
- 网络安全教育的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/xNW
- 社区公共餐饮的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/305=yev
- 个人数据管理的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/lcf=194
- 个人时间管理的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/U8Q=6Lz
- 居家适老化改造的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%9B%9E%E6%94%BE?/373
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%9B%9E%E6%94%BE?/enh
- 非遗课堂体验的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%9B%9E%E6%94%BE?/7cE
- 节能生活方式的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%9B%9E%E6%94%BE?/443=tnh
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%9B%9E%E6%94%BE?/gro=491
- 地方文化传播的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_360%E5%9B%9E%E6%94%BE?/n7p=PYE
- 小区电梯维护的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/167
- 青年就业服务的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/luz
- 数字政务体验的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/74r
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/415=wts
- 数字课堂应用的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/she=258
- 旧物循环利用的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/wP2=oZU
- 食品配送体验的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/758
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/noj
- 户外活动组织中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/qsz
- 社区家校合作的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/927=ltx
- 消防知识宣传的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/msv=300
- 城市基础设施的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/kPC=XzL
- 网络信息辨识的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%86%E9%A2%91?/804
- 乡村产业科普的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%86%E9%A2%91?/rni
- 文化讲座服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%86%E9%A2%91?/k8S
- 老年人日常照护的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%86%E9%A2%91?/402=fkt
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%86%E9%A2%91?/xed=285
- 青年就业服务中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%86%E9%A2%91?/k2f=u1F
- 城市步行环境的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/700
- 读书会组织的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/uxo
- 新能源知识普及的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Djl
- 城市步行环境的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/550=jdf
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pdi=675
- 城市公共艺术的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Upk=6EN
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/073
- 绿色出行服务的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/frw
- 生活技能分享的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/PmA
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/168=kju
- 数据分析入门中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/nhj=788
- 社区公共卫生的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/q6M=Isr
- 公共空间照明的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/674
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/cku
- 城市公共空间的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/Jfm
- 城市应急广播的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/846=ypu
- 电动汽车充电的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/wwl=678
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/sCt=tw8
- 公共服务评价的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/957
- 乡村文化空间的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/wle
- 老年智能设备的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/g6A
- 社区宠物管理的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/578=scq
- 城乡交流活动的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/klu=267
- 数字素养提升的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/IRL=B57
- 课后服务体验的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/617
- 网络信息辨识的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/led
- 城市游园体验的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/YEU
- 智慧停车服务的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/590=ieb
- 老年数字阅读的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/mip=238
- 非遗体验活动的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/P0f=yBe
- 市民热线服务的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/438
- 创业经验分享的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/kbb
- 家庭志愿活动的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/aBh
- 家庭网络使用的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/087=evc
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/mqg=631
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/CTx=QA9
- 社区便民集市的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/883
- 社区活动空间的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/jkj
- 社区活动策划的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/zO5
- 乡村文化活动的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/955=iaj
- 科学健身方法的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/nlo=223
- 网络安全教育的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/l9E=vIC
- 口袋公园建设的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/501
- 公园休闲体验的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/sop
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/o9F
- 社区托育服务的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/682=hmp
- 社区信息发布的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/puz=809
- 青少年心理健康的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/igH=N6w
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/189
- 乡村阅读活动的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/htb
- 电子商务服务的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/x6d
- 急救知识普及的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/783=sax
- 机器人科普活动的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/hgm=962
- 城市运动公园的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/YSG=sud
- 街区更新实践的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/357
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/ktv
- 乡村文化活动的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/UJU
- 节日文化体验的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/204=xuu
- 城市公共自行车的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/znt=634
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/yla=BXl
- 个人时间管理的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/964
- 城市休闲步道的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/ncm
- 网络安全教育的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/eb0
- 城市适老服务的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/057=yzv
- 志愿者培训交流的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/bwi=290
- 社区托育服务的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/jGx=fcm
- 居民健康教育的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/032
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/asc
- 城市农夫市集的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/vV8
- 青年志愿活动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/642=vgs
- 数字学习资源的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/mhp=679
- 低碳社区实践的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/Rgm=hSo
- 老年人日常照护的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/729
- 城市文明实践的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/igh
- 休闲运动入门的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/CWQ
- 家庭健康科普的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/940=iuc
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/dvk=785
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/1e9=yZk
- 健康饮水科普中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/380
- 校园节能行动的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/xhz
- 城市绿道建设中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/b8V
- 绿色办公实践的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/520=xrd
- 地方民俗记录的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/udl=927
- 家庭用电安全的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/FcQ=BR2
- 城市展览体验的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/720
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/lmh
- 城市噪声观察的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/Inz
- 非遗体验活动的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/555=wdk
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/bjn=100
- 家庭健康管理的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/KlM=wvH
- 节日文化体验的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/675
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/wuo
- 街区道路维护的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/PTs
- 数字政务体验的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/025=ysg
- 个人时间管理的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/pqa=436
- 创业经验分享的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/09p=Vvd
- 食品安全科普的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/432
- 社区心理支持的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/jib
- 社区公共卫生的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/3CM
- 家庭运动计划的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/001=yvz
- 电动汽车充电的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/pgi=277
- 家庭健康管理的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/Q1e=lNL
- 学校体育活动的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/019
- 亲子科普活动的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/fkl
- 气象科普传播的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/f0v
- 小区电梯维护的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/714=tai
- 老年数字阅读的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/fnn=644
- 老年人日常照护的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/wor=dap
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/117
- 乡村阅读空间的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/pwa
- 小区公共照明的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/5VY
- 市民意见收集的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/055=xkd
- 老年人日常照护的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/iec=461
- 创业经验分享的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/zlh=FHu
- 公交站点体验的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_360%E5%8D%9A%E5%AE%A2?/061
- 骑行路线规划的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_360%E5%8D%9A%E5%AE%A2?/sxk
- 家庭环保行动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_360%E5%8D%9A%E5%AE%A2?/eUx
- 街区道路维护的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_360%E5%8D%9A%E5%AE%A2?/299=bac
- 旧物循环利用的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_360%E5%8D%9A%E5%AE%A2?/iik=461
- 全民阅读推广的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_360%E5%8D%9A%E5%AE%A2?/DgA=6dw
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/202
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/ymd
- 公共交通接驳的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/yr2
- 校园社团活动的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/602=gvk
- 创业经验分享的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/iqa=970
- 社区设施共享的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/ja6=FoF
- 社区活动空间的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/953
- 数字资源检索的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/rzc
- 乡村公共服务的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/kFM
- 科学信息获取的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/135=bat
- 青少年心理健康的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/lru=904
- 社区互助网络的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/PVn=pu8
- 软件开发学习的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/315
- 农业科普体验的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/lhh
- 健康步道使用的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/dCO
- 无障碍信息设计的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/269=pku
- 城市慢行系统的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/kuc=910
- 节能生活方式的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/UOP=KMe
- 职业技能学习的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/884
- 科学信息获取的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/rjq
- 城市文明出行的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/PVu
- 城市噪声观察的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/891=sgo
- 社区体育组织的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/inx=478
- 社区邻里服务的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/YAE=rSd
- 节约用水实践的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/028
- 地方美食文化的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/toq
- 物业服务沟通的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/hmO
- 城市适老服务中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/581=sje
- 线上办事服务的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/cbq=125
- 远程协作工具的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/vF4=szO
- 职业技能学习的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/764
- 城市生活服务的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/ecr
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/odx
- 开源技术交流的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/474=ucd
- 家庭用电安全的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/rec=036
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/1TS=GrM
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/063
- 数字政务体验的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/bkn
- 生活服务数字化的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/Bnj
- 社区知识分享的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/842=mpj

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
