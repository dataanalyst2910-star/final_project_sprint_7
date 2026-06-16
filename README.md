# Proyecto Final Sprint 7

Este repositorio contiene el análisis realizado durante el proyecto final del Sprint 7 del caso ConnectaTel.

## Objetivo del Proyecto

Explorar, limpiar y analizar estas bases de datos (plans.csv, users_latam.csv y usage.csv) para construir una visión clara, confiable y accionable sobre el comportamiento de uso de los clientes y cómo varía entre diferentes grupos de usuarios, respondiendo a las siguientes interrogantes del negocio:

- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

## Datasets utilizados

- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## Flujo general del proyecto
	                                   	
- Cargar y explorar:	Cargar y explorar plans, users_latam, usage.
   
Resultado para el negocio: Visión clara de la estructura y tipos de columna de cada dataset.
   
- Identificación de problemas de calidad:	Contar nulos, detectar sentinels, revisar fechas fuera de rango.
 
Resultado para el negocio: Lista priorizada de problemas que pueden sesgar decisiones.

- Limpieza básica: Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.
  
Resultado para el negocio: Datos consistentes y listos para análisis estadístico.
  
- Summary statistics: Revisar las medidas clave en variables categóricas y numéricas.
  
Resultado para el negocio: Medidas clave (media, mediana, percentiles) que muestran el comportamiento típico y extremo

- Visualización & outliers: Creación de histogramas y boxplots.
  
Resultado para el negocio: Visualización de sesgos, patrones de usuarios o datos atípicos.
  
- Segmentación:	Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.
   
Resultado para el negocio: Segmentos accionables que permiten diseñar ofertas, campañas y migraciones de plan.
  
- Insight ejecutivo: Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.	

Resultado para el negocio: Responder a las preguntas del negocio y proponer acciones concretas.

## 📂 Contenido del repositorio

- `S7_Version_Estudiante_Project_ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dataanalyst2910-star/final_project_sprint_7/blob/main/S7_Version_Estudiante_Project_ConnectaTel.ipynb)
O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7_Version_Estudiante_Project_ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. Si existe un error o problema a la hora de ejecutar las ordenes, verificar que los datasets que estan en el repositorio esten debidamente cargados en el visualizador
