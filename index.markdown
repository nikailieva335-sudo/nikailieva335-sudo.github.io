---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
nav_order: 0
permalink: /
---

<div class="profile-hero">
  <img src="/images/IMG_5262.jpg" alt="Nika Ilieva">
  <div class="profile-text">
    <h1>Hi, I'm Nika!</h1>
    <p>Device designer and engineer developing solutions for Duke Health systems. Experienced in diagnosing client needs and translating into technical implementation and regulatory-aware product development.</p>
  </div>
</div>

<style>
.profile-hero {
  display: flex;
  align-items: center;
  gap: 2rem;
  margin: 1.5rem 0 2rem;
  flex-wrap: wrap;
}
.profile-hero img {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 4px;
  flex-shrink: 0;
}
.profile-text h1 {
  margin: 0 0 0.5rem;
}
.profile-text p {
  margin: 0;
  color: #ccc;
  line-height: 1.6;
}
</style>
