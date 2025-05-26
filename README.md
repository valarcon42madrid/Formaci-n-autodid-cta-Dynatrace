Esta serie de talleres tiene como objetivo introducir y demostrar el uso de Dynatrace, una plataforma de observabilidad e inteligencia automática, aplicada a diferentes entornos de TI. Los ejercicios están diseñados para simular escenarios reales de monitoreo, seguridad y automatización, utilizando herramientas modernas como Docker, Terraform y AWS.

Antes de comenzar obten un período de prueba gratuito. Si ya se ha gastado puedes usar servicios de email temporal (https://temp-mail.org/es/) o crear una nueva cuenta de correo.

## 🧪 Taller 1 – Introducción con Docker + OneAgent
Enfoque:
Monitoreo básico de una aplicación local.
Se instala Dynatrace OneAgent y se despliega una aplicación web sencilla para observar métricas de rendimiento en tiempo real.

Beneficio clave:
Aprender cómo se conecta Dynatrace a los procesos en ejecución y cómo detecta automáticamente servicios y componentes en contenedores. Ideal para probar a hacer dashboards en DQL (Solicitudes por minuto, Tiempos de respuesta, Errores HTTP).


https://github.com/valarcon42madrid/Dynatrace-t1



## 🔐 Taller 2 – Seguridad en Aplicaciones Java (AppSec)
Enfoque:
Simulación de una vulnerabilidad real (Log4Shell) dentro de una aplicación Java.
Dynatrace OneAgent se integra directamente en la app para mostrar cómo se detectan componentes vulnerables y ejecuciones riesgosas en tiempo de ejecución.

Beneficio clave:
Demostrar la detección automatizada de vulnerabilidades con Dynatrace Application Security y cómo se protegen los entornos sin intervención manual.


https://github.com/valarcon42madrid/Dynatrace-t2



## 🌐 Taller 3 – Synthetic Monitoring desde una red simulada
Enfoque:
Se utiliza un contenedor con ActiveGate para crear una ubicación privada simulada, desde donde se ejecutan monitores sintéticos contra servicios internos de una red Docker.

Beneficio clave:
Visualizar cómo Dynatrace puede simular usuarios finales internos o externos para probar la disponibilidad de servicios, incluso si están en redes privadas.


https://github.com/valarcon42madrid/Dynatrace-t3

## ☁️ Taller 4 – Integración con AWS y Terraform
Enfoque:
Automatización del despliegue de infraestructura en AWS usando Terraform, y su integración con Dynatrace para el monitoreo en la nube.
Se crea un bucket S3 con contenido web y se configura la observabilidad vía API.

Beneficio clave:
Introducir la automatización del monitoreo en la nube, integrando Dynatrace con AWS de forma programada y reproducible.


https://github.com/valarcon42madrid/Dynatrace-t4
