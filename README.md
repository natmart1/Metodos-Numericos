# Métodos Numéricos

Trabajos de la asignatura de Métodos Numéricos, desarrollados en Google Colab con Python (numpy, sympy, scipy, pandas, matplotlib).

**Autora:** Natalia Isabel Martinez

## Contenido

| # | Notebook | Tema |
|---|---|---|
| 1a | [`01a_Raices_Biseccion_Newton_Regla_Falsa_y_Muller.ipynb`](01a_Raices_Biseccion_Newton_Regla_Falsa_y_Muller.ipynb) [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/natmart1/Metodos-Numericos/blob/main/01a_Raices_Biseccion_Newton_Regla_Falsa_y_Muller.ipynb) | Búsqueda de raíces: exactitud y precisión, bisección (con gráfica de las iteraciones y con tolerancia elegida por el usuario), Newton-Raphson, regla falsa, punto fijo y método de Müller. |
| 1b | [`01b_Raices_Punto_Fijo_y_Extremos.ipynb`](01b_Raices_Punto_Fijo_y_Extremos.ipynb) [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/natmart1/Metodos-Numericos/blob/main/01b_Raices_Punto_Fijo_y_Extremos.ipynb) | Otra versión del notebook anterior, con la iteración de punto fijo graficada, el cálculo de máximos y mínimos de una función y la búsqueda de intersecciones de dos curvas, h(x) = g(x), como raíces de f(x) = h(x) − g(x). |
| 2 | [`02_Interpolacion_y_Regresion.ipynb`](02_Interpolacion_y_Regresion.ipynb) [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/natmart1/Metodos-Numericos/blob/main/02_Interpolacion_y_Regresion.ipynb) | Interpolación polinómica: polinomios de Newton con diferencias divididas (incluida la interpolación inversa), polinomio de Lagrange y polinomios de Hermite. Regresión lineal por mínimos cuadrados con error cuadrático medio, varianza y desviación estándar del error. |
| 3 | [`03_Splines.ipynb`](03_Splines.ipynb) [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/natmart1/Metodos-Numericos/blob/main/03_Splines.ipynb) | Interpolación por splines lineales, cuadráticos y cúbicos, implementados a mano y comparados con `scipy.interpolate.CubicSpline`. |

## Cómo ejecutarlos

Ábrelos con el botón **Abrir en Colab**. Varias celdas piden los datos (funciones, intervalos o puntos `x`, `y`) por teclado con `input()`.
