# LFOA_individual_equipo
Trabajo individual y en equipo del modulo Algebra lineal y optimizacion

# Enlaces del proyecto por equipo
## Equipo 15

- **Luis Federico Olivarria Avila**
- **Martin Eduardo Preciado Orozco**
- **Mario Estrada Ferreira**

## Predicción de Errores en el Desarrollo de Software a partir de una Red Neuronal

El trabajo en equipo consistió en la realización del proyecto para entrenar y probar una red neuronal hecho con tensorflow.

## Arquitectura Red Neuronal
Feedforward básica con dos capas ocultas con 10 neuronas cada una Forward Propagation.

## Funciones de Activación
Funcion ReLU para las capas ocultas Funcion sigmoide para la capa de salida.

## Algoritmo y funciones de optimizacion y error
Funcion binary_crossentropy como funcion de perdida, esto porque maneja mejor los problemas de clasificacion binaria. Algoritmo de optimizacion Adam.

## Metricas
Presicion Recall F1-score

## Variables
Características de entrada (X):

loc: Recuento numérico de líneas de código de McCabe.
v(g): Complejidad ciclomática de McCabe.
ev(g): Complejidad esencial de McCabe.
iv(g): Complejidad de diseño de McCabe.
n: Total de operadores y operandos de Halstead.
v: Volumen de Halstead.
l: Longitud del programa de Halstead.
d: Dificultad de Halstead.
i: Inteligencia de Halstead.
e: Esfuerzo de Halstead.
b: Parámetro de Halstead.
t: Estimador de tiempo de Halstead.
lOCode: Recuento de líneas de código de Halstead.
lOComment: Recuento de líneas de comentarios de Halstead.
lOBlank: Recuento de líneas en blanco de Halstead.
lOCodeAndComment: Recuento de líneas de código y comentarios de Halstead.
Etiqueta objetivo (y):

defects: Variable binaria que indica si el módulo tiene o no defectos reportados (false: no tiene defectos, true: tiene defectos).

Se puede observar que existen dos enlaces para distintos entrenamientos y pruebas con distintos algoritmos, solo para ver la viabilidad de los datos y comparar resultados.

El archivo utilizado para la estadística y los distintas pruebas con su entrenamiento de la red neuronal está en el repositorio y es el llamado jm1.csv el cual fue obtenido desde [Base Kaggle](https://www.kaggle.com/datasets/semustafacevik/software-defect-prediction)

## Enlace para la base estadística previa del archivo del dataset con el que trabajamos para el entrenamiento y prueba de la red neuronal:

[Estadística](https://colab.research.google.com/drive/1LHfGFd3TAA6lHdMJVbxNWJbwHNZgE4zY?usp=sharing)

## Enlace donde se ubica los resultados del entrenamiento de la red neuronal, por medio del modelo adam:

[Resultados red neuronal](https://www.kaggle.com/code/marioef/red-neuronal-prediccion-errores-dev-software)

##Enlace donde se ubica los resultados del entrenamiento de la red neuronal, por medio del modelo El descenso de gradiente estocástico:

[Resultados entrenamiento](https://colab.research.google.com/drive/1nqYtgMWJCFrsNShW0i0ZkOO8llPvsJuh?usp=sharing)

## Enlace de la presentación del proyecto:

[Presentación en gamma](https://gamma.app/docs/PrediccionErroresDevSoftwareRedNeuronal-hbkuv1bsf1si3kf?mode=doc)
[Presentación PDF](https://drive.google.com/file/d/1d58xwdQxwgYME6TmrCwQGux472_R9fak/view?usp=sharing)
