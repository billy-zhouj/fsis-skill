# 配料准用：FSIS Directive 7120.1《Safe and Suitable Ingredients》

> **源文档**（体例：每条关键事实标注【源文件 + 条款/页/行号】）
> - `sources/7120.1-Table-2-Rev63-2026-Safe-Suitable-Ingredients.md`（**★ 现行版 Rev.63 完整 Table 2**，71 页官方 PDF 全文，2026-11-12 用户补传；查现行准用限量以本件为准）
> - `sources/FSIS-Directive-7120.1-Rev63-2026-Official-PDF.md`（**现行版 Rev.63 主指令官方 PDF 原件**，3 页，2026-11-12 用户补传）
> - `sources/7120.1-OLR-OFLR-Tables-Rev63-2026-Antimicrobial-Systems.md`（**现行 OLR/OFLR 已批准抗菌干预系统表**，29 页官方 PDF 全文，`Update November 2026`，2026-11-12 用户补传；**仅限禽类 Poultry，不适用于鲇形目**，详见 `olr-oflr-antimicrobial-systems`）
> - `sources/FSIS-Directive-7120.1-Rev63-2026-Current-Portal-Text.md`（同版本指令门户网页转录，Table 1 已表格化，便于检索）
> - `sources/FSIS-Directive-7120.1-Rev44-2017-Safe-Suitable-Ingredients.md`（**历史版 Rev.44 / 2017-12-27**，用户上传 126 页 PDF 全文，仅供沿革对照）
> - `sources/9-CFR-Part-424-Labeling-Ingredients-2026eCFR.md`（§424.21 法规正面清单）
> - 辅助印证：`sources/FSIS-Compliance-Guideline-HACCP-Systems-Validation-2015.md`（GD-2015-0011）、`sources/FSIS-GD-2022-0006-HACCP-Model-Raw-Intact-Farm-raised-Catfish.md`、`sources/FSIS-GD-2020-0013-HACCP-Model-Poultry-Slaughter.md`、`sources/FSIS-GD-2020-0008-Guidebook-HACCP-Plans.md`
>
> **适用意图**：某配料/加工助剂/抗菌剂能否用于输美鲶鱼或肉禽产品 · 限量多少 · 标签怎么写 · 7120.1 能不能当 HACCP 科学支撑 · 无异议函/FCN/GRN 是什么。**OLR/OFLR 已批准系统清单已单独归档，另走 `olr-oflr-antimicrobial-systems`**——该表只管禽类，鲶鱼厂不可套用。

---

## 一、版本警钟（任何回答前先过这一关）

**用户上传的是 Rev.44（2017-12-27），FSIS 现行版是 Rev.63（2026-11-10）——相差 19 个修订次、近 9 年，且 2026-11-10 才刚发布。**

| | 历史版（用户上传） | 现行版（官网核验） |
|---|---|---|
| 修订号 | Rev. 44 | **Rev. 63** |
| 发布日 | 2017-12-27 | **2026-11-10** |
| 取消 | Rev. 43（2017-10-05） | Rev. 62（2026-08-20） |
| 结构 | 126 页单册，Table 1/2/3/4 全在内 | 主指令只留更新摘要；完整 Table 2 与 OLR/OFLR 表**各自独立 PDF** |
| 标签要求列编码 | 数字 (1)–(6) | **大写字母 A–F**（定义不变） |

【Rev.63 官方 PDF §II CANCELLATION、§I PURPOSE A/B；Rev.63 门户源 §1(3) 为门户附加说明、非 PDF 正文；Rev.44 源 frontmatter 与 p.1】

**因此：**
- ✅ 可以用 Rev.44 查"某物质历史上是否列过、法条编号怎么表述、沿革如何"；
- ❌ **不得**用 Rev.44 判定现行准用、引用现行限量、或作为迎检举证依据；
- ⚠️ 引用"现行版"前须回 `https://www.fsis.usda.gov/policy/fsis-directives/7120.1` 核对修订号是否又更新——这份指令修订极频繁（Rev.62 → Rev.63 间隔不到 3 个月）。

