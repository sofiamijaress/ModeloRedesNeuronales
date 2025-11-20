# ModeloRedesNeuronales

En este proyecto se desarrolla un sistema para clasificar numeros escritos a mano utilizando una Red Neuronal Convolucional (CNN) entrenada desde cero, y se extiende hacia un OCR (Optical Character Recognition) capaz de reconocer múltiples números en imágenes y en tiempo real mediante la cámara de la computadora.

Entrené 6 modelos distintos para comparar arquitecturas y ajustar hiperparámetros:
* Cambios en número de filtros (modelos más simples y más complejos)
* Uso de Batch Normalization
* Modelos más profundos con GlobalAveragePooling
* Convoluciones con kernels 5×5
* Regularización L2
* Data Augmentation
* Optimización con Adam y RMSprop


**Informacion del conjunto de datos**

* Imágenes en escala de grises 280×280, un canal
* Valores 0–255 normalizados a [0,1]
* 10 carpetas (0–9), aproximadamente 9100+ imágenes.


Archivos incluidos:
* [Reporte en formato ipynb (Google COLAB)](P_P3_645700.ipynb)

* [Reporte en formato html (Google COLAB)](P_P3_645700.html)

* [Reporte en formato ipynb (Jupyter Notebooks)]()

* [Reporte en formato html (Jupyter Notebooks)]()
  
