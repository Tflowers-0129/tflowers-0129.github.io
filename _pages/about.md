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

I'm a master's student from the [Intelligent Vision Information Processing Laboratory (IVIPC)](ivipc.uestc.edu.cn) at the [University of Electronic Science and Technology of China (UESTC)](https://www.uestc.edu.cn/). During my master's degree, I was supervised by [Assoc. Prof. Linfeng Xu](https://scholar.google.com/citations?hl=en&user=ACxzcW8AAAAJ) and [Prof. Hongliang Li](https://scholar.google.com/citations?hl=en&user=O9-QDwEAAAAJ). I expect to obtain my master's degree in June 2025.

My research interests lie primarily in **deep learning**, **continual learning**, and **multimodal learning**. I’m also deeply interested in **few-shot learning** and **self-supervised learning**. My research has been recognized with publications in prestigious journals and conferences such as TMM, Sensors Journal, and ICASSP.


# 🔥 News
- *2024.10*: 🎉🎉 One paper is accepted in IEEE TMM.
- *2024.04*: &nbsp;🎉🎉 One paper is published in ICASSP 2024. 
- *2024.03*: &nbsp;🎉🎉 One paper is published in the IEEE Sensors Journal. 
- *2023.07*: &nbsp;🎉🎉 One paper is published in the IEEE TMM. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMM</div><img src='images/TMM-2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Distribution-Level Memory Recall for Continual Learning: Preserving Knowledge and Avoiding Confusion](https://arxiv.org/abs/2408.02695) (preprint)

**Shaoxu Cheng**, Kanglei Geng, Chiyuan He, Zihuan Qiu, Linfeng Xu$ ^{\ast}$, Heqian Qiu, Lanxiao Wang, Qingbo Wu, Fanman Meng, Hongliang Li

- DMR method we proposed is the first to fit the distribution of representations in the feature space from the perspective of maintaining the old knowledge distribution and thereby maintaining the classification boundaries within the old task. We also propose an optimization plan for the fitted storage burden, which can ultimately maintain realistic classification boundaries with almost no increase in burden.

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024</div><img src='images/icassp-2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Vision-Sensor Attention Based Continual Multimodal Egocentric Activity Recognition](https://ieeexplore.ieee.org/document/10446924)

**Shaoxu Cheng**, Chiyuan He, Kailong Chen, Linfeng Xu, Hongliang Li, Fanman Meng, Qingbo Wu

- We propose the AID method. The core idea of the AID is to introduce the Vision-Sensor Attention Module (VSAM) to enhance the time and frequency dimensions information of sensor modality that is in a disadvantaged position.

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Sensors Journal</div><img src='images/sensors-2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Continual Egocentric Activity Recognition with Foreseeable-Generalized Visual-IMU Representations](https://ieeexplore.ieee.org/document/10462907)

Chiyuan He, **Shaoxu Cheng** (equal contribution), Zihuan Qiu, Linfeng Xu, Fanman Meng, Qingbo Wu, Hongliang Li

- We propose a motivational optimization scheme to address the limited generalization caused by the modal imbalance, enabling foreseeable generalization in a visual–IMU multimodal network.


</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMM</div><img src='images/TMM-2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Continual Egocentric Activity Recognition: A Multi-modal Egocentric Activity Dataset for Continual Learning](https://ieeexplore.ieee.org/document/10184468)

Linfeng Xu, Qingbo Wu, Lili Pan, Fanman Meng, Hongliang Li, Chiyuan He, Hanxin Wang, **Shaoxu Cheng** (third student author), Yu Dai

- Our dataset is collected by our self-developed glasses integrated with a first-person camera and inertial measurement unit (IMU).
- Our proposed UESTC-MMEA-CL contains 32 daily activity classes with a duration of over 30 hours in total. Each sample clip consists of video, acceleration, and gyroscope signals which can provide rich object and motion attributes.

</div>

</div>

- [一种基于差异性特征蒸馏的多模态连续学习方法](https://bhxb.buaa.edu.cn/bhzk/en/article/doi/10.13700/j.bh.1001-5965.2023.0369)，贺驰原，**程少旭**，许林峰，孟凡满，吴庆波，北京航空航天大学学报,1-9.https://doi.org/10.13700/j.bh.1001-5965.2023.0369.

# 🎓 Project and Research Experience

- **Research on Multimodal Continuous Learning Methods Based on Vision-Sensor Attention Mechanisms** (National Key R&D Program of China—AI 2030 Major Project)

  Principal Investigator

  - **Problem Overview**: Multimodal data often suffer from insuﬀicient fusion, data and network imbalance, and task interference in continuous learning.
  - **Solution**: Proposed a vision-sensor multimodal attention mechanism to address modality imbalance by extracting sensor modality information in time and frequency domains, and reduced task interference using mixup-like techniques.

- **Research on Continuous Learning Methods for Few-Shot Image Generation Based on Diffusion Models** (National Key R&D Program of China—AI 2030 Major Project)

  ​	Principal Investigator

  - **Problem Overview**: Few-shot learning is limited by insuﬀicient sample quantities, particularly impacting continuous learning.
  - **Solution**: (1) Data cleaning and construction of a few-shot behavior recognition dataset; (2) Fine-tuning diffusion models to generate image samples to mitigate data insuﬀiciency.

- **Research on Continuous Behavior Recognition Methods Enhancing Generalization Through Multimodal Representations** (National Key R&D Program of China—AI 2030 Major Project)

  Principal Investigator

  - **Problem Overview**: An imbalance in multimodal data leads to poor generalization of embedded space representations, insuﬀicient for prototype-based incremental learning methods.
  - **Solution**: Mitigated imbalance by masking dominant modality representations to enhance weaker modalities’ generalization, facilitating subsequent prototype-based incremental learning.

- **Research on Continuous Learning Methods Based on Embedded Space Distribution Replay Strategies** (National Key R&D Program of China—AI 2030 Major Project)

  Principal Investigator

  - **Problem Overview**: Prototype-based methods in continuous learning fail to fully reproduce old task knowledge and original classification boundaries in embedded space.
  - **Solution**: Used GMM unsupervised clustering to fit old task knowledge distribution and classification boundaries, fully reproducing them during new tasks to preserve old knowledge in feature space distribution.

- **Smart Classroom Student Evaluation System Based on Object Detection Technology** 

  Team Leader

  - **Problem Overview**: Monitor classroom scenes to detect student behaviors and evaluate classroom atmosphere.
  - **Solution**: Generated teacher image captions using the InstructBlip vision-language model, then used suitable deep neural networks for object detection and classification to assess classroom quality. Implemented the entire system using C++, Qt, etc.

# 💡 Invention Patent

- A Multimodal Continual Behavior Recognition Method Based on Vision-Sensor Attention Mechanism (*First Student Inventor*).

- A Method for Continual Behavior Recognition Based on Predictable Multimodal Generalized Knowledge Representations (*Second Student Inventor*).

- A Continual Learning Capability Evaluation Index for Multi-Source Heterogeneous Data Based on Old and New Task Confusion Rates (*First Student Inventor*).


# 🎖 Honors and Awards

- *2024.04*: Won Second Prize in Huawei Software Elite Challenge Southwest Region.
- *2023.09*: Third Prize Academic Scholarship.
- *2022.09*: Third Prize Graduate Freshman Scholarship. 
- *2022.06*: Won Outstanding Student Leader of Southwest Jiaotong University and School-Level Outstanding Graduate.
- *2021.09*: Third Prize Comprehensive Scholarship.
- *2020.09*: Second Prize Comprehensive Scholarship.
- *2020.05* Won the First Prize in the 17th May Mathematical Modeling Competition National Award.

# 📖 Educations
- *2022.09 - now*, MSc Information and Communication Engineering in University of Electronic Science and Technology of China, GPA: 3.74/4.0. 
- *2018.09 - 2022.06*, BEng Electronic and Information Engineering in Southwest Jiaotong University, AVG: 87.16/100 (top 20%). 