**缺口状态（2026-11-12 收盘更新）**：**7120.1 现行版四件源已全部到齐，本包再无 7120.1 清单缺口**。完整 Table 2（71 页）与 OLR/OFLR 抗菌干预系统表（29 页）均由用户补传归档，前者可查「某物质现行准不准用、限量多少、标签怎么写」，后者可查「某禽类抗菌干预系统是否已批准、FCN 与 COP 是什么」。原「Rev.44 鲇形目条目是否沿用」待核项已逐条核实（见第五节）。此前 FSIS CDN（Akamai）返回 403 的抓取障碍已由用户补传原件解决。

> ⛔ **新归档的 OLR/OFLR 表只适用于禽类（for Poultry）**，29 页全文 `Siluriformes` / `catfish` / `fish` 均 0 次；**输美鲶鱼厂不得据以选系统或举证**。其适用范围、参数、与 Rev.44 差异、HACCP 关系见 `olr-oflr-antimicrobial-systems`。

> ⚠️ **版本日期陷阱**：Table 2 文件头写 `rev. 63 (November 2026)`，但 **71 页页脚全部仍是 `... June, 2023`**（模板未随修订号更新）。以文件头为准，勿把页脚 2023 当作版本日期。

## 二、这份文件是什么、不是什么

| 判断 | 结论 | 依据 |
|---|---|---|
| 是法规吗 | **不是**。是给 IPP（检验人员）用的**准用物质清单/作业指令** | Rev.63 §1 PURPOSE(1) "provides inspection program personnel (IPP) with the latest updates to the list of substances" |
| 能取代法规吗 | **不能**。现行版明示 "This Directive and its associated documents **do not supersede regulations**, including standards of identity (9 CFR 319 and 9 CFR 381 subpart P)" | Rev.63 §1 PURPOSE(2) |
| 谁承担合规责任 | IPP 须核实企业使用所列物质"compliant with **all regulatory requirements**"；企业不能因为"在 7120.1 表内"就自动合规 | 同上 |
| 与 424.21(c) 的关系 | **并行清单**：424.21(c) 是写入 CFR 的正面清单（法定）；7120.1 是动态维护、含 FCN / GRN / 可接受性判定函的作业清单。二者都要对 | Rev.63 §1 PURPOSE(2)；9-CFR-Part-424 源 §424.21(c) |
| 法定底线 | §424.21(a)(1)(b)(2)：配料须先见于 21 CFR 第 I 章 A/B 分章或本章条例，否则禁用；FDA 的 GRAS ≠ FSIS 自动准用 | `labeling-412-424-317`；9-CFR-Part-424 源 |

**一句话**：7120.1 回答"FSIS 认不认这个用法"，424.21/21 CFR 回答"法律准不准"，标签法（541/317/412）回答"标不标、怎么标"。三条链缺一不可。

## 三、现行版文件结构（别再按 126 页单册找）

```
FSIS Directive 7120.1 Rev.63（现行版，2026-11-10）
 ├─ 7120.1.pdf                     主指令：PURPOSE(A/B) / CANCELLATION / Table 1 更新摘要 / QUESTIONS
 │                                  ✅ 官方 PDF 原件 + 门户转录，两份均已归档
 ├─ 7120.1_table_2.pdf             ★ 完整 Safe and Suitable Ingredients（71 页，**七列**大表）
 │                                  ✅ 已归档（2026-11-12 用户补传）
 ├─ 7120.1-olr-oflr-tables.pdf     ★ 已批准 OLR / OFLR 抗菌干预系统表  ✅ 已归档（2026-11-12 用户补传，29 页，仅禽类）
 └─ 9 CFR 424.21(c)               并行法定正面清单（已收）
```

【Rev.63 源 §1 PURPOSE B（官方 PDF；门户转录作第 2 条）及链接表】

