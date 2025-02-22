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

# About me
Welcome to my page! I am **Zheng (Will) Xing (邢正)**, currently pursuing a PhD at the **School of Science and Engineering**, **The Chinese University of Hong Kong, Shenzhen**. I am fortunate to be affiliated with the [**Laboratory for Wireless Communication and Intelligent Signal Processing**](http://chenjunting.org/), under the guidance of **Prof. [Junting Chen (陈俊挺)]([http://chenjunting.org/](https://scholar.google.com.hk/citations?user=hsPzukQAAAAJ&hl=en&oi=ao))**.


<!--I earned my **MPhil** degree from the **School of Electrical Science and Automation**, **Beihang University**, Beijing, China, and my **Bachelor's** degree from the **School of Electrical Science and Automation**, **Ocean University of China**, Qingdao, China.-->

## Research Interests
-- *Unsupervised Learning of Sequential Data*: Exploring the segmentation of human motion sequences through temporal learning of neighboring frames. Additionally, conducting analysis on wireless channel knowledge collected via trajectory data, with a focus on visualizing the data collection trajectories.
-- *Trajectory Estimation*: Developing techniques for recovering data collection trajectories through RSS, CSI, AoA, and ToA measurements, to construct radio maps for enabling indoor localization of mobile users and outdoor localization of vehicles.
-- *Data Clustering*: Investigating the neighbor relationships within data, constructing similarity matrices, and analyzing their block-diagonal properties to enhance clustering algorithms.



<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=TjqNW9QAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=TjqNW9QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.01*: &nbsp;🎉🎉 One paper about vehicle trajectory map matching is accepted by T-ITS.
- *2025.01*: &nbsp;🎉🎉 One paper about outdoor radio map construction is accepted by ICC.

# 📝 Publications 

## Journal Papers

<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS</div><img src='images/TITS2025.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Trajectory Map-Matching in Urban Road Networks Based on RSS Measure-
ments](https://arxiv.org/abs/2502.01280)

**Zheng Xing**, Weibing Zhao

*IEEE Transactions on Intelligent Transportation Systems (T-ITS), vol. 0, no. 0, pp.0 - 0, January 2025 中科院一区 (2023), JCR Q1*

This paper...

</div>
</div>


<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IoT-J</div><img src='images/IOTJ2024.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Calibration-Free Indoor Positioning via Regional Channel Tracing](https://ieeexplore.ieee.org/document/10735384)

**Zheng Xing**, Weibing Zhao

*IEEE Internet of Things Journal (IoT-J), vol. 0, no. 0, pp.0 - 0, November 2024 中科院一区 (2023), JCR Q1*

This paper...

</div>
</div>



<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP</div><img src='images/TIP2024.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Segmentation and Completion of Human Motion Sequence via Temporal
Learning of Subspace Variety Model](https://pubmed.ncbi.nlm.nih.gov/39178090/)

**Zheng Xing**, Weibing Zhao

*IEEE Transactions on Image Processing (TIP), vol. 0, no. 0, pp.0 - 0, November 2024 中科院一区 (2023), CCF A, JCR Q1*

This paper...

</div>
</div>
 
<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDE</div><img src='images/TKDE2024.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Block-Diagonal Guided DBSCAN Clustering](https://ieeexplore.ieee.org/document/10530414)

**Zheng Xing**, Weibing Zhao

*IEEE Transactions on Knowledge and Data Engineering (TKDE), vol. 36, no. 11, pp.5709 - 5722, November 2024 中科院一区 (2022), CCF A, JCR Q1*

This paper presents a refined DBSCAN algorithm that utilizes block-diagonal similarity graphs to improve clustering, addressing challenges in high-dimensional datasets, sensitivity to parameters, and inconsistent outcomes.

</div>
</div>


<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TSP</div><img src='images/TSP2024.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Constructing Indoor Region-Based Radio Map Without Location Labels](https://ieeexplore.ieee.org/abstract/document/10443723/)

**Zheng Xing**, Junting Chen

<!-- -->
<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

*IEEE Transactions on Signal Processing (TSP), vol. 72, no. 22, pp.2512 - 2526, February 2024, 中科院一区 (2022), JCR Q1*


This paper introduces a refined DBSCAN algorithm utilizing block-diagonal similarity graphs, addressing challenges in high-dimensional data and parameter sensitivity. It employs a self-representation model, gradient descent, and a traversal algorithm to generate enhanced cluster orderings, achieving superior clustering performance on real-world datasets.

</div>
</div>

## Conference Papers

<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICC</div><img src='images/ICC2025.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Constructing Angular Power Maps in Massive MIMO Networks Using Measurements without Location Labels](https://arxiv.org/abs/2502.01280)

**Zheng Xing**, Junting Chen

*IEEE International Conference on Communications (ICC), 2025.*

This paper...

</div>
</div>


<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI</div><img src='images/AAAI2024.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Unsupervised Action Segmentation via Fast Learning of Semantically Consistent Actoms](https://ojs.aaai.org/index.php/AAAI/article/view/28445)

**Zheng Xing**, Weibing Zhao

*Proceedings of the AAAI Conference on Artificial Intelligence (AAAI), vol. 38, no. 6, pp. 6270–6278, 2024.*

This paper...

</div>
</div>


<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP</div><img src='images/Icassp2024.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[HMM-Based CSI Embedding for Trajectory Recovery from RSS Measurements of Non-Cooperative Devices](https://sigport.org/documents/hmm-based-csi-embedding-trajectory-recovery-rss-measurements-non-cooperative-devices)

**Zheng Xing**, Junting Chen

*IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 7060–7064, 2024.*

This paper...

</div>
</div>


<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GlobeCom</div><img src='images/GlobeCom2023.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Integrated Segmentation and Subspace Clustering for RSS-Based Localization under Blind Calibration](https://ieeexplore.ieee.org/document/10001272/)

**Zheng Xing**, Weibing Zhao

*IEEE Global Communications Conference (GlobeCom), pp. 5360–5365, 2022.*

This paper...

</div>
</div>

<!-- ############################ -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WCNC</div><img src='images/WCNC2022.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Spectrum Efficiency Prediction for Real-World 5G Networks Based on Drive Testing Data](https://ieeexplore.ieee.org/document/9771696)

**Zheng Xing**, Weibing Zhao

*IEEE Wireless Communications and Networking Conference (WCNC), pp. 2136–2141, 2022.*

This paper...

</div>
</div>

## Patents
- 邢正,陈俊挺,一种基于接收信号强度的轨迹恢复及无线电地图构建方法,	中国, 1775494.6	1,	2024年9月27日,		CN 117768843 B
- 邢正,陈俊挺, 一种室内定位方法及子空间特征提取方法,	中国, 1480461.4	2,	2023年08月18,		CN 115988634 B


## Projects
- Huawei Wireless Spectrum Prediction, Student Leader
- Air-to-Air Missile Seeker Measurement, Student Leader





# 🎖 Honors and Awards
- *Excellent Graduate of the Beihang University*, 2020
- Excellent League Member of the Beihang University, 2018
- First-Class Scholarship of the Beihang University, 2017-2020
- *Excellent Undergraduate of the Ocean University of China*, 2017
- *Excellent Undergraduate of Shandong Province*, 2017
- Silver Award in National Electronic Design Competition 2016
- Excellent Student of the Ocean University of China, 2016
- *National Scholarship*, 2016
- *National Scholarship*, 2015
- Excellent Student of the Ocean University of China, 2014
- First-Class Scholarship, 2013-2017



# 📖 Educations
- <img height="25" src="/images/CUSZ_logo.png" width="25" style="vertical-align: middle;"/> 2021.01 - 2025.7, Doctor of Philosophy, Computer and Information Engineering, School of Science and Engineering, [The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en), China
- <img height="25" src="/images/Beihang_logo.png" width="25" style="vertical-align: middle;"/> 2017.09 - 2020.07, Master of Science, Control Science and Control Engineering, School of Electrical Science and Automation, [Beihang University](https://ev.buaa.edu.cn/), Beijing, China.
- <img height="25" src="/images/OUC_logo.png" width="25" style="vertical-align: middle;"/> 2013.09 - 2017.07, Bachelor of Engineering, Electrical Engineering and Automation, School of Electrical Science and Automation, [Ocean University of China](http://eweb.ouc.edu.cn/), Qingdao, China.


# Experience
- <img height="25" src="/images/Mal_logo.png" width="25" style="vertical-align: middle;"/> 2018.09 - 2019.01, [Universiti Malaya](https://www.um.edu.my/), Kuala Lumpur, Malaysia.
- <img height="25" src="/images/dalian_logo.png" width="25" style="vertical-align: middle;"/> 2014.09 - 2016.04, [Dalian University of Technology](https://en.dlut.edu.cn/), Dalian, China 



<!--# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

  
# 💻 Internships
- *2017.09 - 2020.01*, [China Aerospace Science and Technology](https://www.spacechina.com/n25/index.html), Beijing, China.

# Academic Service

## Reviewer for Journals:
- IEEE Journal on Selected Areas in Communications (JSAC)
- IEEE Transactions on Signal Processing (TSP)
- IEEE Transactions on Wireless Communications (TWC)
- IEEE Transactions on Mobile Computing (TMC)
- IEEE Transactions on Communications (TCOM)
- IEEE Internet of Things Journal (IOTJ)


## Reviewer for Conferences:

- IEEE International Conference on Communications (ICC)
- IEEE Global Communications Conference (Globecom)
- International Conference on Acoustics, Speech, and Signal Processing (ICASSP)
- International Conference on Learning Representations (ICLR)
- International Conference on Machine Learning (ICML)
- AAAI Conference on Artificial Intelligence (AAAI)
- IEEE/CIC International Conference on Communications in China (ICCC)
- IEEE International Conference on Machine Learning in Communications and Networking (ICMLCN)
- International Joint Conference on Neural Networks (IJCNN)


# Teaching Experience
- Calculus I (MAT1001), The Chinese University of University of Hong Kong, Shenzhen, Course Leader, Sep. 2020 - Apr. 2023
- Digital Signal Processing (EE4015), The Chinese University of University of Hong Kong, Shenzhen, Course Leader, Sep. 2023 - Dec. 2023
- Digital Circuits and Systems (ELEG2201), The Chinese University of University of Hong Kong, Shenzhen, Course Leader, Jan. 2024 - Apr. 2024
