# 硕士学位论文答辩准备方案

## 基本信息

- **论文题目**：数字经济创新发展试验区对企业费用粘性的影响
- **答辩人**：江冠洲（2301212234）
- **学院/专业**：汇丰商学院 / 金融硕士（金融科技方向）
- **导师**：童娜琼 副教授
- **答辩时间**：15分钟陈述 + 15分钟评委提问
- **答辩形式**：线下答辩，提供纸质论文
- **陈述语言**：英文
- **评委构成**：3位金融/经济领域教师

## 核心策略

### 叙事主线 — "我的研究旅程"

以"我"作为主语贯穿始终，强调三方面：
1. **学到了什么** — 每个环节点明个人收获
2. **独立完成** — 数据清洗、模型设定、Stata实现均为亲手完成
3. **学术价值** — 视角创新（政策层面数字经济发展的微观成本效应）

### 个人故事开场

以姥爷的钢铁生意经历引出研究动机，建立情感共鸣：
- 2010年前扩张 → 产能过剩 → 费用拖垮企业
- 过渡到学术问题：费用粘性是什么？制度创新能否解决？

## 幻灯片结构（9页，约13分钟）

| # | 内容 | 时间 | 类型 |
|:-:|------|:----:|:----:|
| 1 | 标题 + 姥爷的故事 | 1.5min | 故事开场 |
| 2 | 费用粘性：定义与成因 | 1min | 理论基础 |
| 3 | 文献缺口：从企业数字化到政策数字化 | 1.5min | 研究定位 |
| 4 | 研究设计与数据工作 | 1.5min | 方法论 |
| 5 | 核心发现：平行趋势 + 基准回归 | 2min | 结果 |
| 6 | 三条机制路径 | 2.5min | 主要贡献 |
| 7 | 异质性：谁更受益 | 1min | 深化分析 |
| 8 | 稳健性检验 | 1min | 可信度 |
| 9 | 结论 + 我的收获与反思 | 1.5min | 收尾 |

**弹性时间**：约2分钟缓冲

## 完整英文讲稿

### Slide 1：标题 + 个人故事（1.5 min）

> "Good afternoon, professors. My name is Jiang Guanzhou, from HSBC Business School, majoring in Fintech, supervised by Professor Tong Naqiong."
>
> "Before I present my thesis, let me start with a personal story."
>
> "My grandfather ran a steel business. Before 2010, when China's economy was booming, his company grew rapidly — expanding production lines, hiring aggressively, building new facilities. Business was great. He expanded confidently."
>
> "But then the macroeconomy slowed. Overcapacity hit the steel industry hard. Revenue started falling — at first gradually, then sharply."
>
> "Here's the problem: **when revenue dropped, the costs didn't drop with it.** All those employees, those factory leases, those administrative overheads — they were stuck. They couldn't come down fast enough. That rigid cost structure eventually overwhelmed the business."
>
> "That experience stayed with me. It made me ask: **why is it so hard for firms to reduce costs when revenue declines?** And more importantly — **can anything help?** "
>
> "This led me to the academic literature on cost stickiness, and eventually to my research question: **can China's Digital Economy Pilot Zones — a major institutional innovation — provide a solution to this problem?** "

### Slide 2：费用粘性 — 定义与成因（1 min）

> "What my grandfather experienced is formalized in the accounting literature as **cost stickiness**. Anderson, Banker, and Janakiraman — the ABJ model — defined it in 2003 as an asymmetric cost behavior: when revenue rises by 10%, expenses increase by about 5%; but when revenue falls by 10%, expenses might only decrease by 2%. **Costs go up like an elevator but come down like an escalator.** "
>
> "From my literature review, I found two core drivers. First, **agency costs** — managers resist cutting resources when revenue declines. Second, **adjustment costs** — firing employees and divesting assets is expensive."
>
> "Importantly, this isn't just an accounting curiosity. **It's a governance problem** — and it means a purely internal solution may not be enough."

### Slide 3：文献缺口 — 从企业数字化到政策数字化（1.5 min）

