# 🚢 Análisis del Titanic - Predicción de Supervivencia

## 📋 ¿Qué hace este proyecto?

Este código analiza los datos del famoso naufragio del Titanic para **predecir quién sobrevivió y quién no**. Es perfecto para aprender machine learning porque:

- ✅ Es fácil de entender (sabemos qué pasó en el Titanic)
- ✅ Tiene datos interesantes (edad, sexo, clase, etc.)
- ✅ Es un problema de clasificación (sobrevivió: SÍ o NO)

## 🎯 Objetivo

**Pregunta principal:** *"Dado un pasajero con ciertas características, ¿sobrevivió al naufragio?"*

Probamos 5 algoritmos diferentes para ver cuál es el mejor prediciendo esto.

## 📊 ¿Qué datos usamos?

Los datos incluyen información sobre cada pasajero:

| Columna | Descripción | Ejemplo |
|---------|-------------|---------|
| `survived` | ¿Sobrevivió? (0=No, 1=Sí) | 1 |
| `age` | Edad del pasajero | 29 |
| `sex` | Sexo | male/female |
| `class` | Clase del boleto | First/Second/Third |
| `fare` | Precio del boleto | 7.25 |
| `embarked` | Puerto de embarque | C/Q/S |
| `alone` | ¿Viajaba solo? | True/False |
| `who` | Categoría de persona | man/woman/child |

## 🤖 ¿Qué algoritmos probamos?

1. **Regresión Logística** - Como una ecuación matemática
2. **KNN** - "Dime quiénes son tus vecinos y te diré quién eres"
3. **Árbol de Decisión** - Como un diagrama de flujo con preguntas
4. **XGBoost** - Muchos árboles trabajando juntos (avanzado)
5. **LightGBM** - Similar a XGBoost pero más rápido

---

Autor:
Macarena Mora V.

