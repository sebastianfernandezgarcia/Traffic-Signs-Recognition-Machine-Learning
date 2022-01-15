# Traffic Signs Recognition ⚠️🚦

### Introduction 📄
Development of a neural network capable of recognizing nine different danger warning traffic signs.
1. **Sign P-50.** Other dangers.
2. **Signal P-14b.** Dangerous curves to the left.
3. **Sign P-20.** Pedestrians.
4. **Sign P-19.** Slippery pavement.
5. **Sign P-18.** Works.
6. **Signal P-3.** Traffic lights.
7. **Sign P-15a.** Highlight.
8. **Sign P-1.** Intersection with priority.
9. **Signal P-24.** Passage of animals in freedom.


<img width="632" alt="Screenshot 2022-01-09 at 20 48 42" src="https://user-images.githubusercontent.com/56322714/148700240-8a6a1fdb-bbd6-40f1-be64-5724da7ee35f.png">

### Datasets 📁
The images, both for the training set and for the validation set, have been extracted from several datasets, the most notable being the GTSRB (German Traffic Sign Recognition Benchmark) dataset: https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb -german-traffic-sign

In addition, self-made images have been added.

  * [Training data set](https://drive.google.com/drive/folders/1_C1JM9Ik90DKWz_xu5hwwG6_2QfEnBHq?usp=sharing)
  * [Validation Data Set](https://drive.google.com/drive/folders/13ChyxuCHRbgvNRJ5eX7tHc1TX5VrKDG5?usp=sharing)

### Data Augmentation
Data augmentation has been performed on the training set, to obtain new images from those already present. To do this, we have used various parameters such as rotation angle, cut angle, among others, in the `ImageDataGenerator` class

### Additional Information
All the implementation details are in the memory that we have made, which can be read from the following link: [Proyect Memory](https://github.com/sebastianfernandezgarcia/Traffic-Signs-Recognition-Machine-Learning/blob/main/Project%20Memory%20-%5BTraffic%20Sings%20Recognition%5D%20-%20Nahima%20%26%20Sebastian.pdf)

In this document, the hyperparameters that have been used are detailed, as well as those that we have tested.
Also, the concept of `Categorical Cross Entropy` is explained, and how this loss function works.

### Authors ✒️
  * **Sebastian Fernandez Garcia** - [@sebastianfernandezgarcia](https://github.com/sebastianfernandezgarcia)
  * **Nahima Ortega Rodríguez** - [@nahimaort](https://github.com/nahimaort)
 
 *Base code provided by [Cayetano Guerra Artal](https://cayetanoguerra.github.io/ia/)*
