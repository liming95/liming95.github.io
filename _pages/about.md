---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
.pubtitle{
    background: #BD666D;
    color: white;
    font-size: 12px;
    padding: 1px 5px 1px 5px;
    border-radius: 15px;
    float: left;
    font-weight:bold;
}
.font-bold{
    font-weight:bold;
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
<!-- I am an incoming PhD student at Stevens Institute of Technology, advised by <a href="https://www.liuhongyuan.com/">Hongyuan Liu</a>. My current research focuses on GPU-accelerated regular expression matching engines. -->

I am currently a PhD candidate at the <a href="https://www.hitsz.edu.cn/">Harbin Institute of Technology (Shenzhen)</a>, supervised by <a href="https://shaohuais.github.io/">Prof. Shaohui Shi</a>. My research focuses on RL-based post-training for large models.

Previously, I collaborated with <a href="https://www.liuhongyuan.com/">Prof. Hongyuan Liu</a> at Stevens Institute of Technology on GPU-accelerated regular expression matching.

I received my Master’s degree from the <a href="http://www.ict.ac.cn/">Institute of Computing Technology (ICT)</a>, Chinese Academy of Sciences (CAS), under the supervision of <a href="http://www.ict.cas.cn/sourcedb_2018_ict_cas/cn/jssrck/201310/t20131025_3963079.html">Prof. Guihai Yan</a>. My work during this period focused on DPU-enabled service mesh design and optimization.

Prior to that, I obtained my Bachelor’s degree from the School of Software Engineering at Tianjin University.

My research interests include distributed systems, parallel computing, GPU architecture, and hardware–software co-design in computer architecture.

<a href="../publication/cv.pdf">[CV]</a>
<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

<!-- # 🔥 News 
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

-->
# Publications
<ul>
<li><div class="pubtitle"> arXiv 2024 </div> &nbsp; <a href="../publication/flatproxy.pdf">FlatProxy: A DPU-centric Service Mesh Architecture for Hyperscale Cloud-native Application. </a> <span class="font-bold"> Ming Li </span> Wenyan Lu, Hanyue Lin, Jinya Wu, Guihai Yan. </li>
<li><div class="pubtitle"> ICPP 2023 </div> &nbsp; <a href="../publication/bitcolor.pdf">BitColor: Accelerating Large-Scale Graph Coloring on FPGA with Parallel Bit-Wise Engines.</a> Haishuang Fan, <span class="font-bold">Ming Li</span>, Jingya Wu, Wenyan Lu, Xiaowei Li, Guihai Yan. Proceedings of the 52nd International Conference on Parallel Processing. </li>
<li> <div class="pubtitle"> Master Thesis 2023 </div> &nbsp; <a href="../publication/master_thesis.pdf">The Architecture Design and Optimization of Service Mesh Based on DPU. 基于DPU的服务网格架构设计与优化.</a></li>
<li><div class="pubtitle"> White paper 2022</div> &nbsp; <a href="../publication/dpu_benchmark.pdf">DPU Benchmark Methodology and Implementation. 专用数据处理器（DPU）性能基准评测方法与实现.</a> Guihai Yan, Wenyan Lu, Jinya Wu, Hao Kong, Weiyue Zhao, Haishuang Fan, Yunkun Liao, Yujun Zhang, <span class="font-bold">Ming Li</span>, Hanyue LinLiyun Cheng, Shuai Gu, Mingliang Huang, et al. Institute of Computing Technology, Chinese Academy of Sciences. 2022.</li>
<li><div class="pubtitle"> White paper 2021</div> &nbsp; <a href="../publication/dpu_technology.pdf">The technical White Paper of Data Processing Unit. 专用数据处理器（DPU）技术白皮书.</a> Guihai Yan, Wenyan Lu, Jinya Wu, Hao Kong, Weiyue Zhao, Haishuang Fan, Yunkun Liao, Yujun Zhang, <span class="font-bold">Ming Li</span>, Yan Chen, Yu Zhang, Xiaofei Yuan, Huimin Cui. Institute of Computing Technology, Chinese Academy of Sciences. 2021.</li>
</ul>

# Patent
- *2024* A method, apparatus, and device for resource scheduling. <a href="../publication/patent-2022106929552.pdf"> 一种资源调度方法、装置及设备. </a>

# Honors and Awards
- *2022* Outstanding Scholarship of Institute of Computing Technology
- *2021* The Second Prize Winner in Customized Computing Challenge, hosted by CCF, AMD-Xilinx and PeKing University

# Educations and Experience
- *2025.12 - now*, PHD candidate - Department of Computer Science, Harbin Institute of Technology (Shenzhen)
- *2024.11 - 2025.12*, Research Intern - Department of Computer Science, Stevens Institute of Technology
- *2023.07 - 2024.06*, Software Engineer - Cloud-native Fundamental Software Group, YUSUR Technology
- *2020.09 - 2023.06*, Master - Institute of Computing Technology, Chinese Academy of Sciences
- *2015.09 - 2017.09*, Compulsory military service
- *2014.09 - 2020.06*, Bachelor - School of Software Engineering, Tianjin University

<!-- # 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

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
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
<hr>
<a href="https://info.flagcounter.com/9e1G"><img src="https://s11.flagcounter.com/count2/9e1G/bg_FFFFFF/txt_000000/border_CCCCCC/columns_4/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>