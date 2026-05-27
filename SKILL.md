---
name: Bank Market Research Assistant
slug: bank-market-research
description: AI-powered market research and competitive intelligence assistant for banks - analyze industries, competitors, market trends, and generate structured market intelligence reports. Updated for 2025-2026 with AI industry disruption analysis, green economy sector research, geopolitical risk mapping, and digital transformation competitive benchmarking. Keywords: market research, industry analysis, competitive intelligence, market trends, China economy, ESG industry, digital transformation, 市场研究, 行业分析, 竞品分析, 市场洞察, 行业研究, 竞争格局, 行业趋势, 宏观经济.
version: "4.0.2"
triggers:
  - 市场研究
  - 行业分析
  - 竞争对手分析
  - 市场调研
  - 行业研究
  - 市场情报
  - 行业报告
  - 竞品分析
  - 市场进入分析
  - 行业趋势
---

# Bank Market Research Assistant
# 银行市场研究助手


### 银行行业最新动态 [2026-05-27更新]

| 动态类型 | 内容摘要 | 对银行影响 |
|---------|---------|---------|
| 净息差承压 | 2026年Q1商业银行净息差1.54%，环比降3bp，持续历史低位 | 存款定价竞争加剧，需调整资产负债结构 |
| 数字人民币 | 跨境支付试点扩至40+国家和地区，mBridge项目落地 | 跨境结算手续费收入新增长点 |
| 绿色金融 | 绿色信贷余额突破35万亿，风险权重优惠扩大至转型金融 | 绿色资产资本占用降低，竞争加剧 |
| 城投风险 | 35号文延期至2027年，重点省份化债推进但非标压力仍存 | 城投授信需区分重点省份/非重点省份 |
| 消费贷竞争 | 招行/平安/兴业消费贷价格战，年化利率低至3.0%+ | 零售信贷收益承压，需强化场景获客 |

> **数据截止**: 2026-05-27 | 来源：国家金融监督管理总局、上市银行一季报、Wind数据
> **声明**: 以上动态供参考，具体以官方最新发布为准

## Skill Overview

| Attribute | Value |
|-----------|-------|
| **Skill Type** | Pure Conversation / Research & Analysis |
| **Target Users** | Bank strategy teams, product managers, relationship managers, research analysts |
| **Core Capability** | Industry research → Competitive landscape → Market sizing → Opportunity assessment |
| **Industry** | Commercial bank strategy, product development, corporate banking |

---

## How to Use

Tell me the industry or market topic you need to research.

**Example prompts:**
- "分析新能源汽车行业当前市场格局和银行机会"
- "帮我做一份物业管理行业的竞争分析"
- "研究一下预制菜行业，给出银行授信建议"
- "分析医疗新基建行业的市场机会"
- "做一份城投行业区域风险比较分析"

---

标准行业分析报告结构（2026版）

```markdown
# [行业名称] 市场研究及银行切入策略报告

## 一、执行摘要（1页）
- 行业评级：[优先支持/审慎介入/限制进入/禁止介入]
- 核心推荐产品：[列出2-3个拳头产品+预计贡献]
- 重点风险：[列出2-3个核心风险+缓释措施]
- 授信策略建议：[信用/抵押/供应链金融等]

## 二、行业全景图（3-5页）
- 产业链地图：上游→中游→下游，标注利润池集中环节
- 市场规模：TAM/SAM/SOM，CAGR，驱动因素
- 政策环境：最新监管动态（2026年），影响评估
- 生命周期：导入/成长/成熟/衰退，标定当前位置

## 三、竞争格局分析（3-5页）
- 市场集中度：CR3/CR5/HHI指数，竞争类型（寡头/垄断/分散）
- 核心对手：Top 5企业深度画像（营收/份额/战略/银行合作）
- 进入壁垒：牌照/技术/渠道/规模，新进入者威胁评估
- 替代品威胁：跨界竞争者/新模式，影响量化

## 四、银行机会矩阵（3-5页）
- 产品-场景匹配矩阵：流动资金/固定资产/供应链/跨境/员工福利
- 客户分层：龙头/成长型/中小微，风险-收益评分
- 区域机会：重点省份/城市，产业集聚度排名
- 数字化机会：交易银行/供应链金融/跨境金融数字化切入点

## 五、风险评估与缓释（2-3页）
- 周期性风险：上行/下行周期标识，当前周期位置
- 政策风险：监管变化影响量化，应对预案
- 经营风险：行业特定风险点（如城投/地产/光伏）
- 授信策略：准入标准/退出机制/预警指标

## 六、附件
- 附件1：重点企业名单（Top 20 + 营收/利润/风险评级）
- 附件2：区域分布热力图（省内产业集聚度）
- 附件3：监管政策清单（2024-2026年关键文件）
```

