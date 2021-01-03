# **exodusLimpiezaAnalisisDatos**

### Operaciones de limpieza y análisis de datos del dataset Exodus

<div align="center"><img src="https://i.ibb.co/k6gb85C/exodusWS.jpg" alt="exodusWS" border="0" width = "1024" height = "320"></div>

## Descripción
Con motivos académicos para el Máster en Ciencia de Datos de la UOC, se realiza el proyecto de limpieza y análisis de datos correspondientes al dataset generado en la práctica anterior mediante técnicas de Web Scraping sobre el sitio web <a href = "https://exodus-privacy.eu.org/en/">Exodus-Privacy</a> dedicado a analizar aspectos de seguridad y privacidad en aplicaciones Android.
El NoteBook responde a las preguntas planteadas en el formulario de la práctica realizando las siguientes operaciones:
* Obtención del dataset json.
* Generación del Data Frame.
* Integración con el dataset de Kaggle *Google Play Store Apps*.
  * Nuevo dataset obtenido mediante web scraping para integrar un atributo de unión con el dataset de integración.
* Estrategias de selección por exploración y creación de nuevos atributos.
* Limpieza de datos vacíos y valores extremos.
* Análisis de los datos:
  * Comparación grupos de datos por contraste de hipótesis.
  * Regresión.
  * Correlación.
* Planteamiento y resolución de problemas gracias a los datos obtenidos, limpiados y analizados:
  * Agrupamiento.
  * Clasificación.
  
## Autoría
<table>
 <tr>
  <td><strong>Contribuciones</strong></td>
  <td><strong>Firma</strong></td>
 </tr>
 <tr>
  <td>Investigación previa</td>
  <td>LMMC</td>
 </tr>
 <tr>
  <td>Redacción de respuestas</td>
  <td>LMMC</td>
 </tr>
 <tr>
  <td>Desarrollo código</td>
  <td>LMMC</td>
 </tr>
 </table>

## Código fuente y recursos
* **M2.851_2020_Práctica2_luimoco.html**: Documento Notebook con las respuestas y su desarrollo en código. *¡Es preferible este formato al PDF!*.
* **M2.851_2020_Práctica2_luimoco.pdf**: Documento PDF con las respuestas y su desarrollo en código.
* **M2.851_2020_Práctica2_luimoco.ipynb**: Código Jupyter Notebook con el código y su ejecución. *Para la ejecución y visualización de imágenes, es necesario disponer de las carpetas data y src. En esta primera aplicando las instrucciones descritas más adelante*.
* **exodusAppID.ipynb**: Código Jupyter Notebook con el Web Scraper realizado como parte necesaria para la integración de datos externos.
* **README.md**: Esta misma WIKI.
* **df_exodus_original.zip**: El fichero CSV comprimido con los datos originales integrados.
* **df_exodus_final_analizado.zip**: El fichero CSV comprimido con los datos originales seleccionados y analizados.
  
* **/data/**: Directorio con los ficheros de datos que deben ubicarse en esta ruta que es referenciada desde el código en *M2.851_2020_Práctica2_luimoco.ipynb*:
  * **/data/exodusNoIcon.json.md**: Wiki que indica dónde obtener el fichero json fruto del web scrapping de la práctica 1.
  * **/data/Google-Playstore.csv.md**: Wiki que indica dónde obtener el fichero csv de integración obtenido de Kaggle.
  * **/data/exodusAppId.csv**: Dataset en formato CSV obtenido por la ejecución del web scraper desarrollado en*exodusAppID.ipynb*.
  * **/data/img/1.png**: Imagen de uno de los iconos de aplicación para ilustrar en el código los tipos de dataset origen de datos de *Exodus* considerados.
  
* **/src/**: El directorio contiene 5 imágenes utilizadas para ilustrar las explicaciones del desarrollo de las preguntas de la práctica.
