---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span class="justify-text" style="font-size:125%">전북대학교에서 통계학과 컴퓨터 공학을 복수전공 중입니다.<br> 현재 학점은 4점대를 유지중이고, 데이터 분석, 프로그래밍, 알고리즘, 데이터베이스에 중점을 두고 공부하고 있으며,<br>이를 통해 백엔드 개발 및 인공지능에 대한 기초를 다지고 있습니다.<br>PTYHON, R, JAVASCRIPT를 사용하여 증권 데이터 분석과 웹 개발 관련 프로젝트를 수행한 경험이 있습니다.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">introduce</span>
        content: <span style="font-size:70%">자기 소개 페이지로 이동</span>
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
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: author/강건우/

      - title: <span style="font-size:70%">인공지능</span>
        content: <span style="font-size:70%">파이썬을 활용한 AI 모델 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: Ai.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'

      - title: <span style="font-size:70%">통계</span>
        content: <span style="font-size:70%">파이썬과 R을 활용한 통계 데이터 분석</span>
        align: center
        background:
          image:
            filename: bigdata.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'

      - title: <span style="font-size:70%">개발</span>
        content: <span style="font-size:70%">노드 기반  Full-Stack 어플리케이션 개발</span>
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