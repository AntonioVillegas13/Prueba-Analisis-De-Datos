# Recopilacion de datos (Scraping):
- Facebook
- Twitter
- Tiktok
- Web

## Ruta planteada
![Ruta](https://user-images.githubusercontent.com/75056800/153736293-a1fd5503-7b33-4446-99b9-385e4c9a7a31.png)

# Pasos previos
Para poder ejecutar los scripts que permiten reallizar los procesos plateados anteriormente debemos tomar en cuenta las intalaciones ya sean de [Python](https://www.python.org/) junto con Jupyter Lab o el IDE que les sea conveniente, tambien pueden instalar [Anaconda](https://www.anaconda.com/products/individual) que dentro de su paquete de instalación encontraremos lo necesario para iniciar con este proceso.

# Desarrollo

## Paso 10
### *Conexión de MongoDB a CouchDB*
Para poder crear el script que permite la comunicación entre MongoDB y CouchDB debemos tomar en cuenta la instalacion de las libreria necesarios para su buen funcionamineto, es este caso ocuparemos las siguientes librerias que pueden ser descargadas e instaladas utilizando pip install --nombre

![10](https://user-images.githubusercontent.com/75056800/153835086-9db8ac5b-3c39-4010-b91e-fe9e7ff334c6.png)
Una vez exportada la libreria Creamos nuestra conexión a CouchDB que esta en nuestro servidor local aligual que MongoDB creamos los metodod necesarios que nos informen en el caso de que exista algun error.


![10a](https://user-images.githubusercontent.com/75056800/153835598-a0898ad6-7866-4ae5-ae79-17ad74c66cfb.png)

Definimos los nombres de las bases de datos tanto de salida como de llegada tomando en cuenta que para MongoDB necesitamos un nombre de una colección.
![10b](https://user-images.githubusercontent.com/75056800/153835952-fa398160-3c4d-4c28-b753-833aaee4086c.png)

Una vez confirmadas las conexiones procedemos a extraer los datos de la base de CouchDB le damos formato utilizando codigo de Python y la vamos guardando en MongoDb.


![10c](https://user-images.githubusercontent.com/75056800/153836471-57e5e2c6-dc5f-4d95-af4a-5b902bef2d0e.png)

Se observa que este script nos permite elegir que columnas vamos a tomar para tener una base de datos ordenada.
