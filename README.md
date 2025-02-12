# Jugador-De-Blackjack-Con-IA-Basado-En-Reconocimiento-De-Cartas-Y-Estrategias-Estadisticas
Este repositorio contiene todos los archivos y recursos utilizados en el desarrollo del proyecto de inteligencia artificial para jugar Blackjack basado en el reconocimiento de cartas y estrategias estadísticas. A continuación, se describe la estructura del repositorio y el propósito de cada carpeta y archivo.

Estructura del Repositorio

1. Carpeta Cartas
   
Contiene todas las cartas utilizadas para el entrenamiento del modelo y el dataset. Nota: Se eliminaron algunas imágenes debido a su peso, por lo que la cantidad de imágenes puede diferir de la documentación original.

3. Carpeta CodigoInterfaz
   
Incluye todos los elementos utilizados en la interfaz del programa:

- Iconos, logos e imágenes utilizadas en la interfaz.
- Imágenes de las cartas utilizadas en la aplicación.
- Resultado del entrenamiento: el archivo best.pt, que contiene el modelo entrenado.
- Código del programa: archivos de la lógica del reconocimiento de cartas y la inteligencia artificial.

Interfaz gráfica:

- index.html: Estructura de la interfaz.
- style.css: Diseño y estilos de la interfaz.
- script.js: Funcionalidades interactivas dentro de la interfaz.

3. Carpeta runs

Contiene los resultados del entrenamiento:

segment/train: Almacena los resultados y predicciones generadas durante el entrenamiento del modelo.

4. Archivos de Generación de Datos

- Archivo para crear imágenes: Genera imágenes con dos cartas aleatorias en diferentes posiciones, con variaciones de luz y contraste para mejorar el dataset.
- Dataset: Conjunto de imágenes utilizadas para entrenar el modelo (almacenado en la carpeta Cartas).
- Archivo de etiquetado automático: Etiqueta automáticamente las cartas generadas. Nota: Todas las etiquetas fueron revisadas manualmente para verificar errores.

5. Documentación

Jugador De Blackjack Con IA Basado En Reconocimiento De Cartas Y Estrategias Estadísticas.pdf: Documento que explica el desarrollo del proyecto, el modelo de inteligencia artificial y su funcionamiento.

6. Archivos del Modelo YOLO

- dataset.yaml: Archivo de configuración del dataset utilizado en el entrenamiento.
- yolov8m-seg.pt: Modelo utilizado para el entrenamiento.

Nota: El programa fue entrenado con YOLOv8, pero actualmente se encuentra disponible YOLOv11.
