# Modern Optimizers as Noise-Shaping Mechanisms

Notebooks accompanying **Modern Optimizers as Noise-Shaping Mechanisms: A Stochastic Differential Equation Perspective**, the PhD thesis of **Enea Monzio Compagnoni**, University of Basel, 2026.

| Notebook | What it shows | Thesis chapter | Related figure or section |
|---|---|---|---|
| [Miscellanea_2.ipynb](Miscellanea_2.ipynb) | GD and SGD trajectories on a landscape with sharp and flat minima; a schematic illustration of SDE–optimizer tracking. | 1 — Introduction; 2 — SDE toolkit | Figures 1.1 and 2.3. |
| [Miscellanea_1.ipynb](Miscellanea_1.ipynb) | Illustrations of SGD and its SDE, Brownian motion, the SGD loss and scaling law, SAM, and the signal-to-noise phases of SignSGD. | 1, 2, 3 and 5 | Figures 1.2, 2.1, 2.2, 3.1 and 5.2. |
| [SAM_Quadratic.ipynb](SAM_Quadratic.ipynb) | Compares SAM, USAM and DNSAM with their SDE models on a noisy quadratic, plotting trajectories and losses. | 3 — SAM | Figure 3.2. |
| [Minimax.ipynb](Minimax.ipynb) | Compares SEG with its SDE for different extra-step sizes on a generalized quadratic game. | 4 — Minimax | Section 4.5; Figure 4.4. |
| [Adaptive_Sign.ipynb](Adaptive_Sign.ipynb) | Compares SignSGD trajectories with the full SDE and phase-specific approximations on a quadratic. | 5 — Adaptive methods | Figure 5.3, upper-left panel. |
| [DP_DPSGD_DPSignSGD.ipynb](DP_DPSGD_DPSignSGD.ipynb) | Compares DP-SGD and DP-SignSGD with their SDE approximations through squared gradient norms and trajectories on a quadratic. | 6 — Differential privacy | Figure 6.1. |
| [CSGD_EmbSaddle.ipynb](CSGD_EmbSaddle.ipynb) | Compares distributed SGD with random sparsification and its SDE on an embedded-saddle landscape. | 7 — Distributed learning | Figure 7.1, upper-right panel. |
| [L0L1.ipynb](L0L1.ipynb) | Compares SGD with classical first-order, classical second-order and stability-corrected SDEs below and above a quadratic stability threshold. | 8 — (L0, L1)-smoothness | Section 8.4.2, quadratic stability example; Appendix G.2. |
