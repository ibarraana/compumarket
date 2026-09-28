# Proyecto BackEnd

### Información del proyecto
---

Este proyecto BackEnd esta realizado con las siguientes tecnologias:

* **Express:** *Libreria de JavaScript*
* **Sequelize:** *ORM (Mapeo de Objetos Relacionales), se encarga de hacer el mapeo de las tablas de la base de datos con los modelos del proyecto*
* **NodeJS:** *Entorno de ejecución de JavaScript*
* **MySQL:** *Base de datos*

### Pasos de ejecución del proyecto
---

Primero, para poder ejecutar este proyecto BackEnd en el Visual Studio Code, debemos navegar hacia esta carpeta cuyo nombre es "Back"

```cmd
cd ./back
```
Una posicionado sobre la carpeta del proyecto, debemos escribir el siguiente comando para instalar todas las dependencias sobre el proyecto, asi pueda ejecutarse el mismo, para ello escribimos el siguiente comando:

```cmd
npm install
```

Hecho esto, el siguiente paso es abrir el motor de base de datos de MySQL, y crear la base de datos, para ello, en la carpeta cuyo nombre es "bases de datos", se debe ejecutar el script.sql sobre el motor, que contiene los siguientes comandos de SQL:

```sql
DROP DATABASE IF EXISTS ecommerce1;
CREATE DATABASE IF NOT EXISTS ecommerce1;
```

Ahora, lo que sigue es crear y agregar datos ficticios en las tablas de la base de datos, para hacer esto, en el Visual Studio Code, sobre la terminal, ejecutar el siguiente comando, al hacerlo se ejecutan los scripts de seeders que estan dentro del proyecto

```cmd
npm run seed
```

Una vez que se ha ejecutado el comando, procedemos a levantar todo el proyecto, que se ejecute el servidor, para ello escribimos este nuevo comando

```cmd
npm run dev
```

El proyecto esta corriendo, en caso de que necesiten detener el proyecto, presionamos las siguientes combinacion de teclas sobre la terminal del Visual Studio Code donde estamos escribiendo los comandos

```cmd
Ctrl+C
```


