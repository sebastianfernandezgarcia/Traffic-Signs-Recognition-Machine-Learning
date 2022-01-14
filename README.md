# Traffic Signs Recognition ⚠️🚦
## Fundamentos de los Sistemas Inteligentes 

### Introducción 📄
Desarrollo de una red neuronal capaz de reconocer nueve señales de tráfico de tipo advertencia de peligro distintas.
1.	**Señal P-50.** Otros peligros.
2.	**Señal P-14b.** Curvas peligrosas hacia la izquierda.
3.	**Señal P-20.** Peatones.
4.	**Señal P-19.** Pavimento deslizante.
5.	**Señal P-18.** Obras.
6.	**Señal P-3.** Semáforos.
7.	**Señal P-15a.** Resalto.
8.	**Señal P-1.** Intersección con prioridad.
9.	**Señal P-24.** Paso de animales en libertad.


<img width="632" alt="Captura de pantalla 2022-01-09 a las 20 48 42" src="https://user-images.githubusercontent.com/56322714/148700240-8a6a1fdb-bbd6-40f1-be64-5724da7ee35f.png">

### Datasets 📁
Las imágenes, tanto para el conjunto de entrenamiento como para el de validación, han sido extraídas de varios dataset, siendo el más destacable el dataset GTSRB (German Traffic Sign Recognition Benchmark): https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

Además, se han añadido imágenes de elaboración propia.

  * [Conjunto de datos de entrenamiento](https://drive.google.com/drive/folders/1_C1JM9Ik90DKWz_xu5hwwG6_2QfEnBHq?usp=sharing)
  * [Conjunto de datos de validación](https://drive.google.com/drive/folders/13ChyxuCHRbgvNRJ5eX7tHc1TX5VrKDG5?usp=sharing)

### Data Augmentation 
Se ha realizado aumento de datos sobre el conjunto de entrenamiento, para obtener imágenes nuevas a partir de las ya presentes. Para ello, hemos utilizado diversos parámetros como ángulo de rotación, ángulo de corte, entre otros, en la clase `ImageDataGenerator`

### Información adicional
Todos los detalles de implementación se encuentran en la memoria que hemos realizado, que se puede leer desde el siguiente enlace: https://github.com/nahimaort/Traffic-Signs-Recognition/blob/main/Memoria.pdf
En este documento, se detallan los hiperparámetros que se han empleado, así como aquellos que hemos probado.
Además, se explica el concepto de `Categorical Cross Entropy`, y cómo funciona esta función de pérdida

### Autores ✒️
  * **Sebastián Fernández García** - [@sebastianfernandezgarcia](https://github.com/sebastianfernandezgarcia)
  * **Nahima Ortega Rodríguez** - [@nahimaort](https://github.com/nahimaort)
 
 *Código base proporcionado por [Cayetano Guerra Artal](https://cayetanoguerra.github.io/ia/)*
 
 
