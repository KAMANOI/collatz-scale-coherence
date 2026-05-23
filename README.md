# Scale-Coherence Rigidity and the Orbitwise Gap in Collatz Dynamics

**Hiroki Kamanoi**  
Draft — May 2026

Paper D in a series on Collatz dynamics through finite Markov chain theory.

## Overview

Papers B and C established population-level mixing for Collatz dynamics modulo $2^K$. This paper addresses the fundamental gap between those population statements and the individual orbit statement required by the Collatz conjecture.

## Main Results

The paper establishes:

- the **effective high-bit parameter** $m(t)$: the number of high bits active at time $t$;
- the **self-mixing paradox**: divergent orbits push dynamics into the Haar regime, which has *exponentially small* spectral gap — the opposite of fast mixing;
- Weyl equidistribution and its limits: why frequency-based methods cannot close the orbitwise gap;
- the **Simultaneous Scale Coherence Problem**: a precise formulation equivalent to the Collatz conjecture;
- a **conditional theorem**: if the Open Gap Problem of Paper C holds, divergent orbits require diverging cumulative spectral mixing at every scale.

## Important Clarification

This repository does **not** claim a proof of the Collatz conjecture.

The Simultaneous Scale Coherence Problem (Open Problem in Section 4) is **equivalent** to the Collatz conjecture — meaning it is open. The conditional theorem (Section 5) is explicitly conditional on Paper C's unresolved Open Gap Problem. The remaining gap between population mixing and individual orbit convergence is explicitly identified and left open.

## Logical Structure of the Series

| Paper | Core result | Status |
|-------|-------------|--------|
| A | Exact operator structure and renewal systems | Proved |
| B | Exact TV mixing: $T_\mathrm{mix}(K) = K-1$ | Proved |
| C | One-bit spectral jump $\delta_{K,1} \approx 0.29$; Open Gap Problem | Numerical / Open |
| **D (this paper)** | Simultaneous scale coherence; conditional diverging mixing | Open / Conditional |

## Files

- `collatz_scale_coherence.tex` — LaTeX source
- `collatz_scale_coherence.pdf` — compiled draft

## Suggested arXiv Categories

Primary: `math.DS`  
Secondary: `math.NT`, `math.PR`

## License

MIT License


---

## Related work

This repository is part of a series on Collatz dynamics:

| Repository | Description |
|------------|-------------|
| [collatz-renewal-structure](https://github.com/KAMANOI/collatz-renewal-structure) | Paper A: exact renewal structure and operator theory |
| [collatz-finite-mixing-geometry](https://github.com/KAMANOI/collatz-finite-mixing-geometry) | Finite-level mixing geometry |
| [collatz-spectral-amplification](https://github.com/KAMANOI/collatz-spectral-amplification) | Paper C: spectral amplification |
| [collatz-scale-coherence](https://github.com/KAMANOI/collatz-scale-coherence) | Paper D: scale-coherence rigidity |

## Author

Hiroki Kamanoi  
hirokikamanoi@gmail.com  
https://github.com/KAMANOI