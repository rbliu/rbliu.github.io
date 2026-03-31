---
layout: default
title: About
description: About Binyang Liu
nav_key: about
---

<section class="hero">
  <div class="hero__content panel">
    <span class="eyebrow">About</span>
    <h1>Binyang Liu</h1>
    <p>
      Engineer at Purple Mountain Observatory, CAS. Based in Nanjing, China, I work at
      the intersection of observational astronomy, data-intensive research, and survey
      pipeline development.
    </p>
    <div class="hero__actions">
      <a class="button button--primary" href="{{ '/research/' | relative_url }}">View Research</a>
      <a class="button button--secondary" href="{{ '/cv/' | relative_url }}">Open CV</a>
    </div>
  </div>

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
        <dd><a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></dd>
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
</section>

<section class="grid">
  <article class="section-card panel">
    <h2 class="section-title">Short Bio</h2>
    <p>
      I am an engineer at Purple Mountain Observatory, Chinese Academy of Sciences.
      My interests include galaxy clusters and gravitational lensing, development of
      the data processing pipeline for the Wide Field Survey Telescope (WFST), and
      asteroid detection and related survey applications.
    </p>
  </article>

  <article class="section-card panel">
    <h2 class="section-title">Research Interests</h2>
    <ul>
      <li>Galaxy clusters and gravitational lensing.</li>
      <li>WFST data processing pipeline development.</li>
      <li>Asteroid detection and time-domain survey work.</li>
    </ul>
  </article>

  <article class="section-card panel">
    <h2 class="section-title">Homepage Structure</h2>
    <p>
      This site uses a focused three-page structure: a brief personal introduction on
      the About page, a separate Research page for themes and projects, and a CV page
      with embedded PDF preview and download links.
    </p>
  </article>

  <article class="section-card panel">
    <h2 class="section-title">Links</h2>
    <div class="contact-grid">
      <a class="contact-card" href="mailto:{{ site.author.email }}">
        <span class="contact-card__icon" aria-hidden="true">
          <svg viewBox="0 0 24 24" role="img">
            <path d="M3 5.75A2.75 2.75 0 0 1 5.75 3h12.5A2.75 2.75 0 0 1 21 5.75v12.5A2.75 2.75 0 0 1 18.25 21H5.75A2.75 2.75 0 0 1 3 18.25Zm2.2.25 6.8 5.1L18.8 6Zm13.8 1.25-6.4 4.8a1 1 0 0 1-1.2 0L5 7.25v11a.75.75 0 0 0 .75.75h12.5a.75.75 0 0 0 .75-.75Z"/>
          </svg>
        </span>
        <span class="contact-card__body">
          <span class="contact-card__title">Email</span>
          <span class="contact-card__value">{{ site.author.email }}</span>
        </span>
      </a>

      <a class="contact-card" href="{{ site.author.scholar }}">
        <span class="contact-card__icon" aria-hidden="true">
          <svg viewBox="0 0 24 24" role="img">
            <path d="m12 3 9 4.5-9 4.5-9-4.5Zm-5.5 8.8V15c0 1.98 2.46 3.5 5.5 3.5s5.5-1.52 5.5-3.5v-3.2l-5.05 2.52a1 1 0 0 1-.9 0Zm11.75-.52 1.75-.88v5.85a1 1 0 1 1-2 0v-4.97Z"/>
          </svg>
        </span>
        <span class="contact-card__body">
          <span class="contact-card__title">Google Scholar</span>
          <span class="contact-card__value">Publications and citations</span>
        </span>
      </a>

      <a class="contact-card" href="https://github.com/{{ site.author.github }}">
        <span class="contact-card__icon" aria-hidden="true">
          <svg viewBox="0 0 24 24" role="img">
            <path d="M12 2.5a9.75 9.75 0 0 0-3.08 19c.49.09.67-.21.67-.48v-1.7c-2.73.6-3.3-1.16-3.3-1.16a2.6 2.6 0 0 0-1.09-1.43c-.89-.61.07-.6.07-.6a2.05 2.05 0 0 1 1.49 1 2.08 2.08 0 0 0 2.84.81 2.08 2.08 0 0 1 .62-1.31c-2.18-.25-4.47-1.09-4.47-4.84a3.78 3.78 0 0 1 1-2.63 3.52 3.52 0 0 1 .1-2.59s.82-.26 2.68 1a9.2 9.2 0 0 1 4.88 0c1.86-1.26 2.68-1 2.68-1a3.52 3.52 0 0 1 .1 2.59 3.78 3.78 0 0 1 1 2.63c0 3.76-2.29 4.59-4.48 4.84a2.33 2.33 0 0 1 .67 1.81v2.69c0 .27.18.58.68.48A9.75 9.75 0 0 0 12 2.5"/>
          </svg>
        </span>
        <span class="contact-card__body">
          <span class="contact-card__title">GitHub</span>
          <span class="contact-card__value">github.com/{{ site.author.github }}</span>
        </span>
      </a>
    </div>
  </article>
</section>

<section class="section-card panel">
  <h2 class="section-title">Background</h2>
  <div class="timeline">
    <div class="timeline__item">
      <h3 class="timeline__title">Purple Mountain Observatory, CAS</h3>
      <p class="timeline__meta">Engineer · 2023 - present · Nanjing, China</p>
      <p>
        I work on large-scale survey image processing and analysis pipelines, including
        software and infrastructure support for data storage and computing.
      </p>
    </div>
    <div class="timeline__item">
      <h3 class="timeline__title">Brown University</h3>
      <p class="timeline__meta">PhD in Physics · 2015 - 2020</p>
      <p>
        My doctoral work focused on weak lensing, shear calibration, and dark matter
        structure in galaxy clusters under the supervision of Prof. Ian Dell'Antonio.
      </p>
    </div>
    <div class="timeline__item">
      <h3 class="timeline__title">Chinese University of Hong Kong</h3>
      <p class="timeline__meta">BS in Physics · 2008 - 2012</p>
      <p>
        I completed my undergraduate training in physics before continuing into
        graduate research in observational cosmology and astronomical data analysis.
      </p>
    </div>
  </div>
</section>
