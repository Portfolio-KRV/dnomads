# Dnomads
Desarrollado en el curso de Aprendizaje Automático por: Fernanda Avendaño, Diego Quezada y Kevin Reyes.
## Objetivos
- Predecir el costo de paquetes de viaje utilizando modelos lineales (excluyente).
- Identificar y corregir el incumplimiento de requisitos teóricos de los modelos lineales.
- Aplicar ingeniería de características utilizando información interna y externa al conjunto de datos, además de aplicar métodos del procesamiento del lenguaje natural.

## Descripción
Modelo lineal para predecir el costo de paquetes de viaje para nómades digitales.

## Conclusiones
- Al trabajar con modelos simples se experimenta la importancia de la ingeniería de características para obtener buenos resultados ya que, la diferencia de rendimiento entre distintos modelos lineales es ínfima, por lo que, las grandes mejoras en el desempeño están totalmente correlacionadas con los atributos que se incluyen en el modelo.
- El hecho de eliminar variables para evitar la multicolinearidad entre las variables independientes no siempre provoca una mejora en el desempeño de la regresión lineal.
- A medida que la cantidad de atributos aumenta, el impacto del regularizador en el desempeño de los modelos es más significativo.
- Al realizar un proceso de creación de nuevas características se debe tener siempre en cuenta que se podría estar introduciendo multicolinealidad al modelo, por ejemplo, cuando aplicamos one-hot-encoding, introducimos directamente una multicolinealidad al modelo, la que se puede resolver eliminando una de las variables del one-hot-encoding.

## Stack de tecnologías
- Spacy.
- Scipy.
- Pandas.
- Numpy.
- Matplotlib.
- Seaborn.
- Scikit-learn.