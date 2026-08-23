# Dynamical-system-for-power-law-fluid
# Peristalsis of a Power-Law Fluid — Dynamical System Code

MATLAB code accompanying the analysis of:

> Makhdoom, Ehsan, Hussain & Asghar (2023). *Utilization of entire new
> dynamical system approach for peristalsis of Power law fluid with
> temperature-dependent viscosity.* Waves in Random and Complex Media.

 dynamical_system/
    ├── psi_field.m                    <- closed-form stream function (paper Eq. 49)
    ├── phase_portrait.m               <- streamline plots (like Figs. 5-7)
    ├── find_critical_points.m         <- locates & classifies centers/saddles
    └── bifurcation_diagram.m          <- bifurcation plots (like Fig. 8)
