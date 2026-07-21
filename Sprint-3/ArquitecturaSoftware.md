# Introducción

La arquitectura de software representa la organización de los componentes necesarios para implementar el Sprint 3 del proyecto.

## Arquitectura Seleccionada
| Aspecto       | Descripción                                                                            |
| ------------- | -------------------------------------------------------------------------------------- |
| Tipo          | Arquitectura en Tres Capas                                                             |
| Justificación | Facilita la separación entre la interfaz, la lógica del negocio y la gestión de datos. |

## Componentes
| Capa              | Componentes                                     | Función                         |
| ----------------- | ----------------------------------------------- | ------------------------------- |
| Presentación      | Pantalla de Solicitudes, Pantalla de Evaluación | Interacción con el usuario.     |
| Lógica de Negocio | Controlador, Servicio de Evaluación             | Procesa las reglas del negocio. |
| Datos             | Clientes, Solicitudes, Evaluaciones, Usuarios   | Almacena la información.        |

## Flujo Arquitectónico
| Paso | Acción                                           |
| ---- | ------------------------------------------------ |
| 1    | El evaluador selecciona una solicitud.           |
| 2    | La interfaz envía la solicitud al controlador.   |
| 3    | El controlador invoca el servicio de evaluación. |
| 4    | El servicio consulta la base de datos.           |
| 5    | Se registra la evaluación.                       |
| 6    | El sistema confirma el resultado al evaluador.   |

## Tecnologías
| Tecnología | Uso                       |
| ---------- | ------------------------- |
| UML        | Modelado del sistema      |
| Draw.io    | Diagramas                 |
| GitHub     | Control de versiones      |
| SQL Server | Base de datos (propuesta) |
