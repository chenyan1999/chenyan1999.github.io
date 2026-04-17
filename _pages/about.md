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

# 👋 About me
* Hello, I'm Chenyan!
* I am a 3rd year PhD candidate at the National University of Singapore (NUS), Singapore. 
* I am supervised by [Dr. Yun LIN](http://linyun.info/), [Dr. ZhiYong HUANG](https://www.comp.nus.edu.sg/~huangzy/) and [Dr. Jin Song DONG](https://www.comp.nus.edu.sg/~dongjs/) in the [PLSE Lab](https://nus-plse.github.io/). 
* My research interest is machine learning, specifically AI for software engineering.

<div class="internship-notice" style="background-color: #f0f7ff; border: 1.5px solid #4a90d9; border-radius: 8px; padding: 10px 16px; margin: 12px 0;">
  🔍 I am looking for <strong>internship opportunities</strong> in AI for coding starting from <strong>early 2027</strong> (outside mainland China). Feel free to <a href="mailto:chenyan@u.nus.edu">reach out</a>!
</div>

# 🔥 News
- *2026.02*: &nbsp; 🎉🎉 Our paper *EditFlow: Benchmarking and Optimizing Code Edit Recommendation Systems via Reconstruction of Developer Flows* has been accepted by OOPSLA'26.
- *2025.09*: &nbsp; 🎉🎉 Our paper *Learning Project-wise Subsequent Code Edits via Interleaving Neural-based Induction and Tool-based Deduction* has been accepted by ASE'25.
- *2024.12*: &nbsp; 🎉🎉 I passed the qualifying examination.
- *2024.03*: &nbsp; 🎉🎉 Our paper *CoEdPilot: Recommending Code Edits with Learned Prior Edit Relevance, Project-wise Awareness, and Interactive Nature* has been accepted by ISSTA'24.

<style>
#pub-switch { display:inline-flex; border-radius:999px; background:#e0e0e0; padding:3px; font-size:0.85em; user-select:none; }
#pub-switch span { padding:4px 14px; border-radius:999px; cursor:pointer; font-weight:500; transition:background 0.2s, color 0.2s, box-shadow 0.2s; background:transparent; color:#888; }
#pub-switch span.pub-active { background:#fff; color:#333; box-shadow:0 1px 3px rgba(0,0,0,0.15); }
html[data-theme="dark"] #pub-switch { background:#3a3a3a; }
html[data-theme="dark"] #pub-switch span { color:#aaa; }
html[data-theme="dark"] #pub-switch span.pub-active { background:#555; color:#eee; box-shadow:0 1px 3px rgba(0,0,0,0.4); }
</style>

<div style="display:flex; align-items:center; justify-content:space-between; margin-top:1em;">
  <h1 style="margin:0;">📝 Publications</h1>
  <div id="pub-switch">
    <span id="pub-opt-featured" class="pub-active" onclick="togglePubs(false)">Featured</span>
    <span id="pub-opt-all" onclick="togglePubs(true)">All</span>
  </div>
</div>
(<small><sup>#</sup> refers to equal contribution, <sup>*</sup> refers to corresponding author</small>)

<div class="non-first-author" style="display:none">
<ul>
<li>Liu J, Lin Y, <strong>Liu C</strong>, Qi Y, et al. IssueExec: A Test-Driven Approach for Localizing Software Engineering Issues[C]//Proceedings of the 2026 ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA). ACM, 2026.</li>
<li>Qi B, Lin Y, Weng X, Huang Y, <strong>Liu C</strong>, et al. Generating Project-Specific Test Cases with Requirement Validation Intention[C]//Proceedings of the 2026 ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA). ACM, 2026.
<a href='https://arxiv.org/pdf/2507.20619'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
<li>Qi B, Lin Y, Weng X, <strong>Liu C</strong>, et al. Generalizing Test Cases for Comprehensive Test Scenario Coverage[C]//FSE 2026-2026 ACM International Conference on the Foundations of Software Engineering. ACM, 2026.</li>
</ul>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">OOPSLA'26</div><img src='images/OOPSLA26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	**Liu C**, Lin Y<sup>*</sup>, Chang J, Liu J, et al. EditFlow: Benchmarking and Optimizing Code Edit Recommendation Systems via Reconstruction of Developer Flows[J]. Proc. ACM Program. Lang., 10, OOPSLA1, Article 141 (April 2026), 28 pages.
<a href='https://sites.google.com/view/editflow'><i class="fa fa-home"></i>[Homepage]</a>
<a href='https://arxiv.org/pdf/2602.21697'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/code-philia/EditFlow'><i class="fab fa-github"></i>[GitHub]</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASE'25</div><img src='images/ASE25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	**Liu C**, Lin Y<sup>*</sup>, Huang Y, et al. Learning Project-wise Subsequent Code Edits via Interleaving Neural-based Induction and Tool-based Deduction[C]//2025 40th IEEE/ACM International Conference on Automated Software Engineering (ASE). IEEE, 2025: 1377-1389.
<a href='https://sites.google.com/view/code-trace/homepage'><i class="fa fa-home"></i>[Homepage]</a>
<a href='file/TRACE.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/code-philia/TRACE'><i class="fab fa-github"></i>[GitHub]</a> 

</div>
</div>

<div class="non-first-author" style="display:none">
<ul>
<li>Huang Y H, <strong>Liu C Y</strong>, Lin Y, et al. CoEdPilot: Interactively Recommending Project-Wise Code Edits[J]. Journal of Computer Science and Technology, 2025, 40(4): 980-992.</li>
</ul>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISSTA'24</div><img src='images/ISSTA24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	**Liu C**<sup>#</sup>, Cai Y<sup>#</sup>, Lin Y<sup>*</sup>, Huang Y, et al. CoEdPilot: Recommending Code Edits with Learned Prior Edit Relevance, Project-wise Awareness, and Interactive Nature[C]//Proceedings of the 33rd ACM SIG-
SOFT International Symposium on Software Testing and Analysis. 2024: 466-478
<a href='https://sites.google.com/view/coedpilot/home'><i class="fa fa-home"></i>[Homepage]</a>
<a href='https://arxiv.org/pdf/2408.01733'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/code-philia/CoEdPilot'><i class="fab fa-github"></i>[GitHub]</a>

</div>
</div>

<div class="non-first-author" style="display:none">
<ul>
<li>Nie H, Wang W<sup>*</sup>, Dai R, <strong>Liu C</strong>, et al. Multi-Hop D2D Cluster Formation and Resource Allocation for Scalable Video Multicast[C]//ISPA 2024-2024 IEEE International Symposium on Parallel and Distributed Processing with Applications. IEEE, 2024.
<a href='https://ieeexplore.ieee.org/document/10885132'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
<li>Cai Y, Lin Y<sup>*</sup>, <strong>Liu C</strong>, et al. On-the-Fly Adapting Code Summarization on Trainable Cost-Effective Language Models[J]. Advances in Neural Information Processing Systems, 2023, 36.
<a href='https://sites.google.com/view/adacom23/home'><i class="fa fa-home"></i>[Homepage]</a>
<a href='https://proceedings.neurips.cc/paper_files/paper/2023/file/b16e6de5fbbdcb2df237aa66b302bc17-Paper-Conference.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a></li>
<li><strong>Liu C</strong>, Wang W<sup>*</sup>, Dai R, et al. A Real-Time Scalable Video Distribution Strategy Based on Dynamic Coalition and D2D Broadcast[C]//GLOBECOM 2022-2022 IEEE Global Communications Conference. IEEE, 2022: 19-24.
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

# 📖 Educations
- *2023.08 - Present*, Ph.D. in Computer Science, National University of Singapore (NUS).
- *2021.08 - 2023.03*, M.S. in Computer Science, National University of Singapore (NUS).
- *2017.09 - 2021.06*, B.S. in Computer Science, Huazhong University of Science and Technology (HUST).

# 👨‍💻 Internships
- *2025.01 - 2025.08*, Trae, ByteDance, Shenzhen, China.

# 🎖 Honors and Awards
- *2025.12* Research Achievement Award, NUS.
- *2024.11* 3rd/74 in Prototype System Competition for Software Research Achievements, China Computer Federation (CCF).
- *2024.08* Research Achievement Award, NUS.
- *2021.06* Outstanding Undergraduate Student, HUST.

# 👨‍🏫 Teaching
- *2024 Fall*, Teaching Assistant, CS5228 Knowledge Discovery and Data Mining, NUS.
- *2024 Spring*, Teaching Assistant, CS4248 Natural Language Processing, NUS.

# 🏷 Patent
- *2025.08* Method, System, Apparatus, and Computer-Readable Storage Medium for Constructing Code Editing Datasets. China Invention Patent, Publication No. CN121070316A
- *2025.08* Method, System, Apparatus, and Computer-Readable Storage Medium for Determining Code Editing Recommendations. China Invention Patent, Publication No. CN121029146A.
- *2024.05* Method, System, Apparatus, and Computer-Readable Storage Medium for Code Editing. China Invention Patent, Publication No. CN119088381A.

# 💬 Invited Talks
- *2024.12*, Workshop on LLM-based Code Agent, International Conference on Distributed Artificial Intelligence, Singapore.
