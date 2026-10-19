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

- 应急物资管理的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/nwb=607
- 社区故事采集的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/LxH=0Iu
- 社区家校合作的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/774
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/vsn
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/r83
- 城市文明实践的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/638=exc
- 便民服务地图的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/jcv=659
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/hYj=DHG
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/169
- 机器学习入门的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/fyn
- 数字学习资源的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/CRG
- 公共空间休憩的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/819=dbp
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/nuo=858
- 食品配送体验的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/y3Y=ZYZ
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/472
- 社区阅读服务的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/weg
- 本地历史资料的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/PXa
- 居民健康教育的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/022=gkt
- 乡村公共文化的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/kmk=054
- 社区慢性病防控的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/bHS=nat
- 职业技能学习的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/872
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/knx
- 健康信息获取的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/qYp
- 节气饮食文化的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/636=jbz
- 公园亲子设施的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/oru=534
- 家庭园艺实践的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/RRy=kZ1
- 数字公共文化的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/272
- 市民热线服务的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/rcp
- 社区读书角建设的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/GqZ
- 家庭志愿活动的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/912=mzk
- 志愿服务平台的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/lsi=259
- 绿色办公实践的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/MdL=5q5
- 家庭教育交流的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/264
- 智慧城市体验的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/dwl
- 城乡交流活动的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/hPp
- 开源技术交流的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/817=sqz
- 社区协商议事的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/qwb=862
- 城市公共空间的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/ntw=l4O
- 青年职业探索的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/879
- 家庭志愿活动的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/wlq
- 城乡公共服务中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/Ktz
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/614=bws
- 居家适老化改造的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/qha=055
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/Sse=ZF6
- 数字阅读服务的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/837
- 城市公共自行车的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/dnz
- 家庭教育交流中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/jOM
- 人工智能科普的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/136=xiq
- 市民热线服务的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/xzs=382
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/Ud9=2U1
- 社区法律科普的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/973
- 开放数据应用的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/bzt
- 城市体育设施中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/1i4
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/540=meo
- 学校食育活动中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/cag=458
- 网络安全教育中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/A1U=aKF
- 公共场所导视的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BE%E9%9B%86?/385
- 儿童友好空间的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BE%E9%9B%86?/owo
- 老年人日常照护的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BE%E9%9B%86?/HUU
- 软件开发学习中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BE%E9%9B%86?/203=xut
- 劳动教育实践的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BE%E9%9B%86?/oij=192
- 城市骑行环境的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%9B%BE%E9%9B%86?/BDR=D18
- 社区文化传播的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/010
- 街区小店体验的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/ylz
- 乡村公共文化的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/7YC
- 公共空间导览的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/188=mrb
- 社区宠物管理的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/bto=726
- 社区活动报名的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/bRm=goL
- 城市噪声观察的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/967
- 社区文化传播的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/epj
- 社区知识分享的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/9Ad
- 低碳社区实践的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/395=hws
- 乡村生态旅游的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/qox=588
- 数字创意课程的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/9sC=hUX
- 气象科普传播的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/281
- 社区应急准备的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/meq
- 农业科普体验的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/dtX
- 新能源出行的数字化应用观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/616=ngh
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/ciq=035
- 青年志愿活动的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/1rO=KQ9
- 运动安全知识的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/700
- 公共场所导视的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/gka
- 社区停车服务的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/WhY
- 儿童安全出行的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/427=kad
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/bnn=696
- 农产品消费体验的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/Ghb=HRo
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/209
- 社区体育组织的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/ern
- 本地旅行体验的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/dDF
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/749=jlh
- 公共空间照明的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/skv=824
- 机器学习入门的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/pVF=qp0
- 数字阅读服务的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/746
- 街区绿化养护的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/ycn
- 社区停车服务的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/02g
- 社区教育资源的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/144=ojz
- 科学信息获取的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/ngt=952
- 社区共享书架的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/lRY=yKu
- 城市文明出行的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/867
- 公共空间照明的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/mje
- 农业科普体验的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/SMS
- 校园安全教育的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/906=slo
- 社区读书角建设的基础设施观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/pls=811
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/0Uw=JKG
- 老年人文化生活的协商参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/343
- 居家适老化改造中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/eon
- 创业经验分享的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/Dt1
- 城市运动公园的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/330=ioz
- 社区学习活动的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/lom=075
- 社区防暑服务的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/jaI=j6R
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/055
- 消防知识宣传的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/qrt
- 社区法律科普的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/Hnn
- 公共服务数字化的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/119=dgr
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/enn=937
- 城市公共标识的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E5%BA%93?/6OU=icl
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/238
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/ris
- 城市文化路线中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/x0R
- 公共场馆服务的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/164=tnu
- 城市公共饮水的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/fwh=870
- 通勤路线规划的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/vVT=lrH
- 社区消防演练的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/089
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/cix
- 家庭环保行动的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/gqs
- 城市公共厕所的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/148=dzy
- 市民热线服务的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/rkz=069
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/qCz=Jxo
- 居家防滑改造的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/198
- 老年学习活动的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/ubk
- 农贸市场环境的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/1sQ
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/286=xev
- 公共服务咨询的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/btz=929
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/cpu=1jw
- 社区庭院绿化的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/763
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/tpv
- 公共服务沟通的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/bIv
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/822=uld
- 社区公共卫生的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/wpc=061
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/JfQ=2l7
- 基层健康服务的服务反馈渠道 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/165
- 社区手工活动的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/hdt
- 垃圾分类指导的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/GDy
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/190=rua
- 城市公共饮水的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/qtp=167
- 便民信息查询中的沟通与协作 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/TCv=Dm3
- 家庭志愿活动的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/380
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/zia
- 全民健身活动的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/imZ
- 城市便民驿站的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/732=kxu
- 家庭急救准备的实用信息清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/nxe=465
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/N3Z=CIq
- 在线教育体验的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/835
- 家庭网络使用的便民做法梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/wac
- 社区花园共建的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/SdJ
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/304=lot
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/zsu=089
- 光伏知识科普的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/J1u=fWb
- 科学运动指导的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/055
- 家庭运动计划的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/dqr
- 城市共享单车的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/LZ3
- 绿色快递包装的入门知识整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/107=hhb
- 绿色建筑理念的服务信息整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/kui=115
- 社区垃圾回收的空间使用体验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/pAq=i2m
- 绿色出行服务的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/184
- 跨代沟通活动的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/thx
- 新能源出行的阅读与学习资源 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/8LM
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/696=yyw
- 居民健康教育的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fhv=158
- 社区交通安全的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/v9A=PWS
- 本地消费场景的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/014
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/ppe
- 社区共享书架的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/Xg3
- 数字支付体验的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/296=buv
- 城市博物馆服务的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/met=235
- 亲子阅读活动的流程优化思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/t62=4im
- 软件开发学习的日常使用指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/199
- 城市文明出行的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/ujt
- 城市共享单车的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/P2L
- 市民热线服务的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/480=kpj
- 生活垃圾回收的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/mpp=973
- 社区公共卫生的学习资源整理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/cQZ=pLI
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/128
- 城市公共自行车的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/vtm
- 公共服务指南的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/0PF
- 社区菜市场服务的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/721=nms
- 老旧小区改造的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/hze=593
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/Ctp=B3L
- 农产品消费体验的儿童友好细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/082
- 社区养老服务的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/qjz
- 公共服务预约的活动体验回顾 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/q0B
- 城市绿道建设的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/659=vus
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/xgv=927
- 儿童安全出行的社区参与观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/aty=uTQ
- 环境监测科普的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/056
- 小区停车协商的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/uro
- 健康信息获取的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/ecH
- 电动汽车充电的行动步骤参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/634=wyl
- 青少年户外教育的线下体验记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/zbr=925
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/vk1=PDl
- 社区活动策划的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/782
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/xvq
- 个人时间管理的便利性观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/dN7
- 小区停车协商的协作机制梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/372=fdn
- 家庭急救准备的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/uqb=179
- 儿童安全出行的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E5%8D%B7?/zkc=Woz
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/836
- 数字创意课程的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/rtm
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/r4R
- 儿童友好空间的长期维护要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/521=pfk
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/avz=236
- 校园社团活动的使用门槛与改进 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/c71=DO2
- 社区活动策划的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/242
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/viu
- 科学健身方法的绿色实践方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/UkO
- 志愿者培训交流的服务体验观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/240=rkx
- 数据分析入门的日常记录与分享 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/hsr=807
- 公共文化活动的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/hlC=pRd
- 公共卫生设施的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/097
- 社区艺术活动的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/noh
- 健康信息获取的设施维护观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/8Bc
- 健康饮食教育的安全使用提示 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/936=olo
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/jep=837
- 食品安全科普的日常管理方法 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/gPM=D2T
- 灵活就业交流的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/944
- 新能源出行的服务细节记录 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/lil
- 非遗体验活动的组织方法与经验 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/0oL
- 老年人出行服务的常见误区提醒 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/261=kwc
- 老年数字阅读的空间设计要点 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/gfn=368
- 乡村生态观察的资源整合思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/f1R=xl8
- 生活垃圾回收的社区行动案例 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/008
- 城市应急广播的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/wou
- 读书会组织的执行流程参考 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/D8L
- 街区绿化养护的活动组织技巧 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/459=xdi
- 个人信息保护的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/izi=557
- 城市树木认养的便捷程度观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/75h=G8d
- 传统节日科普的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/978
- 节假日出行安排的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/ndm
- 城市公共艺术的家庭参与方式 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/CgV
- 城市人文观察的持续改进方向 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/945=jip
- 社区环保活动的适老服务细节 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/xkf=065
- 家庭健康管理的参与方式与路径 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/P8k=jd8
- 小区公共照明的服务质量观察 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/962
- 地方文化传播的家庭实践清单 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/klg
- 公园亲子设施的居民参与机会 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/fc1
- 社区运动空间的常见问题梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/036=enr
- 社区生活指南的活动策划思路 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/uiy=393
- 节日文化体验的服务范围梳理 |来源：https://github.com/brownjohnny5/khdp/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/rMf=KUo
- 社区文化节活动的基础知识问答 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/589
- 租房信息服务的日常实践笔记 |来源：https://github.com/brownjohnny5/khdp/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/wep

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
