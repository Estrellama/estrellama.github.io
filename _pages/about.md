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

Hi👋! I'm a first-year Ph.D. student in the joint program between <a href="https://www.westlake.edu.cn/">Westlake University</a> and <a href="https://www.zju.edu.cn/">Zhejiang University</a>, advised by Prof. <a href="https://www.yukaicheng.cn/">Kaicheng Yu</a>. I obtained my M.S. in Computer Science from <a href="http://www.tju.edu.cn/">Tianjin University</a> in 2024, advised by Prof. <a href="https://dilincv.github.io/">Di Lin</a>. And I also received my B.E. in Computer Science from <a href="https://www.tiangong.edu.cn/">Tiangong University</a> in 2021.
I am currently a research intern at Li.Auto. My research interests lie in the fields of computer vision, computer graphics and machine learning. 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 
* denotes equal contributions.

  <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
    <tbody>

      <tr>
        <td style="padding:5pt; width:25%; vertical-align:middle">
          <img src="images/delphi_teaser.png" width="100%" height="auto" style="object-fit:cover">
        </td>
        <td style="padding:5pt; width:75%;vertical-align:middle">
          <span class="papertitle">Unleashing Generalization of End-to-End Autonomous Driving with Controllable Long Video Generation</span>
          
          <br>
          <strong>Enhui Ma*</strong>,
          Lijun Zhou*,
          Tao Tang,
          Zhan Zhang,
          Dong Han,
          Junpeng Jiang,
          Kun Zhan,
          Peng Jia,
          Xianpeng Lang,
          Haiyang Sun,
          <a href="https://dilincv.github.io/">Di Lin</a>,
          <a href="https://www.yukaicheng.cn/">Kaicheng Yu</a>

          <br>
          <em>
            arXiv 2024
          </em>
          <br>
          <a href="https://westlake-autolab.github.io/delphi.github.io/">Project Page</a> /
          <a href="https://arxiv.org/abs/2406.01349">Paper</a>
        </td>
      </tr>
      
      <tr>
        <td style="padding:5pt; width:25%; vertical-align:middle">
          <img src="images/bevcontrol_teaser.jpg" width="100%" height="auto" style="object-fit:cover">
        </td>
        <td style="padding:5pt; width:75%;vertical-align:middle">
          <span class="papertitle">BEVControl: Accurately Controlling Street-view Elements with Multi-perspective Consistency via BEV Sketch Layout</span>
          
          <br>
          Kairui Yang*, 
          <strong>Enhui Ma*,</strong>,        
          Jibin Peng,
          Qing Guo,
          <a href="https://dilincv.github.io/"> Di Lin,</a>,
          <a href="https://www.yukaicheng.cn/"> Kaicheng Yu</a>

          <br>
          <em>
            arXiv 2023
          </em>
          <br>
          <a href="https://arxiv.org/abs/2308.01661">Paper</a>
        </td>
      </tr>
      <tr>
        <td style="padding:5pt; width:25%; vertical-align:middle">
          <img src="images/cvsformer_teaser.png" width="100%" height="auto" style="object-fit:cover">
        </td>
        <td style="padding:5pt; width:75%;vertical-align:middle">
          <span class="papertitle">CVSformer: Cross-View Synthesis Transformer for Semantic Scene Completion</span>
          
          <br>
          Haotian Dong*,
          <strong>Enhui Ma*</strong>,
          Lubo Wang,
          Miaohui Wang,
          Wuyuan Xie,
          Qing Guo,
          Ping Li,
          Lingyu Liang,
          Kairui Yang,
          <a href="https://dilincv.github.io/">Di Lin</a>

          <br>
          <em>
            ICCV 2023
          </em>
          <br>
          <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Dong_CVSformer_Cross-View_Synthesis_Transformer_for_Semantic_Scene_Completion_ICCV_2023_paper.html">Paper</a>
          /
          <a href="https://github.com/donghaotian123/CVSformer">Code</a>
        </td>
      </tr>

      <!-- <tr>
        <td style="padding:5pt; width:25%; vertical-align:middle">
          <video width="100%" height=auto style="bject-fit:cover" muted autoplay loop playsinline>
            <source src="images/lidar_rt.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </td>
        <td style="padding:5pt; width:75%;vertical-align:middle">
          <span class="papertitle">LiDAR-RT: Gaussian-based Ray Tracing for Dynamic LiDAR Re-simulation</span>
          
          <br>
          <a href="https://github.com/cxzhou35">Chenxu Zhou*</a>,
          <a href="https://github.com/lllcccfff">Lvchang Fu*</a>,
          <a href="https://pengsida.net/">Sida Peng</a>,              
          <strong>Yunzhi Yan</strong>,
          Zhanhua Zhang,
          Yong Chen,
          <a href="https://www.xiajiazhi.com/">Jiazhi Xia</a>,
          <a href="https://www.xzhou.me/">Xiaowei Zhou</a>
          <br>
          <em>
            CVPR 2025
          </em>
          <br>
          <a href="https://zju3dv.github.io/lidar-rt/">Project Page</a>
          /
          <a href="https://arxiv.org/abs/2412.15199">Paper</a>
          /
          <a href=https://github.com/zju3dv/LiDAR-RT>Code</a>
        </td>
      </tr> -->

    </tbody>
  </table>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.01 - Present*, Li Auto, [Autonomous Driving Team](https://github.com/LiAutoAD). Research Intern.
- *2023.01 - 2023.08*, Alibaba Group, Autonomous Driving Lab. Research Intern.