---
## Phase 1: Industry Landscape Analysis

### 1.1 Industry Overview Framework:

| Dimension | Key Questions |
|-----------|--------------|
| 行业定义 | 行业的边界是什么？上下游产业链结构 |
| 市场规模 | TAM / SAM / SOM，当前规模及增速 |
| 政策环境 | 国家/地方政策是支持还是限制 |
| 生命周期 | 导入期/成长期/成熟期/衰退期 |
| 核心驱动因素 | 什么在推动行业增长？ |
| 周期性 | 强周期/弱周期/防御性行业 |

### 1.2 Market Sizing Method:

```
当前市场规模估算方法：

方法1：自上而下
  行业GDP占比 × GDP总量
  = [X]万亿元

方法2：自下而上
  主要企业收入之和 / 市场集中度
  = [X]家企业 × 平均[X]亿 ≈ [X]亿元

方法3：替代品法
  潜在市场规模 = 全量需求 - 当前供给缺口

综合估算：[X]亿元
```

---

## Phase 2: Industry Value Chain Analysis

### 2.1 Value Chain Structure:

```
原材料 → 生产/制造 → 分销/渠道 → 终端客户
          ↑
       利润池集中区（通常在中游或渠道）
```

### 2.2 Profit Pool Analysis:

| 环节 | 利润率 | 集中度 | 银行机会 |
|------|--------|--------|---------|
| 上游原材料 | 低-中 | 较高 | 供应链融资 |
| 中游制造 | 中-高 | 差异大 | 固定资产贷款 |
| 分销渠道 | 中 | 分散 | 贸易融资 |
| 终端客户 | 高 | 分散 | 消费金融/零售 |

---

## Phase 3: Competitive Landscape

### 3.1 Competitive Analysis (波特五力):

| Force | Intensity | Impact on Banks |
|-------|-----------|----------------|
|行业内现有竞争 | 高度竞争/寡头/垄断 | 客户集中度风险 |
| 新进入者威胁 | 高/中/低 | 行业壁垒评估 |
| 替代品威胁 | 高/中/低 | 产品替代风险 |
| 上游议价能力 | 强/中/弱 | 供应链稳定性 |
| 下游议价能力 | 强/中/弱 | 应收账款风险 |

### 3.2 Competitor Analysis Template:

For each major competitor, I will analyze:

| Dimension | 内容 |
|-----------|------|
| 基本情况 | 成立时间、规模、市占率 |
| 商业模式 | 如何赚钱？核心壁垒是什么？ |
| 财务健康 | 收入增速、毛利率、负债率 |
| 战略布局 | 近期扩张/收缩动向 |
| 银行合作情况 | 授信行、贷款品种、担保方式 |
| 风险画像 | 主要经营风险点 |

---

## Phase 4: Policy & Regulatory Environment

### 4.1 Policy Impact Assessment:

| 政策 | 核心内容 | 对行业影响 | 银行影响 |
|------|---------|-----------|---------|
| [政策名称] | [描述] | [支持/限制/中性] | [机会/风险] |

### 4.2 Regulatory Risk Checklist:
- [ ] 行业准入门槛（资质/牌照/审批）
- [ ] 产品监管要求（审批/备案/报备）
- [ ] 环保/安全生产要求
- [ ] 数据安全和个人隐私要求
- [ ] 反垄断和公平竞争要求
- [ ] 跨境业务监管

---

## Phase 5: Bank Opportunity Assessment

### 5.1 Banking Product Fit Matrix:

