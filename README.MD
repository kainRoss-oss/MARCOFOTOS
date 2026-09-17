# MARCOFOTOS
App web (PMV) para tomar fotos desde el celular con tamaño exacto en cm, acomodarlas automáticamente en una hoja A4 o Carta, y generar un PDF listo para imprimir y recortar con marcos físicos.

## Estado
En desarrollo — PMV, primeros 30 días de prueba.

## Estructura
- index.html — UI principal
- src/camera.js — captura de cámara + overlay de marcos
- src/layout.js — cálculo de cuadrícula (cuántas fotos caben)
- src/pdf-export.js — generación del PDF (jsPDF)
- src/state.js — manejo de estado (fotos, tamaño elegido, etc.)
- assets/frames/ — marcos gráficos decorativos
