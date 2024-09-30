---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: ''
      username: 강건우

  - block: features
    content:
      title: <span style="font-size:70%">'📚 About me </span>
      text: <br><span style="font-size:125%">전북대학교에서 통계학과 컴퓨터 공학을 복수전공 중입니다.<br>현재 학점은 4점대를 유지중이고, 데이터 분석, 프로그래밍, 알고리즘, 데이터베이스에 중점을 두고 공부하고 있으며,<br>이를 통해 백엔드 개발 및 인공지능에 대한 기초를 다지고 있습니다. <br>PTYHON, R, JAVASCRIPT를 사용하여 증권 데이터 분석과 웹 개발 관련 프로젝트를 수행한 경험이 있습니다.</span> <br><br>
      
        {{% cta cta_link="./field/" cta_text="See Research Field →" %}}
    design:
      columns: '3'  # 두 개의 컬럼으로 설정


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
              brightness: 0.4
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
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">통계</span>
        content: <span style="font-size:70%">파이썬과 R을 활용한 통계 데이터 분석</span>
        align: center
        background:
          image:
            filename: bigdata.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">개발</span>
        content: <span style="font-size:70%">노드 기반  Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: development.png
            filters:
              brightness: 0.4
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


  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Interests</span>
      text: 저는 다음과 같은 분야에 관심을 쏟고 있습니다.<br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">AI 기술을 활용.</span><br><br>
        - name: 클라우드
          icon: cloud
          icon_pack: fab
          description:  <span style="font-size:90%">클라우드 기술을 활용한 데이터 관리</span><br><br>
        - name: 데이터 분석
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">데이터 분석을 통한 인사이트 도출</span><br><br>
        - name: 소셜 미디어 (Contents)
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">소셜 미디어 플랫폼과 연동</span><br><br>
        - name: 웹 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">노드 기반의 Full-Stack 개발.</span><br><br>
        - name: 오픈소스 
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">오픈 소스 프로젝트에 기여</span><br><br>


  - block: collection
    content:
      id: section-1
      title: certification
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '3'

  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Join team →" %}}
    design:
      columns: '1'
---