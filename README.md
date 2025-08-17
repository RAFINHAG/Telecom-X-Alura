# 📊 Análisis de Evasión de Clientes (Churn) – Telecom X

Este proyecto forma parte del desafío del programa One, en colaboración con Alura y Telecom X. El objetivo es analizar el comportamiento de los clientes de una empresa de telecomunicaciones para identificar las causas de su evasión (churn) y preparar los datos para un modelo predictivo.

---

## 🚀 Objetivos del Proyecto

- Extraer datos desde una API en formato JSON.
- Limpiar y transformar los datos para análisis.
- Realizar un análisis exploratorio (EDA) con visualizaciones.
- Identificar patrones que expliquen el churn.
- Redactar un informe final con conclusiones y recomendaciones.

---

## 🛠️ Tecnologías Utilizadas

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Trello (gestión del desafío)

---

## 📁 Estructura del Notebook

### 1. Extracción
Se realizó una solicitud HTTP a una API proporcionada por Telecom X para obtener los datos en formato JSON. Estos fueron convertidos a un DataFrame de Pandas.

### 2. Transformación
- Eliminación de duplicados.
- Tratamiento de valores nulos.
- Codificación de variables categóricas.
- Preparación del dataset para análisis y modelado.

### 3. Carga y Análisis
- Visualización de la distribución de churn.
- Análisis por tipo de contrato, llamadas al servicio al cliente y cargos adicionales.
- Mapa de calor de correlaciones entre variables.

### 4. Informe Final
Se redactó un informe estructurado que incluye:
- Introducción al problema.
- Detalles del tratamiento de datos.
- Hallazgos clave del análisis exploratorio.
- Conclusiones e insights.
- Recomendaciones para reducir la evasión.

---

## 📌 Principales Hallazgos

- Los clientes con contrato mensual presentan mayor tasa de churn.
- El número de llamadas al servicio al cliente está correlacionado con la evasión.
- Cargos adicionales por servicios premium aumentan el riesgo de abandono.

---

## ✅ Recomendaciones

- Implementar programas de fidelización para contratos mensuales.
- Mejorar la atención al cliente con seguimiento personalizado.
- Ofrecer paquetes personalizados con descuentos para servicios premium.

---

## 📄 Archivo de Datos

El archivo limpio y transformado está disponible como `clientes_churn_limpio.csv` para ser utilizado por el equipo de ciencia de datos en modelos predictivos.

---

## 👨‍🏫 Autor

**Wilfredo Rojas** – Instructor del programa One  
**Rafael [Tu Apellido]** – Analista de datos participante del desafío

---

## 📬 Contacto

Para dudas o sugerencias, puedes abrir un issue en este repositorio o contactarme directamente.

---

