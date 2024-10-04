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
      id: blog-section
      title: 블로그
      subtitle: 다양한 플랫폼에서 학습 기록 및 프로젝트를 공유하고 있습니다.
      text:
      count: 3  # 표시할 블로그 항목 수
      offset: 0
      order: desc
      filters:
        folders:
          - blog  # blog 폴더에서 콘텐츠를 불러옵니다.
    design:
      view: compact
      columns: '2'

