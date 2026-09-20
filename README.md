# personal_proyects
This repository is a practice exercise with data that "could" be real, but is for practice purposes only.



# Análisis del Mercado Laboral en México 2020-2024

## Descripción
Análisis exploratorio del mercado laboral mexicano usando datos oficiales 
del INEGI (ENOE). El proyecto estudia la evolución del desempleo, 
informalidad laboral y participación económica en las 32 entidades 
federativas entre 2020 y 2024.

## Fuente de datos
INEGI - Encuesta Nacional de Ocupación y Empleo (ENOE)
https://www.inegi.org.mx/programas/enoe/15ymas/

## Herramientas utilizadas
- Python 3.13
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## Estructura del proyecto
- `analisis_mercado_laboral.ipynb` — Notebook principal con análisis y visualizaciones
- `enoe_desempleo_mexico_2020_2024.csv` — Dataset en formato wide (32 estados x 24 columnas)
- `enoe_desempleo_largo_2020_2024.csv` — Dataset en formato long (640 registros)

## Pasos del análisis
1. Carga y exploración inicial de los datos
2. Verificación de calidad: valores ausentes y duplicados
3. Visualización 1: Evolución nacional del desempleo 2020-2024
4. Visualización 2: Top 10 estados con mayor desempleo promedio
5. Visualización 3: Informalidad laboral por región
6. Visualización 4: Mapa de calor por estado y año
7. Visualización 5: Relación entre informalidad y desempleo por estado
8. Conclusiones y recomendaciones

## Hallazgos principales
- El COVID-19 generó un pico de desempleo del 4.9% en 2020-T2
- Ciudad de México y Tabasco lideran el desempleo promedio 2020-2024
- El Sur-Sureste tiene 24 puntos más de informalidad que el Norte
- Para 2024 todos los estados recuperaron niveles prepandemia

## Autor
Luis Fernando Rubio Avalos
[GitHub](https://github.com/Vaurefu1)
