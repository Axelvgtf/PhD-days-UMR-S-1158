---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: yes
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Bienvenue à la journée des doctorants
      content: ''
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: gosset.JPG
    - title: Présentations des travaux des doctorants 📚
      content: 'dans l'amphitthéâtre Anthonin Gosselet'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: amphi.JPG
    - title: Pause repas à midi dans la bibliothèque ☕️
      content: ''
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: biblio.JPG
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---

