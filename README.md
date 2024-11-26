# DVD Rental Database for SQL Server

Este repositorio contiene la base de datos **DVD Rental** convertida para **SQL Server** en formato `.bak`. Esta conversión fue realizada a partir de la versión original de **PostgreSQL**.

## Descripción

La base de datos DVD Rental es ampliamente utilizada para demostraciones, pruebas y aprendizaje de bases de datos. Incluye datos de ejemplo sobre clientes, películas, actores y transacciones de alquiler, ofreciendo un entorno realista para la práctica de SQL y análisis de datos.

En este repositorio encontrarás:

- Un archivo de respaldo (`.bak`) de la base de datos listo para ser restaurado en SQL Server.
- Instrucciones para la restauración y uso.

## Requisitos

- **SQL Server 2016** o superior.
- **SQL Server Management Studio (SSMS)** para gestionar la restauración.

## Restauración de la Base de Datos

1. Descarga el archivo `DVD_Rental.bak` desde este repositorio.
2. Abre SQL Server Management Studio (SSMS).
3. Conéctate a tu instancia de SQL Server.
4. Haz clic derecho en `Bases de datos` y selecciona `Restaurar base de datos...`.
5. En la ventana de restauración:
   - Selecciona `Dispositivo` y añade el archivo `.bak`.
   - Verifica el nombre de la base de datos objetivo.
   - Revisa las opciones de restauración y ajustes según sea necesario.
6. Haz clic en `Aceptar` para iniciar la restauración.

## Notas de Conversión

La conversión de PostgreSQL a SQL Server incluyó los siguientes ajustes:

- Adaptación de tipos de datos específicos.
- Ajustes en las claves foráneas y restricciones.
- Revisión y modificación de las funciones y procedimientos almacenados, si existían.

Si encuentras algún problema o inconsistencia, por favor, crea un issue en este repositorio.

## Créditos

- **Versión original**: [DVD Rental Database para PostgreSQL](https://www.postgresql.org/ftp/projects/pgFoundry/dbsamples/).
- **Conversión realizada por**: [Tu Nombre o Alias].

## Licencia

Este repositorio sigue los términos de la [licencia original](https://www.postgresql.org/about/licence/). Usa esta base de datos únicamente con fines educativos y de prueba.
