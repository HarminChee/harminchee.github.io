---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
/* ---------- Page-local styles: force high contrast in light mode, nice in dark mode ---------- */
.pubs { margin-top: .5rem; }

/* LIGHT mode (default) */
.pubs .pub-title      { margin: 0 0 .25rem 0; line-height: 1.35; font-weight: 700; color: #111 !important; }
.pubs .pub-authors    { margin-bottom: .15rem; color: #374151 !important; }   /* slate-700 */
.pubs .pub-venue      { color: #6b7280 !important; font-style: italic; }      /* slate-500 */
.pubs .item           { padding: .9rem 0; border-bottom: 1px solid rgba(0,0,0,.14); }
.pubs .item:last-child{ border-bottom: none; }

/* DARK mode overrides */
@media (prefers-color-scheme: dark) {
  .pubs .pub-title   { color: #e5e7eb !important; }  /* slate-200 */
  .pubs .pub-authors { color: #e5e7eb !important; }
  .pubs .pub-venue   { color: #cbd5e1 !important; }  /* slate-300 */
  .pubs .item        { border-bottom: 1px solid rgba(255,255,255,.18); }
}

/* “paper” pill button */
.pubs .btn{
  display:inline-block; padding:.2rem .6rem; border-radius:9999px; font-size:.9rem;
  line-height:1.6; text-decoration:none; transition:background .15s ease,color .15s ease,border-color .15s ease;
}
.pubs .btn-paper{ color:#4f46e5; border:1px solid #4f46e5; background:transparent; }
.pubs .btn-paper:hover{ background:#4f46e5; color:#fff; border-color:#4338ca; }
@media (prefers-color-scheme: dark){
  .pubs .btn-paper{ color:#a78bfa; border-color:#a78bfa; }
  .pubs .btn-paper:hover{ background:#a78bfa; color:#111827; border-color:#c4b5fd; }
}
.pubs .btn + .btn{ margin-left:.35rem; }
</style>

<div class="pubs">

  <div class="item">
    <h3 class="pub-title">TopoEdge: An Edge-assisted LLM Framework for Automated SDN Configuration Generation</h3>
    <div class="pub-authors"><strong>Haomin Qi</strong>, Yuyang Du, Ziheng Kang, Yue Zhan, Soung Chang Liew</div>
    <div class="pub-venue"><em>Under review at IEEE Consumer Communications &amp; Networking Conference 2026 (CCNC ’26 Poster)</em></div>
  </div>

  <div class="item">
    <h3 class="pub-title">VeriRAG: A Retrieval-Augmented Framework for Automated RTL Testability Repair</h3>
    <div class="pub-authors"><strong>Haomin Qi</strong>, Yuyang Du, Soung Chang Liew, Kexin Chen, Yining Du</div>
    <div class="pub-venue"><em>Under review at the 40th Annual AAAI Conference on Artificial Intelligence (AAAI ’26)</em></div>
    <div class="pub-links">
      <a class="btn btn-paper" href="https://arxiv.org/abs/2507.15664" target="_blank" rel="noopener">paper ↗</a>
    </div>
  </div>

  <div class="item">
    <h3 class="pub-title">Transforming ABA Therapy: An IoT-Guided, Retrieval-Augmented LLM Framework</h3>
    <div class="pub-authors"><strong>Haomin Qi</strong>, Chung-Ho Sin, Rosanna Yuen-Yan Chan, Victor Chun-Man Wong</div>
    <div class="pub-venue"><em>IEEE Access Journal (2025-30591)</em></div>
    <div class="pub-links">
      <a class="btn btn-paper" href="/files/ABA-RAG.pdf" target="_blank" rel="noopener">paper</a>
    </div>
  </div>

  <div class="item">
    <h3 class="pub-title">Hybrid and Unitary Fine-Tuning of LLMs: Methods and Benchmarking under Resource Constraints</h3>
    <div class="pub-authors"><strong>Haomin Qi</strong>, Zihan Dai, Chengbo Huang</div>
    <div class="pub-venue"><em>The Advances in Distributed Computing and Artificial Intelligence Journal (ADCAIJ)</em></div>
    <div class="pub-links">
      <a class="btn btn-paper" href="https://arxiv.org/abs/2507.18076" target="_blank" rel="noopener">paper ↗</a>
    </div>
  </div>

</div>
