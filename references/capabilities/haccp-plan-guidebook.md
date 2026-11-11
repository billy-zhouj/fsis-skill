# 能力卡：FSIS HACCP 计划编写指南（FSIS-GD-2020-0008 / 9 CFR 417）

> 定位：**企业侧「一份 HACCP 计划到底怎么从零写出来」的官方操作手册**。一手源是 FSIS《Guidebook for the Preparation of HACCP Plans》（FSIS-GD-2020-0008，2020-10，52 页），`sources/FSIS-GD-2020-0008-Guidebook-HACCP-Plans.md`。本卡【指南】标注均指该文件；【417】【304】【381】指包内对应 eCFR 源文档。**指南本身无法律效力**——它把 9 CFR 417 的条文拆成可操作的工作表，法定义务仍以 CFR 条文为准，模板与表单「不要求必须采用」。

## A2 — 触发场景

### 用户会在什么情境下遇到这类问题？
- 新厂获准检验、新产品投产，要从零写产品描述、流程图、危害分析、HACCP 计划，不知道先做哪一步、一共要交几张表。
- 被问「我们的产品归 9 CFR 417.2(b)(1) 九类里的哪一类」，或「鲶鱼是不是 slaughter 类」。
- 危害分析表里某一行判了 RLTO=Yes / No，不确定下一步该不该设 CCP、CCP 放在本步骤还是后续步骤。
- 关键限值该从哪儿取、能不能直接抄 FSIS 通用模型里的 45 °F / 600 ppm。
- 分不清初始验证 / 持续验证 / 再评估，或把验证支撑文档按 1 年 / 2 年销毁。
- 检查员开 NR 指「危害分析支撑文档不全」「CCP 判定没有依据」「发货前复核没签字」。

### 语言信号（用户的话里出现这些就应激活）
- “Guidebook / FSIS-GD-2020-0008 / HACCP 计划编写 / 预备步骤 preliminary steps / HACCP 七原则 / 加工类别 process category / 九类 / CCP 判定树 NACMCF decision tree / 工作表 worksheet / 危害分析怎么填 / 关键限值从哪来 / 发货前复核 / 记录保存 1 年 2 年 / 产品描述表”。

### 与相邻能力卡的区分
- `haccp-417`：417 全部法条框架与企业义务本体（**必须有什么**）。本卡是**怎么一步步写出来**（顺序、工作表、判断路径）。
- `haccp-validation-2015`：只深挖 §417.4(a)(1) 初始验证两要素、90 天、COP。本卡把验证放在七原则之六，同时给持续验证与再评估的全景，且更偏「写计划时的表格怎么填」。
- `hav-task-5000.6`：检查员侧 HAV 验证脚本（他会怎么查）。本卡是企业侧编写脚本。
- `haccp-generic-models`：FSIS 三份通用模型的**成品示例**（某个产品类别的 CCP 与关键限值长什么样）。本卡是**通用方法**；先看本卡定结构，再回模型找同类参考。
- `ssop-model-2020`：书面 SSOP 模板与 416 义务。本卡只把前提方案作为「预备步骤 1」的一环，不展开 SSOP 细节。
- `dual-jurisdiction`：FDA 21 CFR 117 的 hazard analysis / preventive controls 是另一套，不套用本卡的九类与本卡的工作表。

## 法定依据（逐条，法条锚点不因指南而变）

