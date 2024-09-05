# Documentación del Proyecto JPA

## Introducción y Conceptos

Este proyecto utiliza Java Persistence API (JPA) para gestionar la persistencia de datos en una base de datos relacional. JPA es una especificación de Java para el mapeo de objetos Java a bases de datos relacionales. A través de JPA, se pueden definir entidades, establecer relaciones entre ellas y realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar).

## Creación de Entidades

En JPA, una entidad es una clase que representa una tabla en la base de datos. Cada instancia de la entidad corresponde a una fila en la tabla. Las entidades se definen utilizando la anotación `@Entity`.

## Introducción a Relaciones de Base de Datos

JPA permite definir relaciones entre entidades utilizando varias anotaciones. A continuación se describen los tipos más comunes de relaciones:

- @OneToOne unidireccional y bidireccional

- @ManyToOne unidireccional y bidireccional

- @OneToMany unidireccional

-@OneToMany bidireccional

- @ManyToMany unidireccional y bidireccional

# Ejecución del Programa

Este documento proporciona instrucciones sobre cómo ejecutar el programa JPA que hemos desarrollado.

## Requisitos Previos

Antes de ejecutar el programa, asegúrate de tener instalados los siguientes componentes:

- **Java Development Kit (JDK)**: Asegúrate de tener JDK 8 o superior instalado. Puedes verificar tu versión de Java con el comando:
  ```bash
  java -version
-**Maven**: Para gestionar las dependencias y construir el proyecto. Puedes verificar tu versión de Maven con el comando:
  ```bash
  mvn -v



