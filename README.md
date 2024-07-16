# ForoHub

Este proyecto es la resolución del Challenge 3 del Curso de especialización en Backend de Alura Latam y Oracle Next Education (ONE). El objetivo del desafío es desarrollar un foro que permita realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) utilizando tecnologías modernas de desarrollo backend.

## Tecnologías Utilizadas:

Java 17: Lenguaje de programación principal.
Spring Boot: Framework para la creación de aplicaciones backend.
MySQL: Sistema de gestión de bases de datos.
IntelliJ IDEA: Entorno de desarrollo integrado (IDE).
Insomnia: Herramienta para pruebas de API.


## Funcionalidades del Foro:

Crear Tópico: Permite a los usuarios crear nuevos tópicos en el foro.  
Leer Tópicos: Muestra todos los tópicos creados en el foro.  
Leer Tópico Específico: Permite visualizar un tópico específico junto con sus detalles.  
Actualizar Tópico: Permite a los usuarios actualizar la información de un tópico existente.  
Eliminar Tópico: Permite a los usuarios eliminar un tópico del foro.  

El proyecto consiste en la implementación de una API RESTful que maneja las operaciones CRUD para los tópicos del foro. La API sigue las mejores prácticas del modelo REST y realiza validaciones según las reglas del negocio. La persistencia de la información se maneja a través de una base de datos MySQL.

El sistema de autenticación implementado es de tipo Stateless, lo que significa que no se mantiene el estado de la sesión en el servidor. En su lugar, se utilizan tokens para autenticar y autorizar las solicitudes. Insomnia se utiliza para realizar pruebas de la API, asegurando que las operaciones CRUD funcionen correctamente bajo este esquema de autenticación.

## Autor
Desarrollado por Juan Daleman

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