- **§417.2(a)(1)**：书面危害分析须判定生产过程中 reasonably likely to occur (RLTO) 的食品安全危害并列出预防措施，覆盖**进厂前、中、后**。【417】
- **§417.2(a)(2)**：须有流程图描述各工序与产品流向，并识别终产品的**预期用途或消费者**。【417】产品描述表把预期用途写进去，是满足该款的一种做法（见通用模型脚注）。
- **§417.2(b)(1)**：按**九类加工类别**给产品分组。【417】指南【预备步骤 5】逐类列示例，见下「核心机制」。
- **§417.2(c)**：HACCP 计划七要素；**§417.2(c)(2)** 各 CCP 的关键限值。**§417.1** 定义 critical limit = 「为防止、消除或将已识别危害降到可接受水平，CCP 处须控制的物理/生物/化学危害的最大值、最小值或区间」。【417】
- **§417.3(a)**：偏离关键限值时的书面纠偏程序与四步处置。【417】
- **§417.4(a)(1)(2)(3)**：初始验证 / 持续验证 / 至少年度再评估（另见 `haccp-validation-2015`）。【417】
- **§417.5(a)(1)(2)**：书面危害分析须含**全部**支撑文档；计划须含 CCP 与关键限值选择的决策文档，以及监控、验证程序及其**频率**的依据。【417】指南据此明确「验证支撑文档须留存 **life of the plan**」。【指南·Principle 6】
- **§417.5(b)(c)(e)**：每条记录须由制作人签署/缩写并注明日期；**发货前**须复核该批产品记录的完整性（含关键限值是否达标、纠偏与产品处置），且**在可行时由非记录制作人**签署、最好是 §417.7 培训合格人员；记录期：屠宰活动 ≥1 年、冷藏品 ≥1 年、冷冻品 ≥2 年、耐储品 ≥2 年，**满 6 个月可异地存放但须在 FSIS 要求后 24 小时内可取**。【417；指南·Principle 7】
- **§417.7**：再评估须由按该条培训合格的人员执行。【417；指南·Principle 6】
- **法规已直接确立的关键限值示例**：禽类胴体带可见粪便不得进入冷却槽（**§381.65(f)**「Procedures for controlling visible fecal contamination」，须写入 HACCP 计划、SSOP 或其他前提方案；指南 Principle 3 以此作为「法规确立 CL」的示例）。**勿与 §381.65(g) 混淆**——(g) 是「整个屠宰与修整过程防肠道病原/粪便污染的书面程序 + 按 (g)(1)(2) 部位与频率做微生物采样分析」的另一项义务。其余关键限值须来自技术/科学文献或法规，不能凭经验设定。

## 核心机制

### 一、预备五步（Preliminary Steps，写危害分析之前）
1. 建立基本**前提方案**（prerequisite programs）——SSOP、GMP、采购规格、过敏原控制、虫害控制等。
2. 组建 **HACCP 小组**，至少含 1 名受过 HACCP 培训的人员；指南强调小组要取得管理层持续支持。
3. 描述食品与生产/分销方式，识别**预期用途与消费者**（含 at-risk populations）。
4. 绘制并**现场验证**流程图（观察实际作业、草稿、班组核对）。
5. 按 §417.2(b)(1) 的**九类加工类别**给产品分组。

**九类（指南 p.14–15 原表）**：(i) Slaughter—所有屠宰物种；(ii) Raw product—non-intact（绞碎、机械嫩化）；(iii) Raw product—intact（整块肌肉、大块分割）；(iv) Thermally processed—commercially sterile；(v) Not heat treated—shelf stable；(vi) Heat treated—shelf stable；(vii) Fully cooked—not shelf stable；(viii) Heat treated but not fully cooked—not shelf stable；(ix) Product with secondary inhibitor—not shelf stable。

### 二、HACCP 七原则（指南主线，逐条附工作表）
1. **危害分析**：三类危害（生物/化学/物理）逐步骤列出 → 判 RLTO（Yes/No）→ 写判定依据 → 写可采取的预防/消除/降低措施 → 判是否 CCP。判定依据必须可信、有文档、可回源。
2. **确定 CCP**：NACMCF 判定树（Attachment 5）。**Attachment 4 里每一个 RLTO=Yes 都必须对应一个 CCP**，可落在该步骤或**后续任一步骤**；不同厂做同类产品，CCP 数量与类型可以不同，属正常。
3. **关键限值**：每个 CCP 每项预防措施都要有确切、具体的 CL（温度、时间、pH、Aw、有效氯、浓度等）；须来自底层研究或法规，**建议用原始研究里的 CL 而不是只抄 FSIS 汇总值**。可设 target level 做偏离预警，但 target ≠ CL。
4. **监控**：What / How / Frequency / Who 四要素；监控须能及时发现偏离，且须写明频率的依据。
5. **纠偏**：§417.3(a) 四步——① 留置并处置上次合格检查以来的全部产品 ② 查明并消除偏离原因 ③ 恢复过程控制 ④ 防止再发；另须评估受影响产品是否可进入商业流通。
6. **验证**：初始验证（设计 + 执行两要素，见 `haccp-validation-2015`）→ 持续验证（校准、直接观察、记录复核，§417.4(a)(2) 开放式列举）→ 再评估（至少年度 + 变更触发，§417.4(a)(3)）。年度再评估若判定无需修改，**不要求**记录理由；其他情形须记录改与不改的理由。
7. **记录保持**：Attachment 7（验证与记录程序）、Attachment 8（HACCP Master Sheet）；指南强调「最有效的记录系统通常是最简单、能嵌进现有作业的那套」。

### 三、八张可选工作表（Attachment 1–8）
产品描述 / 配料与进料清单 / 流程 diagram / 危害分析与预防措施 / CCP 判定 / 关键限值·监控·纠偏 / 验证与记录保持 / HACCP Master Sheet。**全部是 optional**——企业可用自有表单，只要能证明满足 417.2–417.5。

