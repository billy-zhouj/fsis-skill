# 能力卡：FSIS 通用 HACCP 模型选用与 CCP 设定（鲶鱼 / 禽类屠宰）

> 定位：**「同类产品的 HACCP 计划长什么样」的成品示例对照**。一手源为两份 FSIS 通用模型：`sources/FSIS-GD-2022-0006-HACCP-Model-Raw-Intact-Farm-raised-Catfish.md`（FSIS-GD-2022-0006，2022-08，14 页）与 `sources/FSIS-GD-2020-0013-HACCP-Model-Poultry-Slaughter.md`（FSIS-GD-2020-0013，2020-11，19 页）。本卡【鲶鱼模型】【禽模型】标注即指二者；【417】【381】指包内 eCFR 源。**模型仅作示范（for demonstration purposes only），不设新义务，不得照抄**。

## A2 — 触发场景

### 用户会在什么情境下遇到这类问题？
- 接手一条鲶鱼（生、整块）或禽类屠宰线，要写危害分析，想找同类别的官方示例看 CCP 怎么设、关键限值填什么。
- 拿着 FSIS 通用模型准备直接改成自家 HACCP 计划交上去，需要判断哪些字段必须重做。
- 检查员质疑「为什么你这个危害判了 NRLTO」「为什么只有 1 个 CCP / 有 3 个 CCP」，需要找到判定依据的写法范本。
- 问「45 °F / 6 小时是不是法规规定的冷却限值」「600–700 ppm 能不能直接用」。
- 分不清 NPIS 家禽屠宰模型与非 NPIS 家禽屠宰模型，或分不清养殖鲶鱼与野捕鲶鱼模型。
- 想用 SSOP、供应商 LOG、批准供应商计划等前提方案论证某危害不 RLTO，不清楚会连带什么义务。

### 语言信号（用户的话里出现这些就应激活）
- “generic HACCP model / 通用模型 / 鲶鱼 HACCP 模型 / catfish model / 家禽屠宰 HACCP 模型 / poultry slaughter model / CCP 1 / CCP 2 / CCP 3 / 金属探测 / 600–700 ppm / 45 °F 6 小时 / zero fecal / 可见金属碎片 / NRLTO 判定 / 模型能不能照抄 / FSIS-GD-2022-0006 / FSIS-GD-2020-0013”。

### 与相邻能力卡的区分
- `haccp-plan-guidebook`：写计划的**通用方法**（预备五步 + 七原则 + 八张工作表）。本卡是**两个具体类别的成品**；先看方法定结构，再回本卡找同类参照。
- `haccp-417`：法条框架；`haccp-validation-2015`：初始验证两要素。本卡脚注大量引用这两者，但不展开。
- `poultry-381`：禽类法规义务（NPIS/传统线速、381.65/381.66 冷却、381.94 ratites E. coli）。本卡是**企业 HACCP 计划示例**，不是法条。
- `siluriformes-china`：鲇形目管辖、中国输美等效。本卡是该品类在美国官方企业内部怎么写 HACCP 计划。
- `ssop-model-2020`：书面 SSOP 模板。本卡只处理 SSOP 被用作 NRLTO 依据时的连带后果。

## 两份模型横向对照

| 维度 | 鲶鱼（养殖、生整块）FSIS-GD-2022-0006 | 禽类屠宰 FSIS-GD-2020-0013 |
|---|---|---|
| 加工类别落点 | Raw product—intact（**不归 slaughter 类**，见 `haccp-plan-guidebook` 脚注 3） | Slaughter—poultry（另含 parts / other intact poultry products） |
| 流程 | 19 步，含 3a 手工 / 3b 自动去头去内脏双线、鲜品与冷冻品分流；18 退回产品为**未连接**的独立步骤 | 17 步（含 1a 非肉物料接收分支），6 离线再加工/回收、10–12 三个 CCP 连续 |
| 主要生物危害判定 | Salmonella、Salmonella outgrowth **全部判 NRLTO = No** | Salmonella、Campylobacter **判 RLTO = Yes** |
| CCP 数量 | **1 个**：CCP 1 金属探测（物理危害 Foreign Materials） | **3 个**：CCP 1 粪便污染监控、CCP 2 预冷抗菌剂、CCP 3 冷却 |
| 控制逻辑 | 生物/化学危害全靠**前提方案**（书面 SSOP、温度 SOP、化学品收储用 SOP、供应商 LOG、批准供应商计划、过敏原控制 SOP） | 病原体由**三个 CCP 串联**控制：视觉检查 → 抗菌剂 → 冷却 |
| 温度 | ≤ 40 °F 贯穿加工、冷却、冷藏、运输；冷藏 5 天 @40 °F、冷冻 4 个月 @≤0 °F | 胴体 45 °F 以内 6 小时；部位/内脏/颈/爪 44 °F 以内 4 小时（自脱离胴体起算） |
| 抽样 | 金属探测**每件**产品 | **10 胴体 + 10 部位/内脏**，随机时段；不足 10 单位时检查全部可用单位 |
| 化学/过敏原 | 多聚磷酸盐（FSIS Directive 7120.1 准用表，见 `ingredients-7120.1`）、鲶鱼本身为过敏原（靠标签）、消毒剂、未申报过敏原 | 抗菌剂浓度、药物残留、加工助剂 |
| 适用检验系统 | 鲇形目强制检验（2015-12-02 最终规则 80 FR 75590） | **SIS / NELS / NTIS / Traditional 四种，不含 NPIS**（禽模型脚注 2） |

