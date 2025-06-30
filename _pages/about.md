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

I am now a PhD student (2022-) in Computer Science and Technology at Shanxi University, supervised by Prof. [Ru Li](https://www.researchgate.net/scientific-contributions/Ru-Li-14829601?_sg=VXNUDhg-exV6GUMTTzZ3UgEBy0zZa6hRgTd8V_oo4GZ0doGm9wp14Vo_rBLhkms1qfdWlJrEIZquUi0). Meanwhile, I am co-supervised by Prof. [Xiaoli Li](https://personal.ntu.edu.sg/xlli/), who is affiliated with the Institute for Infocomm Research at A*Star, Singapore. Before that, I received my B.S. degree from Shanxi University in 2020, majoring in computer science and technology.

My research interests focus on explainable natural language processing, including explainable probing, rationalization, and reasoning. 
I am also interested in explicit knowledge and implicit knowledge, such as FrameNet KBs and Parameterized PLMs.
Feel free to contact me by <a href="mailto:yunxiaomr@163.com">email</a> if you are interested in discussing or collaborating with me.
<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script> 
It has been attented <span id="busuanzi_value_site_pv"></span> times.

<!--<div style="text-align: center; margin-top: 0px;"> -->
<!-- Views: <span id="busuanzi_value_site_pv"></span> times<br>-->
<!--Visitors: <span id="busuanzi_value_site_uv"></span> -->
<!-- *2024.12*: &nbsp; I will visit Singapore as a visiting postgraduate research student between 2024 and 2025.-->
<!--</div> 🎉 -->
<!--I have published several papers on explainability in international conferences and journals. Additionally, I participated in a competition focused on interpretability, achieving the honor of winning the national first prize (champion) in China.  -->
<!--- *2024.08*: &nbsp; We attend the 2024 Annual Conference of the Association for Computational Linguistics in Bangkok, Thailand.-->


# 🔥 News 
- *[Jan. 2025]*: &nbsp; One paper on Explainable Knowledge Probing is accepted in [DASFAA2025](https://dasfaa2025.github.io/#/calls/research-papers), a long oral presentation.
- *2024.11*: &nbsp; One paper on Explainable Multi-hop Reasoning is accepted in [COLING2025](https://coling2025.org/).
- *2024.08*: &nbsp; We attend the 2024 Annual Conference of the ACL in Bangkok, Thailand.
- *2024.05*: &nbsp; One paper on Self-explaining Rationalization is accepted in [ACL2024](https://2024.aclweb.org/). 
- *2023.04*: &nbsp; One Journal paper on FrameNet Knowledge is accepted on [MIR2024](https://www.mi-research.net/).
- *2022.10*: &nbsp; We share our tutorial on winning the championship on [CCL2022](https://hfl-rc.github.io/cmrc2022/program/).
- *2022.09*: &nbsp; 🏆 We get the First Prize on CMRC2022 (the 1st rank) in the 21st China National Conference on Computational Linguistics.
- *2022.05*: &nbsp; Two Journal papers on Machine Reading Comprehension are accepted to the Journal of Chinese Information Processing.
- *2021.05*: &nbsp; One paper on Explainable Evaluation is accepted in [Findings of ACL2021](https://2021.aclweb.org/). 

# 📝 Selected Publications 
<span class="noter" style="color:#7d7d7d"> (* = equal contribution)</span> 
<!--<span class="noter" style="color:#7d7d7d"> (* = equal contribution | † = I mentored)</span> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DASFAA 2025</div><img src='images/KnowProb1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Explaining Black-box Language Models with Knowledge Probing Systems: A Post-hoc Explanation Perspective](https://yunxiaomr.github.io/) (**<font color=red>A long oral presentation</font>**)

Yunxiao Zhao, Hao Xu, Zhiqiang Wang, Xiaoli Li, Jiye Liang, Ru Li.

- Pre-trained Language Models (PLMs) are trained on large amounts of unlabeled data, and they exhibit remarkable reasoning skills. However, the trustworthiness challenges have become increasingly evident. To alleviate this problem, we propose a novel knowledge-guided probing approach called KnowProb in a post-hoc explanation way, which aims to probe whether black-box PLMs understand implicit knowledge beyond the given text, rather than focusing only on the surface-level content of the text. 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2025</div><img src='images/LOG_.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LOG: A Local-to-Global Optimization Approach for Retrieval-based Explainable Multi-Hop Question Answering](https://yunxiaomr.github.io/)

Hao Xu\*, Yunxiao Zhao\*, Jiayang Zhang, Zhiqiang Wang, Ru Li.

- Explainable multi-hop question answering aims to utilize multi-source intensive documents retrieved to derive the answer. However, it is challenging to model the importance of knowledge retrieved. In this paper, we propose LOG, a novel optimized retrieval method to discover more beneficial knowledge from a local-to-global perspective, facilitating multi-hop reasoning, notably for long-chain reasoning.  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/AGR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AGR: Reinforced Causal Agent Guided Self-explaining Rationalization](https://yunxiaomr.github.io/)

Yunxiao Zhao, Zhiqiang Wang, Xiaoli Li, Jiye Liang, Ru Li.
<!-- 
<a href="https://aclanthology.org/2024.acl-short.47.pdf">**Paper**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<a href="../images/poster_agr.pdf">**Poster**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- We propose a novel approach AGR (Agent-Guided Rationalization), guiding the next action of the model based on its current training state. We introduce causal intervention calculus to quantify the causal effects inherent during rationale training, and utilize the reinforcement learning process to refine their learning bias.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MIR 2024</div><img src='images/CFN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A comprehensive Overview of CFN From a Commonsense Perspective](https://yunxiaomr.github.io/)

Ru Li, Yunxiao Zhao, Zhiqiang Wang, Xuefeng Su, Shaoru Guo, Yong Guan, Xiaoqi Han, Hongyan Zhao.
<!-- 
<a href="https://link.springer.com/article/10.1007/s11633-023-1450-8">**Paper**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<a href="https://www.mi-research.net/article/doi/10.1007/s11633-023-1450-8">**Poster**</a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- We conduct a comprehensive overview of Chinese FrameNet from a commonsense perspective, covering topics such as scenario commonsense representation, Chinese FrameNet resources, and its applications. We also summarize recent breakthroughs and identify future research directions. 
</div>
</div>


# 🎖 Honors and Awards
- *2025.06* The Outstanding Graduate Student (PhD Research Student). 
- *2024.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2024.
- *2023.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2023.
- *2022.10* The Champion Award on CCL2022@CMRC, Chinese Information Processing Society of China (CIPS), in 2022.
- *2022.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2022.
- *2021.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2021.
- *2021.06* The Outstanding Graduate Student (Master Research Student). 

# 📖 Educations
- *2022.09 - 2026.06 (now)*, School of Computer and Information Technology, Shanxi University. Ph.D. Student.
- *2020.09 - 2022.06*, School of Computer and Information Technology, Shanxi University. Master Student.
- *2016.09 - 2020.06*, School of Computer and Information Technology, Shanxi University. Undergraduate.


# 💬 Talks
- *2025.05*, We shared our oral on [DASFAA2025](https://dasfaa2025.github.io/). \| [\[video\]](https://yunxiaomr.github.io/) \| [\[slide\]](https://yunxiaomr.github.io/)
- *2022.10*, We shared our tutorial@CMRC on [CCL 2022](https://hfl-rc.github.io/cmrc2022/program/). \| [\[video\]](https://yunxiaomr.github.io/) \| [\[slide\]](https://yunxiaomr.github.io/)


# 💻 Internships
- *2019.12 - 2020.06*, [Taiyuan](https://yunxiaomr.github.io), China.

<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=70&t=n&d=VV8T-NYVjl9sU0A1x6WDxCkr-L4MgnBbZbkCYCK9Ljw&co=ffffff&cmo=ffffff&cmn=ffffff"></script>

<!-- <div>
<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=VV8T-NYVjl9sU0A1x6WDxCkr-L4MgnBbZbkCYCK9Ljw&co=9e9eee&cmo=ff5353&cmn=3acc3a"></script></div>-->

<!-- Default Statcounter code for My personal site  
<script type="text/javascript">
var sc_project=12037091; 
var sc_invisible=0; 
var sc_security="f3e3a82d"; 
var sc_https=1; 
var scJsHost = "https://";
document.write("<sc"+"ript type='text/javascript' src='" + scJsHost+
"statcounter.com/counter/counter.js'></"+"script>");
</script>
<noscript><div class="statcounter"><a title="Web Analytics Made Easy -
StatCounter" href="https://statcounter.com/" target="_blank"><img
class="statcounter" src="https://c.statcounter.com/12037091/0/f3e3a82d/0/"
alt="Web Analytics Made Easy - StatCounter"></a></div></noscript>
 End of Statcounter Code -->
