# Sistema de Recomendación de Compatibilidad de Inquilinos

## Descripción del Proyecto
Este proyecto desarrolla una aplicación interactiva con Streamlit para facilitar la búsqueda y recomendación de inquilinos compatibles, basándose en un análisis detallado de hábitos personales, preferencias de estilo de vida y compatibilidad de personalidad. Emplea técnicas de procesamiento de datos y algoritmos de machine learning para analizar un dataset exhaustivo de inquilinos, proporcionando insights precisos y recomendaciones para mejorar el proceso de selección de inquilinos en propiedades residenciales.

### Tecnologías y Técnicas Empleadas
El proyecto integra diversas herramientas y técnicas de data science y machine learning, incluyendo:

- **Streamlit**: Para crear una interfaz de usuario interactiva y amigable que permite a los usuarios interactuar fácilmente con el modelo de recomendación.
- **Pandas y Numpy**: Utilizados para la manipulación y análisis de datos, facilitando la gestión del dataset de inquilinos y la preparación de datos para el modelado.
- **Scikit-learn**: Emplea herramientas de preprocesamiento como `OneHotEncoder` para convertir variables categóricas en un formato adecuado para los algoritmos de machine learning, y se utiliza para desarrollar modelos de clasificación o clustering que podrían estar en el corazón del sistema de recomendación.
- **Matplotlib y Seaborn**: Para la visualización de datos, proporcionando gráficos y tablas que permiten interpretar la compatibilidad entre inquilinos y otras métricas relevantes de manera intuitiva.

### Análisis de Compatibilidad
El núcleo del sistema de recomendación se basa en algoritmos avanzados de machine learning para evaluar la compatibilidad entre inquilinos potenciales. Este análisis podría incluir:

- **Técnicas de Clustering**: Para agrupar inquilinos con características y preferencias similares, facilitando la identificación de matches compatibles.
- **Análisis de Componentes Principales (PCA)**: Para reducir la dimensionalidad de los datos y mejorar la eficiencia de los algoritmos de clustering o clasificación.
- **Sistemas de Recomendación Basados en Filtros Colaborativos o Contenido**: Personalizando las recomendaciones basadas en similitudes entre inquilinos y sus preferencias.

![ProcessFlowStreamlitApplicationt](./docs/ProcessFlowStreamlitApplication(7).png)

### Interfaz Intuitiva con Streamlit
La aplicación utiliza Streamlit para proporcionar una experiencia de usuario fluida y dinámica, donde los usuarios pueden:

- Ingresar preferencias y requisitos de inquilinos.
- Visualizar recomendaciones de inquilinos compatibles.
- Explorar análisis detallados y visualizaciones de compatibilidad.
## Estructura del Proyecto

El proyecto de **Sistema de Recomendación de Compatibilidad de Inquilinos** está organizado en varios archivos y directorios clave que trabajan conjuntamente para proporcionar una solución completa de análisis y recomendación basada en datos de inquilinos. Aquí se describe la función y el propósito de cada archivo importante dentro de la estructura del proyecto:

- **`app.py`**: Este es el script principal de la aplicación de Streamlit. Define la interfaz de usuario (UI) y maneja la interacción del usuario con la aplicación. Aquí se configuran las visualizaciones, se capturan las entradas del usuario y se muestran los resultados de las recomendaciones de compatibilidad entre inquilinos.

- **`ayudantes.py`**: Contiene funciones auxiliares y de utilidad que son usadas a lo largo del proyecto. Esto incluye funciones para procesamiento de datos, generación de visualizaciones específicas, y cualquier otra operación recurrente necesaria para apoyar la lógica principal del sistema de recomendación.

- **`logica.py`**: Implementa la lógica de negocio central del proyecto. Aquí se encuentran los algoritmos y métodos de machine learning utilizados para analizar el dataset de inquilinos, calcular las métricas de compatibilidad y generar las recomendaciones. Este archivo es crucial para el funcionamiento del sistema de recomendación.

- **`dataset_inquilinos.csv`**: Es el conjunto de datos principal utilizado por el proyecto. Contiene información detallada sobre los inquilinos, incluyendo sus preferencias personales, hábitos, y otros atributos relevantes que son utilizados para evaluar la compatibilidad entre ellos.

- **`metadatos.xlsx`**: Proporciona información adicional y metadatos sobre el dataset de inquilinos. Este archivo puede incluir descripciones de las columnas, detalles sobre la recopilación de datos, y cualquier otra información de contexto que ayude a entender y trabajar con el dataset.

### Organización del Código

El código está estructurado de manera modular para promover la reutilización y facilitar el mantenimiento. Cada archivo `.py` se enfoca en aspectos específicos del proyecto, desde la interfaz de usuario hasta la lógica de procesamiento de datos y las operaciones de backend. Esta organización modular permite que el proyecto sea escalable y fácil de actualizar o modificar según sea necesario.

### Visualizaciones y Análisis de Datos

Las visualizaciones son generadas utilizando **Matplotlib** y **Seaborn**, integradas directamente en la interfaz de Streamlit a través de `app.py`. Estas visualizaciones son fundamentales para presentar los resultados de las recomendaciones de compatibilidad de manera intuitiva y accesible para los usuarios.

### Procesamiento y Análisis de Datos

El preprocesamiento y análisis de datos se llevan a cabo utilizando **Pandas**, **Numpy**, y **Scikit-learn**, aprovechando sus amplias capacidades para manipular datasets complejos y aplicar técnicas de machine learning.
