# 🌌 GCAT: Quantum Gravity as Topological Aliasing
### Informational Friction and Saturation of the Local Kinematic Limit

> **A unified solution to the Hubble ($H_0$) and $S_8$ tensions based on Non-Commutative Geometry and void percolation.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Open in Colab](https://img.shields.io/badge/Jupyter-Open_in_Colab-F37626?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/NachoPeinador/GCAT-Cosmology-Validation/blob/main/Notebooks/GCAT_Analysis_en.ipynb)
[![Papers](https://img.shields.io/badge/Paper-Read_PDF-B31B1B?style=flat&logo=latex&logoColor=white)](https://github.com/NachoPeinador/GCAT-Cosmology-Validation/blob/main/Papers/GCAT_Paper_en.pdf) [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.PLACEHOLDER-0099CC?style=flat&logo=zenodo&logoColor=white)](https://doi.org/)
[![Leer en Español](https://img.shields.io/badge/Language-Leer_en_Español-c62828?style=flat&logo=google-translate&logoColor=white)](https://github.com/NachoPeinador/GCAT-Cosmology-Validation/blob/main/README_ES.md)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--1822--3452-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0008-1822-3452) [![X](https://img.shields.io/badge/-%40todos__lumpen-000000?style=flat&logo=x&logoColor=white)](https://twitter.com/todos_lumpen)

<p align="center">
  <img src="/Images/Aliasing.png" alt="Representación conceptual del Aliasing Topológico y la Burbuja Local" width="100%">
</p>

## 🎯 Executive Summary (TL;DR)

**GCAT (Quantum Gravity as Topological Aliasing)** proposes a paradigm shift: Dark Energy is not an unknown fluid, but the **thermodynamic cost** of processing information in a discrete spacetime.

Accelerated expansion arises from **informational friction**: the mismatch between the optimal volume encoding (ternary base, $\mathbb{Z}/3\mathbb{Z}$) and the forced holographic boundary encoding (binary base, $\mathbb{Z}/2\mathbb{Z}$).

This repository contains the **Bayesian validation pipeline** demonstrating that:
1.  This effect activates upon saturating the local kinematic limit ($D_c \approx 70$ Mpc).
2.  It resolves both the Hubble and $S_8$ tensions simultaneously.
3.  It does so **from first principles**, without ad-hoc free parameters.
---

## 📐 The Master Formulas: From Bit to Cosmos

GCAT derives cosmic acceleration through a strict logical chain, without tuning free parameters.

### Step 1: Microscopic Aliasing ($R_{\text{fund}}$)
Represents pure informational "friction." It arises from the incompatibility between number bases, fixed by vacuum topology:
* **$\xi = 1/6$**: Conformal coupling (dictated by KO-dimension 6).
* **$\mathcal{S} = \log_2 3$**: Cost of translating trits (volume) to bits (boundary).

$$R_{\text{fund}} = \frac{\xi}{\log_2 3} = \frac{1/6}{\log_2 3} \approx 0.10515$$

### Step 2: The Universal Dynamic Constant ($\kappa$)
For this microscopic effect to act on 4D spacetime expansion, it must be dimensionally projected. We use the projection factor **$\beta = 3/4$** (spatial volume $d=3$ onto spacetime manifold $d=4$):

$$\kappa \equiv 2\beta R_{\text{fund}} = 2 \cdot \frac{3}{4} \cdot R_{\text{fund}} = \frac{\ln 2}{4 \ln 3} \approx 0.1578$$

> **Result:** This constant $\kappa \approx 15.78\%$ replaces arbitrary Dark Energy. It is a fixed geometric value that, when introduced into the Friedmann equations, exactly reproduces the observed acceleration.

---

### 📊 Main Results

#### 1. Tension Resolution
The model eliminates statistical discrepancies between the early and late universe:

| Metric | ΛCDM Value (Planck) | Observed Value | **GCAT Prediction** | **Status** |
|:---|:---:|:---:|:---:|:---:|
| **Hubble (H₀)** | 67.4 ± 0.5 | 73.04 ± 1.04 | **73.52 ± 1.04** | ✅ **Resolved (0.46σ)** |
| **Structure (S₈)** | 0.834 ± 0.01 | 0.766 ± 0.02 | **0.782 ± 0.01** | ✅ **Resolved (0.74σ)** |
| **Global Fit** | χ² = 1601.3 | -- | **Δχ² = -18.6** | 📉 **Better Fit** |
| **Evidence** | Ref (0) | -- | **ΔBIC < -10** | 🏆 **Very Strong** |

#### 2. Inferred Physical Parameters
The MCMC analysis does not just fit curves; it reveals the physical structure of the transition:

| Parameter | Inferred Value (Median) | Physical Interpretation |
|:---|:---:|:---|
| **Transition ($z_c$)** | **0.0170 ± 0.001** | Onset of void percolation (very recent). |
| **Scale ($D_c$)** | **70.23 Mpc** | Saturation of the kinematic limit (*CosmicFlows-4*). |
| **Mass ($m_{info}$)** | **~10⁻³³ eV** | Effective mass of the information field. |

---

## ⚛️ Theoretical Foundations: From Quantum to Cosmic

GCAT does not add "dark fluids" to the universe. Instead, it identifies an emergent property of discrete spacetime acting as an entropic force.

### 1. Vacuum Structure (Non-Commutative Geometry)
To accommodate the Standard Model of particles, the internal geometry of spacetime requires a **KO-dimension 6**. This imposes a cyclic modular structure ($\mathbb{Z}/6\mathbb{Z}$) on the microscopic fabric of the vacuum, defining its fundamental "pixelation."

### 2. The Thermodynamic Conflict (Bulk vs. Boundary)
There is a fundamental tension in how the universe stores information:
* **The Volume (Bulk):** Maximizes thermodynamic efficiency by operating in **Base 3** (Optimal Radix $e \approx 2.718 \to 3$).
* **The Boundary (Horizon):** Is forced by the Holographic Principle to encode information in **Base 2** (Bits, Area).

### 3. Informational Friction and Effective Dynamics

GCAT replaces Dark Energy with a two-step mechanism: a topological cause and a dynamic effect.

#### A. The Cause: Topological Aliasing ($R_{\text{fund}}$)
At the microscopic level, translation between the volume (base 3) and the boundary (base 2) generates "noise" or a fundamental informational cost.
> **This is the thermodynamic origin of dark energy.**

$$R_{\text{fund}} = \frac{\text{Topological Coupling}}{\text{Conversion Cost}} = \frac{1/6}{\log_2 3} \approx 0.10515$$

#### B. The Effect: Universal Dynamic Constant ($\kappa$)
For this microscopic cost to accelerate the universe, it must be projected into 4D spacetime geometry. Applying the dimensional projection factor ($\beta = 3/4$) and the metric coupling ($2$), we obtain the effective constant that enters the equations:

$$\kappa \equiv \underbrace{2}_{\text{Metric}} \cdot \underbrace{\beta}_{\text{Projection } 3D \to 4D} \cdot R_{\text{fund}} = \frac{\ln 2}{4 \ln 3} \approx 0.1578$$

> **Result:** We do not tune Dark Energy. We calculate $\kappa \approx 15.78\%$ from first principles, and this fixed value reproduces the observed acceleration.

---

### 🌊 The Activation Mechanism: Percolation and Saturation
Why do we see this now and not in the early universe? GCAT introduces **Void Percolation** dynamics.

1.  **Early Phase:** The universe is dense. The effect is suppressed.
2.  **Phase Transition ($z_c \approx 0.017$):** Cosmic voids grow and touch (percolate). The void network becomes global.
3.  **Kinematic Saturation (70 Mpc):**
    The Bayesian analysis confirms that the transition occurs exactly when the local structure saturates the limits observed by **CosmicFlows-4** (Mazurenko et al., 2024).

> **Result:** Cosmic acceleration is not smooth but "turns on" upon reaching the saturation scale of $D_c \approx 70$ Mpc, explaining the Hubble tension as a local sampling effect.

---

## 💡 Conclusion: A New Cosmological Paradigm

The statistical evidence presented ($\Delta\chi^2 \approx -18.6$ vs ΛCDM) suggests that current tensions do not require exotic "new physics," but a **new ontology** of spacetime.

| Concept | Standard Paradigm (ΛCDM) | GCAT Paradigm (Informational) |
| :--- | :--- | :--- |
| **Origin of Acceleration** | Unknown fluid (Dark Energy) with constant negative pressure. | **Thermodynamic Cost** of processing information at the boundary (Friction). |
| **Nature of Space** | Continuous Riemannian geometry, smooth at all scales. | **Discrete and Modular Structure** ($\mathbb{Z}/6\mathbb{Z}$) derived from NCG. |
| **Hubble Tension ($H_0$)** | Statistical anomaly or local systematic error to be discarded. | **Topological Aliasing**: An inevitable sampling effect upon saturating the kinematic limit ($D_c$). |
| **Status of Local Data** | "Noisy" or contaminated by peculiar flows (often cut at $z < 0.02$). | **Fundamental Signal**: Saturation at 70 Mpc (*CosmicFlows-4*) reveals the phase transition. |

> **In summary:** The universe does not expand faster locally due to "extra energy," but because discrete spacetime imposes an **informational toll** when translating volume (base 3) to surface (base 2). The Hubble tension is simply the bill for that toll.

---

## 🚀 Reproducing Results

To ensure transparency and **exact numerical reproducibility** of the Bayesian (MCMC) results, the entire code has been unified into a single Jupyter Notebook.

### Option 1: Google Colab (Recommended)
This is the fastest and most reliable method. The notebook automatically handles dependency installation in the ephemeral environment.

1.  Click the **"Open in Colab"** button.[![Open in Colab](https://img.shields.io/badge/Jupyter-Open_in_Colab-F37626?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/NachoPeinador/GCAT-Cosmology-Validation/blob/main/Notebooks/GCAT_Analysis_en.ipynb)
2.  In the Colab menu, select **"Runtime"** > **"Run all"**.
3.  The system will perform the full analysis (approx. 1-2 minutes) and generate plots at the end.

### Option 2: Local Execution (Jupyter)
<details>
<summary><strong>👇 Click here if you prefer to run the analysis on your own machine:</strong></summary>

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/NachoPeinador/GCAT-Cosmology-Validation.git](https://github.com/NachoPeinador/GCAT-Cosmology-Validation.git)
    cd GCAT-Cosmology-Validation/Notebooks
    ```

2.  **Install dependencies:**
    Using a virtual environment is recommended. The critical libraries are:
    ```bash
    pip install numpy==2.0.0 scipy==1.14.1 emcee corner matplotlib "pillow<12.0" jupyterlab
    ```

3.  **Run:**
    Launch Jupyter and open the file `GCAT_Analysis_en.ipynb`:
    ```bash
    jupyter lab GCAT_Analysis_en.ipynb
    ```
</details>

---

## 🔮 Falsifiable Predictions

GCAT V9 makes specific quantitative predictions that distinguish it from ΛCDM and allow for short-term experimental verification:

1. **Gravitational Waves (Cavity Resonance):**
   Due to the modular structure of the void network, a characteristic attenuation is predicted in the Stochastic Gravitational Wave Background (SGWB) spectrum, centered at the local cavity's fundamental frequency:
   **f ≈ 1.38 × 10⁻¹⁶ Hz** (Corresponding to $\lambda \approx 70$ Mpc).

2. **Structure Growth (Euclid/DESI):**
   Predicts an abrupt drop in the structure growth rate (**fσ₈**) and fluctuation amplitude, deviating from General Relativity exclusively within the local bubble:
   **z < 0.05**.

3. **High-Frequency Transparency (LIGO/Virgo):**
   Unlike massive gravity theories that disperse waves, GCAT preserves local Lorentz invariance at small scales. It predicts **zero attenuation** and speed $c_g = c$ for compact astrophysical events:
   **f ~ 100 Hz** (Consistent with GW170817).

---

### 💡 Inspiration

> *"I consider it quite possible that physics cannot be based on the concept of field, that is, on continuous structures. In that case, nothing remains of my entire castle in the air, gravitation theory included, [and of] the rest of modern physics."* — **Albert Einstein**, Letter to Michele Besso (1954)

This project materializes Einstein's final intuition: it proposes that current cosmological tensions are not measurement errors, but evidence of a **discrete vacuum structure** that the continuous model (ΛCDM) is no longer capable of describing.

---

## 📂 Repository Structure
<details>
<summary><strong>👇 Click to view repository structure</strong></summary>

```text
GCAT-Cosmology-Validation/
├── 📂 Papers/
│   └── 📄 GCAT_Paper_en.pdf           # Scientific paper preprint (Full Theory)
│
├── 📂 Notebooks/
│   └── 📓 GCAT_Analysis_en.ipynb      # Main Code: Bayesian Validation Pipeline
│
├── 📂 Images/
│   ├── 🖼️ Aliasing.png                # Conceptual representation (Banner)
│   └── 📊 plots/                      # Plots generated by the analysis
│
├── 📜 LICENSE                         # MIT License (Open Source)
├── 📜 COPYRIGHT.md                    # Copyright Declaration
├── 📜 FUNDING.yml                     # Funding Information
├── 📄 README.md                       # Documentation in English (This file)
└── 📄 README_ES.md                    # Documentation in Spanish

</details>

---

<div align="center">
<br>
<b>Last updated:</b> Enero 2026 | <b>Status:</b> Research Complete | Made with ⚛️ & 🐍
<br><br>
</div>

