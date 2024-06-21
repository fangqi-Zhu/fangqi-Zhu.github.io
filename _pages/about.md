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

<!-- Hi, I’m Fangqi Zhu. I',  pursue my Ph.D. in the Department of Computer Science and Engineering (CSE) at the Hong Kong University of Science and Technology (HKUST, 香港科技大学), supervised by Prof. Song Guo in PEILab.

I am currently a third-year M.Eng. student at [Harbin Institute of Technology, Shenzhen (HITSZ)](https://www.hitsz.edu.cn/index.html). And I will join The Hong Kong University of Science and Technology as a PhD student in 2024 fall in the Department of [Computer Science and Engineering (CSE)] (https://cse.hkust.edu.hk/). I am fortunate to be advised by supervised by Prof. [Song Guo](https://cse.hkust.edu.hk/admin/people/faculty/profile/songguo) in [PEILab] (https://peilab.netlify.app/). -->

I am an incoming Fall 2024 PhD student in the [Department of Computer Science and Engineering, Hong Kong University of Science and Technology](https://cse.hkust.edu.hk/) (CSE, HKUST). I am fortunate to be supervised by [Prof. Song Guo](https://cse.hkust.edu.hk/admin/people/faculty/profile/songguo) at [PEILab](https://peilab.netlify.app/). I received my Master's degree in 2024 from the [Harbin Institute of Technology, Shenzhen](http://cs.hitsz.edu.cn/) (HITSZ), supervised by [Prof. Bin Qin](https://homepage.hit.edu.cn/qinbing) and [Prof. Ruifeng Xu](https://faculty.hitsz.edu.cn/xuruifeng). I received my Bachelor's degree in 2017 from [Wuhan University](https://cs.whu.edu.cn/).

My research interests focus on scaling up robot learning. Previously, I gained some experience in NLP. The long-term goal of my research is to develop a machine that can perceive, plan, and act in the real world like humans.

I am currently developing a generative world model for robot learning, which will enable automatic training and evaluation in a virtual environment.



<!-- interested in [MineDojo](https://minedojo.org/) (Minecraft simulator), [CALVIN](https://github.com/mees/calvin)(Robot arm simulator), and [Habitat 3.0](https://aihabitat.org/habitat3/) (Home simulator), and will base my research on this. If you are interested in collaborating, please contact me. I'm open to any form of cooperation. -->

<!-- > 📢📢📢 <font color=red>I am looking for a Ph.D. position (2024 Fall).</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to [contact me](mailto:zhufangqi.hitsz@gmail.com). 😊 -->
<!-- 
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.06*: Our paper, [IRASim](https://gen-irasim.github.io/), which explores generative robot world models, has been released! 🎉 Everything is open source!
- *2023.10*: One paper is accepted by EMNLP 2023!🎉
- *2023.05*: One paper is accepted by ACL Findings 2023! 🎉
- *2022.11*: One paper is accepted by AAAI 2023! 🎉

# Preprint
<div class='paper-box'><img src='images/IRASim.png' alt="sym" width="100%">

[IRASim: Learning Interactive Real-Robot Action Simulators](https://arxiv.org/pdf/2406.14540)

**Fangqi Zhu**, Hongtao Wu, Song Guo, Yuxiao Liu, Chilam Cheang, Tao Kong

[[**Paper**]](https://arxiv.org/pdf/2406.14540) [[**Code**]](https://github.com/bytedance/IRASim) [[**Project Website**]](https://gen-irasim.github.io/) 
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/EMNLP2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning to Describe for Predicting Zero-shot Drug-Drug Interactions](https://aclanthology.org/2023.emnlp-main.918/)

**Fangqi Zhu**, Yongqi Zhang, Lei Chen, Bing Qin, Ruifeng Xu

**<font color=red>EMNLP 2023 (Oral Presentation) </font>** \| [[**Paper**]](https://aclanthology.org/2023.emnlp-main.918/) [[**Code**]](https://github.com/zhufq00/DDIs-Prediction) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL Findings 2023</div><img src='images/ACL2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Diffusion Model for Event Skeleton Generation](https://aclanthology.org/2023.findings-acl.800/)

**Fangqi Zhu**, Lin Zhang, Jun Gao, Bing Qin, Ruifeng Xu, Haiqin Yang

**<font color=red>ACL Findings 2023 (Poster) </font>** \| [[**Paper**]](https://aclanthology.org/2023.findings-acl.800/)  [[**Code**]](https://github.com/zhufq00/EventSkeletonGeneration) [[**Poster**]](resources/DEGM_Poster.pdf) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/AAAI2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Generative Approach for Script Event Prediction via Contrastive Fine-Tuning](https://ojs.aaai.org/index.php/AAAI/article/view/26645)

**Fangqi Zhu**, Jun Gao, Changlong Yu, Wei Wang, Chen Xu, Xin Mu, Min Yang, Ruifeng Xu

**<font color=red>AAAI 2023 (Oral Presentation)  </font>** \| [[**Paper**]](https://ojs.aaai.org/index.php/AAAI/article/view/26645)  [[**Code**]](https://github.com/zhufq00/mcnc) [[**Poster**]](resources/SEP_Poster.pdf) 
</div>
</div>

# 🎖 Honors and Awards
- *2021.09* First-class Scholarship of Harbin Institute of Technology, Shenzhen
- *2022.09* Second-class Scholarship of Harbin Institute of Technology, Shenzhen

# 📖 Educations
- *2021.09 - 2024.1 (expected)*, Master of Engineering in Computer Science and Technology, Department of Computer Science and Technology, Harbin Institute of Technology, Shenzhen (HITSZ)
- *2017.09 - 2021.06*, Bachelor of Engineering in Software Engineering, Department of Computer Science, Wuhan University (WHU)


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.03 - Present*, Research Intern, ByteDance, Robotics Research, AI Lab, Beijing, China

- *2023.04 - 2023.12*, Research Intern, 4Paradigm, Shenzhen, China

    Mentor: [Dr. Yongqi Zhang](https://yzhangee.github.io/)

- *2022.09 - 2023.03*, Research Intern, International Digital Economy Academy (IDEA), DataStory AI lab, Shenzhen, China

    Mentor: [Dr. Haiqin Yang](https://hqyang.github.io/) & [Dr.Lin Zhang](https://lin-zhang-alpha.github.io/)
