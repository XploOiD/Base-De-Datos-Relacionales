# Bases de Datos Relacionales  
## Material y Ejercicios de Clase

### Descripción General del Repositorio
Este repositorio contiene los materiales, ejemplos y ejercicios de la asignatura **Bases de Datos Relacionales**. 

### Estructura del Repositorio
La estructura del repositorio está organizada por clases.

Bases de Datos Relacionales │ 
    ├── Clase 1 │ 
        ├── 1.png │ 
        └── 2.png |
        └── 3.png |
        └── 4.png |
        └── Ejercicios01.pdf |
    ├── Clase 2 │
        ├── Base de Datos Tabla de Davinci │
### Requisitos Previos
Antes de ejecutar los archivos, asegúrate de tener instalado lo siguiente:
- **MySQL** o **SQLite**.
  - MySQL: [Descargar MySQL](https://dev.mysql.com/downloads/)
  - SQLite: [Descargar SQLite](https://www.sqlite.org/download.html)
- **Cliente SQL** para ejecutar los comandos SQL (puede ser una herramienta como [MySQL Workbench](https://dev.mysql.com/downloads/workbench/) o un cliente de línea de comandos).

### Instrucciones para Clonar y Configurar el Repositorio

1. **Clonar el repositorio:**
   - Abre una terminal o línea de comandos.
   - Ejecuta el siguiente comando para clonar el repositorio:
     ```bash
     git clone https://github.com/XploOiD/Base-De-Datos-Relacionales.git
     ```

2. **Configurar la base de datos:**
   - Crea una base de datos en MySQL o SQLite.
   - En MySQL, puedes usar el siguiente comando:
     ```sql
     CREATE DATABASE nombre_base_datos;
     ```
   - En SQLite, crea un archivo de base de datos con el siguiente comando:
     ```bash
     sqlite3 nombre_base_datos.db
     ```

3. **Ejecutar los scripts SQL:**
   - Para ejecutar los archivos SQL, abre el cliente SQL y carga el archivo correspondiente. Por ejemplo, en MySQL:
     ```bash
     mysql -u root -p nombre_base_datos < Clase_01_Crear_Tablas/crear_tabla.sql
     ```

### Descripción de Ejercicios y Contenido por Clase

- **Clase 1: Relacion entre Tablas**
  - Introducción a las relaciones entre tablas y algunos ejercicios.

### Ejemplos de Uso y Ejecución

Para ejecutar un archivo SQL, abre tu cliente SQL y ejecuta el siguiente comando:

```bash
mysql -u root -p Base de datos relacionales < Clase 1/tabla.sql
```
### Recursos de Apoyo
[Documentación oficial de MySQL](https://dev.mysql.com/doc/)

### Actualizaciones
Este repositorio será actualizado con nuevos ejercicios y materiales en un futuro.