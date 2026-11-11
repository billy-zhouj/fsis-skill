---
name: fsis
description: 来自 USDA FSIS 法规与指令（9 CFR 416/417/531–537 + FSIS Directive 5000.1 Rev.8 / 5000.4 Rev.3 / 5000.5 Rev.3）的肉禽与鲇形目食品安全方法论路由入口。当用户的问题涉及 SSOP 卫生体系、FSIS HACCP、驻厂检查（IPP）验证任务、不符合项与执法阶梯、开工前卫生检查选点、鲇形目（catfish/巴沙鱼/叉尾鮰）管辖判定、中国输美鲶鱼等效体系、FDA 与 USDA 双管辖厂体系搭建，但不明确指向某一个具体子任务时，用本入口按意图路由到对应能力卡。触发词：SSOP / 416 / 417 / FSIS / USDA / IPP / 驻厂检查 / U.S. Rejected 封签 / HACCP（FSIS 语境）/ 鲇形目 / 鲶鱼输美 / catfish / Siluriformes / 等效性 equivalence / 一厂两制 / 双管辖 / Rules of Practice / pre-op 卫生检查 / 低频卫生 LTD less than daily / 标签审批 labeling / 通用批准 generic label / 标签送审 / 配料准入 / 海关总署 230 号公告 / 输美备案推荐注册 / 屠宰检验剖检 post-mortem / 线速 line speed / U.S. Retained / SRM 疯牛病 / E. coli 检测 / 禽类 poultry / NPIS 线速 / 9 CFR 381 / 禽类营养标签 381.400 / ratites 走禽 / 含禽配料豁免 / 蛋制品 egg products / 蛋液蛋粉输美 / restricted eggs。
metadata:
  cangjie.bundle-id: usda-fsis-regulatory
  cangjie.source: 9 CFR 416/417/531-537 (eCFR 2026-10-29) + FSIS Directive 5000.1 Rev.8 (2025-01-10) + 5000.4 Rev.3 (2021-10-14) + FR 2019-24055 + FSIS China FY23 audit + 9 CFR 557 & 21 CFR 117/123（源缺口补齐 2026-11-03） + 9 CFR 381（eCFR 2026-11-09，2026-11-11 补齐禽类缺口）
  restored-from: 本会话转换与核实（2026-11-02 用户上传 PDF 蒸馏建包）
---

# USDA FSIS 卫生·HACCP·验证体系：来源路由入口（compact pack）

## 触发与不触发

适用：肉禽/蛋品/鲇形目官方企业的卫生与 HACCP 合规、FSIS 验证与执法机制、鲇形目管辖与中国输美等效、FDA/USDA 双管辖架构。
不适用：

