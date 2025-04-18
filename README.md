# Científico de Datos 

👩‍🔬👩‍💻 Profesional en Administración y Negocios Internacionales, certificada en Ciencia de Datos, con experiencia en análisis de bases de datos, automatización de procesos y visualización de datos. Poseo un nivel de inglés avanzado y una combinación sólida de habilidades analíticas, tecnológicas y comunicativas. He trabajado en gestión de importaciones y el sector marítimo, desempeñándome como Ejecutiva de Importaciones y Sommelier en cruceros, desarrollando experiencia en negociación, análisis de tendencias y evaluación de mercados internacionales. Especializada en Python, Power BI, Excel y SQL, aplico análisis de datos y generación de reportes para la toma de decisiones estratégicas.


## PROYECTOS

## Telecomunicaciones Interconnect

![Vista previa del análisis de Interconnect](images/telecom.png) 

La retención de clientes es un factor clave para la sostenibilidad y crecimiento de las empresas en sectores altamente competitivos como el de las telecomunicaciones. En este contexto, Interconnect, un operador ficticio, busca anticiparse a la cancelación de contratos mediante el uso de ciencia de datos. El objetivo de este proyecto es desarrollar un modelo predictivo que identifique a los clientes con mayor probabilidad de cancelar sus servicios, analizando sus características demográficas, contractuales y de uso.

El proceso incluye preprocesamiento de datos, análisis exploratorio, y la construcción y evaluación de modelos de clasificación utilizando técnicas de machine learning. Tras balancear las clases con SMOTE para abordar el desbalance inicial, se evaluaron tres modelos: RandomForestClassifier, LogisticRegression y DecisionTreeClassifier. El RandomForestClassifier mostró el mejor desempeño inicial con un AUC-ROC de 0.8464, pero fue optimizado utilizando Grid Search, alcanzando un AUC-ROC de 0.8548 en los datos de validación.

Con el objetivo de mejorar aún más el rendimiento, se implementó XGBoost, alcanzando un AUC-ROC de 0.8849, lo que lo convirtió en el modelo más eficiente para este problema. Este enfoque no solo permitió predecir la tasa de cancelación de clientes, sino también extraer insights clave que pueden ayudar a definir estrategias comerciales para mejorar la fidelización.

*Habilidades técnicas: Preprocesamiento de Datos, Análisis Exploratorio de Datos (EDA), Balanceo de Clases (SMOTE), Modelos de Clasificación, Evaluación de Modelos (AUC-ROC), Optimización de Modelos (XGBoost), Extracción de Insights, Visualización y Reportes*

