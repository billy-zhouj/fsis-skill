# 已批准抗菌干预系统：FSIS Directive 7120.1 OLR / OFLR 表（**禽类专用**）

> **源文档**（体例：每条关键事实标注【源文件 + 页/条】）
> - `sources/7120.1-OLR-OFLR-Tables-Rev63-2026-Antimicrobial-Systems.md`（**★ 现行官方 PDF 原件全文，29 页，`Update November 2026`**，2026-11-12 用户补传；此前因 FSIS CDN 403 未收，本包最后一处 7120.1 清单缺口就此闭合）
> - `sources/FSIS-Directive-7120.1-Rev63-2026-Official-PDF.md`（现行 Rev.63 主指令官方原件，§I PURPOSE B 指向本清单）
> - `sources/FSIS-Directive-7120.1-Rev63-2026-Current-Portal-Text.md`（门户转录，含本 PDF 下载链接）
> - `sources/7120.1-Table-2-Rev63-2026-Safe-Suitable-Ingredients.md`（同版本完整准用配料 Table 2）
> - `sources/FSIS-Directive-7120.1-Rev44-2017-Safe-Suitable-Ingredients.md`（**历史版** Rev.44，Table 3 OLR / Table 4 OFLR，仅供沿革对撞）
> - `sources/9-CFR-Part-381-Poultry-2026eCFR.md`（§381.91 污染与再加工）、`sources/9-CFR-Part-416-2026eCFR.md`（§416.2(g) 回用水）、`sources/9-CFR-Part-424-Labeling-Ingredients-2026eCFR.md`（§424.21(c)）
> - 辅助印证：`sources/FSIS-Compliance-Guideline-HACCP-Systems-Validation-2015.md`、`sources/FSIS-Directive-5000.6-Rev2-2018.md`
>
> **适用意图**：OLR / OFLR 是什么 · 某个抗菌干预系统有没有被 FSIS 批准 · FCN 编号与关键操作参数（浓度/pH/接触时间/温度/施加方式）· 20 ppm 游离氯还要不要遵守 · 7120.1 清单能不能当 HACCP 科学支撑 · **输美鲶鱼厂能不能用这张表** · Rev.44 旧数值还能不能引用。

---

## 零、一句话结论（先看这一行）

> ⛔ **这张表只管禽类（Poultry），不管鲇形目（鲶鱼、巴沙鱼）。** 两张表的标题都写 `for Poultry`；29 页全文 `Siluriformes` / `catfish` / `fish` 出现次数**均为 0**；条目里的工序全是禽屠宰（raw poultry carcasses/parts、IOBW 内外洗胴机、pre-chill、chiller、羽毛）。**国内输美鲶鱼加工厂不得据本表选择、申报或举证抗菌干预系统**【OLR/OFLR 源 p.1 与 p.17 表标题；全文关键词核验；Rev.44 源 V.B/C 的 9 CFR 381.91(b) 依据】。
>
> 鲶鱼厂的正确路径见第八节：准用看 `7120.1 Table 2` + `9 CFR 424.21(c)`，标签看 `9 CFR 541.7`，功效支撑另备，与本表无关。

## 一、OLR / OFLR 是什么

| | OLR（On-Line Reprocessing，在线再加工） | OFLR（Off-Line Reprocessing，离线再加工） |
|---|---|---|
| 含义 | 在屠宰线上作为**常规工序**对胴体施加的抗菌干预 | 把胴体**移出生产线**（典型为发现可见污染后）单独处理，再返回或处置 |
| 本表规模 | p.1–17，约 **77 个表行** | p.17–29，约 **53 个表行** |
| 依据 | 79 FR 49566《Modernization of Poultry Slaughter》允许企业使用已批准的 OLR/OFLR 系统，**前提是把相应程序纳入 HACCP 计划、Sanitation SOP 或其他前提方案**，法条为 **9 CFR 381.91(b)(1)、(2)**【Rev.44 源 V.B；9 CFR 381 源 §381.91】 | 同左；该规则同时**取消了「OFLR 必须用 20 ppm 游离有效氯去除可见污染」的强制要求**【Rev.44 源 V.C】 |
| 审批 | **新系统或改动系统须经 FSIS 事先批准**才能投产；申请流程见《Guidance Procedures for Notification and Protocol Submission of New Technology》【Rev.44 源 V.C】 | 同左 |

