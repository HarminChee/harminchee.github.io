---
layout: single
title: "Misc."
permalink: /misc/
author_profile: true
---

<style>
/* 链接：无下划线、蓝色（暗色自动变浅蓝） */
.page__content a { text-decoration: none !important; }
.page__content a { color: #2563eb !important; }
.page__content a:hover { color: #1d4ed8 !important; }
@media (prefers-color-scheme: dark){
  .page__content a { color: #93c5fd !important; }
  .page__content a:hover { color: #bfdbfe !important; }
}

/* Section 间距与排版 */
.misc-intro p { margin-bottom: .5rem; }

/* Follow 按钮 */
.follow-row { margin-top: .5rem; margin-bottom: .5rem; }
.follow-btn {
  display:inline-block; padding:.35rem .75rem; border-radius:9999px;
  border:1px solid #111; color:#111; background:transparent; text-decoration:none; font-weight:600;
}
.follow-btn:hover { background:#111; color:#fff; }
@media (prefers-color-scheme: dark){
  .follow-btn { border-color:#e5e7eb; color:#e5e7eb; }
  .follow-btn:hover { background:#e5e7eb; color:#111; }
}

/* -------- 照片滑动相册 -------- */
.photo-slider { display:flex; gap:.5rem; overflow-x:auto; scroll-snap-type:x mandatory; padding:.5rem 0; }
.photo-slider img { height:220px; object-fit:cover; border-radius:.5rem; flex-shrink:0; scroll-snap-align:start; }

/* 分割线 */
.section-divider { border-top:1px solid rgba(0,0,0,.15); margin:1.25rem 0; }
@media (prefers-color-scheme: dark){
  .section-divider { border-top:1px solid rgba(255,255,255,.25); }
}

/* Instagram 单帖嵌入：靠左 */
.ig-post { margin-top:.75rem; max-width:540px; margin-left:0; margin-right:0; }
</style>

## Beyond Research

<div class="misc-intro">
<p>Outside research, I enjoy <strong>photography</strong>, <strong>fitness</strong>, <strong>classical painting</strong>, <strong>skiing</strong>, <strong>heavy-loaded hiking</strong>, and <strong>cycling</strong>.</p>
</div>

<!-- 照片滑动栏 -->
<div class="photo-slider">
  <img src="/images/1.jpg" alt="photo 1">
  <img src="/images/2.jpg" alt="photo 2">
  <img src="/images/3.jpg" alt="photo 3">
  <img src="/images/4.jpg" alt="photo 4">
  <img src="/images/5.jpg" alt="photo 5">
  <img src="/images/6.jpg" alt="photo 6">
  <img src="/images/7.jpg" alt="photo 7">
  <img src="/images/8.jpg" alt="photo 8">
  <img src="/images/9.jpg" alt="photo 9">
  <img src="/images/10.jpg" alt="photo 10">
  <img src="/images/11.jpg" alt="photo 11">
  <img src="/images/12.jpg" alt="photo 12">
  <img src="/images/13.jpg" alt="photo 13">
</div>

<div class="section-divider"></div>

<p>I usually share photography and daily life on Instagram — feel free to follow!</p>
<div class="follow-row">
  <a class="follow-btn" href="https://www.instagram.com/harminchee/" target="_blank" rel="noopener">Follow @harminchee</a>
</div>

<!-- Instagram主页嵌入 (靠左) -->
<div class="ig-post">
  <blockquote class="instagram-media"
              data-instgrm-permalink="https://www.instagram.com/p/DHLoA_spOzS/?img_index=1"
              data-instgrm-version="14"
              style="background:#fff; border:0; border-radius:12px; box-shadow:0 0 0 1px rgba(0,0,0,.1),0 1px 10px rgba(0,0,0,.1);
                     margin:0; max-width:540px; width:100%;"></blockquote>
</div>
<script async src="https://www.instagram.com/embed.js"></script>