## 鲶鱼模型要点（FSIS-GD-2022-0006）

- **唯一 CCP 1** 落在「3b. Automated – Deheaded and Eviscerated」：危害 = Foreign Materials，关键限值 = **可见金属碎片（visible metal fragments）**；监控 = 包装后产品逐件过金属探测仪，指定员工；纠偏 = §417.3 四步；验证 = 每周主管直接观察监控 + 每周复核记录；记录 = Corrective Action Log、Lab Results Form、Records Review Form、Preshipment Records。
- 危害分析 9 页逐步骤把 **B/C/P 三类危害全部判 No**，依据写法值得照学： Salmonella 用「危害识别研究 + 产品须充分加热后食用 + 有暴发报道但加工中不 RLTO」；Salmonella outgrowth 用「工序时间短 + 符合 FDA《Fish and Fishery Products Hazards and Controls Guidance》Table A-2 (p.421) 时间温度参数 + 书面温度 SOP」；过敏原用「鲶鱼本身是过敏原、靠标签控制」；未申报过敏原用「供应商 LOG + 逐批进货核验 + 批准供应商计划」。
- **脚注 15 的关键连带义务**：前提方案的结果若影响危害分析决策，其记录就是 §417.5(a) 的危害分析支撑文档；一旦企业以某前提方案（SSOP、卫生修整、采购规格、抗菌干预）为由判某危害 NRLTO，该方案**即成为 HACCP system 的一部分且必须验证**（须有设计的科学/技术支撑 + 厂内实施数据），并直接引用 FSIS-GD-2015-0011 p.5。
- **脚注 22**：90 天初始验证期内，若科学支撑含微生物数据且工艺参数与文献一致，厂内数据可只采集可量化 COP（压力、温度、浓度）；若工艺参数与支撑不同、或支撑不含微生物数据，则还须采集厂内微生物数据或另找含微生物数据的支撑（FSIS-GD-2015-0011 p.27）。
- **脚注 18 / 23 的 7120.1 边界**：FSIS Directive 7120.1《Safe and Suitable Ingredients》（含鲇形目专属准用表）可作**化学危害（安全性/适用性）**的支撑，**不能**作为控制**生物危害**的支撑——控制细菌所需抗菌剂浓度与安全适用浓度不同。脚注中的 `FCN# [insert number]` 是源文档占位符，企业须自行填入所用化合物的 FCN 编号。 现有一手源：`sources/FSIS-Directive-7120.1-Rev44-2017-Safe-Suitable-Ingredients.md`（历史版 Rev.44，含 19 处鲇形目条目与十种磷酸盐保水混合物）、`sources/FSIS-Directive-7120.1-Rev63-2026-Current-Portal-Text.md`（现行版 Rev.63 主指令）与 `sources/FSIS-Compliance-Guideline-HACCP-Systems-Validation-2015.md` p.5/p.27（NOL 与 7120.1 不含功效数据与全部 COP，单独作支撑属支撑不足）；方法与版本警示见 `ingredients-7120.1`。
- 退回产品（第 18 步）：须先做退回产品评估 SOP，退回方证明温度与卫生状态，无法证明则拒收或销毁、开封包装不接收；接收时通知 FSIS 人员。

## 禽类屠宰模型要点（FSIS-GD-2020-0013）

