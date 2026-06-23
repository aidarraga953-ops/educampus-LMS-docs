# Buenas prácticas

Este documento reúne recomendaciones para trabajar de forma ordenada en el proyecto EduCampus LMS. Su propósito es mantener una colaboración clara, un historial comprensible y una documentación fácil de revisar.

Las buenas prácticas ayudan a evitar errores comunes, reducir conflictos entre ramas y mejorar la calidad del trabajo entregado por cada integrante del equipo.

## Buenas prácticas de commits

Un commit representa un cambio específico dentro del proyecto. Por esta razón, cada commit debe ser claro, pequeño y relacionado con una sola tarea.

### Recomendaciones

- Realizar commits por tareas específicas.
- Evitar mezclar cambios diferentes en un mismo commit.
- Revisar los archivos modificados antes de confirmar cambios.
- Usar mensajes claros y descriptivos.
- Confirmar únicamente los archivos necesarios.
- Evitar subir archivos temporales o innecesarios.
- Usar gitmoji cuando el equipo lo defina como convención.
- No hacer commits directamente sobre `main`.
- Verificar el estado del repositorio antes de cada commit.

### Ejemplos de commits correctos

```bash
git commit -m ":memo: docs: agregar guía de instalación"
git commit -m ":memo: docs: agregar documentación de módulos"
git commit -m ":bug: fix: corregir conflicto en documentación"
git commit -m ":sparkles: feat: agregar nueva sección de reportes"