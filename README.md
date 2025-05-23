# Challenge Alura Store

Este proyecto es un archivo Jupyter Notebook (.ipynb) que contiene varios scripts para generar estadísticas y gráficos a partir de archivos CSV con datos de ventas de una tienda. Los datos se obtienen directamente desde URLs externas mediante pandas.

## 📦 Requisitos

- Python 3.x
- Jupyter Notebook o JupyterLab
- Bibliotecas:
  - pandas
  - matplotlib

Instala las dependencias ejecutando:

```
pip install pandas matplotlib
```

## 📂 Estructura del Proyecto

- `AluraStoreLatam.ipynb`: Notebook principal que contiene los análisis y gráficos generados.
- `base-de-datos-challenge1-latam/`: Carpeta que contiene los archivos `.csv` con los datos de ventas de la tienda.

## 🌐 Fuentes de Datos

Los datos se obtienen desde los siguientes enlaces:

- [Tienda 1](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [Tienda 2](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [Tienda 3](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [Tienda 4](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

## 📊 Funcionalidades

- Lectura y procesamiento de datos CSV desde URLs
- Generación de gráficos de barras, tortas y líneas
- Cálculo de estadísticas por categoría de producto
- Comparación de ventas entre diferentes tiendas
- Análisis de ingresos por producto y categoría

## 🚀 Cómo Ejecutar

1. Clonar el repositorio:

```
git clone https://github.com/lukitasmois/challenge-alura-store
```

2. Navegar al directorio del proyecto:

```
cd challenge-alura-store

```

3. Iniciar Jupyter Notebook:

```
jupyter notebook
```

4. Abrir `AluraStoreLatam.ipynb` y ejecutar las celdas para cargar los datos y generar los gráficos.


## ✅ Notas

- Los archivos CSV se cargan automáticamente desde las URLs, pero se pueden descargar manualmente si se desea trabajar sin conexión.
- Si se agregan nuevas categorías de productos o tiendas, es necesario actualizar las funciones correspondientes en el notebook.
