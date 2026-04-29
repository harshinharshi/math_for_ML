# Mathematics for Machine Learning — 4-Week Study Plan

**Book:** Mathematics for Machine Learning — Deisenroth, Faisal & Ong  
**Pace:** 3 hours/day · 6 days/week · 4 weeks (~84 hrs total)  
**Level:** Rusty math background, re-learning from foundations

---

## Structure

Each day runs a **2 + 1 split**:
- **2 hrs** — Active reading (pen + paper, rederive results as you go)
- **1 hr** — Exercises, coding, or review

Sundays are rest / catch-up days. Do not skip them.

---

## Week 1 — Linear Algebra & Analytic Geometry (Ch 2–3)

| Day | Read | Practice |
|-----|------|----------|
| Mon | Ch 2.1–2.3 · Systems of equations, matrices, solving | Exercises Ch 2 (first half) |
| Tue | Ch 2.4–2.6 · Vector spaces, linear independence, basis & rank | Exercises Ch 2 (second half) |
| Wed | Ch 2.7–2.8 · Linear mappings, affine spaces | Redo weak exercises from Mon–Tue |
| Thu | Ch 3.1–3.5 · Norms, inner products, orthonormal basis | Exercises Ch 3 (first half) |
| Fri | Ch 3.6–3.9 · Orthogonal complement, projections, rotations | Exercises Ch 3 (second half) |
| Sat | Week 1 recap — restate key theorems in your own words | NumPy: implement basis operations and verify SVD |
| Sun | Rest / catch-up | — |

---

## Week 2 — Matrix Decompositions & Vector Calculus (Ch 4–5)

| Day | Read | Practice |
|-----|------|----------|
| Mon | Ch 4.1–4.2 · Determinant, trace, eigenvalues & eigenvectors | Eigenvalue problems from Ch 4 exercises |
| Tue | Ch 4.3–4.5 · Cholesky, eigendecomposition, SVD | Compute SVD by hand on a small matrix |
| Wed | Ch 4.6–4.7 · Matrix approximation, matrix phylogeny | Image compression via truncated SVD (NumPy) |
| Thu | Ch 5.1–5.4 · Derivatives, partial differentiation, Jacobian | Gradient calculation exercises |
| Fri | Ch 5.5–5.7 · Backpropagation, automatic differentiation, Hessian | Trace backprop manually on a tiny network |
| Sat | Ch 5.8 · Taylor series + Week 2 recap | Manual gradient descent implementation in NumPy |
| Sun | Rest / catch-up | — |

---

## Week 3 — Probability, Statistics & Optimization (Ch 6–7–8)

| Day | Read | Practice |
|-----|------|----------|
| Mon | Ch 6.1–6.3 · Probability space, discrete/continuous, Bayes' theorem | Bayes theorem problems |
| Tue | Ch 6.4–6.5 · Summary statistics, independence, Gaussian distribution | Exercises: Gaussian, marginals, conditionals |
| Wed | Ch 6.6–6.8 · Conjugacy, exponential family, change of variables | Redraw key distribution relationships from memory |
| Thu | Ch 7.1–7.2 · Gradient descent, constrained optimization, Lagrange multipliers | Optimize a constrained function by hand |
| Fri | Ch 7.3 · Convex optimization | SGD vs momentum comparison in NumPy |
| Sat | Ch 8 · When Models Meet Data (read-only, bridge to Part II) | Week 3 exercises revisit |
| Sun | Rest / catch-up | — |

---

## Week 4 — ML Methods: Linear Regression, PCA, GMM, SVM (Ch 9–12)

| Day | Read | Practice |
|-----|------|----------|
| Mon | Ch 9 · Linear Regression (full — MLE, Bayesian, projection view) | Implement Bayesian linear regression from scratch |
| Tue | Ch 10.1–10.4 · PCA: max variance perspective, projection perspective | PCA on MNIST subset, visualize principal components |
| Wed | Ch 10.5–10.8 · High-dimensional PCA, latent variable view | Connect PCA derivation back to SVD from Week 2 |
| Thu | Ch 11 · Gaussian Mixture Models & EM algorithm (full) | Trace E-step and M-step on paper with a toy example |
| Fri | Ch 12 · SVM: separating hyperplanes, primal, dual, kernels | Derive the dual SVM formulation on paper |
| Sat | Full book recap — build one concept map connecting all 4 methods | Verify all 4 methods using scikit-learn on real data |
| Sun | Rest / done | — |

---

## Daily Habits

- **Derivation journal.** When the book shows a result, close it and rederive it yourself before reading the proof. This is the single highest-leverage habit for rusty math.
- **No passive reading.** Every theorem gets a worked example in your notebook before you move on.
- **Code what you prove.** If you derived it on paper, implement it in NumPy. Symbolic understanding and numerical intuition reinforce each other.
- **Flag, don't stall.** If a section takes more than 40 minutes and you're still lost, mark it and move forward. Return on Saturday review day.

---

## Recommended Tooling

- **NumPy / SciPy** — for all linear algebra and optimization coding sessions
- **Matplotlib** — for visualizing PCA components, gradient descent trajectories
- **scikit-learn** — Week 4 verification only (after you've implemented from scratch)
- **Jupyter Notebook** — keep one notebook per chapter for worked examples

---

## Progress Tracker

| Week | Chapters | Status |
|------|----------|--------|
| 1 | Ch 2 · Linear Algebra, Ch 3 · Analytic Geometry | ⬜ Not started |
| 2 | Ch 4 · Matrix Decompositions, Ch 5 · Vector Calculus | ⬜ Not started |
| 3 | Ch 6 · Probability, Ch 7 · Optimization, Ch 8 · Models & Data | ⬜ Not started |
| 4 | Ch 9 · Lin Reg, Ch 10 · PCA, Ch 11 · GMM, Ch 12 · SVM | ⬜ Not started |

Update status to `🟡 In progress` or `✅ Done` as you go.

---

*Book website & free PDF: [https://mml-book.com](https://mml-book.com)*