> "After understanding cost stickiness, I went to the literature to see: **what solutions have already been identified?** "
>
> "I found a growing body of research showing that digital transformation — at the firm level — can reduce cost stickiness. Scholars like Wu Wuqing (2022), Wang Chengcai (2024), and Zhang Yong (2023) have confirmed this effect. Similarly, research on digital finance — by Yuan Chun (2025) and others — also finds a suppressing effect."
>
> "But here's what struck me: **almost all existing research focuses on digital development from the firm's own perspective.** What about the **policy level?** "
>
> "The National Digital Economy Innovation Development Pilot Zones represent the **government's top-down push for digitalization** — providing infrastructure, encouraging data sharing, reforming institutions. This is a fundamentally different angle: **digital economy development as a national policy, not just a firm-level choice.** "
>
> "I realized: **no study had examined whether this policy-level digital economy initiative could reduce corporate cost stickiness.** That became the core question of my thesis."

### Slide 4：研究设计与数据（1.5 min）

> "To test this question, I used a **Difference-in-Differences** model."
>
> "The **treatment group** is firms registered in the six pilot zones. The **control group** is firms outside these zones. The **policy shock** is 2019."
>
> "**Why DID?** Because firm-level digitalization is endogenous. But the pilot zone is an **exogenous policy shock**. This gives us clean causal identification."
>
> "Now let me walk through my data. I started with all A-share listed firms from 2016 to 2024. After excluding financial firms, ST firms, missing data, and winsorizing at 1%, I obtained **19,019 firm-year observations**. Data from iFind and CSMAR databases. All regressions in **Stata 18.0**."
>
> "I want to emphasize: **this was where I learned the most about empirical research.** Every exclusion criterion, every winsorization choice — I had to justify each one."

### Slide 5：核心发现（2 min）

> "Now let me show you what I found."
>
> "First, the **parallel trend test**. As this graph shows, before 2019, there was no systematic difference between treatment and control groups. After the policy shock, the effect becomes positive and significant. **This confirms the parallel trend assumption holds.** "
>
> "Now the **baseline regression result**. The DID coefficient is **0.110, significant at the 1% level**. This means **firms in the pilot zones show about an 11 percentage point reduction in cost stickiness** compared to non-pilot firms. The model explains 32.4% of the variation with 19,019 observations."

### Slide 6：三条机制路径（2.5 min）

> "The headline result is clear. But **I wanted to understand how**. This is where my thesis makes its main contribution."
>
> "**Channel 1: Labor Structure.** The policy significantly increases the proportion of highly educated employees. Highly educated workers can be reassigned across departments during downturns, reducing adjustment costs. Significant at 1%."
>
> "**Channel 2: R&D Investment.** The policy encourages firms to invest more in R&D, funding digital transformation. These technologies convert rigid fixed costs into variable costs — cloud services, smart logistics. When revenue drops, these variable costs can be cut quickly. Significant at 1%."
>
> "**Channel 3: Agency Costs.** The most interesting channel. Digital internal controls — ERPs, financial shared service centers, blockchain audit trails — **penetrate through organizational hierarchies**. Managers can no longer hide redundant expenses. The coefficient is 0.111, significant at 1%."
>
> "In summary: the policy works through **people** (better labor), **technology** (more R&D), and **governance** (stronger controls)."

### Slide 7：异质性（1 min）

> "Not all firms benefit equally. I tested three dimensions."
>
> "First, **information asymmetry**. The effect is significant for firms with high asymmetry but insignificant for low asymmetry. **The policy's main benefit is improving transparency, so firms that start with worse information gain more.** "
>
> "Second, **ownership type**. Significant for non-SOEs, not for SOEs."
>
> "Third, **managerial optimism**. Firms with overconfident managers show a stronger effect. Digital tools help correct optimistic bias."
>
> "These results provide guidance for **targeted policy design**."

### Slide 8：稳健性检验（1 min）

