---
# Leave the homepage title empty to use the site title
title: AVIG Data Collection System
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Welcome!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        This is the portal for VIG practitioners to record data from pre- and post-VIG meetings with clients. We also encourage practitioners to use this system for a 6 month follow up meeting. 

  - block: markdown
    content: 
      title: ''
      text: |-
        - The system includes a meeting structure for you to follow flexibly with your clients.
        - This will help streamline your work by providing the questions and measures you need in one place.
        - This will enhance VIG practice and help you and clients get the most out of your meetings before and after VIG.
        - The system will help us evaluate the effectiveness of VIG using anonymised data.
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
          filename: coders.jpg
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
