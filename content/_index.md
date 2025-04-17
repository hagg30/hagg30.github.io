---
title: "Dongkun Lee | AI Researcher in XR & Explainable AI"
date: 2023-03-08
type: landing

design:
  spacing: "4rem"
  css_class: "container"

sections:
  # ──────────────────────────────── Hero ────────────────────────────────
  - block: markdown
    content:
      title: ""
      text: |
        <div class="section section--space" style="text-align:center;padding:60px 20px;">
          <img src="uploads/dongkun_photo.jpg" alt="Dongkun Lee" style="width:120px;border-radius:50%;margin-bottom:1rem;">
          <h2>👋 Hi, I'm <span style="color:#9B5DE5;">Dongkun Lee</span></h2>
          <p>AI researcher passionate about <strong>Explainable AI</strong>, <strong>XR Simulation</strong>, and <strong>Multimodal Learning</strong>.<br>
          I build intelligent systems that make the complex world understandable.</p>
          <p>
            <a class="btn" href="uploads/resume.pdf" target="_blank">Download CV</a>
          </p>
        </div>
    design:
      columns: "1"

  # ───────────────────────────── Impact ─────────────────────────────
  - block: markdown
    content:
      title: "🚀 Impact Metrics"
      text: |
        - **Publications**: *20 + peer‑reviewed papers*  
        - **Citations**: *500 +*  
        - **Projects**: *6 + AI‑driven deployments*
    design:
      css_class: "section"

  # ──────────────────────── Research & Projects Intro ────────────────
  - block: markdown
    content:
      title: "📚 Research & Projects"
      text: |
        I specialise in building **intelligent systems** for anomaly detection,
        XR simulations, and AI‑based content creation.

        My work bridges **AI, immersive environments, and generative models**
        to tackle real‑world challenges in autonomy, safety, and education.

        Let’s create meaningful solutions together! 🤝
    design:
      css_class: "section"

  # ───────────────────────── Publications List ──────────────────────
  - block: collection
    content:
      title: "Recent Publications"
      filters:
        folders: [publication]
    design:
      view: citation
      css_class: "section"

  # ───────────────────────── Projects Grid ──────────────────────────
  - block: collection
    content:
      title: "Selected Projects"
      filters:
        folders: [project]
    design:
      view: article-grid
      columns: 2
      css_class: "section"

  # ───────────────────────── Experience ─────────────────────────────
  - block: resume-experience
    content:
      title: "Experience"
      username: admin
    design:
      css_class: "section"

  # ───────────────────────── Skills & Hobbies ───────────────────────
  - block: resume-skills
    content:
      title: "Skills & Hobbies"
      username: admin
    design:
      css_class: "section"

  # ───────────────────────── Languages ──────────────────────────────
  - block: resume-languages
    content:
      title: "Languages"
      username: admin
    design:
      css_class: "section"

  # ───────────────────────── Contact ────────────────────────────────
  - block: markdown
    content:
      title: "🤝 Let's Collaborate!"
      text: |
        Always open to exciting research collaborations, innovative projects, and consulting opportunities.

        **Contact**: [hagg30@kaist.ac.kr](mailto:hagg30@kaist.ac.kr)  
        **Full CV**: [Download PDF](uploads/resume.pdf)
    design:
      css_class: "section"
---
