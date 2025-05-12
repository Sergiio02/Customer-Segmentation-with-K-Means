<img src="https://www.xsights.co.uk/wp-content/uploads/2024/05/musteri-segmentasyonu.png" alt="Imagen de Customer Segmentation" width="700"/>

# 🛒 Customer Segmentation with K-Means

Este proyecto tiene como objetivo realizar una segmentación de clientes utilizando el algoritmo de K-Means. A través de este análisis, se busca identificar diferentes grupos de clientes basados en características como datos personales o hábitos de consumo.

## 📝 Descripción Detallada

El flujo de trabajo del proyecto se estructura en varias etapas:

1. **Limpieza de Datos (01_Cleaning.ipynb)**: En esta etapa se realiza una exploración inicial del dataset, así como su limpieza, manejando valores nulos, eliminando registros erróneos o haciendo ingeniería de carcaterísticas.

2. **Análisis Exploratorio de Datos (02_EDA.ipynb)**: Se exploran las principales características del conjunto de datos a través de visualizaciones y estadísticas descriptivas. Esta etapa busca entender las relaciones entre las variables y obtener una idea general del comportamiento de los clientes.

3. **Preprocesamiento de Datos (03_Preprocessing.ipynb)**: Aquí se realizan transformaciones como la codificación de variables categóricas y el escalado.

4. **Modelado (04_Model.ipynb)**: Finalmente, se aplica el algoritmo de K-Means para segmentar a los clientes en diferentes grupos y se explican los resultados.


## 📂 Estructura del Proyecto


- **data/**
  - `clean_dataset.csv` # Dataset limpio y listo para el análisis, sin escalado
  - `df_pca.csv` # Dataset con las componentes principales obtenidas por PCA
  - `df_pre.csv` # Dataset preprocesado
  - `marketing_campaign.csv` # Dataset original con datos de la campaña de marketing

- **notebooks/**
  - `01_Cleaning.ipynb`
  - `02_EDA.ipynb`
  - `03_Preprocessing.ipynb`
  - `04_Model.ipynb`

-  `README.md` # Documentación del proyecto

## 📥 Requisitos

Este proyecto requiere las siguientes bibliotecas de Python:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly

## 📊 Resultados y Conclusiones

El análisis de segmentación con K-Means ha revelado cinco grupos claramente diferenciados de clientes. Estos grupos permiten a la empresa implementar estrategias de marketing más personalizadas y eficaces. A continuación, se detallan los perfiles de cada uno de los clusters:

### 🔸 Cluster 0: Parejas con Alto Poder Adquisitivo y Compromiso Comercial
Este grupo destaca por su elevado nivel de ingresos, alto gasto mensual y fuerte involucramiento con campañas de marketing. Aunque no les interesan los descuentos, participan activamente en promociones y tienen una tasa de conversión elevada. Representan un público ideal para estrategias premium, fidelización y programas exclusivos.

- **Estrategia recomendada**: Ofertas VIP, contenido exclusivo y experiencias personalizadas de marca.

### 🔸 Cluster 1: Jóvenes con Bajos Ingresos y Alta Sensibilidad al Precio
Este cluster está compuesto por los clientes más jóvenes con menor poder adquisitivo. Tienen un consumo limitado, dependen de descuentos y presentan una escasa participación en campañas. Aunque es un segmento difícil de rentabilizar, puede ser clave para captar volumen si se ajustan los precios o se implementan promociones específicas.

- **Estrategia recomendada**: Descuentos agresivos, cupones, campañas dirigidas a productos accesibles o básicos.

### 🔸 Cluster 2: Solteros Profesionales de Alto Nivel y Alta Receptividad
Este grupo está formado por clientes con altos ingresos, educación superior y sin cargas familiares. Son altamente receptivos a campañas de marketing y muestran un comportamiento de compra intensivo, con una elevada tasa de conversión en canales digitales.

- **Estrategia recomendada**: Marketing digital directo, campañas de fidelización y programas de membresía premium.

### 🔸 Cluster 3: Familias Estables de Clase Media con Gasto Controlado
Este cluster está compuesto por parejas con hijos y nivel educativo alto. Aunque sus ingresos son moderados, su gasto es cuidadoso y aprovechan activamente los descuentos. Sin embargo, no participan en campañas, lo que indica una baja sensibilidad al marketing tradicional.

- **Estrategia recomendada**: Packs familiares, descuentos por volumen y promociones orientadas al ahorro familiar.

### 🔸 Cluster 4: Solteros con Hijos y Estabilidad Económica Moderada
Este grupo tiene ingresos medios y una actitud mixta: utilizan descuentos con frecuencia, pero muestran baja participación en campañas. Su comportamiento de compra es regular, pero más contenido en comparación con otros clusters.

- **Estrategia recomendada**: Ofertas prácticas, descuentos personalizados y beneficios por recurrencia o fidelidad.

### Conclusión Final

El análisis de segmentación ha permitido identificar diferentes perfiles de clientes, lo que facilita la creación de campañas de marketing más precisas y adaptadas a cada grupo. Cada cluster muestra comportamientos y preferencias únicas que pueden aprovecharse para desarrollar estrategias de marketing más efectivas, tanto a nivel digital como tradicional. 

Implementar estas estrategias dirigidas a cada segmento de manera personalizada no solo mejorará la tasa de conversión, sino que también fortalecerá la relación con los clientes y potenciará la fidelidad.activamente en promociones y tienen una tasa de conversión elevada. Representan un público ideal para estrategias premium, fidelización y programas exclusivos.

## Próximos Pasos

- **Optimización del número de clusters**: Probar con diferentes números de clusters y otros métodos de evaluación.
- **Ingeniería de características**: Probar a mezclar o crear nuevas variables para analziar como cambian los resultados
- **Aplicación en tiempo real**: Implementar este modelo en un sistema de recomendación o marketing automático.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, por favor abre un pull request o una issue.

## 👨‍💻 Autor

Sergio Delgado  
sergiodelamp@gmail.com  
[https://github.com/Sergiio02](https://github.com/Sergiio02)
