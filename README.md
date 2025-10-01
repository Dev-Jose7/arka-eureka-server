## 🧭 Eureka Server - Arka Platform

Este microservicio actúa como **servidor de registro y descubrimiento de servicios** para la plataforma Arka. Está construido con **Spring Cloud Netflix Eureka Server** y permite que los microservicios del ecosistema se registren y se descubran dinámicamente entre sí.

El Eureka Server está configurado para obtener sus propiedades de forma remota desde el **Config Server de la plataforma**, permitiendo así una administración centralizada de la configuración.

---

## 🚀 Características

🔗 Se conecta al **Config Server** para obtener su configuración (`application.yml`) de manera externa y versionada.  
🧭 Permite el **descubrimiento dinámico** de servicios registrados.  
📡 Expone endpoints de monitoreo y estado a través de **Spring Boot Actuator**.  
🛠️ Preparado para ser integrado con servicios como Gateway, IAM, Notification, entre otros.  
⚙️ Configuración flexible y centralizada por entorno y perfil.

---

## ⚠️ Microservicio aún en desarrollo

Este proyecto se encuentra en una etapa **inicial de desarrollo (`v0.1.0-alpha`)**. Su comportamiento, estructura y configuración pueden cambiar con frecuencia. **No se recomienda su uso en producción** por el momento.

---

📌 Versión actual: `v0.1.0-alpha`

