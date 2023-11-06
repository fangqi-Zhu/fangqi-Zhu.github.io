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

I am currently a third-year M.Eng. student at [Harbin Institute of Technology, Shenzhen (HITSZ)](https://www.hitsz.edu.cn/index.html) <img src='images/logo_HITSZ.jpg' style='width: 1.1em;'> ([learn more about UCAS](https://en.wikipedia.org/wiki/Harbin_Institute_of_Technology,_Shenzhen)).

My research interests lie in the general area of machine learning and deep learning, and I have some research experience in the field of natural language processing.
The long-term goal of my research is to develop a machine that can perceive, plan, and act in real-world scenes like humans.


> 📢📢📢 <font color=red>I am looking for a Ph.D. position (2024 Fall).</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to [contact me](mailto:zhufangqi.hitsz@gmail.com). 😊
<!-- 
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.10*: One paper is accepted by EMNLP 2023!🎉
- *2023.05*: One paper is accepted by ACL Findings 2023! 🎉
- *2022.11*: One paper is accepted by AAAI 2023! 🎉

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning to Describe for Predicting Zero-shot Drug-Drug Interactions](https://openreview.net/pdf?id=3dNeNpmyiO)

**Fangqi Zhu**, Yongqi Zhang, Lei Chen, Bing Qin, Ruifeng Xu

**<font color=red>EMNLP 2023 </font>** \| [**Code**](https://github.com/zhufq00/DDIs-Prediction) 
- Problem: We propose a novel problem setup that leverages textual descriptions for DDI prediction,especially on new drugs as a zero-shot setting.
- Method: We carefully design an LM-based DDI predictor with an RL-based information selector that accurately predicts DDIs with short and relevant descriptions.
- Experiments: We achieve better performance in zero-shot, and few-shot DDI predictions with
the proposed method. In addition, we show that the selected texts by the information selector are semantically relevant to the target prediction
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Diffusion Model for Event Skeleton Generation](https://openreview.net/pdf?id=3dNeNpmyiO)

**Fangqi Zhu**, Lin Zhang, Jun Gao, Bing Qin, Ruifeng Xu, Haiqin Yang

**<font color=red>ACL Findings 2023 </font>** \| [**Paper**](https://aclanthology.org/2023.findings-acl.800/)  [**Code**](https://github.com/zhufq00/EventSkeletonGeneration) 
- We propose a novel Diffusion Event Graph model (DEGM) for event skeleton generation, in which a denoising training stage guarantees the model’s robustness and the schema generation process fulfills error correction via iterative refinement on the latent representation.
- We are the first to tackle event skeleton generation via diffusion models, where we convert an event graph from discrete nodes to latent variables in a continuous space and train the model parameters by optimizing the event sequence reconstruction and graph structure reconstruction simultaneously.
- Experimental results on the event skeleton generation task demonstrate that our approach achieves better results than state-of-the-art baselines.
</div>
</div>

[A Generative Approach for Script Event Prediction via Contrastive Fine-Tuning](https://ojs.aaai.org/index.php/AAAI/article/view/26645)

**Fangqi Zhu**, Lin Zhang, Jun Gao, Bing Qin, Ruifeng Xu, Haiqin Yang

**<font color=red>AAAI 2023 (Oral Presentation)  </font>** \| [**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/26645)  [**Code**](https://github.com/zhufq00/mcnc) 
- We propose a novel generative approach for this task, in which a pretrained language model is fne-tuned with an event-centric pretraining objective and predicts the next event within a generative paradigm.
- We introduce a novel event-level blank inflling strategy as the learning objective to inject event-level knowledge into the pretrained language model and design a likelihood-based contrastive loss to force the model to learn to distinguish between correct and wrong event candidates.
- Experimental results on the multi-choice narrative cloze (MCNC) task demonstrate that our approach achieves better results than other state-of-the-art baselines.
</div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.