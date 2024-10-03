---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span class="justify-text" style="font-size:125%">I am double majoring in Statistics and Computer Engineering at Chonbuk National University.<br> Currently, my grades are in the 4-point range, focusing my studies on data analysis, programming, algorithms, and databases.<br>Through this, I am building a foundation in backend development and artificial intelligence.<br>I have experience conducting securities data analysis and web development projects using Python, R, and JavaScript.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">introduce</span>
        content: <span style="font-size:70%">Go to the Introduction page</span>
        align: center
        background:
          image:
            filename: introduce.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">introduce</span>
          text-color: '#000'
          url: author/강건우/

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">AI Model Development Using Python<span style="font-size:70%">
        align: center
        background:
          image:
            filename: Ai.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'

      - title: <span style="font-size:70%">statistic</span>
        content: <span style="font-size:70%">Statistical Data Analysis Using Python and R</span>
        align: center
        background:
          image:
            filename: bigdata.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'

      - title: <span style="font-size:70%">development</span>
        content: <span style="font-size:70%">Node-based Full-Stack Application Development</span>
        align: center
        background:
          image:
            filename: development.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  # - block: hero
  #   content:
  #     title: |
  #       <span style="font-size:75%">Medical AI & Computational Science (MACS) Lab</span>
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       <span style="font-size:75%">전북대학교 의료 AI 및 계산 수학 연구실 (MACS Lab) 홈페이지에 오신 것을 환영합니다. MACS에서는 의료, 항공, 국방 분야에 AI 및 딥러닝을 활용한 연구를 수행하고 있으며, 의료 수학 및 AI 기반 연구도 함께 수행하고 있습니다. 뿐만 아니라, 풀스택 개발 및 AI를 활용한 어플리케이션 개발 등 Development & Deploy하는 실용적인 분야에도 집중하고 있습니다.</span>
  
---