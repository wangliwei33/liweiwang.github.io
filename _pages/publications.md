---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Selected Peer-Reviewed Publications
___

* **Wang L**, He H, Wen A, Moon S, Fu S, Peterson KJ, Ai X, Liu S, Kavuluru R, Liu H. Acquisition of a Lexicon for Family History Information: Bidirectional Encoder Representations From Transformers–Assisted Sublanguage Analysis. JMIR Medical Informatics. 2023 Jun 27;11:e48072.

* **Wang L**, Fu S, Wen A, Ruan X, He H, Liu S, Moon S, Mai M, Riaz IB, Wang N, Yang P. Assessment of electronic health record for cancer research and patient care through a scoping review of cancer natural language processing. JCO Clinical Cancer Informatics. 2022 Aug;6:e2200006.

* **Wang L**, Olson JE, Bielinski SJ, St. Sauver JL, Fu S, He H, Cicek MS, Hathcock MA, Cerhan JR, Liu H. Impact of diverse data sources on computational phenotyping. Frontiers in genetics. 2020 Jun 3;11:556.

* **Wang L**, Luo L, Wang Y, Wampfler J, Yang P, Liu H. Natural language processing for populating lung cancer clinical research data. BMC medical informatics and decision making. 2019 Dec;19:1-0.

* **Wang L**, Wang Y, Shen F, Rastegar-Mojarad M, Liu H. Discovering associations between problem list and practice setting. BMC medical informatics and decision making. 2019 Apr;19(3):13-22.

* **Wang L**, Wampfler J, Dispenzieri A, Xu H, Yang P, Liu H. Achievability to extract specific date information for cancer research. InAMIA Annual Symposium Proceedings 2019 (Vol. 2019, p. 893). American Medical Informatics Association.

* **Wang L**, Rastegar-Mojarad M, Ji Z, Liu S, Liu K, Moon S, Shen F, Wang Y, Yao L, Davis III JM, Liu H. Detecting pharmacovigilance signals combining electronic medical records with spontaneous reports: a case study of conventional disease-modifying antirheumatic drugs for rheumatoid arthritis. Frontiers in pharmacology. 2018 Aug 7;9:875.

* **Wang L**, Li M, Cao Y, Han Z, Wang X, Atkinson EJ, Liu H, Amin S. Proton pump inhibitors and the risk for fracture at specific sites: data mining of the FDA adverse event reporting system. Scientific reports. 2017 Jul 17;7(1):5527.

* **Wang L**, Li M, Xie J, Cao Y, Liu H, He Y. Ontology-based systematical representation and drug class effect analysis of package insert-reported adverse events associated with cardiovascular drugs used in China. Scientific reports. 2017 Oct 23;7(1):13819.

* **Wang L**, Ruan X, Yang P, Liu H. Comparison of three information sources for smoking information in electronic health records. Cancer informatics. 2016 Jan;15:CIN-S40604.

* **Wang L**, Liu H, Chute CG, Zhu Q. Cancer based pharmacogenomics network supported with scientific evidences: from the view of drug repurposing. BioData mining. 2015 Jun;8(1):1-4.

* **Wang L**, Jiang G, Li D, Liu H. Standardizing adverse drug event reporting data. Journal of biomedical semantics. 2014 Dec;5(1):1-3.


## Cancer informatics
___


{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=QVp3dZIAAAAJ&view_op=list_works&sortby=pubdate">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
