# FIGURES-TODO.md
# Kailath – Linear Systems (Anki Deck)
#
# Purpose:
# This file enumerates all candidate figures/diagrams that may be turned into
# pictorial Anki flashcards. The list is intentionally maximal; pruning and
# deferral are expected later.
#
# Guiding principles:
# - Each figure should convey ONE structural idea.
# - Figures should support active recall, not replace reasoning.
# - Prefer abstract, schematic diagrams over textbook screenshots.
# - Images should remain valid across realizations and coordinate changes.

---

## Global / Cross-Cutting Figures

- State-space vs input–output abstraction
- Multiple realizations, same behavior (equivalence class)
- Similarity transformation (change of basis)
- Structural vs numerical properties (what invariants survive)
- Behavior vs structure vs physical realizability (three-layer diagram)

---

## Chapter 1–2: Systems, State, and Representation

- System vs signal distinction
- Input–output block with hidden internal state
- State evolution via state transition matrix Φ(t)
- Free response vs forced response
- Cascade of realizations vs single realization
- Continuous-time vs discrete-time state evolution
- Direct feedthrough vs strictly proper behavior

---

## Chapter 3: Linear Algebra (Structural View)

- Linear map vs matrix representation (two bases)
- Domain → image → codomain (rank geometry)
- Kernel/nullspace highlighted
- Left vs right nullspaces (dual geometry)
- Invariant subspace under A
- Direct sum decomposition of vector space
- Similarity: same map, different matrices
- Eigenvalues vs eigenvectors (what is invariant)
- Jordan block structure (schematic, not numeric)
- Minimal polynomial vs characteristic polynomial (conceptual)

---

## Chapter 4: Controllability & Observability

- Controllable vs uncontrollable subspaces
- Observable vs unobservable subspaces
- Duality: controllability ↔ observability (mirror diagram)
- Kalman decomposition (four subspaces) **HIGH PRIORITY**
- Input influence cone in state space
- Output sensitivity cone in state space
- Time evolution showing unreachable states
- Time evolution showing hidden states
- Controllability matrix rank intuition
- Observability matrix rank intuition

---

## Chapter 5: Minimal Realizations

- Minimal vs non-minimal realization (dimension comparison)
- Redundant states highlighted
- Equivalence class of minimal realizations
- Pole–zero cancellation in transfer function
- Hidden internal mode despite cancellation **HIGH PRIORITY**
- McMillan degree as “essential dimension”
- Cancellation vs elimination (state-space vs algebra)
- Minimal realization vs physically minimal network

---

## Chapter 6: Canonical Forms

- Controllable canonical form structure
- Observable canonical form structure
- Side-by-side comparison (what each emphasizes)
- Modal / diagonal / Jordan form schematic
- Fragility of diagonalization under perturbation
- Canonical form vs ladder / Jacobi form **HIGH PRIORITY**
- Sparsity destruction under similarity
- Canonical ≠ preferred ≠ physical (warning diagram)

---

## Chapter 7: Stability

- Stability notions comparison:
  - Lyapunov
  - Asymptotic
  - Exponential
  - BIBO
- State trajectories under stable dynamics
- Marginally stable trajectories
- Lyapunov function geometry (shrinking ellipsoids) **HIGH PRIORITY**
- Lyapunov equation as energy balance
- Hidden unstable mode via cancellation
- Internal instability vs BIBO stability

---

## Chapter 8: Realization Theory

- Transfer function → realization pipeline
- Proper vs strictly proper realization
- Realization non-uniqueness (cloud of realizations)
- Minimal realization selection
- Hankel matrix → state dimension
- Markov parameters filling Hankel matrix

---

## Chapter 9: Polynomial & Rational Matrix Theory

- Polynomial matrix acting on module
- Field vs ring scalars (vector space vs module)
- Unimodular transformation as basis change
- Smith normal form (polynomial case)
- Smith–McMillan form (rational case) **HIGH PRIORITY**
- Invariant factors vs diagonal entries
- Zeros and poles as structural invariants
- Coprime factorization geometry

---

## Chapter 10: Zeros & System Structure

- Poles vs zeros vs transmission zeros
- Signal blocking at a zero
- Zero as invariant subspace decoupled from I/O
- MIMO zero blocking paths
- Zero vs resonance interpretation
- Physical meaning of zeros in passive networks

---

## Appendix: Algebraic Tools

- Coprime vs non-coprime polynomials
- Bézout identity schematic
- Sylvester matrix / resultant intuition
- Module vs vector space comparison
- Cancellation vs factorization

---

## Image Creation Notes (Deferred)

- Prefer SVG or high-resolution PNG
- Use consistent visual language (colors, arrows, labels)
- Avoid embedding equations directly into images where possible
- Images should remain readable on mobile screens
- Test each image in Anki before bulk creation

---

## Status Tracking (to be filled later)

- [ ] Pilot images created
- [ ] Tested in Anki
- [ ] Revised after first study cycle
- [ ] Pruned / merged low-value figures