- FDA 管辖水产品的 21 CFR 123 方法论细节（条文原文已收录 sources/21-CFR-Part-123-…；HACCP 控制策略深入用 seafood-haccp 技能）
- FDA 21 CFR 117 HARPC/预防性控制方法论细节（条文原文已收录 sources/21-CFR-Part-117-2025.md；深入用 harpc 技能）
- 屠宰加工工艺工程参数与设备选型（9 CFR 381 禽类、310 畜类条文原文均已收录；本包提供合规方法论，不是工艺工程手册）
- 对特定企业出具具有法律效力的合规结论

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 416 是双轨结构：416.1–416.6 处方式底线（静态状态达标）+ 416.11–416.17 体系义务（书面 SSOP+每日监控+每日记录 6 个月+纠偏三要素）。没有书面 SSOP = 当场吊扣检验标志。
2. 417 HACCP 的法律牙齿：未制定实施计划 = 产品可判掺假；CCP 偏离产品默认留置评估；记录发货前复核且由非执行人签署。
3. FSIS 验证是"日报制"：驻厂 IPP pre-op SSOP 每周 2 次+operational 每班次 1 次，拿企业记录对现场观察；分散 NR 喂进趋势引擎，同类反复 → systemic problem → 执法升级。
4. U.S. Rejected 封签只有 FSIS 能摘——不卫生条件下的生产本身就构成掺杂（FMIA 601(m)(4)，与 FDA 的 FFDCA 402(a)(4) 措辞逐字平行），FSIS 驻厂 IPP 可当场贴签**事前阻断**；FDA 无驻厂、只能事后追责——两边差异在执法机制，不在认定门槛。
5. 鲇形目（整目，含巴沙鱼/塘鲺）2008 年被划入 USDA；同一间厂鲶鱼线走 9 CFR、罗非鱼线走 FDA 123+117——中国输美厂的形式是"一个监工（属地海关）、两套标准"。
6. 等效机制 = 美国规则 + 本国裁判 + FSIS 审计裁判：FSIS 不派员驻华，靠周期审计（六大等效组件）+ 口岸复检维持认定。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 编写/审查 SSOP；416 体系五件套义务；记录保存期限；纠偏怎么写；低于每日频率的卫生程序；水源/化学品/虫害等底线条款 | references/capabilities/ssop-416.md | 条文细节查 sources/9-CFR-Part-416-2026eCFR.md |
| 设计/审查 FSIS HACCP 计划；危害分析清单；CCP 偏离处置；确认 validation；发货前记录复核；培训职能；417 vs FDA 三兄弟差异 | references/capabilities/haccp-417.md | 条文细节查 sources/9-CFR-Part-417-2026eCFR.md |
| FSIS 检查员日常验证怎么做；迎审准备；NR 记录与系统性问题；执法阶梯（贴签→拒标志→停业→NOIE）；E. coli 测试 | references/capabilities/fsis-verification-5000.1.md | 原文查 sources/FSIS-Directive-5000.1-Rev8-2025.md |
| 开工前检查选点逻辑；高风险设备六特征；organoleptically clean；LOTO；MOI 时间约定 | references/capabilities/preop-ssop-5000.4.md | 原文查 sources/FSIS-Directive-5000.4-Rev3-2021.md（2026-11-02 已换干净版） |
| 加工企业能不能隔几天大扫除；LTD 低频卫生；屠宰禁 LTD；LTD 验证逻辑与等效举证；APC/基线/SPC 证明卫生有效 | references/capabilities/ltd-sanitation-5000.5.md | 原文查 sources/FSIS-Directive-5000.5-Rev3-2021.md |
| 标签要不要送审；通用批准条件；八项强制特征；特殊声明边界；Product of USA；出口外文标签（317.7）；配料准用/禁用 | references/capabilities/labeling-412-424-317.md | 原文查 sources/9-CFR-Part-412/424/317；禽类标签实体条款在 381 Subpart M/N/Y（已收录），见 poultry-381 |
| 屠宰后检验：线速、剖检、U.S. Retained/Condemned、SRM 疯牛病风险物质、食用血液、E. coli 过程控制、沙门氏菌性能标准 | references/capabilities/postmortem-310.md | 原文查 sources/9-CFR-Part-310-PostMortem-2026eCFR.md；禽类剖检/线速/冷却见 poultry-381 |
| 禽类检验：NPIS 等六种剖检系统、140·55 bpm 线速、381.66 冷却与冷冻、禽类官方标记、标签与营养标签、记录期、进口等效、含禽配料豁免 | references/capabilities/poultry-381.md | 原文查 sources/9-CFR-Part-381-Poultry-2026eCFR.md（211 条/25 分部）；畜类对照看 postmortem-310 |
| 蛋制品检验：蛋制品厂连续检验、≤45°F 储运、记录 2 年、restricted eggs、巴氏杀菌 RTE 与安全处理标签、蛋品沙门氏菌检测、蛋品进口等效 | references/capabilities/egg-products-590.md | 原文查 sources/9-CFR-Part-590-Egg-Products-2026eCFR.md；资格国清单动态，引用前查 FSIS import library |
| 某种鱼归 FDA 还是 USDA；鲇形目管辖范围；中国输美鲶鱼资格/产品范围/体系要求；等效机制怎么运作；2021 ineligible 案例 | references/capabilities/siluriformes-china.md | 资格与认证清单动态变化，用前回 FSIS 官网核对 |
| 某项 SPS 底线怎么达标（厂房/照明/通风/管道/水/更衣/设备/人员）；回用水分级与监测指标；冰回用；屠宰线回用氯浓度；厂界责任；FIFRA/EPA 药剂框架；1999 Food Code 对应条 | references/capabilities/sps-guide.md | 条文+合规建议全文查 sources/FSIS-SPS-Compliance-Guide-2016.md |
| FDA 117 与 USDA 416/417 总体对比；双管辖厂（一厂两制）体系怎么搭；中国厂变体 | references/dual-jurisdiction.md | 涉及 117 细节时补 harpc 技能 |
| 本包文档概览、术语（IPP/PHIS/NR/MOI/SPS…） | references/overview.md | |

