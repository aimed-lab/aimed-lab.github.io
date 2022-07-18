---
layout: default
title: DMAP
parent: Tools
nav_order: 8
---
![Alt text](/assets/images/DMAP-logo.png?raw=true "DMAP")

[Web Tool](http://discovery.informatics.uab.edu/dmap/){:target="_blank"}{: .btn .btn-blue }
[Docs](https://discovery.informatics.uab.edu/dmap/f?p=101:13::::::){:target="_blank"}{: .btn .btn-green }


## About

### Background
Drug repositioning is a cost-efficient and time-saving process to drug development compared to traditional techniques. A systematic method to drug repositioning is to identify candidate drug's gene expression profiles on target disease models and determine how similar these profiles are to approved drugs. Databases such as the CMAP have been developed recently to help with systematic drug repositioning.

### Methods
To overcome the limitation of connectivity maps on data coverage, we constructed a comprehensive in silico drug-protein connectivity map called DMAP, which contains directed drug-to-protein effects and effect scores. The drug-to-protein effect scores are compiled from all database entries between the drug and protein have been previously observed and provide a confidence measure on the quality of such drug-to-protein effects.

![Alt text](/assets/images/dmap.jpeg?raw=true "DMAP")

### Results
In DMAP, we have compiled the direct effects between 24,121 PubChem Compound ID (CID), which were mapped from 289,571 chemical entities recognized from public literature, and 5,196 reviewed Uniprot proteins. DMAP compiles a total of 438,004 chemical-to-protein effect relationships. Compared to CMAP, DMAP shows an increase of 221 folds in the number of chemicals and 1.92 fold in the number of ATC codes. Furthermore, by overlapping DMAP chemicals with the approved drugs with known indications from the TTD database and literature, we obtained 982 drugs and 622 diseases; meanwhile, we only obtained 394 drugs with known indication from CMAP. To validate the feasibility of applying new DMAP for systematic drug repositioning, we compared the performance of DMAP and the well-known CMAP database on two popular computational techniques: drug-drug-similarity-based method with leave-one-out validation and Kolmogorov-Smirnov scoring based method. In drug-drug-similarity-based method, the drug repositioning prediction using DMAP achieved an Area-Under-Curve (AUC) score of 0.82, compared with that using CMAP, AUC = 0.64. For Kolmogorov-Smirnov scoring based method, with DMAP, we were able to retrieve several drug indications which could not be retrieved using CMAP. DMAP data can be queried using the existing C2MAP server or downloaded freely at: http://bio.informatics.iupui.edu/cmaps

### Conclusions
Reliable measurements of how drug affect disease-related proteins are critical to ongoing drug development in the genome medicine era. We demonstrated that DMAP can help drug development professionals assess drug-to-protein relationship data and improve chances of success for systematic drug repositioning efforts.



## How to cite us
Huang, H., Nguyen, T., Ibrahim, S., Shantharam, S., Yue, Z., & Chen, J. Y. (2015). **DMAP: a connectivity map database to enable identification of novel drug repositioning candidates.** _MC bioinformatics_, 2019, 16 Suppl 13(Suppl 13), S4.  <span class="fs-3">[doi](https://doi.org/10.1186/1471-2105-16-S13-S4){:target="_blank"}</span>

