# Tarea3-Canavera-Martin

# ☕Sloshing in coffee as a pumped pendulum🫖
<span style="font-size: 24px;"></span>
_____________________________
Este proyecto tiene como objetivo analizar y evaluar un modelo matemático no lineal que describe la dinámica del sloshing en un contenedor cilíndrico parcialmente lleno, utilizando ecuaciones diferenciales ordinarias. Se aborda el problema desde la perspectiva del péndulo plano no lineal, con excitaciones paramétricas y directas.

Se implementaron diferentes métodos numéricos para resolver el sistema de ecuaciones diferenciales utilizando Python, específicamente con la función solve_ivp. Además, se realizaron experimentos numéricos variando parámetros clave y se analizaron los efectos en el comportamiento del sistema.

![Sloshing en café](https://cdn.pixabay.com/photo/2017/01/12/02/34/coffee-1973549_1280.jpg)




# ⚙️Requerimientos del sistema⚙️
<span style="font-size: 24px;"></span>
_____________________________

* **NVIDIA A100 GPU**
* **Descomprimir los archivos de test_data y train_data**
* **Descomprimir el conjunto de datos que se encuentra en el Release debido al tamaño de este**

A continuación se presenta la lista de módulos necesarios y sus propósitos en este proyecto:

* **numpy**: Para operaciones matemáticas y manipulación eficiente de matrices y vectores.
* **matplotlib**: Para visualización de datos y creación de animaciones.
* **pandas**: Para manipulación y análisis de datos estructurados.
* **scikit-learn**:
  - **LinearRegression**: Utilizado para tareas auxiliares de regresión.
  - **train_test_split**, **cross_val_score**: Para la evaluación de modelos.
  - **r2_score**, **mean_squared_error**: Para medir el desempeño del modelo.
* **seaborn**: Para generar gráficos estadísticos más elaborados y estilizados.
* **scipy**: Para realizar pruebas estadísticas y cálculos científicos.

### Instalación de Dependencias

Para instalar las dependencias, puedes usar el siguiente comando:

**pip install numpy matplotlib pandas scikit-learn seaborn scipy**

# 👨‍💻Configuración de ejecución👩‍💻
<span style="font-size: 24px;"></span>
_____________________________
Para ejecutar el proyecto tiene 2 alternativas: 
1. **Subir el conjunto de datos a su cuenta de Google Drive y configurar la ruta de importación de este en el colab o subir el conjunto de datos al colab.**
2. **Ejecutarlo en local, pero primero configurando la ruta de importación del conjunto de datos.**

![](https://i0.wp.com/mathwithbaddrawings.com/wp-content/uploads/2017/05/20161031143242_00005-e1495635818490.jpg?resize=1100%2C606&ssl=1)
