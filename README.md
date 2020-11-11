# API REST con JWT 
Pasos:
1. clonar este repositorio.
2. Ejecutar el siguiente comando para la instalación de todos los paquetes:
  ```
  npm install
  ```
3. Modificar la variables de entorno.
4. Ejecutar el siguiente código en MySql:
  ```
  CREATE DATABASE test;
  USE test;
  DROP TABLE IF EXISTS `registration_user`;
  CREATE TABLE IF NOT EXISTS `registration_user` (
    `nombre` varchar(50) NOT NULL,
    `apellido` varchar(50) NOT NULL,
    `genero` varchar(2) NOT NULL,
    `email` varchar(100) NOT NULL,
    `password` varchar(1000) NOT NULL,
    `numero` float NOT NULL,
    `id` int(11) NOT NULL AUTO_INCREMENT,
    PRIMARY KEY (`id`)
  ) ENGINE=InnoDB AUTO_INCREMENT=5 DEFAULT CHARSET=latin1;
  ```
