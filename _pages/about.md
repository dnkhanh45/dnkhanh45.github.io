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

# About Me

I am a Research Resident under the supervision of [Prof. Trung Le](https://scholar.google.com/citations?user=gysdMxwAAAAJ) at [VinAI Research](https://www.vinai.io), Vietnam. Previously, I worked in [Prof. Phi Le Nguyen](https://users.soict.hust.edu.vn/lenp)'s group (ICN Lab) at The School of Information and Communications Technology, Hanoi University of Science and Technology (HUST).I received a bachelor's degree in Computer Science from HUST in 2023.

My research focuses on Deep Generative Models, including Diffusion Models, Consistency Models, and Auto-Regressive Models. I am particularly interested in improving generation quality and computational efficiency in both the training and inference stages.

# 🔥 News

- *January 2025*: Our paper [Improved Training Technique for Latent Consistency Models](https://arxiv.org/abs/2502.01441) is accepted to ICLR 2025!
- *September 2024*: Our paper [Erasing Undesirable Concepts in Diffusion Models with Adversarial Preservation](https://arxiv.org/abs/2410.15618) is accepted to NeurIPS 2024!

# 📝 Publications
<details>
  <summary>Notations</summary>
  <div markdown="1">
  - \*: Equal contributions
  - &dagger;: Project Lead & Corresponding Author
  </div>
</details>

<!-- Improved Training Technique for Latent Consistency Models -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">
        ICLR 2025
      </div>
      <img src='images/500x300.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Improved Training Technique for Latent Consistency Models](https://arxiv.org/abs/2502.01441) \\
  Quan Dao\*&dagger;, **Khanh Doan\***, Di Liu, Trung Le, and Dimitris Metaxas. \\
  The Thirteenth International Conference on Learning Representations (ICLR), 2025. \\
  <a href="https://openreview.net/forum?id=PQjZes6vFV"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICLR 2025&color=blue"></a>
  <a href="https://arxiv.org/abs/2502.01441"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
  <a href="https://github.com/quandao10/sLCT"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a> 
  </div>
</div>

<!-- Erasing Undesirable Concepts in Diffusion Models with Adversarial Preservation -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">
        NeurIPS 2024
      </div>
      <img src='images/500x300.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Erasing Undesirable Concepts in Diffusion Models with Adversarial Preservation](https://arxiv.org/abs/2410.15618) \\
  Anh Bui, Long Vuong, **Khanh Doan**, Trung Le, Paul Montague, Tamas Abraham, and Dinh Phung. \\
  The Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS), 2024. \\
  <a href="https://openreview.net/forum?id=GDz8rkfikp"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=NeurIPS 2024&color=yellow"></a>
  <a href="https://arxiv.org/abs/2410.15618"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
  <a href="https://github.com/tuananhbui89/Erasing-Adversarial-Preservation"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a> 
  </div>
</div>

<!-- Deep Reinforcement Learning-based Charging Algorithm for Target Coverage and Connectivity in WRSNs -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">
        PIMRC 2022
      </div>
      <img src='images/500x300.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Deep Reinforcement Learning-based Charging Algorithm for Target Coverage and Connectivity in WRSNs](https://ieeexplore.ieee.org/abstract/document/9978107) \\
  Hung Cuong Nguyen, Manh Cuong Dao, Thanh Trung Nguyen, **Khanh Doan**, Thanh Hung Nguyen, Truong Thao Nguyen, and Phi Le Nguyen. \\
  2022 IEEE 33rd Annual International Symposium on Personal, Indoor and Mobile Radio Communications (PIMRC), 2022. \\
  <a href="https://ieeexplore.ieee.org/abstract/document/9978107"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=PIMRC 2022&color=purple"></a>
  <a href="https://ieeexplore.ieee.org/abstract/document/9978107"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
  <a href="https://github.com/AIoT-Lab-BKAI/CuongNH-WRSN-DQN"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a> 
  </div>
</div>

<!-- Matching the statements: A simple and accurate model for key point analysis -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">
        EMNLP 2021 Workshop
      </div>
      <img src='images/500x300.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Matching the statements: A simple and accurate model for key point analysis](https://aclanthology.org/2021.argmining-1.17/) \\
  Hoang Phan, Long Nguyen, Long Nguyen, and **Khanh Doan**. \\
  Proceedings of the 8th Workshop on Argument Mining, the 2021 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2021. \\
  <a href="https://aclanthology.org/2021.argmining-1.17/"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=EMNLP 2021&color=orange"></a>
  <a href="https://aclanthology.org/2021.argmining-1.17/"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
  <a href="https://github.com/VietHoang1512/KPA"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a> 
  </div>
</div>

# 🎖 Honors and Awards

<!-- - *October 2022*: Honorable Mention - INFORMS Undergraduate Operations Research Prize
- *October 2022*: Best Thesis Presentation Award - Hanoi University of Science and Technology
- *September 2019*: Excellence Scholarship for the academic year - Hanoi University of Science and Technology -->

- **Second Prize** in Ministerial Science and Technology Award for Students in Higher Education
Institutions, 2022
- **Gold Medals** for both Algebra and Calculus, Group A, Vietnamese Mathematical Olympiad for
college students, Vietnam Mathematical Society (VMS), 2019
- **Second Prize** in Vietnamese Mathematical Olympiad (VMO), 2018
- **Third Prize** in Vietnamese Mathematical Olympiad (VMO), 2017

<!-- # 💬 Invited Talks
- *2022.11*, Inter-Experimental LHC Machine Learning Working Group, CERN
- *2022.10*, Department of Physics, Purdue University
- *2022.08*, AI Time
- *2022.07*, Fast Machine Learning Lab
-->

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experience
- *August 2021 - June 2023*: ICN Lab, The School of Information and Communications Technology, Hanoi University of Science and Technology (HUST), Vietnam
- *August 2023 - Now*: Research Resident at VinAI Research, Vietnam
