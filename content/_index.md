---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-01
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: "The 3D Physical SubSpace Architecture: A Unified Framework Bridging All Scales of Physics"
        content: 'Open Nature Research is proud to announce the release of a groundbreaking new framework **“3D Physical SubSpace Architecture”**'
        align: left
        background:
          image:
            filename: SubSpace.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
        link:
          icon: hero/arrow-right-circle
          # icon_pack: 
          text: Read More
          url: post/05-31-25physicalsubspace/

      - title: "The Natural Science AI Teacher"
        content: 'Open Nature Research is excited to unveil **“Natural Science AI Teacher,”** an immersive, empathetic tutor for high school science'
        align: left
        background:
          image:
            filename: AITeacher.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: hero/arrow-right-circle
          # icon_pack: 
          text: Read More
          url: post/05-22-25aiteacher/

      - title: "Unveiling the Exploration-Based Teaching Model: An AI-Driven Framework for Active Learning"
        content: 'Open Nature Research is thrilled to announce the launch of the **Exploration-Based Teaching Model**, a pioneering AI framework designed to transform how students engage with complex subjects.'
        align: left
        background:
          image:
            filename: TeachingModel.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
        link:
          icon: hero/arrow-right-circle
          # icon_pack: 
          text: Read More
          url: post/05-12-25aimodel/

      - title: "Introducing Full-Attributes Objects"
        content: 'Open Nature Research is delighted to unveil **“Full-Attributes Objects,”** a dynamic framework for modular object modeling'
        align: left
        background:
          image:
            filename: FullAtrr.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
        link:
          icon: arrow-right-circle
          icon_pack: hero
          text: Read More
          url: post/05-01-25fullattributesobjects/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000


  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type:
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: lab.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen


  - block: hero
    content:
      title: |
        About Us
      image:
        filename: AboutUS.jpg
      text: |
        <br>
        
        **Open Nature Research** is dedicated to advancing innovation in AI and physics. We aim to expand scientific understanding by conducting open, interdisciplinary research and share findings that benefit education, collaboration, and the public good.

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: Afflication.png
          filters:
            brightness: 1
          parallax: false
          size: cover
          position: center
          text_color_light: true
      # css_class: fullscreen
      css_class: full-viewport-width

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      background:
        image: 
          filename: BlueBox.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      # css_class: fullscreen

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: GroupContact.png
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: contain
  #         text_color_light: true
  #     css_class: full-viewport-width
  #     spacing:
  #       margin: ['0', '0', '0', '0']



  
---