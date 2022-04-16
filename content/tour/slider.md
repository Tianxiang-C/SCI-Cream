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
    - title: 👋 Welcome to the group
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: eating.jpg
    - title: Lunch & Learn ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: pizza.jpg
    - title: A Fun and Productive Lab
      content: 'Located in The Chinese University of Hong Kong, Shenzhen'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: laughing.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: mailto:hejinbo@cuhk.edu.cn
---
