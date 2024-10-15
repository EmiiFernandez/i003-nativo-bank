# Nativo Banco Rural

Nativo es una aplicación financiera diseñada para mitigar los problemas financieros y de accesibilidad en las comunidades rurales. Esta solución integra un sistema de pagos móviles mediante códigos QR y un sistema de microcréditos con tasas bajas, todo adaptado a la conectividad limitada de estas áreas.

🚀 **Objetivo**

Facilitar las transacciones en comunidades rurales a través de una plataforma bancaria simple, segura y eficiente, impulsando la inclusión financiera y mejorando la economía local.

💡 **Problema**

Las comunidades rurales enfrentan grandes barreras para acceder a servicios bancarios, tanto por la falta de infraestructura como por la conectividad limitada. Estas dificultades generan dependencias al uso de efectivo y limitan el acceso a créditos accesibles.

📊 **Datos Clave:**

- Las áreas rurales tienen menos acceso a cajeros automáticos y sucursales bancarias.
- La digitalización financiera en zonas rurales es casi inexistente.
- La falta de acceso a créditos asequibles impide el crecimiento económico local.

🔧 **Solución**

Nativo ofrece una plataforma accesible que permite:
- **Pagos con QR**: Los usuarios pueden realizar pagos de manera sencilla sin depender de efectivo.
- **Microcréditos**: Sistema de microcréditos con tasas bajas para fomentar el desarrollo económico local.
- **Donaciones**: Facilita la creación de campañas de donación dentro de la comunidad.
- **Integración con comercios locales**: Incentivos tanto para comerciantes como para usuarios.

🌐 **Impacto**

Con Nativo, buscamos:
- Reducir la dependencia de cajeros automáticos y dinero en efectivo.
- Fomentar la inclusión financiera en comunidades rurales.
- Aportar al crecimiento económico local mediante servicios financieros accesibles y adaptados.

🔐 **Seguridad**

La plataforma cuenta con sistemas de autenticación robustos y cifrado de datos para garantizar la protección de la información personal de los usuarios y prevenir fraudes.

🏗️ **Arquitectura y Diseño**

### Frontend
- **Despliegue**: [https://nativo.netlify.app/](https://nativo.netlify.app/)
- **Repositorio**: [https://github.com/igrowker/i003-nativo-front](https://github.com/igrowker/i003-nativo-front)
- **Tecnologías**: React

### Backend Microcréditos (Spring Boot)
- **Despliegue**: [https://i003-nativo-back-production.up.railway.app/swagger-ui/index.html](https://i003-nativo-back-production.up.railway.app/swagger-ui/index.html)
- **Repositorio**: [https://github.com/igrowker/i003-nativo-back](https://github.com/igrowker/i003-nativo-back)
- **Tecnologías**: Java, Spring Boot, PostgreSQL, JWT, Swagger, Docker, Railway, JUnit

📚 **Funcionalidades**

- **Usuarios**: Autenticación y gestión de perfiles mediante JWT.
- **Microcréditos**: Solicitud y gestión de microcréditos.
- **Pagos QR**: Implementación de pagos seguros y rápidos mediante códigos QR.
- **Donaciones**: Plataforma para realizar y recibir donaciones dentro de la comunidad.

🎓 **Equipo de Desarrollo**

- **PM**
  - Nancy Cabral Ruiz Diaz

- **UX/UI**
  - María José González Racedo
  - Luna Cuestas
       
- **Frontend**: 
  - Lucas Quiroga
  - Jazmín Luna
  - Salvador Sánchez

- **Fullstack**
  - Sheila Diz 

- **Backend (Microcréditos)**: 
  - Mario Jarod Grande
  - Pamela Zampieri
  - Matías Mazzitelli
  - Ulises Gadea
  - Guillermo Diván
  - Emilia Fernández

- **QA**:
  - Andrea Laurino
  - Eliana Spaccavento


1. **Docker**: Se utiliza Docker para construir una imagen personalizada y gestionarla en Railway.
2. **Base de datos**: PostgreSQL con conexiones configuradas a través de variables de entorno.
3. **Railway**: Despliegue en Railway con integración continua usando Github Actions.

🏗️ **Cómo correr la aplicación**

1. Clonar el repositorio.
2. Crear y configurar las variables de entorno en el archivo `.env` (template: template.env).
3. Ejecutar la clase principal `NativoApplication`.
4. Requiere JDK 17.

🎉 **Agradecimientos**

Queremos agradecer al equipo de Igrowker por su apoyo constante, documentación y acompañamiento durante este proyecto. Este proyecto es un reflejo del trabajo duro y la dedicación de todo el equipo.

🚀 [Igrowker](https://igrowker.com/)
🚀 [Igrowker en LinkedIn](https://www.linkedin.com/company/igrowker/)
