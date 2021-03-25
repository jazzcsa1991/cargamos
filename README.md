#

ApiRes para la creación de inventario desarrollada en flask,

-requiere una base de datos en posgresql

para su intalación, se requiere:

- instalar las librerias necesarias con:
- pip install -r requirements.txt,
- adicional a las librerias se requiere configurar el archivo config.py donde se editara la variable "SQLALCHEMY_DATABASE_URI" de la siguiente forma SQLALCHEMY_DATABASE_URI = "postgresql://username:password@localhost/database_name"
- para poner el servidor en marcha, ejecutar el archivo run.py
