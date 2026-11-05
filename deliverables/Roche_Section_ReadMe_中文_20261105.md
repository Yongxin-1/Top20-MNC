# Roche章节与收入Excel（2026-11-05）

本次基于用户提供的12份Roche材料，交付独立8页Roche section，可复制进主PPT。保留AZ/J&J的版式体系：白底、青色标题、深蓝表头、TA分组及CStone页脚。未替换其他公司的内容。

## Excel怎么用

打开 **收入_CHF_汇率_USD**：

- 第4–48行为CHF百万收入：按FY2025完整TA销售升序排列，最大TA在下面；TA内Others先列，产品按FY2025销售升序排列。
- **第52行D52:J52是黄色可编辑汇率**，定义为`1 USD = x CHF`。D至H分别对应2021–2025，I为2026H1，J为9M2026。
- 第56–100行为USD百万收入，公式为`CHF ÷ 对应期间汇率`。产品合计、核心产品贴数、TA块、CAGR及Excel图表引用这些公式。
- 公司披露平均CHF/USD：2021 0.91、2022 0.95、2023 0.90、2024 0.88、2025 0.83、2026H1 0.79、9M2026 0.80。按公司两位小数披露精度换算，与公司使用更精细内部汇率的美元指标可能有差异。
- 已在测试副本将2025汇率从0.83改成0.90，确认公司美元总额、产品收入及CAGR自动更新；交付文件保留0.83。
- 选择FY2025销售>USD1bn的初始17个产品/家族。门槛判断会重算，但固定核心cohort不会自动增删、重排；更改汇率后如需改变成员，需同步调整贴图cohort。
- **PPT是当前汇率的快照，不是Excel的外部链接**。改变汇率后需更新PPT图表数据或重新生成。

## 收入口径

- Pharma Division only，不含Diagnostics；FY2021–FY2025为全年，H1和9M单独列，不年化、不混入全年柱图。
- 收入为Roche账面销售，不是同一品牌所有合作方的全球总销售。Xolair主要为Roche美国销售；Elevidys为Roche持有的非美权益；Venclexta由AbbVie入账，未计入Roche产品收入柱图。
- 五年CHF总额已核平：45,041 / 45,551 / 44,612 / 46,171 / 47,669百万；H1 2026为23,629百万。
- MabThera/Rituxan横跨肿瘤血液与免疫：产品合计页相加，TA分层图保留两行。17个家族因此形成18个具名图层。
- 历史Oncology+Haemophilia A映射为Oncology/Hematology；Neuroscience映射为Neurology；Infectious Diseases并入Other。原始披露长表保留公司当年的原分类。
- 2023将Luxturna调整到Ophthalmology，并重列2022；2021没有对应重列数据，保持原披露，相关CAGR带星号。
- 未单列收入保持空白，不能当作零。部分新药在年报Others内，FY2025 presentation披露了单列数，已拆出并扣减Others，确保不重复计算。
- USD CAGR为4个增长区间，包含年度换算汇率变化；H1公司CER增长另列，不与reported增长混用。

## 8页内容

1. Agenda：Roche章节页。
2. Commercial portfolio：FY2021–25按产品堆叠、CAGR与MoA；FY2025/FY2026H1 TA块。
3. Late-stage portfolio：15个company-coded独立NME，按最高阶段分12个PhaseIII、3个Registration。
4. R&D priorities：Pharma Day正式披露的五TA战略与“Bar”投资标准。
5. BD按TA/年：17条有来源的selected inbound cohort。
6. BD按modality/target：同一cohort，一笔交易按一个主要modality计。
7. Selected 2026 transactions：Nurix、DualityBio、Hanmi、Simcere，未披露内容和pending close明确保留。
8. Pharma Day与H1 call总结：较近的Pharma Day在左，每次各6个未来研发议题，药物附MoA，原文段落在Excel和备注。

## 管线和BD边界

官方Q3 appendix第51页披露13个PhaseIII NMEs和3个Registration NMEs，giredestrant在两组重复，按最高阶段去重为15个。**Astegolimab在PhaseIII但被灰色标为AI**，与新分子性质的判断需要进一步核实；本次保留分类例外，不从颜色推断已上市或LCM。2026首次NME批准未形成完整监管清单，没有填一个未经核实的零。

BD是所给材料支持的17条selected cohort，非全量2021–2026交易普查。AntlerA、Simcere等在所读资料中没有完整资产/靶点信息，明确保留未披露；不会从公司logo推断资产。Hanmi在Pharma Day时仍pending close。阶段按交易时证据填写，不把当前PhaseIII倒填为收购时阶段。

所有主要信息均附上传文件名及PDF页/原文段落定位；MoA科学注释与原文区分。没有把分析师提问当管理层承诺。原始上传文件未另行发布到仓库。

## 验证

PPTX通过ZIP/XML及内部关系检查，无遗留think-cell OLE；8页均成功转PDF并逐页检查。包含3个原生可编辑图表、4个原生表格。Excel保留924个公式，重算无错误。PPTX、PDF、Excel均小于40MB。
