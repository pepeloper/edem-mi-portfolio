# Mi portfolio · EDEM

Repositorio de apoyo para la primera sesión de HTML del Máster en Desarrollo Web, IA aplicada y DevOps de EDEM.

Construimos un portfolio personal paso a paso: cabecera y navegación, presentación, proyectos, sección «Ahora» y contacto con formulario y footer. En esta sesión trabajamos la estructura y el contenido con HTML. El diseño con CSS se trabajará más adelante.

## Empezar

Necesitas Git, un editor como Visual Studio Code y un navegador.

```bash
git clone --branch 01-estructura-base https://github.com/pepeloper/edem-mi-portfolio.git
cd edem-mi-portfolio
code .
```

Abre `index.html` en el navegador. No hay que instalar dependencias ni arrancar un servidor. Después de guardar los cambios en el editor, recarga la página para ver el resultado.

Si el comando `code .` no está disponible, abre la carpeta desde tu editor.

## Los pasos de la clase

Cada rama contiene el trabajo de ese paso y todos los anteriores. Son ejemplos para acompañar la explicación, consultar el código y recuperar el hilo si te quedas atrás.

| Rama | Contenido |
| --- | --- |
| `01-estructura-base` | Documento HTML inicial con `head`, `body`, `header`, `main` y `footer`. |
| `02-header-navbar` | Cabecera con el nombre y el menú de navegación. |
| `02-hero` | Presentación personal con título, descripción y enlace. |
| `03-proyecto-destacado` | Sección de proyectos con Folio como proyecto destacado. |
| `03-listado-proyectos` | Listado de otros proyectos: Shipwake y Brackit. |
| `04-ahora-cta` | Sección «Ahora» y enlace para contactar. |
| `05-contacto-footer` | Contacto, formulario con nombre, email y mensaje, y pie de página. |

Para consultar un paso, cambia a su rama:

```bash
git switch 02-header-navbar
```

Sustituye el nombre por cualquiera de los de la tabla. Por ejemplo, `git switch 05-contacto-footer` muestra el portfolio completo de esta sesión.

Si has modificado archivos, guarda tu trabajo en un commit antes de cambiar de rama. Cambiar de rama muestra la versión guardada en esa rama; tus commits siguen en la rama donde los hiciste.

## Tu propio portfolio

Empieza desde la estructura base y crea una rama para tu trabajo:

```bash
git switch 01-estructura-base
git switch -c mi-portfolio
```

Construye los bloques conforme los veamos en clase y sustituye el contenido del ejemplo por tu nombre, presentación, proyectos y enlaces. Puedes usar proyectos de clase y contar qué has aprendido o qué estás construyendo.

Guarda los avances con commits como los del repositorio:

```bash
git add .
git commit -m "feat: hero"
```

Cambia la descripción según lo que hayas añadido, por ejemplo `feat: header and navbar` o `feat: project list`.

## Qué practicarás

- Reconocer etiquetas, atributos y contenido.
- Dividir una página en bloques y elegir las etiquetas para cada uno.
- Organizar el contenido con encabezados y párrafos.
- Añadir enlaces, imágenes y listas de proyectos.
- Construir un formulario con `form`, `label`, `input`, `textarea` y `button`.

El formulario es un ejemplo de HTML: permite escribir en los campos, pero su botón tiene `type="button"` y no envía datos.

## Antes de terminar

Recorre tu portfolio en el navegador. Revisa los encabezados y el contenido, abre los enlaces y comprueba que la imagen se vea. Escribe en los campos del formulario y localiza sus etiquetas en el HTML.

Prepara una pieza para enseñarla al grupo: explica qué etiquetas has usado y qué función cumple cada una. Guarda también una duda para la puesta en común.
