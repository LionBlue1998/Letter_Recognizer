### Letter_Recognizer
#### En la práctica que hemos desarrollado se han comparado un conjunto de más de 500 imágenes de vocales (entre conjunto de entrenamiento y validación) clasificadas en 10 clases, cada vocal tanto en mayúscula como en minúscula, y  para ello nos hemos valido del conocimiento adquirido en el curso de Fundamentos de los Sistemas Inteligentes en lo refente a Redes Neuronales. 

#### En primer lugar, ya que contamos con muestras escasas de imagenes en color debemos ponerlas todas entre 0 y 1 por ello dividimos los elementos entre 255 (los números de la gama de colores) ademas con distintas combinaciones dejaremos todos los elementos estándarizados en tamaño de pixeles y mediante la aplicación del zoom y rotaciones generaremos "nuevas" imagenes. 

#### En segundo lugar, hemos configurado la red de entrenamiento que se entrenará para poder clasificar para ello implementamos distintos números de neuronas de entrada y un número de capas ocultas que mejor resultado genere sin llegar a padecer overfitting.  Como neuronas en la capa de salida tenemos 10, tantas como salidas posibles pueda clasificar la red. Así mismo, empleamos las opciones de kernel y max pooling para aumentar el grado de detalle que puede analizar y percibir la neurona. 

##### Tras el entrenamiento y validación, se adjuntan estadísticas sobre el grado de acuraccy, loss, val_acuraccy y val_loss de los mismos.

##### Finalmente, se realiza una pequeña evaluación del entrenamiento mediante predicciones.
