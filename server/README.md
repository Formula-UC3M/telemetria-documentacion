![header](.osweekends/img/OSW-project-GitHub-template-header.jpg)

![travis](https://img.shields.io/travis/OSWeekends/formula-uc3m.svg)
![issues abiertos](https://img.shields.io/github/issues/OSWeekends/formula-uc3m.svg)
![issues promedio](https://img.shields.io/issuestats/i/github/OSWeekends/formula-uc3m.svg)
![PR Abiertos](https://img.shields.io/github/issues-pr/OSWeekends/formula-uc3m.svg)
![PR Promedio](https://img.shields.io/issuestats/p/github/OSWeekends/formula-uc3m.svg)
![último commit](https://img.shields.io/github/last-commit/OSWeekends/formula-uc3m/master.svg)
![TOP Lang](https://img.shields.io/github/languages/top/OSWeekends/formula-uc3m.svg)
![total lang](https://img.shields.io/github/languages/count/OSWeekends/formula-uc3m.svg)

# Fórmula UC3M - Servidor para guardado y explotación de datos en tiempo real.

> Proyecto para la realización de la telemetría al monoplaza de la UC3M. Dentro del proyecto, esta parte se encargará de la gestión del guardado y explotación de datos, en tiempo real.

![Logo de {{proyecto}}](.osweekends/img/fuc3m-logo.png)

# Tecnologías

- [**Node JS**](https://nodejs.org/en/): Entorno de ejecución de Javascript que funciona sobre el motor v8 de Google Chrome.
- [**MongoDB**](https://www.mongodb.com/es): Almacenamiento de datos para consulta en tiempo real.
    * [**Mongoose**](http://mongoosejs.com/): ODM ([Object Document Mapper](https://stackoverflow.com/questions/12261866/what-is-the-difference-between-an-orm-and-an-odm)) para MongoDB.
- [**Mosca**](https://github.com/mcollina/mosca/wiki): Broker [MQTT](https://geekytheory.com/que-es-mqtt) para [Node JS](https://nodejs.org/en/).
- [**Pillars**](http://pillarsjs.com/): Framework de desarrollo web para Node.js.

# Instalación

Primero clona este repositorio:

```shell
git clone git@github.com:OSWeekends/formula-uc3m.git
```

Es necesario recordar que debes de tener instalado en tu ordenador MongoDB, Node JS y NPM (Gestor de paquetes de Node JS) antes de empezar a instalar este proyecto.
Una vez clonado puedes entrar a la carpeta `./server` y ejecutar el siguiente comando:

```shell
npm install
```

Una vez realizado esto ya deberían estar instaladas todas las dependencias de este paquete. Ahora debes copiar el fichero `.env.example` y crear un fichero `.env`, dentro debes sustituir la configuración de ejemplo por la de tu base de datos.

Una ver realizado esto ya estaría completamente instalado y listo para arrancar (recuerda arrancar el servidor de base de datos antes de arrancar este servidor).

**Iniciar el servidor**

```shell
npm start
```

# Equipo

De la creación y gestión del servidor de datos en tiempo real se encargará el equipo ArduData.

**Equipo ArduData**
- [Javier Gallego (@bifuer)](https://github.com/bifuer) (lider ArduData) Fullstack
- [Sebastián Cabanas (@Sediug)](https://github.com/Sediug) (lider ArduData) Fullstack
- Todos los que quieran colaborar PR con su info sustituyendo este mensage :P