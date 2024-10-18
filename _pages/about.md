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

I am now a second-year PhD candidate at [AML Lab](https://aml-cityu.github.io/) CityU HK supervised by Prof. [Xiangyu Zhao](https://zhaoxyai.github.io/). Before that, I graduated from Zhejiang University (ZJU) with a bachelor's degree in Geographic Information Science and from Hong Kong University (HKU) with a master's degree in Computer Science. My research interest includes Recommender System, Information Retrieval, Large Language Models, and GeoAI.

# 🔥 News

<style>
  .scrollable {
    max-height: 240px; /* 设置最大高度 */
    overflow-y: scroll; /* 设置垂直滚动条 */
  }
</style>

<!-- <font color="red></font>
<a href=""></a> -->

<div class="scrollable">
  <ul>
    <li><strong>2024.10</strong>: I'm Glad to receive the <b>NeurIPS 2024 Scholar Award</b>!</li>
    <li><strong>2024.09</strong>: Our paper G3 is accepted to <b>NeurIPS'24</b>!</li>
    <li><strong>2024.09</strong>: Recieving Outstanding Academic Performance Award (OAPA) from CityUHK.</li>
    <li><strong>2024.08</strong>: Giving a talk on Multi-domain Recommendation at <b>Huawei Noah's Ark Lab</b>.</li>
    <li><strong>2024.07</strong>: Giving a talk on LLM for Query Expansion in IR at <b>DataFun</b>.</li>
    <li><strong>2024.07</strong>: Our team AML_Lab@CityU got second place🥈 in 2 tracks, third place 🥉 in 3 tracks, and student award in 2 tracks, <b>Overall 2/508</b>, and is awarded <b>$8750</b> in <b>Amazon KDD CUP 2024</b>! A big shoutout to the awesome teamwork with my teammates Jingtong, Xiaopeng, Zixuan, and Yiyao!</li>
    <li><strong>2024.07</strong>: I'm honored to receive the KDD'24 student travel award.</li>
    <li><strong>2024.05</strong>: Our paper ERASE got accepted by <b>KDD'24 ADS Track</b>.</li>
    <li><strong>2024.05</strong>: I am honored to be selected as a virtual volunteer for NAACL'2024.</li>
    <li><strong>2024.03</strong>: I will serve as the PC member in <b>CIKM'24</b>.</li>
    <li><strong>2024.03</strong>: Our paper MILL got accepted by <b>NAACL'2024</b> (Main Conference)</li>
    <li><strong>2024.03</strong>: Passed my qualifying examination!</li>
    <li><strong>2023.12</strong>: I am honored to receive the AAAI'24 student scholarship </li>
    <li><strong>2023.12</strong>: Accepted as reviewer of ACM Transactions on Knowledge Discovery from Data (ACM TKDD) </li>
    <li><strong>2023.12</strong>: One paper accepted by <b>AAAI'24</b> </li>
    <li><strong>2023.08</strong>: I will serve as the PC member in <b>AAAI'24</b>  </li>
    <li><strong>2023.04</strong>: Our tutorial on Joint Modeling in Recommendations is accepted by <b>IJCAI'23</b> </li>
    <li><strong>2023.01</strong>: Start my PhD study at CityU. </li>
  </ul>
</div>

# 📝 Publications

## Conference and Journal Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD CUP Workshop Oral</div><img src='images/kddcup2024.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
*Second Place Overall Solution for Amazon KDD Cup 2024*

**Pengyue Jia**, Jingtong Gao, Xiaopeng Li, Zixuan Wang, Yiyao Jin, Xiangyu Zhao

[**Competition Page**](https://www.aicrowd.com/challenges/amazon-kdd-cup-2024-multi-task-online-shopping-challenge-for-llms) \| [**Workshop Page**](https://amazon-kddcup24.github.io/#) \| [**Paper**](https://openreview.net/pdf?id=OEjXPwR7aE) \| [**Certificate**](https://github.com/Jia-py/Jia-py.github.io/blob/main/docs/KDD_Cup_Certificate.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS'24</div><img src='images/G3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
*G3: An Effective and Adaptive Framework for Worldwide Geolocalization Using Large Multi-Modality Models*

**Pengyue Jia**, Yiding Liu, Xiaopeng Li, Xiangyu Zhao, Yuhao Wang, Yantong Du, Xiao Han, Xuetao Wei, Shuaiqiang Wang, Dawei Yin

[**Paper**](https://arxiv.org/abs/2405.14702) \| [**Code**](https://github.com/Applied-Machine-Learning-Lab/G3) \| [**MP16-Pro Dataset**](https://huggingface.co/datasets/Jia-py/MP16-Pro/tree/main)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD'24 ADS</div><img src='images/ERASE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[*ERASE: Benchmarking Feature Selection Methods for Deep Recommender Systems*](https://applied-machine-learning-lab.github.io/ERASE/)


**Pengyue Jia**, Yejing Wang, Zhaocheng Du, Xiangyu Zhao, Yichao Wang, Bo Chen, Wanyu Wang, Huifeng Guo, Ruiming Tang

[**Home Page**](https://applied-machine-learning-lab.github.io/ERASE/) \| [**Paper**](https://arxiv.org/abs/2403.12660) \|  [**Code**](https://github.com/Applied-Machine-Learning-Lab/ERASE) \| [**Dataset**](https://portland-my.sharepoint.com/:f:/g/personal/pyjia2-c_my_cityu_edu_hk/Eig99ijVRYZHuo6mBrJA5jIBioFU8vwATcRYeLLlYFSUAg)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/Agent4Ranking.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
*Agent4Ranking: Semantic Robust Ranking via Personalized Query Rewriting Using Multi-agent LLM*

Xiaopeng Li, Lixin Su, **Pengyue Jia**, Xiangyu Zhao, Suqi Cheng, Junfeng Wang, Dawei Yin.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI'24</div><img src='images/D3.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*D3: A Methodological Exploration of Domain Division, Modeling, and Balance in Multi-Domain Recommendations*

**Pengyue Jia**, Yichao Wang, Xiangyu Zhao, Xiaopeng Li, Huifeng Guo, Ruiming Tang.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL'24 Main Conference</div><img src='images/MILL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[*MILL: Mutual Verification with Large Language Models for Zero-Shot Query Expansion*](https://applied-machine-learning-lab.github.io/MILL/)

**Pengyue Jia**, Yiding Liu, Xiangyu Zhao, Xiaopeng Li, Changying Hao, Shuaiqiang Wang, Dawei Yin.

[**Home Page**](https://applied-machine-learning-lab.github.io/MILL/) \| [**Paper**](https://arxiv.org/abs/2310.19056) \|  [**Code**](https://github.com/Applied-Machine-Learning-Lab/MILL) \| [**Dataset**](https://ir-datasets.com/index.html)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Cybernetics and Systems</div><img src='images/FGC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[*Fine-Grained Population Mobility Data-Based Community-Level COVID-19 Prediction Model*](https://www.tandfonline.com/doi/full/10.1080/01969722.2022.2103614)

 **Pengyue Jia**, Ling Chen, Dandan Lyu.

</div>
</div>

*King William Island*, **Digital Journal of Global Change Data Repository, 2020.**

**Pengyue Jia**, Jihan Wang, Feng Zhang, Chuang Liu, Ruixiang Shi. [**Link**](http://www.geodoi.ac.cn/WebEn/doi.aspx?Id=1454)

## Tutorials

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI'2023</div><img src='images/IJCAI23_joint_modeling.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Joint Modeling in Recommendations: Foundations and Frontiers](https://zhaoxyai.github.io/paper/jointmodeling.pdf)

Xiangyu Zhao, Yichao Wang, Bo Chen, **Pengyue Jia**, Yuhao Wang, Jingtong Gao, Huifeng Guo, Ruiming Tang

</div>
</div>

# 🎖 Honors and Awards

- *2024.10* **NeurIPS 2024 Scholar Award**, Granted by NeurIPS 2024
- *2024.08* **Outstanding Academic Performance Award (OAPA)**, Granted by CityUHK
- *2024.07* **Second place🥈 in 2 tracks, third place🥉 in 3 tracks, student awards in 2 tracks in Amazon KDD CUP 2024**, Overall **2/508** teams, Awarded $8750, Granted by Amazon [[link](https://discourse.aicrowd.com/t/announcing-the-winners-of-amazon-kdd-cup-2024/10758)] \| [[certificate](https://github.com/Jia-py/Jia-py.github.io/blob/main/docs/KDD_Cup_Certificate.pdf)]
- *2024.07* **KDD24 student travel award**, Granted by KDD
- *2023.12* **AAAI24 student scholarship**, Granted by AAAI
- *2020.12* **Academic Excellence Award**, Granted by **Zhejiang University**
- *2020.06* **Second Place🥈 in LA COVID-19 Computational Challenge**, Granted by **RMDS & The Government of LA**

# 📖 Educations
- *2023.01 - now*, PhD candidate in Data Science, AML lab, City University of Hong Kong
- *2021.09 - 2022.12*, MSc in Computer Science, The University of Hong Kong
- *2017.09 - 2021.06*, BSc in Geographic Information Science, Zhejiang University

# 💬 Invited Talks

- *2024.08*, Huawei Noah's Ark Lab, Multi-domain Recommendation
- *2024.07*, [DataFun Open Class](https://www.datafuntalk.com/detail/l_669a1a84e4b0d84dab0558ab/4), LLM for Query Expansion in IR
- *2020.11*, [IM Data 2020](https://www.rmdslab.com/im-data-2020-schedule/), Solution on LA COVID-19 Computational Challenge

<span class='anchor' id='-internships'></span>

# 💻 Internships & Exchange

- *2023.06 - now*, Research Intern, Baidu Search Science Team
- *2023.02 - now*, Research Intern, Huawei Noah's Ark Lab
- *2022.06 - 2022.12*, Ad Recommendation Algorithm Intern, Meituan DaoDian Business Group, Shanghai, China.
- *2020.10 - 2021.01*, Data Analysis Intern, Zhejiang Lab, Hangzhou, China.
- 2019.07 - 2019.08, Summer Session Student, Department of Geography & Geographic Information Science, University of Illinois Urbana-Champaign, USA.
- 2018.07 - 2018.08, Summer Session Student, Shizuoka University, Japan.



<span class='anchor' id='-services'></span>

# ✏️ Services

## Reviewer

* 2023: KDD, Recsys, Nips
* 2024: KDD, ACM TKDD, CIKM
* 2025: KDD, BigData

## Volunteer

* 2024: AAAI, NAACL, KDD [[certificate](https://github.com/Jia-py/Jia-py.github.io/blob/main/docs/KDD2024_Volunteer_Certificate.pdf)]

<span class='anchor' id='-teaching'></span>

# 🏫 Teaching

- **2024.09 - 2024.12**, Teaching Assistant, SDSC 5001 Statistical Machine Learning I.
- **2024.01 - 2024.06**, Teaching Assistant, SDSC 6001 Statistical Machine Learning II.
- **2023.09 - 2023.12**, Teaching Assistant, SDSC 5001 Statistical Machine Learning I.