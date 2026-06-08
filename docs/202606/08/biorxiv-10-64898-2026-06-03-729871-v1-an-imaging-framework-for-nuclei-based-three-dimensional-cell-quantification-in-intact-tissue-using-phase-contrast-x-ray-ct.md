---
title: An imaging framework for nuclei-based three-dimensional cell quantification in intact tissue using phase-contrast X-ray CT
title_zh: 基于相位对比X射线CT的完整组织细胞核三维定量成像框架
authors: "Partridge, T., Ahmad, R., Astolfo, A., Buchanan, I., Endrizzi, M., Hawkins, M., Olivo, A., Esposito, M."
date: 2026-06-08
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.03.729871v1.full.pdf"
tags: ["query:mdr"]
score: 6.0
evidence: 利用X射线CT进行3D细胞定量以测量物理尺寸
tldr: "传统光学与组化方法难以实现完整组织的三维细胞定量，X射线CT虽有潜力但缺乏软组织对比。本研究结合传播相位衬度X射线CT与体积核分割，在未染色人类肝脏组织中实现三维细胞核分割与定量。提取了等效直径、轴比、最近邻距离等形态与空间指标，与H&E组织学结果一致。该方法支持无标记、无损的三维细胞定量分析，并保留组织微环境背景。"
source: biorxiv
selection_source: fresh_fetch
motivation: 现有光学与组化方法二维、有损或受光散射限制，无法实现完整组织三维细胞定量。
method: 结合传播相位衬度X射线CT与体积核分割，对未染色组织进行三维细胞核分割。
result: 在人类肝脏组织中成功提取核形态与空间分布指标，与组织学结果高度一致。
conclusion: 该框架支持无标记无损三维细胞定量，保留组织微结构背景。
---

## 摘要
在完整三维生物样本中进行细胞定量仍然是一个重大挑战，因为标准光学和组织学技术本质上是二维的、有破坏性的或受光散射限制。光学透明化可以扩展成像深度，但耗时、破坏组织完整性，且常与下游分析不兼容，限制了其在常规三维定量中的实际应用。X射线计算机断层扫描可以克服这些限制，但传统显微CT缺乏细胞尺度分析所需的软组织对比度。本文介绍了一种集成成像框架，将基于传播的相位对比X射线CT与体积核分割相结合，实现了未染色体积组织中的三维细胞定量。我们对离体人肝组织进行了成像，并在整个重建体积中分割细胞核，提取了定量核指标和空间组织指标，包括等效直径、短长轴比和最近邻距离。我们评估了两个非重叠感兴趣区域之间测量的一致性，并针对苏木精和伊红组织学对切片分辨核指标进行了基准测试。所得高对比度体积数据集保留了组织背景，允许定量测量与周围结构及微结构一起解释。总之，这些结果表明，实验室相位对比X射线CT支持完整未染色组织中的基于细胞核的体积细胞定量，并提供了保持背景的三维定量分析框架。

## Abstract
Quantifying cells within intact three-dimensional biological specimens remains a major challenge, as standard optical and histological techniques are inherently two-dimensional, destructive, or constrained by light scattering. Optical clearing can extend imaging depth but is time-consuming, disruptive to tissue integrity, and often incompatible with downstream analyses, limiting its practical use for routine three-dimensional quantification. X-ray computed tomography can overcome these limitations, yet conventional micro-CT lacks the soft-tissue contrast required for cellular-scale analysis. Here, we introduce an integrated imaging framework in which propagation-based phase-contrast X-ray CT is combined with volumetric nuclear segmentation to enable three-dimensional cell quantification in unstained volumetric tissue. We imaged ex vivo human liver tissue and segmented nuclei throughout the reconstructed volume, extracting quantitative nuclear metrics and spatial organisation metrics, including equivalent diameter, minor-to-major axis ratio and nearest-neighbour distance. We assessed measurement consistency across two non-overlapping volumes of interest and benchmark slice-resolved nuclear metrics against haematoxylin and eosin histology. The resulting high-contrast volumetric datasets preserve tissue context, allowing quantitative measurements to be interpreted alongside surrounding architecture and microstructure. Together, these results show that laboratory phase-contrast X-ray CT supports nuclei-based volumetric cell quantification in intact unstained tissue and provides a framework for context-preserving quantitative analysis in three dimensions.