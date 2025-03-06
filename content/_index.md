---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
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
      title: '🚀 Research & Projects'
      subtitle: ''
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
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false

  - block: collection
    content:
      title: Selected Projects
      text: ""
      filters:
        folders:
          - project
        exclude_featured: false
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Experience
      text: ""
      filters:
        folders:
          - experience
        exclude_featured: false
    design:
      view: timeline
      card:
        css_class: "bg-primary-100"
        css_style: ""
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

---
