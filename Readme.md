# Recopilacion de datos (Scraping):
- Facebook
- Twitter
- Tiktok
- Web

## Ruta planteada
![Ruta](https://user-images.githubusercontent.com/75056800/153736293-a1fd5503-7b33-4446-99b9-385e4c9a7a31.png)

# Pasos previos
Debemos tener instalado y configurado [MongoDB](https://www.mongodb.com/es), [CouchDB](https://couchdb.apache.org/) y [MySQL](https://dev.mysql.com/downloads/).

Para poder ejecutar los scripts que permiten reallizar los procesos plateados anteriormente debemos tomar en cuenta las intalaciones ya sean de [Python](https://www.python.org/) junto con Jupyter Lab o el IDE que les sea conveniente, tambien pueden instalar [Anaconda](https://www.anaconda.com/products/individual) que dentro de su paquete de instalación encontraremos lo necesario para iniciar con este proceso.

# Obetivos
### - Analizar los diferentes métodos que podemos utilizar para recopilar datos.
### - Crear métodos para guardar la información recopilada en diferentes bases de datos.
### - Crear métodos que nos permitan la comunicación entre bases de datos.

# Desarrollo

## [Paso 1](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-1-Twitter-a-CouchDB)
## [Paso 2](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-2-Twitter-MongoDB)
## [Paso 3](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-3-Facebook-CouchDb)
Almacenar datos de una pagina web de Facebbok en CouchDB 
## [Paso 4](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-4-Facebook-MongoDb)
Almacenar datos de una pagina web de Facebbok en MongoDB 
## [Paso 5](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-5-TikTok-a-CouchDB)
### *Conexión TikTok a CouchDB*
### <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Apache_CouchDB_logo.svg/1200px-Apache_CouchDB_logo.svg.png" width="50">
### 
En el paso 5 se realiza una recopilación de datos haciendo uso de una paquete llamado tiktok-scraper, lo cual nos brinda tres documentos de la recopilación, como lo es un archivo Json, CSV y Zip, dado que el archivo necesario es el Json lo cual nos permite abrir el archivo con código Python, puesto que nos permite leer la información para poder cargar a la Base de Datos CouchDB, Sin embargo se utilizó código para la conexión y creación de la base de datos, Finalmente la ejecución del código es satisfactorio.
## [Paso 6](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-5-TikTok-a-CouchDB)
### *Conexión TikTok a MongoDB*
### <img src="https://sf-tb-sg.ibytedtos.com/obj/eden-sg/uhtyvueh7nulogpoguhm/tiktok-icon2.png" width="50">
### 
En el paso 6 consta de un mismo objetivo que es el de llegar a guardar la información en una base de datos, lo que cambia es su conexión y la base, dado que ahora es con MongoDb, para hace se utilizó diferente librerías como pandas, numpy, json, entre otros, lo cual nos permitió leer el archivo Json que se generó al realizar el tiktok-scraper y guardarlo en un DataFrame, puesto que nos permite visualizar la información en filas y columnas, luego de eso se realizó su respectiva conexión con las credenciales personales y creación de la base de datos y su colección, Finalmente se generó una función que nos permite recorrer columnas del DataFrame colocando un formato para que se vaya guardando en una variable, como ultimo llamamos a la función y pasamos como parámetro al DataFrame, donde nos muestra la recopilación de datos que se guardara en la base MongoDB.
## [Paso 7](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-7-Web-Scraping-a-CouchDB)
## [Paso 8](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-8-Web-Scraping-MongoDB)
## [Paso 9](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-9-CouchDB-a-MongoDB)
### *Conexión de CouchDB a MongoDB*
## [Paso 10](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-10-de-MongoDB-a-CouchDB)

### *Conexión de MongoDB a CouchDB*


## [Paso 11](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-11-CouchDB-a-MongoDB_ATLAS)
## [Paso 12](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-12-MongoATLAS-a-CouchDB)
## [Paso 13](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-13-MongoDB-a-MySQL)
### *Conexión de MongoDB a MySQL*
## [Paso 14](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-14-de-MySQL-a-MongoDB)
### *Conexión de MySQL a MongoDB*
#Datos
## [Paso 15](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-15-MySQL-a-MongoDB)
## [Paso 16](https://github.com/AntonioVillegas13/Prueba-Analisis-De-Datos/tree/Paso-16-MongoDB-a-MySQL)







### Integrantes

 Adrian Chicaiza
 
 Alexander Tupiza
 
 Jean Fuentes
 
 Eduardo Farinango
 
 Antonio Villegas
