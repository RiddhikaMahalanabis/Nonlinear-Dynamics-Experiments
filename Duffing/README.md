# Duffing Oscillator

The **Duffing oscillator** is a classical example of a nonlinear system that exhibits both periodic and chaotic behavior depending on the system parameters.  
It models the motion of a damped, driven oscillator with a nonlinear restoring force.

---

## 🧩 Governing Equation


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

## 🧮 Dynamics

- The system reduces to a **linear harmonic oscillator** when $\beta = 0$.
- For  $\alpha < 0$ and  $\beta > 0$ , the potential has a **double-well** shape.
- Depending on $\gamma$ (the forcing amplitude), the oscillator can show:
  - Periodic motion (small forcing)
  - Period-doubling
  - Chaotic motion (large forcing)

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

## Example results : Phase portrait for $\gamma = 0.3$, $\omega = 1.2$ :

<p align="center">
  <img src="https://github.com/RiddhikaMahalanabis/Nonlinear-Dynamics-Experiments/blob/main/Duffing_PP.png?raw=true" width="400">
</p>

