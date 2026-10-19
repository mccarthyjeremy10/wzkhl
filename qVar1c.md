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

- 网络信息辨识的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/OIw
- 本地历史资料的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/902=ghi
- 智慧城市体验的服务体验观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/pko=929
- 绿色生活实践的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E8%81%8C%E5%9C%BA?/Lrt=H39
- 生成式工具使用的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/464
- 读书会组织的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/swp
- 街道综合服务的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/0HM
- 社区庭院绿化的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/409=cyx
- 街区绿化养护的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/wov=780
- 无障碍信息设计的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/NuW=P3e
- 传统节日科普的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E8%A1%8C%E6%83%85?/095
- 公共交通接驳的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E8%A1%8C%E6%83%85?/vhi
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E8%A1%8C%E6%83%85?/kqm
- 本地消费场景的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E8%A1%8C%E6%83%85?/622=hoi
- 城市展览体验的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E8%A1%8C%E6%83%85?/hrr=464
- 地方美食文化的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E8%A1%8C%E6%83%85?/5mc=BKg
- 街头绿植养护的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/263
- 数字地图应用中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/izj
- 城市共享单车的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/XPx
- 社区交通安全的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/481=jbd
- 老年智能设备的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/moj=560
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%B8%AF%E8%82%A1?/qKz=kFn
- 社区公共议事的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/480
- 城市地名文化的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/pwb
- 数字艺术创作的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/CVh
- 老年友好服务的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/993=stk
- 城市步行友好的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/cqm=936
- 社区故事采集的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/ONC=WS0
- 乡村阅读空间的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/045
- 课后服务体验的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/awe
- 科学教育活动的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/zKa
- 城市可持续生活的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/667=yuq
- 新能源出行的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/ims=259
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/7lN=bHe
- 城市游园体验的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/355
- 城市休闲步道的资源整合思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/qbk
- 城市共享单车的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/Zu3
- 公园亲子设施中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/915=foj
- 公共服务数字化的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/ynb=363
- 城市骑行环境的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/LnN=2Tm
- 急救知识普及的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/578
- 文明养宠科普的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/osa
- 绿色办公实践的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/DzR
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/882=jno
- 城市文明实践的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/xfm=422
- 农村环境治理的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/VUI=q7x
- 社区环保活动的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/956
- 家庭节能设备中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/cxx
- 公共空间安全的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/oMk
- 家庭消费规划的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/287=ffh
- 家庭用电安全的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/nvv=391
- 家庭理财科普的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/MWI=t3i
- 基层健康档案的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/516
- 数字创意课程的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/ewq
- 终身学习资源的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/q5L
- 社区设施共享的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/185=mel
- 乡村电商实践的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/hvk=520
- 家庭健康管理中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/JSE=OP2
- 数字阅读服务的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/592
- 城市文明出行的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/dge
- 开放数据应用的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/NvL
- 健康饮水科普的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/868=afm
- 绿色出行服务的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/gpa=420
- 休闲运动入门的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/N58=L9Y
- 城乡公共服务的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/663
- 家庭环保习惯的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/hlf
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/iPT
- 居家适老化改造的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/195=acz
- 地方民俗记录的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/alz=132
- 电动汽车充电的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/dvg=q7V
- 青年职业探索的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/820
- 公共设施使用的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/sjm
- 电动汽车充电的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/HcH
- 公共图书馆服务的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/047=usv
- 城乡交通衔接的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/nsf=045
- 城市应急科普的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/80H=wS7
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/828
- 基层健康服务的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/hcg
- 网络安全教育的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/tY4
- 城市便民驿站的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/919=pws
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/vpj=570
- 网络信息辨识的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/WvZ=q9S
- 电子商务服务的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/918
- 社区便民服务的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/dnj
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/PMq
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/137=mcw
- 老年运动活动的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/cjt=218
- 绿色建筑理念的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/Ngq=goY
- 青年志愿活动的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/379
- 家庭健康管理的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/ozm
- 数字生活课堂的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/w6Q
- 乡村生活观察中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/275=vvf
- 公共服务评价的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/wau=453
- 社区活动策划的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/lXb=idw
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/788
- 城市慢行系统的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/ynu
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/Fkh
- 城市便民驿站的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/080=ewx
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/dbb=588
- 城市应急广播的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/cyd=Sch
- 城市适老服务中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/462
- 社区垃圾回收的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/vdb
- 社区快递服务的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/EJu
- 数字档案服务的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/295=dlt
- 学校体育活动的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ppj=406
- 数字生活课堂的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Lxb=qzu
- 数字课堂应用的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/996
- 创业经验分享的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/bcm
- 社区绿色空间的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/NOj
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/437=nfu
- 社区运动空间的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/dhs=557
- 地方文化传播的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/Kpa=JZM
- 个人信息保护的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/611
- 公交无障碍服务的长期维护要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qic
- 街区更新实践的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/oqe
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/465=yan
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/twe=490
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Yiu=ePt
- 学校食育活动的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/465
- 乡村产业科普的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/kmx
- 老年数字阅读的基础知识问答 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/11W
- 科普展览体验的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/684=pvl
- 课后服务体验的参与方式与路径 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/aeo=847
- 社区协商议事的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/bwl=8rv
- 城市微更新实践的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/003
- 社区休闲设施的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/wcp
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/CJy
- 非遗课堂体验的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/273=uor
- 城市文化路线的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/das=992
- 乡村文化空间的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/Eaj=FJf
- 社区学习活动的组织方法与经验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/926
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/wnd
- 农业科普体验的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/Tyq
- 物业服务沟通的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/164=qem
- 社区消防演练的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/jds=617
- 老旧小区改造的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/hff=jr7
- 家庭健康管理的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/902
- 通勤路线规划的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/ntt
- 社区宠物管理的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/qRo
- 绿色消费选择的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/442=qww
- 社会体育指导的学习资源整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/zhg=612
- 生活垃圾回收的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/z4o=e0g
- 地方美食文化的适老服务细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/415
- 校园社团活动的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/znh
- 社区读书角建设的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/COW
- 科普展览体验的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/715=ids
- 智能手机助老的流程优化思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/oln=006
- 社区互助网络的数字化应用观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/eoL=0Io
- 青少年科普实践的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/545
- 气象科普传播的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/rhv
- 青年职业探索的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/TTJ
- 个人时间管理中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/806=axs
- 本地旅行体验的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/kgb=497
- 公共设施使用的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/ffl=16G
- 公共交通接驳的日常使用指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E8%B1%86%E7%93%A3?/481
- 青少年科普实践的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E8%B1%86%E7%93%A3?/kze
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E8%B1%86%E7%93%A3?/888
- 绿色校园实践的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E8%B1%86%E7%93%A3?/297=zto
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E8%B1%86%E7%93%A3?/ehz=138
- 居家适老化改造的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E8%B1%86%E7%93%A3?/nJ1=tLv
- 老年人日常照护的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/873
- 节气饮食文化的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/cxu
- 公共卫生设施的绿色实践方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/67S
- 读书会组织的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/331=umb
- 数字档案服务的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/yxt=834
- 物业服务沟通的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/tBO=qCf
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/718
- 乡村教育资源的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/toa
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/NcK
- 全民健身活动的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/190=xxi
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/cyj=019
- 社区读书角建设的居民参与机会 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/2vP=S8X
- 基层健康服务的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/616
- 人工智能科普的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/xwi
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/tIV
- 社区快递服务的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/602=las
- 医院导诊服务的协作机制梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/cxz=962
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/8yu=6Bs
- 数字政务体验的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/471
- 本地历史资料的儿童友好细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/wdb
- 小区公共照明的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/hnP
- 儿童运动体验的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/970=gih
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/sla=578
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/rud=Yjk
- 社区花园共建的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/515
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/hjw
- 数字设备回收的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/3OJ
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/448=buv
- 城市社区治理的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/bfz=677
- 老年运动活动的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/YbC=P5I
- 数字支付体验的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/675
- 城市可持续生活的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/srs
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/tA4
- 街区道路维护的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/296=saf
- 乡村公共文化中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/lif=209
- 家庭教育交流的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/B5x=FF9
- 个人信息保护的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/759
- 基层医疗预约的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/jrl
- 社区防暑服务的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/0sm
- 乡村公共文化的空间使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/788=tus
- 全民健身活动的日常管理方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/qww=464
- 儿童户外活动的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/lFc=SYY
- 图书借阅体验的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/839
- 开源技术交流的日常实践笔记 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/wef
- 社区家政服务的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/tlb
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/565=smk
- 社区养老服务的数字工具使用体验 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/ysn=034
- 社区养老服务的持续改进方向 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/3Rv=ons
- 智慧城市体验的实际需求与回应 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/815
- 城市公共饮水的社区行动案例 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/fuj
- 数字创意课程的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/qp3
- 志愿服务平台的资源利用方法 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/493=dvb
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/hkc=695
- 社区便民服务的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/1mi=K1r
- 地方民俗记录的便民做法梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/149
- 垃圾分类指导的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/apk
- 公共服务预约的便利性观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/Vbz
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/434=eey
- 家庭运动计划的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/rpd=790
- 绿色快递包装的执行流程参考 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/g2E=ua5
- 小区停车协商的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/119
- 城市夜间照明中的几个关键细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/hao
- 社区手工活动的基础设施观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/fJW
- 城市公共厕所的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/688=rzl
- 休闲运动入门的空间设计要点 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/rhq=947
- 城市文化路线的入门知识整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/YRN=W45
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/393
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/tzf
- 数字便民地图的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/3bc
- 创业经验分享的公共信息获取方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/051=tgo
- 基层医疗预约的线下体验记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/len=792
- 线上阅读资源的常见问题梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/TzP=TPo
- 家庭阅读计划的设施维护观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/282
- 小区电梯维护的便捷程度观察 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/zch
- 智能手机助老的常见误区提醒 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/GkB
- 家庭安全提示的活动组织技巧 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/527=uyl
- 社区家校合作的公共参与指南 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/phv=922
- 城市夜间照明的服务细节记录 |来源：https://github.com/hillwalter2088/nuqj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/JcO=keW
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/302
- 食品配送体验的服务范围梳理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/rfr
- 科学运动指导的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/TWW
- 通勤路线规划的实用信息清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/666=lih
- 社区便利生活的家庭实践清单 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/ihy=815
- 公共服务数字化的活动策划思路 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/ITO=efn
- 乡村生活观察的协商参与方式 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/218
- 城市绿色交通的活动体验回顾 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/jyg
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/neV
- 老年人文化生活的安全使用提示 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/365=sqz
- 亲子科普活动的服务信息整理 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/gyg=845
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/hillwalter2088/nuqj/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/twX=QSI

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
