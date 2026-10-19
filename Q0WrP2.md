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

- 社区消防演练的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/506
- 公共空间安全的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/waz
- 乡村公共服务的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/271
- 公共空间安全的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/079=plh
- 节日文化体验的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/egb=331
- 城市文明实践的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/g2q=Kvv
- 周末休闲规划的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/333
- 青年志愿活动的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/yfj
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/reV
- 家庭健康管理的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/485=pgg
- 软件开发学习的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/kqw=457
- 环境教育课程的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/kdL=Y1g
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/221
- 基层健康服务的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/ihu
- 乡村产业科普的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/jhi
- 软件开发学习的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/558=lfb
- 新能源知识普及的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/kdh=112
- 数字设备回收的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/yv7=mjV
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/931
- 健康饮水科普的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/pid
- 老年运动活动的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/Cui
- 无障碍信息设计的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/767=pai
- 公共设施使用的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/whm=046
- 家庭科学教育的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/NVS=uTk
- 城市慢行系统的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/850
- 社区手工活动的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/gfa
- 青年就业服务的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/psM
- 社区科普课堂的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/605=rhl
- 通勤路线规划的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/oow=855
- 日常摄影记录的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/gRG=qaW
- 城市可持续生活的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/784
- 数字创作工具的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/smg
- 城市慢行系统的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6Ym
- 数字政务体验的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/077=oku
- 家庭教育交流的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vap=901
- 社区便民服务的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/UT9=9M1
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/232
- 社区防暑服务的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/afy
- 数字艺术创作的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/1FG
- 城市休闲步道的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/926=lzh
- 社区消防演练的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/dzk=228
- 家庭健康管理中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/WFk=GeV
- 社会体育指导的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/368
- 药品使用科普的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/beq
- 校园节能行动的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/Syt
- 便民维修服务的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/686=khb
- 乡村生活观察的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/mhk=060
- 数据分析入门的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/KNG=FAR
- 社区艺术活动的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/284
- 城市文明出行的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/gls
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/5Im
- 社区阅读服务的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/063=qaf
- 家庭急救准备的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/rza=301
- 本地历史资料的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/nFb=eIW
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/393
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/eue
- 家庭急救准备的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/ADn
- 地方旅游导览的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/214=ate
- 社区阅读服务的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/wsr=890
- 职业技能学习的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/pgh=YiA
- 儿童户外活动的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/564
- 老年人文化生活的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/rwy
- 市民热线服务的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/7YD
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/581=kaa
- 地方民俗记录的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/byh=145
- 个人信息保护的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/AEl=Av7
- 城市休闲步道的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/497
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/lnz
- 社区家政服务的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/j3u
- 地方美食文化的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/485=aur
- 劳动教育实践的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/goz=141
- 家庭用电安全的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/wgC=hLz
- 开源技术交流的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/499
- 绿色校园实践的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/qpx
- 城市噪声观察的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/agk
- 社区运动空间的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/487=vhs
- 公共服务数字化的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/omf=875
- 社区体育组织的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/n27=ok6
- 数据分析入门的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/482
- 乡村电商实践的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/mxv
- 城市地名文化的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/vV3
- 公共交通接驳的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/958=lml
- 开放数据应用的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fmd=857
- 灵活就业交流的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/3Yz=K96
- 校园安全教育的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/111
- 健康饮食教育的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/zfw
- 安全出行教育的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/xPE
- 公益活动组织的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/878=ibk
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/jnr=108
- 社区公共卫生的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/4wQ=QMO
- 文明养宠科普的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1?/035
- 市民热线服务的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1?/uoc
- 城市共享单车的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1?/De3
- 城市夜间生活的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1?/489=bns
- 户外活动组织中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1?/vgj=871
- 乡村生态观察的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1?/99k=HCy
- 公共交通接驳的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/956
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/wdo
- 科学观察活动的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/TpN
- 生成式工具使用的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/837=udn
- 社区手工活动中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/zdm=851
- 智慧停车服务的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/TBW=s7Q
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/934
- 公共卫生宣传的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/ddz
- 社区协商议事的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/Dd1
- 乡村文化空间的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/883=wov
- 人工智能科普的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/rsx=803
- 家庭环保行动的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%BB%8F%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/sRy=N3x
- 农村环境治理的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/914
- 农业科普体验的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/pds
- 农产品品牌传播的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/ge2
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/149=edn
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/nwi=813
- 便民信息查询的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%8C%BB%E8%8D%AF?/QLm=KBP
- 城市空气科普的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/037
- 公共卫生宣传的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/mzk
- 社区便民服务的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/dKZ
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/236=dvs
- 信息无障碍体验的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/gjf=986
- 乡村文化空间的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/oiD=UWC
- 社区设施共享中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/253
- 无障碍信息设计的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/kiq
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/qTK
- 社区宠物管理的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/385=axb
- 城市公共艺术的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/rll=188
- 健康信息获取的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%B0%E8%AF%BB?/wPp=Ekk
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/152
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/pfm
- 校园社团活动的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/p1n
- 公共交通信息服务的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/825=wxk
- 数字学习资源的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/myb=641
- 城市应急科普的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/zom=EeX
- 数字档案服务的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/877
- 节约用水实践的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/ula
- 社区休闲设施的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/tYu
- 邻里互助活动的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/537=ypi
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/kwa=621
- 节气饮食文化的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9B%AD%E8%89%BA?/88W=4ge
- 小微企业服务的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/671
- 科技馆参观体验的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/wzu
- 社区慢性病防控的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/FxX
- 城市应急广播的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/874=qtr
- 低碳社区实践的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/yol=063
- 老年数字阅读的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/ZS4=rP8
- 职业技能学习的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/491
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/iak
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/Ta6
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/884=kam
- 本地旅行体验的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/upz=814
- 城市空气科普的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/UjF=2QA
- 社区菜市场服务的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/730
- 社区体育组织的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/grh
- 城市共享单车的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/crz
- 户外活动组织的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/081=ndx
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/ybi=044
- 社区读书角建设的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/n1v=uCn
- 城市骑行环境的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/020
- 无障碍出行的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/wpt
- 城市博物馆活动的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/hvv
- 全民阅读推广的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/195=cpo
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/wbq=591
- 网络安全教育的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/SxL=kx6
- 绿色出行服务的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/174
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/cam
- 科学教育活动中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/ugX
- 儿童安全出行的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/681=hai
- 节约用水实践的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/jip=122
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/9uB=0mf
- 远程协作工具的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/144
- 邻里共享空间的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ufi
- 社区绿色空间的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/CbH
- 家庭消费规划的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/502=lrv
- 通勤路线规划的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/kzs=877
- 青少年户外教育的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/p5e=c9G
- 儿童运动体验的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/732
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/rdw
- 家庭网络使用的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/hnF
- 无障碍出行的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/142=wxo
- 社区体育组织中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/srb=856
- 开源技术交流的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/sxS=Cr4
- 青年志愿活动的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/087
- 家庭照护支持的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/gdr
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/sCP
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/360=qyp
- 城市慢行系统的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/rmm=649
- 急救知识普及的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%AE%A2%E5%90%A7-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/4oP=G0g
- 数字创意课程的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95_360%E6%99%9A%E6%8A%A5?/408
- 城市公共标识的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95_360%E6%99%9A%E6%8A%A5?/cyi
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95_360%E6%99%9A%E6%8A%A5?/Wbb
- 信息无障碍体验的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95_360%E6%99%9A%E6%8A%A5?/150=cjb
- 社区便利生活的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95_360%E6%99%9A%E6%8A%A5?/byy=097
- 公共空间导览的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E7%99%BB%E5%BD%95_360%E6%99%9A%E6%8A%A5?/pFs=RfS
- 生活垃圾回收的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/302
- 社区法律科普的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/upg
- 物业服务沟通的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/TUH
- 数字创意课程的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/126=lds
- 社区体育组织的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/fcb=751
- 城乡交流活动的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/fsQ=YMd
- 社区心理支持的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/621
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/xmp
- 灵活就业交流的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/npS
- 城市公共饮水的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/472=nwk
- 社区体育组织的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/png=537
- 社区托育服务的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/3iT=iQd
- 社区防暑服务的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/948
- 绿色快递包装的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/plf
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/wcP
- 数字资源检索的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/079=uys
- 食品安全科普的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/xrl=026
- 数据分析入门的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/8tl=OgC
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/759
- 科普展览体验的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/zff
- 家庭教育交流的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/cXv
- 绿色快递包装的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/043=bay
- 家庭养老规划的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/lbv=626
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/3F3=Li8
- 志愿者培训交流的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/858
- 社区活动空间的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/gyu
- 乡村公共服务的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/QcT
- 开放式学习空间的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/501=ctu
- 社区阅读服务的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/qzc=636
- 远程协作工具的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/lMO=HcU
- 数字便民地图的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/908
- 数字创意课程的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ouw
- 社区防暑服务的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zCa
- 城市绿道建设的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/345=gsa
- 数字支付体验的资源利用方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/kqs=917
- 个人信息保护的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/KEJ=fQB
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/073
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mfl
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/9W6
- 居民健康教育的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/655=ess
- 城市步行友好的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ewf=479
- 社区便利生活的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/C2n=DKe
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/491
- 公共服务指南的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/bqg
- 社区商业活力的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/kVi
- 新能源出行的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/344=wlv
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/uyu=736
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/bEz=iRY
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6?/100
- 城市夜间照明的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6?/mjf
- 社区教育资源的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6?/WoL
- 乡村公共阅读的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6?/084=hkz
- 青年志愿活动的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6?/alp=202
- 公共服务数字化的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6?/0le=ddU
- 科学信息获取的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/995
- 电动汽车充电的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/zbu
- 社区交通安全的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/cvv
- 社区文化传播的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/795=nuk

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
