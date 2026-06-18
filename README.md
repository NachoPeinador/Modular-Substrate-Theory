# 🌌 Modular Substrate Theory (MST)
## Resolving the Hubble and $S_8$ Tensions via Informational Friction

### *A cosmological framework based on the discrete ℤ₆⁽¹⁾ vacuum symmetry that derives the informational impedance of the universe from first principles.*

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18609092.svg)](https://doi.org/10.5281/zenodo.18609092)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--1822--3452-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0008-1822-3452) 
[![Papers](https://img.shields.io/badge/Paper-Read_PDF-B31B1B?style=flat&logo=latex&logoColor=white)](https://github.com/NachoPeinador/Modular-Substrate-Theory/blob/main/Papers/MST_Cosmological_Tensions_Resolution.pdf)

---

## 🚨 The Cosmological Crisis

Contemporary cosmology faces decisive observational anomalies that challenge the established ΛCDM theoretical framework:

| Domain | Anomaly | Significance | Standard Model Assumption |
|---------|----------|---------------|-----------------|
| **Expansion Rate** | Hubble Tension ($H_0$) | $\sim 5.0\sigma$ | Flat ΛCDM (Planck vs SH0ES) |
| **Cosmic Structure** | $S_8$ Tension | $\sim 2.5\sigma$ | Scale-independent structure growth |

These tensions are increasingly recognized not as mere systematic errors, but as **structural cracks** in our fundamental understanding of spacetime at late cosmic epochs.

## 🔬 The MST Proposal: Informational Friction

The **Modular Substrate Theory (MST)** proposes that the quantum vacuum possesses a discrete $\mathbb{Z}_6^{(1)}$ gauge symmetry. This topological structure acts as a computational substrate with an intrinsic **informational impedance**. 

This impedance governs a dissipative "informational friction" that modifies the Friedmann expansion equation. Crucially, this friction is geometrically activated by the percolation of cosmic voids in the late universe ($z_c \approx 0.017$), creating a perspective effect where local distance ladders probe an activated universe, while the CMB probes an unactivated one.

### 📐 Derived Fundamental Constants

MST derives its key cosmological parameters **analytically from first principles**, without empirical data fitting:

| Constant | Analytical Expression | Numerical Value | Physical Origin |
|-----------|-------------------|----------------|---------------|
| **Vacuum Impedance** $R_{\text{fund}}$ | $\ln 2/(6\ln 3)$ | $0.105155$ | Gauge topology and holographic bound |
| **Projection Factor** $\beta$ | $3/4$ | $0.75$ | AdS<sub>5</sub>/CFT<sub>4</sub> dimensional ratio |

## 📊 Results: Simultaneous Tension Resolution

By incorporating the informational friction into the evolution of the universe, MST simultaneously resolves both major anomalies:

| Parameter | $\Lambda$CDM (Planck) | Local Observatories | **MST Prediction** | **Residual Tension** |
|-----------|----------------------|--------------------------|-------------------|---------------------|
| $H_0$ (km/s/Mpc) | $67.4 \pm 0.5$ | $73.04 \pm 1.04$ (SH0ES) | **$73.56 \pm 0.58$** | **$0.44\sigma$** (Resolved) |
| $S_8$ | $0.832 \pm 0.013$ | $0.766 \pm 0.020$ (KiDS-1000) | **$0.782 \pm 0.012$** | **$0.68\sigma$** (Resolved) |
| Scale $D_c$ (Mpc) | N/A | $\lesssim 70$ (CosmicFlows-4) | **$70.2 \pm 5.0$** | **Saturates limit** |

**Crucial Insight:** MST predicts a dynamic geometric phase transition at $D_c \approx 70.2$ Mpc that **exactly saturates** the upper limit imposed by peculiar velocity kinematic analyses (CosmicFlows-4), strictly distinguishing itself from refuted static giant void models (like the 300 Mpc KBC void).

## 🔮 Falsifiable Quantitative Predictions (2026-2035)

MST is a highly predictive theory. Upcoming next-generation surveys will test the following rigid signatures:

| Prediction | Experiment | Falsifiable Signature |
| --- | --- | --- |
| **Matter Power Spectrum** | DESI, Euclid | A $\sim 6.0\%$ suppression at $k \approx 0.014\ \text{Mpc}^{-1}$. |
| **Structure Growth** | Euclid | A sharp tomographic drop in $\sigma_8(z)$ at $z < 0.05$. |
| **Gravitational Waves** | IPTA, SKA | A resonant attenuation of the GW background at $f \approx 1.39 \times 10^{-16}\ \text{Hz}$. |

## 📈 Validation Metrics: Bayesian Model Comparison

| Model | Free Parameters ($k$) | $\Delta\chi^2$ | $\Delta$BIC | Evidence (Jeffreys Scale) |
| --- | --- | --- | --- | --- |
| $\Lambda$CDM | 6 | 0 | 0 | Null Hypothesis |
| $w_0w_a$CDM | 8 | -2.1 | +2.1 | Negative |
| Early Dark Energy (EDE) | 7 | -6.4 | -4.3 | Positive |
| Interacting DE (IDE) | 8 | -6.0 | -1.8 | Weak |
| **MST (this work)** | **8** | **-16.3** | **-12.1** | **Very Strong** |

*Note: MST achieves decisive statistical superiority (ΔBIC = -12.1$) without adjusting fundamental constants to fit the data. The percolation parameters emerge naturally constrained by FSS and peculiar velocity catalogs.*

## 🛠️ Scientific Reproducibility & Repository Architecture

All computational analysis, Monte Carlo error propagation ($n=20,000$), and tension resolutions are transparent and 100% reproducible. 

```text
Modular-Substrate-Theory/
├── MST_Cosmological_Tensions_Resolution.pdf       # Main Manuscript
├── MST_Cosmological_Tensions_Resolution.tex       # LaTeX Source Code
├── MST_Cosmological_Tensions_Analysis.ipynb       # Python Executable Notebook
├── MST_Cosmological_Tensions_Analysis_Colab.pdf   # Static Notebook Export
├── MST_Percolation_Schematic.png                  # Conceptual Transition Diagram
└── Visualizations_of_MST_Dynamics.png             # Data Visualizations

```

To verify the calculations locally, clic and run the Jupyter Notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NachoPeinador/Modular-Substrate-Theory/blob/main/Notebooks/MST_Cosmological_Tensions_Analysis.ipynb)

## 🤝 Citation and License

### Cite this Work

```bibtex
@article{PeinadorSala2026MST,
  title = {Resolving the Hubble and S_8 Tensions via Informational Friction in the Modular Substrate Theory},
  author = {Peinador Sala, Jos{\'e} Ignacio},
  year = {2026},
  journal = {Zenodo},
  url = {[https://github.com/NachoPeinador/Modular-Substrate-Theory](https://github.com/NachoPeinador/Modular-Substrate-Theory)},
  doi = {10.5281/zenodo.18609092}
}

```

### Licenses

* **Code:** MIT License - Free use with attribution.
* **Theory and Documentation:** CC BY 4.0 - Share with attribution.

## 📞 Contact

**Lead Author:** José Ignacio Peinador Sala

Independent Researcher

[ORCID: 0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

✉️ joseignacio.peinador@gmail.com

---