- **CCP 1（第 10 步）监控胴体、部位与内脏的粪便污染**：CL = **不得有可见粪便污染物进入冷却系统**；监控 = 目视检查 10 胴体内外表面 + 10 部位/内脏，随机时段；不足 10 单位时全检；验证 = 经理每小时观察一次 CCP 监控活动、每周复核记录（§417.4(a)(2)(iii)）；记录 = Zero Fecal Check Form、Corrective Action Log、Pre-shipment Review Form。
- **CCP 2（第 11 步）预冷抗菌剂应用**：CL = **600–700 ppm 有机酸溶液**；监控 = 配制与混合过程、记录抗菌剂与用水量；验证 = 每班次随机一次经理观察；记录 = Organic Acid Spray Concentration Form。
- **CCP 3（第 12 步）全部产品冷却**：CL = **胴体 45 °F 以内 6 小时；部位/内脏/爪/颈 44 °F 以内 4 小时**（自脱离胴体起算）；监控 = 经校准的手持温度计插入胴体胸肌最厚处 / 部位最厚处，每小时 10 胴体 + 10 部位/内脏；验证 = 经理每个屠宰日观察一次 CCP 监控、每周按厂商程序校准温度计、每周复核记录；记录 = Chilling Form、Thermometer Calibration Form、Corrective Action Log、Pre-shipment Review Form。
- **45 °F/6 h 的来源**（脚注 32）：模型脚注**自述**该 CL 出自参与 **SIP（Salmonella Initiative Program）** 企业所实施的替代程序，FSIS 称其为「safe harbor」，并援引《Guide: Modernization of Poultry Slaughter Inspection: Amendments to Chilling Requirements》（**FSIS-GD-2014-0014**，2014-10，挂 §381.66(b)，无法律效力，**英文原版全文已收录**）；**不是 §381.66 条文直接写定的数值**。该指南的 safe harbor 有**两条路径 + 第三路径**：① 2014 年规则从 §381.66(b) 删除的旧规 **A–H 八款**（A：≤4 lb 4 h→40 °F；4–8 lb 6 h；>8 lb 8 h；冷却后 ≤40 °F；B：加工中可升 55 °F 但包装后立即回 40 °F 或入冷冻；留厂 >24 h 须 ≤36 °F），② SIP 批准程序，③ 企业自定并验证的程序。**★ 但指南 p.6 列举的四条 SIP 示例是 44 °F/6 h（冷却器出口）、45 °F/16 h、≤44 °F 恒定、44 °F/4 h，并不含 45 °F/6 h**——该清单自称 "examples of common alternative procedures" 非穷尽，故不可写成「指南明文列出 45 °F/6 h」；指南中 45 °F 对应的是 16 h。askFSIS 官方 Q&A 确认旧 §381.66(b)(1) 可支撑产品温度 CL。2014 后不再需要 waiver，任何 RTC 禽企业均可采用 SIP 已验证程序且无需再做科学验证（但仍须监控与留记录）。写计划时须回该指南与本厂科学支撑重新论证，不得照抄，也不得写成法定限值。详见 `chilling-requirements-2014`。
- 三处 CCP 的纠偏统一按 **§417.3(a) 四步**：① 留置上次合格检查以来的全部产品并作适当处置（不得让有害健康的产品进入商业流通）② 查明并消除偏离原因 ③ 恢复过程控制 ④ 防止再发。
- 模型脚注引用了当时仍为 **DRAFT** 的《FSIS Compliance Guideline for Controlling Salmonella and Campylobacter in Raw Poultry》；该主题现已拆为 FSIS-GD-2021-0005（Salmonella）与 FSIS-GD-2021-0006（Campylobacter），引用前须核对现行版。

## 边界与易错点（本卡最重要的部分）