> 注意：本表是**「已批准系统 + 该系统的关键操作参数（COP）」清单**，不是法规，也不是功效证明（第七节）。Rev.63 主指令明示其附属文件 `do not supersede regulations`，含 9 CFR 319 / 381 Subpart P 标准 of identity，IPP 须核实企业使用符合**全部**法规要求【Rev.63 官方 PDF 源 §I PURPOSE B】。

## 二、版本与文件结构（别再按 126 页单册找）

```
FSIS Directive 7120.1 Rev.63（现行，2026-11-10 发布，取消 Rev.62）
 ├─ 7120.1.pdf                     主指令：PURPOSE A/B、CANCELLATION、Table 1 更新摘要、QUESTIONS   ✅ 官方原件 + 门户转录
 ├─ 7120.1_table_2.pdf             完整 Safe and Suitable Ingredients（71 页、七列）              ✅ 已归档
 └─ 7120.1-olr-oflr-tables.pdf     ★ 本卡主体：OLR + OFLR 两张表（29 页、五列）                  ✅ 已归档（2026-11-12 用户补传）
```

- 本 PDF **页眉统一写 `Update November 2026`**，但**文件里没有 "7120.1"、没有 "Rev. 63"、没有具体日期**。其「Rev.63 附属清单」身份来自主指令 §I PURPOSE B 与门户链接表，属**外部链接推断**，不是文件自称【Rev.63 门户源第 40 行；OLR/OFLR 源 29 页页眉】。对外举证时须与主指令 PDF 的修订号 `7120.1 Rev. 63 11/10/26` 一并出示。
- Rev.44（2017-12-27）把 Table 3 OLR（p.107 起）/ Table 4 OFLR 塞在 126 页单册里；**Rev.63 已拆为独立 PDF，旧版页号一律作废**【Rev.44 源 p.107、p.126；Rev.63 门户源 §3】。
- 该指令修订极频繁（Rev.62 → Rev.63 间隔不到 3 个月），引用「现行版」前须回 `https://www.fsis.usda.gov/policy/fsis-directives/7120.1` 核对修订号与附件更新日期。

## 三、表怎么读（两表同为五列）

| 列 | 内容 | 读法要点 |
|---|---|---|
| 1 Approved OLR/OFLR System | 已批准系统的商品名 | 同一商品名会因**不同 FCN 变体**重复列行，参数可能差一个数量级（第九节第 5 条） |
| 2 Company Name / Distributor | 厂商/经销商 | 常见更名，如 `Amplon, formerly AFTEC 3000`、`PeroxyChem LLC, formerly FMC` |
| 3 Substance (antimicrobial) and FCN | 抗菌物质 + FDA 食品接触物质通报号 | **FCN 是系统的法定身份**，选系统必须核 FCN 是否与自己采购的配方一致 |
| 4 PPM Concentration (range), pH, Contact Time, Temperature | 浓度上限、pH、接触时间、压力、温度、流量 | **这一列就是 COP**，逐字抄进 HACCP/SSOP/前提方案；`sufficient for purpose` 类表述不等于无限制 |
| 5 Method of Application | 施加方式 | Spray / Spray cabinet / IOBW（有无刷）/ Wash / Dip / Dip tank / Drag through dip tank / Rinse / Drench |

> **提取局限**：本件用版面识别提取，**五列结构完整保留**（优于 Table 2 的压平长行），但 ① 单元格内换行已折为空格；② **跨页续行**以 `|  |  | ...` 空首列行开头，须与上一页末行合读（Cecure、Inspexx、Chem San RBR 等连续跨 2–3 页）；③ 原文存在断字/拼写变体 `Sy stems`、`p H`、`Oxyp Hresh`、`HCI`、`HEPD`、`etic acid`，检索时用变体再查一遍；④ **p.28 有 1 张图片未提取**。引用具体 ppm / FCN / 接触时间前必须核原页【OLR/OFLR 源 extraction_caveat】。

## 四、参数全景（按抗菌剂族整理，均为**禽类**系统）

