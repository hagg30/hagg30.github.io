---
title: "Dongkun Lee | AI Systems & LLM Efficiency Engineer"
date: 2023-03-08
type: landing

design:
  spacing: "4rem"
  css_class: "container"

sections:
  - block: markdown
    content:
      title: ""
      text: |
        <section class="portfolio-hero">
          <div class="portfolio-hero__copy">
            <p class="portfolio-hero__eyebrow">AI SYSTEMS · MODEL EFFICIENCY</p>
            <h1>Engineering efficient AI from model research to real inference.</h1>
            <p class="portfolio-hero__lead">I'm Dongkun Lee, a Senior Staff Engineer focused on LLM inference optimization, model compression, and practical deployment algorithms.</p>
            <div class="portfolio-links">
              <a class="btn" href="https://www.linkedin.com/in/dongkunlee777" target="_blank" rel="noopener">LinkedIn</a>
              <a class="btn btn-secondary" href="https://scholar.google.com/citations?user=8pplxsoAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
              <a class="text-link" href="https://github.com/hagg30" target="_blank" rel="noopener">GitHub ↗</a>
            </div>
          </div>
          <aside class="portfolio-hero__profile" aria-label="Profile summary">
            <img src="uploads/avatar.jpg" alt="Dongkun Lee">
            <dl class="profile-facts">
              <div><dt>Current role</dt><dd>Senior Staff Engineer</dd></div>
              <div><dt>Focus</dt><dd>Efficient AI systems</dd></div>
              <div><dt>Education</dt><dd>Ph.D., KAIST</dd></div>
            </dl>
          </aside>
        </section>
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "What I work on"
      text: |
        <div class="focus-grid">
          <article class="focus-card">
            <span class="focus-card__index">01</span>
            <h3>LLM inference</h3>
            <p>Algorithms that improve deployment efficiency across memory, latency, throughput, and model quality.</p>
          </article>
          <article class="focus-card">
            <span class="focus-card__index">02</span>
            <h3>Model compression</h3>
            <p>Quantization, pruning, knowledge distillation, and sparsity for practical model optimization.</p>
          </article>
          <article class="focus-card">
            <span class="focus-card__index">03</span>
            <h3>Research to deployment</h3>
            <p>Evaluation-driven algorithm development that connects research ideas with real inference systems.</p>
          </article>
        </div>
    design:
      css_class: "naver-section"

  - block: markdown
    content:
      title: "Research foundation"
      text: |
        My research background spans **out-of-distribution detection, road anomaly segmentation,
        uncertainty estimation, generative modeling, and computer vision**, with publications at
        ICRA and ECAI.

        That work established the evaluation discipline I now bring to efficient AI systems:
        define the failure mode, measure the trade-off, and build an algorithm that survives
        contact with deployment constraints.

        <div class="inline-links">
          <a href="publication/lee-2023-road/">ICRA 2023 paper →</a>
          <a href="publication/sim-2023-debiasing/">ECAI 2023 paper →</a>
          <a href="publication/">All publications →</a>
        </div>
    design:
      css_class: "naver-section"

  - block: collection
    content:
      title: "Selected publications"
      filters:
        folders:
          - publication
      design:
        view: citation
        css_class: "naver-section"

  - block: collection
    content:
      title: "Selected research projects"
      text: "Public work from my doctoral research and earlier collaborative projects."
      filters:
        folders:
          - project
      design:
        view: article-grid
        columns: 2
        css_class: "naver-section"

  - block: resume-experience
    content:
      title: "Experience"
      username: admin
    design:
      css_class: "naver-section"

  - block: resume-skills
    content:
      title: "Technical focus"
      username: admin
    design:
      css_class: "naver-section"

  - block: markdown
    content:
      title: "Let's connect"
      text: |
        <div class="contact-panel">
          <p>I welcome research exchange and open-source collaboration around efficient AI systems, model compression, and reliable machine learning.</p>
          <div class="portfolio-links">
            <a class="btn" href="mailto:babba82200@gmail.com">Email</a>
            <a class="btn btn-secondary btn-secondary--light" href="https://www.linkedin.com/in/dongkunlee777" target="_blank" rel="noopener">LinkedIn</a>
            <a class="text-link" href="https://github.com/hagg30" target="_blank" rel="noopener">GitHub ↗</a>
          </div>
        </div>
    design:
      css_class: "naver-section"
---

