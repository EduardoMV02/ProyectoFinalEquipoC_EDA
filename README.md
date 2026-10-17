# Análisis Exploratorio de Ventas E-commerce (Olist) 

## Descripción del Proyecto y el Dataset
Este repositorio contiene el proyecto final de la materia de Ciencia de Datos enfocado en el Análisis Exploratorio de Datos (EDA). El dataset utilizado es el "Brazilian E-Commerce Public Dataset by Olist", el cual contiene más de 90,000 registros reales de compras en línea. El objetivo es limpiar, procesar y analizar estos datos mezclando variables numéricas, categóricas y de fechas para extraer *insights* de valor comercial y responder a tres preguntas de negocio clave.

## Integrantes del Equipo C
- Eduardo Mendez Valenzuela
- Jose de Jesus Polo Martinez
- Juan de Dios Arenas Sanchez

## Preguntas de Negocio (Objetivos)
1. ¿Cuál es la tendencia de ventas mensuales y cómo impacta el costo de envío en el total de la orden?
2. ¿Qué categorías de productos generan los mayores ingresos?
3. ¿Existen tiempos de entrega atípicos (outliers) y en qué estados se concentran los retrasos logísticos?

---

## 📥 Instrucciones para Reproducir el Proyecto (Revisores)

Por restricciones técnicas y mejores prácticas, el archivo `.gitignore` está configurado para no subir los archivos `.csv` pesados a este repositorio. Para ejecutar el cuaderno en un entorno limpio sin errores, sigue estos pasos:

### 1. Preparar los Datos
1. Descarga el dataset oficial desde Kaggle en este enlace: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download
2. En la raíz de este repositorio, crea una carpeta llamada exactamente **`data`** (todo en minúsculas).
3. Descomprime el archivo descargado y coloca todos los archivos `.csv` adentro de esa carpeta `data`.

### 2. Instalar Dependencias
Asegúrate de tener instaladas las librerías necesarias ejecutando el siguiente comando en tu terminal para leer el archivo de requerimientos:
`pip install -r requirements.txt`

### 3. Ejecución
Una vez que los datos estén en la carpeta `data` y las librerías instaladas, abre el archivo `ProyectoFinalEDA.ipynb` y ejecuta todas las celdas. El código realizará la limpieza, imputación, operaciones vectorizadas con Numpy y los cruces con Pandas de forma automática.