- **模型不可照抄**：FSIS 反复声明「for demonstration purposes only」「does not represent requirements that must be met」；每份模型的产品描述、流程图、危害分析、CCP、关键限值、频率与表单都须按本厂设施、生产实践、产品重写。流程图脚注也写明「同一产品的流程图可以不同，但必须覆盖危害分析中所有相关步骤」。
- **关键限值不能从模型搬到本厂**：模型的 CL 是示例且各有出处（poultry 45 °F/6 h 依脚注 32 自述属 SIP 路径的 safe harbor，但 FSIS-GD-2014-0014 p.6 的四条 SIP 示例并不含该数值、其中 45 °F 对应 16 h，见上条；另有「被删旧规 A–H 八款」路径；catfish「可见金属碎片」是该工艺下的示例）。指南要求用**底层研究里的 CL**，且须有可回源的科学/技术支撑。
- **两份禽类模型别混**：本卡是 FSIS-GD-2020-0013（2020-11，适用 SIS/NELS/NTIS/Traditional）；另有 **FSIS-GD-2020-0012《HACCP Model for New Poultry Inspection System (NPIS) Poultry Slaughter》（2020-10）**，本包未收。NPIS 线速 140/55 bpm 见 `poultry-381`，但两者适用的检验系统不同。
- **两份鲶鱼模型别混**：本卡是 FSIS-GD-2022-0006（**养殖** farm-raised）；姊妹篇 **FSIS-GD-2022-0007（野捕 wild-caught，同月）** 本包未收。中国输美等效目前仅涵盖生产品，见 `siluriformes-china`。
- **§381.65(f) 不是 §381.65(g)**：可见粪便不得入冷却槽是 (f)，须写入 HACCP/SSOP/前提方案；(g) 是全程防污染书面程序 + 微生物采样。禽模型 CCP 1 的法定锚点是 (f)。
- **7120.1 只支撑化学危害**：不能用准用表证明抗菌剂对病原体的控制效果（鲶鱼模型脚注 18）。另注意 **Rev.44（2017）已被 Rev.63（2026-11-10）取代**，用旧版准用表举证会直接出错（`ingredients-7120.1`）。
- **判定 RLTO=No 不是「免义务」**：前提方案随即并入 HACCP system 并须按两要素验证、留原始记录贯穿 life of the HACCP system（`hav-task-5000.6` Step 6.G）。

## 专家注记

1. **两份模型的 CCP 数量差异（1 vs 3）不是「哪个更严格」，而是危害分析结论不同**：鲶鱼模型把所有生物危害判 NRLTO=No，故只剩物理危害由 CCP 管；禽模型把 Salmonella/Campylobacter 判 Yes，就必须有 CCP 去控制。写计划时先固化 RLTO 判定与依据，再谈 CCP 数量。
2. **「10 + 10」抽样是模型示例频率，不是法定最低频次**；企业须在计划里写明选定频率的依据（§417.5(a)(2)），并检查员会按 `hav-task-5000.6` Step 6 追问该依据。
3. 两份模型都把「流程图片段」「退回产品」列为**未闭合分支**，转换件按版面坐标保留步骤编号与名称；引用具体步骤号时回 sources 原文核对版面，勿凭本卡表格推断箭头走向。

## 审计信息

- **一手源**：`sources/FSIS-GD-2022-0006-HACCP-Model-Raw-Intact-Farm-raised-Catfish.md`（14 页 / 464 行 / 29.9K 字符）、`sources/FSIS-GD-2020-0013-HACCP-Model-Poultry-Slaughter.md`（19 页 / 820 行 / 52.9K 字符）。2026-11-11 由用户上传 PDF 按词坐标重建，危害分析表与 HACCP plan 表按矢量网格列边界切 GFM 表格。
- **保真校验**：鲶鱼 **227/227**、禽类 **332/332** 原文长句全量命中；同口径词袋零丢失；以未做任何剔除的原始 PDF 全文实词为基准**两者均零丢失**。鲶鱼表格框线在文本层为 4.2–4.9pt 装饰字（正文最小 6.4pt），按字号精准剔除，避免长虚线 bbox 误删同行正文。
- **版本核验**：2026-11-11 查 FSIS guidance portal：FSIS-GD-2020-0013（Nov 2020）、FSIS-GD-2022-0006（Aug 2022）均在列且现行；同页另列 FSIS-GD-2020-0012（NPIS, Oct 2020）与 FSIS-GD-2022-0007（Wild-caught, Aug 2022）。
- **已知限制**：两份 PDF 的流程图页为矢量方框，文本层为散字，按坐标重建后箭头走向不可恢复；危害分析表跨页且每页重复表头，按版面 y 行展开，未按逻辑行合并；禽模型 PDF p.19 表头含源文档自带的 `Error! Bookmark not defined.`（Word 域错误），按原文保留。
- **法条回源**：§417.2/417.3/417.4/417.5 查 `sources/9-CFR-Part-417-2026eCFR.md`；§381.65(f)(g)、§381.66、§381.69 查 `sources/9-CFR-Part-381-Poultry-2026eCFR.md`。
- **蒸馏时间**：2026-11-11 ｜ **关联卡**：haccp-plan-guidebook、haccp-417、haccp-validation-2015、poultry-381、siluriformes-china、hav-task-5000.6
