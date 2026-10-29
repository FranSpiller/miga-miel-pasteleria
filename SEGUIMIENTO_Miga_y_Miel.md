# Seguimiento del proyecto — Miga & Miel

**Responsable del desarrollo:** Francisco Bracamontes  
**Cliente y usuaria administradora:** Propietaria de la pastelería (negocio familiar)

Este documento describe la configuración de las cuatro herramientas de seguimiento solicitadas en el curso.

## 1. Tablero Kanban — Trello

Se utiliza un tablero con cuatro columnas: **Por hacer**, **En proceso**, **En revisión** y **Terminado**. Cada tarjeta representa una de las 12 historias de usuario del proyecto y tiene una prioridad y un responsable.

**Estado de la revisión del prototipo (29/10/2026):**

| Estado | Historias |
| --- | ---: |
| Por hacer | 0 |
| En proceso | 0 |
| En revisión | 2 |
| Terminado | 10 |
| **Total** | **12** |

Historias en revisión:

- **HU01 — Consultar catálogo de pasteles:** pendiente incorporar fotografías reales de los pasteles.
- **HU09 — Administrar catálogo de pasteles:** pendiente permitir el registro de nuevos pasteles.

Las historias terminadas se consideran **validadas en el prototipo**, no listas para producción.

## 2. Niko-niko — Excel

Se registra el estado de ánimo del desarrollador en jornadas reales de trabajo, mediante las opciones **Bien**, **Regular** o **Difícil**. Las observaciones y los bloqueos permiten dar contexto a la actividad. No se inventan registros.

**Jornadas registradas:** 16/10/2026 (preparación), 21/10/2026 (preparación) y 29/10/2026 (Sprint 1), según la hoja Niko-niko del archivo de seguimiento.

## 3. Burndown chart — Excel

La gráfica compara los puntos pendientes de acuerdo con un **avance ideal** y los puntos **realmente pendientes** según el tablero Kanban.

| Indicador | Valor al 29/10/2026 |
| --- | ---: |
| Puntos estimados | 45 |
| Puntos validados en el prototipo | 37 |
| Puntos pendientes | 8 |
| Avance del prototipo | 82.2 % |

El Burndown se ajustó a un calendario de **seis semanas**, con fecha final propuesta del **04/12/2026**. Los puntos futuros deben permanecer sin registrar hasta que haya nuevas revisiones. Este calendario debe mantenerse alineado con la versión actual del Release Planning.

## 4. Repositorio de código — GitHub

**Repositorio:** https://github.com/FranSpiller/miga-miel-pasteleria

Archivos principales:

- `index.html`: código del prototipo web.
- `README.md`: descripción y modo de ejecución.
- `SEGUIMIENTO.md`: documentación de las herramientas ágiles.

Los cambios del código se registrarán mediante **commits**, con mensajes que expliquen lo modificado.

## Evidencias recomendadas para la actividad

1. Captura del tablero de Trello con sus cuatro columnas y las 12 tarjetas.
2. Captura de la hoja Niko-niko con registros reales.
3. Captura de la gráfica Burndown y sus valores actuales.
4. Captura de GitHub con los archivos publicados, el historial de commits y la URL del repositorio.

**Nota:** Los resultados de Kanban y Burndown representan el estado de validación del prototipo, no el porcentaje de implementación de un sistema comercial completo.
