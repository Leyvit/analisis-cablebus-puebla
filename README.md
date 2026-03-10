# 🚡 Análisis del Cablebús de Puebla

> **¿Proyecto ecológico o narrativa política?** Un análisis de datos independiente sobre el impacto económico, social y ambiental del Cablebús de Puebla.

---

## 📌 Objetivo

Determinar si el Cablebús de Puebla vale la pena económica, social y ambientalmente, y si el gobierno está siendo honesto sobre su impacto ecológico.

## ❓ Pregunta Central

**¿El Cablebús realmente beneficia a la ciudadanía o es un proyecto político que daña el medio ambiente bajo una narrativa falsa de 'proyecto ecológico'?**

---

## 🔍 Hipótesis

El gobierno vende el Cablebús como ecológico, pero el impacto ambiental real es negativo. Una alternativa de transporte eléctrico sería más beneficiosa sin dañar el ecosistema urbano.

---

## 📊 Dimensiones del Análisis

| Dimensión | Preguntas clave |
|-----------|----------------|
| 💰 **Económica** | ¿El costo es justificable? ¿Quién se beneficia financieramente? |
| 👥 **Social** | ¿A quién beneficia realmente? ¿La ciudadanía lo quiere? |
| 🌳 **Ambiental** | ¿Cuántos árboles se pierden realmente? ¿La compensación es suficiente? |

---

## 📁 Estructura del Proyecto

```
analisis-cablebus-puebla/
│
├── 📂 data/
│   ├── raw/            # Datos originales sin modificar
│   └── processed/      # Datos limpios listos para analizar
│
├── 📂 notebooks/       # Análisis paso a paso en Jupyter
│   └── 01_exploracion_inicial.ipynb
│
├── 📂 src/             # Funciones y scripts reutilizables
│
├── 📂 visualizations/  # Gráficas exportadas
│
├── 📂 reports/         # Reportes y conclusiones finales
│
├── requirements.txt    # Librerías necesarias
└── README.md
```

---

## 🗂️ Datos del Proyecto

### Generales
- **Inversión total:** $6,752 millones de pesos
- **Extensión:** 13.6 km | 4 líneas | 9 estaciones | 90 torres
- **Constructor:** Doppelmayr (Austria)
- **Tarifa:** $10–12 pesos por viaje

### Impacto Social (datos oficiales)
- **Capacidad:** 90,000 usuarios diarios
- **Beneficio directo:** 132,306 habitantes
- **Beneficio indirecto:** 1.6 millones de personas en 45 colonias

### Costo por Habitante (cálculo propio)
| Escenario | Costo |
|-----------|-------|
| Por habitante beneficio directo | **$51,036 pesos** |
| Por habitante beneficio indirecto | **$4,220 pesos** |

### Impacto Ambiental
| Fuente | Árboles afectados |
|--------|-------------------|
| Gobierno (cifra inicial) | 980 |
| Gobierno (cifra revisada) | 746 |
| Gobierno (cifra final) | 350 |
| Compensación prometida | 10,000 nuevos árboles |

> ⚠️ **Nota:** La cifra oficial cambió 3 veces en pocas semanas. Los expertos de la BUAP advierten que los trasplantes de árboles adultos tienen menos del 30% de supervivencia.

---

## 🛠️ Herramientas

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)

```
Python · Pandas · Matplotlib · NumPy · Jupyter Notebook · Google Colab
```

---

## 📚 Fuentes

**Oficiales**
- [Gobierno de Puebla](https://puebla.gob.mx/index.php/noticias/item/21737)
- [Datos Abiertos Puebla](https://datos.puebla.gob.mx/grupo/secretaria-de-infraestructura-movilidad-y-transportes)
- [RUTA Puebla](https://ruta.puebla.gob.mx)

**Independientes**
- [INEGI](https://www.inegi.org.mx)
- [SEMARNAT](https://www.gob.mx/semarnat)
- [Animal Político](https://animalpolitico.com)
- [Lado B Puebla](https://ladobe.com.mx)

---

## ⚠️ Nota Metodológica

Los datos oficiales del gobierno serán contrastados con fuentes independientes. Las discrepancias encontradas son parte central del análisis.

---

## 👤 Autor

**@Leyvit** — Proyecto de Data Science aplicado a política pública local.

*Este proyecto busca generar conversación ciudadana informada sobre el Cablebús de Puebla.*
