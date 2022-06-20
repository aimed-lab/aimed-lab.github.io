---
layout: default
title: PGC
parent: Tools
nav_order: 6
---
# Polar Gini Curve (PGC)

[GitHub](https://github.com/aimed-uab/Polar-Gini-Curve){:target="_blank"}{: .btn .btn-purple } 
[Web Tool](https://nguyenminhthanh060.wixsite.com/polarginicurve){:target="_blank"}{: .btn .btn-blue }
[Docs](https://nguyenminhthanh060.wixsite.com/polarginicurve/tutorial){:target="_blank"}{: .btn .btn-green }
[Ask Questions!](https://uabdatascience.slack.com/archives/C03LPL3697T){: .btn }

## About

In this work, we design the Polar Gini Curve (PGC) technique, which combines the gene expression and the 2D embedded visual information to detect biomarkers from single-cell data. Theoretically, a Polar Gini Curve characterizes the shape and ‘evenness’ of cell-point distribution of cell-point set. To quantify whether a gene could be a marker in a cell cluster, we can combine two Polar Gini Curves: one drawn upon the cell-points expressing the gene, and the other drawn upon all cell-points in the cluster. We hypothesize that the closers these two curves are, the more likely the gene would be cluster markers. We demonstrate the framework in several simulation case-studies. Applying our framework in analyzing neonatal mouse heart single-cell data, the detected biomarkers may characterize novel subtypes of cardiac muscle cells.

![Alt text](/assets/images/pgc-img.webp?raw=true "PGC")

## How to cite us

Nguyen, T.M., Jeevan, J.J., Xu, N. and Chen, J.Y.,, **Polar Gini Curve: a technique to discover gene expression spatial patterns from single-cell RNA-seq data,** _Genomics, Proteomics & Bioinformatics_, 4, 19(3), pp.493-503., <span class="fs-3">[doi](https://doi.org/10.1101/2020.03.04.977140){:target="_blank"}</span>
