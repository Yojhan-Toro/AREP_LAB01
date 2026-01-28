# AREP_LAB01

## Author
Yojhan Toro Rivera – Escuela Colombiana de Ingeniería Julio Garavito


# Stellar Luminosity Regression
Este proyecto implementa modelos de regresión lineal y polinómica desde primeros principios para modelar la relación entre la masa estelar, la temperatura y la luminosidad. No se utilizan librerías de machine learning, únicamente NumPy y Matplotlib.

## Repository Structure


├── README.md

├── 01_part1_linreg_1feature.ipynb

└── 02_part2_polyreg.ipynb

## Requirements

- Python
- NumPy
- Matplotlib

## Notebooks

### 01_part1_linreg_1feature.ipynb
Implementa regresión lineal con una sola variable (masa estelar) utilizando descenso por gradiente, incluyendo visualización de la superficie de costo y análisis de convergencia.

### 02_part2_polyreg.ipynb
Implementa regresión polinómica con múltiples características (masa, temperatura, términos no lineales e interacción), y compara distintos modelos.

## AWS SageMaker Execution Evidence

Los notebooks fueron subidos a AWS SageMaker Studio mediante carga directa desde el entorno local. Ambos notebooks fueron ejecutados completamente sin errores dentro del entorno de SageMaker.

### Screenshots

Prueba de mauina virtual corriendo 

![](images/0.png)

Pruebas de 01_part1_linreg_1feature.ipynb corriendo sin problemas 

![](images/1.png)
![](images/2.png)
![](images/3.png)
![](images/4.png)
![](images/5.png)

Pruebas de 02_part2_polyreg.ipynb corriendo sin problemas 

![](images/2_1.png)
![](images/2_2.png)
![](images/2_3.png)
![](images/2_4.png)
![](images/2_5.png)
![](images/2_6.png)






