# RED NEURONAL CONVOLUCIONAL CLASIFICADORA DE IMÁGENES
El proyecto consiste en la clasificación de imágenes mediante el uso de redes neuronales, la clasificación dependerá de las siguientes 10 categorías:
* Avión
* Auto
* Pájaro
* Gato
* Venado
* Perro
* Rana
* Caballo
* Bote
* Camión

Estas categrías se deben al uso de [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), un dataset con 60 000 imágenes, teniendo 6 000 imágenes por cada categoría anteriormente mencionada. Su uso será esencial para el entrenamiento de la red.

Existirán dos escenarios, los cuales consisten una red convolucional para cada uno, la diferencia radica en al tamaño de imágenes para su entrenamiento, siendo que, para el primer caso, se usan 50 000 imágenes, mientras que para el segundo, únicamente 5 000. Posterior a esto, se probarán las mismas 10 000 imágenes con ambas redes para poder comprobar y comparar el comportamiento de ambas.


## ¿Como usarla?
El archivo llamado **[Proyecto_Final_Simulacion.ipynb](https://github.com/Miguel2900/Simulacion/blob/main/Proyecto_Final_Simulacion.ipynb)** es un notebook de Google Colab, el cual contiene el código necesario para la creación y entrenamiento de la red.

Para ejecutar el código por completo puede usarse el comando **CTRL+F9** o ir ejecutando cada celda mediante el comando **CTRL+ENTER**.

Al acabar de ejecutarse, en la pestaña de archivos se encontrará un archivo llamado **results.xml**, el cual podrá ser descargado, conteniendo la matriz de confusión de ambas redes.
![files](https://user-images.githubusercontent.com/61810656/169936239-1c89305d-d5f7-4004-9d3d-ed476cb306aa.png)
![results](https://user-images.githubusercontent.com/61810656/169936436-4ced2843-67fb-4439-876c-3b274e2ca233.png)

## Recomendaciones
Para un entrenamiento más rápido se recomienda la aceleración de hardware mediante GPU dentro del Colab. Para ello, se debe seleccionar el botón marcado en la siguiente imagen.
![entornoEjecucion](https://user-images.githubusercontent.com/61810656/169934271-18bc31a0-8868-474f-b7e7-39e4934c2b21.png)

Posteriormente, se debe seleccionar el botón de cambiar tipo de entorno de ejecución.
![cambiarTipo](https://user-images.githubusercontent.com/61810656/169934498-d5ce12f1-7524-41cf-933d-ebe524eb0229.png)

Finalmente seleccionar GPU dentro de las opciones.
![select](https://user-images.githubusercontent.com/61810656/169935120-ce684964-4974-459e-b339-40fca37f9496.png)
