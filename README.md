# Badr Elsayed

Mechanical engineering senior (aerospace minor) at NYU Tandon, applying to aerospace engineering M.S. programs for Fall 2027. I’m interested in high-speed aerodynamics and propulsion for rockets and spacecraft. I write my own simulations to understand the physics, validating them against theory and published data.

📫 badrelsayed@nyu.edu · [LinkedIn](https://www.linkedin.com/in/badr-elsayed/)

---

## Projects

| Project | What it does | Focus |
|---|---|---|
| [**Euler Flow Solver: Shock Tubes & Blunt Bodies**](https://github.com/badrelsayedNYU/shock-tube-solver) · [Shock Tube Lab](https://badrelsayednyu.github.io/shock-tube-solver/) · [1D studies](https://badrelsayednyu.github.io/shock-tube-solver/studies.html) | Compares Rusanov, Roe, and HLLC fluxes with MUSCL limiters against the exact 1D Riemann solution. A 2D cylinder extension checks bow-shock standoff against Billig’s correlation and stagnation pressure against the exact pitot value (within 0.2% at Mach 2–6), and demonstrates HLLC’s carbuncle instability at Mach 6. 65 automated tests. | High-speed CFD |
| [**Vortex Panel Method Airfoil Solver**](https://github.com/badrelsayedNYU/vortex-panel-solver) · [Airfoil app](https://vortex-panel-solver.streamlit.app/) | Linear-strength vortex panel solver for 2D airfoils with Kármán–Tsien critical-Mach analysis and an interactive airfoil analysis app, validated against an exact Kármán–Trefftz solution, thin-airfoil theory, and XFOIL. The app includes streamlines, pressure fields, panel convergence and validation comparisons. | Computational aerodynamics |
| [**Reentry Heating & TPS Thermal Model**](https://github.com/badrelsayedNYU/reentry-tps) · [Heat Shield Sizer](https://badrelsayednyu.github.io/reentry-tps/) | Sizes a capsule heat shield from an entry trajectory, Sutton–Graves heating, and multi-layer conduction. For the baseline entry, 7.03 cm of LI-900 meets the bondline limit but exceeds the tile’s surface limit; FRCI-12 is the lightest of the three tiles studied that stays within both limits. The browser app re-sizes the shield, compares materials, plots temperature through the wall, and runs parameter studies. | Aerothermodynamics |
| [**Liquid Rocket Engine Design Tool**](https://github.com/badrelsayedNYU/rocket-engine-design) · [Engine Design app](https://rocket-engine-design.streamlit.app/) | Designs a liquid bipropellant engine from top-level requirements: NASA CEA thermochemistry, isentropic nozzle theory, a Rao bell contour, divergence and efficiency losses, and Bartz heat flux with a regenerative-cooling capacity check. Validated against sourced RS-25 and RL10B-2 data: delivered vacuum Isp is within 2.7% and 1.7%, and ideal shifting-equilibrium Isp lies above both, as it must. The Merlin 1D is included as an illustrative gas-generator case. The app sizes an engine, plots its contour and heat flux, and compares it to real engines. 191 automated tests. | Propulsion system design |

## Research

Ongoing group work. The public code is the four projects above.

- **Undergraduate Researcher, High-Speed CFD** (NYU Tandon, Prof. Nicholas DiZinno, Sept 2026–present): extending a strongly implicit incompressible-flow method to the supersonic blunt-body problem: bow shock, shock standoff, and the mixed subsonic–supersonic region.
- **Aerodynamics Lead, Smart Rotor Load Control** (NYU Tandon senior design, Aug 2026–present): 3D rotating-frame and dynamic-mesh CFD in ANSYS Fluent, plus OpenFAST BEM modeling for a trailing-edge-flap controller on a scaled NREL 5-MW turbine.
- **Propulsion Lead, AIAA Design/Build/Fly** (NYU, Nov 2025–present).

## Tools

Python (NumPy, SciPy, Matplotlib) · MATLAB/Simulink · C++ · ANSYS Fluent · OpenFAST · XFOIL · SolidWorks · CATIA · Git
