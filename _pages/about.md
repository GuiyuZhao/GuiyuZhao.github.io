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

<!--I'm a first-year PhD in [Institute of Automation, Chinese Academy of Sciences](https://ia.cas.cn/)).  -->
I'm a currently third year master from [National Key Laboratory of Autonomous Intelligent Unmanned](https://csicdgz.bit.edu.cn/), [Beijing Institute of Technology](https://www.bit.edu.cn/). 
I am advised by [Prof. Ma Hongbin](http://www.we-learn.net.cn/mathmhb/).
Before this, I received my Bachelor’s Degree, majoring in Automation, from China University of Geosciences (Wuhan) in June 2022, under the supervision of [Prof. Li Danyun](https://grzy.cug.edu.cn/lidanyun/). 

My research focuses on 3D Computer Vision, Embodied AI, and Robotics. Currently, I specialize in Point Cloud Registration, Visual-Language-Action Model.  If you are interested in my research, feel free to contact me at <zhaoguiyu2025@ia.ac.cn>.
<a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


# 🔥 News
- *2025-05*: I won the [Xu Teli Scholarship](https://xtlfund.bit.edu.cn/) (highest scholarship in BIT, Top 5)! 🎉🎉🎉
- *2025-03*: Our Regor is accepted by CVPR 2025! Many thanks to Prof. Guo and Prof. Ao.🎉🎉🎉
- *2024-11*: Our Cross-PCR is accepted by AAAI 2025! 🎉🎉🎉
- *2024-11*: Our GOR-PCR is accepted by IEEE TIM! 🎉🎉🎉
- *2024-10*: I won the National Scholarship for masters! 🎉🎉🎉
- *2024-08*: Our LDA-AQU accepted by ACM MM 2024! 🎉🎉🎉
- *2024-08*: Our SGOR is accepted by IROS 2024! 🎉🎉🎉
- *2024-05*: Our VRHCF is accepted by ICME 2024! 🎉🎉🎉
- *2023-12*: Our SphereNet is accepted by IEEE TGRS 2024! 🎉🎉🎉
- *2020-09*: I won the National Scholarship for undergraduate students! 🎉🎉🎉

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/Regor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Progressive Correspondence Regenerator for Robust 3D Registration

**Guiyu Zhao<sup>*</sup>**, Sheng Ao<sup>*</sup>, Ye Zhang, Kai Xu, Yulan Guo<sup>&dagger;</sup>

<span style="color:red">**CVPR 2025 (CCF-A)**</span>

[[Paper]](https://arxiv.org/abs/2412.18873), [[Code]](https://github.com/GuiyuZhao/Regor)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/Cross-PCR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"Cross-PCR: A Robust Cross-Source Point Cloud Registration Framework

**Guiyu Zhao**, Zhentao Guo, Hongbin Ma<sup>&dagger;</sup>

<span style="color:red">**AAAI 2025 (CCF-A)**</span>

[[Paper]](https://arxiv.org/abs/2412.18873), [[Code]](https://github.com/GuiyuZhao/Cross-PCR)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/SGOR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SGOR: Outlier Removal by Leveraging Semantic and Geometric Information for Robust Point Cloud Registration

**Guiyu Zhao**, Zhentao Guo, Hongbin Ma<sup>&dagger;</sup>

<span style="color:red">**IROS 2024 (CCF-B, Oral)**</span>

[[Paper]](https://arxiv.org/abs/2407.06297), [[Code]](https://github.com/GuiyuZhao/SGOR)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/SphereNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SphereNet: Learning a Noise-Robust and General Descriptor for Point Cloud Registration

**Guiyu Zhao**, Zhentao Guo, Xin Wang, Hongbin Ma<sup>&dagger;</sup>

<span style="color:red">**IEEE TGRS (CCF-B, IF=8.6)**</span>

[[Paper]](https://ieeexplore.ieee.org/document/10356130), [[Code]](https://github.com/GuiyuZhao/SphereNet)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/GOR-PCR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

GOR-PCR: Graph-based Outlier Removal with global-to-local consistency for Point Cloud Registration

**Guiyu Zhao**, Zhentao Guo, Hongbin Ma<sup>&dagger;</sup>

<span style="color:red">**IEEE TIM (IF=5.9)**</span>

[[Paper]](https://ieeexplore.ieee.org/document/10752621), [[Code]](https://github.com/GuiyuZhao/GOR-PCR)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/ICME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Cross-source Point Cloud Registration via Voxel Representation and Hierarchical Correspondence Fitering

**Guiyu Zhao**, Zewen Du, Zhentao Guo, Hongbin Ma<sup>&dagger;</sup>

<span style="color:red">**ICME (CCF-B)**</span>

[[Paper]](https://arxiv.org/pdf/2403.10085), [[Code]](https://github.com/GuiyuZhao/VRHCF)
</div>
</div>



<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🎖 Honors and Awards
## 💬 Scholarships
- *2025-05*: [Xu Teli Scholarship](https://xtlfund.bit.edu.cn/) (highest scholarship in BIT)
- *2024-10*: Graduate Academic Scholarship (BIT) - Special Class
- *2024-10*: National Scholarship for Master
- *2024-05*: NORINCO Scholarship
- *2023-10*: Graduate Academic Scholarship (BIT) - Special Class
- *2022-10*: Graduate Academic Scholarship (BIT) - Special Class
- *2021-10*: Academician Scholarship
- *2020-10*: National Scholarship for Bachelor

## 💬 Honors
- *2025-06*: Beijing Outstanding Graduates
- *2024-12*: Outstanding graduate student, Beijing Association of Automation
- *2024-10*: Young Researcher Award, ISCIIA-ITCA 2024
- *2024-09*: BIT Excellent Student Model
- *2024-09*: BIT Excellent Student Model
- *2023-09*: BIT Excellent Student Model
- *2022-06*: CUG Outstanding Graduates
- *2022-06*: CUG Excellent Graduation Thesis
- *2022-05*: CUG Excellent Communist Party member
- *2021,2020-09*: CUG Excellent Student Model
- *2021-05*: CUG Excellent Member of the Communist Youth League
- *2020-05*: CUG Excellent Cadres of the Communist Youth League

## 💬 Competitions
- *2023-08*: **Champion** of 2023 International Autonomous Intelligent Robot Competition
- *2022-11*: **Second Prize** of National Artificial Intelligence Robot Competition
- *2022-10*: **Second Prize** of China Graduate Mathematical Contest in Modeling
- *2022-08*: **First Prize** of 2022 International Autonomous Intelligent Robot Competition
- *2021-05*: **First prize (2nd)** of Huazhong Mathematical Contest in Modeling
- *2020-05*: **Second Prize** of Hubei Mathematics Competition.
  
# 📖 Educations
- Ph.D in Computer Science, XXX University, 2025 (expected)
- M.S. in Automation, Beijing Institute of Technology, 2022
- B.S. in Automation, China University of Geosciences, 2018

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
