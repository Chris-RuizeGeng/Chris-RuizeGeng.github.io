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

I am a **Master's student in Robotics** at **Johns Hopkins University**. I also worked as a **Research Assistant** at the **Safe AI Lab, Carnegie Mellon University**, advised by Associate Professor [Ding Zhao](https://www.meche.engineering.cmu.edu/directory/bios/zhao-ding.html) and Postdoctoral Researcher [Hao E. Zhang](https://haozhang-thu.github.io/). I received my B.S. in Mechanical Design, Manufacturing and Automation from **Dalian University of Technology**, where I was advised by **Prof. Zhenyuan Jia**, Academician of the Chinese Academy of Engineering. During my senior year, I spent one year as an exchange student at the **NUS (Suzhou) Research Institute, National University of Singapore**.

My research focuses on whole-body control of humanoid robots, multi-agent cooperation and game theory, and vision-language models (VLMs). A video of one of my projects has received **110K+** views and **22K+** likes on social media. I have also collaborated with **General Motors** on a joint research project.


# 💻 Research Interests

- Whole-body control for humanoid robots: Reinforcement learning, Imitation learning, and Sim-to-real transfer
- Multi-agent cooperation and competition: Self-play and heterogeneous-robot games
- Multi-modal foundation models: Fusing vision, touch, and language for safe robotic manipulation

<table style="border:none;">
  <tr>
    <td width="25%" style="border:none; text-align:center;">
      <video src="images/agile_wbc.mp4" width="100%" style="border-radius:8px;" autoplay loop muted playsinline></video>
      <br>Agile Whole-Body Control
    </td>
    <td width="25%" style="border:none; text-align:center;">
      <video src="images/multiagent_safe.mp4" width="100%" style="border-radius:8px;" autoplay loop muted playsinline></video>
      <br>Multi-Agent Safe Decision Making
    </td>
    <td width="25%" style="border:none; text-align:center;">
      <video src="images/selfplay.mp4" width="100%" style="border-radius:8px;" autoplay loop muted playsinline></video>
      <br>Multi-Agent Self-Play
    </td>
    <td width="25%" style="border:none; text-align:center;">
      <video src="images/vtl_manipulation.mp4" width="100%" style="border-radius:8px;" autoplay loop muted playsinline></video>
      <br>Visual-Tactile LM for Safe Manipulation
    </td>
  </tr>
</table>

# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Successfully completed a joint research project with **General Motors**.
- *2026.06*: &nbsp;🎉🎉 I joined the **Safe AI Lab** at **Carnegie Mellon University** as a Research Assistant.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted to ICRA 2027</div><video src='images/selfplay.mp4' width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[Dynamics-Induced Commitment in Learning-Based Robotic Penalty Kicks](https://arxiv.org/abs/2609.21100)

**Ruize Geng**, Hao E. Zhang, Yisen Li, Yikai Wang, H. Eric Tseng, Ding Zhao

[**arXiv**](https://arxiv.org/abs/2609.21100)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted to ICRA 2027</div><video src='images/sage.mp4' width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[SAGE: Safety-Aligned Gradient Enforcement for Human-Robot Collaboration](https://arxiv.org/abs/2609.21130)

Yisen Li\*, Hao Zhang\*, **Ruize Geng**\*, Yves Tseng, Ding Zhao, H. Eric Tseng (\* equal contribution)

[**arXiv**](https://arxiv.org/abs/2609.21130)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted to ICRA 2027</div><video src='images/goalkeeping.mp4' width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[Anticipatory Robot Goalkeeping via Monotone Optimal Stopping](https://arxiv.org/abs/2609.23976)

Hao E. Zhang\*, **Ruize Geng**\*, Yisen Li, Yaru Niu, Yikai Wang, Raihan Haque, Khalil Zbiss, Guanyang Luo, Hui-ping Wang, H. Eric Tseng, Ding Zhao (\* equal contribution)

[**arXiv**](https://arxiv.org/abs/2609.23976)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted to ICRA 2027</div><video src='images/banana_kick.mp4' width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[Banana Kick: Response-Informed Skill Evolution for Humanoid Soccer](https://arxiv.org/abs/2609.27269)

Hao E. Zhang\*, **Ruize Geng**\*, Raihan Haque, Khalil Zbiss, Guanyang Luo, Hui-ping Wang, H. Eric Tseng, Ding Zhao (\* equal contribution)

[**arXiv**](https://arxiv.org/abs/2609.27269)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted to ICRA 2027</div><video src='images/cognition_control.mp4' width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[Cognition to Control: Multi-Agent Learning for Human-Humanoid Collaborative Transport](https://arxiv.org/abs/2603.03768)

Hao Zhang, Yisen Li, **Ruize Geng**, Yves Tseng, Yaru Niu, Ding Zhao, H. Eric Tseng

[**arXiv**](https://arxiv.org/abs/2603.03768)
</div>
</div>

# 📖 Educations
- *2025.08 - now*, M.S. in Robotics, **Johns Hopkins University**, Baltimore, USA.
- *2024.09 - 2025.07*, Exchange Student, **NUS (Suzhou) Research Institute, National University of Singapore**, Suzhou, China.
- *2021.09 - 2025.07*, B.E. in Mechanical Design, Manufacturing and Automation, **Dalian University of Technology**, Dalian, China.

# 💻 Research Experience
- *2026.06 - now*, Research Assistant, **Safe AI Lab, Carnegie Mellon University**, Pittsburgh, USA.
- *2023.07 - 2023.08*, Research Intern, **Institute of Automation, Chinese Academy of Sciences**, Beijing, China.