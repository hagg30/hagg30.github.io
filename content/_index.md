---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |
        👋 Hi, I'm Dongkun Lee  
        AI Researcher specializing in **Explainable AI**, **XR Simulation**, and **Multimodal Learning**.
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "🚀 Impact Metrics"
      text: |
        - 📄 Publications: **10+**
        - 📑 Total Citations: **2345**
        - 🏆 Projects: **15+**
        - 🎤 Talks: **8**
    design:
      columns: '1'

  - block: cta-card
    content:
      title: "🕹️ Featured Project"
      text: |
        **XR Counter-Terrorism Simulation**  
        AI-powered XR training platform for real-world police counter-terrorism.
      button:
        text: "View Project"
        url: /project/xr-counter-terrorism
    design:
      card:
        css_class: "bg-primary-700"

  - block: markdown
    content:
      title: '📚 Research & Projects'
      text: |-
        I am an AI researcher focusing on **Anomaly Detection**, **XR Simulation**, and **Generative AI for Content Creation**.  

        My work aims to build robust systems that detect abnormal events in complex environments, such as autonomous driving scenarios and industrial applications. I also explore XR-based training platforms and develop generative models to create interactive content for virtual simulations and educational tools.  

        I am passionate about applying AI to real-world challenges by combining multimodal data, immersive technologies, and creative automation.  

        Feel free to reach out for collaborations! 🤝
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false

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

  - block: resume-experience
    content:
      title: Experience
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false

  - block: resume-languages
    content:
      title: Languages
      username: admin

  - block: markdown
    content:
      title: "🤝 Let's Collaborate!"
      text: |
        Open to research collaborations, innovative projects, and consulting opportunities.

        📬 [Email Me](mailto:babba82200@gmail.com)  
        📄 [Download CV](/uploads/resume.pdf)
    design:
      columns: '1'
---
