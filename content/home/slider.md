---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '1100px'
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title:
      content:
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.9
        media: hiring.svg
    - title: Lunch & Learn ☕️
      content: '.......................'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media:
    - title: Under Construction
      content: 'This website is under construction.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media:
      link:
        icon: fa-github
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
