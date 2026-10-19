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

- 公共健身器材的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%AD8_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/tbv=742
- 周末休闲规划的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%B4%AD8_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/qJw=Cb0
- 应急物资管理的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9EIV_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/300
- 老年人出行服务的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9EIV_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/vqk
- 家庭健康科普的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9EIV_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/0B9
- 家庭照护支持的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9EIV_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/436=tzo
- 城市人文观察的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9EIV_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/lxu=439
- 乡村公共文化的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9EIV_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/INE=3W1
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/220
- 数字创作工具的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/guy
- 家庭阅读计划的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/7nF
- 社区活动空间的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/324=adv
- 社区便利生活的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/kls=733
- 青年就业服务中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/vN8=XC8
- 城市建设科普的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/297
- 机器学习入门的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/ful
- 社区环保活动的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/yST
- 社区活动策划的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/204=ykc
- 学校食育活动的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/msg=557
- 青少年心理健康的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/zdD=n5C
- 本地旅行体验的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_360%E9%A3%9F%E5%93%81?/529
- 社会体育指导的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_360%E9%A3%9F%E5%93%81?/bjd
- 城市适老服务的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_360%E9%A3%9F%E5%93%81?/TlZ
- 青年志愿活动的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_360%E9%A3%9F%E5%93%81?/247=bst
- 城市公共自行车的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_360%E9%A3%9F%E5%93%81?/lwg=948
- 城市展览体验的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_360%E9%A3%9F%E5%93%81?/owz=9r8
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/662
- 数字阅读服务的学习资源整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/vee
- 信息无障碍体验的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/pN0
- 智慧城市体验的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/990=tgs
- 公共交通接驳的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/taf=310
- 社区知识分享的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/l6U=P8r
- 社区文化节活动的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/433
- 地方戏曲体验的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/xle
- 公共场所导视的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/Jaz
- 社区活动策划的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/658=zop
- 安全出行教育的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/gpt=076
- 网络信息辨识中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/amb=yLR
- 环境教育课程的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/798
- 青年就业服务的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/dwq
- 城市农夫市集的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/D3S
- 公共健身器材的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/818=ybm
- 街头绿植养护的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/gme=020
- 青年志愿活动中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/Vfg=EMn
- 骑行路线规划的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/474
- 远程协作工具的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/qtt
- 数字设备回收的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/gJt
- 数字生活课堂的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/799=vjy
- 数字设备回收的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/xif=343
- 全民阅读推广中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/knh=Q5c
- 智慧停车服务的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/333
- 城市文化路线的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/zpj
- 家庭健康管理中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/rio
- 公共交通接驳的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/826=tuy
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/gbz=510
- 数字便民地图的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/C6j=OqG
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/373
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/whw
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/Bom
- 社区垃圾回收的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/957=eca
- 公交无障碍服务的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/iwv=580
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/23f=fdH
- 社区活动策划的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_360%E8%AE%B2%E5%9D%9B?/020
- 社区信息发布中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_360%E8%AE%B2%E5%9D%9B?/xth
- 老年学习活动的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_360%E8%AE%B2%E5%9D%9B?/wzW
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_360%E8%AE%B2%E5%9D%9B?/665=cpl
- 家庭食品保存的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_360%E8%AE%B2%E5%9D%9B?/ytb=208
- 城市骑行环境的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_360%E8%AE%B2%E5%9D%9B?/Gt3=D2L
- 机器人科普活动的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/135
- 生活服务数字化的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/keq
- 居家适老化改造的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/vLd
- 志愿服务平台的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/129=osb
- 城市体育设施中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/dvr=860
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/gHh=ViW
- 家庭防灾准备的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/386
- 个人数据管理的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/peb
- 乡村公共服务的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/31L
- 节能生活方式的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/133=diz
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/ltc=127
- 城市运动公园的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/tXe=6HL
- 校园社团活动的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/086
- 公交站点体验的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/ixu
- 安全出行教育的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/5HG
- 邻里互助活动的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/007=oyu
- 乡村生态旅游的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/uwp=673
- 终身学习资源的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/Bkf=oCY
- 公共场馆服务的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/494
- 社区环保活动的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/lfr
- 科学信息获取的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/uTl
- 城市慢行系统的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/485=yhs
- 数字地图应用的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/cyt=578
- 城市运动公园的线下体验记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/dMv=0Ah
- 终身学习资源的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/492
- 城市慢行系统的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/grt
- 社区生活指南的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/B8W
- 家庭环保行动的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/039=xng
- 社区家校合作的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/bls=906
- 家庭环保行动的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/MIH=TL3
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/545
- 在线学习体验的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/cya
- 医院导诊服务中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/0GK
- 公共服务沟通的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/153=gvp
- 食品配送体验的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/lge=710
- 数字创意课程的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/Kxz=aiX
- 休闲运动入门的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/047
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/kgn
- 社区家政服务的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/GxO
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/090=klq
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/koa=250
- 节能生活方式的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/9zt=JOv
- 城市体育设施的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/485
- 社区信息发布的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/abg
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/Iew
- 城市树木认养的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/194=qba
- 儿童友好空间的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/bvh=576
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/viQ=xjD
- 社区邻里服务的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/301
- 食品安全科普的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/rrs
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/2AN
- 绿色校园实践的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/347=tog
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/iqj=143
- 社区读书角建设的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/ZCg=9eF
- 家庭阅读计划的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_360%E5%86%9C%E4%B8%9A?/551
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_360%E5%86%9C%E4%B8%9A?/cfm
- 便民维修服务的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_360%E5%86%9C%E4%B8%9A?/9dn
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_360%E5%86%9C%E4%B8%9A?/619=nsg
- 社区便民集市的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_360%E5%86%9C%E4%B8%9A?/axo=238
- 文化讲座服务的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_360%E5%86%9C%E4%B8%9A?/3V3=KZD
- 食品配送体验的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/154
- 农业科普体验的服务细节记录 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/iwb
- 城市水环境观察的活动策划思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/WkI
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/953=rlq
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/qmg=447
- 运动安全知识的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/waN=cqu
- 社区艺术活动的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/664
- 乡村公共阅读的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/ksc
- 乡村教育资源的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/SmQ
- 城市运动公园的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/964=zzi
- 城市运动公园从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/etf=437
- 绿色办公实践的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/YEp=iOK
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/954
- 终身学习资源的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/kzk
- 城市树木认养的基础设施观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/lJA
- 小区停车协商的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/313=vnp
- 家庭用电安全的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/nka=140
- 租房信息服务的参与方式与路径 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/hkI=L8b
- 家庭节能设备的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/585
- 乡村文化活动的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/wmg
- 小区电梯维护的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/3pV
- 城市便民驿站中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/999=rty
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/hmb=004
- 科技馆参观体验的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/WnY=B7Q
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/326
- 街道综合服务的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/dgg
- 城市体育设施的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/gO9
- 旧物循环利用的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/122=kwe
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/djb=243
- 公共空间休憩的数字化应用观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/lQK=xpv
- 节假日出行安排的入门知识整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/182
- 社会体育指导的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/tir
- 老年学习活动的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/zl1
- 社区阅读服务的资源整合思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/597=pto
- 城乡公共服务的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/tav=442
- 城市体育设施的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/qcy=gaE
- 公共空间照明的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/516
- 乡村文化活动的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/mlp
- 人工智能科普的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/C2t
- 农产品品牌传播的流程优化思路 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/385=cli
- 数字生活课堂的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/zyc=414
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%89%B4?/8OD=wYD
- 网络信息辨识的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/413
- 城市公共厕所的服务质量观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/gbo
- 家庭环保行动的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/CHm
- 青少年科普实践的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/547=hbm
- 社区体育组织的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/kxm=822
- 公共服务评价的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/jlE=ECT
- 电子商务服务中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/440
- 公共空间休憩的常见问题梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/nww
- 城乡交流活动中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/Bt4
- 公交站点体验的适老服务细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/787=hfc
- 光伏知识科普的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/dnn=024
- 城乡交流活动的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/Yz8=hv1
- 街道综合服务的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/152
- 电动汽车充电的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/hag
- 家庭阅读计划的服务体验观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/ny1
- 口袋公园建设的日常实践笔记 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/101=nwh
- 家庭园艺实践的社区行动案例 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/zga=362
- 学校体育活动的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/azf=pNo
- 软件开发学习的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/662
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/jwx
- 社区共享书架的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/nrC
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/377=siy
- 社区停车服务的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/rmt=102
- 公共场所导视的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/qgV=mfX
- 家庭节能实践的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/954
- 城市生活服务的基础知识问答 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/cec
- 节能家电使用的日常使用指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/CSK
- 数字阅读服务的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/616=jrd
- 便民维修服务的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/fat=128
- 社区安全巡查的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/JZ2=c9x
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/569
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/dvq
- 街头绿植养护的组织方法与经验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/Own
- 城市社区治理的便民做法梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/147=lgs
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/jjd=267
- 读书会组织的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/RG6=XVc
- 职业技能学习的协作机制梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/102
- 休闲运动入门的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/vwh
- 社区家校合作的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/Iwl
- 街头绿植养护的社区参与观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/584=atg
- 校园节能行动的使用门槛与改进 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/gfm=211
- 城市农夫市集的常见误区提醒 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/7bn=3NP
- 邻里互助活动的儿童友好细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/028
- 社区交通安全的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/iwj
- 城市步行友好的行动步骤参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/3kZ
- 公交无障碍服务的长期维护要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/975=zzm
- 读书会组织的便利性观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/txb=849
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/pcq=rrH
- 公共服务咨询的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/524
- 公共设施维护的公共信息获取方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/kko
- 节能家电使用的绿色实践方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/Ber
- 公共交通信息服务的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/243=ljy
- 社区互助网络的服务范围梳理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/ntf=925
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/2Dd=SZZ
- 家庭健康管理的执行流程参考 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/335
- 青少年户外教育中的沟通与协作 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/fon
- 健康步道使用中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/th7
- 消防知识宣传的家庭参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/415=csq
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/dcd=586
- 数字学习资源的实用信息清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/yU8=1pw
- 城市水环境观察的协商参与方式 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/192
- 社区教育资源的日常记录与分享 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/npa
- 城市文化路线的持续改进方向 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/qiJ
- 文明养宠科普的空间设计要点 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/443=fyj
- 机器学习入门的设施维护观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/act=523
- 信息无障碍体验的服务信息整理 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/gJr=iz1
- 骑行路线规划的资源利用方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/914
- 软件开发学习的便捷程度观察 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/nla
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/Jok
- 城市水环境观察的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/871=hry
- 社区托育服务的空间使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/lrb=904
- 乡村产业科普的公共参与指南 |来源：https://github.com/perrymichelle1568/aayd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/zpi=IdZ
- 安全出行教育的日常管理方法 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/302
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/ljb
- 社区活动策划的家庭实践清单 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/93v
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/630=zxg
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/svj=910
- 校园阅读活动的安全使用提示 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/UO1=13m
- 数字设备回收的活动体验回顾 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/647
- 数字支付体验中的几个关键细节 |来源：https://github.com/perrymichelle1568/aayd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/obo

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
