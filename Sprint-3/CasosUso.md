# Introducción

Los siguientes casos de uso representan las funcionalidades desarrolladas durante el Sprint 3.

## Casos de Uso
| Código | Caso de Uso                           | Actor     | Prioridad |
| ------ | ------------------------------------- | --------- | --------- |
| CU-01  | Visualizar solicitudes pendientes     | Evaluador | Alta      |
| CU-02  | Consultar información del solicitante | Evaluador | Alta      |
| CU-03  | Registrar observaciones               | Evaluador | Alta      |
| CU-04  | Registrar resultado de evaluación     | Evaluador | Alta      |
| CU-05  | Guardar evaluación                    | Evaluador | Alta      |

## Relación Requisito - Caso de Uso
| Requisito | Caso de Uso |
| --------- | ----------- |
| RF-01     | CU-01       |
| RF-02     | CU-02       |
| RF-03     | CU-03       |
| RF-04     | CU-04       |
| RF-05     | CU-05       |

## Especificación del Caso de Uso
| Campo           | Descripción                                                                     |
| --------------- | ------------------------------------------------------------------------------- |
| Código          | CU-01                                                                           |
| Nombre          | Visualizar solicitudes pendientes                                               |
| Actor           | Evaluador                                                                       |
| Precondición    | Usuario autenticado                                                             |
| Flujo Principal | El evaluador ingresa al módulo y el sistema muestra las solicitudes pendientes. |
| Postcondición   | El evaluador puede seleccionar una solicitud para iniciar la evaluación.        |
