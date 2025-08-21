---
permalink: /
title: "Haomin Qi/ Harmin Chee"
author_profile: true
layout: single
redirect_from:
  - /about/
  - /about.html
---

<!-- Page-local styles -->
<style>
/* 链接无下划线，蓝色 */
.page__content a { text-decoration: none !important; }
.page__content a { color: #2563eb !important; }
.page__content a:hover { color: #1d4ed8 !important; }
@media (prefers-color-scheme: dark){
  .page__content a { color: #93c5fd !important; }
  .page__content a:hover { color: #bfdbfe !important; }
}

/* Selected Work */
.work-list { display: flex; flex-direction: column; gap: 1.25rem; margin-top: .75rem; }
.work-item  { display: flex; gap: 1rem; align-items: flex-start; padding: .75rem 0; border-bottom: 1px solid rgba(0,0,0,.08); }
.work-item:last-child { border-bottom: none; }
.work-thumb { width: 220px; max-width: 40vw; border-radius: .5rem; overflow: hidden; flex-shrink: 0; }
.work-thumb img { width: 100%; height: auto; display: block; }
.work-meta h3 { margin: 0 0 .35rem 0; line-height: 1.35; font-weight: 700; }
.work-authors { margin: 0 0 .3rem 0; font-size: 0.9rem; color: #374151; }
@media (prefers-color-scheme: dark){
  .work-authors { color: #d1d5db; }
  .work-venue { color: #cbd5e1; }
}

/* 通用按钮基础 */
.work-actions .btn { margin-right: .4rem; border-radius: 9999px; padding: .25rem .7rem; font-size: .85rem; text-decoration: none; font-weight: 500; display:inline-block; }
.work-actions .btn:last-child { margin-right: 0; }

/* 自定义按钮颜色 */
.btn-arxiv {
  color: #dc2626 !important; border: 1px solid #dc2626 !important; background: transparent !important;
}
.btn-arxiv:hover {
  background: #dc2626 !important; color: #fff !important;
}

.btn-ieee {
  color: #2563eb !important; border: 1px solid #2563eb !important; background: transparent !important;
}
.btn-ieee:hover {
  background: #2563eb !important; color: #fff !important;
}

.btn-github {
  color: #111 !important; border: 1px solid #111 !important; background: transparent !important;
}
.btn-github:hover {
  background: #111 !important; color: #fff !important;
}
</style>


I am an M.S. student in [Electrical and Computer Engineering](https://ece.ucsd.edu/) at [UC San Diego](https://ucsd.edu/). ...

## Research Interests
... （省略）

## Selected Work

<div class="work-list">

  <!-- VeriRAG -->
  <div class="work-item">
    <div class="work-thumb">
      <img src="/images/verirag.jpg" alt="VeriRAG teaser">
    </div>
    <div class="work-meta">
      <h3>VeriRAG: A Retrieval-Augmented Framework for Automated RTL Testability Repair</h3>
      <div class="work-authors"><strong>Haomin Qi</strong>, Yuyang Du, Lihao Zhang, Soung Chang Liew, Kexin Chen, Yining Du</div>
      <div class="work-actions">
        <a href="https://arxiv.org/abs/2507.15664" class="btn btn-arxiv" target="_blank" rel="noopener">ArXiv</a>
        <a href="https://github.com/yuyangdu01/LLM4DFT" class="btn btn-github" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
  </div>

  <!-- ABA-RAG -->
  <div class="work-item">
    <div class="work-thumb">
      <img src="/images/aba-rag.jpg" alt="ABA-RAG teaser">
    </div>
    <div class="work-meta">
      <h3>Transforming ABA Therapy: An IoT-Guided, Retrieval-Augmented LLM Framework</h3>
      <div class="work-authors"><strong>Haomin Qi</strong>, Chung-Ho Sin, Rosanna Yuen-Yan Chan, Victor Chun-Man Wong</div>
      <div class="work-actions">
        <a href="https://ieeexplore.ieee.org/document/11129621" class="btn btn-ieee" target="_blank" rel="noopener">IEEE Xplore</a>
        <a href="https://github.com/1314spb/IoT-RAG-ABA" class="btn btn-github" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
  </div>

</div>
