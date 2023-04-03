---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '600px'
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: AI Research Engineer
      content: FIVE three-year positions at the University of Sheffield for those with a passion for AI/machine learning research AND software development.
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.6
        media: slide.jpg
    - title: <iframe width=110% height="850px" src="https://www.youtube.com/embed/2gizHKlaDqE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      content: 
      align: center
      background:
        position: right
        color: '#333'
        brightness: 1
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
