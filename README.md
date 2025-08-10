# Freshly Cosmetics - Data Analyst Case Study

Este repositorio contiene la documentación y recursos del proyecto realizado para Freshly Cosmetics, enfocado en análisis de datos para apoyar al equipo de marketing y producto.

---

## Contenidos

- Preparación y limpieza de los datos originales
-	Exploración y análisis descriptivo de ventas
-	Dashboards interactivos
-	Análisis de cohortes para entender la repetición de compra
-	Estudio de las preocupaciones principales de los clientes
-	Propuestas y recomendaciones basadas en los datos para marketing y producto
-	Respuestas a preguntas clave del proceso de selección

---

## Datasets

Los datos proporcionados están almacenados en BigQuery bajo el proyecto `freshly-case-study-468308`, con las siguientes tablas principales:

- `freshly_data.INFORMACION_PRODUCTOS`: información detallada de productos vinculada a un archivo .xlsx en Drive  
- `freshly_data.INFORMACION_PEDIDOS`: datos de pedidos, clientes y mercados vinculados a un archivo .xlsx en Drive  
- `freshly_data.venta_sku_2024`: datos sobre ventas vinculados a un archivo .csv en Drive  

---

## Notebooks

Los notebooks están alojados en BigQuery y disponibles para consulta con acceso al proyecto:

- [Limpieza y preparación de los datos](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1sfreshly-case-study-468308!2seurope-southwest1!3sb4f03c22-71d1-46a9-a4d0-bc5bd5eb72cf!2e2)  
En este notebook se han cargado y unido las tres fuentes de datos proporcionadas, se ha realizado su tratamiento y limpieza, y finalmente se ha exportado un nuevo dataframe llamado `df_cleaned`, que es la base para las visualizaciones en Looker Studio y el desarrollo del case study en el siguiente notebook.

- [Case Study](https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1sfreshly-case-study-468308!2seurope-southwest1!3s8c109f42-c2ff-4a76-a887-b3937f5037f1!2e2)  
En este notebook se desarrollan los distintos ejercicios propuestos en el case study para la posición de Data Analyst en Freshly Cosmetics.  
Se exploran los datos, se extraen conclusiones generales, se realiza un análisis de cohortes, otro análisis específico para el equipo de marketing, y se responden preguntas relacionadas con el rol de Data Analyst dentro de Freshly.

*(Los enlaces están disponibles según permisos de acceso)*

---

## Dashboards Interactivos

- [Dashboard Looker Studio](https://lookerstudio.google.com/reporting/4fbe94d7-af23-433c-aabf-25c1e019c676)  
Dashboard interactivo vinculado al dataframe de BigQuery donde se pueden consultar los datos en tiempo real y extraer insights útiles para departamentos no técnicos.  

Consta de 3 hojas principales:  
- La primera está enfocada al análisis financiero, mostrando facturación total, por categoría, producto y el valor de productos vendidos o regalados.  
- La segunda está orientada al análisis de marketing, donde el equipo puede consultar clientes nuevos y repetidores, productos más comprados, principales preocupaciones, distribución de ventas por mercado y tipo de venta.  
- La tercera muestra el impacto de las colaboraciones en las ventas. Actualmente hay pocas colaboraciones y el impacto no es muy evidente, pero servirá para monitorizar su efecto si en el futuro se incrementa la inversión en este área.

Los dashboards cuentan con filtros para consultar por fecha, categoría, SKU, cliente y mercado.

---

## Notas

- Se integraron múltiples fuentes de datos (productos, pedidos, ventas) para un análisis completo y facilmente actualizable.
- El proyecto está desarrollado para facilitar la toma de decisiones en Freshly Cosmetics, con dashboards interactivos y análisis detallados.
- **Todo el contenido y los recursos compartidos en este repositorio son privados y están accesibles únicamente para los reclutadores de Freshly Cosmetics con los permisos adecuados.** 
- Para consultas o más información, contacta conmigo en [fpiqueraspons@gmail.com].

---

¡Gracias por vuestro interés en mi trabajo! He aprendido mucho realizándolo y, además, me he divertido bastante en el proceso. Espero que os guste y quedo a vuestra disposición para cualquier consulta.
