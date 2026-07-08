# SCOR供应链运作参考模型

SCOR 是用于描述、衡量和改进供应链流程的参考模型；本文明确区分旧版 SCOR 的线性五流程和当前 SCOR Digital Standard 14.0 的七个管理流程，避免将历史材料拼接成“最新标准”。

**状态**：已核验  
**最后更新**：2026-07-06  
**复核触发条件**：ASCM 发布新版 SCOR，或补充正式 SCOR 12 原文

## 模型来源与价值

SCOR（Supply Chain Operations Reference）最早由国际供应链理事会 SCC 于 1996 年提出，SCC 后并入 APICS，现由 ASCM 维护。[来源:SRC-002，PDF第8页]

其核心价值是提供跨企业的共同流程语言，将流程、绩效指标、实践和人员能力关联起来，用于诊断现状和设计改进方案。[来源:SRC-001，DOCX段落122]

## 历史版本：五大流程

知识库原始资料主要描述 SCOR 12 及更早版本的五个一级流程：[来源:SRC-001，DOCX段落122-134]

| 流程 | 含义 |
|---|---|
| Plan | 平衡需求与资源，形成采购、生产、交付和退货计划 |
| Source | 采购、接收、核验、转运和付款授权 |
| Make | 将原料或输入转化为产品，包括生产、检测、包装和暂存 |
| Deliver | 订单确认、拣配、运输、安装和交付 |
| Return | 识别、处置和逆向运输退回物品 |

这套五流程仍具有历史和教学价值，但不能再称为“当前最新 SCOR”。SRC-002 称 SCOR 已发展到第12版，反映的是该资料成文时采用的旧口径。[来源:SRC-002，PDF第8页]

## 当前版本：SCOR DS 14.0

截至 2026-07-06，ASCM 官方发布的 SCOR Digital Standard 为 14.0，采用一个 Level 0 流程和六个 Level 1 流程：

| 层级 | 流程 | 与旧版关系 |
|---|---|---|
| Level 0 | Orchestrate | 新增顶层编排，覆盖战略、规则、数据、技术、风险、ESG 和网络设计等 |
| Level 1 | Plan | 保留计划职能 |
| Level 1 | Order | 将客户购买和订单信息作为独立流程 |
| Level 1 | Source | 保留寻源与采购职能 |
| Level 1 | Transform | 扩展并替代旧版 Make，同时覆盖产品和服务转化 |
| Level 1 | Fulfill | 扩展并替代旧版 Deliver |
| Level 1 | Return | 保留并扩展逆向流与循环活动 |

[外部核验:ASCM《SCOR Digital Standard 14.0》，2026-07-06访问](https://www.ascm.org/globalassets/ascm_website_assets/docs/scor/intro-and-front-matter-scor-digital-standard-2025.pdf)

ASCM 将其描述为从线性供应链模型转向同步网络，并增加可持续性和供应链编排能力。[外部核验:ASCM SCOR DS介绍，2026-07-06访问](https://www.ascm.org/corporate-solutions/standards-tools/scor-ds/)

## 流程层级

SRC-001 将模型概括为供应链划分、配置和流程元素三个层次。[来源:SRC-001，DOCX段落122]

SRC-002 的后部章节则将流程描述为 Level 1—4，其中第四层是企业自己的实施流程，而不是 SCOR 提供的统一标准内容。[来源:SRC-002，PDF第217页]

ASCM SCOR 14.0 聚焦行业中立的 Level 0—3，并明确要求采用 SCOR 改进供应链的组织至少扩展到 Level 4，以补充行业、组织、地点特定的流程、系统和实践。[外部核验:ASCM《SCOR Digital Standard 14.0》第v页，2026-07-06访问](https://www.ascm.org/globalassets/ascm_website_assets/docs/scor/intro-and-front-matter-scor-digital-standard-2025.pdf)

因此，SCOR 提供标准化的上层流程层级，企业需要继续设计 Level 4 实施流程。SRC-001 的“三层”与 SRC-002 的“四层”主要是是否把企业实施层计入描述的口径差异。

## 覆盖边界

SCOR 14.0 覆盖从订单录入到回款的客户交互、从供应商的供应商到客户的客户之间的实物交易，以及从理解汇总需求到履行每个订单的市场交互，但并不描述所有业务活动。[外部核验:ASCM《SCOR Digital Standard 14.0》第v页，2026-07-06访问](https://www.ascm.org/globalassets/ascm_website_assets/docs/scor/intro-and-front-matter-scor-digital-standard-2025.pdf)

ASCM 明确说明 SCOR 14.0 不覆盖：

- 销售与营销，包括需求创造。
- 产品开发。
- 研究与开发。

新增 `Order` 和 `Orchestrate` 扩展了订单、战略编排、数据、风险、网络设计等供应链管理活动，但不能据此推断销售营销、产品开发或研发已经纳入 SCOR。边界判断应以 ASCM 官方范围说明为准，而不是仅凭流程名称推演。

## 指标使用原则

客户满意度、库存周转率、订单履行周期和成本等可以作为供应链改进指标，但华为案例中的具体改善幅度是企业二手案例数据，不是 SCOR 标准值。[来源:SRC-002，PDF第33页]

使用 SCOR 时应先明确：

1. 采用的 SCOR 版本。
2. 指标定义和统计范围。
3. 基准期与目标期。
4. 企业自定义流程与标准流程的映射关系。

## 分歧与待核验

- SRC-001 的“三层”与 SRC-002 的“四层”属于统计口径差异，已保留两种解释。
- SRC-002 同时包含五流程、第12版、包含 Enable 的六流程等内容，说明它汇编了不同版本材料，不能作为当前版本的单一权威来源。
- 原笔记中的 BTS、MTO、ETO 是企业生产策略或配置，不应直接写成 SCOR 当前版本支持模式。

## 相关主题

- [[供应链基础概念]]
- [[华为ISC集成供应链变革]]
- [[物流规划方法论]]
- [[来源目录]]

## 来源

- `SRC-001`：SCOR 旧版流程及物流规划中的应用。
- `SRC-002`：SCOR 历史、层级和华为案例；属于二手汇编。
- ASCM 官方 SCOR DS 页面和 14.0 文档：当前版本核验。
