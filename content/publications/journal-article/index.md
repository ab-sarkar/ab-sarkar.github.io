---
title: "Identification Over Permutation Channels"
authors:
- me
- Bikash Kumar Dey
math: true
doi:"10.1109/TIT.2025.3582862"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Information Theory, Volume 71, Issue 9"
publication_short: 

abstract: |
  We study message identification over a noiseless $q$-ary uniform permutation channel, where the transmitted vector is permuted by a permutation chosen uniformly at random. The channel is noiseless in the sense that the channel only rearranges the symbols in a different order, without changing the symbol values. For discrete memoryless channels (DMCs), the number of identifiable messages grows doubly exponentially. Identification capacity, the maximum second-order exponent, is known to be the same as the Shannon capacity of the DMC. Permutation channels support reliable communication of only polynomially many messages. A simple achievability result shows that message sizes growing as $2^{\epsilon_nn^{q-1}}$ are identifiable for any $\epsilon_n\rightarrow 0$. We prove two converse results. A soft converse shows that for any $R>0$, there is no sequence of identification codes with message size growing as $2^{Rn^{q-1}}$ with a power-law decay ($n^{-\mu}$) of the error probability. We also prove a strong converse showing that for any sequence of identification codes with message size $2^{R_n n^{q-1}}$, where $R_n \rightarrow \infty$, the sum of Type I and Type II error probabilities approaches at least $1$ as $n\rightarrow \infty$. To prove the soft converse, we use a sequence of steps to construct a new identification code with a simpler structure which relates to a set system, and then use a lower bound on the normalized maximum pairwise intersection of a set system. To prove the strong converse, we use results on approximation of distributions. The achievability and converse results are generalized to the case of coding over multiple blocks. We also show that under deterministic encoding, the number of messages that can be identified per block is the number of types, i.e., $\binom{n+q-1}{q-1}$, and this is same as the message size for reliable communication. We finally study message identification over a $q$-ary uniform permutation channel in the presence of causal block-wise feedback from the receiver, where the encoder receives an entire $n$-length received block after the transmission of the block is complete. We show that in the presence of feedback, the maximum number of identifiable messages grows doubly exponentially even under deterministic encoding, and we present a two-phase achievability scheme. 

tags:
- Source Themes
featured: false

hugoblox:
  ids:
    arxiv: "2405.09309v3"

links:
  - type: pdf
    url: https://ieeexplore.ieee.org/abstract/document/11049815

---

> [!NOTE]
> Click the *Cite* button above for citation purposes.
