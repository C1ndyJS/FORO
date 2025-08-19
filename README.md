<p align="center">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Java-17+-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Maven-4.0.0-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="JWT"/>
  <img src="https://img.shields.io/badge/Lombok-EA3323?style=for-the-badge&logo=lombok&logoColor=white" alt="Lombok"/>
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security"/>
  <img src="https://img.shields.io/badge/Flyway-0092CA?style=for-the-badge&logo=flyway&logoColor=white" alt="Flyway"/>
  <img src="https://img.shields.io/badge/Validation-FFB300?style=for-the-badge" alt="Validation"/>
</p>

<h1 align="center">🟢 Foro Hub API 📝</h1>
<p align="center">
  <em>Una API REST de foros construida con Spring Boot, MySQL y JWT.<br>
  Proyecto desarrollado para <b>Alura Latam ONE (Oracle Next Education)</b>.</em>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original-wordmark.svg" alt="Spring Logo" width="90"/>
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="Spring animation" width="120"/>
</p>
<p align="center"><b>Cindy Jiménez</b></p>

---

## 🚀 ¿Cómo funciona?

Foro Hub simula un foro real, permitiendo:
- 🔐 **Inicio de sesión** (autenticación JWT)
- 📄 **CRUD de tópicos**: crear, consultar, actualizar y eliminación lógica (soft delete)
- 🗄️ **Persistencia en MySQL**
- 👤 Visualización del autor en cada acción

La API está protegida: solo usuarios autenticados pueden acceder a los endpoints de tópicos.

---

## 🛠️ Tecnologías usadas

<p align="center">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Java-17+-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Maven-4.0.0-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="JWT"/>
  <img src="https://img.shields.io/badge/Lombok-EA3323?style=for-the-badge&logo=lombok&logoColor=white" alt="Lombok"/>
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security"/>
  <img src="https://img.shields.io/badge/Flyway-0092CA?style=for-the-badge&logo=flyway&logoColor=white" alt="Flyway"/>
  <img src="https://img.shields.io/badge/Validation-FFB300?style=for-the-badge" alt="Validation"/>
</p>

---

## 📝 Instalación

1. 📦 Clona el repositorio:
   ```bash
   git clone https://github.com/C1ndyJS/FORO.git
   ```
2. 💻 Abre el proyecto en tu IDE favorito.
3. ⚙️ Instala las dependencias con Maven (`pom.xml`).
4. 🗂️ Configura la conexión en `application.properties` (DB, JWT secret, etc).
5. ▶️ Ejecuta el proyecto.

### 🔧 Dependencias recomendadas (Spring Initializr)

- Lombok
- Spring Web
- Spring Boot DevTools
- Spring Security
- Flyway
- MySQL Driver
- Validation

---

## 🛤️ Migraciones

- Las migraciones SQL (tablas, constraints, seeds) están en la carpeta `src/main/resources/db/migration/`.
- Usa Flyway para versionar y aplicar los cambios en tu base de datos automáticamente.
- Pausa el servidor antes de añadir o modificar archivos `.sql`.

---

## 📬 Endpoints principales

| Método | Ruta                  | Descripción                        | Requiere JWT |
|--------|-----------------------|------------------------------------|:------------:|
| POST   | /login                | Iniciar sesión                     |      ❌      |
| POST   | /topicos              | Crear tópico                       |      ✅      |
| GET    | /topicos              | Listar todos los tópicos           |      ✅      |
| GET    | /topicos/{id}         | Ver detalle de un tópico           |      ✅      |
| PUT    | /topicos/{id}         | Actualizar un tópico               |      ✅      |
| DELETE | /topicos/{id}         | Eliminar (lógico) un tópico        |      ✅      |

> Puedes probar la API con [Insomnia](https://insomnia.rest/) o [Postman](https://www.postman.com/).

---

## 💡 Características

- ✅ API REST siguiendo buenas prácticas
- ✅ Validaciones de reglas de negocio
- ✅ Persistencia en base de datos relacional
- ✅ Autenticación y autorización con JWT
- ✅ Eliminación lógica para integridad y auditoría

---

## 🖼️ Vista conceptual

<p align="center">
  <img src="https://raw.githubusercontent.com/spring-projects/spring-petclinic/main/docs/images/spring-petclinic-rest.png" width="550" alt="Spring REST Concept"/>
</p>

---

## 👩‍💻 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/cindy-jimenez-s/)
[![GitHub](https://img.shields.io/badge/GitHub-333?style=flat&logo=github)](https://github.com/C1ndyJS)

---

## 🏆 Créditos

Este proyecto es complementario con **LiterAlura** y parte de **Oracle Next Education - Alura Latam**.

---
