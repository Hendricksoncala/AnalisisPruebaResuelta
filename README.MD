

```
# 📊 Análisis de Datos - Prueba Técnica Allied Global

Este proyecto carga una base de datos desde un archivo Excel, transforma los datos en una estructura relacional y genera análisis básicos usando Python y pandas.

## 📁 Estructura del Proyecto

- `Prueba.py`: Script principal que realiza toda la transformación y análisis.
- `requirements.txt`: Lista de librerías necesarias.
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

## 🚀 Ejecución

Una vez dentro del entorno virtual, ejecuta el script principal:

```bash
python Prueba.py
```

Esto generará dos archivos:

- `base_datos_relacional.xlsx`
- `resultados_analisis.xlsx`

## 🧠 ¿Qué analiza?

- Total de ingresos por región
- Cliente con mayor volumen de compras
- Ingreso promedio por categoría
- Producto más vendido
```

---