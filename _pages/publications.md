---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
/* ---------- Page-local styles (dark-mode friendly) ---------- */
.pubs {
  margin-top: .5rem;
  --text: #1f2937;       /* default text */
  --muted: #4b5563;      /* secondary text */
  --border: rgba(0,0,0,.12);
  --accent: #4f46e5;     /* indigo */
  --accent-hover: #4338ca;
  --on-accent: #ffffff;
}
@media (prefers-color-scheme: dark) {
  .pubs {
    --text: #e5e7eb;
    --muted: #cbd5e1;
    --border: rgba(255,255,255,.14);
    --accent: #a78bfa;       /* lighter indigo for dark */
    --accent-hover: #c4b5fd;
    --on-accent: #111827;
  }
}
.pubs .item{
  padding: .9rem 0;
  border-bottom: 1px solid var(--border);
}
.pubs .item:last-child{ border-bottom: none; }
.pubs .pub-title{
  margin: 0 0 .25rem 0;
  line-height: 1.35;
  font-weight: 700;
  color: var(--text);
}
.pubs .pub-authors{
  margin-bottom: .15rem;
  color: var(--text);          /* use primary color for readability in dark mode */
}
.pubs .pub-venue{
  color: var(--muted);
  font-style: italic;
}

/* “paper” pill button (nicer than plain links) */
.pubs .btn{
  display: inline-block;
  padding: .2rem .6rem;
  border-radius: 9999px;
  font-size: .9rem;
  line-height: 1.6;
  text-decoration: none;
  transition: background .15s ease, color .15s ease, border-color .15s ease;
}
.pubs .btn-paper{
  color: var(--accent);
  border: 1px solid var(--accent);
  background: transparent;
}
.pubs .btn-paper:hover{
  background: var(--accent);
  color: var(--on-accent);
  border-color: var(--accent-hover);
}
.pubs .btn + .btn{ margin-left: .35rem; }
</style>

<div class="pubs">

  <div class="item">
    <h3 class="pub-title">TopoEdge: An Edge-assisted LLM Framework for Automated SDN Configuration Generation</h3>
    <div class="pub-authors"><strong>Haomin Qi</strong>, Yuyang Du, Ziheng Kang, Yue Zhan, Soung Chang Liew</div>
    <div class="pub-venue"><em>Under review at IEEE Consumer Communications &amp; Networking Conference 2026 (IEEE CCNC ’26 Poster)</em></div>
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
