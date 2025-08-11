# 🏪 RetailPlus Sales Prediction - Machine Learning Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-green.svg)](https://scikit-learn.org)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-purple.svg)](https://pandas.pydata.org)

## 📖 Descripción del Proyecto

Este proyecto desarrolla un **modelo predictivo de machine learning** para predecir el monto de facturación (Monto USD) de RetailPlus, una empresa líder del sector minorista peruano. El modelo ayuda a optimizar la planificación de ventas, gestión de inventario y estrategias comerciales.

### 🎯 Objetivo Principal
Predecir el monto de facturación utilizando variables como características del cliente, producto, condiciones de pago y ubicación geográfica, logrando un **R² de 0.8965** con Random Forest.

## 🏢 Contexto de Negocio

**RetailPlus** es un ecosistema comercial peruano que opera desde hace más de 20 años, atendiendo desde pequeñas bodegas hasta grandes industrias en sectores como:
- 🍕 Alimentos y restaurantes
- 🧪 Industria química  
- 👕 Sector textil
- 💊 Laboratorios farmacéuticos
- 📦 Distribuidores mayoristas

### Problemática
- Excesos de inventario y quiebres de stock
- Decisiones de precios subóptimas
- Gestión compleja de crédito y cobranza

## 📊 Resultados Principales

| Modelo | R² Score | MSE | Performance |
|--------|----------|-----|-------------|
| Linear Regression | 0.8469 | 0.2034 | ⭐⭐⭐ |
| Ridge Regression | 0.8469 | 0.2034 | ⭐⭐⭐ |
| Lasso Regression | 0.8469 | 0.2034 | ⭐⭐⭐ |
| ElasticNet | 0.8469 | 0.2034 | ⭐⭐⭐ |
| Decision Tree | 0.8958 | - | ⭐⭐⭐⭐ |
| **Random Forest** | **0.8965** | - | ⭐⭐⭐⭐⭐ |

> 🏆 **Random Forest** fue seleccionado como el mejor modelo por su superior capacidad predictiva y robustez.

## 🔧 Tecnologías Utilizadas

```python
# Librerías principales
pandas==1.3.3
numpy==1.21.2  
scikit-learn==1.0.2
matplotlib==3.4.3
seaborn==0.11.2
jupyter==1.0.0
