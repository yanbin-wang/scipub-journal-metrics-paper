# SciPub 期刊指标论文指导文档

本文档用于指导学生将 SciPub（SCI 期刊审稿速度与相关指标）数据集成为一篇可投稿的科学计量学论文。

## 1. 论文定位

- **类型**：Data Resource + Descriptive Scientometric Analysis
- **核心贡献**：构建一个多来源、可追溯的 SCI 期刊审稿时效数据库，并基于此开展描述性与关联性分析。
- **差异化**：三级来源（官方发布 > 论文证据 > 社区经验）的系统整合与对比。
- **目标期刊**：*Scientometrics* 、*Journal of Informetrics* 、*Quantitative Science Studies* 、*Learned Publishing* 等。

## 2. 背景与动机

- 审稿速度是研究者选刊时的重要考虑因素（引用 Springer Nature 等调查）。
- 现有资源存在明显不足：
  - SciRev 众包数据样本有限、偏差难控（Huisman & Smits, 2017）
  - PubMed 日期推算覆盖窄、仅限已发表论文
  - 官方数据分散、定义不一致
  - 缺乏系统的多来源对比与可追溯机制
- 本工作填补上述缺口，为研究者提供更可靠的选刊参考。

## 3. 相关工作（请学生引用以下文献）

| 研究 | 数据来源 | 核心内容 | 完整引用 |
|------|----------|----------|----------|
| Huisman & Smits (2017) | SciRev 众包（约 3500 条） | 审稿时长、学科差异、desk reject 时间、作者满意度 | Huisman, J., & Smits, J. (2017). Duration and quality of the peer review process: the author’s perspective. *Scientometrics*, 113(1), 633–650. https://doi.org/10.1007/s11192-017-2310-5 |
| Manusights Journal Outcomes Dataset | PubMed 日期推算 + 官方报告 | 投稿到录用中位数、部分官方 first decision | Manusights. (2026). *Journal outcomes dataset, 2026 edition* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23001076 （另见 https://manusights.com/resources/journal-intelligence） |
| Hurley et al. (2025) | 手工收集顶刊 | 会计顶刊 STA 时间趋势及影响因素 | Hurley, P. J., Gal-Or, R., Knechel, W. R., & Pesch, H. L. (2025). Submit-to-accept times in accounting: Determinants and comparisons to other business disciplines. *The Accounting Review*, 100(2), 219–247. https://doi.org/10.2308/TAR-2022-0574 |
| 其他单学科研究 | 各异 | 局部审稿效率 | 见各学科内分散论文 |

**备注**：Manusights 主要以数据集形式发布，并未在正规期刊发表对应论文。引用时请使用上述 DOI 或官网链接。

## 4. 建议章节结构

1. **Introduction**：背景、缺口、贡献
2. **Related Work**：相关科学计量学与审稿时效研究
3. **Data and Methods**：期刊范围、指标定义、三级来源采集与优先级、质量控制、覆盖情况
4. **Results**：多维度分析（见下节）
5. **Discussion**：发现意义、局限性、更新计划
6. **Data Availability**：数据集说明（可部分公开或延迟公开）

## 5. Results 分析维度（优先级）

1. **数据覆盖与基本特征**
   - 各指标有效数据比例、分布（中位数、IQR）
   - 按学科、出版社、JCR 分区分层

2. **多来源一致性与偏差**（核心亮点）
   - 官方 vs 论文推算 vs 社区的成对比较
   - 偏差方向与幅度
   - 相关性与一致性指标

3. **学科与出版社差异**
   - 分层描述与统计检验
   - 学科相对位置（百分位）

4. **与其他指标的关联**
   - 与影响因子、录用率、OA 费用的相关/回归
   - 分区与速度的关系

5. **时间节点关系**
   - 首次决定 vs 投稿至录用的差距
   - 不同节点速度的模式

6. **稳健性与敏感性**
   - 异常值影响
   - 不同来源优先级规则下的结论稳定性

7. **实用价值**（可选）
   - 哪个指标对真实等待时间的预测力更强

## 6. 需要量化的内容

- 覆盖期刊数量与各指标有效数据比例
- 各来源样本量与中位数差异
- 学科间差异的统计检验结果
- 来源一致性指标（相关系数、偏差分布）
- 速度与 IF / 录用率的相关强度

## 7. 数据策略建议

- 论文可公开聚合统计与方法。
- 完整明细数据可选择不公开、部分公开或采用 CC BY-NC 等限制商业使用。
- 网页作为持续更新与交互工具，数据本身不是唯一护城河。

## 8. 学生执行建议

1. 整理现有数据覆盖情况，量化各指标有效比例。
2. 完成多来源一致性分析。
3. 完成学科与出版社分层描述。
4. 补充与 IF、录用率等的关联分析。
5. 撰写 Methods 与 Results 初稿。
6. 根据审稿意见迭代。

## 9. 注意事项

- 明确数据局限（社区偏差、日期推算误差、官方定义不统一）。
- 避免过度解释速度数字的因果关系。
- 保持可追溯性（来源标签、样本量、核验日期）。