## 边界与易错点

- **指南无法律效力**：`guidance documents lack the force and effect of law`；不得把工作表、模板、示例表单写成法定义务。§417 条文原文以正文形式嵌在指南里，引用时挂条号不挂页码。
- **鲇形目（catfish）不归入 (i) Slaughter 类**【指南脚注 3】：FSIS 认定典型鱼类「屠宰 + 加工」是同一连续自动化流程，更像**加工类**作业而非传统屠宰；依据见《Changes to the Inspection Coverage in Official Establishments That Slaughter Fish of the Order Siluriformes》。写鲶鱼计划时照搬畜/禽 slaughter 类别是错的。
- **417.2(b)(1) 法条原文写的是 "Raw product—ground" / "Raw product—not ground"，不是 non-intact / intact**【指南脚注 4】：FSIS 澄清术语以把机械嫩化、真空滚揉产品纳入 non-intact（参见 64 FR No.11, 1999-01-19）。这与 `hav-task-5000.6` 的 **Table 1 十类 ≠ 法定九类**是同一处命名差异，三套类别名（法条 ground/not ground、指南 non-intact/intact、5000.6 Table 1 十类）不要混写。
- **90 天不在 §417.4 条文里**：法源是 §304.3(b)(c)（畜）/ §381.22(b)(c)（禽）。
- **验证支撑文档 life of the plan ≠ 日常记录 1 年 / 2 年**：前者属 §417.5(a)(1)(2) 的决策/支撑文档，后者是 §417.5(e) 的运行记录。
- **关键限值不能照抄通用模型**：模型 CL 是示例，且 poultry 的 45 °F/6 h 来自 SIP 路径的 safe harbor（另有「被删旧时间温度表」路径，见 `haccp-generic-models`）、catfish 的「可见金属碎片」是特定工艺下的示例；企业须用本厂工艺的科学支撑重新论证。
- **发货前复核的签字人**：可行时须由**非记录制作人**签署，最好为 §417.7 培训合格人员；不是随便找个主管签。

## 专家注记（写计划时最常返工的三处）

1. **危害分析判了 NRLTO 却只有一句「由 SSOP 控制」**：前提方案一旦被用作 NRLTO 的依据，就并入 HACCP system，须按两要素验证并留下支撑文档（`haccp-validation-2015` Step 4 / 5000.6 Step 4.C 四问就是检查员评分表）。
2. **CCP 判定与 RLTO 列对不上**：Attachment 4 里有 Yes 却没在流程任何一步设 CCP，或反过来把质量参数设成 CCP（CCP 只管食品安全危害）。
3. **记录系统做成「二次整理表」**：原始记录被汇总表替代、验证支撑文档按日常记录期销毁、发货前复核由记录制作人自己签——三处都能直接触发 NR。

## 审计信息

- **一手源**：`sources/FSIS-GD-2020-0008-Guidebook-HACCP-Plans.md`（52 页，正文 1792 行 / 96K 字符，34 个书签章节 + 8 张附件工作表）。2026-11-11 由用户上传 PDF 按词坐标重建：书签生成 `##`/`###`/`####` 层级，表格按版面 y 行保序 + 矢量网格列边界切列为 GFM，剔除目录页（PDF p.4）、逐页免责声明与页码。
- **保真校验**：与 PDF 原文长句全量对撞 **1092/1092 命中**、同口径词袋零丢失；以未做任何剔除的原始 PDF 全文实词为基准仅差 4 个封面装饰词（`usda`/`small`/`non`/`me`）。
- **版本核验**：2026-11-11 查 FSIS guidance portal 与 Small & Very Small Plant Guidance 列表：**FSIS-GD-2020-0008，Issue Date October 2020**，现行；旧版页面曾标 Sep 2020，以 guidance portal 为准。另有 USDA 官方中文译本（本包未并入）。
- **已知限制**：决策树页（PDF p.16、p.29）为矢量图形，文本层仅存方框散字，按坐标重建后个别散字被识别为短标题；复杂工作表的合并单元格按版面 y 行展开，未按逻辑行合并。
- **法条回源**：§417.1–417.8 查 `sources/9-CFR-Part-417-2026eCFR.md`；§304.3(b)(c) 查 `sources/9-CFR-Part-304-Official-Establishments-2026eCFR.md`；§381.22(b)(c) 与 381.65(f)(g) 查 `sources/9-CFR-Part-381-Poultry-2026eCFR.md`。
- **蒸馏时间**：2026-11-11 ｜ **关联卡**：haccp-417、haccp-validation-2015、haccp-generic-models、hav-task-5000.6、ssop-model-2020、siluriformes-china
