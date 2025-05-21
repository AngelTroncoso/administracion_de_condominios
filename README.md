# 🏢 Análisis de Pagos - Salud Financiera del Condominio

Este proyecto tiene como objetivo analizar los registros de pagos de un condominio con el fin de evaluar su salud financiera, identificar patrones de morosidad y proponer estrategias de mejora en la gestión de ingresos.

## 📊 Objetivos

- Analizar el cumplimiento de pagos por parte de los residentes.
- Detectar unidades con morosidad recurrente.
- Visualizar tendencias de ingresos mensuales.
- Calcular métricas clave: tasa de morosidad, ingreso proyectado vs. real, etc.
- Proporcionar recomendaciones basadas en datos para una administración más eficiente.

## 🧰 Herramientas y Tecnologías

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Power BI** o **Tableau** (para dashboards ejecutivos)
- **Git** y **GitHub** (control de versiones)
- **Markdown** (documentación)

## 🗂️ Estructura del Proyecto

📦 salud-financiera-condominio/
├── data/
│ ├── pagos_original.csv
│ └── pagos_limpios.csv
├── notebooks/
│ └── analisis_pagos_condominio.ipynb
├── visuals/
│ └── resumen_morosidad.png
├── README.md



## 📈 Métricas Analizadas

- Porcentaje de unidades al día vs. morosas
- Promedio de días de atraso por unidad
- Comparativa entre ingresos esperados y reales
- Historial de pagos por unidad
- Tendencias por mes y por tipo de unidad

## 🔍 Principales Hallazgos

- 🔴 Cerca del 22% de las unidades presenta pagos atrasados por más de 60 días.
- 📉 Los ingresos reales son en promedio un 15% inferiores a los proyectados.
- 🕒 Las unidades tipo “B” presentan mayores retrasos que las tipo “A”.
- 📆 El mes con más atrasos recurrentes es **enero**, posiblemente por efecto post-vacacional.

## 💡 Recomendaciones

- Implementar recordatorios automáticos previos a la fecha de vencimiento.
- Ofrecer incentivos por pago anticipado o puntual.
- Establecer un plan de regularización para unidades morosas con más de 3 meses.

## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/analisis-pagos-condominio.git
   cd analisis-pagos-condominio

Crea un entorno virtual:
  python -m venv venv
  source venv/bin/activate  # En Windows: venv\Scripts\activate
  
2. Instala las dependencias:
  pip install -r requirements.txt
  Ejecuta el notebook:

3. Ejecuta el notebook:
  jupyter notebook notebooks/analisis_pagos_condominio.ipynb

##  ✍️ Autor
Ángel Troncoso

📧 angeltroncoso2019@outlook.es

💼 LinkedIn [www.linkedin.com/in/angeltroncoso]

💻 web [https://angeltroncoso.github.io/business_analytics_pro/]

## 📄 Licencia
Este proyecto está bajo la Licencia MIT. Eres libre de usar, modificar y distribuir este trabajo con atribución correspondiente.