| 体系 | 代表商品 / FCN | 关键参数（原文单位） | 出处 |
|---|---|---|---|
| **PAA 复配（占绝大多数）** | AFCO 4360 FC-100 / 4363 Perasafe 23（FCN 1389）、Inspexx 系列（FCN 1096/1495/1745/2046）、Perasan MP-2 / MP-2C 系列（FCN 887 / 1806 / 1132）、PeroxyMAX 与 T24（FCN 2352）、HydriShield PA 系列（FCN 2274）、Promoat XL（FCN 2266）、Biosan 2205 MPS（FCN 2036）、Harcros PAA（FCN 1960）、DiverContact（FCN 1936）等 | **PAA 上限多为 2000 ppm**（低浓度型 18–220、40–220、80–150、80–400 ppm；Peraclean 22 为 1150 ppm）；**HP 44.4–1474 ppm**；**HEDP 0.5–136 ppm**；**DPA 0.5–6.7 ppm**；**pH 1–12.5**；**接触时间 0.5–120 秒**；**喷淋压力 0.5–170 psi**；施加方式覆盖 Spray / IOBW / Wash / Dip / Rinse | 全表 p.1–29；例：OLR p.1（AFCO 4360）、p.9（Inspexx 2046）、p.13（PeroxyMAX）、p.14（FCN 1960）、p.17（T24） |
| **酸化亚氯酸钠 ASC** | Ascend（Zee）、Bio-Cide（FCN 739）、Chloro San、Sanova | 500–1200 ppm + GRAS 酸调 **pH 2.3–2.9**（21 CFR 173.325）；Bio-Cide 为 pH 2.2–3 再以 pH 提升剂调到 5–7.5，**终液 NaClO₂ ≤1200 mg/kg、ClO₂ ≤30 mg/kg** | OLR p.2、p.3、p.6、p.15 |
| **氯 / 次氯酸** | Accutab Chlorination、Circlean IOBW、Hypochlorous acid（JBT / Tyson / TOMCO）、Sodium Hypochlorite | **20–50 ppm**（TOMCO 条 ≤50 ppm、接触 ≥10 秒、pH 5–10、5–170 psi）；Accutab pH 6–7、刷柜喷淋 **5–10 gal/min**；Circlean 接触 2–4 秒、柠檬酸终浓度 1.995 ppb | OLR p.1、p.6、p.8、p.9、p.15 |
| **有机酸 / 低 pH** | Acid FX 32、Citrilow / Citrilow Plus、Fresh FX L-12 / LP、Syntrx3200、Assist | **pH 1–2.2**；接触 2–5 秒（Citrilow ≥2 秒、Assist ≥2 秒）；Fresh FX **pH ≤2.2**；Acid FX 32 压力 5–40 psi、温度 **34–75°F** | OLR p.1、p.6、p.16；OFLR p.20 |
| **硫酸 / 硫酸钠（pH 1.8 体系）** | Amplon、Apex Clear、CMS Clear | 目标 **pH 1.8 ± 0.4**（CMS Clear 1.4–2.2）；系统压力 ≥10 psi；流量 **5–10 gal/min** | OLR p.2、p.6 |
| **DBDMH 溴** | Avibrom（Albemarle） | **60–450 ppm 有效溴**；0.1 gal 溴液 ≤15 秒；25 psi / 10 gal/min；第二喷淋柜用回用液，须满足 **9 CFR 416.2(g)**；OFLR 要求胴体内外**完全覆盖 60–90 秒**，挂 FCNs 334 / 453 / 1190 | OLR p.3；OFLR p.18 |
| **十六烷基氯化吡啶 CPC** | Cecure（Safe Foods） | 细雾喷于冷却前生禽胴体，**≤0.3 g CPC / lb 生鲜禽胴体**（≈0.66 g/kg）；溶液 CPC **≤0.8% 重量比**；浸渍 ≤10 秒或淋洗 2–5 秒、**≤5 gal/只**（≈19 L）；系统须**回收 ≥99%** 溶液；后续不进冷却器时须饮用水冲洗（可含 ≤50 ppm 游离氯）；丙二醇须合 21 CFR 184.1666（1.5 倍 CPC），消泡剂依 21 CFR 173.340 + 9 CFR 424.21(c) | OLR p.4–5；OFLR p.19–20 |
| **磷酸三钠 TSP** | Trisodium phosphate | 预冷前喷淋 **8–12% 溶液、≤15 秒**，按 GMP（21 CFR 182.1778） | OLR p.17 |
| **臭氧 / 偏硅酸钠** | Ozone（BOC Gas）、AVGard XP（Danisco） | 臭氧 3.5–4 ppm @ 3% 浓度；AVGard XP 第一柜 20 ppm 氯、第二柜 **SMS 4% ± 2%** | OLR p.12、p.2 |
| **氯上限的历史沿革** | OFLR Calcium hypochlorite、electrolytically generated hypochlorous acid | 表列 **20 ppm 游离有效氯**，但均附 `NOTE: Agency guidance has allowed the use of up to 50 ppm` —— 与 79 FR 49566 取消强制 20 ppm 一致；**不要死读 20 ppm 为唯一上限** | OFLR p.18、p.22；Rev.44 源 V.C |

