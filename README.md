# ParcialBackend
parcial reservas coworking

Este proyecto permite a los usuarios reservar espacios de coworking, ver la lista de reservas y eliminar reservas existentes.

## Funcionalidades
- Reserva de espacios.
- Listado de reservas.
- Eliminación de reservas.

## Requisitos
- Java 17
- Apache Tomcat 10.x
- Maven 3.8.x

## Despliegue
1. Clonar el repositorio.
2. Compilar el proyecto con Maven.
3. Desplegar el archivo WAR en Tomcat.
4. Acceder a la aplicación en `http://localhost:8080/ProyectoReservaCoworking/index.html`

##informe
Durante el desarrollo del proyecto, se implementaron las siguientes funcionalidades:

Proceso de reserva: Los usuarios pueden realizar reservas mediante un formulario.
Lista de reservas: Se muestra una lista de todas las reservas realizadas.
Eliminación de reservas: Los usuarios pueden eliminar reservas específicas.
Validación y manejo de errores: Se valida que todos los campos del formulario estén completos y se maneja cualquier error de entrada.
Despliegue en Tomcat: El proyecto se despliega correctamente en el servidor Tomcat.

##Desafíos Encontrados
Configuración de Maven: Se resolvieron problemas relacionados con la configuración de Maven y la compatibilidad de versiones.
Errores de despliegue en Tomcat: Se solucionaron conflictos en el mapeo de servlets y problemas de permisos.
