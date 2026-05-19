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
 # - block: markdown
 #   content:
 #     title: '📚 My Research'
 #     subtitle: ''
 #     text: |-
 #       My research explores fundamental information-theoretic questions for physical systems, spanning both the classical and quantum regimes. I try to provide simple answers to questions about communication, storage, and computation in such physical systems, employing the universal language of mathematics. 
#
 # Please reach out to collaborate 😃
 # **Message Identification:** 
  #  design:
  #    columns: '1'

  - block: markdown
    id: research
    content:
      title: 📚 My Research
      text: |
        <style>
          #research .prose { max-width: 70% !important; }
        </style>
        My research explores fundamental information-theoretic questions for physical systems, spanning both the classical and quantum regimes. I try to provide simple answers to questions about communication, storage, and computation in such physical systems, employing the universal language of mathematics. 

        * **Message Identification:** Introduced by Rudolf Ahlswede and Gunter Dueck in 1989, message identification is a communication paradigm where the receiver does not need to decode the exact transmitted data. Instead, the receiver only performs a binary check to determine whether a specific, predetermined message of interest was sent or not. The significance of studying this process lies in its remarkable efficiency: it allows the number of possible messages to grow doubly exponentially with the channel block length, bypassing Shannon's traditional single exponential capacity limit. This revolutionary capability makes message identification highly valuable for large-scale applications like alerting systems, targeted advertising, and database search protocols where full data decoding is unnecessary.
        * **Permutation Channels:** Message identification, initially introduced by JàJà and by Ahlswede and Dueck, focuses on verifying if a specific message was sent rather than decoding the data entirely. When applied to permutation channels—a framework, with its noisy variant formalized by Anuran Makur, studied to model systems like DNA data storage and packet-switched networks where the order of transmitted symbols is completely lost—this paradigm yields profound theoretical contributions. Typically, noiseless permutation channels have a zero Shannon capacity for reliable communication because only polynomially many distinct symbol compositions exist. However, utilizing message identification overcomes this bottleneck, allowing the identifiable message set to grow sub-exponentially, specifically as ‭$2^{\epsilon_n n^{q-1}}$‬. Furthermore, introducing block-wise feedback enables doubly exponential growth in message size, offering a highly efficient communication strategy for severely unordered environments.

         Please reach out to collaborate 😃


  
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
