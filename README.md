
# AutoTrack

**Sistema multiplataforma para la gestión de talleres mecánicos y el mantenimiento preventivo de vehículos.**

## Descripción del proyecto

AutoTrack es un proyecto intermodular de 2.º de Desarrollo de Aplicaciones Multiplataforma (DAM) cuyo objetivo es conectar talleres mecánicos con sus clientes mediante herramientas digitales que faciliten la gestión de vehículos, las intervenciones realizadas y el mantenimiento preventivo.

El sistema permitirá al personal del taller gestionar clientes, vehículos, citas y revisiones desde una aplicación de escritorio. Los clientes dispondrán de una aplicación móvil para consultar el estado de mantenimiento de sus vehículos, revisar su historial y comunicar incidencias.

La aplicación calculará las próximas revisiones a partir de los intervalos de tiempo y kilometraje configurados. Además, se contempla la comunicación de incidencias relevantes al cliente mediante notificaciones.

## Objetivos

- Centralizar la información de clientes, vehículos e intervenciones.
- Facilitar la planificación y gestión de citas en el taller.
- Anticipar las necesidades de mantenimiento mediante avisos orientativos.
- Mejorar la comunicación entre los talleres y sus clientes.
- Aplicar los conocimientos adquiridos en los distintos módulos del ciclo DAM.

## Equipo de desarrollo

| Integrante | Rol principal |
|---|---|
| [Nombre y apellidos 1] | Product Owner / Desarrollador |
| [Nombre y apellidos 2] | Scrum Master / Desarrollador |
| [Nombre y apellidos 3] | Desarrollador / Datos |
| [Nombre y apellidos 4] | Desarrollador / QA |

## Tecnologías previstas

| Área | Tecnologías |
|---|---|
| Interfaz de escritorio (DI) | C#, .NET 10, WPF, XAML y MVVM |
| Acceso a datos (AD) | PostgreSQL y Entity Framework Core |
| Servicios y procesos (PSP) | ASP.NET Core Web API, JWT y SignalR |
| Aplicación móvil (PMDM) | Aplicación Android; tecnología pendiente de concretar |
| Sistemas de gestión empresarial (SGE) | Análisis de procesos e interoperabilidad con Odoo |
| Control de versiones | Git y GitHub |
| Gestión del proyecto | GitHub Projects |
| Diseño de interfaces | Figma |

Las tecnologías indicadas constituyen la planificación inicial y podrán ajustarse durante el desarrollo según la viabilidad técnica y el alcance acordado.

## Alcance del MVP

La primera versión funcional de AutoTrack contempla:

1. Autenticación y control de acceso según roles.
2. Gestión de clientes y vehículos.
3. Configuración de componentes e intervalos de mantenimiento.
4. Registro de inspecciones e intervenciones mecánicas.
5. Gestión de la agenda de citas.
6. Consulta móvil del historial y del estado de mantenimiento.
7. Comunicación de incidencias y notificaciones al cliente.

La lectura automática de datos del vehículo, las integraciones avanzadas con sistemas externos y la automatización completa de procesos empresariales quedan fuera del alcance inicial.

## Organización del repositorio

El repositorio utiliza una estrategia de ramas para organizar el desarrollo y revisar los cambios antes de integrarlos.

- `main`: versión estable y validada del proyecto.
- `develop`: rama de integración del trabajo desarrollado.
- `feature/<nombre-tarea>`: rama individual para implementar una funcionalidad o tarea.

Los cambios se propondrán mediante Pull Requests vinculadas a las tareas correspondientes. Se realizarán revisiones y pruebas antes de integrar el código en `develop` y, posteriormente, publicar versiones estables en `main`.

## Gestión ágil

El equipo utilizará GitHub Projects como tablero Kanban para planificar y supervisar el trabajo.

Las columnas de trabajo serán:

- Product Backlog
- To Do (Sprint)
- In Progress
- In Review (PR)
- Done

Las tareas se documentarán mediante historias de usuario cuando corresponda, con criterios de aceptación verificables, responsable asignado, etiquetas de tipo, prioridad MoSCoW y módulo DAM implicado.

## Enlaces del proyecto

- **Repositorio GitHub:** [Añadir URL del repositorio]
- **Tablero GitHub Projects:** [Añadir URL del tablero]
- **Vídeo de presentación:** [Añadir enlace al vídeo]

## Estado del proyecto

**Fase actual:** propuesta y planificación inicial.

El desarrollo se organizará de forma incremental, priorizando las funcionalidades esenciales del MVP y verificando su integración mediante pruebas.

## Licencia

Proyecto académico desarrollado en el marco del módulo de Proyecto Intermodular del ciclo formativo de Desarrollo de Aplicaciones Multiplataforma.
