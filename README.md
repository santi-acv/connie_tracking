# Tracking de muones del experimento CONNIE

A continuación se detallan los notebooks en el repositorio.

* *1. generar_catalogo_simulacion*: Lee datos de una simulación en formato root y genera un catálogo de impactos en formato csv. Este catálogo contiene los números de track, las posiciones y las features de cada impacto.

* *2. tracking_determinar_parametros*: Lee un catálogo generado y entrena los modelos de regresión lineal con sus datos. Luego, ejecuta el algoritmo de tracking y evalúa su desempeño. Esto permite ajustar los parámetros hasta que se obtenga un desempeño deseado.

* *3. tracking_solo_algoritmo*: Lee un catálogo generado y ejecuta el algoritmo de tracking con parametros obtenidos previamente.

* *analisis_varios*: Genera gráficos y extrae cierta información a partir de un catálogo.

* *graficador_root*: Lee un archivo root y genera imágenes de los CCDs en formato fits o png.

* *leer_datos_connie*: Lee datos del experimento CONNIE en formato root.
