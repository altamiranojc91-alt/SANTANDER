# Panel de alarmas — Centro de control

Página web estática que muestra estadísticas a partir de un reporte de alarmas (.xlsx, .xlsm, .xls o .csv).

- Todo se procesa en el navegador; los datos del archivo no se envían a ningún servidor.
- Detecta automáticamente las columnas (Fecha, Hora, Oficina, Descripcion_Condicion, etc.) y permite corregirlas.
- Filtro por rango de fechas, hallazgos clave, gráficos por oficina, hora, día y tipo de alarma, y tabla de detalle.

## Cómo publicarla con GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube los archivos de este comprimido (`index.html`, `README.md` y `.nojekyll`).
3. En el repositorio ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
5. En uno o dos minutos la página estará disponible en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Notas

- Requiere conexión a internet para cargar las librerías SheetJS y Chart.js desde cdnjs.
- También puedes abrir `index.html` directamente en el navegador sin publicarlo.
