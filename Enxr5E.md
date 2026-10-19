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

- 家庭阅读计划的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/rmm=595
- 图书借阅体验的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/s6V=u2d
- 社区停车服务的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/102
- 邻里共享空间的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/avn
- 线上阅读资源的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/aV0
- 乡村生活观察的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/228=rva
- 生活垃圾回收的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/seg=472
- 家庭健康科普的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/Pvr=1KN
- 机器人科普活动的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/987
- 地方美食文化的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/wir
- 网络安全教育的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/gd3
- 创业经验分享的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/747=gzr
- 开源技术交流的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/hka=705
- 社区防暑服务的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/wdy=tuh
- 公共空间照明的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/318
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/vcq
- 乡村公共服务的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/gCE
- 城市公共空间的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/614=ixl
- 数字创意课程的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/tnu=619
- 安全出行教育的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/1dS=x0T
- 新能源知识普及的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/476
- 城市农夫市集的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/nda
- 社区活动策划的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/jZC
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/119=wvt
- 公共服务评价的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/bri=200
- 科普展览体验的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/0h1=PcM
- 家庭教育交流的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/301
- 农产品品牌传播的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/ejd
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/BGW
- 城乡公共服务的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/843=ppq
- 数字素养提升中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/zts=033
- 农产品消费体验的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/N2R=jLD
- 社区互助网络的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/581
- 老年数字阅读的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/bkv
- 生活垃圾回收的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/fK9
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/420=nei
- 小区公共照明的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/vxw=131
- 儿童友好空间的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/N5w=9uu
- 社区活动空间的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/417
- 城市绿色交通中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/qso
- 城市休闲步道的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/aau
- 农贸市场环境的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/943=wry
- 本地消费场景的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/rpg=843
- 户外活动组织的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/ppR=iZj
- 智能家居应用的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/583
- 社区商业活力的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/ylr
- 公园休闲体验的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/inK
- 乡村电商实践的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/584=ruh
- 城市文明出行的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/jlc=379
- 家庭运动计划的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/AsA=cOJ
- 公共场所导视的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/952
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/yvu
- 机器学习入门的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/exx
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/707=gue
- 乡村公共文化的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/pzy=886
- 数字支付体验的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E7%AD%96?/orJ=qgU
- 社区科普课堂的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/757
- 公共空间休憩的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/xie
- 物业服务沟通的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/ljQ
- 旧物循环利用的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/531=mcz
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/lvd=569
- 旧物循环利用的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/8A3=HGk
- 读书会组织的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/994
- 社区文化节活动的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/hcb
- 社区停车服务的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/tJQ
- 新能源出行的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/826=asq
- 线上阅读资源的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/rfb=612
- 社区文化传播的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/91A=DoE
- 文化场馆预约的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/918
- 社区老年食堂的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/hub
- 传统手工艺体验的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/FOt
- 老年学习活动的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/634=xww
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/jtc=400
- 低碳社区实践的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/uQ0=SGw
- 城乡交通衔接的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/703
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/azt
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/tQ5
- 休闲运动入门的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/291=veq
- 老年人日常照护的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/mgc=193
- 社区协商议事的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/xNh=SeX
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/599
- 开源技术交流的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/nja
- 节能生活方式的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/wwm
- 节假日出行安排的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/654=ifj
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/kxo=620
- 社区阅读服务的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/TtC=Ek3
- 数字艺术创作的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/382
- 学校体育活动的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/jxb
- 地方民俗记录的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/RKJ
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/095=rif
- 软件开发学习的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/fed=649
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/ceb=ubf
- 社区消防演练的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/878
- 便民服务窗口的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/zox
- 软件开发学习的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/Bmw
- 在线教育体验的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/515=phy
- 灵活就业交流中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/fwq=440
- 基层服务创新的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/P20=k6o
- 社区学习活动的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/566
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/src
- 城市体育设施的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/byK
- 公共交通信息服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/120=sjh
- 公共服务评价的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/syf=784
- 文化场馆预约的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%BA%94%E7%99%BE%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/gts=mCd
- 城市文明实践的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/598
- 城市基础设施的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/itk
- 公共空间休憩的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/uaE
- 社区家校合作的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/754=iss
- 急救知识普及的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/wjw=665
- 智慧城市体验的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/lqo=Grr
- 家庭安全提示的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_360%E5%85%AC%E7%9B%8A?/517
- 新能源知识普及的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_360%E5%85%AC%E7%9B%8A?/wdd
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_360%E5%85%AC%E7%9B%8A?/JEz
- 儿童运动体验的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_360%E5%85%AC%E7%9B%8A?/585=axk
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_360%E5%85%AC%E7%9B%8A?/mcj=289
- 家庭教育交流的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_360%E5%85%AC%E7%9B%8A?/jeN=pKk
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/033
- 绿色快递包装的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/hqp
- 电子商务服务的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/o16
- 城市建设科普的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/455=tmf
- 居民健康教育的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/tev=717
- 数字政务体验的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/iB1=tCh
- 社区故事采集的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/823
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/qiw
- 无障碍出行的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/517
- 农贸市场环境的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/882=mgm
- 城市公共标识的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/uvi=335
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A4%BE%E5%8C%BA?/2mb=Qyq
- 数字创作工具的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/696
- 社区商业活力的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/ood
- 数字创作工具的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/0UJ
- 社区停车服务的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/422=ula
- 公园休闲体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/obz=867
- 家庭饮食安排的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/bc8=Fia
- 城市生活记录的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/430
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/ueb
- 全民健身活动的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/XQs
- 家庭消费规划的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/990=jrg
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/nip=691
- 城市绿道建设的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/ZnS=zoo
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/944
- 小区电梯维护的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/arn
- 城市文明实践的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/M9Y
- 个人数据管理的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/854=oze
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/awm=468
- 老旧小区改造的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/crj=RYg
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/640
- 社区法律科普的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/nxo
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/S5Q
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/587=bsa
- 农业科普体验的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/jll=574
- 公共服务数字化的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/RTk=W0F
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/257
- 小区电梯维护的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/avz
- 终身学习资源的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/tDX
- 低碳社区实践的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/791=qud
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/qao=567
- 家庭消费规划的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/K7Q=bZm
- 科普展览体验的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/138
- 骑行路线规划的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/ado
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/Xnz
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/227=jci
- 生活技能分享的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/ozh=257
- 公共空间导览的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/ymU=SDO
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/570
- 城市文化路线的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/sdk
- 校园阅读活动的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/2j6
- 乡村公共文化的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/279=bpl
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/zlg=238
- 家庭理财科普的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/JuX=qEY
- 农村环境治理的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/126
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/dmq
- 校园阅读活动的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/EtQ
- 老年学习活动的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/170=tjw
- 邻里互助活动的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/qcl=469
- 社区互助网络的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90-APP_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/sWK=8Hd
- 儿童运动体验的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/206
- 数字素养提升的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/udw
- 城市公共标识的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/J8S
- 社区休闲设施的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/144=mhh
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/xnz=895
- 城市人文观察的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E4%B8%87%E5%AE%B6%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/Buq=ReM
- 安全出行教育的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/987
- 图书馆数字服务的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/lvz
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/gSd
- 城市共享单车的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/236=wct
- 生成式工具使用的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/hgw=203
- 公共服务沟通的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/9IW=zXi
- 个人时间管理的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/354
- 城市便民驿站的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/xth
- 环境教育课程的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/N17
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/550=hcb
- 社区文化节活动的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/tbr=459
- 基层健康档案的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/lNh=GVS
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/839
- 开放数据应用的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/keg
- 社区安全巡查的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/kf9
- 新能源出行的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/300=zyl
- 社区法律科普的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/rmo=588
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/iZW=4z3
- 数字地图应用的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/048
- 老年运动活动的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/rvb
- 家庭网络使用的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/7od
- 社区艺术活动的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/859=wdd
- 社区快递服务的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/yin=678
- 低碳社区实践中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%AE%B6%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Krd=JQg
- 智慧城市体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/404
- 数字设备回收的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/bnn
- 城市共享单车的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/a5P
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/815=ypv
- 公益活动组织的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/qbi=739
- 社区信息发布的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/psn=Eom
- 便民信息查询的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/651
- 在线学习体验的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/yul
- 乡村阅读空间的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/OKG
- 数字课堂应用的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/683=gvi
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/hxe=282
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/pUW=Az8
- 乡村文化活动的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%AE%B6%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/811
- 社区公共卫生的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%AE%B6%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/siq
- 社区设施共享的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%AE%B6%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/eCM
- 机器学习入门的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%AE%B6%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/483=rjm
- 科学运动指导的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%AE%B6%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/iff=145
- 安全出行教育的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%AE%B6%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/iAv=Fls
- 周末休闲规划的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/089
- 绿色出行服务的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/sce
- 图书借阅体验的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/QmO
- 校园安全教育的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/309=ncv
- 科学观察活动的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/dyo=014
- 网络安全教育的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B8%87%E5%AE%B6%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/bjb=Y5E
- 社区休闲设施的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/664
- 乡村教育资源的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/xev
- 开源技术交流的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/Usu
- 文明养宠科普的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/693=dmj
- 环境监测科普的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/xtr=786
- 老年人出行服务的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/Ywq=cME
- 家庭急救准备的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/709
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/gye
- 社区菜市场服务的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/zNj
- 社区休闲设施的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/080=ycd
- 社区消防演练的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/uxo=730
- 亲子科普活动的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/ikv=EgF
- 光伏知识科普中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/490
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/vpc
- 城市共享单车的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/nog
- 地方文化传播的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/122=yvd
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/uxn=929
- 邻里互助活动的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/oCM=zgm
- 气象科普传播的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/955
- 社区垃圾回收的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/lxm

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
