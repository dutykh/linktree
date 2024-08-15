---
title: 'Home'
date: 2024-08-15
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: My personal home page
          icon: custom/url
          url: http://www.denys-dutykh.com/
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/dutykh/
        - text: Follow me on ResearchGate
          icon: custom/researchgate
          url: https://www.researchgate.net/profile/Denys-Dutykh/
        - text: Read my latest articles on Arxiv
          icon: academicons/arxiv
          url: https://arxiv.org/a/dutykh_d_1.html
        - text: My YouTube channel
          icon: brands/youtube
          url: https://www.youtube.com/@DenysDutykh/
---
