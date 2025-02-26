🔬 Actividades Prácticas: Conceptos Básicos de Teledetección

📌 Actividad 1: Exploración de Imágenes Satelitales en Google Earth Engine
📍 Objetivo: Familiarizarse con la visualización de imágenes satelitales y la diferencia entre sensores pasivos y activos.

🔹 Pasos:

 1. Accede a Google Earth Engine con tu cuenta de Google.
 2. Copia y pega el siguiente script en el Editor de Código:
 3. Analiza las diferencias entre la imagen óptica (Landsat 8) y la de radar (Sentinel-1).

Pregunta de análisis: ¿Cuáles son las ventajas de cada tipo de sensor en términos de nubosidad y detección de estructuras en la superficie?


![GEE](https://github.com/user-attachments/assets/400396d9-2fd1-4189-a81a-0d8b55acb844)


📌 Actividad 2: Descarga y Visualización de Imágenes Satelitales en QGIS
📍 Objetivo: Descargar imágenes satelitales gratuitas y analizarlas en un software SIG.

🔹 Pasos:

-Descarga una imagen de Landsat 8 desde USGS Earth Explorer. o en su defecto usa el codigo proporcionado desde GEE 02_descargar_img_LS2
- Busca una imagen de tu región de interés. Modifica nombre y coordendas
- Descarga el producto Level 2 Surface Reflectance (SR).
- Abre QGIS y carga las bandas de la imagen descargada.

Crea una composición en color falso: 
Bandas (B5, B4, B3) → Vegetación en rojo (NDVI). 
Bandas (B6, B5, B4) → Imagen en falso color infrarrojo térmico. 

Pregunta de análisis: ¿Cómo cambia la percepción de los objetos en función de la combinación de bandas?