Rev.44 的 Table 3（OLR）/ Table 4（OFLR）在 p.107 起；**Rev.63 已拆出单册，页号不可沿用**【Rev.44 源 p.107、p.126；Rev.63 源校勘注记】。OLR/OFLR 依 79 FR 49566（禽类屠宰现代化最终规则）纳入企业 HACCP 计划、SSOP 或其他前提方案（9 CFR 381.91(b)(1)(2)）；该规则同时取消了"OFLR 必须用 20 ppm 游离有效氯"的旧要求【Rev.44 源 V.B/C】。现行 29 页表**仅限禽类**（for Poultry），与鲇形目无关；参数、FCN 变体、Rev.44 数值差异与 HACCP 关系全表见 `olr-oflr-antimicrobial-systems`。

## 四、Table 2 怎么读（Rev.63 **七列** / Rev.44 六列）

> **结构变化**：Rev.63 在原有六列前**新增首列 CATEGORY**（如 Acidifiers/Alkalizers、Antimicrobials、Binders、Flavoring Agents、Miscellaneous、Moisture Retention、Packaging Systems），便于按用途类别定位。Rev.44 无此列。

| 列 | 内容 | 读法要点 |
|---|---|---|
| **CATEGORY**（Rev.63 新增） | 用途类别 | 鲇形目条目集中在 Binders / Flavoring Agents / Moisture Retention / Acidifiers/Alkalizers / Antimicrobials |
| SUBSTANCE | 物质/专有混合物名 | 混合物即使组分都是 GRAS，整体也可能属**专有配方**（proprietary）【Rev.44 源 V.D】 |
| INTENDED USE OF PRODUCT | 适用产品与用途 | 会写明 "fish of the order Siluriformes" 等专属适用对象 |
| AMOUNT | 限量 / sufficient for purpose using GMP | "sufficient for purpose" 不是无限制，仍受 GMP |
| REFERENCE | 法律依据 | 见第六节四类 |
| LABELING REQUIREMENTS | 标签后果 | Rev.44 用 (1)–(6)，**Rev.63 改 A–F**；定义见下 |

**A–F 定义（Rev.63；与 Rev.44 数字 1–6 **按序一一对应，已核实**）**【Rev.63 Table 2 每页页眉；Rev.44 源 V 段原文 `1) processing aid, 2) GRAS, 3) Secondary Direct Food Additive, 4) Direct Food Additive, 5) Color Additive, 6) FCS`】：
A 加工助剂（符合 FDA 标签定义）/ B GRAS / C 次级直接食品添加剂 / D 直接食品添加剂 / E 着色剂 / F 食品接触物质（FCN，制造、包装、运输、盛放食品用材料成分，且对食品不产生技术作用）。

## 五、鲇形目专属准用条目（**现行版 Rev.63 已逐条核实**）

**核实结论（2026-11-12）**：现行 `7120.1-Table-2-Rev63` 中 "Siluriformes" 出现 **31 次、分布 30 个文本行**；Rev.44 的**十组磷酸盐保水混合物全部沿用**，AMOUNT 一律 `Sufficient for purpose`，21 CFR 依据与标签要求（按主次降序 + 子清单 + 磷酸盐可统称 "sodium phosphate"）**均未变**。以下清单因此可以**作为现行依据使用**（引用限量前仍建议核原页，因 PDF 文本层表格列交错）。物质名保留英文原名以便检索。

> **Rev.63 新增/本次新识别的鲇形目相关条目**：Bacteriophage preparation（E. coli STEC-targeted，GRN 834，1×10⁸ PFU/g，适用于 intact red meat / poultry / **Siluriformes**）；Electrolytically generated hypochlorous acid（含 Siluriformes 清洗/冷却水，游离氯 ≤50 ppm、pH 4–7.5）；Rice bran extract（GRN 884，≤1.2 percent，作为磷酸盐替代品，**仅限标准 of identity 允许的肉禽制品**）；Algal oil、Hydrolyzed chicken and turkey protein。
>
> ⛔ **排除项**：Transglutaminase enzyme preparation（GRN 1021，≤65 ppm）明确写 `excluding Siluriformes fish products` —— **鲇形目制品禁用**，别把"肉禽可用"直接推到鲶鱼上。
>
> 表内**不出现 "catfish" 字样**；物种常用名（basa/swai/tra/sutchi）与 "catfish" 仅限鮰科的规则在 **9 CFR 541.7(d)**，不属本表范围。

