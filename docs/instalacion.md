# Guía de instalación

## Requisitos del entorno

Para ejecutar EduCampus LMS en un entorno local, se recomienda contar con un equipo con conexión a internet, Git instalado y un editor de código como Visual Studio Code.

También es importante tener configuradas las herramientas necesarias según la tecnología final del proyecto, como servidor local, gestor de dependencias y motor de base de datos.

## Base de datos

La plataforma debe contar con una base de datos para almacenar información de usuarios, cursos, inscripciones, evaluaciones, calificaciones y reportes académicos.

Antes de iniciar el sistema, se debe verificar que la base de datos esté creada y que las credenciales de conexión sean correctas.

## Variables de entorno

Las variables de entorno permiten configurar datos sensibles o específicos del entorno, como:

- Nombre de la base de datos.
- Usuario de conexión.
- Contraseña.
- Puerto del servidor.
- Claves de configuración.

Estas variables no deben publicarse directamente en el repositorio.

## Ejecución local

Para ejecutar el proyecto localmente, se deben instalar las dependencias necesarias, configurar la base de datos y levantar el servidor de desarrollo.

El equipo debe seguir las instrucciones técnicas definidas por el proyecto para asegurar que todos trabajen bajo la misma configuración.

## Verificación inicial del sistema

Después de iniciar el sistema, se debe comprobar que:

- El servidor carga correctamente.
- La conexión con la base de datos funciona.
- Los módulos principales responden.
- No aparecen errores críticos en consola.