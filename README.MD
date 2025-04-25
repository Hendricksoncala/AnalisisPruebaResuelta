
```markdown
# 📊 Análisis de Datos - Prueba Técnica Allied Global

Este proyecto carga una base de datos desde un archivo Excel, transforma los datos en una estructura relacional y genera análisis básicos usando Python y pandas.

## 📁 Estructura del Proyecto

- `Proyecto_Analisis.py`: Script principal que realiza toda la transformación y análisis.
- `requirements.txt`: Lista de librerías necesarias.
- `PRUEBA_TECNICA_ALLIEDGLOBAL.xlsx`: Archivo de entrada (base de datos en Excel).
- `base_datos_relacional.xlsx`: Archivo generado con las tablas normalizadas.
- `resultados_analisis.xlsx`: Archivo generado con análisis básicos.

## 🛠️ Requisitos

- Python 3.10 o superior
- pandas
- numpy
- matplotlib
- seaborn
- openpyxl

## ⚙️ Instalación

1. Clona el repositorio o descarga los archivos.
2. Crea y activa un entorno virtual:

```bash
python -m venv .venv
.venv\Scripts\activate     # En Windows
# source .venv/bin/activate  # En Mac/Linux
```

3. Instala las dependencias necesarias con el archivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

## 📥 Datos de entrada

El archivo `PRUEBA_TECNICA_ALLIEDGLOBAL.xlsx` **no está incluido en el repositorio** por motivos de confidencialidad o tamaño.

Debes descargarlo por tu cuenta y colocar el archivo en la misma carpeta del script.

Luego, asegúrate de que en tu código esta línea esté así:

```python
archivo = "PRUEBA_TECNICA_ALLIEDGLOBAL.xlsx"
```

> 📌 Este archivo debe tener una hoja llamada `BBDD` para que el script funcione correctamente.

## 🚀 Ejecución

Una vez dentro del entorno virtual, ejecuta el script principal:

```bash
python Proyecto_Analisis.py
```

O si estás en Visual Studio Code, puedes ejecutarlo con el botón de **Run**.

Esto generará automáticamente dos archivos:

- `base_datos_relacional.xlsx`
- `resultados_analisis.xlsx`

## 🧠 ¿Qué analiza?

- Total de ingresos por región
- Cliente con mayor volumen de compras
- Ingreso promedio por categoría
- Producto más vendido
```

