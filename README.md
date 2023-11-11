# trabajo_integrador_cac

PHP full stack – Codo a Codo
Trabajo práctico integrador BD
Katherine Alejandra Lujan Quiroz
Comisión 23586
Lun y Mie 19:30 a 21
____________________________________________________________________________________
Crear la base de datos
CREATE DATABASE desafio;
Tabla de oradores
CREATE TABLE `primera_datebase`.`oradores` (`id_orador` INT(11) NOT NULL AUTO_INCREMENT , `nombre` VARCHAR(50) NOT NULL , `apellido` VARCHAR(50) NOT NULL , `email` VARCHAR(100) NOT NULL , `tema` INT(255) NOT NULL , `fecha_alta` DATETIME NOT NULL DEFAULT CURRENT_TIMESTAMP , PRIMARY KEY (`id_orador`)) ENGINE = InnoDB;
Llave primaria para la tabla oradores
PRIMARY KEY (`id_orador`)) ENGINE = InnoDB;
Restricciones correspondientes
Todos los campos son obligatorios 
Insertar 10 registros
INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) VALUES (NULL, 'Pedro', 'Lopez', 'pedro@gmail.com', 'Sobre Javascript', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'Juan', 'Gomez', 'juan@gmail.com', 'Sobre TypeScript', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'María', 'Rodríguez', 'maria@gmail.com', 'Sobre HTML', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'Carlos', 'Martínez', 'carlos@gmail.com', 'Sobre CSS', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, 'apellido', `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'Laura', 'Pérez', 'laura@gmail.com', 'Sobre React', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'Miguel', 'Hernández', 'miguel@gmail.com', 'Sobre Vue.js', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'Ana', 'López', 'ana@gmail.com', 'Sobre Node.js', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'David', 'Ramírez', 'david@gmail.com', 'Sobre Angular', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'Elena', 'Sánchez', 'elena@gmail.com', 'Sobre TypeScript', current_timestamp());

INSERT INTO `oradores` (`id_orador`, `nombre`, `apellido`, `email`, `tema`, `fecha_alta`) 
VALUES (NULL, 'Javier', 'Fernández', 'javier@gmail.com', 'Sobre Web Development', current_timestamp());




