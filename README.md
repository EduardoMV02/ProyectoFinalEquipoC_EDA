# Análisis Exploratorio de Ventas E-commerce (Olist)

## Descripción del Proyecto
Este repositorio contiene el proyecto final de la materia de Ciencia de Datos enfocado en el Análisis Exploratorio de Datos (EDA) del "Brazilian E-Commerce Public Dataset" proveído por Olist. El objetivo es limpiar, procesar y analizar más de 90,000 registros para extraer *insights* de valor comercial.

## Integrantes del Equipo C
- Eduardo Mendez Valenzuela
- Jose de Jesus Polo Martinez
- Juan de Dios Arenas Sanchez

## Preguntas de Negocio Resueltas
1. ¿Cuál es la tendencia de ventas mensuales y cómo impacta el costo de envío en el total de la orden?
2. ¿Qué categorías de productos generan los mayores ingresos?
3. ¿Existen tiempos de entrega atípicos (outliers) y en qué estados se concentran los retrasos logísticos?

## Tecnologías Utilizadas
- **Lenguaje:** Python 3
- **Librerías:** Pandas, Numpy (Limpieza y manipulación de datos), Matplotlib (Visualizaciones)
- **Entorno:** Jupyter Notebook / Visual Studio Code


## 📥 Instrucciones para ejecutar este código (Revisores)

Por cuestiones de buenas prácticas y para evitar sobrepasar los límites de almacenamiento en GitHub, los archivos originales de la base de datos (`.csv`) no están incluidos directamente en este repositorio. 

Para que el código se ejecute correctamente y sin errores (ya sea en Google Colab o en un entorno local), por favor sigue estos pasos:

1. **Descargar los datos:** Descarga los archivos del dataset desde el siguiente enlace: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download
2. **Crear la carpeta contenedora:** En el mismo lugar donde abriste el cuaderno (la raíz del proyecto o en el entorno virtual de Google Colab), crea una carpeta llamada exactamente **`data`** (todo en minúsculas).
3. **Acomodar los archivos:** Descomprime los datos que descargaste y coloca los archivos `.csv` directamente adentro de la carpeta `data`. 
4. **Ejecutar el cuaderno:** Una vez que los archivos `.csv` estén guardados dentro de la carpeta `data`, puedes abrir el archivo `ProyectoFinalEDA.ipynb` y "Ejecutar todas" las celdas. El código leerá las rutas correctamente y no marcará ningún error.