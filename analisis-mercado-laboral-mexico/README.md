# Labor Market Analysis in Mexico 2020-2024

## Description
Exploratory analysis of the Mexican labor market using official INEGI 
(ENOE) data. Studies the evolution of unemployment, labor informality 
and economic participation across the 32 states between 2020 and 2024.

## Objective
Identify patterns and regional inequalities in the Mexican labor market 
to support decision-making in public policy and business strategy.

## Data Source
INEGI - National Survey of Occupation and Employment (ENOE)
https://www.inegi.org.mx/programas/enoe/15ymas/

## Tools
- Python 3.13
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## Files
- `analisis_mercado_laboral.ipynb` — Notebook with complete analysis
- `enoe_desempleo_mexico_2020_2024.csv` — Wide dataset (32 x 24)
- `enoe_desempleo_largo_2020_2024.csv` — Long dataset (640 records)

## Analysis Steps
1. Data loading and initial exploration
2. Quality check: no missing values or duplicates found
3. National unemployment trend 2020-2024
4. Top 10 states with highest average unemployment
5. Labor informality by region
6. Heatmap by state and year
7. Relationship between informality and unemployment by state
8. Conclusions and recommendations

## Key Findings
- COVID-19 caused a unemployment peak of 4.9% in 2020-Q2
- Mexico City (4.42%) and Tabasco (4.18%) lead average unemployment
- The South-Southeast region has 24 percentage points more informality than the North
- By 2024 all states recovered to pre-pandemic levels

## Conclusions
Southern states like Oaxaca and Guerrero show low unemployment but 
very high informality, indicating precarious work conditions without 
access to social security. Formalization policies should be focused 
on the South-Southeast region.

---

# Análisis del Mercado Laboral en México 2020-2024

## Descripción
Análisis exploratorio del mercado laboral mexicano usando datos 
oficiales del INEGI (ENOE). Estudia la evolución del desempleo, 
informalidad laboral y participación económica en las 32 entidades 
federativas entre 2020 y 2024.

## Objetivo
Identificar patrones y desigualdades regionales en el mercado 
laboral mexicano que apoyen la toma de decisiones en política 
pública y estrategia empresarial.

## Fuente de datos
INEGI - Encuesta Nacional de Ocupación y Empleo (ENOE)
https://www.inegi.org.mx/programas/enoe/15ymas/

## Herramientas
- Python 3.13
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## Archivos
- `analisis_mercado_laboral.ipynb` — Notebook con análisis completo
- `enoe_desempleo_mexico_2020_2024.csv` — Dataset wide (32 x 24)
- `enoe_desempleo_largo_2020_2024.csv` — Dataset long (640 registros)

## Pasos del análisis
1. Carga y exploración inicial de datos
2. Verificación de calidad: sin valores ausentes ni duplicados
3. Evolución nacional del desempleo 2020-2024
4. Top 10 estados con mayor desempleo promedio
5. Informalidad laboral por región
6. Mapa de calor por estado y año
7. Relación entre informalidad y desempleo por estado
8. Conclusiones y recomendaciones

## Hallazgos principales
- El COVID-19 generó un pico de desempleo del 4.9% en 2020-T2
- Ciudad de México (4.42%) y Tabasco (4.18%) lideran el desempleo promedio
- El Sur-Sureste tiene 24 puntos más de informalidad que el Norte
- Para 2024 todos los estados recuperaron niveles prepandemia

## Conclusiones
Estados del sur como Oaxaca y Guerrero presentan baja desocupación 
pero altísima informalidad, lo que indica trabajo en condiciones 
precarias sin acceso a seguridad social. Se recomienda focalizar 
políticas de formalización laboral en la región Sur-Sureste.
