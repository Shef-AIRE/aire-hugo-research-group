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
    - title: AIRE Team
      content:
      align: center
      background:
        position: center
        color: '#666'
        brightness: 1
        media: aire_team.jpg
    - title: Multimodal Cardiothoracic Disease Prediction
      content: Utilising advanced AI to process multimodal heart and lung data for better Cardiothoracic Disease (CTD) diagnosis and prognosis, enabling personalised medical care.
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.6
        media: heart.png
    - title: Text Recovery from Historical Documents
      content: Leveraging deep learning to refine OCR transcriptions of the extensive British Library Newspapers collection and overcome the barrier of inaccurate text data
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.6
        media: hist.png
    - title: AI Brain Imaging for Nerve Pain Detection
      content: Harnessing advanced AI technology to discern novel biomarkers, paving the way for enhanced chronic nerve pain treatments, revolutionising healthcare outcomes
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.6
        media: brain_mri.png
---
