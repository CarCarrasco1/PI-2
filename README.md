# PI-2

# <h1 align=center>PROYECTO INDIVIDUAL
## <h1 align=center> DATA ANALYTICS</h1>


![](https://blog.soyhenry.com/content/images/2021/02/HEADER-BLOG-NEGRO-01.jpg)





## **INTRODUCCIÓN**


Antes de comenzar el desarrollo del proyecto algunas de las pautas de inicio del mismo.

- Rol a desarrollar: Data Analytics.

- Objetivo:  Extraer informacion del Índice S&P500, analizarla, realizar respectivos KPI's y entregar un informe visual con recomendaciones sobre compra de acciones. 

- Propuesta de trabajo:

		Búsqueda y descarga de información: Realizar el  trabajo de desacarga de datos desde Yahoo Finance para obtener el material de trabajo.

		Análisis exploratorio de los datos: Con el fin de descubrir las relaciones entre los datos, las empresas durante el tiempo, y comenzar a entablar las relaciones necesarias a futuro.

		KPI´s:  Establecer parametros objetivos para poder determinar cual es la recomndación de compra para el cliente.

		Dashboard y storytelling: Se encontrará la documentación en forma visual a traves de un dashboard de PowerBI, mediante el cual se comunicara la información y los resultados obtenidos.


## **DESARROLLO**


### PLANTEO DEL PROBLEMA


Como primer paso se buscan los datos con los que debo trabajar, estos fueron proporcionados en el siguiente `<links>` : [Yahoo Finance](https://finance.yahoo.com/) & [List of S&P 500 companies](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies).


Se observan los archivos que hay, y se decide trazar la ruta de trabajo, para día a día cumplir con pequeñas tareas y poder obtener informacioón de valor a los consultantes.


En resumen los pasos son a grandes rasgos: DESCARGA Y EDA - PLANTEO DE KPIS - DASHBOARD.


### EDA

"Exploratory Data Analysis" o "Análisis Exploratorio de Datos" en español. Es un proceso clave en el desarrollo de proyectos ya que ayuda a comprender mejor los datos que se utilizarán para en este caso establecer información de calidad.

La actividad comenzó descargando desde la web de los links anteriormente nombrados, la información sobre el S&p500. Para ello se hizo uso de una herramienta específica de Python, la librería: [yfinance](https://pypi.org/project/yfinance/). 

Acto seguido, obtenidos los registros desde el año 2000 hasta la actualidad, se descargó información descriptiva que complementaba y completaba a la anterior, la cual venía formada con datos de origen, nombres, lugar de fundación y más sobre las compañías.

Con los datos en un formato acorde para poder trabarlos, se inicio con el EDA propiamente dicho, se unieron ambas informaciones en un DataFrame único, el cual se uso para hacer exploración tanto de varibles, como de relaciones y comportamientos de los datos.

Este paso si bien no era de vital profundidad, requirió de bastante estudio del tema y caso en particular, después de consultar bastante bibliografía al respecto, se procedió a hacer los análisis relevantes, como: Matrices de correlaciones entre variables, los promedios de precio, el volumen y otros con respecto al tiempo transcurrido.

A medida que la data se fue esclareciendo, pude centrarme sobre unas variables que captaron mas mi atención, y fue así como el proceso se volcó sobre un sector en específico y  donde empecé a entablar mis primeras conclusiones sobre el tema.

Finalmente me quede procese los datos a un formato compatible para mi próximo paso.

### KPI´S

Los KPIs pueden ayudar a identificar áreas problemáticas y oportunidades de mejora, así como a establecer objetivos específicos y medibles para los equipos de trabajo.

Para este caso en particular se plantearon los siguientes KPI´s:

- **Índice ROI**: Un índice ROI positivo indica que la inversión ha sido rentable. Un índice ROI más alto que el promedio del mercado puede indicar una inversión exitosa.

- **Volatilidad**: Una volatilidad baja indica una mayor estabilidad y una menor probabilidad de pérdidas significativas debido a fluctuaciones de precios.

- **Volumen anual promedio**: Un volumen anual promedio alto indica una mayor liquidez y facilidad para comprar o vender acciones en el mercado.

### DASHBOARD

Se cargaron los datos obtenidos en la etapa de EDA y se realizo el calculo de los KPI's en lenguaje DAX, propio de Power BI, se desarrollaron gráficas acordes a los datos que se querían presentar y se concluyó con el análisis logrando el objetivo de poder hacer una recomendación de las cuatro compañías que por información encontre estables para la posible inversión. 

**Adjunto el link para que puedan visualizarlo aquí ->** [Dashboard S&P500](https://drive.google.com/drive/folders/1qoR2sIdQliKiNLTFV28eIhCP5gFsLhDq?usp=sharing).


### <h1 align=center> CARLA CARRASCO.</h1>


![](https://blog.soyhenry.com/content/images/size/w2000/2022/11/Paid-Media_BlogBanner.png)
