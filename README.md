# Facilities Maintenance KPI Analysis

## Descripción del proyecto

Este proyecto analiza órdenes de trabajo de mantenimiento en una instalación industrial para identificar patrones de costos, tiempos de resolución, cumplimiento de SLA y áreas con mayor impacto operativo.

> Nota: el dataset incluido es simulado con una estructura realista de mantenimiento industrial. Se utiliza para demostrar habilidades de análisis de datos, métricas operativas, visualización y comunicación de hallazgos.

## Problema de negocio

En operaciones de mantenimiento, no basta con cerrar órdenes de trabajo. También es importante entender qué áreas generan más trabajo, qué categorías generan más costo, qué prioridades incumplen más los tiempos esperados y dónde se acumulan más horas de paro.

Este proyecto responde a la pregunta:

**¿Cómo se puede usar el análisis de datos para mejorar la gestión de mantenimiento y priorizar acciones operativas?**

## Objetivos

- Crear indicadores clave de mantenimiento.
- Analizar órdenes de trabajo por categoría, prioridad, área y técnico.
- Evaluar cumplimiento de SLA.
- Identificar áreas con mayor costo y mayor tiempo de paro.
- Comunicar hallazgos de forma clara para apoyar decisiones.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Estructura del repositorio

```text
facilities-maintenance-kpi-analysis/
├── data/
│   └── maintenance_work_orders.csv
├── notebooks/
│   └── facilities_maintenance_kpi_analysis.ipynb
├── assets/
│   ├── work_orders_by_category.png
│   ├── sla_by_priority.png
│   ├── monthly_cost.png
│   └── downtime_by_site.png
└── README.md
```

## Indicadores principales

| Indicador | Resultado |
|---|---:|
| Total de órdenes de trabajo | 1,300 |
| Cumplimiento general de SLA | 92.5% |
| Tiempo promedio de resolución | 24.0 horas |
| Costo total estimado | $1,821,056.71 |
| Categoría con más órdenes | HVAC |
| Área con mayor costo | Production A |

## Visualizaciones

### Órdenes de trabajo por categoría

![Órdenes por categoría](assets/work_orders_by_category.png)

### Cumplimiento SLA por prioridad

![SLA por prioridad](assets/sla_by_priority.png)

### Costo mensual de mantenimiento

![Costo mensual](assets/monthly_cost.png)

### Horas de paro por área

![Horas de paro por área](assets/downtime_by_site.png)

## Hallazgos principales

- La categoría con mayor volumen de trabajo fue **HVAC**, lo que sugiere una oportunidad para revisar rutinas preventivas o causas repetitivas.
- El cumplimiento general de SLA fue de **92.5%**, por lo que todavía existe oportunidad de mejora en tiempos de respuesta.
- El área con mayor costo estimado fue **Production A**, lo que puede indicar una zona crítica para mantenimiento preventivo.
- Las órdenes de prioridad alta y crítica tienen mayor impacto en horas de paro y costo total.

## Recomendaciones

- Revisar las categorías con mayor número de órdenes repetitivas.
- Priorizar mantenimiento preventivo en las áreas con mayor costo y mayor tiempo de paro.
- Analizar causas raíz en órdenes críticas.
- Crear un dashboard operativo para seguimiento semanal.
- Establecer metas de mejora para cumplimiento SLA y reducción de tiempo promedio de resolución.

## Conclusión

Este proyecto muestra cómo el análisis de datos puede apoyar la toma de decisiones en mantenimiento industrial. Al convertir órdenes de trabajo en indicadores claros, es posible identificar áreas críticas, reducir tiempos de respuesta, controlar costos y mejorar la planeación del mantenimiento.
