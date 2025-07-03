# 🏘️ Análisis Exploratorio de Datos - Propiedades en Alquiler

Este proyecto forma parte de mi proceso de formación en Ciencia de Datos con **Alura Latam** y está enfocado en el desarrollo de habilidades en **análisis exploratorio de datos (EDA)** utilizando la biblioteca **Pandas**.

---

## 🎯 Objetivo del Proyecto

Comprender y limpiar una base de datos de propiedades en alquiler, respondiendo preguntas clave que permitan preparar los datos para un futuro modelo de Machine Learning.

Entre los objetivos principales:

- Entender la estructura general de los datos.
- Identificar y tratar valores faltantes o inconsistentes.
- Eliminar registros irrelevantes.
- Crear nuevas variables categóricas útiles para la visualización o modelado.

---

## 📚 Tecnologías utilizadas

- Python 3.10+
- Google Colab
- Pandas
- Trello (para organización del proyecto)

---

## 🔍 Preguntas clave abordadas

- ¿Cuál es el valor promedio de alquiler por tipo de propiedad?
- ¿Qué porcentaje representa cada tipo de propiedad?
- ¿Hay propiedades con alquiler o condominio igual a cero?
- ¿Qué columnas son útiles para generar nuevas variables?
- ¿Qué datos son necesarios para construir un modelo de predicción?

---

## 🛠️ Principales tareas realizadas

1. **Carga y exploración inicial de datos:**
   - Número de filas y columnas.
   - Columnas presentes y tipos de datos.
   - Exploración general de valores.

2. **Tratamiento de valores faltantes:**
   - Eliminación o imputación de datos nulos, según el caso.

3. **Eliminación de registros inconsistentes:**
   - Departamentos con alquiler = 0 o condominio = 0 fueron removidos.

4. **Creación de nuevas columnas:**
   - `descripcion`: Resumen amigable para mostrar en un sitio web (tipo, barrio, habitaciones, estacionamiento).
   - `tiene_suite`: Variable booleana indicando si tiene o no suite.

---

## 📊 Resultados esperados

Este análisis forma parte de una etapa previa a la construcción de un modelo de Machine Learning para estimar el valor de alquiler de propiedades. La calidad de los datos es crucial para un modelo exitoso, y este proyecto sienta las bases para lograrlo.

---

## 🧠 Lecciones aprendidas

- La importancia de tratar datos nulos antes del modelado.
- El poder de las transformaciones con Pandas.
- Cómo una buena preparación de datos mejora la calidad de los análisis posteriores.

---

## 🤝 Agradecimientos

Gracias a **Alura Latam** por su excelente metodología y a **Oracle Next Education** por patrocinar iniciativas de formación que realmente transforman vidas.

También agradezco al equipo técnico y mentores por su orientación durante el proceso.

---

## 📂 Estructura del repositorio