条款号直达速查（用户消息出现 § 416.xxx / § 417.xxx / § 533.2 / "5000.1 说了什么"时按本表路由）：

| 条款/指令 | 覆盖内容 | 去向 |
|---|---|---|
| § 412 / 317 / 424（标签与配料） | 标签审批、强制特征、出口外文、配料准入 | labeling-412-424-317 |
| § 310（屠宰后检验） | 剖检、线速、SRM、E. coli/沙门氏菌性能标准 | postmortem-310 |
| § 381（禽类产品检验） | 六种剖检系统、NPIS 线速、381.66 冷却、381.94 ratites E. coli、Subpart M/N/Y 标签与营养标签、381.196 进口等效 | poultry-381 |
| § 590（蛋制品） | 连续检验、冷链、记录、进口等效 | egg-products-590 |
| § 557（鲇形目进口） | 外国体系等效判定（557.2 引用 327.2 指定子款+养殖运输条件）、合格国清单、每批外国证书（557.4） | siluriformes-china；原文查 sources/9-CFR-Part-557-Importation-2026eCFR.md |
| § 123（FDA 水产 HACCP） | FDA 管辖水产品的 HACCP（双管辖厂 FDA 侧） | dual-jurisdiction；原文查 sources/21-CFR-Part-123-FishAndFisheryProducts-2026eCFR.md |
| 21 CFR 117（FDA cGMP/HARPC） | 与 416/417 对比的 FDA 侧条文 | dual-jurisdiction；原文查 sources/21-CFR-Part-117-2025.md |
| § 416.1–416.6（SPS 底线） | 厂区虫害、建筑、照明、通风、给排水、水源回用、更衣盥洗、设备、卫生操作、人员卫生、封签 | 条文义务查 ssop-416；逐条合规建议与回用水细则查 sps-guide（含 1999 Food Code 映射） |
| § 416.11–416.17（SSOP 体系） | 制定/实施/维护/纠偏/记录/官方验证全义务 | ssop-416 |
| § 417.1–417.8（HACCP 全部） | 定义、危害分析与计划、纠偏、验证、记录、不合格情形、培训、官方验证 | haccp-417 |
| § 531.1 鲇形目定义、532.2 资格申请、533 分隔与检查员设施、534 收获前、537 适用清单 | 鲇形目法规族 | siluriformes-china |
| Directive 5000.1 Rev.8 | 六章验证体系全图 | fsis-verification-5000.1 |
| Directive 5000.4 Rev.3 | pre-op 选点法 | preop-ssop-5000.4 |
| Directive 5000.5 Rev.3 | LTD 低频卫生验证 | ltd-sanitation-5000.5 |
| 9 CFR 412 / 317 / 424 | 标签审批与配料准入 | labeling-412-424-317 |
| 9 CFR 310 | 屠宰后检验与微生物性能标准 | postmortem-310 |
| 9 CFR 381 | 禽类产品检验全套（PPIA，211 条/25 分部） | poultry-381 |
| 9 CFR 590 | 蛋与蛋制品检验（EPIA） | egg-products-590 |

非能力类查询：

- 文档概览与术语 → references/overview.md
- 完整意图与关键词索引 → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 1 张能力卡；跨域任务（如双管辖厂）最多加 2 张。
- 概览类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 都无法命中的意图，明确告知超出本包范围，不要硬套。

## 边界与判停

- 用户要条文原文时：优先引用能力卡内置要点，需要长上下文查 sources/ 对应文件，不要凭记忆背条款。
- 指令（5000.1/5000.4）是给 FSIS 员工的作业指令，不直接给企业设义务——企业义务在 416/417 条文本身；引用时注意这个层次。
- 等效资格、认证企业清单、产品范围动态变化——涉及"现在还能不能出口"类判断，提醒回 FSIS 官网核对最新状态。
- 涉及具体企业放行决策时，提醒最终判定须由 417.7 培训合格人员/PCQI 作出，本技能是辅助方法论不是授权签字人。

---

# 写作核对模式（写稿/查稿用）