### 5.1 保水磷酸盐混合物 —— 鲶鱼片最常用（Moisture Retention 段，p.96–100）

**统一用法**：注射，或作为喷淋、浸渍浴、拖过浸槽、滚揉施加，用于**保持鲇形目鱼类及其制品水分**。
**统一限量**：混合物按 GMP "sufficient for purpose"，逐项挂 21 CFR 条款。
**统一标签后果**（每一条都重复写明）：**按主次降序列出，并附混合物各成分的子清单；磷酸盐可统称 "sodium phosphate"，但仍须在子清单的正确主次位置**。

| # | 混合物组成 | 21 CFR 依据 |
|---|---|---|
| 1 | 三聚磷酸钠 + 六偏磷酸钠 + 食盐（可选） | 182.1810、182.6760 |
| 2 | 三聚磷酸钠 + 食盐 + 六偏磷酸钠 + 柠檬酸 + 抗坏血酸 | 182.1810、182.6760、182.1033、182.3013 |
| 3 | 三聚磷酸钠 + 食盐 + 六偏磷酸钠 + 酸性焦磷酸钠 + 柠檬酸 | 182.1810、182.6760、182.1087、182.1033 |
| 4 | 三聚磷酸钠 + 食盐 + 柠檬酸（五钠三磷酸盐 / 四钠二磷酸盐） | 182.1810、182.1033 |
| 5 | 五钠三磷酸盐 + 四钠二磷酸盐 | 182.1810、182.6789 |
| 6 | 三聚磷酸钠 + 柠檬酸钾 + 柠檬酸 + 四钠二磷酸盐 + 氯化钠 | 182.1810、182.6789、182.1033 |
| 7 | 食盐 + 柠檬酸 + 柠檬酸钾 + 五钠三磷酸盐 + 四钠二磷酸盐 | 182.1810、182.6789、182.1033 |
| 8 | 柠檬酸 + 三聚磷酸钠 + 磷酸氢二钾 | 182.1033、182.1810 |
| 9 | 三聚磷酸钠 + 食盐 + 柠檬酸钾 | 182.1810、184.1625 |
| 10 | 三聚磷酸钠 + 食盐（可选） | 182.1810 |

【Rev.44 源 p.96–100，第 1282–1314 行；**Rev.63 Table 2 p.63–66 逐条核实全部沿用**（L1645/1647/1649/1658/1660/1662/1671/1673/1675/1677/1694）】

> ⚠️ Rev.63 PDF 文本层把这几行的**物质名、REFERENCE、标签要求三列文字切成交错片段**（例如 p.63 第三行的物质名与 182.1087 出现错位）。上表组分以 Rev.44 清晰文本层为准、法条号两版一致；对外举证前请核对现行 PDF 原页 p.63–65。

### 5.2 单体与其他鲇形目专属条目

