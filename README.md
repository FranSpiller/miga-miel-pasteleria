# Miga & Miel — Pastelería artesanal

**Proyecto académico de Desarrollo de Software**  
**Desarrollador:** Francisco Javier Bracamontes Avendaño  
**Tipo de producto:** prototipo web interactivo de alta fidelidad  
**Repositorio:** https://github.com/FranSpiller/miga-miel-pasteleria

## Descripción del proyecto

Miga & Miel es un prototipo de sistema web para una pastelería artesanal que elabora pasteles por encargo. Permite que los clientes consulten productos, personalicen una solicitud y consulten el estado de sus encargos. La propietaria cuenta con un panel administrativo para gestionar catálogo, disponibilidad, solicitudes, cotizaciones y pedidos.

**Objetivo:** facilitar el registro y la organización de pedidos personalizados, así como la comunicación del avance del pedido dentro de una demostración académica.

## Tecnologías y almacenamiento

- **HTML5:** estructura y formularios de la aplicación.
- **CSS3:** diseño adaptable y presentación visual.
- **JavaScript:** navegación, validaciones y acciones de clientes y administradora.
- **`localStorage`:** persistencia local de productos, modificaciones, fechas y pedidos de demostración.
- **`sessionStorage`:** control de la sesión administrativa de demostración.
- **GitHub:** control de versiones, documentación e incidencias.

La aplicación **no dispone de backend ni base de datos central**. El almacenamiento está asociado al navegador y al origen desde el que se abre la aplicación; no sincroniza datos entre diferentes dispositivos o usuarios.

## Funcionalidades disponibles

### Área del cliente

- Consultar un catálogo de seis pasteles iniciales con fotografías y precios de referencia.
- Filtrar productos y consultar su descripción y detalles.
- Personalizar un pastel (tamaño, sabor, relleno, decoración y mensaje).
- Consultar fechas y solicitar un pastel por encargo.
- Revisar y aceptar una cotización de demostración.
- Consultar el estado de un pedido con su folio y teléfono.

### Área de administración

- Iniciar y cerrar sesión de **demostración**.
- **Agregar pasteles** con nombre, descripción, categoría, precio y fotografía.
- **Editar pasteles** existentes, incluida su fotografía (opcional al editar).
- Cambiar la disponibilidad de un pastel mediante **activar/desactivar**.
- **Eliminar pasteles del catálogo** mediante confirmación. Si un pastel tiene pedidos anteriores, sus datos se conservan internamente para consultar dichos pedidos.
- Bloquear y habilitar fechas, revisar solicitudes, elaborar cotizaciones y avanzar el estado de pedidos.

### Mejoras pendientes

- **HU12:** permitir retroceder/corregir la etapa de un pedido si la administradora lo avanzó por error. Propuesta para el Sprint 3, aún no implementada.
- Estudiar una base de datos compartida y autenticación segura para una eventual versión de uso real. **No forman parte de la implementación actual.**

## Estructura del repositorio

```text
miga-miel-pasteleria/
├── index.html                 # Aplicación web
├── img/                       # Fotografías utilizadas en el catálogo inicial
├── documentacion/             # Release Planning, pruebas y seguimiento
├── apuntes/                   # Apuntes auxiliares del curso
├── README.md                  # Este archivo
└── .gitignore                 # Exclusiones de control de versiones
```

Los documentos relevantes se encuentran en `documentacion/`, entre ellos:

- [Release Planning de 3 sprints](documentacion/ReleasePlanning_3Sprints.docx)
- [Seguimiento del proyecto](documentacion/SEGUIMIENTO_Miga_y_Miel.md)
- [Excel con Kanban, Niko-niko y Burndown](documentacion/Miga_y_Miel_Seguimiento_Nuevo_Enlace.xlsx)

> Si algún documento se guarda con otro nombre, actualizar su enlace en este README.

## Cómo ejecutar el prototipo

1. Descargar el repositorio completo como ZIP desde GitHub y extraerlo, o clonarlo con Git.
2. Abrir la carpeta `miga-miel-pasteleria` en **Visual Studio Code**.
3. Abrir `index.html` usando **Live Server** (recomendado) o directamente en un navegador moderno.
4. Mantener la carpeta `img/` junto al archivo `index.html` para que carguen las seis fotografías.
5. Probar las funciones de cliente y entrar al apartado **Administración** para gestionar el catálogo.

**Acceso de demostración:**

- Correo: `admin@migamiel.demo`
- Contraseña: `demo123`

Estas credenciales están incorporadas al prototipo únicamente para pruebas; **no protegen información real**.

### Recomendaciones durante las pruebas

- Utilizar nombres, teléfonos y encargos **ficticios**.
- Evitar cambiar de dirección u origen del servidor durante una prueba, porque el navegador puede mostrar distintos datos de `localStorage`.
- No borrar los datos del sitio ni utilizar **«Reiniciar demostración»** si se desean conservar las modificaciones locales.
- Los pasteles agregados mediante el panel se guardan en el navegador; **no se publican automáticamente en GitHub ni quedan disponibles en otro equipo**.
- Si la imagen de un pastel no aparece, verificar que coincidan exactamente la ruta y el nombre del archivo dentro de `img/`.

## Historias de usuario y planificación

El backlog del proyecto contiene **12 historias de usuario y 45 puntos de historia**, organizados en **3 sprints**:

| Sprint | Fechas previstas | Historias | Puntos |
|---|---|---|---:|
| Sprint 1 | 26 oct. – 6 nov. de 2026 | HU08, HU09, HU01 | 11 |
| Sprint 2 | 9 – 20 nov. de 2026 | HU03, HU10, HU04, HU05 | 16 |
| Sprint 3 | 23 nov. – 4 dic. de 2026 | HU11, HU02, HU06, HU12, HU07 | 18 |
| **Total** | **6 semanas (provisional)** | **12 historias** | **45** |

**Estado registrado del prototipo (9 de noviembre de 2026):** las 12 historias figuran en *Terminado* en Trello; el Excel registra 45/45 puntos del **alcance funcional del prototipo**. Esto **no equivale** a haber completado las entregas, las pruebas formales de todos los sprints ni una aplicación lista para producción.

## Pruebas y seguimiento

Las herramientas de seguimiento utilizadas son:

- **Kanban:** tablero de Trello *Miga & Miel – Proyecto de Software*.
- **Niko-niko:** registro de actividades y ánimo en el Excel.
- **Burndown:** gráfica ideal y real de puntos pendientes del prototipo, en el mismo Excel.
- **GitHub:** commits, documentación y seguimiento de incidencias.

Para el **Sprint 1** se preparó el documento de diseño de pruebas para HU08, HU09 y HU01. El registro de ejecución está abierto en [GitHub Issues, incidencia #1](https://github.com/FranSpiller/miga-miel-pasteleria/issues/1); los resultados y capturas deben documentarse según se realicen. **No se consideran pruebas aprobadas únicamente por haber diseñado los casos o creado la incidencia.**

## Alcance y advertencias

Este es un **prototipo académico**, no una tienda en línea de producción. No procesa pagos reales, no utiliza autenticación segura ni sincroniza pedidos entre dispositivos. Las fotografías utilizadas para demostrar la interfaz deben contar con autorización antes de emplearse comercialmente; algunas son imágenes de prueba.

---

**Miga & Miel — Proyecto de Desarrollo de Software · Versión documental actualizada: 9 de noviembre de 2026.**
