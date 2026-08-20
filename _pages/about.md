---
layout: default
permalink: /
title: "Yehan Zhang"
excerpt: "Undergraduate researcher working on multimodal large language models and lifelong learning."
redirect_from:
  - /about/
  - /about.html
---

<main class="academic-home" id="about">
  <section class="academic-hero" aria-labelledby="hero-title">
    <div class="academic-hero__content">
      <p class="academic-eyebrow">Undergraduate Researcher · Guangzhou, China</p>
      <h1 id="hero-title">Yehan Zhang</h1>
      <p class="academic-hero__role">
        Data Science and Big Data Technology<br>
        <a href="https://www.scut.edu.cn/en/">South China University of Technology</a>
      </p>
      <p class="academic-hero__intro">
        I work on <strong>multimodal large language models</strong> and
        <strong>lifelong learning</strong>, with a focus on systems that understand
        long contexts, adapt continuously, and retain useful knowledge over time.
      </p>
      <div class="academic-actions" aria-label="Contact and profile links">
        <a class="academic-button academic-button--primary" href="mailto:yehanzhang@mail.scut.edu.cn">
          <i class="fas fa-envelope" aria-hidden="true"></i> Email
        </a>
        <a class="academic-button" href="https://github.com/yhzhang1309">
          <i class="fab fa-github" aria-hidden="true"></i> GitHub
        </a>
        <a class="academic-button" href="{{ '/files/CV.pdf' | relative_url }}">
          <i class="fas fa-file-lines" aria-hidden="true"></i> CV
        </a>
      </div>
      <a class="academic-profile-link" href="https://openreview.net/profile?id=%7EYehan_Zhang2">
        View my OpenReview profile <span aria-hidden="true">↗</span>
      </a>
    </div>

    {% if site.author.avatar %}
      <figure class="academic-hero__portrait">
        {% if site.author.avatar contains '://' %}
          <img src="{{ site.author.avatar }}" alt="Portrait of Yehan Zhang">
        {% else %}
          <img src="{{ site.author.avatar | prepend: '/images/' | relative_url }}" alt="Portrait of Yehan Zhang">
        {% endif %}
      </figure>
    {% endif %}
  </section>

  <section class="academic-section academic-news" aria-labelledby="news-title">
    <div class="academic-section__heading">
      <p class="academic-section__kicker">Updates</p>
      <h2 id="news-title">News</h2>
    </div>
    <div class="academic-news__list">
      <article class="academic-news__item">
        <time datetime="2026">2026</time>
        <p><strong>Healthcare Insurance Fraud Detection via Continual Fiedler Vector Graph Model</strong> was accepted as a poster at ICLR 2026.</p>
      </article>
      <article class="academic-news__item">
        <time datetime="2026">2026</time>
        <p><strong>IntentRAG</strong> is under review at ACM Multimedia 2026.</p>
      </article>
      <article class="academic-news__item">
        <time datetime="2026">2026</time>
        <p><strong>DynLearn</strong> is under review at <em>Neural Networks</em>.</p>
      </article>
    </div>
  </section>

  <section class="academic-section" id="publications" aria-labelledby="publications-title">
    <div class="academic-section__heading academic-section__heading--split">
      <div>
        <p class="academic-section__kicker">Selected work</p>
        <h2 id="publications-title">Publications</h2>
      </div>
      <a href="https://openreview.net/profile?id=%7EYehan_Zhang2">OpenReview <span aria-hidden="true">↗</span></a>
    </div>

    <div class="publication-list">
      <article class="publication-card publication-card--featured">
        <div class="publication-card__content">
          <div class="publication-card__meta">
            <span class="publication-badge publication-badge--accepted">ICLR 2026 · Poster</span>
            <span>Conference paper</span>
          </div>
          <h3>Healthcare Insurance Fraud Detection via Continual Fiedler Vector Graph Model</h3>
          <p class="publication-card__authors"><strong>Yehan Zhang</strong>, Huaidong Zhang, Xuandi Luo, Shengfeng He</p>
          <p class="publication-card__venue">The Fourteenth International Conference on Learning Representations</p>
          <a class="publication-card__link" href="https://openreview.net/forum?id=ZWDvIKMkMG">
            Paper on OpenReview <span aria-hidden="true">↗</span>
          </a>
        </div>
        <figure class="publication-card__figure">
          <img src="{{ '/images/publications/confvg-overview.png' | relative_url }}" alt="ConFVG pretraining and online adaptation framework" loading="lazy">
        </figure>
      </article>

      <article class="publication-card">
        <div class="publication-card__content">
          <div class="publication-card__meta">
            <span class="publication-badge">Under Review</span>
            <span>Journal article</span>
          </div>
          <h3>DynLearn: Steering Task-Specific Learning Dynamics in Exemplar-Free Class-Incremental Learning</h3>
          <p class="publication-card__authors">Xuandi Luo, Huaidong Zhang, <strong>Yehan Zhang</strong>, Shengfeng He</p>
          <p class="publication-card__venue"><em>Neural Networks</em></p>
        </div>
        <figure class="publication-card__figure">
          <img src="{{ '/images/publications/dynlearn-overview.png' | relative_url }}" alt="DynLearn framework with complexity-evolved distillation and relational temperature scheduling" loading="lazy">
        </figure>
      </article>

      <article class="publication-card">
        <div class="publication-card__content">
          <div class="publication-card__meta">
            <span class="publication-badge">Under Review</span>
            <span>Conference paper</span>
          </div>
          <h3>IntentRAG: Intent-guided Multimodal Long Document Understanding</h3>
          <p class="publication-card__authors"><strong>Yehan Zhang</strong>, Fei Ma</p>
          <p class="publication-card__venue">ACM International Conference on Multimedia (ACM MM 2026)</p>
        </div>
        <figure class="publication-card__figure">
          <img src="{{ '/images/publications/intentrag-overview.png' | relative_url }}" alt="IntentRAG intent generation, retrieval, and answer generation pipeline" loading="lazy">
        </figure>
      </article>
    </div>
  </section>

  <section class="academic-section" id="research" aria-labelledby="research-title">
    <div class="academic-section__heading">
      <p class="academic-section__kicker">Experience</p>
      <h2 id="research-title">Research</h2>
    </div>

    <div class="research-timeline">
      <article class="research-item">
        <div class="research-item__date">Nov 2025 – Feb 2026</div>
        <div class="research-item__body">
          <p class="research-item__place">GuangMing Laboratory · Shenzhen</p>
          <h3>Long-Context Understanding in Multimodal LLMs</h3>
          <p>Introduced answer intention into retrieval and generation, using reinforcement learning to help compact models locate evidence in long multimodal documents.</p>
        </div>
      </article>

      <article class="research-item">
        <div class="research-item__date">May 2025 – Sep 2025</div>
        <div class="research-item__body">
          <p class="research-item__place">South China University of Technology</p>
          <h3>Lifelong Learning in Fraud Detection</h3>
          <p>Developed a Fiedler-vector-guided graph autoencoder and Subgraph Attention Fusion for label-scarce, non-stationary fraud detection.</p>
        </div>
      </article>

      <article class="research-item">
        <div class="research-item__date">Mar 2025 – May 2025</div>
        <div class="research-item__body">
          <p class="research-item__place">South China University of Technology</p>
          <h3>Lifelong Learning in Computer Vision</h3>
          <p>Designed task-adaptive distillation and temperature scheduling strategies to preserve prior knowledge while learning new classes.</p>
        </div>
      </article>
    </div>
  </section>

  <section class="academic-section academic-details" aria-labelledby="background-title">
    <div class="academic-section__heading">
      <p class="academic-section__kicker">Background</p>
      <h2 id="background-title">Education &amp; Skills</h2>
    </div>

    <div class="academic-details__grid">
      <article class="academic-detail-card">
        <div class="academic-detail-card__icon" aria-hidden="true"><i class="fas fa-graduation-cap"></i></div>
        <p class="academic-detail-card__label">Education</p>
        <h3>South China University of Technology</h3>
        <p>B.S. in Data Science and Big Data Technology<br>2023 – 2027 (expected)</p>
        <p class="academic-detail-card__note">GPA: 3.67 / 4.00</p>
      </article>

      <article class="academic-detail-card">
        <div class="academic-detail-card__icon" aria-hidden="true"><i class="fas fa-code"></i></div>
        <p class="academic-detail-card__label">Toolkit</p>
        <h3>Research Engineering</h3>
        <p>PyTorch · ms-swift · TRL<br>Machine learning experimentation and debugging</p>
        <p class="academic-detail-card__note">Chinese (native) · English (fluent)</p>
      </article>
    </div>
  </section>

  <footer class="academic-contact">
    <p>Interested in multimodal learning or continual learning?</p>
    <a href="mailto:yehanzhang@mail.scut.edu.cn">Let’s talk <span aria-hidden="true">→</span></a>
  </footer>
</main>