**纪律：稿件里每一个条号、每一段引用原文、每一个数字，都必须回到一手来源核对，不得凭记忆写。**

## 流程

1. 查对应能力卡的「法规原文引用层」——大部分核对点直接命中；
2. 不足则拉原文（eCFR 接口必须 `-L` 跟随重定向，且需 `--compressed`；versioner API 的日期不能超过该卷最新 issue date）：

```bash
curl -sL --compressed "https://www.ecfr.gov/api/versioner/v1/full/2026-10-29/title-9.xml?part=416" | python3 -c "import re,sys;text=re.sub(r'<[^>]+>','\n',sys.stdin.read());print(re.sub(r'\n\s*\n+','\n',text))"
```

3. 输出三栏核对报告：稿件表述｜原文（附条号）｜结论（✅一致 / ⚠️偏差+最小修改建议）。

## 高频陷阱（已踩过/已核实）

- **"catfish"是目级定义**（order Siluriformes）——写"只有叉尾鮰归 USDA"是错的；巴沙鱼、塘鲺都中招。
- **中国输美鲶鱼仅生产品**——写"熟制鲶鱼可输美"错（FY23 审计资格表确认：raw intact / raw non-intact 两类）。
- **等效 ≠ FSIS 派驻**——中国厂由属地海关承担官方检验，FSIS 只做周期审计+口岸复检；"FSIS 检查员驻厂"只在美国国内成立。
- **SSOP 记录保存 6 个月/现场 48 小时**（416.16）——与 117 的 2 年记录期数字不同，勿混。
- **"没有书面 SSOP 吊扣检验标志"**出自 5000.1 Chapter II Part III B（指令），不是 416 条文——引用时挂对来源。
- **鲶鱼等效的列名落点是 9 CFR 557.2**（Part 557 IMPORTATION，鲇形目专属章），不是 327.2——557.2(a) 引用 327.2 指定子款并加评养殖与运输条件；写"鲶鱼等效依据 327.2"不精确。
- **533.2 是 [Reserved] 保留条款**——物理分隔条款是 **§533.1 Separation of establishments**（官方企业须与非官方企业 separate and distinct）；写"533.2 分隔"是错的（531–537 源第 206 行明示 §533.2 [Reserved]）。
- **537.2 属于 Part 537（鲇形目专属），不在 417**——417 只是通用 HACCP 框架；537.2 要求危害分析覆盖收获前/中/后（含养殖端水质/药残/运鱼车），是 537 对 417 的加严。
- **蛋制品进口等效认定在 §590.910（非 590.500）**——590.910(a) 要求外国体系等同美国（镜像 §§590.500–590.580 的卫生/加工/设施/政府检验要求），590.910(b) 列合格国清单、590.910(d) 仅清单内国可进口；旧卡误归于 590.500。
- **"不卫生条件 = 掺杂"两边是平行的**：FFDCA 402(a)(4) ≈ FMIA 601(m)(4)，均为 "may have become"（可能性即可，无需证明实际污染）——写"FDA 要证明产品已掺假才能执法"是错的；FDA/USDA 的差异在**驻厂事前阻断 vs 事后追责**的执法机制，不在认定门槛。
- **eCFR versioner API 日期坑**：请求日期超过该卷最新 issue date 会报错，先查 titles 接口拿有效日期。
- **GPO PDF 有前置页混入**：Part 416/417 的 GPO PDF 卷首含上一部分的尾部内容，引用条文时先定位 PART 标题行。
- **禽类没有 310.25 式沙门氏菌性能标准**：9 CFR 381 正文 Salmonella 仅 2 处、Campylobacter 0 处；§381.94 的强制 E. coli 检测只针对 **ratites（走禽）屠宰企业**。Directive 5000.1 Chapter IV 把 §310.25/§381.94 并列，不等于禽类有沙门氏菌性能标准；禽类病原体性能标准走 FSIS 抽样计划与 Federal Register 公告。
- **NPIS 线速 140 bpm（幼鸡）/55 bpm（火鸡）出自 §381.69**，只适用 NPIS；传统检验看 §381.67 表、NTI 看 §381.68，且 IIC 一律可指令降速。§381.177 记录期措辞是 "not to exceed 2 years"，与 416.16 的 6 个月、590.200 的 2 年并列勿混。