| 类别 | 物质 | 用途 / 依据 | 标签 |
|---|---|---|---|
| 粘合/稳定 | 瓜尔胶 Guar Gum | (1) 蛋制品打发助剂 ≤0.5%；(2) 鲇形目 GMP 足量；Acceptability determination | 通用名列出 (4) |
| 粘合/稳定 | 黄原胶 Xanthan gum（乙醇回收纯化） | 非标准化肉禽制品、鲇形目；GRN 000121；按 21 CFR 172.5 及 9 CFR 424.21(c) | 通用名列出 (4) |
| 磷酸盐类 | 磷酸钙 Monocalcium phosphate（一/二/三代） | 鲇形目 GMP 足量；21 CFR 182.1217 | 通用名列出 (4) |
| 磷酸盐类 | 磷酸铝钠 Sodium aluminum phosphate | 鲇形目；21 CFR 182.1781 | 通用名列出 (4) |
| 磷酸盐类 | 磷酸钠 Sodium phosphate（一/二/三代） | 鲇形目；21 CFR 182.1778 | 通用名列出 (4) |
| 磷酸盐类 | 三聚磷酸钠 Sodium tripolyphosphate（单体） | 鲇形目 GMP 足量；21 CFR 182.1810 | 通用名列出 (4) |
| pH/配方助剂 | 碳酸钠 / 碳酸氢钠 Sodium carbonate / sodium bicarbonate | 鲇形目；21 CFR 184.1742 / 184.1736 | 通用名列出 (4) |
| pH/配方助剂 | 碳酸氢钾 Potassium bicarbonate | 鲇形目配方助剂；21 CFR 184.1613 | 通用名列出 (4) |
| pH/配方助剂 | 碳酸钾 Potassium carbonate | 鲇形目风味剂；21 CFR 184.1619 | 通用名列出 (4) |
| pH 控制 | 氢氧化镁 / 碳酸钾 / 碳酸氢钾 | 加工用水 pH 控制，含鲇形目加工水；21 CFR 184.1428 / 184.1619 / 184.1613 | 依受理条件无须标 (1) |
| 风味剂 | 苹果酸 Malic acid | 鲇形目风味剂 GMP；21 CFR 582.1069 | 通用名列出 (4) |
| 风味剂 | 谷氨酸钠 Monosodium glutamate（MSG） | 鲇形目及肉禽；9 CFR 424.21、21 CFR 182.1 | 通用名列出 (4) |
| 螯合/酸度 | 柠檬酸钙 Calcium citrate | 鲇形目 GMP；21 CFR 582.1195 | 通用名列出 (4) |
| 螯合/酸度 | 柠檬酸钠 Sodium citrate | 鲇形目 GMP；21 CFR 184.1751 | 通用名列出 (4) |

【Rev.44 源第 151、884、912、949、979、981、983、1002、1088、1092、1103、1303、1305、1312 行】

> ✅ **现行版 CATEGORY 归属（Rev.63 Table 2）**：Binders = Guar gum / Monocalcium phosphate / Sodium aluminum phosphate / Sodium carbonate or sodium bicarbonate / Sodium phosphate / Potassium bicarbonate / Xanthan gum；Flavoring Agents = Malic acid / Potassium carbonate；Moisture Retention = Calcium citrate / Sodium citrate / Sodium tripolyphosphate；Acidifiers/Alkalizers = Potassium carbonate or potassium bicarbonate。上表标签列 **(4)** 在现行版为 **(D)**（数字 4 = 字母 D，直接食品添加剂）。
>
> ⚠️ 上表物质名与限量已由 Rev.63 完整 Table 2 核实仍在表内；但**列归属与具体限量**仍建议核现行 PDF 原页（文本层表格压平）。配方定型前按第九节顺序走一遍。

### 5.3 三条链在"加溶液鲶鱼片"上交汇（本卡最实用的一段）

做**注水/加磷酸盐溶液/包冰衣**的输美鲶鱼片时，会同时触发三条互不相干的要求，缺一条就出问题：

1. **准用**：所用磷酸盐混合物必须在现行 7120.1 Table 2 内，且 AMOUNT 与 INTENDED USE 对得上（本卡 §5.1）；同时不违反 §424.21。
2. **标签**：中国海关作业指导书附1-4 要求"生制产品添加其他成分的，须有描述性文字并按主→次降序**列全部成分常用名**"，例 "Contains 10% added solution of water, salt, phosphates…"；7120.1 的标签列又要求**子清单 + 磷酸盐可统称 sodium phosphate**；美国侧 §541.7(e) 另管 441/442 保水与**冷冻鱼须标解冻后 100% 净重**、脱冰衣净重按 NIST Handbook 133 第 2 章 2.6 节抽样。
3. **净重**：加溶液/包冰衣直接影响标示净重是否被判短重，与 §541.7(e) 联动。

→ 详见 `gacc-inspection-workbook`（附1-4 四、标签验证）与 `labeling-412-424-317`（541.7(e)）。**不要把"在 7120.1 表内"当成标签合规的证明。**

## 六、REFERENCE 列四类来源（判断证据强度）

| 类型 | 含义 | 常见于 |
|---|---|---|
| **Acceptability determination** | FSIS 就某物质/用途出具的**可接受性判定**（常以"无异议函 NOL"形式流转） | 专有混合物、新用途 |
| **21 CFR §§** | FDA 层面的食品添加剂/GRAS 法定条款（182/184/172/173/582 等） | 单体、常规配料 |
| **GRAS Notice No. (GRN)** | FDA GRAS 通报编号 | 新 GRAS 物质 |
| **FCN** | 食品接触物质通报（Food Contact Notification） | 包装、抗菌干预系统 |

