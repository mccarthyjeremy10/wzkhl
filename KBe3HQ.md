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

- 儿童运动体验的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/lxu=539
- 公共场所导视的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/sjW=ZYb
- 基层医疗预约的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/715
- 节约用水实践的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/shg
- 网络安全教育的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/sC7
- 城市游园体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/769=ztl
- 公共空间照明中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/ere=663
- 公园亲子设施的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/yzU=nX9
- 社区协商议事的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/223
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/ukd
- 城市噪声观察的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/So9
- 街区更新实践的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/996=ixo
- 家庭照护支持的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/fni=001
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/Pmg=s98
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/043
- 社区花园共建的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/jbf
- 城市微更新实践中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/XGQ
- 社区绿色空间的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/864=pfs
- 公园无障碍服务的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/ryr=187
- 城市步行环境的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/9Gq=CNn
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/004
- 城市休闲步道的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/xcy
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/ezs
- 城市人文观察的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/588=osm
- 光伏知识科普的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/kgw=840
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/e3s=qIp
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/388
- 公交无障碍服务的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/awr
- 远程协作工具的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/jAd
- 城市步行友好的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/007=fhm
- 基层医疗预约的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/eqy=876
- 农业科普体验的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%94%90%E8%AF%84?/N9f=1pj
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/120
- 骑行路线规划的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/puw
- 健康步道使用的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/ABR
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/043=cen
- 青少年编程学习的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/mdw=372
- 城市骑行环境中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/UJt=yPc
- 社区宠物管理的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/112
- 社区法律科普中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/qdf
- 节能家电使用的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/znW
- 城市应急科普的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/598=efv
- 家庭用电安全的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/jzy=663
- 公益活动组织的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/FJb=2cj
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/878
- 老年人出行服务的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/lgt
- 数字政务体验的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/WbC
- 乡村教育资源的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/174=ibr
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/nmi=916
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/tsD=Sfo
- 气象科普传播的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/124
- 旧物循环利用的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/ldk
- 社区消防演练的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/oyJ
- 无障碍出行的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/662=jrg
- 生活垃圾回收的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/dqa=142
- 社会体育指导的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/GAG=Bli
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E8%AF%BB%E6%8A%A5?/253
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E8%AF%BB%E6%8A%A5?/mgz
- 家庭网络使用的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E8%AF%BB%E6%8A%A5?/8yX
- 家庭网络使用的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E8%AF%BB%E6%8A%A5?/402=lbm
- 绿色快递包装的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E8%AF%BB%E6%8A%A5?/ihu=346
- 消防知识宣传的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E8%AF%BB%E6%8A%A5?/2uH=vT8
- 人工智能科普的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/185
- 公共服务指南的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/lzf
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/kFU
- 城市公共空间的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/981=ylz
- 日常摄影记录的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/hon=745
- 街道综合服务的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/4Da=k0o
- 公共空间照明的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/168
- 家庭网络使用的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/oyv
- 节约用水实践的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/b3p
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/002=yfu
- 城市公共座椅的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/syt=286
- 公共服务咨询的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%B6%E7%94%B5?/Kg2=gZU
- 食品配送体验的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/468
- 城市建设科普的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/sfg
- 校园节能行动的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/GQ5
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/008=csk
- 社区宣传栏更新有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/fnr=587
- 城市地名文化的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/RC4=cEC
- 基层健康档案的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/766
- 在线教育体验的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/cja
- 老年学习活动的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/x9V
- 地方旅游导览的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/574=awo
- 社区文化节活动的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/xza=201
- 城市应急广播的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/lw6=WhU
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/439
- 城市住房服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/ykz
- 城市空气科普的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/X3i
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/338=lhm
- 租房信息服务的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/iof=402
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/Ajq=AmI
- 城市住房服务的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/626
- 家庭理财科普的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/kvy
- 社区活动报名的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/35M
- 城市公共饮水的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/787=nep
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/zmb=128
- 家庭健康科普的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/sN8=ExF
- 口袋公园建设的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/584
- 生成式工具使用的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/pit
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/y8m
- 公共服务预约的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/915=alv
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/ipr=763
- 数字便民地图的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/oRf=EJQ
- 基层服务创新的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/850
- 城市应急广播的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/tod
- 社区生活指南的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/eiI
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/453=qvu
- 城市公共厕所的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/nye=461
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/hpW=SjA
- 社区停车服务的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/947
- 乡村文化空间的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/ctt
- 校园社团活动的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/ZAY
- 公共空间照明的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/665=bvw
- 家庭科学教育的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/tyx=021
- 街区绿化养护的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/nfP=7du
- 社区花园共建的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/799
- 城市住房服务的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/zrb
- 家庭环保行动的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/aX5
- 智慧城市体验的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/195=ogv
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/pso=060
- 志愿服务平台的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/16T=JFs
- 社会体育指导的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/066
- 社区文化节活动的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/voy
- 科学运动指导的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/DBY
- 无障碍出行的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/884=qfz
- 科学教育活动的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/jdo=805
- 家庭运动计划的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/lK8=0qN
- 便民服务地图的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/944
- 基层服务创新的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/djz
- 周末休闲规划的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/9Z2
- 社区交通安全的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/274=axe
- 跨代沟通活动的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/mkk=019
- 气象科普传播的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/Mzs=eZx
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/950
- 数字阅读服务的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/cgg
- 社区协商议事的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/jQ7
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/363=qcd
- 社区活动策划的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/jfh=441
- 本地历史资料的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/jaj=TIQ
- 社区艺术活动的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/641
- 科学观察活动的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/wwv
- 传统节日科普的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/sWy
- 家庭网络使用的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/931=orm
- 休闲运动入门的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/eac=479
- 数字创作工具的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/3KT=S36
- 城市便民驿站的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/808
- 物业服务沟通的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/ozr
- 青少年户外教育的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/mxn
- 地方民俗记录的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/092=ezs
- 老年运动活动的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/pwp=978
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/Jzs=04T
- 乡村公共文化的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/651
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/uvk
- 机器人科普活动的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/dvJ
- 数字学习资源的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/829=nci
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/wrx=698
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%BD%AC%E8%BD%BD?/156=Hgg
- 社区学习活动的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%AE%B2%E5%9D%9B?/167
- 城市骑行环境的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%AE%B2%E5%9D%9B?/cxr
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%AE%B2%E5%9D%9B?/g7o
- 数字学习资源的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%AE%B2%E5%9D%9B?/724=ruq
- 居家防滑改造中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%AE%B2%E5%9D%9B?/zgx=630
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%AE%B2%E5%9D%9B?/SwJ=GbS
- 消防知识宣传的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/632
- 社区教育资源的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/sxf
- 开源技术交流的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/g1u
- 公共服务预约的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/737=pib
- 家庭食品保存的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/ngo=240
- 城市微更新实践的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/K01=HKh
- 社区绿色空间的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/875
- 居民健康教育的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/khk
- 数字公共文化的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/bOt
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/689=ttx
- 街头绿植养护的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/ffw=053
- 社区文化节活动的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/BcE=rl7
- 数字地图应用的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/196
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/udo
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/voK
- 公共设施维护的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/729=iai
- 远程协作工具的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/obc=935
- 城市可持续生活的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/fYi=S2p
- 青年志愿活动的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/126
- 小区公共照明的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/ufh
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/qfb
- 骑行路线规划的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/935=zxd
- 节约用水实践的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/bkr=137
- 社区共享书架的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/gzW=Gyr
- 节约用水实践的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/949
- 亲子科普活动的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/xoo
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/ILN
- 邻里共享空间的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/831=vxh
- 城乡公共服务中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/acg=425
- 职业技能学习的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/eZc=0Au
- 便民服务地图的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/102
- 城市文明出行的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/zhg
- 社区养老服务的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/wpQ
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/083=pgs
- 城市树木认养的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/han=848
- 家庭园艺实践的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/nst=AID
- 社区生活指南的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/813
- 绿色校园实践的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/hae
- 运动安全知识的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/AgS
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/298=sah
- 周末休闲规划的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/ajo=816
- 社区艺术活动的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/rJv=OJC
- 健康信息获取的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/115
- 机器人科普活动的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/pfm
- 校园社团活动的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/8Ff
- 个人数据管理的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/427=iqs
- 青少年编程学习中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/qry=297
- 地方戏曲体验的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/6Lw=XX2
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/711
- 城市便民驿站的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/fjc
- 公共空间导览的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/cVY
- 线上办事服务的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/820=bfv
- 小微企业服务的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/oeg=692
- 城市农夫市集的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/uCF=i0H
- 社区商业活力的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/265
- 安全出行教育的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/uqc
- 公共设施使用的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/LS4
- 数字政务体验的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/121=see
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/mhp=214
- 数字政务体验的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/kcz=Mod
- 公共服务沟通的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/267
- 市民意见收集的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/iry
- 智能手机助老的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/pN7
- 食品配送体验的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/959=zyc
- 公共卫生设施的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/uyx=835
- 科学信息获取的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/5ub=1dQ
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/661
- 非遗体验活动的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/elq
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/fnQ
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/086=jfd
- 家庭食品保存的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/vwv=575
- 社区文化传播的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/hHZ=TEZ
- 绿色快递包装的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/160
- 城市步行环境的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/lnt
- 数字艺术创作的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/fIg
- 生成式工具使用的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/503=ikl
- 数字创作工具的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/ook=740
- 安全出行教育的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/FId=NW3
- 在线学习体验的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/083
- 数字创意课程的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/isg
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/dDy
- 社区便民集市的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/793=iri
- 社区宠物管理的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/akd=287
- 社区托育服务的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/WYq=Aa9
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/770
- 公共场馆服务的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B8%BF%E5%88%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/fup

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
