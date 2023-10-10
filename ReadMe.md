<h1 align=center>Proyecto Individual</h1>
<h3 align=center>Accidentes-Aereos-PI</h3>

---
<p align=center><img src="https://aeronoticias.com.pe/noticiero/wp-content/uploads/2020/02/Terminal-A%C3%A9rea-Internacional-JFK.jpg" height=200></p>

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


<p align=center><img src="https://th.bing.com/th/id/R.eac2c83821b51153e7420766a08d5327?rik=y3Xv64SUVi%2fpiA&pid=ImgRaw&r=0" height=200></p>

En este contexto, este proyecto toma una profunda preocupación sobre la forma de registro de los datos que nos han proporcionado, la forma en la que se registran los accidentes podría ser mejor y más eficiente.
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

<p align=center><img src="https://th.bing.com/th/id/OIP.WqdMmNrSKzbDWx0Yc9_VUgHaC_?pid=ImgDet&rs=1" height=80>
<img src="https://miro.medium.com/max/765/1*qePzd2m_uIPvsozXYh89CQ.png" height=80> 
<img src="https://th.bing.com/th/id/R.13e8ebca307d02e996f676ecaabdffb2?rik=Syl7UOWvJYGwSQ&pid=ImgRaw&r=0" height=80>
<img src="https://th.bing.com/th/id/OIP.IDZGIlL9zPcQsl8xdhX2KwHaEV?pid=ImgDet&rs=1" height=80>
<img src="https://th.bing.com/th/id/R.10327dc6812b05b66a2b6b44c55a097c?rik=nKIXnE7Aetd6Uw&pid=ImgRaw&r=0" height=80>
<img src="https://th.bing.com/th/id/R.69107c46265ecc114173f2b2d6433209?rik=ikZgnCKxf3dQpA&pid=ImgRaw&r=0" height=80>
</p>

## Dashboard Interactivo

El Dashboard interactivo, pensado para contribuir con la comprensión de los análisis hechos, está abordado desde la plataforma de Power BI. Trabajado con la base de datos SQL. Teniendo en el valores importantes como los KPI's o los múltiples gráficos que funcionan conjuntamente con los filtros para obtener la información requerida por el usuario. A continuación, se presenta una imagen del Dashboard realizado para este proyecto.

<p align=center><img src="" height=200></p>

## Contacto
Respecto al proyecto, puede hacer un <em>fork</em> a su repositorios y trabajar con el. O bien, trabajar con el en este mismo repositorio, en una rama diferente y solicitar incorporar los cambios, a través de:

- <img src="https://th.bing.com/th/id/R.229079c8f5240851cece598cf8eee770?rik=TvMiz3mBQ9DAlQ&riu=http%3a%2f%2fwww.techerator.com%2fwp-content%2fuploads%2f2013%2f06%2fGmail-Logo.png&ehk=whqP3PDQYFbziZN8i5yRAa9t7YY2hWS0gvPmKvxRoug%3d&risl=&pid=ImgRaw&r=0" height=15> Mail: [Gmail Profesional](mariagustin.prog@gmail.com)

En caso de querer contactar con el desarrollador del proyecto:

- <img src="https://th.bing.com/th/id/R.6f9a03bd4554e5454de1c79f4c91aadf?rik=OLlYUhJuVFf4RQ&pid=ImgRaw&r=0" height=20> LinkedIN: [Mariano Acosta Chico](https://ar.linkedin.com/in/mariano-agust%C3%ADn-acosta-chico-b67584266)

- <img src="https://th.bing.com/th/id/R.26d9974a1feec9905a4e0d5e5ddf8db6?rik=Og1ujXM2C1AJHQ&riu=http%3a%2f%2fupload.wikimedia.org%2fwikipedia%2fcommons%2fa%2fa5%2fInstagram_icon.png&ehk=1%2fZWXYn2nN%2fR80TOtcKH5SsdLkkUvMLrB%2fHUXRDHk9I%3d&risl=&pid=ImgRaw&r=0" height=20> [Cuenta Personal de Instagram](https://www.instagram.com/mariagustin_017/)

- <img src="https://th.bing.com/th/id/OIP.NGIDdVP6vw9ue_D-mrEVFQHaHa?pid=ImgDet&rs=1https://logos-download.com/wp-content/uploads/2016/09/GitHub_logo.png" height=20> [GitHub](https://github.com/Mariagustin-Prg/)

---
<h5 align=center>Este proyecto fue producido en el marco de estudios de Henry, en la etapa de Proyectos Individuales.</h5>
<p align=center><img src="https://th.bing.com/th/id/OIP.367zRo1Vd57GRoXqjF6sxgAAAA?pid=ImgDet&rs=1" height=169></p>
<hr>