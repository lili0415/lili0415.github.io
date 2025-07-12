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

# About Me
<span class='anchor' id='about-me'></span>

Hi! I am Li (Shawn) Li, a PhD student at Thomas Lord Department of Computer Science, **University of Southern California**, supervised by Prof. [Yue Zhao](https://scholar.google.com/citations?user=zoGDYsoAAAAJ&hl=en).

Before my PhD study in the USA, I spent wonderful years in Singapore and cooperated with great professors. I served as a research associate at **Nanyang Technological University**, working with Prof. [Aixin Sun](https://scholar.google.com/citations?user=wyKGVKUAAAAJ&hl=zh-CN). I earned my Master's degree from **National University of Singapore** in 2024, where I contributed as a research intern under the guidance of Prof. [Tat-Seng Chua](https://scholar.google.com/citations?user=Z9DWCBEAAAAJ&hl=zh-CN&oi=ao) and Prof. [Roger Zimmermann](https://scholar.google.com/citations?user=IDREwXEAAAAJ&hl=zh-CN&oi=ao). Prior to that, I successfully completed my Bachelor's degree at **TongJi University**, China in 2022.
My research interests are centered around multimodal learning, Out-of-Distribution detection, and information retrieval.

# News
<span class='anchor' id='news'></span>

**2025.06 -** Our paper "JailDAM: Jailbreak Detection with Adaptive Memory for Vision-Language Model" is accepted by COLM 2025; see our [Preprint](https://arxiv.org/pdf/2504.03770).

**2025.06 -** Our paper "Secure On-Device Video OOD Detection Without Backpropagation" is accepted by ICCV 2025.

**2025.05 -** We have a new paper benchmarking personalized conversation; see our [Preprint](https://arxiv.org/pdf/2505.14106).

**2025.05 -** Our paper "AD-LLM: Benchmarking Large Language Models for Anomaly Detection" is accepted as Findings by the ACL 2025; see our [Preprint](https://arxiv.org/abs/2412.11142).

**2025.05 -** I will join Adobe as a Research Scientist Intern this summer 2025. Hope to have a great summer life in San Jose!

**2025.04 -** We have a new paper using premise verification to prevent LLM from hallucinations; see our [Preprint](https://arxiv.org/pdf/2504.06438).

**2025.04 -** We have a new paper on VLM jailbreak detection; see our [Preprint](https://arxiv.org/pdf/2504.03770).

**2025.03 -** We have a new paper aiming for secured on-device OOD detetion; see our [Preprint](https://arxiv.org/pdf/2503.06166).

**2025.03 -** We have a new paper tackling VLM hallucination from a causal prospective; see our [Preprint](https://arxiv.org/pdf/2503.06169).

**2025.03 -** We have a new paper for decoupled multimodal representation learning; see our [Preprint](https://arxiv.org/pdf/2503.11892).

**2025.02 -** Our paper "DPU: Dynamic Prototype Updating for Multimodal Out-of-Distribution Detection" is accepted as a Highlight Paper by the CVPR 2025.

**2025.01 -** Our paper "Generalized Video Moment Retrieval" is accepted by the ICLR 2025. 

**2025.01 -** Our paper "PyOD 2: A Python Library for Outlier Detection with LLM-powered Model Selection" is accepted by the WebConf 2025 Demo Track.

**2024.11 -** Our paper "Backpropagation-Free Multi-modal On-Device Model Adaptation via Cloud-Device Collaboration" is accepted by ACM Transactions on Multimedia Computing Communications and Applications.

**2024.10 -** Our paper "Towards Complex-query Referring Image Segmentation: A Novel Benchmark" is accepted by ACM Transactions on Multimedia Computing Communications and Applications.

**2024.10 -** We have a new paper on concept-based zero-shot OOD detection; see our [Preprint](https://arxiv.org/pdf/2411.13578).

**2024.08.22 -** Start my PhD journey at USC.

**2024.07.31 -** My last day at S-Lab NTU and in Singapore.

**2024.7 -** We have a new paper on ranked video moment retrieval; see our [Preprint](https://arxiv.org/pdf/2407.06597).

**2024.02 -** Start to working as a research associate at S-Lab NTU.


# Work Experiences
<span class='anchor' id='work-experiences'></span>
<b>Research Scientist Intern, Adobe. </b>

<div style="text-align: right;">
<b>05/2025-present</b>
<br/>
San Jose, CA
</div>

---

<span class='anchor' id='work-experiences'></span>
<b>Research Assistant, FORTIS, USC. </b>

<div style="text-align: right;">
<b>08/2024-present</b>
<br/>
Prof. Yue Zhao
</div>



<!-- Mainly focus on multimodal understanding and information retrieval. -->

---
<b>Research Associate, S-Lab, NTU. </b>

<div style="text-align: right;">
<b>02/2024-08/2024</b>
<br/>
Prof. Aixin Sun
</div>



<!-- Mainly focus on multimodal understanding and information retrieval. -->

---


<b>Research Intern, NExT++, NUS.  </b>
         
<div style="text-align: right;">
<b>06/2022-02/2024</b>
<br/>
Prof. Tat-Seng Chua
</div>



<!-- Mainly focus on multimodal fusion and understanding. -->

---

<!-- <b>Research Intern, School of Software Engineering, TongJi University.</b>

<div style="text-align: right;">
<b>08/2020-06/2022</b>
<br/>
Prof. Yan Liu
</div> -->



<!-- Mainly focus on neural code search and neural code completion. -->
         


# Selected Publications
<span class='anchor' id='publications'></span>
please refer to [google scholar](https://scholar.google.com/citations?user=r4kIL4cAAAAJ&hl=zh-CN) page to check all my publications. (* Equal Contribution)

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2505.14106" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">A Personalized Conversational Benchmark: Towards Simulating Personalized Conversations</span> 
      <br><b>Li Li</b>, Peilin Cai, Ryan A. Rossi, Franck Dernoncourt, Branislav Kveton, Junda Wu, Tong Yu, Linxin Song, Tiankai Yang, Yuehan Qin, Nesreen K. Ahmed, Samyadeep Basu, Subhojyoti Mukherjee, Ruiyi Zhang, Zhengmian Hu, Bo Ni, Yuxiao Zhou, Zichao Wang, Yue Huang, Yu Wang, Xiangliang Zhang, Philip S. Yu, Xiyang Hu, Yue Zhao
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>


<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2504.06438" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Don’t Let It Hallucinate: Premise Verification via Retrieval-Augmented Logical Reasoning</span> 
      <br>Yuehan Qin, <b>Li Li</b>, Yi Nian, Xinyan Velocity Yu, Yue Zhao, Xuezhe Ma
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

-->




<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2503.06169" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Treble Counterfactual VLMs: A Causal Approach to Hallucination</span> 
      <br><b>Li Li</b>, Jiashu Qu, Yuxiao Zhou, Yuehan Qin, Tiankai Yang, Yue Zhao
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2504.03770" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">JailDAM: Jailbreak Detection with Adaptive Memory for Vision-Language Model</span> 
      <br>Yi Nian, Shenzhe Zhu, Yuehan Qin, <b>Li Li</b>, Ziyi Wang, Chaowei Xiao, Yue Zhao
    <br>COLM 2025&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>  -->

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2503.06166" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Secure On-Device Video OOD Detection Without Backpropagation</span> 
      <br><b>Li Li</b>, Peilin Cai, Yuxiao Zhou, Zhiyu Ni, Renjie Liang, You Qin, Yi Nian, Zhengzhong Tu, Xiyang Hu, Yue Zhao
    <br>ICCV 2025&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2503.11892" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">DecAlign: Hierarchical Cross-Modal Alignment for Decoupled Multimodal Representation Learning</span> 
      <br>Chengxuan Qian, Shuo Xing, <b>Li Li</b>, Yue Zhao, Zhengzhong Tu
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>


<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2411.13578" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">COOD: Concept-based Zero-shot OOD Detection</span> 
      <br>Zhendong Liu*, Yi Nian*, Henry Peng Zou, <b>Li Li</b>, Xiyang Hu, Yue Zhao
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2407.06597" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">TVR-Ranking: A Dataset for Ranked Video Moment Retrieval with Imprecise Queries</span> 
      <br>Renjie Liang, <b>Li Li</b>, Chongzhi Zhang, Jing Wang, Xizhou Zhu, Aixin Sun
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->


<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2308.09412.pdf" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Causal SAR ATR with Limited Data via Dual Invariance</span> 
      <br>Chenwei Wang, You Qin, <b>Li Li</b>, Siyi Luo, Yulin Huang, Jifang Pei, Yin Zhang, Jianyu Yang
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/pdf/2308.03725.pdf" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Efficient Temporal Sentence Grounding in Videos with Multi-Teacher Knowledge Distillation</span> 
      <br>Renjie Liang, Yiming Yang, Hui Lu, <b>Li Li</b>
    <br>Preprint&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://arxiv.org/abs/2412.11142" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">AD-LLM: Benchmarking Large Language Models for Anomaly Detection</span> 
      <br>Tiankai Yang*, Yi Nian*, <b>Li Li</b>, Ruiyao Xu, Yuangang Li, Jiaqi Li, Zhuo Xiao, Xiyang Hu, Ryan Rossi, Kaize Ding, Xia Hu, Yue Zhao
    <br>ACL 2025 Findings&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Li_DPU_Dynamic_Prototype_Updating_for_Multimodal_Out-of-Distribution_Detection_CVPR_2025_paper.pdf" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">DPU: Dynamic Prototype Updating for Multimodal Out-of-Distribution Detection</span> 
      <br><b>Li Li</b>, Huixian Gong, Hao Dong, Tiankai Yang, Zhengzhong Tu, Yue Zhao
    <br>CVPR 2025 <span style="color: red">(Highlight)</span>&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://openreview.net/forum?id=qdOIkeZ5e4&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2025%2FConference%2FAuthors%23your-submissions)" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Generalized Video Moment Retrieval</span> 
      <br>You Qin, Qilong Wu, Yicong Li, Wei Ji, <b>Li Li</b>, Pengcheng Cai, Lina Wei, Roger Zimmermann 
    <br>ICLR 2025&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://www.arxiv.org/pdf/2412.12154" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">PyOD 2: A Python Library for Outlier Detection with LLM-powered Model Selection</span> 
      <br>Sihan Chen*, Zhuangzhuang Qian*, Wingchun Siu*, Xingcan Hu, Jiaqi Li, <b>Shawn Li</b>, Yuehan Qin, Tiankai Yang, Zhuo Xiao, Wanghao Ye, Yichi Zhang, Yushun Dong, Yue Zhao
    <br>WebConf 2025, Demo Paper&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://dl.acm.org/doi/abs/10.1145/3706422" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Backpropagation-Free Multi-modal On-Device Model Adaptation via Cloud-Device Collaboration</span> 
      <br><b>Li Li</b>*， Wei Ji*, Zheqi Lv*, Wenqiao Zhang, Mengze Li, Zhen Wan, Wenqiang Lei, Roger Zimmermann
    <br>ACM Transactions on Multimedia Computing Communications and Applications&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://dl.acm.org/doi/abs/10.1145/3701733" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Towards Complex-query Referring Image Segmentation: A Novel Benchmark</span> 
      <br>Wei Ji, <b>Li Li</b>, Hao Fei, Xiangyan Liu, Xun Yang, Juncheng Li, Roger Zimmermann
    <br>ACM Transactions on Multimedia Computing Communications and Applications &nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://ojs.aaai.org/index.php/AAAI/article/download/28098/28201" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Panoptic Scene Graph Generation with Semantics-prototype Learning</span> 
      <br><b>Li Li</b>, Wei Ji, Yiming Wu, Mengze Li, You Qin, Lina Wei, Roger Zimmermann
    <br>AAAI 2024&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10447193" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Domain-wise Invariant Learning for Panoptic Scene Graph Generation</span> 
      <br><b>Li Li</b>, You Qin, Wei Ji, Yuxiao Zhou, Roger Zimmermann
    <br>ICASSP 2024&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://dl.acm.org/doi/pdf/10.1145/3581783.3611847" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">Biased-Predicate Annotation Identification via Unbiased Visual Predicate Representation</span> 
      <br><b>Li Li</b>*, Chenwei Wang*, You Qin, Wei Ji, Renjie Liang
    <br>ACM MM 2023&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>

<!-- <table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/407106f4b56040b2e8dcad75a6e461e5-Paper-Conference.pdf" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">VPGTrans: Transfer Visual Prompt Generator across LLMs</span> 
      <br>Ao Zhang, Hao Fei, Yuan Yao, Wei Ji, <b>Li Li</b>, Zhiyuan Liu, Tat-Seng Chua
    <br>NeurIPS 2023&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table> -->

<table style="MARGIN-BOTTOM: 10px; FONT-SIZE: 13px; BORDER-COLLAPSE: collapse; TEXT-ALIGN: left; WIDTH: 98%; BACKGROUND-COLOR: #f6fbfe">
  <tbody>
  <tr>
    <td class="left" style="FONT-SIZE: 10px; TEXT-ALIGN: center; WIDTH: 60px; BACKGROUND-COLOR: #e2eff9"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9793971" target="_blank"><img src="./images/pdf.png" width="100" height="100"></a></td>
    <td><span class="title" style="FONT-WEIGHT: bold">On the Importance of Building High-quality Training Datasets for Neural Code Search</span> 
      <br>Zhensu Sun, <b>Li Li</b>, Yan Liu, Xiaoning Du, Li Li
    <br>ICSE 2022, <span style="color: red">Nominated for ACM SIGSOFT Distinguished Paper Award</span>&nbsp;&nbsp; 
  </td> 
  </tr>
 </tbody>
</table>


# Honors and Awards
<span class='anchor' id='honors-and-awards'></span>
Capital One Fellowship 2025.

ICSE 2022 Distinguished Paper Award Nomination.

AAAI 2024 Student Scholarship.

# Services
<span class='anchor' id='services'></span>
Program Committee Member of ICML (2025).

Program Committee Member of ICLR (2025).

Program Committee Member of ICCV (2025).

Program Committee Member of COLM (2025).

Program Committee Member of ICASSP (2025).

Program Committee Member of KDD (2025).

Program Committee Member of IJCNN (2025).

Program Committee Member of ACM MM (2024).

Program Committee Member of ECCV (2024).

Program Committee Member of ACL ARR (2024, 2025).

Program Committee Member of ACM MM MMGR Workshop (2023, 2024).

Program Committee Member of CVPR TMM-OpenWorld Workshop (2025).

Journal Reviewer for IEEE Transactions on Neural Networks and Learning Systems.

Journal Reviewer for IEEE Transactions on Multimedia.

Journal Reviewer for IEEE Transactions on Circuits and Systems for Video Technology.

Student Volunteer at ACM Web Conference (2024).

# Educations
<span class='anchor' id='educations'></span>
  08/2024 - present

  Doctor of Philosophy in Computer Science

  University of Southern California, USA


  ---


  2022.08 - 2024.02

  Master of Science in Industry 4.0

  National University of Singapore, Singapore


  ---
  
  2018.08 - 2022.06

  Bachelor of Engineering in Software Engineering

  TongJi University, China

<!-- <script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=MtgOD5bYVhrJl1tzX74CbRhUUslEFdbq-StiPxMz5Ts&cl=ffffff&w=a"></script> -->




<!-- <script>
  var _paq = window._paq = window._paq || [];
  /* tracker methods like "setCustomDimension" should be called before "trackPageView" */
  _paq.push(['trackPageView']);
  _paq.push(['enableLinkTracking']);
  (function() {
    var u="https://githublili.matomo.cloud/";
    _paq.push(['setTrackerUrl', u+'matomo.php']);
    _paq.push(['setSiteId', '1']);
    var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
    g.async=true; g.src='https://cdn.matomo.cloud/githublili.matomo.cloud/matomo.js'; s.parentNode.insertBefore(g,s);
  })();
</script> -->