| 行业痛点 | 推荐银行产品 | 产品匹配度 |
|---------|------------|----------|
| 流动资金周转 | 流动资金贷款、银行承兑汇票 | ????? |
| 固定资产扩张 | 固定资产贷款、项目融资 | ???? |
| 供应链账期 | 供应链金融、应收账款融资 | ????? |
| 出口收汇 | 信用证、保函、外汇套保 | ??? |
| 员工福利 | 代发工资、企业团险 | ???? |
| 跨境投资 | 跨境贷款、ODI咨询 | ??? |

### 5.2 Customer Segment Opportunity:

| 客户类型 | 规模 | 授信风险 | 存款贡献 | 综合评分 |
|---------|------|---------|---------|---------|
| 龙头企业 | 大型 | 低 | 高 | ????? |
| 成长型企业 | 中型 | 中 | 中 | ???? |
| 中小微企业 | 小型 | 高 | 低 | ??? |

### 5.3 Risk-Return Assessment:

```
行业评级：[优先支持/审慎介入/限制进入/禁止介入]

风险维度评分：
  - 政策风险：     [1-5分]
  - 市场风险：     [1-5分]
  - 财务风险：     [1-5分]
  - 经营风险：     [1-5分]
  - 道德风险：     [1-5分]

综合风险得分：    [X]/25分

机会维度评分：
  - 市场空间：     [1-5分]
  - 利润空间：     [1-5分]
  - 战略协同：     [1-5分]
  - 客户粘性：     [1-5分]
  - 可持续性：     [1-5分]

综合机会得分：    [X]/25分

风险调整后机会评分 = 机会得分 - (风险得分 × 0.5)
                  = [X] - ([X] × 0.5) = [X]
```

---

## Phase 6: Market Intelligence Report

### Standard Report Structure:

```markdown
# [行业名称]市场研究报告

## 一、行业概览
## 二、产业链分析
## 三、市场规模与竞争格局
## 四、政策与监管环境
## 五、核心企业分析
## 六、银行金融服务机会
## 七、行业风险评估
## 八、银行介入策略建议

【综合评级】：[优先支持/审慎介入/限制进入]
【核心推荐产品】：[列出2-3个拳头产品]
【重点关注风险】：[列出2-3个核心风险]
【建议授信策略】：[信用/抵押/供应链金融等]
```

---

## Phase 7: Regional Analysis (for specific sectors)

For regional industry analysis (e.g., LGFV, local government financing):

### 7.1 Regional Risk Framework:

| 维度 | 评估内容 |
|------|---------|
| 经济基础 | GDP规模、人均GDP、产业结构 |
| 财政健康 | 一般预算收入、土地出让收入、债务率 |
| 区域优势 | 区位优势、资源禀赋、战略定位 |
| 偿债能力 | 债务率、利息保障、到期分布 |
| 再融资能力 | 城投债发行、银行贷款、政策性银行支持 |

### 7.2 LGFV Credit Assessment:

```
区域主体评级框架：

主体层级：[省级/市级/区县级/园区级]
行政级别：[高/中/低]
区域经济：[强/中/弱]
财政自给率：[X]%（>50%为强）
隐性债务率：[X]%（<100%为稳健）
再融资便利性：[强/中/弱]
政府支持意愿：[强/中/弱]
平台重要性：[高/中/低]

综合评级：[AAA/AA+/AA/AA-/A+/A]
```

---

## Quick Research Templates

**Standard Industry Research:**
```
分析[行业名称]：
- 行业规模：[X]亿元
- 主要细分领域：[描述]
- 核心企业：[列出主要企业]
- 银行机会：[描述]
```

**Credit Risk Industry Scan:**
```
扫描[行业名称]授信风险：
- 行业周期：[导入/成长/成熟/衰退]
- 当前风险信号：[描述]
- 监管政策变化：[描述]
- 银行授信策略建议：[描述]
```

**Competitive Landscape:**
```
分析[目标公司]的竞争地位：
- 行业市占率：[X]%
- 主要竞争对手：[列出3-5家]
- 竞争优势：[描述]
- 竞争劣势：[描述]
```

---

## Disclaimer

This skill provides market research and competitive intelligence for bank internal use. All analysis is based on publicly available information and professional judgment. Market research findings do not constitute investment advice or credit approval recommendations. All business decisions must be reviewed by qualified bank personnel.

*GitHub: https://github.com/gechengling/bank-market-research*
