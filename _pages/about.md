---
permalink: /
title: ""
excerpt: ""
author_profile: true
analytics: true
google_site_verification: true
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

Hi! I'm a first-year PhD student at OpenRobotLab@[Shanghai AI Lab](https://www.shlab.org.cn/)(through joint-training program with CS@ZJU), advised by [Jiangmiao Pang](https://oceanpang.github.io/) and [Dahua Lin](http://dahua.site/), co-advised by [Xiaowei Zhou](https://www.xzhou.me/). Prior to this, I got my bachelor's degree from [College of Control Science and Engineering](http://www.cse.zju.edu.cn/cseenglish/main.htm) and [Chu Kochen Honors College](http://ckc.zju.edu.cn/ckcen/)(Advanced Honor Class of Engineering Education) at Zhejiang University in 2024.

My research interests include Embodied AI, Robot Learning and Computer Vision, currently I'm working on humanoid robot motion generation. Feel free to reach out to me :)

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News -->
# Recent News
- *2024.09*: &nbsp;[MGF](https://github.com/mulplue/MGF) is accepted by Neurips 2024 🎉 Many thanks to Jinkun and Jiangmiao!
- *2024.07*: &nbsp;We released [GRUtopia](https://github.com/OpenRobotLab/GRUtopia)(aka. 桃源 in Chinese), the first simulated interactive 3D society designed for various robots.
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📝 Publications  -->
# Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv preprint</div><img src='images/teaser/grutopia.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[GRUtopia: Dream General Robots in a City at Scale](https://arxiv.org/abs/2407.10943) \\
Hanqing Wang$\ast$, **Jiahe Chen**$\ast$, Wensi Huang$\ast$, Qingwei Ben$\ast$, Tai Wang$\ast$, Boyu Mi$\ast$, Tao Huang, Siheng Zhao, Yilun Chen, Sizhe Yang, Peizhou Cao, Wenye Yu, Zichao Ye, Jialun Li, Junfeng Long, Zirui Wang, Huiling Wang, Ying Zhao, Zhongying Tu, Yu Qiao, Dahua Lin, Jiangmiao Pang$\dagger$ \\
[**Github**](https://github.com/OpenRobotLab/GRUtopia) | ![](https://img.shields.io/github/stars/OpenRobotLab/GRUtopia)
- We proposed GRUtopia, the first simulated interactive 3D society designed for various robots. It features (a)GRScenes, a dataset with 100k interactive and finely annotated scenes. (b) GRResidents, a LLM driven NPC system. (c) GRBench, a benchmark posing moderately challenging tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurips 2024</div><img src='images/teaser/mgf.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[MGF: Mixed Gaussian Flow for Diverse Trajectory Prediction](https://arxiv.org/abs/2402.12238) \\
**Jiahe Chen**$\ast$, Jinkun Cao$\ast$, Dahua Lin, Kris Kitani, Jiangmiao Pang$\dagger$ \\
[**Github**](https://github.com/mulplue/MGF) | ![](https://img.shields.io/github/stars/mulplue/MGF) Code coming soon...(to be organized)
- We proposed MGF for improving the diversity of trajectory prediction, which achieves SOTA performance in the evaluation of both accuracy and diversity.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards -->
# Honors and Awards
- Zhejiang University Outstanding Graduate.
- Zhejiang Government Scholarship.
- Zhejiang University 1st Class Scholarships.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!-- # 💻 Internships -->
# Internships
- *2023.02 - 2024.07*, [Shanghai AI Lab](https://www.shlab.org.cn/), advised by [Jiangmiao Pang](https://oceanpang.github.io/).
- *2022.09 - 2023.06*, [CSE@ZJU](http://www.cse.zju.edu.cn/cseenglish/main.htm), advised by [Qingyuan Ren](https://person.zju.edu.cn/en/0008668).
- *2022.05 - 2022.11*, [CS@W&M](https://www.wm.edu/as/computerscience/), advised by [Huajie Shao](https://shj1987.github.io/).
- *2021.04 - 2021.10*, [Supcon](https://global.supcon.com/), advised by [Wenjun Huang](https://person.zju.edu.cn/en/huangwj).

<!-- # Educations
- *2024.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2020.09 - 2024.06*, Undergraduate (in honor), College of Control Science and Engineering & C -->