Rev.63 本次 Table 1 五条更新的 Reference 即由 GRN（435 / 468 / 065）与 Acceptability determination + 21 CFR 组合构成【Rev.63 源 §3.1】。

**注意**：Table 2 里有些混合物即使组分都获批，**整体配方仍可能属专有信息**，企业不能以"组分都合法"自行推定配方准用【Rev.44 源 V.D】。

## 七、与 HACCP 验证的关系：**只支撑化学危害**（高频考点）

这是包内已被四处引用、现在终于有一手源支撑的边界：

> **7120.1 可作化学危害（安全性 / 适用性）的支撑文档，但不能用它证明对生物危害（病原体）的控制效果**——控制细菌所需的抗菌剂浓度与"安全且适用"的浓度不是一回事。

- `FSIS-GD-2022-0006` 鲶鱼 HACCP 模型脚注 18、23 明确此边界，且提示 `FCN# [insert number]` 是模型占位符，企业须填自己所用化合物的 FCN 编号。
- `FSIS-GD-2020-0013` 禽模型：7120.1 "cannot be used as support for the control of biological hazards"。
- `FSIS-GD-2015-0011`（HACCP Systems Validation）p.5 / p.27：**NOL 与 7120.1 不含功效数据（efficacy data），也不含全部关键操作参数（COP）**，单独拿 NOL 或 7120.1 当科学支撑，属于"支撑不足"；必须另补在指定 COP 下有效的科学/技术支撑（挑战研究、同行评议文献、厂内 90 天数据等）。
- `FSIS Directive 5000.6 Rev.2` 把"只有 NOL 或 7120.1 申请、缺少指定 COP 下有效性的补充支撑"列为 HAV 任务的选样触发情形之一。

→ 交叉见 `haccp-generic-models`、`hav-task-5000.6`、`haccp-417`（初始验证 90 天）。

## 八、边界与易错点

1. **拿旧版当现行** —— 本轮最大风险。Rev.44 是 2017 年的，现行 Rev.63 是 2026-11-10 的。凡对外意见、迎检举证，一律先核官网修订号。
2. **把 7120.1 当法规** —— 它是 IPP 清单，不取代 9 CFR 319 / 381 Subpart P 标准 of identity，也不取代 424.21。
3. **以为"在表内"就万事大吉** —— 仍须满足标准 of identity、限量、标签声明与全部法规要求（Rev.63 §1 PURPOSE(2) 原文）。
4. **把 7120.1 当抗菌功效证据** —— 见第七节，只支撑化学危害。
5. **标签代码混淆** —— Rev.44 数字 (1)–(6) 与 Rev.63 字母 A–F 定义相同、编码不同；引用时注明版本。
6. **页号沿用** —— Rev.63 的 Table 2/OLR/OFLR 已拆成独立 PDF，Rev.44 的 p.107 / p.126 不再适用；OLR/OFLR 现用 29 页独立 PDF 的 `<!-- Page N -->` 页标记。
7. **PDF 文本层表格错位** —— 两版源都是多列大表压成连续长行（Rev.63 更是七列交错），列边界不可靠；**不得据以引用限量或列归属**，须核原页。
8. **"sufficient for purpose" 读成无限制** —— 仍受 GMP 约束。
9. **专有混合物忽略** —— 组分合法 ≠ 配方合法。
10. **GRAS 自动适用误解** —— FDA GRAS 不等于 FSIS 自动准用，须对 424.21 与本指令。
11. **页脚日期当版本日期** —— 现行 Table 2 文件头 `rev. 63 (November 2026)`、71 页页脚却全是 `June, 2023`；以文件头为准。
12. **把肉禽可用的新条目推到鲇形目** —— Transglutaminase enzyme preparation 明确 `excluding Siluriformes fish products`；Rice bran extract 也仅限标准 of identity 允许的肉禽制品。
13. **以为准用表会写物种名** —— Table 2 不出现 "catfish"；物种常用名与 "catfish" 仅限鮰科在 9 CFR 541.7(d)，属标签法而非准用表。

