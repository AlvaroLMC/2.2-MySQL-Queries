# 🛠️ Ejercicios de Consultas en Bases de Datos - MySQL

## 📄 Descripción

Este proyecto contiene una serie de ejercicios prácticos para trabajar consultas SQL sobre dos bases de datos diferentes: **Tienda** y **Universidad**. En cada ejercicio se propone trabajar con datos bien estructurados utilizando herramientas como `JOIN`, condiciones, agrupaciones, entre otros conceptos avanzados de SQL.

### 🧩 Ejercicios propuestos:

#### Base de Datos: Tienda
- La base de datos incluye dos tablas: `producto` y `fabricante`.
- El objetivo es realizar consultas como: filtrados, ordenamientos, conversiones de datos, y relaciones entre tablas.

#### Base de Datos: Universidad
- Se plantea trabajar con una base de datos que incluye tablas relacionadas con `alumnos`, `profesores`, `departamentos`, `grados` y `asignaturas`.
- El objetivo es trabajar con operaciones complejas, como jerarquías de relaciones, uniones externas (`LEFT JOIN`, `RIGHT JOIN`), y consultas resumen.

Cada ejercicio está diseñado para poner en práctica conceptos esenciales de SQL, desde lo básico hasta operaciones más avanzadas.

---

## 💻 Tecnologías Utilizadas

El proyecto utiliza únicamente tecnologías relacionadas con bases de datos y sistemas de gestión. Aquí tienes un listado de lo utilizado:

- **MySQL** 8.0 o superior.
- Scripts SQL para definición y manipulación de datos (DDL, DML).
- Herramientas de edición y conexión:
  - MySQL Workbench
  - DBeaver o Navicat *(opcional)*
  - Línea de comandos de MySQL
- Editor de texto para revisar y modificar scripts (por ejemplo, Visual Studio Code).

---

## 📋 Requisitos

Antes de comenzar, asegúrate de cumplir con los siguientes requisitos mínimos:

- Base de datos **MySQL** instalada en tu sistema (versión 8.0 o superior recomendada).
- Una herramienta (Workbench, DBeaver, etc.) para cargar y ejecutar los scripts SQL.
- Acceso a internet para descargar los scripts de este repositorio.
- [Opcional] Un servidor local de bases de datos como **XAMPP** o **WAMP**.

---

## 🛠️ Instalación

Sigue los pasos indicados para instalar el entorno y cargar las bases de datos:

### 1. Clona el repositorio

    ```bash
     git clone https://github.com/AlvaroLMC/2.2-MySQL-Queries.git
     cd 2.2-MySQL-Queries

2. Configura el servidor MySQL

    Inicia tu base de datos local (en XAMPP, WAMP o cualquier otro servidor MySQL).

    Asegúrate de conocer tu usuario (root) y contraseña (por defecto, sin contraseña para root).

3. Carga los esquemas de las bases de datos

- Para cargar la base de datos Tienda:
   ```bash
    mysql -u root -p < schema_tienda.sql
- Para cargar la base de datos Universidad:
   ```bash
    mysql -u root -p < schema_universidad.sql

## ▶️ Ejecución

Una vez cargados los esquemas de las bases de datos, puedes comenzar a ejecutar las consultas propuestas:

  1. Abre tu herramienta favorita, como MySQL Workbench o DBeaver.

  2. Selecciona la base de datos correspondiente con alguno de los siguientes comandos:
     ```bash
    USE tienda;
    USE universidad;

  3. Carga y ejecuta las consultas proporcionadas en los archivos:

  - consultas_tienda.sql → Ejercicios para la base de datos Tienda.

  - consultas_universidad.sql → Ejercicios para la base de datos Universidad.

  4. Inspecciona los resultados en tu herramienta.

  - Cada consulta está diseñada para devolver una salida específica basada en las tablas proporcionadas.

---
