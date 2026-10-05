# Chiral Orientation of the Directed Heisenberg Frontier

This repository contains the source of the Cosmochrony fermionic-matter paper
*Chiral Orientation of the Directed Heisenberg Frontier*.

The directed Heisenberg frontier carries a chirally dressed cocycle signal
$\Theta_\chi = \langle \sigma_L\,(2\pi/q)\,d_{ac}\rangle_{\partial^+}$, a discrete counterpart of
the orientation datum (in the sense of Q11OF) of the angular generation split of the projected Dirac
residue $E_\Pi$; it is not the $J_3$ coefficient of the metaplectic step, which in the $\mathrm{SL}(2)$
model of Q14 is produced by the $\mathfrak{sl}_2$ commutator $[E,F]=H$ (Q14, Proposition 6.5). The raw cocycle average and
the maximal-locking bound are computable from the arithmetic backend, but the signal depends on
the chiral weight $\sigma_L$, whose origin lies in the Lorentzian spin-lift, not the arithmetic
frontier.

## Core Result

Under the hypothesis [H-WS] of Q11OF ($R_b$ acts on the chiral carrier as a scalar, so $[\gamma_5,R_b]=0$;
supplied by no source), $\sigma_L$ **cannot be any function of the real
cascade generator $T(e)$**: edge inversion and the
residual reflection $\varphi$ both act as $T \mapsto -T$, so every $f(T)$ has identical
arrow-parity and $\varphi$-parity, whereas $\sigma_L$ must be arrow-even and $\varphi$-odd. The
resolution, under [H-WS]: $\sigma_L$ is the **Weyl representation type**, $\mathbf{2}$ versus $\bar{\mathbf{2}}$
— group inversion preserves the representation (arrow-even) while complex conjugation exchanges it
($\varphi$-odd). In the inherited Heisenberg central-phase lift the chiral phase is the linear
cyclotomic character $\omega_\chi(e) = \zeta_q^{d_{ac}(e)}$, giving $\sigma_L(e) = \operatorname{sgn} d_{ac}(e)$
and a non-zero frontier amplitude datum.

This establishes chiral orientation **conditionally** in the inherited central-phase lift and under
[H-WS]; the only remaining obstruction besides [H-WS] is an additional spin-Galois phase outside the central character (a
$\sqrt{5}$ or ADE-spin factor). It is a conditional derivation of the frontier amplitude datum and
does not by itself derive $u \neq 0$, which would further require a transport of the oriented signal to the
$J_\Pi$-odd generation sector; the only transport stated in PRS is the hypothesis [H-Tr] for the
$\mathfrak{sl}_2$ opening, supplied by no source, and the identification of the frontier signal with
that opening is a further input.

## Keywords

Chiral orientation, directed Heisenberg frontier, Weyl representation type, cyclotomic character,
projected Dirac residue, spin-lift, cocycle signal.

## Repository Contents

```
chiral-orientation-frontier/
├── code/        # Diagnostic scripts (+ requirements.txt)
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── out/         # Compiled paper PDF (ChiralOrientationFrontier.pdf)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.20735907](https://doi.org/10.5281/zenodo.20735907)
- 🌐 Website: https://cosmochrony.org/science/fermionic-matter/chiral-orientation-frontier/

## Citation

> J. Beau, *Chiral Orientation of the Directed Heisenberg Frontier*, Zenodo, 2026.
> DOI: 10.5281/zenodo.20735907.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations remain
the sole responsibility of the author.
