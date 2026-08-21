# Optimización de Portafolios: Mínima Varianza y Tangencia

## Descripción del Proyecto
Este repositorio contiene un algoritmo implementado en Python para la optimización de un portafolio compuesto por 15 acciones del mercado mexicano (BMV)[cite: 5]. Se utiliza la teoría de selección de cartera de Markowitz para mapear el conjunto factible, calcular la frontera eficiente y determinar las ponderaciones óptimas de inversión[cite: 5].

## Metodología Matemática
El código ejecuta los siguientes procesos analíticos:
* **Estadística Descriptiva:** Cálculo de retornos logarítmicos, rendimientos esperados y matrices de covarianza anualizadas[cite: 5].
* **Portafolio de Mínima Varianza:** Optimización con restricciones (SLSQP) para encontrar los pesos que minimizan la varianza global del portafolio[cite: 5].
* **Cartera de Tangencia:** Maximización del Ratio de Sharpe utilizando una tasa libre de riesgo (Rf) como referencia[cite: 5].
* **Visualización Financiera:** Graficación de la Frontera Eficiente, la Línea del Mercado de Capitales (CML) y la distribución porcentual de los activos[cite: 5].

## Herramientas y Tecnologías
* **Python** (Lógica base del algoritmo).
* **SciPy (`scipy.optimize.minimize`)** (Resolución matemática de los problemas de optimización con restricciones de no negatividad)[cite: 5].
* **Pandas & NumPy** (Manipulación de series de tiempo financieras y cálculo matricial)[cite: 5].
* **Matplotlib** (Renderizado de los gráficos financieros)[cite: 5].
