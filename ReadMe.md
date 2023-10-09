<h1 align=center>Proyecto Individual</h1>
<h3 align=center>Accidentes-Aereos-PI</h3>

---
<p align=center><img src="https://th.bing.com/th/id/OIP.h98UvBu_yr_BsgFztzTzSwAAAA?pid=ImgDet&rs=1" height=200></p>

---
## Contenido
- [Introducción](##Introduccion")
- [Repositorio](##repositorio)
- [Instalación y Uso](##instalacion-y-uso)
- [Desarrollo y herramientas](##desarrollo-y-herramientas)
- [Dashborard Interactivo](##dashboard)
- [Contacto](##contacto)

---
---
## Introduccion 
Para este proyecto de Data Analytics, el propósito de todo el trabajo es encontrar las causas principales de los accidentes aéreos registrados por la OACI (Organización de la Aviación Civil) e intentar proponer una solución para disminuir los accidentes y su fatalidad.

Existen algunos patrones interensantes que podrán observar en el [Análisis Exploratorio](./Analisis_Exploratorio.ipynb) junto a sus respectivas visulizaciones y conclusiones.

En este contexto, este proyecto toma una profunda preocupación sobre la forma de registro de los datos que nos han proporcionado, la forma en la que se registran los accidentes podría ser mejor y más eficiente.

<p align=center><img src="https://th.bing.com/th/id/R.eac2c83821b51153e7420766a08d5327?rik=y3Xv64SUVi%2fpiA&pid=ImgRaw&r=0" height=200></p>

## Repositorio

<p align=center><img src="https://th.bing.com/th/id/OIP.tXLFnThYgg4QUI2R-KQHxAHaEK?pid=ImgDet&rs=1" height=200></p>

En este repositorio se encuentran los siguientes archivos y contienen la siguiente información:

[**AccidentesAviones.csv**](./AccidentesAviones.csv): Es el archivo en el que se basa todo este proyecto, es el csv que contiene toda la información que después se segmenta y analiza.

[**Analisis_Exploratorio.ipynb**](Analisis_Exploratorio.ipynb):  En este archivo se analizan los registros duplicados, los valores faltantes y los valores atípicos. También se hacen análisis respecto a la relación de las columnas incluidas en el dataset inicial con visualizaciones y utilizando códigos de python para encontrar patrones, similitudes, valores extremos, promedios, entre otros análisis que se hicieron en este notebook.

[**database.sql**](database.sql): Este archivo contiene la misma información que [AccidentesAviones.csv](AccidentesAviones.csv), en formato de base de datos relacional SQL.

[**introduccion_1.ipynb**](introduccion_1.ipynb): En este notebook se hace un paneo general de como esta el dataset, como la cantidad de filas, de columnas, cambiando los nombres de las columnas.

[**requirements.txt**](requirements.txt): Aquí se encuentran todas las dependencias necesarias para poder ejecutar el proyecto en su entorno local.

[**segmentacion.ipynb**](segmentacion_2.ipynb): En este notebook incluimos la formación de la [base de datos relacional](database.sql) que se encuentra en este repositorio, con la segmentación de tablas y exportación a un motor de consultas SQL en el entorno local, como se especifica en el mismo notebook.

## Instalación y Uso
Para poder utilizar este repositorio en su entorno local, teniendo acceso a todos los archivos de este repositorio, puedes utilizar el siguiente comando de **GIT**:
```
git clone https://github.com/Mariagustin-Prg/Accidentes-Aviones-PI.git
```
```En caso de no tener instalado GIT, puede acceder a la descarga de este en su página:``` [git-scm.com](https://git-scm.com/downloads)

<p align=center><img src="https://th.bing.com/th/id/R.475062ddf343c988cbb17760f4eaa820?rik=80a78shVstRy3g&pid=ImgRaw&r=0" height=200>

Debería utilizar un entorno virtual para instalar las dependecias. En el desarrollo de este proyecto se utilizo un entorno virtual de Python. Para poder tener un entorno virtual:

```
py -m venv nombre-del-entorno-virtual
```

Para activar el entorno e instalar las dependecias:
```
venv\Scripts\activate

pip install -r requirements.txt
```

## Desarrollo y Herramientas
Para el desarrollo de este proyecto se utilizaron herramientas como *librerías de python*, *jupyter notebook's*, *SQL Workbench* o *ChatGPT*, entre otras. Entre las librerías utilizadas están: *pandas*, *ntkl*, *re*, *numpy*, *pymysql*, *sqlalchemy* o *datetime*.

<p align=center><img src="https://th.bing.com/th/id/OIP.WqdMmNrSKzbDWx0Yc9_VUgHaC_?pid=ImgDet&rs=1" height=60>
<img src="https://miro.medium.com/max/765/1*qePzd2m_uIPvsozXYh89CQ.png" height=60> 
<img src="https://th.bing.com/th/id/R.13e8ebca307d02e996f676ecaabdffb2?rik=Syl7UOWvJYGwSQ&pid=ImgRaw&r=0" height=60>
<img src="https://th.bing.com/th/id/OIP.IDZGIlL9zPcQsl8xdhX2KwHaEV?pid=ImgDet&rs=1" height=60>
</p>