> **表内 33 个不同 FCN 编号，范围 739–2352**；Rev.44（2017）全文最高仅 1810。FCN 1936 / 1960 / 2036 / 2046 / 2266 / 2274 / 2352 等均为 2017 年后新增批准，说明本表是动态更新的现行清单【OLR/OFLR 源全文 FCN 检索；Rev.44 源全文检索】。

## 五、度量衡换算（法定原文以 °F / lb / gal / psi 为准）

| 原文 | 中国习惯单位 | 换算说明 |
|---|---|---|
| 34–75°F（Acid FX 32，OLR p.1） | **约 1.1–23.9 °C** | (34−32)×5/9 ≈ 1.1；(75−32)×5/9 ≈ 23.9 |
| 32–99°F（Pearl OX / All-O-San，OLR p.13、OFLR p.26） | **约 0–37.2 °C** | 99°F ≈ 37.2 °C；这是**喷淋液温度窗口**，不是冷藏/冷却要求 |
| 0.3 g CPC / lb（Cecure） | **约 0.66 g/kg** | 1 lb ≈ 0.4536 kg |
| 5 gal / carcass（Cecure） | **约 19 L/只** | 1 US gal ≈ 3.785 L |
| 0.1 gal（Avibrom） | **约 0.38 L** | 同上 |
| 5–10 gal/min（Accutab / Amplon / CMS Clear） | **约 19–38 L/min** | 同上 |
| 5–170 psi（多条目） | **约 0.03–1.17 MPa** | 1 psi ≈ 6.895 kPa |
| 8–12%、4% ± 2%、0.8% by weight | 质量分数，无需换算 | 溶液配制浓度 |

ppm 为国际通用浓度单位，表内保留原样；`ppb`（1.995 ppb 柠檬酸）同理。对外文件、迎检记录中引用数值时**务必同时保留法定原文单位**，换算值只作内部理解用。

## 六、与 Rev.44 对撞：旧版数值不可沿用

| 项 | Rev.44（2017-12-27，126 页单册） | 现行（Update November 2026，29 页独立 PDF） |
|---|---|---|
| 结构 | Table 3 OLR 自 p.107 起、Table 4 OFLR 至 p.126 | 两张表在同一独立 PDF，p.1–17 / p.17–29；**旧页号作废** |
| FCN 编号上限 | 1810 | **2352**（新增 1936 / 1960 / 2036 / 2046 / 2266 / 2274 / 2352 等） |
| **AVIBROM 有效溴** | Table 3/4 均为 **60–100 ppm**【Rev.44 源第 1452 行】 | OLR p.3 与 OFLR p.18 均为 **60–450 ppm**，挂 FCNs 334 / 453 / 1190 —— **这是最直接的数值变更实证** |
| 新增/更名系统 | 无 PeroxyMAX / T24、HydriShield PA 系列、Promoat XL（FCN 2266）、Harcros PAA（FCN 1960）、Biosan 2205 MPS（FCN 2036）等 | 均已列入 |
| 20 ppm 氯 NOTE | Table 4 已写 `Note: Agency guidance has allowed the use of up to 50 ppm` | 沿用到 OFLR p.18、p.22，未变 |

> 结论：Rev.44 只能用于沿革解释，**不得据以设定现行 COP、写 HACCP 关键限值或做迎检举证**。

## 七、和 HACCP 验证的关系（高频考点）

