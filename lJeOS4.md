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

- 公共空间照明的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%9C%89%E5%95%A5%E5%A5%BD%E5%A4%84%E5%92%8C%E5%9D%8F%E5%A4%84_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/ksz=960
- 在线教育体验的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%9C%89%E5%95%A5%E5%A5%BD%E5%A4%84%E5%92%8C%E5%9D%8F%E5%A4%84_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/trE=Zjz
- 公园休闲体验的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/472
- 城市水环境观察的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/xcj
- 乡村阅读空间的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/iF6
- 非遗体验活动的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/375=xjr
- 乡村阅读空间的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/sbl=543
- 公共设施维护的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/fmX=RYT
- 社区便民集市的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/019
- 家庭教育交流的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/qfn
- 数字艺术创作的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/Vqa
- 家庭阅读计划的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/386=pnj
- 青少年心理健康的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/dlo=090
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/yKs=pXQ
- 绿色办公实践的社区参与观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%BF%85%E8%83%9C%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/608
- 家庭食品保存的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%BF%85%E8%83%9C%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/vns
- 儿童阅读角的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%BF%85%E8%83%9C%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/3zi
- 儿童安全出行的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%BF%85%E8%83%9C%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/963=opf
- 青少年心理健康的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%BF%85%E8%83%9C%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/ywh=529
- 街头绿植养护的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%BF%85%E8%83%9C%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/tdF=yV1
- 农产品消费体验的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/156
- 校园社团活动的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/jdb
- 便民服务窗口的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/PxL
- 便民服务地图的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/222=hyw
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/urj=335
- 街区道路维护的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/MZi=xH8
- 城市慢行系统的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/068
- 家庭安全提示的协商参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ydc
- 数字创作工具的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pBZ
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/362=ead
- 便民维修服务的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mqc=343
- 健康饮水科普的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/7Yy=JXX
- 开源技术交流的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E4%B8%8D%E8%B5%9A%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/540
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E4%B8%8D%E8%B5%9A%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/zwg
- 全民健身活动的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E4%B8%8D%E8%B5%9A%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/r5P
- 周末休闲规划的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E4%B8%8D%E8%B5%9A%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/475=egg
- 读书会组织的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E4%B8%8D%E8%B5%9A%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/yjm=024
- 街区绿化养护的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E4%B8%8D%E8%B5%9A%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/Kew=7hV
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%B4%AD%E5%BD%A9_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/019
- 城市水环境观察的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%B4%AD%E5%BD%A9_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/tqo
- 家庭用电安全的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%B4%AD%E5%BD%A9_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/Reo
- 科学教育活动中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%B4%AD%E5%BD%A9_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/539=edx
- 文化场馆预约的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%B4%AD%E5%BD%A9_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/wnk=818
- 机器人科普活动的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%B4%AD%E5%BD%A9_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/GSP=zYh
- 青少年科技社团的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/423
- 医院导诊服务的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/qho
- 城市文明实践中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/cul
- 城市步行友好的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/112=qlu
- 社区体育组织的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/euo=919
- 科普展览体验的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/Ia6=uNi
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/636
- 学校食育活动的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/gtv
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/H60
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/219=ffb
- 乡村生态观察的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/xwz=415
- 乡村公共文化的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/BAj=eJA
- 科普展览体验的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/541
- 城市文明出行的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/jsa
- 城市应急科普的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/F6A
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/202=cvk
- 街道综合服务的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/zdr=927
- 志愿服务平台的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/lUW=HsA
- 城市夜间照明的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9B%9E%E8%A1%80%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/078
- 老年人文化生活的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9B%9E%E8%A1%80%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/vlf
- 乡村生活观察的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9B%9E%E8%A1%80%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/Q1s
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9B%9E%E8%A1%80%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/495=kjv
- 街区道路维护的便捷程度观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9B%9E%E8%A1%80%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/yet=995
- 节能家电使用的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%9B%9E%E8%A1%80%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/sjJ=3m1
- 节能生活方式的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E8%B5%B0%E5%8A%BF%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/576
- 城市夜间生活的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E8%B5%B0%E5%8A%BF%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/bkm
- 骑行路线规划的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E8%B5%B0%E5%8A%BF%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/Y4k
- 青少年户外教育的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E8%B5%B0%E5%8A%BF%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/537=wtk
- 社区便利生活中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E8%B5%B0%E5%8A%BF%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/gnf=810
- 非遗课堂体验的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E8%B5%B0%E5%8A%BF%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/U3n=Fr6
- 老年智能设备的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/252
- 城市便民驿站的居民参与机会 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/afq
- 志愿者培训交流的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/7q8
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/609=pin
- 家庭消费规划的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/dmh=404
- 城市共享单车的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/36H=QuE
- 社区家校合作的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91welcome%E8%81%9A%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/147
- 口袋公园建设的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91welcome%E8%81%9A%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/kdy
- 图书借阅体验的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91welcome%E8%81%9A%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/2JK
- 社区安全巡查的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91welcome%E8%81%9A%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/449=pdu
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91welcome%E8%81%9A%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/bza=277
- 城市公共艺术的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91welcome%E8%81%9A%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/r0L=d77
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/943
- 公共场所导视中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/gzt
- 旧物循环利用的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/t4P
- 社区修缮行动的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/474=izm
- 数字支付体验的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/oew=775
- 公共设施维护的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/wGX=18T
- 数字素养提升的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/519
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/lkd
- 电动汽车充电的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/nfX
- 节能生活方式的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/201=bru
- 数字政务体验的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/cxr=826
- 线上办事服务的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/sN9=uKl
- 城市运动公园的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%9158%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/695
- 家庭健康管理的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%9158%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/stt
- 城市生活服务的入门知识整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%9158%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/JTh
- 运动安全知识的行动步骤参考 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%9158%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/007=ohg
- 志愿服务平台的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%9158%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/acu=377
- 绿色办公实践的日常实践笔记 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%9158%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/T6N=UsQ
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%E7%9A%84_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/361
- 公共服务评价的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%E7%9A%84_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/azi
- 绿色生活实践的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%E7%9A%84_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/cJF
- 公共服务数字化的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%E7%9A%84_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/683=dgf
- 乡村公共文化的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%E7%9A%84_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/boq=367
- 机器学习入门的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%E7%9A%84_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/UtR=YhP
- 绿色校园实践的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/824
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/msj
- 乡村公共文化的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/IzH
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/946=aoq
- 社区活动策划的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/vsv=088
- 城市适老服务的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/CSg=e5m
- 社区公共卫生的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9A%84%E6%8E%A8%E5%B9%BF%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/531
- 城市生活服务的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9A%84%E6%8E%A8%E5%B9%BF%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/ame
- 城乡交通衔接的日常管理方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9A%84%E6%8E%A8%E5%B9%BF%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/pU1
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9A%84%E6%8E%A8%E5%B9%BF%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/514=wde
- 小微企业服务的学习资源整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9A%84%E6%8E%A8%E5%B9%BF%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/xgr=525
- 地方文化传播的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9A%84%E6%8E%A8%E5%B9%BF%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/fT5=VST
- 课后服务体验的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/854
- 开源技术交流的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/pbf
- 社区手工活动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/BiT
- 学校食育活动的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/162=ztt
- 社区便利生活的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/ehf=179
- 健康饮食教育的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/Anz=Ajs
- 社区环保活动的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9A%84%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/694
- 乡村公共服务的组织方法与经验 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9A%84%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/tlg
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9A%84%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/Xnj
- 家庭科学教育的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9A%84%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/470=wal
- 社区故事采集的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9A%84%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/bes=926
- 社区活动空间的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9A%84%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/d69=3yG
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/383
- 城市应急科普的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/yta
- 节假日出行安排的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/SGw
- 居民健康教育的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/170=wwp
- 公共服务评价的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/unu=898
- 社区便民集市中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/HzL=ck4
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/085
- 家庭消费规划的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/wej
- 非遗体验活动的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/X96
- 社区老年食堂的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/715=fll
- 户外活动组织的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/lxn=248
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/Edr=yzk
- 城市共享单车的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/841
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/xix
- 健康步道使用的绿色实践方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/Kwp
- 城市适老服务的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/973=cet
- 社区生活指南中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/lqt=242
- 儿童友好空间的线下体验记录 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/YYc=I8I
- 信息无障碍体验的社区行动案例 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%80%BB%E4%BB%A3%E7%90%86_360%E7%9B%98%E7%82%B9?/398
- 健康步道使用的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%80%BB%E4%BB%A3%E7%90%86_360%E7%9B%98%E7%82%B9?/pyn
- 便民维修服务的活动组织技巧 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%80%BB%E4%BB%A3%E7%90%86_360%E7%9B%98%E7%82%B9?/W4l
- 社区公共议事的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%80%BB%E4%BB%A3%E7%90%86_360%E7%9B%98%E7%82%B9?/724=vie
- 城市空气科普的服务细节记录 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%80%BB%E4%BB%A3%E7%90%86_360%E7%9B%98%E7%82%B9?/dht=818
- 城市人文观察的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%80%BB%E4%BB%A3%E7%90%86_360%E7%9B%98%E7%82%B9?/RQT=bBb
- 青年志愿活动的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/814
- 软件开发学习的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/ddh
- 社区故事采集的家庭参与方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/DYi
- 健康步道使用中的沟通与协作 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/257=dwu
- 基层服务创新中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/dhv=219
- 社区艺术活动的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/rmq=tYO
- 绿色校园实践的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/981
- 社区托育服务的数字工具使用体验 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/xkg
- 家庭收纳实践的公共参与指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/tR4
- 社区故事采集的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/150=vhl
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/cwn=239
- 机器学习入门的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/rb1=NnZ
- 社区活动策划的常见误区提醒 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/844
- 家庭用电安全的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/mrd
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/Bu9
- 家庭养老规划的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/752=xab
- 乡村生态旅游的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/uge=862
- 校园社团活动的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/fQl=Hlk
- 旧物循环利用的资源利用方法 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/260
- 绿色生活实践的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/etx
- 社区互助网络的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/P3l
- 家庭防灾准备的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/465=nwf
- 志愿服务平台的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/fhu=388
- 社区消防演练的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/U9r=5Yd
- 公益活动组织的基础设施观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%8824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/210
- 社区教育资源的公共信息获取方式 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%8824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/lfe
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%8824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/XwQ
- 数字便民地图的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%8824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/276=aos
- 乡村公共服务的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%8824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/ziy=622
- 数字资源检索的家庭实践清单 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%8824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/eEy=NNR
- 街头绿植养护的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/728
- 传统节日科普的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/ksf
- 志愿服务平台的活动策划思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/Dgk
- 乡村公共阅读的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/023=kai
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/gwh=380
- 社区安全巡查的流程优化思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/SwW=Wh1
- 志愿者培训交流的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9C%A8%E7%BA%BF%E6%95%99%E5%AD%A6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/044
- 家庭饮食安排的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9C%A8%E7%BA%BF%E6%95%99%E5%AD%A6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/lny
- 城市公共空间的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9C%A8%E7%BA%BF%E6%95%99%E5%AD%A6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/EQ1
- 家庭环保习惯的长期维护要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9C%A8%E7%BA%BF%E6%95%99%E5%AD%A6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/383=vof
- 城市适老服务的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9C%A8%E7%BA%BF%E6%95%99%E5%AD%A6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/mtc=907
- 个人时间管理的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9C%A8%E7%BA%BF%E6%95%99%E5%AD%A6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/1K3=e02
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/927
- 城市夜间照明的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/vjg
- 基层医疗预约的活动体验回顾 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/ggL
- 社区休闲设施的安全使用提示 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/257=gio
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/ysi=236
- 机器人科普活动的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%B4%AD%E5%BD%A9%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/41i=ks6
- 社区便利生活的设施维护观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/215
- 城市公共饮水的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/aff
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/Xje
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/541=hwo
- 家庭安全提示的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/are=904
- 公园亲子设施的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/3eU=6pd
- 家庭节能实践的常见问题梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/034
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/ino
- 口袋公园建设的服务信息整理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/4pD
- 文明养宠科普的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/916=mnm
- 无障碍信息设计的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/pzd=101
- 网络安全教育的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/GaP=vWr
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%AD%BE%E5%88%B0_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/292
- 数字素养提升的数字化应用观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%AD%BE%E5%88%B0_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/qsx
- 城市空气科普的资源整合思路 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%AD%BE%E5%88%B0_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/164
- 社区菜市场服务的服务质量观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%AD%BE%E5%88%B0_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/372=ryj
- 社区生活指南的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%AD%BE%E5%88%B0_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/rov=678
- 邻里互助活动的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%AD%BE%E5%88%B0_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/dpT=ZqF
- 环境监测科普的儿童友好细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/631
- 老年学习活动的服务范围梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/kei
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/pxt
- 传统手工艺体验的实用信息清单 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/238=hud
- 城市共享单车的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/asz=073
- 科学观察活动的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%9D%A0%E8%B0%B1%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/OUw=YtM
- 光伏知识科普的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/524
- 乡村教育资源的空间使用体验 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/aym
- 社区科普课堂的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/yYI
- 老年人文化生活的日常记录与分享 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/934=rag
- 休闲运动入门的空间设计要点 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/gkn=968
- 绿色消费选择的参与方式与路径 |来源：https://github.com/millershelley99/meim/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/Gqs=tip
- 家庭养老规划的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/385
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/wud
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/938
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/993=bao
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/yjd=071
- 社区法律科普的日常使用指南 |来源：https://github.com/millershelley99/meim/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/C92=Z4w
- 公共空间导览的持续改进方向 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%ABWelcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/719
- 节能家电使用的实际需求与回应 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%ABWelcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/yod
- 老旧小区改造的执行流程参考 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%ABWelcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/5KG
- 数字艺术创作的便利性观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%ABWelcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/533=zqm
- 课后服务体验的便民做法梳理 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%ABWelcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/cpu=807
- 机器学习入门的基础知识问答 |来源：https://github.com/millershelley99/meim/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%ABWelcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/gTI=Acs
- 图书馆活动策划的适老服务细节 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/493
- 公共交通接驳的服务体验观察 |来源：https://github.com/millershelley99/meim/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%94%BE?/soh

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
