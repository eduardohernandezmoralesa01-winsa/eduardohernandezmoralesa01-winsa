---
layout: default
title: LabStore
permalink: /labstore.md/
---

# GSRL LabStore

### Advanced Control Engineering & Digital Twins
**Morelia, Michoacán, México · Director Científico: Eduardo Hernández-Morales (IEEE Member)**

Tienda oficial de componentes de software, simuladores de misión crítica y herramientas de validación espectral en tiempo real de GSRL. Tecnologías respaldadas por publicaciones en *IEEE Access* y preprints indexados en *Zenodo*.

<div class="card" style="border-color: var(--warn)">
⚠️ <strong>Nota:</strong> los botones de compra son marcadores de posición. Reemplaza <code>href="#"</code> por tu enlace real de Gumroad, Stripe Payment Link o Lemon Squeezy en <code>labstore.md</code> antes de publicar.
</div>

## 1. Simuladores Interactivos (Digital Twins)

<div class="product">
  <div class="product-header">
    <h3>SIM-01 · Ultra-Realistic Drone Simulator</h3>
    <span class="product-tag">LMI H∞ vs PID</span>
  </div>
  <p>Simulador profesional de quadrotor con dinámica completa 6-DOF. Expone la vulnerabilidad del PID frente al control robusto bajo perturbaciones severas de viento, ruido de sensores y fallos críticos de motor.</p>
  <p><strong>Stack:</strong> C++ (2,000+ líneas) · Python · MATLAB. <strong>Entregables:</strong> código fuente, manual técnico de 90 pp., fundamentación teórica y Tuning Guide.</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Basic</div>
      <div class="tier-price">$149 USD</div>
      <a href="#" class="buy-btn">Comprar</a>
    </div>
    <div class="tier">
      <div class="tier-name">Professional</div>
      <div class="tier-price">$299 USD</div>
      <a href="#" class="buy-btn">Comprar</a>
    </div>
    <div class="tier">
      <div class="tier-name">Enterprise</div>
      <div class="tier-price">$2,999 USD</div>
      <a href="#" class="buy-btn secondary">Contactar</a>
    </div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>SIM-02 · Satellite Attitude Control Simulator</h3>
    <span class="product-tag">HSB Guardian</span>
  </div>
  <p>Gemelo digital de un CubeSat 6U con cinemática de cuaterniones y resolvedor RK45. Simula arrastre atmosférico, presión de radiación solar, torque magnético y gradiente gravitacional, con la capa de protección del Guardián HSB nativa.</p>
  <p><strong>Validación:</strong> respaldado por el paper de <em>IEEE Access</em> (tag <code>hdzme001d</code>). Certifica 395 intervenciones de estabilización con latencia &lt; 1 ms. <strong>Stack:</strong> Python (~730 líneas).</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Académico / Comercial</div>
      <div class="tier-price">$500 – $3,000 USD</div>
      <a href="#" class="buy-btn secondary">Solicitar cotización</a>
    </div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>SIM-03 · Ultra-Realistic CSTR Reactor Simulator</h3>
  </div>
  <p>Simulador dinámico de un reactor de tanque agitado continuo (CSTR) con balance termodinámico acoplado. Emplea el invariante crítico $\Gamma_{11}$ para detectar y mitigar escenarios de desbocamiento térmico en menos de 100 ms.</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Según escala de planta</div>
      <div class="tier-price">$300 – $2,500 USD</div>
      <a href="#" class="buy-btn secondary">Solicitar cotización</a>
    </div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>SIM-04 · HSB vs LMI Mini Demo</h3>
    <span class="product-tag">Lead Magnet</span>
  </div>
  <p>Módulo ligero de comparación espectral para drones. Genera <code>data_hsb.csv</code>, <code>data_lmi.csv</code> y gráficos comparativos automáticos en PNG.</p>
  <div class="price-tiers">
    <div class="tier">
      <div class="tier-name">Gratuito</div>
      <div class="tier-price">$0</div>
      <a href="#" class="buy-btn">Descargar</a>
    </div>
    <div class="tier">
      <div class="tier-name">Extendida</div>
      <div class="tier-price">$9 – $19 USD</div>
      <a href="#" class="buy-btn">Comprar</a>
    </div>
  </div>
