<p align=left><img src=src\logo.png width="35%">

# **Proyecto Individual 2:** Data Analitycs: Telecomunicaciones
### by Nilda Pérez Otero

Este es mi segundo proyecto individual de Labs de la carrera de Data Sciende de Soy Henry. Bienvenidos! 

## **Descripción del problema**


### **Contexto**

Cuando hablamos de telecomunicaciones nos referimos a la transmisión de información a través de medios electrónicos, como la telefonía, la televisión, la radio y el internet. Estos medios permiten la comunicación y el intercambio de información entre personas, organizaciones y dispositivos a larga distancia. El internet, como una red global de computadoras interconectadas, ha revolucionado la forma en que nos comunicamos, trabajamos y nos relacionamos, brindando acceso a información instantánea y permitiendo la interacción en tiempo real.

En Argentina, la industria de las telecomunicaciones ha experimentado un importante desarrollo, con una amplia disponibilidad de conexiones y servicios. Con un total de [62,12 millones de conexiones](https://www.datosmundial.com/america/argentina/telecomunicacion.php), Argentina se encuentra en una posición destacada en comparación con la media mundial. Las telecomunicaciones desempeñan un papel fundamental en la sociedad argentina, permitiendo la comunicación constante y el acceso a información en todo el país y más allá.

 
### **Rol a desarrollar**

En este contexto,la empresa ficticia JujuyNet, una mediana empresa jujeña, prestadora de servicios de telecomunicaciones ha encargado la realización de un **análisis** completo que permita reconocer el comportamiento de este sector a nivel nacional. La empresa, además de brindar **acceso a internet** es proveedora de **televisón por cable** solo en Jujuy, y está analizando la posibilidad de ingresar en el mercado regional.

### **Objetivo del proyecto**

El objetivo de este proyecto consiste en ayudar a la empresa a identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.
Para ello, en primer lugar se realiza un [EDA](PI02_EDA.ipynb) de las fuentes de datos entregadas, luego se identifican KPI adecuados y finalmente se presentará a los directivos de la empresa un *dashboard* interactivo en PowerBI para facilitarles el acceso a la información y su análisis.

## **EDA**

Para realizar el EDA se trabajó con información de mercado, oferta, demanda y cobertura de los servicios de comunicaciones (hasta el tercer trimestre 2022), brindados por el Ente Nacional de Comunicaciones (Enacom), en la sección [Acceso a Internet](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/).
En este análisis se identificaron, entre otras:

* Distribución a nivel nacional de las diferentes tecnologías de acceso a internet.
* Tecnologías que están quedando obsoletas frente a las que están en crecimiento.
* Evolución de las velocidades de bajada por localidades, provincias y regiones.

`Datos utilizados para el análisis`

Además de los datasets de Acceso a internet se utilizó el de [Penetración nacional de la telefonía móvil (accesos por cada 100 habitantes)](https://datosabiertos.enacom.gob.ar/visualizations/29940/penetracion-nacional-de-la-telefonia-movil-accesos-por-cada-100-habitantes/) y algunos de la sección [TV Paga](https://datosabiertos.enacom.gob.ar/dashboards/20002/television-por-suscripcion-y-satelital/).

## **KPI's** 

Los KPI's que se sugieren en función de lo requerido por la empresa ficticia, y que se presentarán en el *dashboard* son:

* Cobertura geográfica
* Velocidad de la conexión
* Rentabilidad