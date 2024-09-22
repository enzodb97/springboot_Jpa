## Configuración de JPA usando Hibernate
Este proyecto muestra cómo configurar JPA (Java Persistence API) utilizando Hibernate para crear y gestionar una tabla en una base de datos MySQL usando PhpMyAdmin. Ideal para quienes buscan integrar una solución de persistencia robusta y eficiente en aplicaciones basadas en Spring Boot.

## Comenzando 🚀
Estas instrucciones te permitirán obtener una copia local del proyecto para propósitos de desarrollo y pruebas. Sigue los pasos indicados para poner en marcha el entorno.

##  Pre-requisitos 📋
Asegúrate de tener los siguientes elementos configurados:

`Java Development Kit (JDK)`: Necesitas la versión 17 o superior para ejecutar la aplicación.

`Maven`: Herramienta de gestión de dependencias para compilar y ejecutar el proyecto.

`Base de datos MySQL`: Crea una base de datos llamada `Persona` en PhpMyAdmin o en tu servidor MySQL preferido.

Usuario y Contraseña de MySQL: Si estás utilizando un usuario distinto de `root` o tienes una contraseña personalizada, actualiza el archivo de configuración `src/main/resources/application.properties` con tus credenciales.

properties
```javascript
spring.datasource.url=jdbc:mysql://localhost:3306/Persona
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
```

## Instalación 🔧
Clonar el repositorio:

```javascript

git clone github.com/enzodb97/springboot_Jpa.git
cd springboot_Jpa
```
Compilar el proyecto:

Ejecuta el siguiente comando para descargar las dependencias y compilar el proyecto:

bash
```javascript
mvn clean install
```

Ejecutar la aplicación:

Para iniciar la aplicación localmente, utiliza el siguiente comando:

```javascript

mvn spring-boot:run
```

Verificación:

La aplicación estará disponible en `http://localhost:8080/`. Asegúrate de que la tabla `Persona` se haya creado correctamente en tu base de datos MySQL.

##  Uso de la Aplicación ⚙️
Una vez la aplicación esté corriendo, puedes interactuar con la API para realizar operaciones CRUD sobre la tabla Persona. Puedes utilizar herramientas como Postman o cURL para probar los endpoints de la API.

##  Construido con 🛠️
Spring Boot: Framework de Java para construir aplicaciones empresariales rápidas y seguras.

JPA (Java Persistence API): Interfaz estándar de Java para manejar bases de datos relacionales.

Hibernate: Implementación de JPA para la persistencia de datos.

MySQL: Sistema de gestión de bases de datos relacional utilizado para almacenar la información.

PhpMyAdmin: Herramienta de administración de bases de datos MySQL a través de una interfaz web.

## 🔗 Links
Si tienes alguna pregunta o sugerencia, no dudes en contactarme a través de mi perfil de LinkedIn:
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzobertolusso/)