[Proyecto completo](https://github.com/yesi-or/Telecom.git)

## Telecomunicaciones MEGALINE

![Vista previa del análisis de Interconnect](images/megaline.jpg) 

Este proyecto trata sobre el análisis de los ingresos generados por dos planes de prepago de Megaline, Surf y Ultimate, utilizando datos de 500 clientes durante 2018. El objetivo principal fue identificar qué plan generaba mayores ingresos y cómo variaban estos según el consumo de datos, minutos y mensajes. A través de este análisis, se buscó entender el comportamiento de los usuarios y cómo optimizar la oferta de servicios.

Se encontró que, en los primeros dos meses, Ultimate generó más ingresos que Surf, pero a partir de marzo, Surf superó a Ultimate en ingresos. Además, el plan Surf mostró más variabilidad en los ingresos, mientras que Ultimate mantuvo ingresos más estables.

En cuanto al comportamiento de los usuarios, los del plan Surf incurrieron en más cargos adicionales por datos, ya que muchos superaron el límite de GB incluidos en su plan. En cambio, los usuarios de Ultimate generalmente se mantuvieron dentro de su límite de datos.

El plan Ultimate generó más ingresos fijos debido a su mayor tarifa y número de usuarios, pero los cargos adicionales por consumo de datos provinieron principalmente de los usuarios de Surf.

Se plantearon dos pruebas de hipótesis: Verificar si los ingresos promedio de Ultimate y Surf eran diferentes. Y comprobar si los ingresos de los usuarios en Nueva York-Nueva Jersey diferían de los de otras regiones. Ambas pruebas se realizaron con un nivel de significancia del 5% (α = 0.05).

*Habilidades técnicas: Análisis de Ingresos, Preprocesamiento de Datos, Análisis Exploratorio de Datos (EDA), Visualización de Datos, Modelado Predictivo, Evaluación de Modelos, Balanceo de Clases (SMOTE), Optimización de Modelos, Pruebas de Hipótesis, Estadísticas Descriptivas, Análisis de Comportamiento del Cliente, Extracción de Insights*

[Proyecto completo](https://github.com/yesi-or/Megaline.git)

## INSTACART

![Vista previa del análisis de Instacart](images/instacart.jpg) 

En este proyecto se analizan los datos proporcionados por Instacart, una empresa de entregas de supermercado en línea, con el objetivo de explorar el comportamiento de compra de los usuarios y descubrir relaciones significativas entre variables clave.

El análisis comienza con un Análisis Exploratorio de Datos (EDA), donde se realiza una limpieza y comprensión profunda del dataset. Se examinan aspectos como la frecuencia de pedidos, los productos más comprados, los horarios con mayor actividad, y las categorías más populares.

A lo largo del proceso, se identifican y visualizan patrones, correlaciones y tendencias entre los distintos conjuntos de datos disponibles, como productos, órdenes, usuarios y departamentos. Estas visualizaciones permiten evaluar comportamientos de compra repetitiva, identificar hábitos de consumo y generar hallazgos útiles para futuras estrategias de negocio o personalización de la experiencia del cliente.

Este enfoque no solo proporciona una visión global del funcionamiento de la plataforma, sino que también sienta las bases para desarrollar modelos predictivos o sistemas de recomendación basados en los datos analizados.

*Habilidades técnicas: Python, Análisis Exploratorio de Datos (EDA), Limpieza de datos, Visualización de datos, Pandas, NumPy, Matplotlib/Seaborn, Correlación de datos, Machine Learning (para futuros modelos predictivos o sistemas de recomendación), SQL*

[Proyecto completo](https://github.com/yesi-or/Instacart.git)

## Pozos Petroleros

![Predicción de rentabilidad de pozos petroleros](images/pozos.jpeg) 

En este proyecto se aborda un caso de análisis y modelado para una empresa del sector petrolero, con el objetivo de identificar los pozos de petróleo más rentables a partir de datos históricos de producción y ganancias estimadas.

El primer paso consiste en desarrollar una función que calcule la ganancia total esperada para un conjunto de pozos seleccionados, considerando tanto los ingresos proyectados como los costos operativos. Posteriormente, se construyen modelos de predicción que permiten estimar con mayor precisión el rendimiento de pozos no evaluados previamente, basados en características geológicas, ubicación y producción histórica.

A través de este enfoque, se busca no solo hallar el pozo más rentable, sino también ofrecer una herramienta que facilite la toma de decisiones estratégicas para la inversión y explotación de nuevos pozos. El análisis incluye visualizaciones de las predicciones y una evaluación comparativa entre los diferentes sitios de perforación, destacando aquellos con mayor potencial de retorno económico.

Este trabajo combina programación, análisis de datos y modelado predictivo para generar valor cuantificable en un contexto de alto impacto financiero como es la industria del petróleo.

*Habilidades técnicas: Python, Análisis de datos, Modelado predictivo, Machine Learning, Regresión, Evaluación de modelos, Visualización de datos, Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn, Bootstrapping*

[Proyecto completo](https://github.com/yesi-or/M-todo-Bootstrapping)


## Film-Junky-Union

![Análisis NLP de reseñas de cine](images/movie.jpeg)

En el marco del desarrollo de Film Junky Union, una innovadora comunidad enfocada en los amantes del cine clásico, se ha planteado la necesidad de automatizar el proceso de análisis de reseñas de películas. El objetivo principal de este proyecto es construir un sistema capaz de identificar automáticamente críticas negativas, permitiendo así una mejor moderación y personalización del contenido para los usuarios.

Para lograrlo, se utilizó un conjunto de datos de reseñas de películas provenientes de IMDB, el cual incluye etiquetas de polaridad (positiva o negativa). A partir de este corpus, se entrenaron distintos modelos de clasificación de texto, con la meta de alcanzar un valor F1 mínimo de 0.85, asegurando un equilibrio entre precisión y exhaustividad en la detección de críticas negativas.

Este proyecto explora diferentes enfoques de preprocesamiento y vectorización de texto, incluyendo técnicas tradicionales como TF-IDF combinadas con modelos lineales, así como modelos de lenguaje más avanzados como BERT. A lo largo del desarrollo, se analizó la eficiencia, el rendimiento y la capacidad de generalización de cada enfoque, priorizando un balance entre calidad y costo computacional.

*Habilidades técnicas: Python, NLP (Natural Language Processing), spaCy, TF-IDF, Logistic Regression, BERT (Bidirectional Encoder Representations from Transformers), Scikit-learn, Evaluación de modelos, GPU/CPU Computation*

[Proyecto completo](https://github.com/yesi-or/Film-Junky-Union.git)

### Compañia de Seguros

![Aplicación de k-NN en seguros](images/seguros.jpeg) 

La compañía de seguros Sure Tomorrow ha identificado la oportunidad de utilizar técnicas de machine learning para resolver diversas tareas clave en su negocio y mejorar la eficiencia operativa. El proyecto se centra en cuatro tareas principales que buscan optimizar el marketing, la predicción de prestaciones y la protección de datos personales de los clientes.

La primera tarea consiste en encontrar clientes similares a un cliente determinado para mejorar las estrategias de marketing, utilizando el algoritmo k-NN (k-Nearest Neighbors). En la segunda tarea, se busca predecir la probabilidad de que un nuevo cliente reciba una prestación del seguro, comparando el desempeño de un modelo predictivo con un modelo dummy. La tercera tarea se enfoca en predecir el número de prestaciones de seguro que un nuevo cliente podría recibir utilizando un modelo de regresión lineal.

La cuarta y última tarea tiene como objetivo proteger los datos personales de los clientes mediante un algoritmo de enmascaramiento u ofuscación de datos, asegurando que no se vea afectada la calidad de los modelos de machine learning. Este enfoque permite mantener la confidencialidad de la información sin comprometer el rendimiento de los modelos predictivos.

El proyecto combina un análisis exhaustivo de datos, el uso de algoritmos de machine learning, y técnicas de protección de datos para mejorar la toma de decisiones estratégicas y la personalización de servicios en el sector asegurador.

*Habilidades técnicas: Python, Machine Learning, Algoritmo k-NN (k-Nearest Neighbors), Regresión Lineal, Modelos predictivos, Escalado de datos, Enmascaramiento de datos, Transformación de datos, Evaluación de modelos (F1 score, RMSE, R2), Métricas de distancia (Manhattan, Euclidiana), Pandas, NumPy, Scikit-learn*

[Proyecto completo](https://github.com/yesi-or/Compa-ia-de-Seguros.git)


### HABILIDADES TECNOLÓGICAS

- 📊 **Lenguajes de programación:** Python, SQL
- 🖼️ **Visualización de datos:** Plotly, Seaborn, Tableau, Matplotlib
- 🧰 **Librerías:** Sci-kit learn, Pandas, NumPy
- 🧠 **Machine Learning:** XGBoost, LightGBM, TensorFlow, PyTorch
- 📉 **Herramientas adicionales:** Git & GitHub, Excel (macros y tablas dinámicas), Data Wrangling y Cleaning
- ☁️ **Otros:** Google Workspace, Zoom, VS Code, Jupyter Notebook, ERP, Fidelio


### COMPETENCIAS

- 🧩 Pensamiento analítico
- 📊 Modelado estadístico
- 🧠 Resolución de problemas
- ⚙️ Optimización de algoritmos
- 📈 Toma de decisiones basada en datos
- 🗣️ Comunicación efectiva
- 🤝 Trabajo en equipo
- ⏱️ Gestión del tiempo
- 🔍 Curiosidad y aprendizaje continuo
- 🌱 Adaptabilidad


