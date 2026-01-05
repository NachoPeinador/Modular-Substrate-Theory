# 🌌 GCAT V9: Gravedad Cuántica como Aliasing Topológico
### Fricción Informacional y Saturación del Límite Cinemático Local

> **Una solución unificada a las tensiones de Hubble ($H_0$) y $S_8$ basada en la Geometría No Conmutativa y la percolación de vacíos.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Open in Colab](https://img.shields.io/badge/Jupyter-Open_in_Colab-F37626?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/NachoPeinador/GCAT-Cosmology-Validation/blob/main/GCAT_V9_Analysis.ipynb)
[![arXiv](https://img.shields.io/badge/Status-Draft_V9-b31b1b?style=flat&logo=arxiv&logoColor=white)]()

---

## 🎯 Resumen Ejecutivo (TL;DR)

**GCAT (Gravedad Cuántica como Aliasing Topológico)** propone un cambio de paradigma: la energía oscura no es un fluido desconocido, sino el **coste termodinámico** de procesar información en un espacio-tiempo discreto.

La expansión acelerada surge de una **fricción informacional**: el desajuste entre la codificación óptima del volumen (base ternaria, $\mathbb{Z}/3\mathbb{Z}$) y la codificación forzada de la frontera holográfica (base binaria, $\mathbb{Z}/2\mathbb{Z}$).

Este repositorio contiene el **pipeline de validación bayesiana** que demuestra que:
1.  Este efecto se activa al saturar el límite cinemático local ($D_c \approx 70$ Mpc).
2.  Resuelve las tensiones de Hubble y $S_8$ simultáneamente.
3.  Lo hace **desde primeros principios**, sin parámetros libres ad-hoc.
---

## 📐 Las Fórmulas Maestras: Del Bit al Cosmos

GCAT deriva la aceleración cósmica mediante una cadena lógica estricta, sin ajustar parámetros libres.

### Paso 1: El Aliasing Microscópico ($R_{\text{fund}}$)
Representa la "fricción" informacional pura. Surge de la incompatibilidad entre bases numéricas, fijada por la topología del vacío:
* **$\xi = 1/6$**: Acoplamiento conforme (dictado por la KO-dimensión 6).
* **$\mathcal{S} = \log_2 3$**: Coste de traducir trits (volumen) a bits (frontera).

$$R_{\text{fund}} = \frac{\xi}{\log_2 3} = \frac{1/6}{\log_2 3} \approx 0.10515$$

### Paso 2: La Constante Dinámica Universal ($\kappa$)
Para que este efecto microscópico actúe sobre la expansión del universo (4D), debe proyectarse dimensionalmente. Usamos el factor de proyección **$\beta = 3/4$** (volumen espacial $d=3$ sobre variedad espacio-temporal $d=4$):

$$\kappa \equiv 2\beta R_{\text{fund}} = 2 \cdot \frac{3}{4} \cdot R_{\text{fund}} = \frac{\ln 2}{4 \ln 3} \approx 0.1578$$

> **Resultado:** Esta constante $\kappa \approx 15.78\%$ sustituye a la Energía Oscura arbitraria. Es un valor geométrico fijo que, al introducirse en las ecuaciones de Friedmann, reproduce exactamente la aceleración observada.

---

### 📊 Resultados Principales (V9)

#### 1. Resolución de Tensiones
El modelo elimina las discrepancias estadísticas entre el universo temprano y el tardío:

| Métrica | Valor ΛCDM (Planck) | Valor Observado | **Predicción GCAT** | **Estado** |
|:---|:---:|:---:|:---:|:---:|
| **Hubble (H₀)** | 67.4 ± 0.5 | 73.04 ± 1.04 | **73.52 ± 1.04** | ✅ **Resuelta (0.46σ)** |
| **Estructura (S₈)** | 0.834 ± 0.01 | 0.766 ± 0.02 | **0.782 ± 0.01** | ✅ **Resuelta (0.74σ)** |
| **Ajuste Global** | χ² = 1601.3 | -- | **Δχ² = -18.6** | 📉 **Mejor Ajuste** |
| **Evidencia** | Ref (0) | -- | **ΔBIC < -10** | 🏆 **Muy Fuerte** |

#### 2. Parámetros Físicos Inferidos
El análisis MCMC no solo ajusta curvas, sino que revela la estructura física de la transición:

| Parámetro | Valor Inferido (Mediana) | Interpretación Física |
|:---|:---:|:---|
| **Transición ($z_c$)** | **0.0170 ± 0.001** | Inicio de la percolación de vacíos (muy reciente). |
| **Escala ($D_c$)** | **70.23 Mpc** | Saturación del límite cinemático (*CosmicFlows-4*). |
| **Masa ($m_{info}$)** | **~10⁻³³ eV** | Masa efectiva del campo de información. |

---

## ⚛️ Fundamentos Teóricos: De lo Cuántico a lo Cósmico

GCAT no añade "fluidos oscuros" al universo. En su lugar, identifica una propiedad emergente del espacio-tiempo discreto que actúa como una fuerza entrópica.

### 1. La Estructura del Vacío (Geometría No Conmutativa)
Para acomodar el Modelo Estándar de partículas, la geometría interna del espacio-tiempo requiere una **KO-dimensión 6**. Esto impone una estructura modular cíclica ($\mathbb{Z}/6\mathbb{Z}$) en el tejido microscópico del vacío, definiendo su "pixelación" fundamental.

### 2. El Conflicto Termodinámico (Bulk vs Frontera)
Existe una tensión fundamental en cómo el universo almacena información:
* **El Volumen (Bulk):** Maximiza su eficiencia termodinámica operando en **Base 3** (Radix óptimo $e \approx 2.718 \to 3$).
* **La Frontera (Horizonte):** Está obligada por el Principio Holográfico a codificar información en **Base 2** (Bits, Área).

### 3. Fricción Informacional (Aliasing)
La traducción constante entre el volumen ternario y la frontera binaria no es perfecta. Genera un "ruido de cuantización" o aliasing topológico.
> **La Energía Oscura es la manifestación macroscópica de este coste de traducción.**

$$R_{\text{fund}} = \frac{\text{Acoplamiento Topológico}}{\text{Coste de Conversión}} = \frac{1/6}{\log_2 3} \approx 0.10515$$

---

### 🌊 El Mecanismo de Activación: Percolación y Saturación
¿Por qué vemos esto ahora y no en el universo temprano? GCAT introduce la dinámica de **Percolación de Vacíos**.

1.  **Fase Temprana:** El universo es denso. El efecto está suprimido.
2.  **Transición de Fase ($z_c \approx 0.017$):** Los vacíos cósmicos crecen y se tocan (percolan). La red de vacíos se vuelve global.
3.  **Saturación Cinemática (70 Mpc):**
    El análisis bayesiano confirma que la transición ocurre exactamente cuando la estructura local satura los límites observados por **CosmicFlows-4** (Mazurenko et al., 2024).

> **Resultado:** La aceleración cósmica no es suave, sino que se "enciende" al alcanzar la escala de saturación de $D_c \approx 70$ Mpc, explicando la tensión de Hubble como un efecto de muestreo local.

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
