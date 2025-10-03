## 🧭 Eureka Server - Arka Platform

Este microservicio actúa como **servidor de registro y descubrimiento de servicios** para la plataforma Arka. Está construido con **Spring Cloud Netflix Eureka Server** y permite que los microservicios del ecosistema se registren y se descubran dinámicamente entre sí.

Actualmente se ha implementado Config Client permitiendo así **consumir su configuración desde un Config Server externo**, obteniendo sus **propiedades de configuración definidas en un archivo llamado `eureka-server.yml`** ubicado en el repositorio privado gestionado por Config Server

Cuenta con soporte para **autenticación básica HTTP (Basic Auth)** mediante **Spring Security**, lo que permite restringir el acceso a los endpoints expuestos por Eureka.

---

## 🚀 Características

⚙️ Obtiene su configuración mediante Config Server.  
🔐 Incluye autenticación básica HTTP con Spring Security.  
🧭 Permite el **descubrimiento dinámico** de servicios registrados.  
📡 Expone endpoints de monitoreo y estado a través de **Spring Boot Actuator**.  
🛠️ Preparado para integrarse con servicios como Gateway, IAM, Notification, entre otros.

---

## 🧩 Tecnologías usadas

- Java 17
- Spring Boot 3.x
- Spring Web
- Spring Cloud Eureka Server
- Spring Cloud Config Client
- Spring Security (Basic Auth)
- Spring Boot Actuator

---

📌 Versión actual: `v1.0.0`