> "I performed **five sets of robustness checks**. Replacing the dependent variable, placebo test (500 permutations), fixed effects model, PSM-DID, and excluding confounding policies (Innovative City Pilot, Broadband China, etc.)."
>
> "The key takeaway: **my core finding holds in every single check.** "

### Slide 9：结论 + 我的收获与反思（1.5 min）

> "Let me conclude with **what I found and what I learned.** "
>
> "**What I found:** The Digital Economy Pilot Zones significantly reduce corporate cost stickiness through three mechanisms — labor structure, R&D investment, and internal controls. The effect is stronger for non-SOEs, high information asymmetry firms, and those with overconfident managers."
>
> "**What I learned:** First, **how to design a rigorous empirical study** — from identifying a research gap, to choosing an identification strategy, to cleaning data, running regressions, and testing robustness. Second, **that research questions can come from personal experience.** Third, **the value of persistence** when results weren't clean and robustness checks failed."
>
> "I recognize this study has limitations — the sample covers only listed firms, the policy has been in place for only five years. **But I believe this thesis makes a meaningful first step** in connecting macroeconomic policy to micro-level cost behavior."
>
> "Thank you. I welcome your questions."

## 视觉设计建议

### 图表替换方案

| 论文表格 | 替换为 | 所在Slide |
|----------|--------|:---------:|
| 表6-1 描述性统计 | 关键变量分布密度图/箱线图 | 4 |
| 表6-3 基准回归 | 系数森林图（Forest Plot），突出 DID=0.110*** | 5 |
| 表7-1/2/3 机制检验 | 三通路路径流程图 + 系数标注 | 6 |
| 表7-4/5/6 异质性 | 分组对比柱状图（显著标星） | 7 |

### 色调方案

- **主色**：#1e40af（深蓝）— 标题、主要元素
- **强调色**：#3b82f6（亮蓝）— 图表主要系列
- **高亮色**：#f59e0b（金色）— 关键系数、核心结果
- **警示色**：#ef4444（红色）— 负向关系、p值标注
- **背景色**：#f3f4f6（浅灰）— 页内卡片背景

### 布局模板

1. **左侧文字页**（Slide 2-3）：左文右图，文字占比1/3
2. **图表主导页**（Slide 5、7）：全页图表，底部一小行结论
3. **流程图页**（Slide 6）：自上而下的三通路箭头图
4. **对比页**（Slide 7）：左右/上下分栏，彩色 vs 灰色

## Q&A 准备

### 高频预测问题

**关于识别策略：**
1. "为什么选择DID而不是PSM或其他方法？"
   - DID利用外生政策冲击识别因果，比PSM更直接控制时间不变异质性和共同时间趋势
2. "平行趋势假设可能不成立的情况？"
   - 讨论了，事件研究图显示政策前系数不显著

**关于机制：**
3. "如何排除三条机制之间的相互干扰？"
   - 分别纳入模型检验，每条的中介效应独立显著
4. "劳动力结构和研发投入会不会存在反向因果？"
   - 使用滞后变量作为稳健性检验

**关于数据：**
5. "为什么选择2016-2024这个窗口？"
   - 对称覆盖政策前后，DID需要充足的时间维度
6. "样本选择偏差问题？"
   - PSM-DID作为稳健性检验解决了这个问题

**关于局限：**
7. "研究有哪些不足？"
   - 仅上市公司样本、政策仅五年、不能完全排除所有混淆因素
   - （坦承不足展现学术成熟度）

### 应答策略

- **知之为知之**：数据、模型、结果相关问题直接回答
- **不足坦承**：涉及局限性时先承认再说明为何不影响结论
- **"好问题"开场**：对挑战性问题先说"That's a great question"，争取思考时间

## 演讲注意事项

1. **语速控制**：约130-150词/分钟，关键结论放慢
2. **眼神交流**：轮流看三位评委，不要盯屏幕
3. **手势配合**：重要系数用手指向图表对应位置
4. **停顿制造张力**：讲完姥爷故事→"But then..." 停一下
5. **时间敏感**：听到"12分钟"提示时自然过渡到Slide 8（稳健性），跳过不重要的细节
