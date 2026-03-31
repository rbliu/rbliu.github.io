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
        <dd class="meta-line">Binyang Liu / 刘滨阳</dd>
      </div>
      <div class="meta-list__item">
        <dd class="meta-line">{{ site.author.title }}</dd>
      </div>
      <div class="meta-list__item">
        <dd class="meta-line">
          <span class="meta-icon" aria-hidden="true">
            <svg viewBox="0 0 24 24" role="img">
              <path d="M12 2.75a6.75 6.75 0 0 0-6.75 6.75c0 4.65 5.22 10.75 6.75 12.42 1.53-1.67 6.75-7.77 6.75-12.42A6.75 6.75 0 0 0 12 2.75Zm0 9.25a2.5 2.5 0 1 1 0-5 2.5 2.5 0 0 1 0 5Z"/>
            </svg>
          </span>
          <span>{{ site.author.location }}</span>
        </dd>
      </div>
      <div class="meta-list__item">
        <dd class="meta-line">
          <span class="meta-icon" aria-hidden="true">
            <svg viewBox="0 0 24 24" role="img">
              <path d="M3 5.75A2.75 2.75 0 0 1 5.75 3h12.5A2.75 2.75 0 0 1 21 5.75v12.5A2.75 2.75 0 0 1 18.25 21H5.75A2.75 2.75 0 0 1 3 18.25Zm2.2.25 6.8 5.1L18.8 6Zm13.8 1.25-6.4 4.8a1 1 0 0 1-1.2 0L5 7.25v11a.75.75 0 0 0 .75.75h12.5a.75.75 0 0 0 .75-.75Z"/>
            </svg>
          </span>
          <span>byliu.AT.pmo.ac.cn</span>
        </dd>
      </div>
      <div class="meta-list__item">
        <dd class="meta-line">
          <span class="meta-icon" aria-hidden="true">
            <svg viewBox="0 0 24 24" role="img">
              <path d="m12 3 9 4.5-9 4.5-9-4.5Zm-5.5 8.8V15c0 1.98 2.46 3.5 5.5 3.5s5.5-1.52 5.5-3.5v-3.2l-5.05 2.52a1 1 0 0 1-.9 0Zm11.75-.52 1.75-.88v5.85a1 1 0 1 1-2 0v-4.97Z"/>
            </svg>
          </span>
          <a href="{{ site.author.scholar }}">Google Scholar</a>
        </dd>
      </div>
      <div class="meta-list__item">
        <dd class="meta-line">
          <span class="meta-icon" aria-hidden="true">
            <svg viewBox="0 0 24 24" role="img">
              <path d="M12 2.5a9.75 9.75 0 0 0-3.08 19c.49.09.67-.21.67-.48v-1.7c-2.73.6-3.3-1.16-3.3-1.16a2.6 2.6 0 0 0-1.09-1.43c-.89-.61.07-.6.07-.6a2.05 2.05 0 0 1 1.49 1 2.08 2.08 0 0 0 2.84.81 2.08 2.08 0 0 1 .62-1.31c-2.18-.25-4.47-1.09-4.47-4.84a3.78 3.78 0 0 1 1-2.63 3.52 3.52 0 0 1 .1-2.59s.82-.26 2.68 1a9.2 9.2 0 0 1 4.88 0c1.86-1.26 2.68-1 2.68-1a3.52 3.52 0 0 1 .1 2.59 3.78 3.78 0 0 1 1 2.63c0 3.76-2.29 4.59-4.48 4.84a2.33 2.33 0 0 1 .67 1.81v2.69c0 .27.18.58.68.48A9.75 9.75 0 0 0 12 2.5"/>
            </svg>
          </span>
          <a href="https://github.com/{{ site.author.github }}">github.com/{{ site.author.github }}</a>
        </dd>
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
          <li>Astronomical data processing pipeline development.</li>
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
