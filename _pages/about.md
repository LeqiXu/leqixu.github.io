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

I am a Postdoctoral Scholar in Genetics at Stanford University, advised by [Prof. Jonathan Pritchard](https://web.stanford.edu/group/pritchardlab/home.html). Previously, I completed my Ph.D. in Biostatistics at Yale University, advised by [Prof. Hongyu Zhao](https://zhaocenter.org).

The central theme of my research is to develop novel statistical and AI methods that integrate genetics, single-cell, and electronic health records (EHR) data to understand the biological mechanisms and clinical pathways underlying complex traits and diseases. By bridging these complementary data sources, I aim to enable new scientific discoveries and to enhance disease prediction, risk stratification, and personalized healthcare.

# 💼 Employment

- Postdoctoral Scholar in Genetics, Stanford University (June 2026 – December 2026).

# 📖 Education

- Ph.D. in Biostatistics, Yale University (September 2021 – May 2026), dissertation awarded with distinction.
- B.S. in Statistics, Fudan University (September 2017 – June 2021).

<span class="anchor" id="selected-publications"></span>

# 📝 Selected Publications

(<sup>∗</sup> indicates co-first authorship; <sup>†</sup> indicates co-corresponding authorship)

## **Statistical Methodologies**

1. **Xu, L.**, Dong, Y., Zeng, X., Bian, Z., Zhou, G., Guan, L., Zhao, H. (2026)  
   MIXPRS enables multi-population and multi-method polygenic risk scores using summary statistics.  
   **Nature Genetics** [[paper](https://doi.org/10.1038/s41588-026-02637-4)] [[software](https://github.com/LeqiXu/MIXPRS)] [[analysis](https://github.com/LeqiXu/MIXPRS_analysis)]

2. Lin, C., Lin, Y., Li, W., **Xu, L.**, Zhang, X., Zhao, H. (2026)  
   Leveraging cell-type specificity and similarity improves single-cell eQTL fine-mapping.  
   **Nature Communications** [[paper](https://www.nature.com/articles/s41467-026-72176-3)] [[software](https://github.com/leaffur/CASE)]

3. **Xu, L.**, Zheng, W., Hu, J., Lin, Y., Zhao, J., Wang, G., Liu, T., Zhao, H. (2025)  
   Improving polygenic risk prediction performance through integrating electronic health records by phenotype embedding.  
   **The American Journal of Human Genetics** [[paper](https://www.cell.com/ajhg/fulltext/S0002-9297(25)00431-8)] [[software](https://github.com/LeqiXu/EEPRS)] [[analysis](https://github.com/LeqiXu/EEPRS_analysis)]

4. **Xu, L.**, Zhou, G., Jiang, W., Zhang, H., Dong, Y., Guan, L.<sup>†</sup>, Zhao, H.<sup>†</sup> (2025)  
   JointPRS: A data-adaptive framework for multi-population genetic risk prediction incorporating genetic correlation.  
   **Nature Communications** [[paper](https://www.nature.com/articles/s41467-025-59243-x)] [[software](https://github.com/LeqiXu/JointPRS)] [[analysis](https://github.com/LeqiXu/JointPRS_analysis)]  
   * **Reviewers' Choice Award**, American Society of Human Genetics 2023 Annual Meeting.

5. Jiang, J., **Xu, L.**, Zhang, Y., Zhao, H. (2024)  
   The method of limits and its application to the analysis of count data in genome-wide association studies.  
   **Statistica Sinica** [[paper](https://www3.stat.sinica.edu.tw/statistica/fp/SS-2024-0092.html)] [[analysis](https://github.com/LeqiXu/MoL_analysis)]  
   * **Statistica Sinica Invited Paper**, Joint Meetings of 2025 Taipei International Statistical Symposium and 13th ICSA International Conference.

## **Applications**

1. Rivier, C., **Xu, L.**, Clocchiatti-Tuozzo, S., Zhao, H., Ohno-Machado, L., Hafler, D., Falcone, G.<sup>†</sup>, Longbrake, E.<sup>†</sup> (2025)  
   Differential results of genetic risk scoring for multiple sclerosis in European and African-American populations.  
   **Multiple Sclerosis Journal** [[paper](https://journals.sagepub.com/doi/10.1177/13524585251377607)]

2. Gygi, J.P.<sup>∗</sup>, Maguire, C.<sup>∗</sup>, Patel, R.K.<sup>∗</sup>, Shinde, P., Konstorum, A., Shannon, C.P., **Xu, L.**, …, Guan, L. (2024)  
   Integrated longitudinal multiomics study identifies immune programs associated with acute COVID-19 severity and mortality.  
   **The Journal of Clinical Investigation** [[paper](https://www.jci.org/articles/view/176640)]
