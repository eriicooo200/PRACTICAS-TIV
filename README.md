# PRACTICAS-TIV
**Practicas de Tecnologías de la Imagen y Video**

## PRACTICA 1 - TIV

La Práctica 1 del Laboratorio de Tecnologías de la Imagen y Vídeo se enfoca en la estadística de imágenes y operadores puntuales. En esta practica debemos completar un notebook de Jupyter y subirlo a GitHub para su evaluación. Se proporcionan varias imágenes, como mamografías, estudios esqueléticos y otras, ubicadas en la carpeta "images" del repositorio de la asignatura.

Para cada imagen, se requiere realizar las siguientes tareas:

1. **Leer y Visualizar:**

- Leer e mostrar cada imagen.

2. **Análisis Estadístico:**

- Calcular estadísticas como máximo, mínimo, rango, media, desviación típica, varianza, coeficiente de variación, mediana, cuartiles, rango intercuartil y rango medio intercuartil.
- Construir histograma y función de distribución cumulativa.
- Crear un diagrama de dispersión (caja bigote).
- Describir razonadamente los resultados estadísticos basándose en la observación de las imágenes.
- Para imágenes a color, realizar el análisis por canales (R, G, B) y (H, S, V).

3. **Mejorar Exposición:**

- Ajustar brillo y contraste para mejorar la impresión visual en niveles de grises.
- Explicar los objetivos y métodos utilizados.

4. **Negativo para Imágenes Médicas:**

- Aplicar el negativo a las imágenes médicas.

5. **Transformaciones en Imágenes a Color:**

- Para imágenes a color, aplicar transformaciones solo sobre el canal de luminancia.

6. **Generar Máscaras:**

- Crear máscaras para extraer áreas de interés en cada imagen.

7. **Desaturar con Máscaras:**

- Desaturar zonas de la imagen en color utilizando máscaras para realzar otras áreas.
- La práctica tiene como objetivo repasar conceptos previamente aprendidos y experimentados en clase. 

## PRACTICA 2 - TIV

La Práctica 2 del Laboratorio de Tecnologías de la Imagen y Vídeo se centra en Operadores Locales y Detección de Bordes. En esta práctica debemos completar un notebook de Jupyter y subirlo a GitHub para su revisión. Las imágenes necesarias se encuentran en la carpeta "images" del repositorio de la asignatura, y las específicas para esta práctica son: gray_bands.tif, building.tif y head_CT.tif.

Las tareas solicitadas son las siguientes:

1. **Leer y Representar la Imagen:**

- Leer y visualizar la imagen gray_bands.tif.

2. **Detectar Bordes con Operador de Gradiente:**

- Utilizar un operador de gradiente para detectar y visualizar los bordes en la imagen.

3. **Detectar Bordes con Operador de Laplaciana:**

- Aplicar el operador de laplaciana para detectar y representar los bordes en la imagen.

4. **Añadir Ruido Gaussiano:**

- Introducir ruido gaussiano a la imagen, permitiendo al usuario configurar la desviación estándar.
- Representar las imágenes resultantes.

5. **Aplicar Operadores a Imágenes Ruidosas:**

- Utilizar los operadores de gradiente y laplaciana en las imágenes con ruido.
- Discutir la capacidad de detección de bordes en base a los resultados obtenidos.

6. **Filtrado Gaussiano Previo:**

- Aplicar un filtrado gaussiano a la imagen antes de utilizar los operadores mencionados.
- Evaluar si este preprocesamiento mejora la detección de bordes y discutir los resultados.

7. **Aplicar Detector de Canny:**

- Emplear el detector de Canny en las imágenes reales (building.tif y head_CT.tif) presentadas en clase.
- Discutir los resultados obtenidos y los parámetros utilizados en el algoritmo.

La práctica busca explorar y comprender métodos de detección de bordes, con un enfoque especial en la aplicación de operadores locales y técnicas de filtrado. 

## PRACTICA 3 - TIV

La Práctica 3 del Laboratorio de Tecnologías de la Imagen y Vídeo se centra en el tema de Segmentación. Al igual que en las prácticas anteriores, debemos completar un notebook de Jupyter y subirlo a GitHub para su revisión. La imagen proporcionada para esta práctica es riceBGgradient.tif.

Las tareas solicitadas son las siguientes:

1. **Leer y Representar la Imagen:**
   - Leer y visualizar la imagen riceBGgradient.tif.

2. **Separar Granos del Fondo con Umbral:**
   - Intentar separar los granos del fondo mediante la aplicación de un umbral.

3. **Corregir Inhomogeneidad con Transformación Morfológica Top-Hat:**
   - Reconocer la limitación del método de umbral debido a la inhomogeneidad en la iluminación.
   - Utilizar una transformación morfológica top-hat para corregir la iluminación, según lo enseñado en clase.

4. **Buscar Umbral Optimizado:**
   - Emplear la función "skimage.filters.threshold_otsu" para encontrar un umbral óptimo después de la corrección de iluminación.

La práctica tiene como objetivo abordar los desafíos de segmentación causados por irregularidades en la iluminación. 
