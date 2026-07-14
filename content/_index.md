---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: bio
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Yi-Hua-Chung-Resume-20260521.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  - block: markdown
    id: publications
    content:
      columns_content:
        - title: Selected Publications
          icon: hero/book-open
          items:
            - image: /img/publications/simpart.png
              text: |
                **SimPart: A Simple Yet Effective Replication-aided Partitioning Algorithm for Logic Simulation on GPU**<br>
                **Yi-Hua Chung**, Shui Jiang, Wan Luan Lee, Yanqing Zhang, Haoxing Ren, Tsung-Yi Ho, and Tsung-Wei Huang<br>
                International European Conference on Parallel and Distributed Computing (Euro-Par), 2025
              buttons:
                - text: Paper
                  url: uploads/publications/2025-simpart-paper.pdf
                  icon: hero/document-text
                - text: Slides
                  url: uploads/publications/2025-simpart-slides.pdf
                  icon: hero/presentation-chart-bar
            - image: /img/publications/gate-sizing.png
              text: |
                **Accelerating Gate Sizing using GPU**<br>
                **Yi-Hua Chung**, Nahmsuk Oh, Malleswara Gupta Balabhadra Naga Venkata, Aditya Shiledar, Sudipto Kundu, Vishal Khandelwal, and Tsung-Wei Huang<br>
                International European Conference on Parallel and Distributed Computing (Euro-Par), 2025
              buttons:
                - text: Paper
                  url: uploads/publications/2025-gate-sizing-paper.pdf
                  icon: hero/document-text
                - text: Poster
                  url: uploads/publications/2025-gate-sizing-poster.pdf
                  icon: hero/photo
                - text: Slides
                  url: uploads/publications/2025-gate-sizing-slides.pdf
                  icon: hero/presentation-chart-bar
          button:
            text: Full Publications
            url: publications/
            icon: hero/document-text
  - block: resume-experience
    id: experience
    content:
      title: Professional Experience
      username: me
      source_field: experience
      show_education: false
    design:
      date_format: 'MMM 2006'
  - block: resume-experience
    id: teaching
    content:
      title: Teaching & Service
      username: me
      source_field: teaching
      show_education: false
      color: secondary
    design:
      date_format: 'MMM 2006'
  - block: markdown
    id: awards-skills
    content:
      columns_content:
        - title: Awards
          icon: hero/trophy
          items:
            - text: Department of ECE The Gerald Holdridge Teaching Excellence Award, 2026
              image: /img/awards/holdridge-award.JPG
            - text: ACM/IEEE DAC Young Student Fellowship, 2024, 2025
              image: /img/awards/dac-fellowship.jpg
            - text: NTUEE-1975 Innovation and Entrepreneurship Fund Award, College of Electrical Engineering and Computer Science, National Taiwan University
              image: /img/awards/NTUEE-1975.png
            - text: 2022 Future Tech Awards, National Science and Technology Council, R.O.C.
              image: /img/awards/future-tech-awards.jpg
            - text: Best Paper Award, 9th International Multi-Conference on Engineering and Technology Innovation 2020
              image: /img/awards/best-paper-2020.png
            - text: Outstanding Performance Award, NTU-IBM Q System 2020 Q-Camp, Hackathon, Sep 2020
              image: /img/awards/ibm-qcamp.jpg
        - title: Skills
          icon: hero/light-bulb
          text: |
            - **Expert:** C/C++, CUDA C/C++, OpenMP, ARM Intrinsic, ARM Assembly, Linux, Shell
            - **Experienced:** Python, C#, Qiskit, JavaScript, WebGL
---
