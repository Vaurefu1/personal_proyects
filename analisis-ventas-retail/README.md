# Análisis de Ventas Retail 2023

**Autor:** Luis Fernando Rubio Avalos · Data Analyst  
**Fecha:** Noviembre 2026  
**Herramientas:** Python · Pandas · Matplotlib · NumPy · Jupyter Notebook

---

## 🔗 Link al Proyecto

📓 **Notebook:** `analisis_ventas_retail.ipynb`  
📄 **Reporte PDF:** `reporte_ventas_retail_mexico.pdf`  
📦 **Dataset:** `online_retail_2023.csv` (58,029 registros de transacciones)

---

## ❓ Problema Identificado

Los negocios de retail toman decisiones de inventario, marketing y retención de clientes de forma intuitiva, sin análisis de datos. Esto genera tres problemas concretos:

1. **Quiebre o exceso de stock** por no anticipar la demanda estacional
2. **Presupuesto de marketing mal distribuido** al no conocer qué productos son los más rentables
3. **Pérdida de clientes valiosos** por no detectar a tiempo quiénes están dejando de comprar

Este proyecto responde cuatro preguntas de negocio clave usando datos reales de transacciones.

---

## 🛠️ Solución Desarrollada

Análisis exploratorio de datos (EDA) completo sobre 58,029 transacciones de un retailer con operaciones en UK y 11 países internacionales.

**Preguntas respondidas:**
- ¿Cómo evolucionan las ventas a lo largo del año? → Análisis de estacionalidad mensual
- ¿Qué productos generan más ingresos? → Ranking de SKUs por revenue
- ¿Qué mercados internacionales son más valiosos? → Distribución geográfica de ventas
- ¿Qué segmentos de clientes existen? → Segmentación RFM (Recencia, Frecuencia, Monto)

---

## ⚙️ Herramientas Utilizadas

| Herramienta | Uso |
|---|---|
| **Python 3** | Lenguaje principal |
| **Pandas** | Limpieza, transformación y agrupación de datos |
| **Matplotlib** | Visualizaciones y gráficas |
| **NumPy** | Cálculos estadísticos y ranking percentil (RFM) |
| **Jupyter Notebook** | Entorno de análisis y documentación |
| **GitHub** | Control de versiones y portafolio |

---

## 📊 Resultados

### Métricas generales

| Métrica | Valor |
|---|---|
| Venta total 2023 | £2,225,573 |
| Facturas emitidas | 12,940 |
| Clientes únicos | 4,606 |
| Ticket promedio | £171.99 |

### Hallazgos clave

1. **Estacionalidad fuerte:** Noviembre es el mes pico con £328k (2.3x el mínimo de julio). El Q4 concentra el 36% del ingreso anual.
2. **Concentración de productos:** El top 10 de SKUs genera ~20% del revenue; seguimiento de Principio de Pareto.
3. **Mercados internacionales:** Alemania y Francia son los destinos más valiosos fuera de UK.
4. **Segmentación RFM:** Los Champions (742 clientes, 16%) generan el 32.7% del ingreso total. Hay 1,098 clientes "En riesgo" con £214k de valor histórico.

### Recomendaciones accionables

- 📦 Anticipar inventario en agosto para cubrir demanda Q4
- 👑 Lanzar programa VIP para Champions (máximo valor, mínimo costo de retención)
- 📧 Campaña de reactivación para los 1,098 clientes "En riesgo"
- 🌍 Evaluar expansión en Alemania y Francia con catálogo localizado

---

## 💡 Valor para una Empresa

Este análisis demuestra cómo los datos de transacciones permiten pasar de reportes descriptivos básicos a **decisiones de negocio accionables**: desde la optimización de inventario estacional hasta estrategias diferenciadas por segmento de cliente.

Un analista de datos especializado en retail puede reducir el quiebre de stock, aumentar la retención de clientes de alto valor y maximizar el ROI de campañas de marketing, generando impacto directo en el P&L del negocio.

---

*Proyecto desarrollado como parte del portafolio de especialización en retail analytics.*
