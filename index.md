---
layout: default
title: About
description: About Binyang Liu
nav_key: about
---

<section class="hero">
  <aside class="hero__aside panel">
    <div class="profile-photo-wrap">
      <img
        class="profile-photo"
        src="{{ '/assets/images/profile.jpg' | relative_url }}"
        alt="Binyang Liu standing in front of a telescope"
      >
    </div>
    <dl class="meta-list">
      <div class="meta-list__item">
        <dt class="meta-label">Name</dt>
        <dd>Binyang Liu / 刘滨阳</dd>
      </div>
      <div class="meta-list__item">
        <dt class="meta-label">Role</dt>
        <dd>{{ site.author.title }}</dd>
      </div>
      <div class="meta-list__item">
        <dt class="meta-label">Location</dt>
        <dd>{{ site.author.location }}</dd>
      </div>
      <div class="meta-list__item">
        <dt class="meta-label">Email</dt>
        <dd>byliu.AT.pmo.ac.cn</dd>
      </div>
      <div class="meta-list__item">
        <dt class="meta-label">Google Scholar</dt>
        <dd><a href="{{ site.author.scholar }}">Profile</a></dd>
      </div>
      <div class="meta-list__item">
        <dt class="meta-label">GitHub</dt>
        <dd><a href="https://github.com/{{ site.author.github }}">github.com/{{ site.author.github }}</a></dd>
      </div>
    </dl>
  </aside>

  <div class="hero__content panel">
    <span class="eyebrow">About</span>
    <p class="lead">
      Engineer at Purple Mountain Observatory, CAS. Based in Nanjing, China, I work at
      the intersection of observational astronomy, data-intensive research, and survey
      pipeline development.
    </p>

    <div class="content-stack">
      <div>
        <p class="content-heading">Research Interests</p>
        <ul>
          <li>Galaxy clusters and gravitational lensing.</li>
          <li>WFST data processing pipeline development.</li>
          <li>Asteroid detection and time-domain survey work.</li>
        </ul>
      </div>
    </div>

    <div class="hero__actions">
      <a class="button button--primary" href="{{ '/research/' | relative_url }}">View Research</a>
      <a class="button button--secondary" href="{{ '/cv/' | relative_url }}">Open CV</a>
    </div>
  </div>
</section>
