---
title: "Message Identification Over Binary Noisy Permutation Channels"
authors:
- me
- Bikash Kumar Dey
math: true
doi: "10.1109/ISIT63088.2025.11195449"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "2025 IEEE International Symposium on Information Theory (ISIT)"
publication_short: 

abstract: |
  We study message identification over the binary noisy permutation channel. When a vector is transmitted over the binary noisy permutation channel, the components of the vector first get permuted (re-ordered) by a randomly chosen permutation, and then each bit is flipped with probability $p$. It is known from earlier works that the message size for reliable communication over this channel can grow as $n^{R}$, where $R>0$ is defined as the rate. The capacity, defined as the supremum of achievable rates $R$, is proved to be $1/2$. We study message identification over this channel, where a decoder wants to determine if a particular message of interest was transmitted. 
We show that message sizes growing as $2^{\epsilon_n \sqrt{\frac{n}{\log n}}}$ are identifiable for any $\epsilon_n\rightarrow 0$. We also prove a strong converse result showing that for any sequence of identification codes with message size $2^{R_n \sqrt{n}\log n}$, where $R_n \rightarrow \infty$, the sum of Type-I and Type-II error probabilities approaches at least $1$ as $n\rightarrow \infty$. Defining identification rate as the $\log\log$ of the message size, normalized by $\log n$, our results imply the achievability of any rate below $0.5$ and a strong converse above this rate. Our proof of the strong converse uses the idea of channel resolvability. We propose a novel deterministic quantization scheme for the quantization of a Hamming weight distribution by an $M$-type distribution when the distortion is measured on the Hamming weight distribution at the output of BSC($p$) in total variation distance.
This plays a key role in the converse proof.



links:
  - type: pdf
    url: https://ieeexplore.ieee.org/abstract/document/11195449

---

> [!NOTE]
> Click the *Cite* button above for citation purposes.
