# Airline
# Sistema de Gestión para Aerolíneas

## Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un sistema de gestión para una aerolínea utilizando **Spring Boot** y **Spring Security**. La aplicación permitirá la gestión integral de usuarios, vuelos, reservas y destinos, asegurando una autenticación segura mediante **Basic Auth o JWT**. Entre sus funcionalidades clave, se incluyen la gestión de reservas con validación de disponibilidad y la administración de vuelos con cambios automáticos de estado.

## Tecnologías Utilizadas
- **Java 21**
- **Spring Boot**
- **Spring Security** (Basic Auth o JWT)
- **Maven**
- **MySQL o PostgreSQL**
- **Docker** (opcional)
- **GitHub Actions** (CI/CD)
- **Postman** (para pruebas)

## Objetivos del Proyecto
- Reforzar la creación de APIs con Spring Boot.
- Implementar relaciones en bases de datos relacionales.
- Aplicar autenticación segura con Spring Security.
- Optimizar la gestión de vuelos y reservas.

## Requisitos Funcionales
### **Gestión de Clientes**
- Registro, autenticación y manejo de roles (**ROLE_ADMIN** y **ROLE_USER**).
- Generación y validación de tokens **JWT** o uso de **Basic Auth**.
- Carga de imagen de perfil (con opción por defecto si no se proporciona).
- Consulta de historial de reservas.

### **Gestión de Vuelos**
- Creación automática de vuelos en la base de datos al momento de la compilación.
- Cambio de estado de "disponible" a "false" cuando no haya plazas o la fecha haya expirado.

### **Buscador de Vuelos**
- Búsqueda por aeropuerto de salida y destino.
- Filtrado por fecha y cantidad de plazas disponibles.

### **Gestión de Reservas**
- Verificación de disponibilidad antes de confirmar una reserva.
- Bloqueo de plazas durante **15 minutos** para evitar sobreventas.

### **Funciones para ADMIN (ROLE_ADMIN)**
- CRUD de aeropuertos y trayectos de vuelos.
- Listado resumido de reservas de clientes.

### **Funciones para CLIENTE (ROLE_USER)**
- Registro e inicio de sesión.
- Consulta de historial de reservas.
- Imposibilidad de reservar sin haber iniciado sesión.

### **Gestión de Excepciones**
- Manejo personalizado de errores y excepciones.

## Requisitos No Funcionales
- **Seguridad:** Implementación de **Spring Security** con **Basic Auth o JWT**.
- **Rendimiento:** Optimizaciones en validación de reservas y cambio de estado de vuelos.
- **Disponibilidad:** Implementación de pruebas automatizadas para garantizar estabilidad.

## Extras
- **Dockerización** y subida de la imagen a **Docker Hub**.
- **CI/CD** con **GitHub Actions**.
- **Pruebas automatizadas** con **Postman**.

## Requisitos Técnicos
- Conocimientos en **Java y POO**.
- Experiencia con **Spring Boot, Spring Security, Basic Auth y JWT**.
- Manejo de **bases de datos relacionales** y precarga de datos.
- Conocimientos de **Docker y Testing**.

## Entregables Esperados
- Código fuente en **GitHub**.
- Colección de **Postman** con pruebas de la API.
- Documentación de la API (**README, diagramas, listado de endpoints**).
- Presentación del proceso de desarrollo.
- Imagen de la aplicación en **Docker Hub** (opcional).

## Cronograma del Proyecto
- **Inicio:** Martes 07/01/2025
- **Duración:** 4 semanas (1 sprint)
- **Revisión final:** Jueves 30/01/2025 y Viernes 31/01/2025
- **Entrega:** 31/01/2025

## Competencias a Desarrollar
- Gestión de proyectos con **metodologías ágiles**.
- Desarrollo de APIs con **Spring Boot**.
- Administración de bases de datos.
- Creación y ejecución de pruebas automatizadas.

---