1. **清单给 COP，不给功效数据。** `FSIS-GD-2015-0011`（HACCP Systems Validation）p.5 / p.27 明确：NOL 与 7120.1 **不含 efficacy data，也不含全部 COP**；单靠 NOL 或 7120.1 作科学支撑属「支撑不足」，须另补在指定 COP 下有效的挑战研究、同行评议文献或厂内 90 天数据。本表虽然列出 COP，仍不替代功效支撑。
2. **生物危害 ≠ 化学危害。** `FSIS-GD-2022-0006` 鲶鱼模型脚注 18/23、`FSIS-GD-2020-0013` 禽模型均指出 7120.1 **只支撑化学危害（安全性/适用性）**，不能证明对病原体的控制效果——控制细菌所需浓度与「安全且适用」浓度不是一回事。
3. **HAV 会查。** Directive 5000.6 Rev.2 把「只有 NOL / 7120.1 申请、缺少指定 COP 下有效性的补充支撑」列为 HAV 任务选样触发情形之一。
4. **纳入体系是法定前提。** 依 9 CFR 381.91(b)(1)(2)，OLR/OFLR 程序必须写进 HACCP 计划、Sanitation SOP 或其他前提方案；9 CFR 417.4 初始验证 90 calendar days 照常适用。

→ 交叉见 `haccp-validation-2015`、`hav-task-5000.6`、`haccp-417`、`haccp-generic-models`、`ingredients-7120.1`。

## 八、输美鲶鱼厂怎么用这张表（本卡最重要的实务段）

**答：不能用；但必须知道它存在、且明确不适用于自己。**

| 常见场景 | 正确处理 |
|---|---|
| 工厂想在鲶鱼片清洗/浸渍环节用 PAA 或次氯酸，问「7120.1 批准了没有」 | **不能引 OLR/OFLR 表**。准用性查 `sources/7120.1-Table-2-Rev63-2026-Safe-Suitable-Ingredients.md`（含 `Electrolytically generated hypochlorous acid` 用于 Siluriformes 清洗/冷却水，游离氯 ≤50 ppm、pH 4–7.5 等专属条目）+ 9 CFR 424.21(c) + 21 CFR 相应条款 |
| 想拿某商品名（如 Inspexx、Perasan）的 2000 ppm PAA 参数直接抄进鲶鱼 HACCP 计划 | ❌ 该参数是**禽胴体喷淋**的 COP，与鱼片浸渍的产品、设备、微生物谱都不同；且清单不提供功效数据，须另备科学支撑与厂内验证 |
| FSIS 或客户问「你们的抗菌干预系统是否在 FSIS 批准清单内」 | 说明本表为 **for Poultry** 的禽类清单，鲶鱼产品不在其适用范围；出示自己所用物质的 7120.1 Table 2 条目、FCN/GRN/NOL 原件、配方用量计算与厂内验证记录 |
| 一厂两制（同厂兼有禽线与鲶鱼线） | 禽线可依本表选系统并纳入禽线 HACCP/SSOP；**鲶鱼线不得共用禽线参数、记录或 COP**，两套体系的危害分析与验证记录须分开 |
| 迎检举证引用页号 | 用本件 `<!-- Page N -->` 页标记；**不得引用 Rev.44 的 Table 3/4 页号** |

> 中国侧另有硬要求：海关总署作业指导书附1-4 的标签验证、附1-8 装运前 CCP 回顾性核查等，见 `gacc-inspection-workbook`；美国侧鲇形目标签专章见 `labeling-412-424-317`（9 CFR 541.7）。

## 九、易错点

