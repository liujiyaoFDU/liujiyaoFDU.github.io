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

<!-- ![](https://picx.zhimg.com/v2-19c81401b0b538ae313c8b8a1082c4f7_1440w.jpg?source=32738c0c) -->
👨‍🎓 I'm Jiyao Liu (刘继垚), currently a third-year Ph.D. student majoring in Biomedical Engineering at 
[Institute of Science and Technology for Brain-Inspired Intelligence (ISTBI)](https://istbi.fudan.edu.cn/), Fudan University. I am honored to be advised by Prof. Dr. [Xiahai Zhuang](https://zmiclab.github.io/zxh/) and [Dr. Ningsheng Xu](https://en.wikipedia.org/wiki/Xu_Ningsheng). Previously, I received the Bachelor's degree (June 2022) in Intelligence Science and Technology from Xidian University.

🔭 Research interests

My research interest includes **AI in Medical Imaging** and **Generative Model**, e.g., trustworthy multimodal medical image synthesis, generalizable MRI reconstruction / inverse problem in medical imaging. At present, I devote to enhancing the reliability and generalizability of medical image reconstruction.



<!-- I have published more than 1 papers at the medical conferences with total <a href='https://scholar.google.com/citations?user=01i77FUAAAAJ'>google scholar citations <strong><span id='total_cit'>0</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=01i77FUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.10*: &nbsp;🎉🎉  One paper has been oral reported on SASHIMI, MICCAI workshop, 2023.
- *2021.12*: &nbsp;I started my research on Cross-modality face recognition with Dr. [Qigong Sun](https://scholar.google.com/citations?hl=en&user=u_cpfzQAAAAJ&view_op=list_works&sortby=pubdate) from SenseTime Group.
- *2021.05*: &nbsp;🎉🎉  MCM/ICM, Mathematical Contest in Modeling, **Outstanding Winner🎉**（美国大学生数学建模竞赛特等奖，O奖）

# 📝 Publications 

sensitivity1.png

<!-- TTARecon -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submited to IEEE TMI</div><img src='images/sensitivity1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A New Framework of Implicit Prior Adaptation for Boosting Test-Time MRI Reconstruction

**Jiyao Liu**, Shangqi Gao, Xiao-Yong Zhang, Ningsheng Xu and Xiahai Zhuang

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this work, we propose a zero-shot adaptation framework tailored to the reference phase of an implicit prior-based MRI reconstruction model. This framework is designed to seamlessly integrate with any contemporary implicit prior-based methods without modifying their architectures or pre-trained weights. Our approach requires only the automatic adjustment of three scaling factors during inference. 
</div>
</div>
<!--  -->

<!-- TrustI2I -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/trusti2i.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trustworthy Contrast-enhanced Brain MRI Synthesis with Deep Evidential Regression](https://arxiv.org/abs/2407.07372)

**Jiyao Liu**, Yuxin Li, Shangqi Gao, Yuncheng Zhou, Ningsheng Xu, Xiao-Yong Zhang, and Xiahai Zhuang

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this work, we propose a new method that approaches multi-to-one medical image translation as a multimodal regression problem for brain CE-MRI synthesis. We developed an uncertainty-aware framework using deep evidential regression with uncertainty calibration and incorporated source modality fusion to improve performance, reliability, and interpretability.
</div>
</div>
<!--  -->

<!-- MrGAN -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI workshop 2023 oral</div><img src='images/miccai_workshop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Phase Liver-Specific DCE-MRI Translation via a Registration-Guided GAN](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=01i77FUAAAAJ&citation_for_view=01i77FUAAAAJ:9yKSN-GCB0IC)

**Jiyao Liu**, Yuxin Li, Nannan Shi, Yuncheng Zhou, Shangqi Gao, Yuxin Shi , Xiao-Yong Zhang, Xiahai Zhuang

[**Project**](https://github.com/Jy-stdio/MrGAN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper introduces a new dataset and a novel application of image translation from multi-phase DCE-MRIs into a virtual GED- HBP image (v-HBP) that could be used as a substitute for GED-HBP in clinical liver diagnosis. 
</div>
</div>
<!--  -->

# 🎖 Honors and Awards
- *2022.06* Undergraduate Excellence Award.
- *2021.05* MCM/ICM, Mathematical Contest in Modeling, Outstanding Winner \| [\[blog\]](https://zhuanlan.zhihu.com/p/370250195) \| [\[github\]](https://github.com/Jy-stdio/2021-ICM-D-Outstanding). 
- *2019/2020/2021* National Endeavor Scholarship (BSc), Xidian University.
# 📖 Educations
- *2022.09 - 2027.06 (now)*, P.h.d., Fudan University, Shanghai.
- *2018.09 - 2022.06*, B.S., Xi Dian University, Xi'an.

# 💬 Invited Talks
- *2023.10*, Oral report \| [International Workshop on Simulation and Synthesis in Medical Imaging (SASHIMI)](https://2023.sashimi-workshop.org/) ,MICCAI workshop, 2023.
- *2021.03*, Oral report \| [International Society for Magnetic Resonance in Medicine (ISMRM)](https://www.ismrm.org/)

# 💻 Internships
- *2021.12 - 2022.06*, Sensetime（商汤科技，算法实习生）, Xi'an.

# Daily Life
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">2023.10 共青森林公园</div><img src='images/life-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-image'><div><div class="badge">2024.08 香港大学 </div><img src='images/life-3.jpg' alt="sym" width="100%"></div></div>
</div>