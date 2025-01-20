# ForoHub API

ForoHub API es una aplicación RESTful desarrollada en Java que permite gestionar tópicos de foros, ofreciendo funcionalidades para autenticar usuarios y realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre los tópicos. Esta API es ideal para integrar sistemas de discusión o foros en plataformas web o móviles.

---

## 📋 Características

- **Gestión de Tópicos**: 
  - Crear nuevos tópicos.
  - Listar todos los tópicos.
  - Buscar un tópico por ID.
  - Actualizar información de un tópico.
  - Eliminar tópicos existentes.

- **Autenticación mediante API**: 
  - Login seguro para usuarios con generación de tokens JWT.
  - Acceso protegido a las funcionalidades CRUD mediante autenticación.

---

## 📂 Estructura del Proyecto

La aplicación está desarrollada siguiendo las mejores prácticas de diseño de software utilizando Spring Boot:

- **`api.alura.forohub`**: Paquete principal del proyecto.
- **`infra.security`**: Contiene la configuración de seguridad y manejo de tokens JWT.
- **`controllers`**: Manejo de las solicitudes REST.
- **`services`**: Contiene la lógica de negocio.
- **`repositories`**: Interacción con la base de datos.
- **`models`**: Definición de las entidades de la base de datos.

---

## 🚀 Tecnologías Utilizadas

- **Java 21**
- **Spring Boot 3**
- **JWT (JSON Web Token)** para autenticación.
- **H2 Database** (Base de datos en memoria, configurable a otras bases como PostgreSQL o MySQL).
- **Maven** para gestión de dependencias.
- **Lombok** para simplificación del código.

---

## 🛠️ Instalación y Configuración

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tuusuario/forohub-api.git
   cd forohub-api
