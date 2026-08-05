---
layout: default
title: LabStore
permalink: /labstore/
---

# GSRL LabStore

### Advanced Control Engineering & Digital Twins
**Morelia, Michoacán, México · Scientific Director: Eduardo Hernández-Morales (IEEE Member)**

Official store for software components, mission-critical simulators, and real-time spectral validation tools from GSRL. Technologies backed by publications in *IEEE Access* and preprints indexed on *Zenodo*.

<div class="card" style="border-color: var(--warn)">
⚠️ <strong>Note:</strong> Purchase buttons are placeholders. Replace <code>href="#"</code> with your actual link from Gumroad, Stripe Payment Link, or Lemon Squeezy in <code>labstore.md</code> before publishing.
</div>

## 1. Interactive Simulators (Digital Twins)

<div class="product">
  <div class="product-header">
    <h3>SIM-01 · Ultra-Realistic Drone Simulator</h3>
    <span class="product-tag">LMI H∞ vs PID</span>
  </div>
  <p>Professional quadrotor simulator with full 6-DOF dynamics. Exposes PID vulnerability against robust control under severe wind perturbations, sensor noise, and critical motor failures.</p>
  <p><strong>Stack:</strong> C++ (2,000+ lines) · Python · MATLAB. <strong>Deliverables:</strong> source code, 90-page technical manual, theoretical foundations, and Tuning Guide.</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Basic</div>
      <div class="tier-price">$149 USD</div>
      <a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">Buy</a>
    </div>
    <div class="tier">
      <div class="tier-name">Professional</div>
      <div class="tier-price">$299 USD</div>
      <a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">Buy</a>
    </div>
    <div class="tier">
      <div class="tier-name">Enterprise</div>
      <div class="tier-price">$2,999 USD</div>
      <a href="#" class="buy-btn secondary" style="color: #ffffff !important; background-color: #374151; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">Contact</a>
    </div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>SIM-02 · Satellite Attitude Control Simulator</h3>
    <span class="product-tag">HSB Guardian</span>
  </div>
  <p>Digital twin of a 6U CubeSat with quaternion kinematics and RK45 solver. Simulates atmospheric drag, solar radiation pressure, magnetic torque, and gravity gradient, with native HSB Guardian protection layer.</p>
  <p><strong>Validation:</strong> Backed by the <em>IEEE Access</em> paper (tag <code>hdzme001d</code>). Certifies 395 stabilization interventions with latency &lt; 1 ms. <strong>Stack:</strong> Python (~730 lines).</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Academic / Commercial</div>
      <div class="tier-price">$500 – $3,000 USD</div>
      <a href="#" class="buy-btn secondary" style="color: #ffffff !important; background-color: #374151; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">Request Quote</a>
    </div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>SIM-03 · Ultra-Realistic CSTR Reactor Simulator</h3>
  </div>
  <p>Dynamic simulator of a Continuous Stirred-Tank Reactor (CSTR) with coupled thermodynamic balance. Employs the critical $\Gamma_{11}$ invariant to detect and mitigate thermal runaway scenarios in under 100 ms.</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Based on Plant Scale</div>
      <div class="tier-price">$300 – $2,500 USD</div>
      <a href="#" class="buy-btn secondary" style="color: #ffffff !important; background-color: #374151; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">Request Quote</a>
    </div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>SIM-04 · HSB vs LMI Mini Demo</h3>
    <span class="product-tag">Lead Magnet</span>
  </div>
  <p>Lightweight spectral comparison module for drones. Generates <code>data_hsb.csv</code>, <code>data_lmi.csv</code>, and automated comparative PNG charts.</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Free</div>
      <div class="tier-price">$0</div>
      <a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #059669; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">Download</a>
    </div>
    <div class="tier">
      <div class="tier-name">Extended</div>
      <div class="tier-price">$9 – $19 USD</div>
      <a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">Buy</a>
    </div>
  </div>
</div>

## 2. Code Toolkits & Control Suites

<div class="product">
  <div class="product-header"><h3>TK-01 · LMI H∞ Controller Toolkit</h3></div>
  <p>Cross-platform framework for automated robust controller design via LMIs with global optimality guarantees ($\|T_{zw}\|_\infty < \gamma$). Support: MATLAB, Python, C++ (Simulink generator included).</p>
  <div class="price-tiers">
    <div class="tier"><div class="tier-name">Student</div><div class="tier-price">$25 – $40 USD</div><a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Buy</a></div>
    <div class="tier"><div class="tier-name">Departmental</div><div class="tier-price">$120 – $200 USD</div><a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Buy</a></div>
    <div class="tier"><div class="tier-name">Commercial</div><div class="tier-price">$200 – $400 USD</div><a href="#" class="buy-btn secondary" style="color: #ffffff !important; background-color: #374151; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Contact</a></div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>TK-02 · HSB + Gamma Diagnostics + OCS Supervisor Suite</h3>
    <span class="product-tag">Flagship Product</span>
  </div>
  <p>Real-time spectral monitoring system. Supervisory layer operating on legacy controllers without altering their nominal certification.</p>
  <ul>
    <li><strong>HSB Guardian:</strong> Stability certification in &lt; 1 ms, $\mathcal{O}(n^2)$.</li>
    <li><strong>Gamma Diagnostics:</strong> Multivariable monitoring ($\Gamma_{11}$, $\Gamma_{58}$, $\Gamma_2$).</li>
    <li><strong>OCS Supervisor:</strong> Autonomous corrective actions under Lyapunov guarantees.</li>
  </ul>
  <div class="price-tiers">
    <div class="tier"><div class="tier-name">Academic</div><div class="tier-price">$35 – $60 USD</div><a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Buy</a></div>
    <div class="tier"><div class="tier-name">Per Industrial Plant</div><div class="tier-price">$10,000 – $50,000 USD</div><a href="#" class="buy-btn secondary" style="color: #ffffff !important; background-color: #374151; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Contact</a></div>
    <div class="tier"><div class="tier-name">Embedded Royalty</div><div class="tier-price">$500 – $5,000 USD</div><a href="#" class="buy-btn secondary" style="color: #ffffff !important; background-color: #374151; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Contact</a></div>
  </div>
</div>

<div class="product">
  <div class="product-header"><h3>TK-03 · MRAC Complete Toolkit</h3></div>
  <p>Model Reference Adaptive Control (MIT rule + Lyapunov stability). Includes RMSE and settling time metrics.</p>
  <div class="price-tiers">
    <div class="tier"><div class="tier-name">Academic</div><div class="tier-price">$20 – $30 USD</div><a href="#" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Buy</a></div>
    <div class="tier"><div class="tier-name">Commercial</div><div class="tier-price">$150 – $300 USD</div><a href="#" class="buy-btn secondary" style="color: #ffffff !important; background-color: #374151; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold;">Contact</a></div>
  </div>
</div>

## 3. Promotional Bundles

| Bundle | Components | Academic Price | Commercial Price |
|---|---|---|---|
| **Gamma EDU** | PID + LMI H∞ Toolkit + MRAC Complete | $1,000 USD | N/A |
| **Gamma PRO** | LMI Toolkit + MRAC Toolkit + HSB & Gamma Diagnostics Suite | Inquire | $25,000 USD |
| **Gamma ENTERPRISE** | Full catalog access + priority support + unrestricted commercial license | N/A | $60,000+ USD |

---

> **Note:** 80% of listed technologies derive directly from consolidated numerical frameworks and active production mathematical simulations. For corporate quotes, NDAs, or custom integrations, contact **gammasystemsresearchlab@gmail.com** directly.
