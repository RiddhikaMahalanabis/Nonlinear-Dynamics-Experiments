# Van der Pol Oscillator

The **van der Pol oscillator** is a classical nonlinear system originally introduced to model self-sustaining oscillations in electrical circuits with vacuum tubes.  
It is one of the most fundamental examples of a **limit cycle oscillator**: trajectories starting from different initial conditions converge to a unique stable periodic orbit.

---

## Governing Equation

The van der Pol oscillator is defined by the second-order ODE:

\[
\ddot{x} - \mu (1 - x^2)\dot{x} + x = 0
\]

where:

| Symbol | Meaning | Typical value |
|:-------:|:---------|:---------------|
| \( \mu \) | nonlinearity / damping parameter | 0.5 – 5.0 |

### First-order form
To integrate numerically, we rewrite it as a system:

\[
\dot{x} = y
\]

\[
\dot{y} = \mu (1 - x^2) y - x
\]

When:
- \( \mu = 0 \): reduces to a simple harmonic oscillator.
- \( \mu > 0 \): exhibits nonlinear damping leading to a stable limit cycle.


---

##  Dynamics

The parameter \( \mu \) controls the nonlinearity:

### Small μ (e.g., μ = 0.5)
- Oscillation is nearly sinusoidal  
- Oscillator behaves almost linearly

### Large μ (e.g., μ ≥ 5)
- Strong nonlinear damping  
- Trajectory develops fast and slow timescales  
- The limit cycle becomes relaxation oscillations (sharp peaks and slow intervals)

### Key characteristics
- Single, stable limit cycle for all μ > 0  
- Nonlinear, state-dependent damping  
- Classic example in:
  - Nonlinear dynamics
  - Biological oscillations (heartbeats, circadian rhythms)
  - Control theory

---
