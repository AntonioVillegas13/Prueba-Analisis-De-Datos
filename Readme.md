# Recopilacion de datos (Scraping):
- Facebook
- Twitter
- Tiktok
- Web

## Ruta planteada
![Ruta](https://user-images.githubusercontent.com/75056800/153736293-a1fd5503-7b33-4446-99b9-385e4c9a7a31.png)

# Marco Teorico

(Ingresar información)


# Obetivos
### - Analizar los diferentes métodos que podemos utilizar para recopilar datos.
### - Crear métodos para guardar la información recopilada en diferentes bases de datos.
### - Crear métodos que nos permitan la comunicación entre bases de datos.

# Desarrollo

## Paso 1
## Paso 2
## Paso 3
Almacenar datos de una pagina web de Facebbok en CouchDB 
## Paso 4
Almacenar datos de una pagina web de Facebbok en MongoDB 
## Paso 5
### *Conexión TikTok a CouchDB*
### <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Apache_CouchDB_logo.svg/1200px-Apache_CouchDB_logo.svg.png" width="50">
### 
En el paso 5 se realiza una recopilación de datos haciendo uso de una paquete llamado tiktok-scraper, lo cual nos brinda tres documentos de la recopilación, como lo es un archivo Json, CSV y Zip, dado que el archivo necesario es el Json lo cual nos permite abrir el archivo con código Python, puesto que nos permite leer la información para poder cargar a la Base de Datos CouchDB, Sin embargo se utilizó código para la conexión y creación de la base de datos, Finalmente la ejecución del código es satisfactorio.
## Paso 6
### *Conexión TikTok a MongoDB*
### <img src="https://sf-tb-sg.ibytedtos.com/obj/eden-sg/uhtyvueh7nulogpoguhm/tiktok-icon2.png" width="50">
### 
En el paso 6 consta de un mismo objetivo que es el de llegar a guardar la información en una base de datos, lo que cambia es su conexión y la base, dado que ahora es con MongoDb, para hace se utilizó diferente librerías como pandas, numpy, json, entre otros, lo cual nos permitió leer el archivo Json que se generó al realizar el tiktok-scraper y guardarlo en un DataFrame, puesto que nos permite visualizar la información en filas y columnas, luego de eso se realizó su respectiva conexión con las credenciales personales y creación de la base de datos y su colección, Finalmente se generó una función que nos permite recorrer columnas del DataFrame colocando un formato para que se vaya guardando en una variable, como ultimo llamamos a la función y pasamos como parámetro al DataFrame, donde nos muestra la recopilación de datos que se guardara en la base MongoDB.
## Paso 7
## Paso 8
## Paso 9
### *Conexión de CouchDB a MongoDB*
## Paso 10
### *Conexión de MongoDB a CouchDB*
## Paso 11
## Paso 12
## Paso 13
### *Conexión de MongoDB a MySQL*
## Paso 14
### *Conexión de MySQL a MongoDB*
#Datos
## Paso 15
## Paso 16







### Integrantes

## Adrian Chicaiza
## Alexander Tupiza
## Jean Fuentes
## Eduardo Farinango
## Antonio Villegas
