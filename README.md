# Dynamical-system-for-power-law-fluid
# Peristalsis of a Power-Law Fluid — Dynamical System Code


Makhdoom, Ehsan, Hussain & Asghar (2023). Utilization of entire new dynamical system approach for peristalsis of Power law fluid with temperature-dependent viscosity. *Waves in Random and Complex Media*.

## Files

| File | Description |
|---|---|
| `psi_field.m` | Closed-form stream function (paper Eq. 49) |
| `phase_portrait.m` | Streamline plots (like Figs. 5-7) |
| `find_critical_points.m` | Locates and classifies centers and saddles |
| `bifurcation_diagram.m` | Bifurcation plots (like Fig. 8) |

## How to run

Run in this order:

1. `find_critical_points.m` locates and classifies equilibria
2. `phase_portrait.m` produces Figures 5-7
3. `bifurcation_diagram.m` produces Figure 8

Requires MATLAB R2020a or later.

## Parameters

The paper uses power-law index \(n = 0.5, 1.0, 1.5\) and flow rates for backward, trapping, and augmented regimes. See the paper for the full parameter set.

## License

MIT License. See `LICENSE` for details.
