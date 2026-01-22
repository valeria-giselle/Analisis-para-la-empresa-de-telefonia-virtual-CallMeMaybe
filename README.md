# CallMeMaybe – Sistema de Scoring de Desempeño de Operadores

## 📌 Problema de Negocio
CallMeMaybe es una empresa de telefonía virtual que depende de operadores de call center para brindar atención a sus clientes.
La gerencia necesitaba una forma objetiva y basada en datos para identificar operadores con bajo desempeño, con el fin de mejorar la calidad del servicio y reducir los tiempos de espera de los clientes.

## 🎯 Objetivo
Desarrollar un sistema de scoring que permita identificar operadores ineficientes a partir de indicadores clave de desempeño (KPIs), reduciendo el tiempo de análisis manual y facilitando la toma de decisiones basada en datos.

## 📊 Dataset
El análisis se realizó a partir de registros de llamadas que incluyen:

- Llamadas entrantes y salientes
- Llamadas perdidas
- Tiempo de espera
- Identificador del operador

Los datos fueron limpiados, transformados y preparados utilizando Python.

## 🛠️ Metodología
1. Limpieza y preprocesamiento de datos
2. Definición de KPIs clave:
   - Llamadas perdidas
   - Tiempos de espera elevados
   - Bajo volumen de llamadas salientes
3. Construcción de la lógica de scoring para evaluar el desempeño de los operadores
4. Visualización de resultados mediante un dashboard interactivo en Tableau

## 📈 Resultados Clave
- Identificación clara de operadores con bajo desempeño a través de un modelo de scoring
- Reducción del 30% en el tiempo de análisis
- Mejora en la focalización de acciones de supervisión y capacitación

## 📊 Dashboard
👉 https://public.tableau.com/app/profile/valeria.godoy/viz/Dashboard_17522059746270/Dashboard1?publish=yes
<img width="1454" height="780" alt="image" src="https://github.com/user-attachments/assets/84ea2ed6-92c7-428a-a0cd-f4bc42767062" />

## 📌 Recomendaciones de Negocio
- Implementar planes de capacitación específicos para operadores con bajo score
- Monitorear los KPIs de forma semanal en lugar de mensual
- Utilizar el sistema de scoring como un mecanismo de alerta temprana para detectar problemas operativos

## 📁 Estructura del Repositorio
- `dashboard/`     → Tableau link
- `datasets/`          → Datasets usados en el proyecto
- `notebooks/`     → Jupyter notebook
- `Hallazgos Evaluación Empresa CallMeMaybe.pdf` → Presentación del proyecto
- `README.md` → Descripción del proyecto en español
- `README_EN.md` → Descripción del proyecto en inglés
- `requirements.txt` → Dependencias del proyecto

## ⚙️ Tecnologías
- Python
- Pandas
- NumPy
- Seaborn
- Plotly
- Matplotlib

## ▶ Cómo Ejecutar el Proyecto
pip install -r requirements.txt

jupyter notebook notebooks/proyecto_sprint_14.ipynb

## ✨ Nota Final
Este proyecto demuestra la aplicación de análisis de datos para resolver un problema real de negocio, combinando métricas operativas, automatización del análisis y visualización para apoyar la toma de decisiones.
