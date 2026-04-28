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

<div class="lang-en" markdown="1">

# 👋 About me {#about-me-en}
* Hello, I'm Chenyan!
* I am a 3rd year PhD candidate at the National University of Singapore (NUS), Singapore. 
* I am supervised by [Dr. ZhiYong HUANG](https://www.comp.nus.edu.sg/~huangzy/) and [Dr. Jin Song DONG](https://www.comp.nus.edu.sg/~dongjs/) at NUS [PLSE Lab](https://nus-plse.github.io/). I also collaborate closely with [Dr. Yun LIN](http://linyun.info/).
* My research interest is machine learning, specifically AI for software engineering.

</div>
<div class="lang-zh" markdown="1">

# 👋 关于我 {#about-me-zh}
* 你好，我是晨彦！
* 我是新加坡国立大学（NUS）计算机科学系三年级博士生。
* 我的导师是 NUS [PLSE 实验室](https://nus-plse.github.io/)的[黄志勇博士](https://www.comp.nus.edu.sg/~huangzy/)和[董劲松博士](https://www.comp.nus.edu.sg/~dongjs/)，同时与[林云博士](http://linyun.info/)保持密切合作。
* 我的研究方向为机器学习，专注于 AI 赋能软件工程（AI4SE）。

</div>

<div class="lang-en">
<div class="internship-notice" style="background-color: #f0f7ff; border: 1.5px solid #4a90d9; border-radius: 8px; padding: 10px 16px; margin: 12px 0;">
  🔍 I am looking for <strong>internship opportunities</strong> in AI for coding starting from <strong>early 2027</strong> (outside mainland China). Feel free to <a href="mailto:chenyan@u.nus.edu">reach out</a>!
</div>
</div>
<div class="lang-zh">
<div class="internship-notice" style="background-color: #f0f7ff; border: 1.5px solid #4a90d9; border-radius: 8px; padding: 10px 16px; margin: 12px 0;">
  🔍 我正在寻找从 <strong>2027 年初</strong>开始的 AI 编程方向<strong>实习机会</strong>（中国大陆以外地区）。欢迎<a href="mailto:chenyan@u.nus.edu">联系我</a>！
</div>
</div>

<span class='anchor' id='-news'></span>

<div class="lang-en" markdown="1">

# 🔥 News {#news-en}
- *2026.02*: &nbsp; 🎉🎉 Our paper *EditFlow: Benchmarking and Optimizing Code Edit Recommendation Systems via Reconstruction of Developer Flows* has been accepted by OOPSLA'26.
- *2025.09*: &nbsp; 🎉🎉 Our paper *Learning Project-wise Subsequent Code Edits via Interleaving Neural-based Induction and Tool-based Deduction* has been accepted by ASE'25.
- *2024.12*: &nbsp; 🎉🎉 I passed the qualifying examination.
- *2024.03*: &nbsp; 🎉🎉 Our paper *CoEdPilot: Recommending Code Edits with Learned Prior Edit Relevance, Project-wise Awareness, and Interactive Nature* has been accepted by ISSTA'24.

</div>
<div class="lang-zh" markdown="1">

# 🔥 动态 {#news-zh}
- *2026.02*: &nbsp; 🎉🎉 我们的论文 *EditFlow: Benchmarking and Optimizing Code Edit Recommendation Systems via Reconstruction of Developer Flows* 被 OOPSLA'26 接收。
- *2025.09*: &nbsp; 🎉🎉 我们的论文 *Learning Project-wise Subsequent Code Edits via Interleaving Neural-based Induction and Tool-based Deduction* 被 ASE'25 接收。
- *2024.12*: &nbsp; 🎉🎉 我通过了资格考试。
- *2024.03*: &nbsp; 🎉🎉 我们的论文 *CoEdPilot: Recommending Code Edits with Learned Prior Edit Relevance, Project-wise Awareness, and Interactive Nature* 被 ISSTA'24 接收。

</div>

<style>
#pub-switch { display:inline-flex; border-radius:999px; background:#e0e0e0; padding:3px; font-size:0.85em; user-select:none; }
#pub-switch span { padding:4px 14px; border-radius:999px; cursor:pointer; font-weight:500; transition:background 0.2s, color 0.2s, box-shadow 0.2s; background:transparent; color:#888; }
#pub-switch span.pub-active { background:#fff; color:#333; box-shadow:0 1px 3px rgba(0,0,0,0.15); }
html[data-theme="dark"] #pub-switch { background:#3a3a3a; }
html[data-theme="dark"] #pub-switch span { color:#aaa; }
html[data-theme="dark"] #pub-switch span.pub-active { background:#555; color:#eee; box-shadow:0 1px 3px rgba(0,0,0,0.4); }
</style>

<span class='anchor' id='-publications'></span>
<div style="display:flex; align-items:center; justify-content:space-between; margin-top:1em;">
  <h1 style="margin:0;">📝 <span class="lang-en">Publications</span><span class="lang-zh">发表论文</span></h1>
  <div id="pub-switch">
    <span id="pub-opt-featured" class="pub-active" onclick="togglePubs(false)"><span class="lang-en">Featured</span><span class="lang-zh">精选</span></span>
    <span id="pub-opt-all" onclick="togglePubs(true)"><span class="lang-en">All</span><span class="lang-zh">全部</span></span>
  </div>
</div>
(<small><sup>#</sup> <span class="lang-en">refers to equal contribution</span><span class="lang-zh">表示同等贡献</span>, <sup>*</sup> <span class="lang-en">refers to corresponding author</span><span class="lang-zh">表示通讯作者</span></small>)

<div class="non-first-author" style="display:none">
<ul>
<li>Liu J, Lin Y<sup>*</sup>, <strong>Liu C</strong>, Qian Y, Liu Y, Chang J, Zhang W, Huang L. IssueExec: A Test-Driven Approach for Localizing Software Engineering Issues[C]//Proceedings of the 2026 ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA). ACM, 2026.</li>
<li>Qi B, Lin Y<sup>*</sup>, Weng X, Huang Y, <strong>Liu C</strong>, Sun H, Jin Z, Dong JS. Generating Project-Specific Test Cases with Requirement Validation Intention[C]//Proceedings of the 2026 ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA). ACM, 2026.
<a href='https://arxiv.org/pdf/2507.20619'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
<li>Qi B, Lin Y<sup>*</sup>, Weng X, <strong>Liu C</strong>, Sun H, Fraser G, Dong JS. Generalizing Test Cases for Comprehensive Test Scenario Coverage[C]//FSE 2026-2026 ACM International Conference on the Foundations of Software Engineering. ACM, 2026.
<a href='https://arxiv.org/pdf/2604.21771'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
</ul>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">OOPSLA'26</div><img src='images/OOPSLA26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	**Liu C**, Lin Y<sup>*</sup>, Chang J, Liu J, Qi B, Jiang B, Huang Z, Dong JS. EditFlow: Benchmarking and Optimizing Code Edit Recommendation Systems via Reconstruction of Developer Flows[J]. Proc. ACM Program. Lang., 10, OOPSLA1, Article 141 (April 2026), 28 pages.
<a href='https://sites.google.com/view/editflow'><i class="fa fa-home"></i>[Homepage]</a>
<a href='https://arxiv.org/pdf/2602.21697'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/code-philia/EditFlow'><i class="fab fa-github"></i>[GitHub]</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASE'25</div><img src='images/ASE25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	**Liu C**, Lin Y<sup>*</sup>, Huang Y, Chang J, Qi B, Jiang B, Huang Z, Dong JS. Learning Project-wise Subsequent Code Edits via Interleaving Neural-based Induction and Tool-based Deduction[C]//2025 40th IEEE/ACM International Conference on Automated Software Engineering (ASE). IEEE, 2025: 1377-1389.
<a href='https://sites.google.com/view/code-trace/homepage'><i class="fa fa-home"></i>[Homepage]</a>
<a href='https://arxiv.org/pdf/2604.12220'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/code-philia/TRACE'><i class="fab fa-github"></i>[GitHub]</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISSTA'24</div><img src='images/ISSTA24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	**Liu C**<sup>#</sup>, Cai Y<sup>#</sup>, Lin Y<sup>*</sup>, Huang Y, Pei Y, Jiang B, Yang P, Dong JS, Mei H. CoEdPilot: Recommending Code Edits with Learned Prior Edit Relevance, Project-wise Awareness, and Interactive Nature[C]//Proceedings of the 33rd ACM SIG-
SOFT International Symposium on Software Testing and Analysis. 2024: 466-478
<a href='https://sites.google.com/view/coedpilot/home'><i class="fa fa-home"></i>[Homepage]</a>
<a href='https://arxiv.org/pdf/2408.01733'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/code-philia/CoEdPilot'><i class="fab fa-github"></i>[GitHub]</a>

</div>
</div>

<div class="non-first-author" style="display:none">
<ul>
<li>Nie H, Wang W<sup>*</sup>, Dai R, <strong>Liu C</strong>, Wang Z, Xu P. Multi-Hop D2D Cluster Formation and Resource Allocation for Scalable Video Multicast[C]//ISPA 2024-2024 IEEE International Symposium on Parallel and Distributed Processing with Applications. IEEE, 2024.
<a href='https://ieeexplore.ieee.org/document/10885132'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
<li>Cai Y, Lin Y<sup>*</sup>, <strong>Liu C</strong>, Wu J, Zhang Y, Liu Y, Gong Y, Dong JS. On-the-Fly Adapting Code Summarization on Trainable Cost-Effective Language Models[J]. Advances in Neural Information Processing Systems, 2023, 36.
<a href='https://sites.google.com/view/adacom23/home'><i class="fa fa-home"></i>[Homepage]</a>
<a href='https://proceedings.neurips.cc/paper_files/paper/2023/file/b16e6de5fbbdcb2df237aa66b302bc17-Paper-Conference.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
<li><strong>Liu C</strong>, Wang W<sup>*</sup>, Dai R, Nie H, Xu P. A Real-Time Scalable Video Distribution Strategy Based on Dynamic Coalition and D2D Broadcast[C]//GLOBECOM 2022-2022 IEEE Global Communications Conference. IEEE, 2022: 19-24.
<a href='https://ieeexplore.ieee.org/document/10001625'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
</ul>
</div>

<script>
function togglePubs(showAll) {
  document.querySelectorAll('.non-first-author').forEach(function(el) {
    el.style.display = showAll ? 'block' : 'none';
  });
  document.querySelectorAll('.paper-box-image').forEach(function(el) {
    el.style.display = showAll ? 'none' : '';
  });
  document.querySelectorAll('.paper-box-text').forEach(function(el) {
    el.style.maxWidth = showAll ? '100%' : '';
    el.style.paddingLeft = showAll ? '0' : '';
  });
  document.querySelectorAll('.paper-box').forEach(function(el) {
    el.style.padding = showAll ? '0' : '';
    el.style.margin = showAll ? '0' : '';
    el.style.borderBottom = showAll ? 'none' : '';
    el.style.display = showAll ? 'block' : '';
  });
  document.getElementById('pub-opt-featured').classList.toggle('pub-active', !showAll);
  document.getElementById('pub-opt-all').classList.toggle('pub-active', showAll);
}
</script>

<span class='anchor' id='-educations'></span>

<div class="lang-en" markdown="1">

# 📖 Educations {#educations-en}
- *2023.08 - Present*, Ph.D. in Computer Science, National University of Singapore (NUS).
- *2021.08 - 2023.03*, M.S. in Computer Science, National University of Singapore (NUS).
- *2017.09 - 2021.06*, B.S. in Computer Science, Huazhong University of Science and Technology (HUST).

</div>
<div class="lang-zh" markdown="1">

# 📖 教育经历 {#educations-zh}
- *2023.08 - 至今*，博士，计算机科学，新加坡国立大学（NUS）。
- *2021.08 - 2023.03*，硕士，计算机科学，新加坡国立大学（NUS）。
- *2017.09 - 2021.06*，学士，计算机科学，华中科技大学（HUST）。

</div>

<span class='anchor' id='-internships'></span>

<div class="lang-en" markdown="1">

# 👨‍💻 Internships {#internships-en}
- *2025.01 - 2025.08*, Trae, ByteDance, Shenzhen, China.

</div>
<div class="lang-zh" markdown="1">

# 👨‍💻 实习经历 {#internships-zh}
- *2025.01 - 2025.08*，Trae，字节跳动，中国深圳。

</div>

<span class='anchor' id='-honors-and-awards'></span>

<div class="lang-en" markdown="1">

# 🎖 Honors and Awards {#honors-en}
- *2025.12* Research Achievement Award, NUS.
- *2024.11* Second Prize, 3rd/74 in Prototype System Competition for Software Research Achievements, China Computer Federation (CCF).
- *2024.08* Research Achievement Award, NUS.
- *2021.06* Outstanding Undergraduate Student, HUST.

</div>
<div class="lang-zh" markdown="1">

# 🎖 荣誉 {#honors-zh}
- *2025.12* NUS 科研成就奖。
- *2024.11* 中国计算机学会（CCF）软件工程研究成果原型系统大赛二等奖（74 支参赛队伍第 3 名）。
- *2024.08* NUS 科研成就奖。
- *2021.06* 华中科技大学优秀本科毕业生。

</div>

<span class='anchor' id='-teaching'></span>

<div class="lang-en" markdown="1">

# 👨‍🏫 Teaching {#teaching-en}
- *2026 Spring*, Teaching Assistant, CS4211 Formal Methods for Software Engineering, NUS.
- *2024 Fall*, Teaching Assistant, CS5228 Knowledge Discovery and Data Mining, NUS.
- *2024 Spring*, Teaching Assistant, CS4248 Natural Language Processing, NUS.

</div>
<div class="lang-zh" markdown="1">

# 👨‍🏫 教学经历 {#teaching-zh}
- *2026 春*，助教，CS4211 软件工程形式化方法，NUS。
- *2024 秋*，助教，CS5228 知识发现与数据挖掘，NUS。
- *2024 春*，助教，CS4248 自然语言处理，NUS。

</div>

<span class='anchor' id='-patent'></span>

<div class="lang-en" markdown="1">

# 🏷 Patent {#patent-en}
- *2025.08* Method, System, Apparatus, and Computer-Readable Storage Medium for Constructing Code Editing Datasets. China Invention Patent, Publication No. CN121070316A
- *2025.08* Method, System, Apparatus, and Computer-Readable Storage Medium for Determining Code Editing Recommendations. China Invention Patent, Publication No. CN121029146A.
- *2024.05* Method, System, Apparatus, and Computer-Readable Storage Medium for Code Editing. China Invention Patent, Publication No. CN119088381A.

</div>
<div class="lang-zh" markdown="1">

# 🏷 专利 {#patent-zh}
- *2025.08* 代码编辑数据集的构建方法、 装置、 设备、 介质、 产品。中国发明专利，公告号 CN121070316A。
- *2025.08* 代码编辑推荐确定方法、 装置、 电子设备以及存储介质。中国发明专利，公告号 CN121029146A。
- *2024.05* 用于代码编辑的方法、 装置、 设备和存储介质。中国发明专利，公告号 CN119088381A。

</div>

<span class='anchor' id='-invited-talks'></span>

<div class="lang-en" markdown="1">

# 💬 Invited Talks {#talks-en}
- *2024.12*, Workshop on LLM-based Code Agent, International Conference on Distributed Artificial Intelligence, Singapore.

</div>
<div class="lang-zh" markdown="1">

# 💬 受邀演讲 {#talks-zh}
- *2024.12*，基于大模型的代码智能体研讨会，分布式人工智能国际会议，新加坡。

</div>
