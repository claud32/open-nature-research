---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-01
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: "Introducing the 3D Physical SubSpace Architecture: A Unified Framework Bridging All Scales of Physics"
        content: 'Open Nature Research is proud to announce the release of a groundbreaking new framework **“3D Physical SubSpace Architecture”**'
        align: right
        background:
          image:
            filename: SubSpace.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: hero/arrow-right-circle
          icon_pack: hero
          text: Read More
          url: ../post/05-31-25physicalsubspace/

      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000


  - block: collection
    content:
      title: Latest News
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
      view: card
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
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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

  - block: hero
    content:
      title: |
        About Us
      image:
        filename: AboutUSjpg.jpg
      text: |
        <br>
        
        **Open Nature Research** is dedicated to advancing innovation in AI and physics. We aim to expand scientific understanding by conducting open, interdisciplinary research and share findings that benefit education, collaboration, and the public good.

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
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
          filename: Afflication.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: GroupContact.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: fullscreen


  
---