# Seguimiento del proyecto — Miga & Miel

**Responsable:** Francisco Javier Bracamontes Avendaño  
**Proyecto:** prototipo de gestión de pedidos de pastelería artesanal  
**Corte del estado documentado:** 9 de noviembre de 2026  
**Revisión documental:** 15 de noviembre de 2026

## 1. Kanban — Trello

Tablero: **Miga & Miel – Proyecto de Software**. Columnas: Por hacer, En proceso, En revisión y Terminado.

| Estado del prototipo (09/11/2026) | Historias |
|---|---:|
| Por hacer | 0 |
| En proceso | 0 |
| En revisión | 0 |
| Terminado | 12 |
| **Total** | **12** |

Las historias HU01 y HU09, que en octubre se encontraban en revisión, fueron completadas dentro del prototipo: fotografías en el catálogo y administración de pasteles (agregar, editar, activar/desactivar y eliminar). **Terminado** describe el alcance funcional del prototipo, no certifica pruebas formales ni preparación para uso comercial.

## 2. Niko-niko — Excel

El registro del desarrollador contiene **4 jornadas reales**: 16/10, 21/10, 29/10 y 09/11/2026; **3 Bien** y **1 Regular**. Las observaciones del 09/11 mencionan ajustes de imágenes y cambios registrados en GitHub. No se agregan estados emocionales inventados para otras fechas.

## 3. Burndown chart — Excel

Registro histórico de puntos pendientes para el alcance original del prototipo:

| Fecha | Puntos pendientes |
|---|---:|
| 26/10/2026 | 45 |
| 29/10/2026 | 8 |
| 09/11/2026 | 0 |

Se trata de **45 puntos / 12 historias** del prototipo, cuyo tablero muestra el 100 % funcional. El seguimiento de entregas formales, pruebas e incrementos posteriores debe quedar separado. No se inventan registros para fechas futuras.

## 4. Release Planning — 3 sprints

| Sprint | Periodo planeado | Historias | Puntos |
|---|---|---|---:|
| Sprint 1 | 26/10–06/11/2026 | HU08, HU09, HU01 | 11 |
| Sprint 2 | 09/11–20/11/2026 | HU03, HU10, HU04, HU05 | 16 |
| Sprint 3 | 23/11–04/12/2026 | HU11, HU02, HU06, HU12, HU07 | 18 |
| **Total** | | **12** | **45** |

La mejora adicional prevista para HU12 (corregir/retroceder estados) se registra separadamente de la estimación original, hasta que el profesor apruebe ajustar el alcance.

## 5. GitHub y pruebas

- Repositorio: https://github.com/FranSpiller/miga-miel-pasteleria
- Código actual: [`index.html`](../index.html)
- Descripción y ejecución: [`README.md`](../README.md)
- Ejecución formal de pruebas: [Issue #1](https://github.com/FranSpiller/miga-miel-pasteleria/issues/1)
- Diseños de pruebas Sprint 1: 23 casos elaborados; **resultados de ejecución pendientes**.

## 6. Evidencias para reuniones

Se recomienda presentar capturas con **fecha de corte explícita** de GitHub, tablero Trello, hoja Niko-niko y Burndown. Los documentos BiWeekly 1/2/3 reflejan los cortes conocidos; las imágenes anteriores no deben presentarse como capturas nuevas.

**Limitaciones conocidas:** persistencia con localStorage sin sincronización entre equipos y autenticación de demostración. Antes de usar el sistema con clientes reales se requieren servidor, base de datos y seguridad adecuada.
