<div align="center">

# Hola, soy Jorge Ruiz 👋
### Backend Developer (Java · Spring Boot) & Android Developer (Kotlin · Jetpack Compose)

Construyo aplicaciones completas de punta a punta: APIs REST robustas, apps Android nativas y frontends web conectados a esas APIs. Me enfoco en arquitectura limpia, código mantenible y sistemas que resuelven problemas de negocio reales.

📍 Lima, Perú &nbsp;·&nbsp; ✉️ [jorgeruiztapia0218@gmail.com](mailto:jorgeruiztapia0218@gmail.com) &nbsp;·&nbsp; 🌐 [Portafolio](https://jorgeruiz20.github.io/Portafolio/)

[![Portafolio](https://img.shields.io/badge/Portafolio-Visitar-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://jorgeruiz20.github.io/Portafolio/)
[![Email](https://img.shields.io/badge/Email-Contactarme-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jorgeruiztapia0218@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-JorgeRuiz20-181717?style=for-the-badge&logo=github)](https://github.com/JorgeRuiz20)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3&section=header" width="100%" />

## 🚀 Sobre mí

Soy desarrollador de software con doble especialización: **Backend con Java + Spring Boot** y **desarrollo Android con Kotlin + Jetpack Compose**. Trabajo cómodo en todo el ciclo de un producto: diseño de la lógica de negocio, construcción de APIs REST, persistencia de datos, integración de servicios externos (Firebase, notificaciones push, generación de reportes) y despliegue en contenedores.

Los proyectos de este perfil no son ejercicios sueltos: cada uno simula un sistema real con roles de usuario, reglas de negocio y flujos completos — desde una app Android offline-first para talleres de motos hasta una plataforma de torneos con motor de brackets y caché en memoria.

**Actualmente enfocado en:**

`Clean Architecture` · `Spring Boot` · `Kotlin & Jetpack Compose` · `APIs REST` · `Docker` · `Bases de datos relacionales y NoSQL` · `Testing`

---

## 🛠️ Stack Tecnológico

<table>
<tr>
<td valign="top" width="50%">

**☕ Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

Java · Spring Boot · Spring Security · Spring Data JPA · Hibernate · JWT · REST API · Maven · JUnit · Swagger/OpenAPI

**📱 Android**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

Kotlin · Jetpack Compose · Material 3 · MVI · MVVM · Clean Architecture · Room · Retrofit · Hilt · Firebase (Firestore, Auth, FCM)

</td>
<td valign="top" width="50%">

**🌐 Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

React · JavaScript · HTML5 · CSS3 · Bootstrap 5 · Vite · Axios · React Router

**🗄️ Bases de datos**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)

MySQL · Firebase Firestore · Room (SQLite)

**🐳 DevOps & Herramientas**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

Docker (multi-stage builds) · Git & GitHub · Nginx · Render · Postman

</td>
</tr>
</table>

---

## ⭐ Proyectos Destacados

<br>

### 📱 MotoStock — App Android de gestión de taller mecánico
![Proyecto Principal](https://img.shields.io/badge/★-Proyecto_Principal-FFC107?style=flat-square)

**Sistema de gestión integral para talleres de motocicletas**, con tres roles (Administrador, Mecánico, Cliente) que cubre todo el flujo: citas, inventario, historial de servicios y notificaciones en tiempo real.

- 🏗️ **Clean Architecture multi-módulo** con patrón **MVI** (Model-View-Intent) y flujo de datos unidireccional
- 📡 Estrategia **Offline-First**: Room como fuente única de verdad, sincronizada en segundo plano con Firestore
- 🔐 Autenticación multi-rol con Firebase Auth + Google Sign-In, e instancias secundarias aisladas de Firebase para creación segura de cuentas
- 📦 Descuento atómico de inventario al finalizar un servicio, con alertas automáticas de stock bajo
- 📲 Notificaciones push segmentadas por canal (citas / stock) vía Firebase Cloud Messaging
- 🎨 Interfaz 100% declarativa en Jetpack Compose + Material 3, inyección de dependencias con Hilt

**Stack:** Kotlin · Jetpack Compose · Room · Firebase (Firestore, Auth, FCM) · Hilt · Retrofit · Coroutines

🔗 [Ver repositorio](https://github.com/JorgeRuiz20/MotoStockv2)

<br>

<details open>
<summary><h3 style="display:inline">🤖 RoboTech — Plataforma de gestión de torneos de robótica</h3></summary>
<br>

**Sistema Full Stack** para organizar competencias de robótica: desde la inscripción de clubes y homologación técnica de robots hasta la generación automática de brackets y rankings en vivo.

- 🔐 Control de acceso basado en 5 roles (`RBAC`) con Spring Security + JWT
- 🏆 Motor de torneos con dos modalidades (eliminatoria directa y todos-contra-todos), generación automática de llaves y avance de fases
- ⚡ **Caché en memoria con Caffeine** (TTL de 5s) para servir rankings en tiempo real sin saturar la base de datos
- 🔍 Sistema anti-duplicados con algoritmo de similitud **Jaro-Winkler** para detectar registros repetidos o typos
- 📄 Generación de reportes PDF con **iText 7**, apoyada en vistas SQL pre-agregadas para respuestas en milisegundos
- ⏰ Automatización de torneos programados mediante tareas Cron (`Scheduler`)
- 📚 API documentada con Swagger / OpenAPI 3

**Stack Backend:** Java 17 · Spring Boot 3 · Spring Security · JWT · MySQL · Hibernate · Caffeine Cache · iText 7  
**Stack Frontend:** React 19 · Vite · React Router · Axios

🔗 [Backend](https://github.com/JorgeRuiz20/BackendRobotech) &nbsp;·&nbsp; 🔗 [Frontend](https://github.com/JorgeRuiz20/FrontendRobotech)

</details>

<br>

<details open>
<summary><h3 style="display:inline">🚗 CarWash — Sistema de gestión para lavado de vehículos</h3></summary>
<br>

**Plataforma Full Stack** para digitalizar la operación de un negocio de carwash: clientes, vehículos, servicios, reservas, caja y fidelización, expuesta a través de una API REST securizada con JWT.

- 🔐 Autenticación y control de acceso con Spring Security + JWT
- 🧾 Módulos de negocio completos: reservas, pagos/caja, cupones y sistema de fidelización de clientes
- 📄 Generación de reportes con iText y Apache POI (PDF / Excel)
- 🐳 Backend contenerizado y listo para despliegue en la nube

**Stack Backend:** Java 17 · Spring Boot 3 · Spring Security · JWT · MySQL · Hibernate · iText · Apache POI  
**Stack Frontend:** React 18 · Vite · Axios · React Router

🔗 [Backend](https://github.com/JorgeRuiz20/BackendCarwash) &nbsp;·&nbsp; 🔗 [Frontend](https://github.com/JorgeRuiz20/FrontendCarwash)

</details>

<br>

<details open>
<summary><h3 style="display:inline">🚕 RinRed (Explora Cusco) — Plataforma de transporte y viajes</h3></summary>
<br>

**Aplicación web** para solicitar y gestionar viajes de taxi en Cusco, Perú: asignación de conductores, seguimiento de estado del viaje y ficha de confianza del conductor antes de abordar.

- 🚖 Asignación dinámica de conductores (manual o aleatoria automática, con conductor de contingencia si no hay disponibles)
- 📍 Consulta de viajes pendientes/finalizados indexada por DNI, sin necesidad de registro
- ❤️ Endpoint de **Health Check** listo para monitoreo en plataformas PaaS
- 🐳 Despliegue con Docker multi-stage (build con Maven + runtime JRE Alpine) para imágenes ligeras
- 🌐 CORS abierto, preparado para ser consumido desde web, apps móviles o herramientas de testing

**Stack Backend:** Java 21 · Spring Boot 3.5 · Spring Data JPA · Hibernate · MySQL  
**Stack Frontend:** HTML5 · CSS3 · JavaScript · Bootstrap 5 · Docker + Nginx

🔗 [Backend](https://github.com/JorgeRuiz20/BackendRinRed) &nbsp;·&nbsp; 🔗 [Frontend](https://github.com/JorgeRuiz20/FrontendRinRed)

</details>

---

## 🏗️ Mi enfoque de desarrollo

<div align="center">

| Paso | Qué hago |
|:---:|---|
| 💡 | **Entender el problema** — antes de escribir código, defino roles, reglas de negocio y flujos reales |
| 🏗️ | **Diseñar el backend** — Java + Spring Boot, con arquitectura por capas y reglas bien probadas |
| 🌐 | **Exponer una API REST** — punto único de verdad que consume cualquier cliente |
| 📱 | **Construir la interfaz** — React (web) o Kotlin + Jetpack Compose (Android), desacoplada del backend |
| 🗄️ | **Persistir los datos** — MySQL o Firebase, según lo que el proyecto necesite |
| 🐳 | **Empaquetar y desplegar** — Docker y despliegue en la nube, listo para producción |

</div>

Sea cual sea el proyecto, sigo el mismo principio: **entender el problema de negocio primero**, diseñar un backend con reglas claras y bien probadas, y luego construir la interfaz (web o Android) que consuma esa lógica de forma desacoplada.

---

## 📊 Actividad en GitHub

<div align="center">

<a href="https://github.com/JorgeRuiz20">
<img height="165" src="https://github-stats-extended.vercel.app/api?username=JorgeRuiz20&show_icons=true&theme=tokyonight&hide_border=true" alt="Estadísticas de GitHub de Jorge Ruiz" />
</a>
<a href="https://github.com/JorgeRuiz20">
<img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=JorgeRuiz20&layout=compact&theme=tokyonight&hide_border=true" alt="Lenguajes más usados por Jorge Ruiz" />
</a>

</div>

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3&section=footer" width="100%" />

<div align="center">

### 📬 ¿Buscas un desarrollador Backend / Android para tu equipo?

Estoy abierto a oportunidades. Puedes revisar el detalle de mis proyectos en mi [portafolio](https://jorgeruiz20.github.io/Portafolio/) o escribirme directamente a **[jorgeruiztapia0218@gmail.com](mailto:jorgeruiztapia0218@gmail.com)**.

⭐ Gracias por visitar mi perfil.

</div>
