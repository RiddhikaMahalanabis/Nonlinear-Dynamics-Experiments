# Duffing Oscillator

The **Duffing oscillator** is a classical example of a nonlinear system that exhibits both periodic and chaotic behavior depending on the system parameters.  
It models the motion of a damped, driven oscillator with a nonlinear restoring force.

---

## Governing Equation


$\ddot{x} + \delta \dot{x} + \alpha x + \beta x^3 = \gamma \cos(\omega t)$


where:

| Symbol | Meaning | Typical value |
|:-------:|:---------|:---------------|
|  $\delta$  | damping coefficient | 0.2 |
|  $\alpha$  | linear stiffness | -1.0 |
|  $\beta$  | nonlinear stiffness | 1.0 |
|  $\gamma$  | driving amplitude | 0.3 |
|  $\omega$  | driving frequency | 1.2 |

---

## Dynamics

- The system reduces to a **linear harmonic oscillator** when $\beta = 0$.
- For  $\alpha < 0$ and  $\beta > 0$ , the potential has a **double-well** shape.
- Depending on $\gamma$ (the forcing amplitude), the oscillator can show:
  - Periodic motion (small forcing)
  - Period-doubling
  - Chaotic motion (large forcing)

---
## Dynamical Regimes

The Duffing oscillator exhibits qualitatively different behavior depending on the forcing amplitude $\gamma$.

### Periodic regime ($\gamma = 0.2$)

The system oscillates regularly within a single well of the potential.

### Chaotic regime ($\gamma = 0.3$)

The motion becomes aperiodic and explores both wells, leading to a strange attractor in phase space.

### Time evolution comparison :

<img src="Time_series_comparison.png" width="800" alt="Alt text">

### Phase portrait comparison :
<img src="Phase_portrait_comparison.png" width="800" alt="Alt text">

### Poincare section comparison :
<img src="poincare_comparison.png" width="800" alt="Alt text">

---

## Files in this Folder

| File | Description |
|------|--------------|
| `duffing.ipynb` | Colab-ready notebook for visualizing time series, phase portraits and more|
| `README.md` | Describes the system and how to use the code. |

---

## Typical Outputs

- **Time series** showing oscillatory or chaotic motion.  
- **Phase portrait** showing the attractor in \((x, \dot{x})\)-space.  

---


