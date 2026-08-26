# Enunciado didáctico reconstruido — CameraX: foto, vídeo y análisis

Laboratorio Android para practicar varios casos de uso de **CameraX** dentro de una misma aplicación.

La aplicación debe:

- mostrar la previsualización de cámara mediante `PreviewView`;
- enlazar los casos de uso al ciclo de vida de la Activity;
- capturar fotografías JPEG y guardarlas mediante `MediaStore`;
- grabar vídeo MP4 mediante `VideoCapture<Recorder>`, con audio opcional cuando exista permiso de micrófono;
- ejecutar `ImageAnalysis` con estrategia `KEEP_ONLY_LATEST`;
- calcular como ejemplo la luminancia media del plano Y de los frames analizados;
- solicitar los permisos necesarios en tiempo de ejecución;
- degradar correctamente cuando el dispositivo no dispone de cámara o no soporta una combinación determinada de casos de uso.

La ejecución completa requiere dispositivo o emulador con cámara; las capacidades de codificación dependen del hardware.

No existe una base de datos asociada.
