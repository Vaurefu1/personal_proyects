# 📊 Análisis de Inflación en México por Sexenio (2007–2024)
# 📊 Mexico Inflation Analysis by Presidential Term (2007–2024)

---

## 🇲🇽 Español

### Descripción
Análisis de la inflación anual en México durante tres sexenios presidenciales (2007–2024), utilizando datos reales del INEGI (Índice Nacional de Precios al Consumidor - INPC). El proyecto aplica SQL con SQLite, Python y visualizaciones para comparar el comportamiento de los precios entre administraciones y evaluar el cumplimiento de la meta del Banco de México.

### Preguntas que responde este proyecto
- ¿Cómo evolucionó la inflación en México durante los últimos tres sexenios?
- ¿Qué administración tuvo la inflación promedio más baja?
- ¿Cuántos años se cumplió la meta de inflación del Banco de México (3%)?
- ¿Qué factores externos influyeron más en los precios?

### Herramientas y tecnologías
| Herramienta | Uso |
|-------------|-----|
| Python 3 | Análisis y visualización |
| Pandas | Manipulación de datos |
| SQLite3 | Base de datos y consultas SQL |
| Matplotlib / Seaborn | Gráficas |
| SciPy | Pruebas estadísticas |
| Jupyter Notebook | Entorno de desarrollo |

### Fuentes de datos
- **INEGI** — Índice Nacional de Precios al Consumidor (INPC)
- **Banco de México (Banxico)** — Meta de inflación oficial
- **CEFP** — Centro de Estudios de las Finanzas Públicas

### Estructura del proyecto
```
analisis-inflacion-mexico/
│
├── inflacion_mexico.ipynb          # Notebook principal
├── inflacion_mexico_2007_2024.csv  # Dataset anual (18 registros)
├── inflacion_por_sexenio.csv       # Resumen por sexenio
└── README.md
```

### Hallazgos principales
- La inflación promedio fue similar entre los tres sexenios: Calderón 4.27%, Peña Nieto 4.19%, AMLO 5.00%
- El pico histórico fue **7.82% en 2022**, impulsado por la guerra en Ucrania y presiones postpandemia
- El mínimo histórico fue **2.13% en 2015**, año de baja inflación global
- **16 de 18 años** (89%) la inflación superó la meta oficial del Banco de México (3%)
- Las pruebas estadísticas sugieren que los choques externos tienen mayor impacto en la inflación que el partido gobernante

---

## 🇺🇸 English

### Description
Analysis of Mexico's annual inflation across three presidential terms (2007–2024), using real data from INEGI (National Consumer Price Index - INPC). The project applies SQL with SQLite, Python, and visualizations to compare price behavior between administrations and evaluate compliance with the Bank of Mexico's inflation target.

### Questions this project answers
- How did inflation evolve in Mexico over the last three presidential terms?
- Which administration had the lowest average inflation?
- How many years met the Bank of Mexico's inflation target (3%)?
- What external factors had the most impact on prices?

### Tools and technologies
| Tool | Use |
|------|-----|
| Python 3 | Analysis and visualization |
| Pandas | Data manipulation |
| SQLite3 | Database and SQL queries |
| Matplotlib / Seaborn | Charts |
| SciPy | Statistical tests |
| Jupyter Notebook | Development environment |

### Data sources
- **INEGI** — National Consumer Price Index (INPC)
- **Banco de México (Banxico)** — Official inflation target
- **CEFP** — Center for Public Finance Studies

### Project structure
```
analisis-inflacion-mexico/
│
├── inflacion_mexico.ipynb          # Main notebook
├── inflacion_mexico_2007_2024.csv  # Annual dataset (18 records)
├── inflacion_por_sexenio.csv       # Summary by presidential term
└── README.md
```

### Key findings
- Average inflation was similar across the three terms: Calderón 4.27%, Peña Nieto 4.19%, AMLO 5.00%
- The historical peak was **7.82% in 2022**, driven by the war in Ukraine and post-pandemic pressures
- The historical low was **2.13% in 2015**, a year of low global inflation
- **16 of 18 years** (89%) inflation exceeded the Bank of Mexico's official target (3%)
- Statistical tests suggest external shocks have a greater impact on inflation than the ruling party

---

*Proyecto de portafolio / Portfolio project — Luis Fernando Rubio Avalos*