</div>

## 2. Toolkits de Código y Suites de Control

<div class="product">
  <div class="product-header"><h3>TK-01 · LMI H∞ Controller Toolkit</h3></div>
  <p>Framework multi-plataforma para diseño automatizado de controladores robustos mediante LMIs con garantías globales de optimalidad ($\|T_{zw}\|_\infty < \gamma$). Soporte: MATLAB, Python, C++ (generador de Simulink incluido).</p>
  <div class="price-tiers">
    <div class="tier"><div class="tier-name">Estudiante</div><div class="tier-price">$25 – $40 USD</div><a href="#" class="buy-btn">Comprar</a></div>
    <div class="tier"><div class="tier-name">Departamental</div><div class="tier-price">$120 – $200 USD</div><a href="#" class="buy-btn">Comprar</a></div>
    <div class="tier"><div class="tier-name">Comercial</div><div class="tier-price">$200 – $400 USD</div><a href="#" class="buy-btn secondary">Contactar</a></div>
  </div>
</div>

<div class="product">
  <div class="product-header">
    <h3>TK-02 · HSB + Gamma Diagnostics + OCS Supervisor Suite</h3>
    <span class="product-tag">Producto insignia</span>
  </div>
  <p>Sistema de monitoreo espectral en tiempo real. Capa de supervisión que opera sobre controladores heredados sin alterar su certificación nominal.</p>
  <ul>
    <li><strong>HSB Guardian:</strong> certificación de estabilidad en &lt; 1 ms, $\mathcal{O}(n^2)$.</li>
    <li><strong>Gamma Diagnostics:</strong> monitoreo multivariable ($\Gamma_{11}$, $\Gamma_{58}$, $\Gamma_2$).</li>
    <li><strong>OCS Supervisor:</strong> acciones correctivas autónomas bajo garantías de Lyapunov.</li>
  </ul>
  <div class="price-tiers">
    <div class="tier"><div class="tier-name">Académico</div><div class="tier-price">$35 – $60 USD</div><a href="#" class="buy-btn">Comprar</a></div>
    <div class="tier"><div class="tier-name">Por planta industrial</div><div class="tier-price">$10,000 – $50,000 USD</div><a href="#" class="buy-btn secondary">Contactar</a></div>
    <div class="tier"><div class="tier-name">Royalty embebido</div><div class="tier-price">$500 – $5,000 USD</div><a href="#" class="buy-btn secondary">Contactar</a></div>
  </div>
</div>

<div class="product">
  <div class="product-header"><h3>TK-03 · MRAC Complete Toolkit</h3></div>
  <p>Control Adaptativo por Modelo de Referencia (regla MIT + estabilidad Lyapunov). Incluye métricas RMSE y settling time.</p>
  <div class="price-tiers">
    <div class="tier"><div class="tier-name">Académico</div><div class="tier-price">$20 – $30 USD</div><a href="#" class="buy-btn">Comprar</a></div>
    <div class="tier"><div class="tier-name">Comercial</div><div class="tier-price">$150 – $300 USD</div><a href="#" class="buy-btn secondary">Contactar</a></div>
  </div>
</div>

## 3. Bundles Promocionales

| Bundle | Componentes | Precio Académico | Precio Comercial |
|---|---|---|---|
| **Gamma EDU** | PID + LMI H∞ Toolkit + MRAC Complete | $1,000 USD | N/A |
| **Gamma PRO** | LMI Toolkit + MRAC Toolkit + HSB & Gamma Diagnostics Suite | Consultar | $25,000 USD |
| **Gamma ENTERPRISE** | Acceso total al catálogo + soporte prioritario + licencia comercial irrestricta | N/A | $60,000+ USD |

---

> **Nota:** el 80% de las tecnologías listadas se derivan directamente de frameworks numéricos consolidados y simulaciones matemáticas en producción. Para cotizaciones corporativas, NDA o integraciones a medida, contacta directamente a **gammasystemsresearchlab@gmail.com**.
