## 🧭 Eureka Server - Arka Platform

Este microservicio actúa como **servidor de registro y descubrimiento de servicios** para la plataforma Arka. Está construido con **Spring Cloud Netflix Eureka Server** y permite que los microservicios del ecosistema se registren y se descubran dinámicamente entre sí.

Actualmente, el Eureka Server **no consume configuración desde un Config Server externo**, sino que utiliza **propiedades locales definidas en su archivo `application.yml`**, facilitando así su despliegue y pruebas en entornos aislados o de desarrollo.

Además, se ha añadido soporte para **autenticación básica HTTP (Basic Auth)** mediante **Spring Security**, lo que permite restringir el acceso a los endpoints expuestos por Eureka.

---

## 🚀 Características

⚙️ Utiliza configuración local mediante `application.yml`.  
🔐 Incluye autenticación básica HTTP con Spring Security.  
🧭 Permite el **descubrimiento dinámico** de servicios registrados.  
📡 Expone endpoints de monitoreo y estado a través de **Spring Boot Actuator**.  
🛠️ Preparado para integrarse con servicios como Gateway, IAM, Notification, entre otros.

---

## ⚠️ Microservicio aún en desarrollo

Este proyecto se encuentra en una etapa de desarrollo activo (`v0.2.0`).  
Su comportamiento, estructura y configuración pueden cambiar con frecuencia.  
**No se recomienda su uso en entornos de producción por el momento.**

---

📌 Versión actual: `v0.2.0`
