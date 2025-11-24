GUÍA DE USUARIO

1. Inicio
- Al ejecutar gui.py, se abre una ventana con:
  - Título del sistema.
  - Logo de la universidad (arriba a la derecha).
  - Panel de información (izquierda).
  - Imagen de la cafetería (derecha).

2. Panel de información
El recuadro de la izquierda muestra:
- Fecha actual.
- Clasificación de ocupación (llena, media_llena, vacía).
- Exactitud de la predicción de la CNN (porcentaje).
- Hora de la foto (si viene en el nombre del archivo).
- Cantidad de personas detectadas por YOLO.

3. Imagen de la cafetería
- A la derecha se muestra la foto que está siendo analizada.
- La imagen cambia automáticamente cada cierto tiempo (por ejemplo, cada 10 segundos).
- Las imágenes se leen desde la carpeta configurada en CARPETA_IMAGENES.

4. Funcionamiento básico
- La CNN clasifica qué tan llena está la cafetería.
- YOLO cuenta cuántas personas aparecen en la foto.
- Los resultados se actualizan junto con cada nueva imagen.

5. Cierre
- Para cerrar el sistema, simplemente cierra la ventana de la interfaz
  o detén la ejecución desde la terminal (Ctrl + C).
