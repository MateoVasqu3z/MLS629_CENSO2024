# CENSO2024 - Análisis de Datos del Censo

Proyecto de análisis de datos del censo utilizando técnicas de limpieza, estandarización, clustering y visualización.

## 📋 Requisitos

- Python 3.12 o superior
- pip

## 🚀 Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/MateoVasqu3z/MLS629_CENSO2024.git
cd MLS629_CENSO2024
```

2. Crea un ambiente virtual:
```bash
python -m venv venv

# Activar en Windows:
venv\Scripts\activate

# Activar en Mac/Linux:
source venv/bin/activate
```

3. Instala las dependencias:
```bash
pip install -r requirements.txt
```

## 📁 Estructura del Proyecto
```
CENSO2024/
├── input/              # Coloca aquí tus archivos de datos
├── output/             # Resultados generados (se crea automáticamente)
├── images/             # Visualizaciones generadas
├── Notebook 1 - limpieza_datos.ipynb
├── Notebook 2 - estandarizacion_procesamiento.ipynb
├── Notebook 3 - reduccion de dimensionalidad.ipynb
├── Notebook 4 - clustering.ipynb
├── Notebook 5 - interpretacion de perfiles.ipynb
├── Notebook 6 - Visualizaciones.ipynb
└── requirements.txt
```

## 📊 Datos Necesarios

Coloca los siguientes archivos en la carpeta `input/`:
- `[datos.parquet]` - Son los datos crudos del censo 2024
- `[diccionario_variables.xlsx]` - Nombre de las etiquetas del dataset

> **Nota:** Los archivos de datos no están incluidos en el repositorio.

## ▶️ Uso

Ejecuta los notebooks en orden secuencial:

1. **Notebook 1**: Limpieza de datos
2. **Notebook 2**: Estandarización y procesamiento
3. **Notebook 3**: Reduccion de dimensionalidad
4. **Notebook 4**: Clustering
5. **Notebook 5**: Interpretacion de perfiles
6. **Notebook 6**: Visualizaciones

Cada notebook genera archivos que son utilizados por el siguiente, por lo que **es importante seguir el orden**.

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib/Seaborn
- Jupyter Notebook

## 👤 Autores

- Jacqueline Elizabeth Alfaro Rivas
- Tania Ivon Cañas de Escalante
- Jocelyn Alejandra Cornejo Cruz
- Diego Mateo Vasquez Perez
- Maestría en Data Science & Business Intelligence, Universidad Don Bosco


## 📄 Acerca del Proyecto

Proyecto académico desarrollado para la materia de Machine Learning no supervisado de la Maestría en Ciencia de Datos e Inteligencia de Negocios en la Universidad Don Bosco, El Salvador.

**Objetivo:** Aplicar técnicas de Machine Learning no supervisado (K-means y HDBSCAN) para el análisis y segmentación de datos del censo.

**Uso:** Este código está disponible con fines educativos y de referencia académica.