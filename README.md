# Interacciones con mi Smarpthone con Android

Realizado como proyecto para el curso sobre Visualización de Información de la [Especialización en Ciencia de Datos](https://www.itba.edu.ar/especializacion-en-ciencia-de-datos/) en el Instituto Tecnológico de Buenos Aires (Argentina). 

Link a la Visualización: [fermasia.github.io/interacciones-android](https://fermasia.github.io/interacciones-android/)

---

Cómo utilizarlo:

Descargar desde takeout.google.com en el apartado 'Mi Actividad' el archivo en formato JSON para ser procesado.

Utilizar [notebook en python](https://github.com/fermasia/interacciones-android/blob/gh_pages/Android_Apps_Usage.ipynb) para procesar el origen en JSON publicado RAW en una url en Github, pudiendo adpatarse para cualquier origen local o publicado.

De la notebook/script resultan archivoss en formato CSV para poder alimentar gráficos a desarrollar en https://flourish.studio/, sobre (1) la evolución histórica del uso de aplicaciones en Smartphone ([**Line chart race**](https://app.flourish.studio/@flourish/horserace)), (2) la distribución del uso por día de la semana ([**Radar chart**](https://app.flourish.studio/@flourish/radar/)), y (3) un heatmap por día de la semana y hora de interacciones agregadas con aplicaciones ([**Heatmap**](https://app.flourish.studio/@flourish/heatmap/)).

Para el ejemplo fueron seleccionadas manualmente las apps más representativas, pero el script incluye para funcionalidad para tomar automáticamente un nro defindo (Top N) aplicaciones.