1. **把禽类清单用到鲶鱼** —— 本轮最大风险，见第八节。
2. **拿 Rev.44 的 Table 3/4 数值当现行** —— AVIBROM 60–100 → 60–450 ppm 只是其中一例。
3. **把清单当抗菌功效证据** —— 见第七节。
4. **死读 20 ppm 游离氯** —— OFLR 两条附 NOTE 允许最高 50 ppm；79 FR 49566 已取消强制 20 ppm。
5. **忽略同名不同 FCN 的变体** —— 例：OFLR p.27 `Perasan MP-2C` 同时有 **FCN 1806（PAA 80–2000 ppm）** 与 **FCN 1132（PAA 80–400 ppm）** 两行，而 `Perasan MP-2`（FCN 887）为 80–150 ppm —— 同一商品族上限相差一个数量级；`Inspexx 150` 挂 FCN 1096 / 1495 / 1745 / 2046 四行且上限各异。**必须按采购产品的实际 FCN 对行**。
6. **跨页续行误读为新条目** —— 以空首列 `|  |  |` 开头的行是上一页条目的后半段。
7. **变体拼写检索漏** —— `Sy stems`/`p H`/`Oxyp Hresh`/`HCI`/`HEPD` 等，检索时用多种写法。
8. **把页眉 `Update November 2026` 当成修订号或正式发布日期** —— 文件本身不写 7120.1 / Rev.63 / 日期，版本身份靠主指令链接推断。
9. **把 32–99°F（0–37.2 °C）当成产品冷藏/冷却要求** —— 那是 Pearl OX / All-O-San 喷淋液的温度窗口；禽类冷却合规另见 `chilling-requirements-2014`（9 CFR 381.66(b)）。
10. **把 ppm 与 mg/kg 无条件等同** —— 水溶液稀溶液可近似，但对外计算须按产品密度与配方核算。
11. **以为「在清单内」就自动合规** —— 仍须满足标准 of identity、424.21(c)、全部法规要求，且 IPP 会逐项核验。
12. **把 FCN 当作 GRN / NOL** —— 三者是不同证据类型；分类见 `ingredients-7120.1` §6。

## 十、使用路径（给企业的自检顺序）

1. **先确认物种与工序**：只有禽类（poultry）屠宰/胴体加工才继续；鲇形目直接转第八节路径。
2. 回 `https://www.fsis.usda.gov/policy/fsis-directives/7120.1` 核对当日主指令修订号与附件更新日期，并保存页面截图。
3. 在 `sources/7120.1-OLR-OFLR-Tables-Rev63-2026-Antimicrobial-Systems.md` 按商品名 / 厂商 / FCN 检索；用变体拼写补检一遍。
4. **核原页**：确认 FCN 与自己采购的配方一致、确认跨页续行已合并、抄全第 4 列全部 COP（浓度、pH、接触时间、压力、温度、流量）与第 5 列施加方式。
5. 把 COP 写入 HACCP 计划 / SSOP / 前提方案（9 CFR 381.91(b)(1)(2)），另备**功效与指定 COP 下有效性**的科学支撑 + 厂内 90 天验证数据。
6. 证据链归档：现行表页截图（带页眉日期）、主指令修订号页、FCN 原件、浓度检测记录（如 Inspexx 2046 条要求「Use a PAA test kit or in-line monitor to verify the PAA concentration」）、设备参数校准、HACCP/SSOP 修订记录、验证报告。

## 十一、审计信息

- **归档与核验（2026-11-12）**：用户补传 `G:/下载/7120.1-olr-oflr-tables.pdf`（29 页 / 1,018,998 字节），此前 FSIS CDN（Akamai）返回 403 无法抓取；用内置 PDF CLI `md-plain` 版面识别提取（30 个表格 / 3,222 段落），五列结构完整保留；另以 `txt` 纯文本层对撞关键词与首尾页。
- **核验结论**：① 两表标题与全文确认**仅限禽类**，`Siluriformes` / `catfish` / `fish` 均为 0 次；② 统计约 77 / 53 个表行、33 个 FCN 编号（739–2352）；③ 与 Rev.44 Table 3/4 对撞，查明 AVIBROM 60–100 → 60–450 ppm、FCN 上限 1810 → 2352、新增系统清单；④ 确认 OFLR 20 ppm 氯的 50 ppm NOTE 与 79 FR 49566 沿革一致；⑤ 提取页标记、跨页续行与拼写变体局限已写入源 frontmatter。
- **未核实项**：本件不含鲇形目或红肉产品的 OLR/OFLR 清单，FSIS 是否另有非禽类清单须回官网核对；p.28 一张图片未提取（不影响表格文字）；文件自身版本标识缺失，靠链接推断。
- **源文档**：本卡头部所列 1 份官方清单原件 + 3 份 7120.1 同版本/历史版源 + 3 份法规源 + 2 份验证/HAV 辅助源。
- **蒸馏时间**：2026-11-12。
