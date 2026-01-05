# 🌌 GCAT V9: Gravedad Cuántica como Aliasing Topológico
### Fricción Informacional y Saturación del Límite Cinemático Local

> **Una solución unificada a las tensiones de Hubble ($H_0$) y $S_8$ basada en la Geometría No Conmutativa y la percolación de vacíos.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Open in Colab](https://img.shields.io/badge/Jupyter-Open_in_Colab-F37626?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/NachoPeinador/GCAT-Cosmology-Validation/blob/main/GCAT_V9_Analysis.ipynb)
[![arXiv](https://img.shields.io/badge/Status-Draft_V9-b31b1b?style=flat&logo=arxiv&logoColor=white)]()

---

## 🎯 Resumen Ejecutivo (TL;DR)

**GCAT (Quantum Gravity as Topological Aliasing)** propone que la energía oscura no es un fluido, sino un **coste termodinámico** de procesar información. El desajuste entre la codificación óptima del volumen (base ternaria, $\mathbb{Z}/3\mathbb{Z}$) y la frontera holográfica (base binaria, $\mathbb{Z}/2\mathbb{Z}$) genera un "aliasing" o fricción informacional.

Este repositorio contiene el **pipeline de validación bayesiana** que demuestra cómo este efecto se activa al saturar el límite cinemático local ($D_c \approx 70$ Mpc), resolviendo las tensiones cosmológicas actuales sin parámetros libres ajustables.

---

## 📐 Las Fórmulas Maestras: Del Bit al Cosmos

GCAT deriva la aceleración cósmica mediante una cadena lógica sin parámetros libres.

### Paso 1: El Aliasing Microscópico ($R_{\text{fund}}$)
Surge de la fricción entre la codificación de volumen (base 3) y frontera (base 2), modulada por la topología ($\xi=1/6$):

$$R_{\text{fund}} = \frac{1/6}{\log_2 3} \approx 0.10515$$

### Paso 2: La Constante Dinámica Universal ($\kappa$)
Para manifestarse en el espacio-tiempo 4D, este aliasing se proyecta dimensionalmente ($\beta=3/4$) generando la constante efectiva que rige la expansión:

$$\kappa \equiv 2\beta R_{\text{fund}} = 2 \cdot \frac{3}{4} \cdot R_{\text{fund}} = \frac{\ln 2}{4 \ln 3} \approx 0.1578$$

Esta constante $\kappa \approx 15.78\%$ es la que aparece en las ecuaciones de Friedmann modificadas, prediciendo la magnitud exacta de las tensiones observadas.

---

### 📊 Resultados Principales (V9)

| Métrica | Valor ΛCDM (Planck) | Valor Observado (SH0ES/KiDS) | **Predicción GCAT** | **Estado** |
|:---|:---:|:---:|:---:|:---:|
| **Hubble (H₀)** | 67.4 ± 0.5 | 73.04 ± 1.04 | **73.52 ± 1.04** | ✅ **Resuelta (0.46σ)** |
| **Estructura (S₈)** | 0.834 ± 0.01 | 0.766 ± 0.02 | **0.782 ± 0.01** | ✅ **Resuelta (0.74σ)** |
| **Evidencia Bayesiana** | Ref (0) | -- | **ΔBIC < -10** | 🏆 **Muy Fuerte** |

---

## ⚛️ Fundamentos Teóricos

La teoría se construye sobre tres pilares derivados desde primeros principios:

1.  **Geometría No Conmutativa (NCG):** El Modelo Estándar requiere una KO-dimensión interna de 6, imponiendo una estructura modular $\mathbb{Z}/6\mathbb{Z}$.
2.  **Economía de Radix:** La base 3 es termodinámicamente más eficiente ($E \approx 2.73$) que la base 2 ($E \approx 2.89$). El volumen del universo adopta la base 3, mientras que el horizonte está forzado a ser binario (holografía).
3.  **Factor de Aliasing ($R_{\text{fund}}$):** El coste de traducir información entre el volumen y la frontera genera una presión efectiva (aceleración).
    $$R_{\text{fund}} = \frac{1}{6 \log_2 3} \approx 0.105155$$

### El Mecanismo de Activación: Saturación a 70 Mpc
A diferencia de modelos anteriores, GCAT identifica que este efecto se activa globalmente cuando la red de vacíos cósmicos **percola y satura la estructura local**.
* **Límite Cinemático:** Datos de *CosmicFlows-4* (Mazurenko et al., 2024) imponen un límite de $\sim 70$ Mpc a las estructuras locales.
* **Hallazgo V9:** Nuestro análisis bayesiano converge a $D_c = 70.23$ Mpc, saturando este límite físico y explicando el "escalón" en los datos de supernovas (Pantheon+).

---

## 💡 Conclusión: Un Nuevo Paradigma Físico

El análisis bayesiano presentado en este repositorio sugiere que estamos ante un cambio ontológico en la cosmología:

| Concepto | Paradigma $\Lambda$CDM (Actual) | Paradigma GCAT (Propuesto) |
| :--- | :--- | :--- |
| **Origen Aceleración** | Fluido desconocido (Energía Oscura) con presión negativa. | **Fricción Informacional** por desajuste topológico (Aliasing). |
| **Naturaleza del Espacio** | Continuo, Geometría Riemanniana suave. | **Discreto**, Modular $\mathbb{Z}/6\mathbb{Z}$ (Geometría No Conmutativa). |
| **Tensiones ($H_0, S_8$)** | "Errores sistemáticos" o "Nueva Física" ad-hoc. | **Manifestaciones esperadas** de la transición de fase local. |
| **Datos Locales** | A menudo descartados o recortados ($z>0.02$). | **Fundamentales**: Validan la saturación del límite cinemático. |

> **En resumen:** El universo no se expande más rápido localmente porque haya una "energía extra", sino porque el espacio-tiempo discreto tiene un coste de computación más alto en la frontera holográfica que en el volumen.

---

## 🛠️ Instalación y Uso

Este código está diseñado para ser reproducible en **Google Colab** o en un entorno local Linux/Mac.

### Opción 1: Google Colab (Recomendada)
Haz clic en el botón "Open in Colab" arriba para ejecutar el análisis completo con un solo clic.

### Opción 2: Instalación Local

```bash
# 1. Clonar el repositorio
git clone [https://github.com/NachoPeinador/GCAT-Cosmology-Validation.git](https://github.com/NachoPeinador/GCAT-Cosmology-Validation.git)
cd GCAT-Cosmology-Validation

# 2. Crear entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate

# 3. Instalar dependencias exactas (CRÍTICO para reproducibilidad numérica)
pip install numpy==2.0.0 scipy==1.14.1 emcee corner matplotlib "pillow<12.0"

```

### Ejecutar el Pipeline

```bash
python run_analysis.py

```

*Esto ejecutará la optimización bayesiana (Differential Evolution + MCMC) y generará los gráficos en la carpeta `/output`.*

---

## 🔮 Predicciones Falsables

GCAT V9 hace predicciones cuantitativas que permitirán confirmar o descartar la teoría en la próxima década:

1. **Ondas Gravitacionales (Resonancia):**
   Predice una atenuación resonante del fondo estocástico de GW centrada en **f ≈ 1.38 × 10⁻¹⁶ Hz**, detectable por IPTA/SKA.

2. **Tomografía con Euclid:**
   Predice una caída abrupta en la amplitud de fluctuaciones (**σ₈**) exclusivamente a muy bajo redshift (**z < 0.05**).

3. **Transparencia a Alta Frecuencia:**
   A diferencia de otras teorías de gravedad modificada, GCAT predice **cero** atenuación para eventos tipo LIGO (**~100 Hz**), consistente con GW170817.

---

## 📂 Estructura del Repositorio

```
GCAT-Cosmology-Validation/
├── 📄 GCAT_V9_Paper.pdf           # Paper completo (Preprint)
├── 📄 run_analysis.py             # Script principal de ejecución
├── 📓 GCAT_V9_Analysis.ipynb      # Notebook interactivo (Paso a paso)
├── 📂 modules/
│   ├── physics.py                 # Ecuaciones de Friedmann modificadas
│   ├── likelihood.py              # Priors (CosmicFlows-4) y Log-Prob
│   └── visualizer.py              # Generador de gráficos del paper
├── 📂 output/                     # Resultados generados (Imágenes/JSON)
└── 📜 LICENSE                     # Licencia MIT

```

---

## 📜 Citación y Reconocimientos

Si utilizas este código o la teoría GCAT en tu investigación, por favor cita el repositorio y el preprint asociado:

```bibtex
@article{PeinadorSala2026,
  title = {Gravedad Cuántica como Aliasing Topológico: Unificación de la Dinámica de Percolación y la Geometría No Conmutativa},
  author = {Peinador Sala, José Ignacio},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub Repository},
  url = {[https://github.com/NachoPeinador/GCAT-Cosmology-Validation](https://github.com/NachoPeinador/GCAT-Cosmology-Validation)}
}

```

### Inspiración

> *"Considero muy posible que la física no pueda basarse en el concepto de campo, es decir, en estructuras continuas. En ese caso, no quedaría nada de todo mi castillo en el aire, incluida la teoría de la gravitación, y del resto de la física moderna."* — **Albert Einstein**, Carta a Michele Besso (1954)

Este proyecto materializa la intuición final de Einstein: propone que las tensiones cosmológicas actuales no son errores de medida, sino la evidencia de una **estructura discreta del vacío** que el modelo continuo (ΛCDM) ya no es capaz de describir.

---

## ⚖️ Licencia

Distribuido bajo la licencia **MIT**. Ver `LICENSE` para más información.

```

```
