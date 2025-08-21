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
/* 全文链接：无下划线、蓝色（暗色自动变浅蓝） */
.page__content a { text-decoration: none !important; }
.page__content a { color: #2563eb !important; }
.page__content a:hover { color: #1d4ed8 !important; }
@media (prefers-color-scheme: dark){
  .page__content a { color: #93c5fd !important; }
  .page__content a:hover { color: #bfdbfe !important; }
}

/* Selected Work 布局与排版 */
.work-list { display: flex; flex-direction: column; gap: 1.25rem; margin-top: .75rem; }
.work-item  { display: flex; gap: 1rem; align-items: flex-start; padding: .75rem 0; border-bottom: 1px solid rgba(0,0,0,.08); }
.work-item:last-child { border-bottom: none; }
.work-thumb { width: 220px; max-width: 40vw; border-radius: .5rem; overflow: hidden; flex-shrink: 0; }
.work-thumb img { width: 100%; height: auto; display: block; }

.work-meta h3 { margin: 0 0 .35rem 0; line-height: 1.35; font-weight: 700; }
/* 作者行：与标题同色，不用灰色；略小一号以区分层级 */
.work-authors { margin: 0 0 .3rem 0; font-size: 0.95rem; color: inherit; }
@media (prefers-color-scheme: dark){
  .work-authors { color: inherit; } /* 明确继承，确保与标题同色 */
}

/* 通用按钮基础（填充色 + 白字） */
.work-actions .btn {
  margin-right: .4rem; border-radius: 9999px; padding: .35rem .8rem;
  font-size: .88rem; text-decoration: none; font-weight: 600; display:inline-block;
  line-height: 1.2; color: #fff !important; border: 1px solid transparent;
}
.work-actions .btn:last-child { margin-right: 0; }

/* 三类按钮的填充色 */
.btn-arxiv { background: #dc2626 !important; border-color: #dc2626 !important; }   /* red-600 */
.btn-ieee  { background: #2563eb !important; border-color: #2563eb !important; }  /* blue-600 */
.btn-github{ background: #111 !important;    border-color: #111 !important; }     /* near-black */

/* hover 略微提亮 */
.btn-arxiv:hover { background: #b91c1c !important; border-color: #b91c1c !important; }
.btn-ieee:hover  { background: #1d4ed8 !important; border-color: #1d4ed8 !important; }
.btn-github:hover{ background: #000 !important;    border-color: #000 !important; }
</style>


I am an M.S. student in [Electrical and Computer Engineering](https://ece.ucsd.edu/) at [UC San Diego](https://ucsd.edu/). I received my B.S. in [Mathematics and Information Engineering](https://www.ie.cuhk.edu.hk/programmes/bsc-in-mieg/) from [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/chinese/index.html). During my undergraduate time, I worked as a research assistant in CUHK’s [Advanced Wireless Systems Group](https://wireless.ie.cuhk.edu.hk/) under the guidance of [Prof. Soung Chang Liew](https://www.ie.cuhk.edu.hk/faculty/liew-soung-chang/) and [Dr. Yuyang Du](https://yuyangdu01.github.io/), conducting research in Generative AI and AI for Network. I also collaborated with [Prof. Rosanna Yuen-Yan Chan](https://www.ie.cuhk.edu.hk/faculty/chan-yuen-yan-rosanna/) for my undergraduate dissertation research. Prior to that, I worked with [Prof. Min-Te (Peter) Sun](https://wasn.csie.ncu.edu.tw/advisor) at National Central University and [Prof. Jun-Wei Hsieh](https://aicvlab2019.wordpress.com/) at National Yang Ming Chiao Tung University, Taiwan. In industry, I served as a Machine Learning Application Intern at Deloitte Hong Kong and as Operations Director at Intell-Pro Global, an AI startup that received significant investment from HK CityU Tech300 Entrepreneurship program and TSSSU award.

## Research Interests

My research focuses on large language and vision-language models (LLMs/VLMs) and machine learning (ML) for systems. 

- Accelerated inference and generation for LLMs and multimodal models: efficient decoding (e.g., speculative and batched decoding), KV-cache management, quantization and distillation, routing/MoE scheduling, and systems-level optimizations that improve end-to-end latency–throughput–quality trade-offs under practical constraints.

- Multimodal reasoning and efficient perception with vision-language models: robust grounding and alignment, retrieval-augmented perception, parameter-efficient adaptation for resource-limited settings, and evaluation protocols that stress long-context understanding and cross-modal consistency.

- Machine learning for systems: leveraging ML to improve the correctness, efficiency, and automation of computing infrastructures. This includes areas such as network intelligence and topology-aware optimization, AI agents for managing complex system pipelines, and LLM-driven design automation in domains like electronic design automation (EDA).

I am also interested in applications of LLMs in education, engineering, and scientific discovery.

## Selected Work

<div class="work-list">

  <!-- VeriRAG -->
  <div class="work-item">
    <div class="work-thumb">
      <img src="/images/1.jpg" alt="VeriRAG teaser">
    </div>
    <div class="work-meta">
      <h3>VeriRAG: A Retrieval-Augmented Framework for Automated RTL Testability Repair</h3>
      <div class="work-authors"><strong>H. Qi</strong>, Y. Du, L. Zhang, S. C. Liew, K. Chen, Yi. Du</div>
      <div class="work-actions">
        <a href="https://arxiv.org/abs/2507.15664" class="btn btn-arxiv" target="_blank" rel="noopener">ArXiv</a>
        <a href="https://github.com/yuyangdu01/LLM4DFT" class="btn btn-github" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
  </div>

  <!-- ABA-RAG -->
  <div class="work-item">
    <div class="work-thumb">
      <img src="/images/2.jpg" alt="ABA-RAG teaser">
    </div>
    <div class="work-meta">
      <h3>Transforming ABA Therapy: An IoT-Guided, Retrieval-Augmented LLM Framework</h3>
      <div class="work-authors"><strong>H. Qi</strong>, C. H. Sin, Rosanna Y. Y. Chan, Victor C. M. Wong</div>
      <div class="work-actions">
        <a href="https://ieeexplore.ieee.org/document/11129621" class="btn btn-ieee" target="_blank" rel="noopener">IEEE Xplore</a>
        <a href="https://github.com/1314spb/IoT-RAG-ABA" class="btn btn-github" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
  </div>

</div>
