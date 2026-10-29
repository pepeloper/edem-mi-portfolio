# Mi portfolio · EDEM

Implementación del [portfolio de Alex Moreno en Figma](https://www.figma.com/design/Ynt4jxiAyLwMKjbX2KDEdj/Alex-Moreno-%C2%B7-Tres-portfolios?node-id=5-40), siguiendo el ejercicio 01-Portfolio.

## Abrir el proyecto

Abre `index.html` en el navegador. No necesita instalación ni compilación. La fuente Arimo se carga desde Google Fonts. Las imágenes están guardadas en `assets/`.

## Ramas para revisar

Estas ramas son acumulativas: cada una añade su paso sobre la anterior. La rama `06-css-design` conserva el punto de partida.

| Rama | Cambio |
| --- | --- |
| `06-css-base` | Variables de color, fuentes y estilos generales. |
| `07-css-header-navbar` | Cabecera y navegación con Flexbox. |
| `08-css-hero` | Presentación y botón reutilizable. |
| `09-css-featured-project` | Sección Trabajo y proyecto Turno. |
| `10-css-project-list` | Listado de proyectos con Grid. |
| `11-css-now` | Bloque Ahora y llamada a la acción. |
| `12-css-contact` | Contacto con Grid y formulario. |
| `13-css-footer` | Pie de página con Flexbox. |

Para revisar un paso y compararlo con el anterior:

```bash
git switch 08-css-hero
git diff 07-css-header-navbar..08-css-hero
```

Guarda tus cambios en un commit antes de cambiar de rama y recarga el navegador después.

## Organización del CSS

`index.css` importa los estilos generales y los ficheros de cada bloque. Los colores se definen en `css/variables.css`.

Las clases usan BEM en inglés: `hero`, `hero__title` o `contact__control--textarea`. Cada bloque tiene su propio CSS con sus elementos y modificadores. La versión móvil sigue el diseño de Figma.

El formulario es solo una práctica de maquetación con HTML y CSS. No envía mensajes.
