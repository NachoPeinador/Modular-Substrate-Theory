# 🌌 GCAT: Gravedad Cuántica como Aliasing Topológico
### Fricción Informacional y Saturación del Límite Cinemático Local. > **English Version Available** | [![Read in English](https://img.shields.io/badge/Lang-Read%20in%20English-blue?style=for-the-badge&logoColor=white&color=012169)](https://github.com/NachoPeinador/GCAT-Cosmology-Validation/blob/main/README.md)

> **Una solución unificada a las tensiones de Hubble ($H_0$) y $S_8$ basada en la Geometría No Conmutativa y la percolación de vacíos.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Open in Colab](https://img.shields.io/badge/Jupyter-Open_in_Colab-F37626?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/NachoPeinador/GCAT-Cosmology-Validation/blob/main/Notebooks/GCAT_PLATINUM.ipynb)
[![arXiv](https://img.shields.io/badge/Status-Draft_V9-b31b1b?style=flat&logo=arxiv&logoColor=white)]()

<p align="center">
  <img src="/Images/Aliasing.png" alt="Representación conceptual del Aliasing Topológico y la Burbuja Local" width="100%">
</p>
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

### 3. Fricción Informacional y Dinámica Efectiva

GCAT sustituye la Energía Oscura por un mecanismo de dos pasos: una causa topológica y un efecto dinámico.

#### A. La Causa: Aliasing Topológico ($R_{\text{fund}}$)
A nivel microscópico, la traducción entre el volumen (base 3) y la frontera (base 2) genera un "ruido" o coste informacional fundamental.
> **Este es el origen termodinámico de la energía oscura.**

$$R_{\text{fund}} = \frac{\text{Acoplamiento Topológico}}{\text{Coste de Conversión}} = \frac{1/6}{\log_2 3} \approx 0.10515$$

#### B. El Efecto: Constante Dinámica Universal ($\kappa$)
Para que este coste microscópico acelere el universo, debe proyectarse en la geometría 4D del espacio-tiempo. Aplicando el factor de proyección dimensional ($\beta = 3/4$) y el acoplamiento métrico ($2$), obtenemos la constante efectiva que entra en las ecuaciones:

$$\kappa \equiv \underbrace{2}_{\text{Métrica}} \cdot \underbrace{\beta}_{\text{Proyección } 3D \to 4D} \cdot R_{\text{fund}} = \frac{\ln 2}{4 \ln 3} \approx 0.1578$$

> **Resultado:** No ajustamos la Energía Oscura. Calculamos $\kappa \approx 15.78\%$ desde primeros principios y este valor fijo reproduce la aceleración observada.

---

### 🌊 El Mecanismo de Activación: Percolación y Saturación
¿Por qué vemos esto ahora y no en el universo temprano? GCAT introduce la dinámica de **Percolación de Vacíos**.

1.  **Fase Temprana:** El universo es denso. El efecto está suprimido.
2.  **Transición de Fase ($z_c \approx 0.017$):** Los vacíos cósmicos crecen y se tocan (percolan). La red de vacíos se vuelve global.
3.  **Saturación Cinemática (70 Mpc):**
    El análisis bayesiano confirma que la transición ocurre exactamente cuando la estructura local satura los límites observados por **CosmicFlows-4** (Mazurenko et al., 2024).

> **Resultado:** La aceleración cósmica no es suave, sino que se "enciende" al alcanzar la escala de saturación de $D_c \approx 70$ Mpc, explicando la tensión de Hubble como un efecto de muestreo local.

---

## 💡 Conclusión: Un Nuevo Paradigma Cosmológico

La evidencia estadística presentada ($\Delta\chi^2 \approx -18.6$ vs ΛCDM) sugiere que las tensiones actuales no requieren "nueva física" exótica, sino una **nueva ontología** del espacio-tiempo.

| Concepto | Paradigma Estándar (ΛCDM) | Paradigma GCAT (Informacional) |
| :--- | :--- | :--- |
| **Origen Aceleración** | Fluido desconocido (Energía Oscura) con presión negativa constante. | **Coste Termodinámico** por procesar información en la frontera (Fricción). |
| **Naturaleza del Espacio** | Geometría Riemanniana continua y suave a cualquier escala. | **Estructura Discreta y Modular** ($\mathbb{Z}/6\mathbb{Z}$) derivada de la NCG. |
| **Tensión de Hubble ($H_0$)** | Anomalía estadística o error sistemático local a descartar. | **Aliasing Topológico**: Un efecto de muestreo inevitable al saturar el límite cinemático ($D_c$). |
| **Estatus de Datos Locales** | "Ruidosos" o contaminados por flujos peculiares (se recortan $z < 0.02$). | **Señal Fundamental**: La saturación a 70 Mpc (*CosmicFlows-4*) revela la transición de fase. |

> **En resumen:** El universo no se expande más rápido localmente debido a una "energía extra", sino porque el espacio-tiempo discreto impone un **peaje informacional** al traducir el volumen (base 3) a la superficie (base 2). La tensión de Hubble es, simplemente, la factura de ese peaje.

---

## 🚀 Reproducción de Resultados

Para garantizar la transparencia y la **reproducibilidad numérica exacta** de los resultados bayesianos (MCMC), el código completo se ha unificado en un único Cuaderno de Jupyter (Notebook).

### Opción 1: Google Colab (Recomendada)
Es la forma más rápida y fiable. El cuaderno gestiona automáticamente la instalación de dependencias en el entorno efímero.

1.  Haz clic en el botón **"Open in Colab"**.[![Open in Colab](https://img.shields.io/badge/Jupyter-Open_in_Colab-F37626?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/NachoPeinador/GCAT-Cosmology-Validation/blob/main/Notebooks/GCAT_PLATINUM.ipynb)
2.  En el menú de Colab, selecciona **"Entorno de ejecución"** > **"Ejecutar todas"**.
3.  El sistema realizará el análisis completo (aprox. 1-2 minutos) y generará los gráficos al final.

### Opción 2: Ejecución Local (Jupyter)
<details>
<summary><strong>👇 Clic para si prefieres ejecutar el análisis en tu propia máquina:</strong></summary>

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/NachoPeinador/GCAT-Cosmology-Validation.git](https://github.com/NachoPeinador/GCAT-Cosmology-Validation.git)
    cd GCAT-Cosmology-Validation/Notebooks
    ```

2.  **Instalar dependencias:**
    Se recomienda usar un entorno virtual. Las librerías críticas son:
    ```bash
    pip install numpy==2.0.0 scipy==1.14.1 emcee corner matplotlib "pillow<12.0" jupyterlab
    ```

3.  **Ejecutar:**
    Lanza Jupyter y abre el archivo `GCAT_V9_Analysis.ipynb`:
    ```bash
    jupyter lab GCAT_V9_Analysis.ipynb
    ```
</details>

---

## 🔮 Predicciones Falsables

GCAT V9 realiza predicciones cuantitativas específicas que la diferencian de ΛCDM y permiten su verificación experimental a corto plazo:

1. **Ondas Gravitacionales (Resonancia de Cavidad):**
   Debido a la estructura modular de la red de vacíos, se predice una atenuación característica en el espectro de fondo estocástico de GW (SGWB) centrada en la frecuencia fundamental de la cavidad local:
   **f ≈ 1.38 × 10⁻¹⁶ Hz** (Correspondiente a $\lambda \approx 70$ Mpc).

2. **Crecimiento de Estructuras (Euclid/DESI):**
   Predice una caída abrupta en la tasa de crecimiento de estructuras (**fσ₈**) y en la amplitud de fluctuaciones, desviándose de la Relatividad General exclusivamente dentro de la burbuja local:
   **z < 0.05**.

3. **Transparencia a Alta Frecuencia (LIGO/Virgo):**
   A diferencia de las teorías de gravedad masiva que dispersan las ondas, GCAT preserva la invariancia Lorentz local a pequeñas escalas. Predice **cero atenuación** y velocidad $c_g = c$ para eventos astrofísicos compactos:
   **f ~ 100 Hz** (Consistente con GW170817).

---

## 📂 Estructura del Repositorio
<details>
<summary><strong>👇 Clic para ver la estructura del repositorio</strong></summary>

```
GCAT-Cosmology-Validation/
├── 📂 Papers/
│   └── 📄 GCAT_V9_Paper.pdf           # Preprint del artículo científico (Teoría completa)
│
├── 📂 Notebooks/
│   └── 📓 GCAT_V9_Analysis.ipynb      # Código principal: Pipeline de validación bayesiana
│
├── 📂 Images/
│   ├── 🖼️ Aliasing.png                # Representación conceptual (Banner)
│   └── 📊 plots/                      # Gráficos generados por el análisis
│
├── 📜 LICENSE                         # Licencia MIT (Código abierto)
├── 📜 COPYRIGHT.md                    # Declaración de derechos de autor
├── 📜 FUNDING.yml                     # Información de financiación
├── 📄 README.md                       # Documentación en Inglés (English)
└── 📄 README_ES.md                    # Documentación en Español (Este archivo)

```
</details>

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
