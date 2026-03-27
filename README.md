# Robust Matrix Recovery via Truncated $L_{t,*-F}$ Regularization

**Author:** Zahia Aidene  
**Affiliation:** Southwest University, School of Mathematics and Statistics, Chongqing, China  
**Email:** zahiaaidene@gmail.com  

---

## Overview

This repository contains the theoretical and numerical study of **robust low-rank matrix recovery** under **noise folding** and **operator perturbation**. We explore two non-convex regularization models:

1. **Difference of Nuclear and Frobenius norms ($L_{*-F}$)**
2. **Truncated Difference ($L_{t,*-F}$)**

The truncated regularization achieves a **tighter recovery error bound** and superior robustness compared to standard nuclear norm-based methods.

---

## Main Contributions

- Analysis of **noise folding** in completely perturbed low-rank matrix models.
- RIP-based sufficient conditions for **stable recovery** using $L_{*-F}$.
- Recovery guarantees for the **truncated $L_{t,*-F}$ model**.
- Numerical validation showing **improved recovery performance** with truncation.

---

## Mathematical Models

**1. $L_{*-F}$ Minimization**

$$
\min_{X \in \mathbb{R}^{m\times n}} \| X \|_{*} - \| X \|_{F} \quad \text{s.t.} \quad \| \widehat{\mathcal{B}}(X) - y \|_2 \leq \epsilon
$$

**2. Truncated $L_{t,*-F}$ Minimization**

$$
\min_{X \in \mathbb{R}^{m\times n}} \| X \|_{t,*} - \| X \|_{t,F} \quad \text{s.t.} \quad \| \widehat{\mathcal{B}}(X) - y \|_2 \leq \epsilon
$$

---

## Results

- The truncated model consistently yields **smaller error constants** than the standard $L_{*-F}$ model.
- Numerical experiments confirm the **effectiveness of truncation** under various noise and operator perturbation scenarios.
- Figures and tables illustrate the **tighter error bounds** of the $L_{t,*-F}$ model.

---


---

## References

1. Aidene, Z. *Robust Matrix Recovery via Truncated $L_{t,*-F}$ Regularization under Noise Folding and Operator Perturbation*.
2. Arias-Castro, E., & Eldar, Y. C. *Noise Folding in Compressed Sensing*  
3. Cai, J.-F., & Guo, H. *Truncated Nuclear Norm for Low-Rank Matrix Recovery*  
*(Additional references as cited in the paper)*

---
