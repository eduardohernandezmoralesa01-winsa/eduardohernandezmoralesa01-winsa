---
layout: default
title: Productos & Publicaciones
permalink: /productos/
---
# Products & Scientific Publications

### Advanced Control Engineering, Digital Twins & Spectral Stability
*Morelia, Michoacán, México · Scientific Director: Eduardo Hernández-Morales 

Official catalog of software components, mission-critical simulators, publishing solutions, and real-time spectral validation tools from GSRL. Our technologies are backed by high-impact publications and indexed preprints.

## Scientific Publications

*The theoretical and mathematical foundation of the laboratory is completely open, auditable, and transparent for the scientific and industrial community.*

<div class="card">
  <strong>PUB-01 — IEEE Access (Published)</strong>
  <p><em>Real-Time Spectral Stability Guardian for Satellite Attitude Control: Ultra-Fast Validation with Quaternion Dynamics</em> <span class="product-tag">hdzme001d</span></p>
  <p style="margin:0">First experimental validation of the HSB framework in satellite attitude control. Certifies 395 active interventions with pointing error below specification.</p>
</div>

<div class="card">
  <strong>PUB-02 — IEEE TAC (In preparation)</strong>
  <p><em>HSB-Gamma: A Spectral Framework for LMI-Free Nonlinear Robust Stability and Control Synthesis</em></p>
  <p style="margin:0">Unified HSB + Gamma framework featuring four primary invariants as foundational geometric tools (~1,657 lines in LaTeX).</p>
</div>

<div class="card">
  <strong>PUB-03 — SIAM SICON (In preparation / Resubmission)</strong>
  <p><em>Gamma Dominant Invariant for Riemannian Manifolds with Stochastic Extensions</em></p>
  <p style="margin:0">Extension of the Gamma dominant invariant to Riemannian manifolds with stochastic perturbations for nonholonomic systems.</p>
</div>

<div class="card">
  <strong>PUB-04 — Zenodo Preprint (Published with DOI)</strong>
  <p><em>Hermitian Spectral Bound Framework</em> (preprint 2025)</p>
  <p style="margin:0">Establishes the intellectual priority of the laboratory and serves as the baseline mathematical reference for the entire portfolio.</p>
</div>

---

## Interactive Simulators (Digital Twins)

*High-fidelity mathematical models packaged for simulation, dynamic analysis, and conceptual industrial deployment.*

### SIM-01: Ultra-Realistic Drone Simulator (LMI $H_\infty$ vs PID)
Professional quadrotor simulator with full 6-DOF dynamics and realistic perturbations (wind, sensor noise, motor failure). Side-by-side comparisons of classic PID versus robust control.

**Technical stack:** C++ core engine (2,000+ lines) + Python visualization + MATLAB analysis. **Deliverables:** source code, 90-page manual, Theory PDF, and Tuning Guide.

### SIM-02: Satellite Attitude Control Simulator (HSB Guardian)
Digital twin of a 6U CubeSat with quaternion kinematics, RK45 integration, and full orbital perturbations. Integrates the real-time HSB Guardian. Closed-loop latency &lt; 1 ms for critical pointing maneuvers. **Pricing:** $500 – $3,000 USD.

### SIM-03: Ultra-Realistic CSTR Reactor Simulator
CSTR chemical reactor simulator featuring a full thermodynamic model and runaway risk tracking. Uses the critical $\Gamma_{11}$ invariant to detect and prevent explosions in under 100 ms. **Pricing:** $300 – $2,500 USD.

### SIM-04: HSB vs LMI Mini Demo (Lead Magnet)
Compact spectral comparison demo that automatically exports `data_hsb.csv`, `data_lmi.csv`, and report-ready charts. **Pricing:** Free / $9 – $19 USD.

<p style="margin-top: 20px;">
  <a href="{{ '/labstore/' | relative_url }}" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 12px 24px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">
    View Full Pricing & Purchase Links in LabStore &rarr;
  </a>
</p>

---

## Technical Books (In Production)

- **Hermitian Spectral Bound: Theory, Proofs and Applications** — Hermitian linear algebra, closed-form analytical bounds, and stochastic extensions. $40 – $80 USD.
- **Gamma Theory: 314 Spectral Invariants for Nonlinear Control** — Axiomatic and geometric foundations of the 314 primary and secondary spectral invariants. $50 – $90 USD.
- **Satellite Attitude Control: HSB Guardian for CubeSats** — Aerospace implementation guide based on quaternions and the IEEE Access paper. $45 – $90 USD.

## Online Courses (In Production)

- **LMI $H_\infty$ Control in Python: From Zero to Controller** (3–4 hrs) — $29 – $49 USD.
- **Control System Design: A Unified Framework** (PID → LMI → MRAC → HSB, 10–12 hrs) — $79 – $129 USD.
- **Industrial Process Safety with HSB + Gamma + OCS** (15–18 hrs) — $1,000 – $5,000 USD (Corporate).

---

> **Licensing & IP Note:** 80% of our catalog content derives directly from consolidated software, active simulations, and laboratory-published papers. For critical hardware integrations or access to the OCS mathematical core, requests are subject to a Non-Disclosure Agreement (NDA). Contact us at **gammasystemsresearchlab@gmail.com**.
