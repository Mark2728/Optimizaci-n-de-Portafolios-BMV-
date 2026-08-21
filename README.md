# Optimización de Portafolios: Mínima Varianza y Tangencia

## Descripción del Proyecto
Este repositorio contiene un algoritmo implementado en Python para la optimización de un portafolio compuesto por 15 acciones del mercado mexicano (BMV). Se utiliza la teoría de selección de cartera de Markowitz para mapear el conjunto factible, calcular la frontera eficiente y determinar las ponderaciones óptimas de inversión.

## Metodología Matemática
El código ejecuta los siguientes procesos analíticos:
* **Estadística Descriptiva:** Cálculo de retornos logarítmicos, rendimientos esperados y matrices de covarianza anualizadas.
* **Portafolio de Mínima Varianza:** Optimización con restricciones (SLSQP) para encontrar los pesos que minimizan la varianza global del portafolio.
* **Cartera de Tangencia:** Maximización del Ratio de Sharpe utilizando una tasa libre de riesgo (Rf) como referencia.
* **Visualización Financiera:** Graficación de la Frontera Eficiente, la Línea del Mercado de Capitales (CML) y la distribución porcentual de los activos.

## Herramientas y Tecnologías
* **Python** (Lógica base del algoritmo).
* **SciPy (`scipy.optimize.minimize`)** (Resolución matemática de los problemas de optimización con restricciones de no negatividad).
* **Pandas & NumPy** (Manipulación de series de tiempo financieras y cálculo matricial).
* **Matplotlib** (Renderizado de los gráficos financieros).
