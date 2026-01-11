# Predicción de Emisiones de CO2 mediante Regresión Lineal

## 📋 Descripción del Proyecto

Este proyecto implementa un **algoritmo de regresión lineal** para predecir las emisiones de CO2 de vehículos basándose en características técnicas como el tamaño del motor, el consumo de combustible y el tamaño del vehículo. La regresión lineal es una técnica de aprendizaje automático supervisado que permite modelar la relación entre variables independientes (características del vehículo) y una variable dependiente (emisiones de CO2).

## 🎯 Objetivo

Desarrollar un modelo predictivo que permita:
- Estimar las emisiones de CO2 de un vehículo basándose en sus características técnicas
- Identificar qué variables tienen mayor impacto en las emisiones
- Proporcionar una herramienta para la toma de decisiones ambientales y de eficiencia energética

## 🔬 ¿Qué es la Regresión Lineal?

La **regresión lineal** es un método estadístico que modela la relación entre una o más variables independientes (predictores) y una variable dependiente (objetivo) mediante una ecuación lineal

### Ventajas de la Regresión Lineal
- ✅ Fácil interpretación de resultados
- ✅ Computacionalmente eficiente
- ✅ Requiere menos datos que modelos complejos
- ✅ Permite identificar relaciones lineales entre variables

## 📊 Variables del Modelo

### Variables Independientes (Predictores)
1. **Tamaño del Motor (Engine Size)**
   - Medida en litros (L)
   - Relación directa: motores más grandes tienden a consumir más combustible
   - Ejemplo: 1.5L, 2.0L, 3.5L

2. **Consumo de Combustible (Fuel Consumption)**
   - Medida en litros por 100 kilómetros (L/100km)
   - Mayor consumo implica mayores emisiones
   - Puede incluir consumo urbano, carretera o combinado

3. **Tamaño del Vehículo (Vehicle Size)**
   - Categoría o dimensiones del vehículo
   - Puede ser: compacto, mediano, grande, SUV
   - Vehículos más grandes generalmente tienen mayor peso y resistencia al aire

### Variable Dependiente (Objetivo)
- **Emisiones de CO2**: Cantidad de dióxido de carbono emitido, medida en gramos por kilómetro (g/km)

## 🔄 Relaciones Entre Variables

### Tamaño del Motor → Emisiones de CO2
- **Relación**: Positiva y directa
- **Explicación**: Motores más grandes requieren mayor cantidad de combustible para funcionar, lo que incrementa la combustión y, por ende, las emisiones de CO2

### Consumo de Combustible → Emisiones de CO2
- **Relación**: Positiva y fuerte
- **Explicación**: A mayor consumo de combustible, mayor es la cantidad de hidrocarburos quemados, generando más CO2 como producto de la combustión

### Tamaño del Vehículo → Emisiones de CO2
- **Relación**: Positiva e indirecta
- **Explicación**: Vehículos más grandes tienen mayor peso y resistencia aerodinámica, requiriendo más energía (combustible) para desplazarse

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**: Lenguaje de programación principal
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas y matriciales
- **Scikit-learn**: Implementación del algoritmo de regresión lineal
- **Matplotlib/Seaborn**: Visualización de datos y resultados
- **Jupyter Notebook**: Entorno de desarrollo interactivo (opcional)
