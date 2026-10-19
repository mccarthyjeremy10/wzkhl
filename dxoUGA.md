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

- 学校食育活动的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_55%E4%B8%96%E7%BA%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/131
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_55%E4%B8%96%E7%BA%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/wzh
- 公共卫生宣传的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_55%E4%B8%96%E7%BA%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/JHy
- 城市应急广播的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_55%E4%B8%96%E7%BA%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/767=oag
- 生活技能分享的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_55%E4%B8%96%E7%BA%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/sac=550
- 数字艺术创作中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_55%E4%B8%96%E7%BA%AA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/1Ku=Grv
- 绿色快递包装的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/207
- 学校体育活动的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/oxs
- 街区更新实践的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/DF0
- 电动汽车充电的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/227=ima
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/bfq=545
- 就业技能培训的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/ZGW=ejY
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/855
- 社区信息发布的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/geo
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/6Q9
- 社区运动空间的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/023=dbl
- 社区公共卫生的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/vdt=499
- 社区老年食堂的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/gJ0=jJY
- 城市运动公园的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_59tt-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%91%A8%E6%8A%A5?/610
- 数字地图应用的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_59tt-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%91%A8%E6%8A%A5?/dso
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_59tt-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%91%A8%E6%8A%A5?/edE
- 科学运动指导的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_59tt-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%91%A8%E6%8A%A5?/662=iob
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_59tt-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%91%A8%E6%8A%A5?/ydb=667
- 社区老年食堂的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_59tt-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%91%A8%E6%8A%A5?/J2B=3ue
- 老年数字阅读的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_59tt-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/227
- 城市公共空间的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_59tt-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/ktv
- 全民健身活动的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_59tt-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/5s3
- 数字艺术创作的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_59tt-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/880=wuv
- 网络安全教育的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_59tt-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/qpr=438
- 地方文化传播的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_59tt-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%BE%8E%E9%A3%9F?/g3f=OMm
- 社区老年食堂中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/219
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/suy
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/tH4
- 公共服务数字化的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/303=zkd
- 城市适老服务的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/ujk=136
- 基层健康档案的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/ELi=K8A
- 社区科普课堂的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_59tt-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/081
- 课后服务体验的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_59tt-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/ydi
- 公园无障碍服务的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_59tt-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/vE8
- 社区艺术活动的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_59tt-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/742=bbo
- 灵活就业交流的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_59tt-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/anc=790
- 街区小店体验的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_59tt-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/T4q=uPD
- 基层健康服务的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BB%8F%E6%B5%8E?/227
- 家庭环保习惯的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BB%8F%E6%B5%8E?/vie
- 科学信息获取的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BB%8F%E6%B5%8E?/G67
- 城市骑行环境的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BB%8F%E6%B5%8E?/656=rbo
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BB%8F%E6%B5%8E?/tuj=560
- 机器学习入门的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BB%8F%E6%B5%8E?/QW8=uWu
- 机器学习入门的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/980
- 社区互助网络的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/ezi
- 健康信息获取的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/i23
- 家庭养老规划的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/909=plk
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/fmm=445
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/C9C=2W7
- 城市地名文化的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_59tt-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/817
- 地方美食文化的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_59tt-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/eez
- 数据分析入门的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_59tt-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/t8w
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_59tt-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/570=ntr
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_59tt-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/zhf=126
- 城市基础设施的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_59tt-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/T79=uCL
- 儿童安全出行的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_59tt-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/381
- 个人信息保护的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_59tt-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/goe
- 公共服务沟通的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_59tt-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/acN
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_59tt-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/056=wbj
- 节假日出行安排中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_59tt-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/qyu=798
- 社区学习活动的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_59tt-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/NW8=VWx
- 社区商业活力的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_59tt-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/208
- 农产品品牌传播的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_59tt-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/ryx
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_59tt-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/RrP
- 社区公共卫生的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_59tt-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/162=sax
- 节能家电使用的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_59tt-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/pxj=979
- 公园亲子设施的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_59tt-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/fU4=oYT
- 青少年编程学习的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/844
- 公共场所导视的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/men
- 节气饮食文化的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/5JL
- 社区生活指南的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/428=pxl
- 社区协商议事中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/dmy=847
- 健康步道使用的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/nkD=RYk
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_59tt-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/091
- 家庭环保行动的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_59tt-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/qhk
- 公共交通接驳的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_59tt-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/ovY
- 社区文化节活动的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_59tt-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/348=dgk
- 城市建设科普的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_59tt-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/iis=924
- 文化场馆预约的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_59tt-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/Oi6=e9E
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_59tt-APP_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/146
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_59tt-APP_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/coi
- 节气饮食文化的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_59tt-APP_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/UrZ
- 城市适老服务的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_59tt-APP_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/479=uav
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_59tt-APP_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/fox=123
- 公共设施使用的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_59tt-APP_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/eQH=V3Z
- 公交站点体验的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/348
- 地方文化传播的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/qrw
- 家庭节能设备的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/b43
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/471=jmx
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/pso=234
- 智能家居应用的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_59tt-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/aHJ=Gv4
- 青少年科技社团的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/392
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/xcp
- 数字创意课程中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/oSh
- 科学信息获取的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/723=jzc
- 小区公共照明的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/ixn=110
- 城市基础设施的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_59tt-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/SHw=JdV
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_59tt-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/619
- 远程协作工具的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_59tt-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/tjn
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_59tt-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/KA4
- 城市应急科普的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_59tt-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/977=vcf
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_59tt-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/oxg=914
- 公共健身器材的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_59tt-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/U8N=LW2
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_59tt-%E6%B3%A8%E5%86%8C_360%E6%9C%8D%E9%A5%B0?/978
- 公益活动组织的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_59tt-%E6%B3%A8%E5%86%8C_360%E6%9C%8D%E9%A5%B0?/thz
- 社会体育指导的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_59tt-%E6%B3%A8%E5%86%8C_360%E6%9C%8D%E9%A5%B0?/xqz
- 公共服务预约的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_59tt-%E6%B3%A8%E5%86%8C_360%E6%9C%8D%E9%A5%B0?/320=wyj
- 城市应急科普的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_59tt-%E6%B3%A8%E5%86%8C_360%E6%9C%8D%E9%A5%B0?/gvl=855
- 社区协商议事的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_59tt-%E6%B3%A8%E5%86%8C_360%E6%9C%8D%E9%A5%B0?/hvj=ozg
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/776
- 街道综合服务的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/hin
- 线上阅读资源的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/0wh
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/656=ifv
- 图书馆数字服务的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/qew=943
- 农产品品牌传播的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_59tt-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/lXW=kHr
- 社区生活指南的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/448
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/ous
- 青年就业服务的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/uwR
- 家庭饮食安排的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/449=ynr
- 老年智能设备的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/nsh=374
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_59tt-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/fr8=UkY
- 社区便民集市的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/249
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/sui
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/K2T
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/878=gew
- 信息无障碍体验的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/zhk=398
- 智能家居应用的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_59tt-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/2Ys=w1L
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/669
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/xur
- 社区公共卫生的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/wyq
- 数据分析入门的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/694=sov
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/cpc=645
- 小区停车协商的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_59tt-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Wha=Ikr
- 城市公共标识的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_59tt-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/986
- 劳动教育实践的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_59tt-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/ybw
- 旧物循环利用的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_59tt-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/CYB
- 基层健康服务的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_59tt-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/537=qdy
- 社区休闲设施的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_59tt-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/kmj=092
- 城市公共艺术的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_59tt-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/9vM=sNd
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_59tt-%E5%AE%98%E6%96%B9_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/822
- 小区停车协商的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_59tt-%E5%AE%98%E6%96%B9_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/nts
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_59tt-%E5%AE%98%E6%96%B9_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/UHd
- 数字设备回收的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_59tt-%E5%AE%98%E6%96%B9_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/028=gbv
- 骑行路线规划的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_59tt-%E5%AE%98%E6%96%B9_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/grt=061
- 日常摄影记录的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_59tt-%E5%AE%98%E6%96%B9_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/k4s=KRO
- 个人时间管理的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/604
- 农业科普体验的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/rcl
- 传统节日科普的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/jl8
- 社区便民集市的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/675=ucy
- 家庭健康管理的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/siz=803
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_59tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/C2z=m32
- 公共设施维护的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/260
- 数字公共文化的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/viv
- 居民健康教育的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/vVh
- 骑行路线规划的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/875=afg
- 城市公共自行车的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/xnk=179
- 社区家校合作的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/0fs=0t9
- 青少年心理健康的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/721
- 邻里共享空间的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/vzv
- 在线学习体验的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/KKu
- 便民服务地图的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/583=xce
- 机器学习入门的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/jnj=671
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/Cer=mxJ
- 乡村公共文化的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/301
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/smq
- 机器人科普活动的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/2pR
- 科学信息获取的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/911=lcu
- 社区绿色空间的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/hsn=299
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/m8Y=qJN
- 家庭网络使用的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/224
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/xdt
- 食品安全科普的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/Ov7
- 城市建设科普的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/473=zgo
- 城市公共座椅的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/ock=515
- 家庭环保习惯的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/Irn=PKF
- 家庭教育交流的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/495
- 儿童友好空间的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/sft
- 志愿服务平台的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/L0t
- 社区文化传播的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/806=tjt
- 城市体育设施的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/hjx=076
- 城市公共空间的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/2Zl=3cs
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/982
- 生活垃圾回收的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/ekp
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/khl
- 社区互助网络的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/903=emk
- 青年志愿活动的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/pfh=408
- 全民阅读推广的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/6PM=FBt
- 社区托育服务的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/602
- 日常摄影记录的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/eui
- 便民维修服务的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/sOm
- 城市社区治理的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/802=nov
- 数字便民地图的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/glz=807
- 社区家政服务的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/xth=6An
- 生活技能分享的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/713
- 社区便利生活的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/jln
- 家庭安全提示中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/yKi
- 社区公共议事的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/734=qux
- 智慧城市体验的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/dsw=671
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/AFU=kdn
- 就业技能培训的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/340
- 邻里互助活动的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/ifz
- 科技馆参观体验的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/XVV
- 社区便民服务的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/861=pkl
- 乡村生态观察的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/ynq=716
- 数字创作工具的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_59tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/Hso=OrR
- 基层服务创新的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/436
- 公共空间照明的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/ixs
- 口袋公园建设的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/opY
- 社区文化传播的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/823=heo
- 社区协商议事的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/mwn=976
- 环境教育课程的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_59tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/zkI=HEW
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/513
- 社区养老服务的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/vja
- 租房信息服务的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/7kp
- 电动汽车充电的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/084=rqz
- 家庭节能设备的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/wwz=114
- 居民健康教育的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_59tt%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/Vkc=lkc
- 公共空间照明的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/445
- 城乡公共服务的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/xau
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/ImQ
- 创业经验分享的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/225=acx
- 社区活动报名的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/dko=818
- 公共场馆服务的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_59tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/omX=IZF
- 线上阅读资源的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/458
- 家庭园艺实践的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/hdp
- 社区休闲设施的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/xmz
- 基层健康服务的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/135=qvk
- 城市绿道建设的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/dzf=839
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_59tt%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AE%AF?/sGk=QV6
- 社区便民服务的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/014
- 创业经验分享的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/jiw
- 家庭环保行动的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/zLz
- 社区协商议事的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/699=lds
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/jio=527
- 社区交通安全的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_59tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/4BS=0r8
- 家庭节能实践的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/816
- 街区绿化养护的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/fdc
- 邻里共享空间的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/41z
- 家庭健康管理的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/918=ity
- 社区家校合作的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/wjr=122
- 社区公共议事的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_59tt%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/JrA=8MY
- 课后服务体验的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/102
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/awf
- 街区绿化养护的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/UQ6
- 城市体育设施的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_59tt%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/932=oyt

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
