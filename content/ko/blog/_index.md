---
title: '블로그'
date: '2023-10-26'
type: landing

design:
  # Section spacing
  spacing: '5rem'


sections:
  - block: collection
    content:
      title: 블로그
      text: 다양한 플랫폼에서 학습 기록 및 프로젝트를 공유하고 있습니다.
      filters:
        folders:
          - blog  # blog 폴더에 있는 콘텐츠를 불러옵니다.
    design:
      view: article-grid  # 그리드 뷰로 블로그 목록을 표시합니다.
      fill_image: false  # 이미지를 그리드에 꽉 차게 표시합니다.
      columns: 3  # 한 줄에 3개의 블로그 항목을 표시합니다.


