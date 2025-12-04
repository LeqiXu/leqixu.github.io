---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a fourth-year Ph.D. student in Biostatistics at Yale School of Public Health, advised by Dr. Hongyu Zhao. My research interests focus on both methodological development and applied analysis involving polygenic risk scores (PRS) and electronic health records (EHR). I develop statistical methods to integrate genetic and clinical data, aiming to enhance disease prediction, risk stratification, and personalized healthcare.

# 📖 Education
- Ph.D. in Biostatisitcs, Yale University (2021 - Present).
- B.S. in Statistics, Fudan University (2017 - 2021). 
  
# 📝 Selected Publications  
(<sup>∗</sup> indicates co-first authorship; † indicates co-corresponding authorship)

## **Statistical Methodologies**
1. **Xu, L.**, Dong, Y., Zeng, X., Bian, Z., Zhou, G., Guan, L., Zhao, H. (2025)  
   Almost Free Enhancement of Multi-Population PRS: From Data-Fission to Pseudo-GWAS Subsampling.  
   *bioRxiv* [[preprint](https://www.biorxiv.org/content/10.1101/2025.06.16.659952v1)] [[software](https://github.com/LeqiXu/MIXPRS)] [[analysis](https://github.com/LeqiXu/MIXPRS_analysis)]

2. **Xu, L.**, Zheng, W., Hu, J., Lin, Y., Zhao, J., Wang, G., Liu, T., Zhao, H. (2025)  
   Improving polygenic risk prediction performance through integrating electronic health records by phenotype embedding.  
   **The American Journal of Human Genetics**  [[paper](https://authors.elsevier.com/c/1mDFegeXDzeU)] [[software](https://github.com/LeqiXu/EEPRS)] [[analysis](https://github.com/LeqiXu/EEPRS_analysis)]

3. **Xu, L.**, Zhou, G., Jiang, W., Zhang, H., Dong, Y., Guan, L.†, Zhao, H.† (2025)  
   JointPRS: A data-adaptive framework for multi-population genetic risk prediction incorporating genetic correlation.  
   **Nature Communications**  [[paper](https://www.nature.com/articles/s41467-025-59243-x)] [[software](https://github.com/LeqiXu/JointPRS)] [[analysis](https://github.com/LeqiXu/JointPRS_analysis)]  
   * **Reviewers’ Choice Award**, American Society of Human Genetics 2023 Annual Meeting.

4. Jiang, J., **Xu, L.**, Zhang, Y., Zhao, H. (2024)  
   The Method of Limits and Its Application to the Analysis of Count Data in Genome-wide Association Studies.  
   **Statistica Sinica** [[paper](https://www3.stat.sinica.edu.tw/ss_newpaper/SS-2024-0092_na.pdf)] [[analysis](https://github.com/LeqiXu/MoL_analysis)]
   * **Statistica Sinica Invited Paper**, Joint Meetings of 2025 Taipei International Statistical Symposium and 13th ICSA International Conference.

## **Applications**

1. Rivier, C., **Xu, L.**, Clocchiatti-Tuozzo, S., Zhao, H., Ohno-Machado, L., Hafler, D., Falcone, G.†, Longbrake, E.† (2025)  
   Differential Results of Genetic Risk Scoring for Multiple Sclerosis in European and African-American Populations.  
   **Multiple Sclerosis Journal** [[paper](https://journals.sagepub.com/doi/10.1177/13524585251377607)]
  
2. Gygi, J.P.<sup>∗</sup>, Maguire, C.<sup>∗</sup>, Patel, R.K.<sup>∗</sup>, Shinde, P., Konstorum, A., Shannon, C.P., **Xu, L.**, …, Guan, L. (2024)  
   Integrated longitudinal multiomics study identifies immune programs associated with acute COVID-19 severity and mortality.  
   **The Journal of Clinical Investigation** [[paper](https://www.jci.org/articles/view/176640)] 
