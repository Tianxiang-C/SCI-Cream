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
        media: 2305-cake2.jpg
    - title: PI & RAs
      align: bottom
      background:
        position: top
        color: '#555'
        brightness: 0.7
        media: PI-RAs.jpg
      link:
        text: Investigate More
        url: https://sci-cream.netlify.app/people/
    - title: A Fun and Productive Lab
      content: 'Located in The Chinese University of Hong Kong, Shenzhen'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: 2305-2.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: mailto:hejinbo@cuhk.edu.cn
---
