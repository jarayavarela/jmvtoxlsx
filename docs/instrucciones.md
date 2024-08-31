# Instrucciones

<p style="text-align: justify;">
Los archivos en formato JSON obtenidos del Historial de Ubicaciones de Google deben estar ubicados en una única carpeta. El programa te pedirá que indiques esta carpeta para integrar todos los archivos en un solo archivo Excel. Este Excel contendrá la información más relevante, optimizada para su posterior integración con los datos de los diarios de viaje.
</p>

## Ejemplo de JSON

<p style="text-align: justify;">
Este es el formato aproximado inicial que deben tener los archivos JSON para su análisis. Asegúrate de que tus archivos sigan esta estructura, ya que es esencial para que el software pueda generar correctamente los datos relacionados con los viajes realizados. Cada entrada en el JSON debe contener la información básica necesaria, como la marca de tiempo, la latitud, la longitud y la precisión, así como cualquier actividad asociada a ese momento específico.

Es fundamental que todos los archivos JSON que quieras analizar mantengan esta estructura, ya que cualquier desviación podría afectar la precisión de los resultados generados por el software. A continuación, se presenta un ejemplo del formato JSON requerido para asegurar una integración y análisis efectivos.
</p>

!!! hint

    Es importante destacar que el archivo JSON puede tener como segunda clave tanto "placeVisit" como "activitySegment" sin afectar el funcionamiento del software.

````json
{
  "timelineObjects": [{
    "activitySegment": {
      "startLocation": {
        "latitudeE7": 394807539,
        "longitudeE7": -3427222,
        "sourceInfo": {
          "deviceTag": -1364780865
        }
      },
      "endLocation": {
        "latitudeE7": 394754983,
        "longitudeE7": -3471247,
        "sourceInfo": {
          "deviceTag": -1364780865
        }
      },
      "duration": {
        "startTimestamp": "2022-10-20T19:16:10.414Z",
        "endTimestamp": "2022-10-20T19:28:00.690Z"
      },
      "distance": 751,
      "activityType": "WALKING",
      "confidence": "HIGH",
      "activities": [{
        "activityType": "WALKING",
        "probability": 86.69926524162292
      }, {
        "activityType": "STILL",
        "probability": 6.853951513767242
````

## Salida

<p style="text-align: justify;">
En la misma carpeta que selecciones para los archivos JSON, el software generará automáticamente una nueva carpeta llamada <i>salida</i>. Dentro de esta carpeta, se encontrará un archivo Excel denominado <i>resumen.xlsx</i>, que contiene la integración de todos los archivos JSON procesados. Este archivo <i>resumen.xlsx</i> consolida toda la información relevante de los datos de movilidad, facilitando su análisis y comparación con otros conjuntos de datos, como los diarios de viaje.
</p>

![archivo_de_salida](imagenes/carpeta_salida.gif)


