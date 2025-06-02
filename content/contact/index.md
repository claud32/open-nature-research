---
title: Contact
date: 2025-05-01

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        At Open Nature Research, we welcome collaboration, questions, and ideas. Whether you're interested in our projects, exploring partnership opportunities, or simply want to learn more about our work in open science, AI, and physics research, we'd love to hear from you.
        Please reach out using the form below or contact us directly via email. Let's explore how we can advance science together.
      email: contact@open-nature.com
      address:
        street: 1751 Liberty St
        city: El Cerrito
        region: CA
        postcode: '94530'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.924303'
        longitude: '-122.314516' #保留小数点后四位如果不work
      directions: Enter Building and take the stairs to STE 106 on Floor 1
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
