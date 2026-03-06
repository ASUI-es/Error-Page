# Error Page – Página de Error Personalizable

Este repositorio contiene una **página de error moderna, minimalista y fácil de personalizar**, ideal para usar como página 404, 500 o cualquier otro estado HTTP que requiera una presentación visual clara.

La estructura es sencilla y está pensada para integrarse rápidamente en cualquier proyecto web.

---

## Contenido del repositorio

| Archivo / Carpeta | Descripción |
|-------------------|-------------|
| **index.html**     | Estructura principal de la página de error. Incluye el mensaje, el código de error y el botón de retorno. |
| **style.css**      | Hoja de estilos del proyecto. Contiene variables globales definidas en `:root` para facilitar la personalización. |
| **/assets**        | Carpeta opcional para imágenes, iconos o recursos adicionales. |

---

## Personalización mediante `:root` en CSS

El archivo `style.css` utiliza la pseudo-clase `:root` para definir **variables CSS** que controlan colores, tamaños y otros valores reutilizables. Esto permite modificar la apariencia completa de la página desde un único lugar.

### ¿Qué es `:root`?

`:root` es el selector que apunta al elemento raíz del documento (similar a `html`), pero con mayor especificidad.  
Es el lugar ideal para definir **variables globales** que luego se pueden usar en todo el CSS.

