# 🚡 Análisis del Cablebús de Puebla

> Análisis de datos independiente sobre el impacto económico, social y ambiental del Cablebús de Puebla, contrastando fuentes oficiales con fuentes independientes.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)

---

## 📌 Objetivo

Evaluar el impacto económico, social y ambiental del Cablebús de Puebla a partir de datos públicos disponibles, identificando consistencias y discrepancias entre las cifras oficiales y fuentes independientes.

## ❓ Preguntas de Investigación

1. ¿El costo de inversión es proporcional al beneficio social esperado?
2. ¿Las cifras oficiales sobre impacto ambiental son consistentes a lo largo del tiempo?
3. ¿Existe una alternativa de transporte más eficiente para las zonas beneficiadas?

---

## 🔍 Hipótesis de trabajo

> La narrativa oficial del proyecto presenta inconsistencias cuantificables en su dimensión ambiental. Se explorará si una alternativa de transporte eléctrico podría ofrecer beneficios comparables con menor impacto en el ecosistema urbano.

*Nota: Esta hipótesis será evaluada con los datos — las conclusiones seguirán a la evidencia, no al revés.*

---

## 📊 Dimensiones del Análisis

| Dimensión | Preguntas clave | Estado |
|-----------|----------------|--------|
| 💰 **Económica** | Costo por habitante, costo por km, retorno de inversión | 🔄 En proceso |
| 👥 **Social** | Perfil de colonias beneficiadas, opinión ciudadana | ⏳ Pendiente |
| 🌳 **Ambiental** | Evolución de cifras oficiales de árboles, supervivencia de trasplantes | ✅ Notebook 01 |

---

## 📁 Estructura del Proyecto

```
analisis-cablebus-puebla/
│
├── 📂 data/
│   ├── raw/            # Datos originales sin modificar
│   └── processed/      # Datos limpios listos para analizar
│
├── 📂 notebooks/
│   ├── 01_exploracion_inicial.ipynb    ✅ Completado
│   ├── 02_analisis_economico.ipynb     🔄 En desarrollo
│   └── 03_analisis_social.ipynb        ⏳ Pendiente
│
├── 📂 src/             # Funciones y scripts reutilizables
├── 📂 visualizations/  # Gráficas exportadas
├── 📂 reports/         # Reportes y conclusiones finales
├── requirements.txt
└── README.md
```

---

## 🗂️ Datos del Proyecto

### Generales
| Variable | Valor | Fuente |
|----------|-------|--------|
| Inversión total | $6,752 millones de pesos | Gobierno de Puebla / Ley de Egresos 2026 |
| Extensión | 13.6 km | Comunicado oficial |
| Infraestructura | 4 líneas, 9 estaciones, 90 torres | Comunicado oficial |
| Constructor | Doppelmayr (Austria) | Licitación SPFA-OP-LPE-2025-165 |
| Tarifa | $10–12 pesos | Declaración gobernador Armenta |

### Impacto Social (datos oficiales)
| Variable | Valor | Nota |
|----------|-------|------|
| Capacidad | 90,000 usuarios/día | Dato oficial verificado |
| Beneficio directo | 132,306 habitantes | ⚠️ Sin metodología pública |
| Beneficio indirecto | 1.6 millones (45 colonias) | ⚠️ Sin metodología pública |

### Costo por Habitante (cálculo propio)
| Escenario | Costo | Equivalencia |
|-----------|-------|--------------|
| Beneficio directo | $51,033 pesos/persona | ~15.7 salarios mínimos mensuales |
| Beneficio indirecto | $4,220 pesos/persona | ~1.3 salarios mínimos mensuales |

### Evolución de Cifras Ambientales Oficiales
| Fecha | Árboles afectados | Fuente |
|-------|-------------------|--------|
| Enero 2026 | 980 | Secretaría de Infraestructura (declaración inicial) |
| Febrero 2026 | 746 | Declaración García Parra — Angulo7 |
| Marzo 2026 (inicio) | 350 | Ajuste técnico — El Sol de Puebla |
| Marzo 2026 (9 mar) | 116 | Nueva declaración García Parra — Angulo7 |
| Compensación prometida | 10,000 nuevos árboles | Gobierno del Estado |

> 📉 La cifra oficial se redujo un **88% en 3 meses**. Se requiere el dictamen técnico de Manifestación de Impacto Ambiental (MIA) para validar estos datos.

---

## 🛠️ Herramientas

```
Python · Pandas · Matplotlib · NumPy · Jupyter Notebook · Google Colab
```

---

## ⚠️ Metodología y Limitaciones

- Los datos oficiales provienen de comunicados del Gobierno de Puebla y declaraciones en medios verificados.
- Las cifras de árboles afectados se obtuvieron de declaraciones públicas rastreadas en medios — **no de un documento técnico oficial publicado**.
- Los datos de habitantes beneficiados (132,306 y 1.6M) son cifras oficiales sin metodología pública disponible.
- Se buscará el dictamen técnico de impacto ambiental (MIA) vía solicitud de transparencia (INFOMEX Puebla).
- Todas las discrepancias encontradas serán documentadas con sus fuentes.

---

## 📚 Fuentes

**Oficiales**
- [Gobierno de Puebla](https://puebla.gob.mx/index.php/noticias/item/21737)
- [Datos Abiertos Puebla](https://datosabiertos.puebla.gob.mx)
- [RUTA Puebla](https://ruta.puebla.gob.mx)

**Independientes**
- [Angulo7 Puebla](https://angulo7.com.mx)
- [Lado B Puebla](https://ladobe.com.mx)
- [Animal Político](https://animalpolitico.com)
- [INEGI](https://www.inegi.org.mx)
- [SEMARNAT](https://www.gob.mx/semarnat)

---

## 👤 Autor

**@Leyvit** — Proyecto de Data Science aplicado al análisis de política pública local.

*Proyecto desarrollado como ejercicio de aprendizaje de Data Science con impacto ciudadano.*
