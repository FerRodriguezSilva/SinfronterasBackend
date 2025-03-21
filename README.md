# SinfronterasBackend
Proyecto: [Nombre del Proyecto]

Este repositorio contiene una aplicación basada en Java (Spring Boot) para el backend, Angular para el frontend, Maven para la gestión de dependencias, y MySQL como base de datos.

Tecnologías utilizadas

Backend:

Java (Spring Boot)

Maven (Gestor de dependencias)

Spring Data JPA (Para manejo de base de datos)

Spring Security (Opcional, para autenticación y autorización)

Lombok (Para reducir código boilerplate)

Frontend:

Angular

Angular Material / Bootstrap (Opcional, para estilos y componentes UI)

RxJS (Para manejo de peticiones asíncronas)

Base de Datos:

MySQL


Instalación y Configuración

Prerrequisitos

Asegúrate de tener instalados los siguientes programas:

Java 17+

Maven

Node.js & npm

MySQL Server

Configuración del Backend

Clona el repositorio:

git clone https://github.com/usuario/proyecto.git
cd proyecto/backend

Configura la base de datos en application.properties o application.yml:

spring.datasource.url=jdbc:mysql://localhost:3306/nombre_bd
spring.datasource.username=usuario
spring.datasource.password=contraseña
spring.jpa.hibernate.ddl-auto=update

Ejecuta la aplicación:

mvn spring-boot:run

Configuración del Frontend

Accede a la carpeta del frontend:

cd frontend

Instala las dependencias:

npm install

Ejecuta la aplicación en modo desarrollo:

ng serve

Accede a la aplicación en el navegador:

http://localhost:4200

Endpoints API

Algunos de los principales endpoints disponibles:

Método

Ruta

Descripción

GET

/api/entidades

Obtener todas

GET

/api/entidades/{id}

Obtener por ID

POST

/api/entidades

Crear nueva

PUT

/api/entidades/{id}

Actualizar por ID

DELETE

/api/entidades/{id}

Eliminar por ID

Contribución

Haz un fork del repositorio.

Crea una nueva rama con tu funcionalidad:

git checkout -b feature/nueva-funcionalidad

Realiza cambios y haz commit:

git commit -m "Agregada nueva funcionalidad"

Sube los cambios a tu fork:

git push origin feature/nueva-funcionalidad

Crea un Pull Request en GitHub.