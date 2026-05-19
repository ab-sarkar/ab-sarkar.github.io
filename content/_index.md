---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research explores fundamental information-theoretic questions for physical systems, spanning both the classical and quantum regimes. I try to provide simple answers to questions about communication, storage, and computation in such physical systems, employing the universal language of mathematics. 

  Please reach out to collaborate 😃

  * **Message Identification:** 
    design:
      columns: '1'
#  - block: collection
#    id: papers
 #   content:
 #     title: Publications
 #     filters:
  #      folders:
  #        - publications
  #      featured_only: true
 #   design:
  #    view: article-grid
 #     columns: 2
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
 # - block: collection
 #   id: talks
 #   content:
 #     title: Recent & Upcoming Talks
 #     filters:
 #       folders:
  #        - events
 #   design:
 #     view: card
---
