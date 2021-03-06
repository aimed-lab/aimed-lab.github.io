---
layout: default
title: SEAS
parent: Tools
nav_order: 1
---
![Alt text](/assets/images/SEAS-logo.png?raw=true "SEAS")

[GitHub](https://github.com/aimed-uab/SEAS){:target="_blank"}{: .btn .btn-purple } 
[Web Tool](https://aimed-lab.shinyapps.io/SEAS/){:target="_blank"}{: .btn .btn-blue }
[Docs](https://aimed-uab.github.io/SEAS/){:target="_blank"}{: .btn .btn-green }
[Ask Questions!](https://uabdatascience.slack.com/archives/C03KWBTPDJT){: .btn }

![Alt text](/assets/images/SEAS.png?raw=true "SEAS workflow")

## About

Statistical Enrichment Analysis of Samples (SEAS) is a tool to find which clinical (metadata) attributes are enriched within a sample subset. For example, SEAS answer the following questions:
* I have population data with brain cancer survival time; I select an interested patient subcohort, such as who received X treatment; does this subcohort have long survival time?
SEAS can be used to infer or annotate the unknown clinical (metadata) attribute of a sample. For example:
* I same a brain cancer patient whom I do not know the survival time; can I use SEAS to infer the survival time of the patient?
To do so, I can define a subcohort, which includes the most similar patients to the unknown survival-time patient. The question is converted to the one above, which can be answered by SEAS. Also, in SEAS, I can use embedding to view similar patients.

## How to cite us

Nguyen, T. M., Bharti, S., Yue, Z., Willey, C. D., & Chen, J. Y. (2021). **Statistical Enrichment Analysis of Samples: A General-Purpose Tool to Annotate Metadata Neighborhoods of Biological Samples.** _Frontiers in big data_, 4, 725276.  <span class="fs-3">[doi](https://doi.org/10.3389/fdata.2021.725276){:target="_blank"}</span>
