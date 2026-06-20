# Segmentación de Clientes de e-commerce

## Resumen

En el comercio electrónico, comprender el comportamiento de los usuarios es fundamental para optimizar las estrategias de marketing y la retención de clientes. Por esta razón, el objetivo de este proyecto es segmentar a los visitantes de un sitio web en grupos con características homogéneas utilizando un conjunto de datos de Google Analytics que registra el origen de visitas, los tipos de dispositivos y métricas de interacción en la sesión. En primer lugar, se realizó un Análisis Exploratorio de Datos (EDA) en el cual se identificó que la mayor afluencia ocurre desde computadores de escritorio vía Chrome en las tardes de lunes a viernes. Además, se evidenció que las visitas al sitio web provienen principalmente de enlaces referidos (44%) y búsquedas orgánicas (32%). Posteriormente, tras el preprocesamiento, se implementó un modelo de segmentación con K-Means, justificando la elección de 5 clústers mediante el método del codo y gráficos de siluetas. Finalmente, se aplicó t-SNE para la reducción de dimensionalidad, lo que permitió visualizar la distribución y validar la calidad de los clústeres formados.

---

## Objetivos

- Comprender los patrones de comportamiento, las características tecnológicas y el origen del tráfico de los visitantes del sitio web.
- Segmentar a los usuarios en grupos homogéneos mediante técnicas de aprendizaje no supervisado para descubrir perfiles de clientes claramente diferenciados.
- Definir perfiles accionables a partir de los clústeres identificados para facilitar el diseño de campañas de marketing personalizadas y orientadas a mejorar la retención.

---

## Tecnologías utilizadas

- `Python` como lenguaje de programación.
- `Visual Studio Code` como entorno de desarrollo.

---

##  Descripción de archivos

- `notebook_segmentacion.ipynb`: Notebook en Python con todo el flujo de trabajo (análisis exploratorio, limpieza de datos, modelo de segmentación).  
- `informe_segmentacion.pdf`: Informe con los resultados.  
