---
permalink: /
title: "Fangqi Zhu"
excerpt: "Fangqi Zhu is a PhD student at HKUST CSE working on robot learning, world models, and model-based reinforcement learning."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<main class="site-shell" id="top">
  <header class="site-nav" aria-label="Primary navigation">
    <nav class="site-nav__links">
      <a href="#about-me">About</a>
      <a href="#recent">Recent</a>
      <a href="#publications">Papers</a>
      <a href="#experience">Work</a>
      <a href="#education">Edu</a>
    </nav>
  </header>

  <section class="hero" id="about-me">
    <div class="hero__identity">
      <h1>Fangqi Zhu</h1>
      <div class="hero__actions" aria-label="Profile links">
        <a class="button button--primary" href="mailto:fangqi.zhu@connect.ust.hk">Email</a>
        <a class="button" href="https://scholar.google.com.tw/citations?hl=zh-CN&amp;user=yio0974AAAAJ" target="_blank" rel="noopener">Google Scholar</a>
      </div>
    </div>
    <div class="hero__copy">
      <p class="hero__status">HKUST CSE PhD · NVIDIA GEAR intern · 2027 industry job market</p>
      <p class="hero__intro">
        I am a second-year PhD student in the <a href="https://cse.hkust.edu.hk/" target="_blank" rel="noopener">Department of Computer Science and Engineering at HKUST</a>, advised by
        <a href="https://cse.hkust.edu.hk/admin/people/faculty/profile/songguo" target="_blank" rel="noopener">Prof. Song Guo</a> at
        <a href="https://peilab.netlify.app/" target="_blank" rel="noopener">PEILab</a>. I am broadly interested in robot learning, world models, and reinforcement learning.
      </p>
      <p class="hero__intro">
        My current research explores how robots can learn from models of the physical world, with the goal of making robot learning more scalable, data-efficient, and adaptable across tasks and environments.
      </p>
      <p class="hero__intro">
        Since May 2026, I have been a research intern at
        <a href="https://research.nvidia.com/labs/gear/" target="_blank" rel="noopener">NVIDIA GEAR</a>, working on world models for robot learning with
        <a href="https://github.com/Little-Podi" target="_blank" rel="noopener">Shenyuan Gao</a>,
        <a href="https://yukezhu.me/" target="_blank" rel="noopener">Yuke Zhu</a>, and
        <a href="https://jimfan.me/" target="_blank" rel="noopener">Jim Fan</a>. I expect to graduate in 2027 and am on the industry job market.
      </p>
    </div>
  </section>

  <section class="section recent-grid" id="recent">
    <div class="section__header">
      <p class="eyebrow">Recent</p>
      <h2>News</h2>
    </div>

    <div class="update-list">
      <article class="update-item update-item--accent">
        <span class="update-item__date">2026.05</span>
        <div>
          <h3>Started at <a href="https://research.nvidia.com/labs/gear/" target="_blank" rel="noopener">NVIDIA GEAR</a></h3>
          <p>Research internship with Shenyuan Gao, Yuke Zhu, and Jim Fan on world models for robot learning.</p>
        </div>
      </article>
      <article class="update-item">
        <span class="update-item__date">2026.05</span>
        <div>
          <h3>HALO accepted to ICML 2026</h3>
          <p>Work on embodied multimodal chain-of-thought reasoning and action generation.</p>
        </div>
      </article>
      <article class="update-item">
        <span class="update-item__date">2026.01</span>
        <div>
          <h3>WMPO accepted to ICLR 2026</h3>
          <p>World model-based policy optimization for robot learning.</p>
        </div>
      </article>
      <article class="update-item">
        <span class="update-item__date">2025.06</span>
        <div>
          <h3>IRASim accepted to ICCV 2025</h3>
          <p>Interactive real-robot action simulators for generative robot world models.</p>
        </div>
      </article>
    </div>
  </section>

  <section class="section" id="publications">
    <div class="section__header">
      <p class="eyebrow">Research</p>
      <h2>Selected publications</h2>
    </div>

    <div class="paper-list">
      <article class="paper-card paper-card--featured">
        <a class="paper-card__media" href="https://arxiv.org/abs/2602.21157" target="_blank" rel="noopener">
          <span class="paper-card__badge">ICML 2026</span>
          <img src="{{ '/images/HALO.png' | relative_url }}" alt="HALO method overview">
        </a>
        <div class="paper-card__body">
          <p class="paper-card__venue">ICML 2026</p>
          <h3><a href="https://arxiv.org/abs/2602.21157" target="_blank" rel="noopener">HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning</a></h3>
          <p class="paper-card__authors">Quanxin Shou*, <strong>Fangqi Zhu*</strong>, Shawn Chen, Puxin Yan, Zhengyang Yan, Yikun Miao, Xiaoyi Pang, Zicong Hong, Ruikai Shi, Hao Huang, Jie Zhang, Song Guo</p>
          <p class="paper-card__note">* Equal contribution.</p>
          <p>HALO combines textual reasoning, visual subgoal prediction, and action generation for embodied multimodal chain-of-thought reasoning.</p>
          <div class="paper-card__links">
            <a href="https://arxiv.org/abs/2602.21157" target="_blank" rel="noopener">Paper</a>
            <a href="https://github.com/qshou-coder/HALO" target="_blank" rel="noopener">Code</a>
          </div>
        </div>
      </article>

      <article class="paper-card">
        <a class="paper-card__media" href="https://arxiv.org/abs/2511.09515" target="_blank" rel="noopener">
          <span class="paper-card__badge">ICLR 2026</span>
          <img src="{{ '/images/WMPO.png' | relative_url }}" alt="WMPO overview">
        </a>
        <div class="paper-card__body">
          <p class="paper-card__venue">ICLR 2026</p>
          <h3><a href="https://arxiv.org/abs/2511.09515" target="_blank" rel="noopener">WMPO: World Model-based Policy Optimization for Vision-Language-Action Models</a></h3>
          <p class="paper-card__authors"><strong>Fangqi Zhu</strong>, Zhengyang Yan, Zicong Hong, Quanxin Shou, Xiao Ma, Song Guo</p>
          <p>Explores model-based policy optimization in a learned world model.</p>
          <div class="paper-card__links">
            <a href="https://arxiv.org/abs/2511.09515" target="_blank" rel="noopener">Paper</a>
            <a href="https://github.com/WM-PO/WMPO" target="_blank" rel="noopener">Code</a>
            <a href="https://wm-po.github.io/" target="_blank" rel="noopener">Project</a>
          </div>
        </div>
      </article>

      <article class="paper-card">
        <a class="paper-card__media" href="https://arxiv.org/pdf/2406.14540" target="_blank" rel="noopener">
          <span class="paper-card__badge">ICCV 2025</span>
          <img src="{{ '/images/IRASim.png' | relative_url }}" alt="IRASim overview">
        </a>
        <div class="paper-card__body">
          <p class="paper-card__venue">ICCV 2025</p>
          <h3><a href="https://arxiv.org/pdf/2406.14540" target="_blank" rel="noopener">IRASim: Learning Interactive Real-Robot Action Simulators</a></h3>
          <p class="paper-card__authors"><strong>Fangqi Zhu</strong>, Hongtao Wu, Song Guo, Yuxiao Liu, Chilam Cheang, Tao Kong</p>
          <p>Studies generative robot world models for interactive real-robot action simulation.</p>
          <div class="paper-card__links">
            <a href="https://arxiv.org/pdf/2406.14540" target="_blank" rel="noopener">Paper</a>
            <a href="https://github.com/bytedance/IRASim" target="_blank" rel="noopener">Code</a>
            <a href="https://gen-irasim.github.io/" target="_blank" rel="noopener">Project</a>
          </div>
        </div>
      </article>

      <details class="paper-archive">
        <summary>
          <span>Earlier NLP publications</span>
          <small>EMNLP 2023, ACL Findings 2023, AAAI 2023</small>
        </summary>
        <div class="paper-archive__content">
          <article class="paper-card paper-card--compact">
            <a class="paper-card__media" href="https://aclanthology.org/2023.emnlp-main.918/" target="_blank" rel="noopener">
              <span class="paper-card__badge">EMNLP 2023</span>
              <img src="{{ '/images/EMNLP2023.png' | relative_url }}" alt="DDI paper overview">
            </a>
            <div class="paper-card__body">
              <p class="paper-card__venue">EMNLP 2023 · Oral</p>
              <h3><a href="https://aclanthology.org/2023.emnlp-main.918/" target="_blank" rel="noopener">Learning to Describe for Predicting Zero-shot Drug-Drug Interactions</a></h3>
              <p class="paper-card__authors"><strong>Fangqi Zhu</strong>, Yongqi Zhang, Lei Chen, Bing Qin, Ruifeng Xu</p>
              <div class="paper-card__links">
                <a href="https://aclanthology.org/2023.emnlp-main.918/" target="_blank" rel="noopener">Paper</a>
                <a href="https://github.com/zhufq00/DDIs-Prediction" target="_blank" rel="noopener">Code</a>
              </div>
            </div>
          </article>

          <article class="paper-card paper-card--compact">
            <a class="paper-card__media" href="https://aclanthology.org/2023.findings-acl.800/" target="_blank" rel="noopener">
              <span class="paper-card__badge">ACL Findings 2023</span>
              <img src="{{ '/images/ACL2023.png' | relative_url }}" alt="Event skeleton generation overview">
            </a>
            <div class="paper-card__body">
              <p class="paper-card__venue">ACL Findings 2023</p>
              <h3><a href="https://aclanthology.org/2023.findings-acl.800/" target="_blank" rel="noopener">A Diffusion Model for Event Skeleton Generation</a></h3>
              <p class="paper-card__authors"><strong>Fangqi Zhu</strong>, Lin Zhang, Jun Gao, Bing Qin, Ruifeng Xu, Haiqin Yang</p>
              <div class="paper-card__links">
                <a href="https://aclanthology.org/2023.findings-acl.800/" target="_blank" rel="noopener">Paper</a>
                <a href="https://github.com/zhufq00/EventSkeletonGeneration" target="_blank" rel="noopener">Code</a>
                <a href="{{ '/resources/DEGM_Poster.pdf' | relative_url }}" target="_blank" rel="noopener">Poster</a>
              </div>
            </div>
          </article>

          <article class="paper-card paper-card--compact">
            <a class="paper-card__media" href="https://ojs.aaai.org/index.php/AAAI/article/view/26645" target="_blank" rel="noopener">
              <span class="paper-card__badge">AAAI 2023</span>
              <img src="{{ '/images/AAAI2023.png' | relative_url }}" alt="Script event prediction overview">
            </a>
            <div class="paper-card__body">
              <p class="paper-card__venue">AAAI 2023 · Oral</p>
              <h3><a href="https://ojs.aaai.org/index.php/AAAI/article/view/26645" target="_blank" rel="noopener">A Generative Approach for Script Event Prediction via Contrastive Fine-Tuning</a></h3>
              <p class="paper-card__authors"><strong>Fangqi Zhu</strong>, Jun Gao, Changlong Yu, Wei Wang, Chen Xu, Xin Mu, Min Yang, Ruifeng Xu</p>
              <div class="paper-card__links">
                <a href="https://ojs.aaai.org/index.php/AAAI/article/view/26645" target="_blank" rel="noopener">Paper</a>
                <a href="https://github.com/zhufq00/mcnc" target="_blank" rel="noopener">Code</a>
                <a href="{{ '/resources/SEP_Poster.pdf' | relative_url }}" target="_blank" rel="noopener">Poster</a>
              </div>
            </div>
          </article>
        </div>
      </details>
    </div>
  </section>

  <section class="section split-section" id="experience">
    <div class="section__header">
      <p class="eyebrow">Experience</p>
      <h2>Research internships</h2>
    </div>

    <div class="timeline">
      <article class="timeline-item timeline-item--current">
        <span class="timeline-item__date">2026.05 - Present</span>
        <div>
          <h3><a href="https://research.nvidia.com/labs/gear/" target="_blank" rel="noopener">NVIDIA GEAR</a></h3>
          <p>Research Intern · World models for robot learning</p>
          <p>Collaborating with <a href="https://github.com/Little-Podi" target="_blank" rel="noopener">Shenyuan Gao</a>, <a href="https://yukezhu.me/" target="_blank" rel="noopener">Yuke Zhu</a>, and <a href="https://jimfan.me/" target="_blank" rel="noopener">Jim Fan</a>.</p>
        </div>
      </article>
      <article class="timeline-item">
        <span class="timeline-item__date">2025.09 - 2026.05</span>
        <div>
          <h3><a href="https://seed.bytedance.com/en/" target="_blank" rel="noopener">ByteDance Seed Multimodal</a></h3>
          <p>Research Intern · Multimodal foundation models</p>
          <p>Mentor: <a href="https://haoqifan.github.io/" target="_blank" rel="noopener">Haoqi Fan</a>.</p>
        </div>
      </article>
      <article class="timeline-item">
        <span class="timeline-item__date">2024.03 - 2025.09</span>
        <div>
          <h3><a href="https://seed.bytedance.com/en/direction/robotics" target="_blank" rel="noopener">ByteDance Seed Robotics</a></h3>
          <p>Research Intern · Robot world models and real-robot simulation</p>
          <p>Mentors: <a href="https://www.taokong.org/" target="_blank" rel="noopener">Tao Kong</a>, <a href="https://scholar.google.com/citations?user=7u0TYgIAAAAJ&amp;hl=zh-CN&amp;oi=ao" target="_blank" rel="noopener">Hongtao Wu</a>, and <a href="https://yusufma03.github.io/" target="_blank" rel="noopener">Xiao Ma</a>.</p>
        </div>
      </article>
      <article class="timeline-item">
        <span class="timeline-item__date">2023.04 - 2023.12</span>
        <div>
          <h3>4Paradigm</h3>
          <p>Research Intern · NLP and drug-drug interaction prediction</p>
          <p>Mentor: <a href="https://yzhangee.github.io/" target="_blank" rel="noopener">Yongqi Zhang</a>.</p>
        </div>
      </article>
      <article class="timeline-item">
        <span class="timeline-item__date">2022.09 - 2023.03</span>
        <div>
          <h3><a href="https://idea.edu.cn/" target="_blank" rel="noopener">International Digital Economy Academy</a></h3>
          <p>Research Intern · DataStory AI Lab</p>
          <p>Mentor: <a href="https://hqyang.github.io/" target="_blank" rel="noopener">Haiqin Yang</a>.</p>
        </div>
      </article>
    </div>
  </section>

  <section class="section" id="education">
    <div class="section__header">
      <h2>Education</h2>
    </div>
    <div class="mini-list">
      <article>
        <span>2024 - Present</span>
        <h3>PhD in Computer Science and Engineering</h3>
        <p>Hong Kong University of Science and Technology · Advisor: Prof. Song Guo</p>
      </article>
      <article>
        <span>2021.09 - 2024.01</span>
        <h3>Master of Engineering in Computer Science and Technology</h3>
        <p>Harbin Institute of Technology, Shenzhen</p>
      </article>
      <article>
        <span>2017.09 - 2021.06</span>
        <h3>Bachelor of Engineering in Software Engineering</h3>
        <p>Wuhan University</p>
      </article>
    </div>
  </section>

  <footer class="site-footer">
    <div class="site-footer__meta">
      <p>© Fangqi Zhu</p>
      <a href="#top">Back to top</a>
    </div>
    <div class="site-traffic" aria-label="Visitor map and traffic">
      <p class="site-traffic__label">Visitors</p>
      <script type="text/javascript" id="clustrmaps" src="https://cdn.clustrmaps.com/map_v2.js?cl=ffffff&amp;w=300&amp;t=n&amp;d=ifeNXTINjIfXkEwLoSDWssg3YSpojOXvFlVY4sXZqVw"></script>
    </div>
  </footer>
</main>
