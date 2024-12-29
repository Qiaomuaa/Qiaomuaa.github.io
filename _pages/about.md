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

I am Xinbao Qiao (Sheen-bao Ciao /ʃɪnbaʊ/ /tʃjaʊ/), a third-year master student in the [Zhejiang University](https://www.zju.edu.cn/english/) . 

I graduated from [Shandong University](https://www.en.sdu.edu.cn/) with a bachelor’s degree. Now I study at [ZJUI](https://zjui.intl.zju.edu.cn/en) with a master’s degree, advised by [Meng Zhang](https://person.zju.edu.cn/mengzhang).

My research interest includes Trustworthy ML, including Machine Unlearning, Privacy, Fairness, and exploration of trade-offs between different pillars of trust in Machine Learning.

<!-- 
I have published 1 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=nhC_OfEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

<!-- 
# News
- *2022.07*: &nbsp;🎉🎉 I graduated from Shandong University with a bachelor’s degree!
<br>
-->

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2024</div><img src='images/HF Unlearning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hessian-Free Online Certified Unlearning](https://arxiv.org/abs/2404.01712)

**Xinbao Qiao**, Meng Zhang, Ming Tang, Ermin Wei

- Approximate Machine Unlearning, Certified Data Removal, Privacy
  
**TL;DR**: addressing second-order certified unlearning gaps in non-convex settings and nonconvergence conditions, while achieving the most efficient data removal.

[**Code**](https://github.com/XinbaoQiao/Hessian-Free-Certified-Unlearning) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>    [**Slide**](https://arxiv.org/abs/2404.01712) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
 [**Paper**](https://arxiv.org/abs/2404.01712) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2024</div><img src='images/DynFrs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[DynFrs: An Efficient Framework for Machine Unlearning in Random Forest](https://arxiv.org/abs/2410.01588)

Shurong Wang, Zhuoyang Shen, **Xinbao Qiao**, Tongning Zhang, Meng Zhang

- Exact Machine Unlearning, Random Forest, Privacy
  
**TL;DR**: combining subsampling methods, the lazy tag strategy, and the robustness of Extremely Randomized Trees to achieve Random Forest unlearning in dynamic environments.

[**Code**](https://arxiv.org/abs/2410.01588) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>    [**Slide**](https://arxiv.org/abs/2410.01588) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
 [**Paper**](https://arxiv.org/abs/2410.01588) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/HF Unlearning.png.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Soft-Weighted Machine Unlearning (manuscript)]((https://arxiv.org/abs/2404.01712))

**Xinbao Qiao**, Meng Zhang, Ningning Ding

- Machine Unlearning, Influence Function, Fairness, Data Drift
  
**TL;DR**: Addressing the challenge of excessive unlearning in non-privacy-focused scenarios through soft-weighted strategies.

[**Code**](https://arxiv.org/abs/2410.01588) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>    [**Slide**](https://arxiv.org/abs/2410.01588) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
 [**Paper**](https://arxiv.org/abs/2410.01588) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>

<!-- 
# Honors and Awards
- *2022.10* None.
-->

# Educations
- *2022.09* -  present, Master, Artificial Intelligence, Zhejiang University
- *2018.09 - 2022.07*, Bachelor, Communication Engineering, Shandong Univeristy.

<!-- 
# Experiences
- *2022.10 - 2022.10*, [None](https://github.com/), China.
-->



<!-- 添加样式 -->
<style>
    .page-view-container {
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 20px 0;
        padding: 10px 20px;
        background: #f9f9f9;
        border: 1px solid #ddd;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        font-family: Arial, sans-serif;
        color: #333;
    }
    .page-view-container i {
        margin-left: 5px;
        color: #007BFF;
    }
</style>

<!-- 页脚内容 -->
<div class="page-view-container">
    Total page views: <span id="busuanzi_value_page_pv"><i class="fa fa-spinner fa-spin"></i></span>
</div>

<!-- Font Awesome 样式表 -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">


