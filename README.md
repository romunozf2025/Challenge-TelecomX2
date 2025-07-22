# Análisis de Cancelación de Clientes - Telecom X2

Repositorio para el desarrollo completo de un proyecto de análisis y modelado para identificar los factores que influyen en la cancelación de clientes en la empresa **Telecom X**.

### 1. **Análisis Exploratorio**
- Evaluación por categorías como contrato, método de pago, etc.
- Visualización y análisis de variables numéricas.
- Identificación de patrones y comportamiento.

### 2. **Modelado Predictivo**
Se entrenaron tres modelos para predecir la cancelación de clientes:
- **Dummy Classifier:** Usado como línea base (accuracy: 0.50).
- **Decision Tree Classifier:** Árbol de decisión básico (accuracy: 0.80).
- **Random Forest Classifier:** Mejor desempeño general (accuracy: 0.86).

### 3. **Análisis de Variables **
Se utilizó la importancia de variables en los modelos para identificar los factores más influyentes en el churn, confirmando hallazgos del análisis exploratorio:
- Tipo de contrato.
- Tiempo como cliente.
- Método de pago.
- Tipo de servicio de internet
- Servicios adicionales como `TechSupport` y `OnlineSecurity`

### 4. **Estrategias de Retención**
Basado en los resultados, se plantearon acciones para reducir el churn:
- Fortalecer la incorporacion de nuevos clientes.
- Promover contratos a largo plazo.
- Incentivar métodos de pago más estables.
- Detectar y actuar sobre clientes de bajo compromiso y dar opciones atractivas para que se sientan comodos para comprometerse con la empresa.

## Conclusión

El proyecto combina análisis estadístico de interpretación de resultados para entregar una solución aplicable a problemas reales de retención de clientes. El uso de modelos permite no solo predecir cancelaciones, sino también entender qué variables influyen más en esa decisión.

## ⚙️ Tecnologías Utilizadas

- Python.
- Pandas, Numpy.

## Contacto

Desarrollado por **Rodrigo Alfredo Muñoz Fuentealba**  




