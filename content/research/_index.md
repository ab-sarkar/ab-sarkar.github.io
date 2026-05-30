---
title: Research Interests
summary: My research
type: landing

cascade:
  - target:
      path: '{/research/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:

  - block: markdown
    id: research
    content:
      title: 📚 My Research
      text: |
        <style>
          #research .prose { max-width: 120% !important; }
        </style>
        My research explores fundamental information-theoretic questions for physical systems, spanning both the classical and quantum regimes. I try to provide simple answers to questions about communication, storage, and computation in such physical systems, employing the universal language of mathematics. 
        * ** Research Areas:** *


        * **Message Identification:** Introduced by Rudolf Ahlswede and Gunter Dueck in 1989, message identification is a communication paradigm where the receiver does not need to decode the exact transmitted data. Instead, the receiver only performs a binary check to determine whether a specific, predetermined message of interest was sent or not. The significance of studying this process lies in its remarkable efficiency: it allows the number of possible messages to grow doubly exponentially with the channel block length, bypassing Shannon's traditional single exponential capacity limit. This revolutionary capability makes message identification highly valuable for large-scale applications like alerting systems, targeted advertising, and database search protocols where full data decoding is unnecessary.
        <img src="/id.png" alt="Message Identification Diagram" style="display: block; margin: 0 auto; max-width: 80%; padding: 20px 0;">
        * **Permutation Channels:** Message identification, initially introduced by JàJà and by Ahlswede and Dueck, focuses on verifying if a specific message was sent rather than decoding the data entirely. When applied to permutation channels—a framework, with its noisy variant formalized by Anuran Makur, studied to model systems like DNA data storage and packet-switched networks where the order of transmitted symbols is completely lost—this paradigm yields profound theoretical contributions. Typically, noiseless permutation channels have a zero Shannon capacity for reliable communication because only polynomially many distinct symbol compositions exist. However, utilizing message identification overcomes this bottleneck, allowing the identifiable message set to grow sub-exponentially, specifically as ‭$2^{\epsilon_n n^{q-1}}$‬. Furthermore, introducing block-wise feedback enables doubly exponential growth in message size, offering a highly efficient communication strategy for severely unordered environments.
        <img src="/permutation.png" alt="Permutation Channels Diagram and Message identification over Permutation channel" style="display: block; margin: 0 auto; max-width: 80%; padding: 20px 0;">
  

         Please reach out to collaborate 😃
    design:
      view: article-grid
      columns: 2
---