## 九、使用路径（给企业的自检顺序）

1. 打开 `https://www.fsis.usda.gov/policy/fsis-directives/7120.1`，**记下当日修订号与 Issue Date**。
2. 在包内 `sources/7120.1-Table-2-Rev63-2026-Safe-Suitable-Ingredients.md` 检索物质名（必要时核现行 PDF 原页）→ 核对 CATEGORY、INTENDED USE（是否含 "fish of the order Siluriformes" 或是否写 `excluding Siluriformes`）、AMOUNT、REFERENCE、LABELING REQUIREMENTS（A–F）。
3. 同时核 9 CFR §424.21(c) 与 21 CFR 相应条款；确认不违反产品标准 of identity。
4. 按标签列与中国侧附1-4、美国侧 §541.7(d)(e) 生成标签稿；加溶液/包冰衣产品另核解冻后净重。
5. 若该物质用作抗菌干预：另备**功效与 COP 支撑**（7120.1/NOL 不够）；**禽类** OLR/OFLR 系统查 `sources/7120.1-OLR-OFLR-Tables-Rev63-2026-Antimicrobial-Systems.md` 并纳入 HACCP/SSOP/前提方案（9 CFR 381.91(b)(1)(2)），详见 `olr-oflr-antimicrobial-systems`；**鲇形目不在该表范围内**。
6. 证据链归档：现行表页截图（带修订号与日期）、FCN/GRN/NOL 原件、配方用量计算、标签批准件、厂内验证记录。

## 十、审计信息

- **质量核验（2026-11-12 初核）**：现行版修订号/日期/取消关系/结构拆分/A–F 定义/Table 1 五条更新，逐项取自 FSIS 指令门户网页正文；Rev.44 的 Siluriformes 条目从用户上传 PDF 文本层逐行定位。
- **质量核验（2026-11-12 用户补传两份官方 PDF 后复核）**：① 主指令官方 PDF（3 页）与门户转录逐句对撞，Table 1 五条的限量/接触时间/21 CFR 法条号 **24/25 项全命中**，证实转录可靠；并查明**门户 PURPOSE 第 3 条不是官方 PDF 正文**（官方 PDF 仅 A、B 两条）；② 完整 Table 2（71 页）证实鲇形目十组磷酸盐混合物**全部沿用**、限量与标签要求未变，原待核项**已消**；③ 查明 Rev.63 表结构**新增 CATEGORY 列（七列）**、数字 (1)–(6) 与字母 A–F 按序一一对应、页脚 `June, 2023` 为模板遗留；④ 识别 Transglutaminase 排除鲇形目等新边界。
- **质量核验（2026-11-12 用户补传第三份官方 PDF 后收盘）**：`7120.1-olr-oflr-tables.pdf`（29 页，`Update November 2026`）已归档为 `sources/7120.1-OLR-OFLR-Tables-Rev63-2026-Antimicrobial-Systems.md`，**7120.1 现行四件源全部到齐、本包再无 7120.1 清单缺口**；查明的重大边界是该表**仅限禽类（for Poultry）**、全文零 Siluriformes/catfish/fish，故对输美鲶鱼迎检方案**不可用**；另查得 AVIBROM 有效溴由 Rev.44 的 60–100 ppm 改为 60–450 ppm、FCN 编号上限由 1810 升至 2352，实证旧版数值不可沿用。整理版见 `olr-oflr-antimicrobial-systems`。
- **未核实项**：OLR/OFLR 表本身不写修订号与日期（版本身份靠主指令 PURPOSE B 与门户链接推断）；FSIS 是否另有非禽类 OLR/OFLR 清单须回官网核对；表内 p.28 一张图片未提取。
- **源文档**：本卡头部所列 5 份 7120.1 主源 + 424 法规源 + 4 份辅助印证源；OLR/OFLR 部分另见 `olr-oflr-antimicrobial-systems`
- **蒸馏时间**：2026-11-12
