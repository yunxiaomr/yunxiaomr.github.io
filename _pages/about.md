---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}
{% <script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script> %}


<span class='anchor' id='about-me'></span>


I am pursuing my PhD degree (2022~) at [Shanxi University](https://www.sxu.edu.cn/), supervised by Prof. [Ru Li](https://www.researchgate.net/scientific-contributions/Ru-Li-14829601?_sg=VXNUDhg-exV6GUMTTzZ3UgEBy0zZa6hRgTd8V_oo4GZ0doGm9wp14Vo_rBLhkms1qfdWlJrEIZquUi0). I am also supervised Prof. [Xiaoli Li](https://personal.ntu.edu.sg/xlli/), who is affiliated with the Institute for Infocomm Research at A*Star, Singapore. Before that, I received a B.S. degree from Shanxi University in 2020, majoring in computer science and technology (Excellent Lab Class of Big Data, Top %10). 

My research interests include rationalization, reinforcement learning and language models. Also I am interested in framenet knowledge in the linguistics. 
I have published some academic papers at the international conference ACL, the journal Machine Intelligence Research, and the Journal of Chinese Information Processing. Additionally, I participated in natural language processing evaluations related to interpretability and won the national first prize (champion) in China.

It has been attented <span id="busuanzi_value_site_pv"></span> times, involving <span id="busuanzi_value_site_uv"></span> visitors.



<!--<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script> -->
<!--<div style="text-align: center; margin-top: 0px;"> -->
<!-- Views: <span id="busuanzi_value_site_pv"></span> times<br>-->
<!--Visitors: <span id="busuanzi_value_site_uv"></span> -->
<!--</div> -->



# 🔥 News
- *2024.08*: &nbsp; We attend the 2024 Annual Conference of the Association for Computational Linguistics in Bangkok, Thailand.
- *2024.05*: &nbsp; One paper on Self-explaining Rationalization is accepted in [ACL 2024](https://2024.aclweb.org/). 
- *2023.04*: &nbsp; One Journal paper on FrameNet Knowledge is accepted on [MIR 2024](https://www.mi-research.net/).
- *2022.10*: &nbsp; We share our tutorial on winning the championship on [CCL 2022](https://hfl-rc.github.io/cmrc2022/program/).
- *2022.10*: &nbsp; We get the First Prize on CMRC2022 in the 21st China National Conference on Computational Linguistics.
- *2022.05*: &nbsp; Two Journal papers on Machine Reading Comprehension are accepted to the Journal of Chinese Information Processing.
- *2021.05*: &nbsp; One paper on Explainable Evaluation is accepted in [ACL 2021](https://2021.aclweb.org/). 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/AGR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AGR: Reinforced Causal Agent Guided Self-explaining Rationalization](https://yunxiaomr.github.io/)

**Yunxiao Zhao**, Zhiqiang Wang, Xiaoli Li, Jiye Liang, Ru Li.

<a href="../images/paper_agr.pdf">**Paper**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<a href="../images/poster_agr.pdf">**Poster**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- We propose a novel approach AGR (Agent-Guided Rationalization), guiding the next action of the model based on its current training state. We introduce causal intervention calculus to quantify the causal effects inherent during rationale training, and utilize reinforcement learning process to refine their learning bias.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MIR 2024</div><img src='images/CFN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A comprehensive Overview of CFN From a Commonsense Perspective](https://yunxiaomr.github.io/)

Ru Li, **Yunxiao Zhao**, Zhiqiang Wang, Xuefeng Su, Shaoru Guo, Yong Guan, Xiaoqi Han, Hongyan Zhao.

<a href="https://link.springer.com/article/10.1007/s11633-023-1450-8">**Paper**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<a href="https://www.mi-research.net/article/doi/10.1007/s11633-023-1450-8">**Poster**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We conduct a comprehensive overview of Chinese FrameNet from a commonsense perspective, covering topics such as scenario commonsense representation, Chinese FrameNet resources, and its applications. We also summarize recent breakthroughs and identify future research directions. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2021</div><img src='images/GCRC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GCRC: A New Challenging MRC Dataset from Gaokao Chinese for Explainable Evaluation](https://yunxiaomr.github.io/)

Hongye Tan, Xiaoyue Wang, Yu Ji, Ru Li, Xiaoli Li, Zhiwei Hu, **Yunxiao Zhao**, Xiaoqi Han.

<a href="https://aclanthology.org/2021.findings-acl.113.pdf">**Paper**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<a href="https://aclanthology.org/2021.findings-acl.113.pdf">**Poster**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose GCRC, a new dataset with challenging and high-quality multi-choice questions, collected from Gaokao Chinese (Chinese subject from the National College Entrance Examination of China). We have manually labelled three types of evidence to evaluate MRC systems’ reasoning process: 1) sentence-level relevant supporting facts in an article required for answering a given question, 2) error reason of a distractor (i.e., an incorrect option) for explaining why a distractor should be eliminated, which is an important reasoning step for multi-choice questions, and 3) types of reasoning skills required for answering questions.
</div>
</div>




# 🎖 Honors and Awards
- *2024.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2024.
- *2023.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2023.
- *2022.10* CCL 2022 Explainable Machine Reading Comprehension - Choice Track, Champion.
- *2022.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2022.
- *2021.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2021.
- *2021.05* The Outstanding Graduate Student. 

# 📖 Educations
- *2022.09 - 2026.06 (now)*, School of Computer and Information Technology, Shanxi University. Ph.D. Student.
- *2020.09 - 2022.06*, School of Computer and Information Technology, Shanxi University. Master Student.
- *2016.09 - 2020.06*, School of Computer and Information Technology, Shanxi University. Undergraduate.


# 💬 Invited Talks
- *2022.10*, We shared our tutorial on winning the championship on [CCL 2022](https://hfl-rc.github.io/cmrc2022/program/). \| [\[video\]](https://yunxiaomr.github.io/) \| [\[slide\]](https://yunxiaomr.github.io/)




# 💻 Internships
- *2019.12 - 2020.06*, [Taiyuan](https://yunxiaomr.github.io), China.
