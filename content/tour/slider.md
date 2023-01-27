---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Bienvenue à la journée des doctorants
      content: de l'UMR-S 1158
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Présentations ☕️
      content: 'Les doctorants profiteront de cette journée pour vous présenter leur thèse et les travaux qu'ils ont réalisé'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
        link:
        icon: graduation-cap
        icon_pack: fas
        text: Retrouvez nous !
        url: ../contact/
   # - title: World-Class Semiconductor Lab
      #content: 'Just opened last month!'
     # align: right
      #background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      #link:
        icon: graduation-cap
        icon_pack: fas
        text: Retrouvez nous !
        url: ../contact/
---
