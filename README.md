# Simulación de Procesos Gaussianos (Gaussian Processes)

Este repositorio contiene un cuaderno interactivo de Google Colab diseñado para explorar, entender y visualizar la simulación de **Procesos Gaussianos (GPs)** utilizando Python. 

A lo largo del cuaderno, se construyen los conceptos matemáticos desde la base, comenzando con distribuciones normales multivariantes, hasta llegar a la implementación de diferentes funciones de covarianza (kernels) y un enfoque de Programación Orientada a Objetos (POO) para generalizar el código.

## 📋 Contenido del Cuaderno

El cuaderno está estructurado en 5 secciones principales:

1. **Muestras de una Normal Multivariante:**
   * Introducción teórica y práctica a la simulación de distribuciones normales en múltiples dimensiones.
   * Visualizaciones en 3D de muestras generadas con diferentes matrices de covarianza.

2. **Simulación de un GP con Kernel RBF (Radial Basis Function):**
   * Implementación matemática del kernel RBF.
   * Visualización del efecto que tienen los parámetros de **varianza** (`sigma_sq`) y **escala de longitud** (`lengthscale`).

3. **Simulación de un GP con Kernel Periódico:**
   * Implementación de un kernel diseñado para modelar patrones repetitivos.
   * Análisis gráfico variando el parámetro de **periodo** (`p`) y **varianza** (`sigma`).

4. **Simulación de un GP con Kernel DPK (Polinómico):**
   * Creación de un kernel basado en funciones base polinómicas (hasta grado m).
   * Resolución de problemas numéricos (matrices no semidefinidas positivas) mediante la adición de ruido o *jitter*.
   * Generación de trayectorias para polinomios de grados m=1, m=2 y m=3.

5. **Refactorización con Programación Orientada a Objetos (POO):**

## 🛠️ Tecnologías y Librerías Utilizadas

El código está escrito en **Python 3** y utiliza las siguientes librerías:

* `numpy`: Para el cálculo matricial y la generación de números aleatorios (muestreo multivariante).
* `matplotlib`: Para la generación de gráficos en 2D y 3D.
* `math`: Para operaciones matemáticas estándar.
