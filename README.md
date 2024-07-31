Este repositorio contiene dos archivos de codigo (.ipynb y .py) para ejecutar en el ambiente Google Colab se recomienda usar el archivo Prueba_tic_7.ipynb
# Resumen trabajo-de-integración-curricular
Para este trabajo de integración curricular se ha escogido como tema el progreso de los pacientes de Alzheimer, para el desarrollo de un modelo de aprendizaje no supervisado, mismo que se realizó a partir de un conjunto de datos.
El desarrollo del modelo, se trabajó en el ambiente de trabajo de *Google Colab*, mismo que evidenció la necesidad de utilizar un tratamiento de valores faltantes sobre los datos, para poder realizar la posterior ejecución de los algoritmos correspondientes.
Luego se realizó la correlación entre las variables, para poder eliminar las que causan ruido dentro del análisis. A partir de esto se escalaron los datos, para realizar el análisis de componentes principales (PCA) y reducir la dimensionalidad del conjunto de datos y así poder observar la separabilidad de los datos.
La aplicación de la clusterización permitió asignar a los pacientes de Alzheimer al grupo de estado al que pertenecen, esto es al de demencia, no demencia y en transición o converted.
Los algoritmos de aprendizaje no supervisado no son susceptibles de medición en porcentaje de certeza, los resultados obtenidos a partir de este trabajo, pueden tomarse como base para algoritmos de aprendizaje supervisado para permitir la predicción del avance o no de la enfermedad hacia una demencia diagnosticada.

