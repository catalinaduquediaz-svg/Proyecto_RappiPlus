# Proyecto RappiPlus: de datos a decisiones de negocio

Proyecto final del bootcamp de **Data Analytics de TripleTen**. El objetivo es evaluar el desempeño de RappiPlus y convertir los datos de pedidos, catálogo, marketing y comportamiento de usuarios en información útil para la toma de decisiones.

## Objetivos del análisis

- Revisar y preparar los datos, identificando duplicados, valores faltantes e inconsistencias.
- Evaluar la rentabilidad mediante ingresos, costos, inversión en marketing, utilidad y margen.
- Analizar el embudo de conversión para identificar las etapas con mayor abandono.
- Examinar la retención de usuarios por cohortes.
- Evaluar un experimento A/B relacionado con la interfaz del proceso de checkout.
- Comunicar los resultados mediante dashboards interactivos en Tableau.

## Herramientas

- **Python y Pandas:** exploración, limpieza, validación y análisis de datos.
- **SQL:** análisis del comportamiento de los usuarios, embudo de conversión y retención.
- **Tableau Public:** visualización de indicadores y dashboards interactivos.
- **Jupyter Notebook:** documentación del proceso analítico y sus resultados.

## Hallazgos principales

- **Rentabilidad:** para los pedidos con información numérica completa, se calcularon ingresos por **$51.965.834,26**, utilidad de **$5.969.972,32** y margen de utilidad de **11,49 %**.
- **Embudo:** la mayor pérdida de usuarios se observó entre el inicio del checkout y el registro de la información de pago.
- **Experimento A/B:** la conversión fue de **15,69 %** en el grupo de control y **16,29 %** en el grupo de tratamiento. La prueba estadística no encontró evidencia suficiente para concluir que la nueva interfaz mejorara significativamente la conversión.
- **Calidad de datos:** se detectaron duplicados, valores faltantes y cantidades extremas. Estas limitaciones se documentaron y deben considerarse al interpretar los indicadores, especialmente los resultados por producto.

Los indicadores financieros corresponden al subconjunto de pedidos utilizado en el análisis tras la revisión de calidad. Las conclusiones deben leerse teniendo en cuenta las limitaciones documentadas en el notebook.

## Dashboards en Tableau Public

- [Resumen ejecutivo](https://public.tableau.com/app/profile/catalina.duque/viz/ProyectoRappiplus_Final/ResumenEjecutivo?publish=yes)
- [Detalle de pedidos](https://public.tableau.com/app/profile/catalina.duque/viz/ProyectoRappiplus_Final/DetalledePedidos?publish=yes)

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `S12 Estudiante_Proyecto_Final (5).ipynb` | Notebook principal con el flujo de análisis, validaciones y resultados. |
| `orders_tableau.csv` | Datos de pedidos preparados para Tableau. |
| `catalog_tableau.csv` | Datos del catálogo preparados para Tableau. |
| `marketing_tableau.csv` | Datos de inversión en marketing preparados para Tableau. |
| `ProyectoRappiplus_Final.twb` | Libro de Tableau con las hojas y dashboards del proyecto. |

## Cómo consultar el proyecto

1. Comienza por el notebook para revisar las preguntas de negocio, la preparación de los datos y el análisis.
2. Abre los dashboards de Tableau para explorar los principales indicadores y los detalles de los pedidos.
3. Consulta los CSV incluidos en el repositorio como fuentes preparadas para las visualizaciones.

> **Nota de reproducibilidad:** el libro `.twb` puede conservar rutas locales de los archivos de datos. Si al abrirlo Tableau no encuentra las fuentes, vuelve a conectar cada fuente con el CSV correspondiente de este repositorio.

## Flujo de trabajo del portafolio

Este repositorio complementa la documentación de proyectos en Notion. Notion funciona como espacio de presentación y síntesis; GitHub conserva notebooks, archivos de datos, documentación técnica y recursos del proyecto.

**Portafolio profesional en Notion:** [Abrir portafolio](https://app.notion.com/p/Portafolio-Profesional-3c8ea9f7feee807ba167f79d7996ad00?source=copy_link)

---
*Proyecto académico de portafolio. Los resultados se basan en los datos y supuestos documentados en el notebook.*
