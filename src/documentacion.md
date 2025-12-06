# Documentation: `destinations.csv`

## 1. Descripción general
El archivo **`destinations.csv`** se lo ha descargado de *kaggle.com/datasets/faizadani/european-tour-destinations-dataset*, este archivo contiene informacion de destinos turisticos europeos, esta comprendido por 209 filas que cubren mas de 20 paises de toda europa

## 2. Ubicación del archivo
el archivo se encuentra dentro de este proyecto en la carpeta **dataset** 

## 3. Estructura del archivo

| Columna | Tipo recomendado | Descripción |
|--------|------------------|-------------|
| **Destination** | string | Nombre del destino turístico. |
| **Region** | string | Región dentro del país donde se encuentra el destino. |
| **Country** | string | País al que pertenece el destino. |
| **Category** | string | Tipo de destino (ej.: playa, montaña, ciudad, aventura). |
| **Latitude** | float | Coordenada de latitud del destino (para geolocalización). |
| **Longitude** | float | Coordenada de longitud del destino. |
| **Approximate Annual Tourists** | string | Cantidad aproximada de turistas que visitan el destino por año |
| **Currency** | string | Moneda oficial utilizada en el destino. |
| **Majority Religion** | string | Religión predominante en la región o país del destino. |
| **Famous Foods** | string | Platos típicos o gastronomía representativa del destino. |
| **Language** | string | Idioma principal hablado en el destino. |
| **Best Time to Visit** | string | Temporada o meses recomendados para visitar el destino. |
| **Cost of Living** | string | Nivel general del costo de vida (ej.: Bajo, Medio, Alto). |
| **Safety** | string | Indicador general del nivel de seguridad (Seguro, Moderado, Riesgoso). |
| **Cultural Significance** | string | Información sobre la historia, tradiciones o patrimonio cultural relevante. |
| **Description** | string | Descripción general del destino y sus principales atractivos. |

## 4. Estadísticas básicas (pendiente de análisis con Python)
- Número de filas: 209
- Número de columnas: 16

---

## 5. Uso en el sistema de recomendación
El Objetivo de este sistema de recomendacion sera lo siguiente:
* Mostrar los lugares mas visitados y mostrar al Cliente Primerizo que ingrese a la aplicacion y con ello abordaremos la solucion **COLD START**
* Luego como segundo ejercicio abordaremos la solucion con **FILTRADO COLABORATIVO BASADO EN CONTENIDO CON TF-IDF**

---
