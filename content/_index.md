---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: biography
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">sleighers</span>
        content: <span style="font-size:70%">5인용 멀티 레이싱게임</span>
        align: left
        background:
          image:
            filename: sleighers.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">StackGrowth</span>
        content: <span style="font-size:70%">직접 제작하며 익히는 습관<span style="font-size:70%">
        align: right
        background:
          image:
            filename: SG.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">O.S</span>
        content: <span style="font-size:70%">Operation System의 깊은 이해</span>
        align: left
        background:
          image:
            filename: OS.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">효율성</span>
        content: <span style="font-size:70%">주어진 Budget에 맞추어 프로젝트를 runnable하게 만드는 능력</span>
        align: right
        background:
          image:
            filename: recruitment.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">협업</span>
        content: <span style="font-size:70%">다양한 협업 경험으로 의사소통 능력 보유</span>
        align: left
        background:
          image:
            filename: contact.jpg
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
      interval: 5000

  - block: collection
    content:
      title: 활동 사진
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '1'
  
  - block: collection
    content:
      title: portfolio
      text: ""
      count: 3
      filters:
        folders:
          - portfolio
    design:
      view: compact
      columns: '1'


  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'
---
