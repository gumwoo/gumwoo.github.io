---
# Leave the homepage title empty to use the site title
title: "전북대 강건우"
description: "전북대학교에서 공부 중인 강건우의 포트폴리오 페이지입니다."
keywords: "전북대, 강건우, 전북대 강건우포트폴리오"
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
      title: <span style="font-size:70%">📚 Summary of Self-Introduction </span>
      text: <br><span style="font-size:125%">I am double majoring in Statistics and Computer Engineering at Chonbuk National University.<br>I currently maintain a GPA in the 4 range, focusing my studies on data analysis, programming, algorithms, and databases,<br>building a foundation in backend development and artificial intelligence.<br>I have experience conducting securities data analysis and web development projects using Python, R, and JavaScript.</span> <br><br>
      
        {{% cta cta_link="./project/" cta_text="View Projects →" %}}
    design:
      columns: '3'


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">introduce</span>
        content: <span style="font-size:70%">Go to Self-Introduction Page</span>
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
          text: <span style="font-size:60%">instroduction</span>
          text-color: '#000'
          url: author/강건우/

      - title: <span style="font-size:70%">Artificial Intelligence</span>
        content: <span style="font-size:70%">AI Model Development Using Python<span style="font-size:70%">
        align: center
        background:
          image:
            filename: Ai.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Statistics</span>
        content: <span style="font-size:70%">Statistical Data Analysis Using Python and R</span>
        align: center
        background:
          image:
            filename: bigdata.png
            filters:
              brightness: 0.6
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Node-Based Full-Stack Application Development</span>
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


  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Interests</span>
      text: I am interested in the following fields.<br><br><br><br>
      items:
        - name: Artificial Intelligence (AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">Utilizing AI technologies.</span><br><br>
        - name: Cloud Computing
          icon: cloud
          icon_pack: fab
          description:  <span style="font-size:90%">Data management using cloud technologies.</span><br><br>
        - name: Data Analysis
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">Deriving insights through data analysis.</span><br><br>
        - name: Social Media (Contents)
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">Integration with social media platforms.</span><br><br>
        - name: Web Development
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Node-based Full-Stack development.</span><br><br>
        - name: Open Source 
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">Contributing to open source projects.</span><br><br>


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
      columns: '2'

  - block: collection
    content:
      id: blog-section
      title: 블로그
      subtitle: I share my learning records and projects across various platforms.
      text:
      count: 3  # 표시할 블로그 항목 수
      offset: 0
      order: desc
      filters:
        folders:
          - blog  # blog 폴더에서 콘텐츠를 불러옵니다.
    design:
      view: custom_compact
      columns: '2'

  - block: collection
    content:
      title: project
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: project
    design:
      view: community/custom_horizontal
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="연락 방법 →" %}}
    design:
      columns: '1'
---