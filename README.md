# ConnectaTel Telecom Analysis – Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del Bootcamp de Análisis de Datos.

El proyecto utiliza información de clientes, planes y uso de servicios móviles de la empresa  ConnectaTel. Los datasets incluyen información de usuarios, planes contratados y registros de actividad (llamadas y mensajes), permitiendo realizar procesos de limpieza, análisis exploratorio, detección de outliers y segmentación de clientes.

## 📂 Contenido del repositorio

- `notebooks/connectatel_analysis.ipynb`

## Datasets utilizados:

- `plans.csv`: Información de los planes disponibles con 2 registros.
  → Con las columnas: plan_name,	messages_included,	gb_per_month,	minutes_included,	usd_monthly_pay,	usd_per_gb,	usd_per_message,	usd_per_minute

- `users_latam.csv`: Información de los clientes con 4,000 registros.
  → Con las columnas: user_id,	first_name,	last_name,	age	city,	reg_date,	plan,	churn_date

- `usage.csv`: Registros de llamadas y mensajes por usuario con 40,000 registros
  → con las columnas: id,	user_id,	type,	date,	duration,	length

## Etapas del análisis

1. Exploración inicial de los datasets.
2. Identificación de problemas de calidad de datos.
3. Limpieza y corrección de sentinels, fechas inválidas y valores faltantes.
4. Construcción de métricas de uso por usuario.
5. Análisis estadístico descriptivo.
6. Visualización de distribuciones y detección de outliers.
7. Segmentación de clientes por edad y nivel de uso.
8. Elaboración de insights y recomendaciones para el negocio.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/angelica-perez-carrillo/telecom-analysis.git)

O:

1. Abre el archivo `.ipynb` en GitHub.
2. Haz clic en **Open in Colab**.

## 📘 Cómo reproducir el análisis

1. Clona o descarga este repositorio.
2. Abre el archivo `notebooks/connectatel_analysis.ipynb`.
3. Instala las librerías necesarias:
   ```python
   pandas
   numpy
   matplotlib
   seaborn
