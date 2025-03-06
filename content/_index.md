---
# Leave the homepage title empty to use the site title
title: "Dongkun Lee | AI Researcher in XR & Explainable AI"
date: 2022-10-24
type: landing

design:
  spacing: "4rem"
  css_class: forbes-style

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |
        👋 Hi, I'm **Dongkun Lee**  
        AI Researcher passionate about **Explainable AI**, **XR Simulation**, and **Multimodal Learning**.  
        I build intelligent systems that make the complex world understandable.
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: forbes-hero
      background:
        color: white
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 0.9
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "🚀 Impact Metrics"
      text: |
        - 📄 **Publications**: *20+ peer-reviewed papers*
        - 📑 **Total Citations**: *500+*
        - 🏆 **Projects**: *6+ AI-driven projects*
    design:
      columns: '1'
      css_class: forbes-section

  - block: markdown
    content:
      title: '📚 Research & Projects'
      text: |-
        I specialize in building **intelligent systems** for detecting anomalies, enhancing XR simulations, and generating creative content through AI.  

        My research bridges **AI, immersive environments, and generative models** to tackle real-world challenges in autonomous driving, industrial safety, and education.  

        Let's create meaningful, innovative solutions together! 🤝
    design:
      columns: '1'
      css_class: forbes-section

  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      css_class: forbes-collection

  - block: collection
    content:
      title: Selected Projects
      filters:
        folders:
          - project
        exclude_featured: false
    design:
      view: article-grid
      columns: 2
      css_class: forbes-collection

  - block: resume-experience
    content:
      title: Experience
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false
      css_class: forbes-section

  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      css_class: forbes-section

  - block: resume-languages
    content:
      title: Languages
      username: admin
    design:
      css_class: forbes-section

  - block: markdown
    content:
      title: "🤝 Let's Collaborate!"
      text: |
        Always open to exciting research collaborations, innovative projects, and consulting opportunities.  

        📬 [Reach me via email](mailto:hagg30@kaist.ac.kr)  
        📄 [Download my full CV](/uploads/resume.pdf)
    design:
      columns: '1'
      css_class: forbes-section
---