## **Descripción**

El objetivo de este trabajo es realizar un Análisis Exploratorio de Datos (EDA) sobre el conjunto de datos del dataset “Heart Disease 2022”, con el fin de comprender su estructura, detectar patrones relevantes, errores y así poder llegar a sacar unas conclusiones que respondan a las hipótesis que nos planteamos.

Este dataset está relacionado con la salud física y mental, puesto que queremos desarrollar el siguiente tema: “Actividad física y salud cardiovascular: analizar cómo diferentes niveles de ejercicio influyen en indicadores de riesgo (colesterol, IMC, frecuencia cardíaca en reposo, hipertensión)”.

Más concretamente, este dataset recoge información procedente de encuestas de salud realizadas en Estados Unidos a una serie de personas, donde contiene datos como variables demográficas, hábitos de vida, indicadores de salud general y antecedentes médicos. El análisis de este tipo de datos es especialmente relevante en el ámbito de la salud, ya que permite identificar factores de riesgo asociados a enfermedades cardiovasculares y apoyar la toma de decisiones preventivas.

El EDA permite detectar valores faltantes, incoherencias, variables poco informativas y posibles relaciones entre variables que pueden guiar a análisis posteriores.

## **Hipótesis**

Las hipótesis que se han planteado han sido las siguientes:

**Hipótesis 1**: Las personas que tienen peor estado de salud general (General Health) presentan una mayor prevalencia de enfermedades cardiovasculares como ataques al corazón o angina de pecho.

**Hipótesis 2**: Existen diferencias significativas en la incidencia de problemas cardíacos en función del sexo y la edad.

**Hipótesis 3**: Los hábitos de vida poco saludables (sedentarismo, tabaquismo, consumo de alcohol, bajo número de horas de sueño) están asociados a un mayor riesgo de enfermedades del corazón.

**Hipótesis 4**: Variables como el IMC y la presencia de diabetes muestran relación con los antecedentes cardiovasculares.

Estas hipótesis servirán como guía durante el EDA y podrán ser confirmadas o descartadas a partir de los datos.

## **Tecnologías utilizadas (librerías, herramientas, lenguajes)**

El dataset utilizado para el análisis de datos se ha obtenido desde la plataforma Kaggle, en formato CSV y se ha empleado GitHub para el control de versiones del proyecto, creando 3 ramas diferentes según los miembros del equipo y trabajando cada uno sobre la suya.

El análisis exploratorio de datos se ha desarrollado utilizando el lenguaje de programación Python, empleando principalmene las librerías NumPy y Pandas para la manipulación y el análisis de los datos, así como Matplotlib y Seaborn para la visualización de los gráficos. Por último, el entorno de trabajo utilizado ha sido Jupyter Notebook, con una estructura del proyecto dentro de una carpeta **src**, gestionando la importación de módulos propios mediante las librerías estándares de Python (**sys** y **pathlib**).

## **Estructura del repositorio**
Para la elaboración del EDA hemos creado 3 ramas diferentes en función de los miembros del equipo. De esta manera, cada miembro ha funcionado de forma independiente pero siempre comunicándose con los otros miembros del equipo.

El repositorio, llamado EDA_Actividades_enfermedades está distribuido de la siguiente manera:

En la rama main encontramos el archivo readME, donde se encuentran las instrucciones de este EDA. También, encontramos el archivo main, donde está todo el código utilizado en el EDA. Asimismo, encontramos la Memoria y la presentación en formato PDF. Por último, creamos una carpeta llamada **src**, donde dentro encontramos 4 carpetas:
- **data**: Observamos los dos dataset utilizados, el extraído de Kaggle ("dataset sucio") y el dataset que hemos creado a partir de la limpieza y la transformación del anterior.
- **img**: Carpeta donde encontramos todos los gráficos utilizados para el análisis.
- **notebooks**: Carpeta donde hemos añadido todos los Jupyter Notebook utilizados para el análisis (Primer Análisis, Limpieza y transformación, Análisis Univariante, Análisis Bivariante y Análisis Multivariante).
- **utils**: Carpeta donde hemos añadido el archivo *bootcampviztools.py*, un módulo con funciones personalizadas.

## **Instrucciones de reproducción**

Para su funcionalidad, el código que se debe ejecutar es el archivo main.ipynb, el cual se encuentra en la rama main del repositorio.
# ***AQUÍ IGUAL EXPLAYARNOS UN POCO MÁS***

## **Principales conclusiones**

# ***PONER AQUÍ LAS PRINCIPALES CONCLUSIONES***

## **Autores**

La distribución del flujo de trabajo ha sido la siguiente:

### *1. Judit:* https://github.com/Juditga97 | https://www.linkedin.com/in/judit-garcia-aguilar/

**Semana 1**

Responsabilidad principal: entender el dataset y limpieza base

- Exploración inicial del dataset
- Diccionario de variables (qué es cada columna)
- Detección de problemas generales
- Tratamiento de valores nulos
- Eliminación de duplicados
- Corrección de tipos de datos

**Semana 1**

Responsabilidad principal: empezar la memoria desde el día 1

Redacción de:
- Introducción y contexto
- Descripción del dataset
- Hipótesis

**Semana 2**

Estadísticas descriptivas: **Análisis univariante**

- Boxplots
- Interpretación de distribuciones
- Redacción de la sección Análisis Univariante de la memoria

**Semana 3**

GitHub y README

- Estructura del repositorio
- README completo:Descripción, Hipótesis, Resultados, Instrucciones de ejecución

### *2. Camila:* https://github.com/cflorenciafiore

**Semana 1**

Responsabilidad principal: dejar el dataset “listo para analizar”

- Revisión de decisiones de limpieza
- Validación de datos raros
- Creación de variables nuevas (si aplica)
- Estandarización de categorías
- Detección y tratamiento de outliers

**Semana 2**

Estadísticas descriptivas: **Análisis bivariante**

- Relaciones entre variables clave
- Gráficos comparativos
- Correlaciones simples
- Redacción de la sección Análisis Bivariante de la memoria

**Semana 3**

Presentación

- Crear diapositivas (Canva / Slides)
- Seleccionar gráficos clave
- Mantener enfoque ejecutivo (sin código)

### *3. Alejandro:* https://github.com/alejandroarbide | https://www.linkedin.com/in/alejandro-arbide-b1672a2a3

**Semana 2**

Estadísticas descriptivas: **Análisis multivariante**

- Heatmaps, interacciones múltiples
- Patrones complejos
- Segmentaciones (si aplica)

**Semana 3**

Hipótesis y conclusiones

- Verificación de hipótesis
- Qué se cumple / qué no se cumple
- Insights clave
- Redacción de conclusiones finales
- Recomendaciones
