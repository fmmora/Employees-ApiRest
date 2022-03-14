# Kruger-Test
# Tecnología utilizada
  - Java 11
  - IDE Sprint Tool Suite Versión: 4.10.0.RELEASE
  -Spring Boot Version 2.4.4
  -Datos de la api
    - Nombre: service-empleado
    - Puerto: 8080
    - Url documentación OpenApi: http://localhost:8080/swagger-ui.html (Se podra visualizar al ejecutar el microservicio)
    - Metodos: Get, Post, Put, Delete
    - Se utiliza el servidor tomcat embebido
  - Base de DatosPostgreSql 13
    - User: postgres
    - Password: sasa
    - Nombre de la base de datos: db_kruger (Se debe crear la base de datos antes de levantar el microservicio)

# Consideraciones para la ejecución
   - Descargar el fuente de la rama master (git pull)
   - Crear la base de datos db_kruger
   - Importar el proyecto en el IDE
   - Click derecho sobre el proyecto y seleccionar Run ass -> Spring Boot App
   - Se podra encontrar los endpoints y ejemplos del request en la url http://localhost:8080/swagger-ui.html
   - Se deberan crear los empleados, ya que no contiene registros inicialmente.
   - Si detiene el microservicio, se eliminara toda la informacion en la base de datos db_kruger
