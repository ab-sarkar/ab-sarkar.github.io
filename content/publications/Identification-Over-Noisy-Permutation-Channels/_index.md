---
title: "Identification Over Noisy Permutation Channels"
authors:
- me
- Bikash Kumar Dey
math: true

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["manuscript"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to IEEE Transactions on Information Theory"
publication_short: 

abstract: |
  We study message identification over the noisy permutation channel. For discrete memoryless channels (DMCs), the number of identifiable messages grows doubly exponentially, and the maximum second-order exponent is the same as the Shannon capacity of the DMC. We consider a $q$-ary noisy permutation channel where the transmitted vector is first permuted by a permutation, chosen uniformly at random, and then passed through a DMC with transition probability matrix $U$. In an earlier work, we showed that over the $q$-ary noiseless permutation channel, $2^{c_n n^{q-1}}$ messages can be identified if $c_n\rightarrow 0$, and a strong converse holds for $2^{c_n n^{q-1}}$ messages if $c_n\rightarrow \infty$. For a $q$-ary noisy permutation channel, we show in this paper that message sizes growing as $2^{R_n \left( \frac{n}{\log n}\right)^{(r-1)/2}}$, where $r$ is the rank of $\dmcmatrix$, are identifiable for any $R_n\rightarrow 0$. We also prove two converse results for the $q$-ary noisy permutation channels where the constituent DMC has strictly positive entries in the transition probability matrix.  For any sequence of identification codes with $$2^{\left(R_n n^{(q-1)/2}(\log n)^{1+\frac{(q-1)(q-2)}{2}}\right)}$$ messages, our weak converse shows that there exists a constant $R'>0$ such that the sum of Type I and Type II error probabilities is asymptotically bounded away from $0$ for any sequence $R_n>R$, if $R>R'$, and our strong converse shows that the sum of Type I and Type II error probabilities approaches at least $1$ as $n\rightarrow \infty$ for $R_n \rightarrow \infty$. Our proof of the converses uses the idea of channel resolvability. The permutation channel only preserves the composition (i.e., type) of the transmitted vector. Hence, the effect of the noisy permutation channel is captured in the way the composition of the transmitted vector is changed by the DMC. This is represented by a new channel -- ``$q$-ary noisy composition channel ($\qww$)''. We propose a novel channel-dependent and deterministic quantization scheme for the quantization of a distribution over the set of all compositions by an $M$-type distribution when the distortion is measured on the output distribution (over the $\qww$) in total variation distance. This plays a key role in the converse proof. We also study identification with deterministic encoder and decoders, and prove tight achievability, a weak converse, and a strong converse. 

tags:
- Source Themes
featured: false

hugoblox:
  ids:
    arxiv: "2412.11091v2"

links:
  - type: pdf
    url: https://doi.org/10.48550/arXiv.2412.11091

---

> [!NOTE]
> Click the *Cite* button above for citation purposes.
