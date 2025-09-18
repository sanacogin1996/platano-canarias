# Proyecto Header con Logo

## Descripción
Este proyecto contiene la implementación de un **header** para una página web, con un contenedor para el logo y elementos adicionales. La clase principal `.header__logo` controla la alineación y distribución de los elementos dentro del header.

## Estructura del proyecto
- `index.html` → Archivo principal de la página.
- `styles.css` → Contiene los estilos de la página, incluyendo `.header__logo`.
- `README.md` → Documentación del proyecto.

## Clase `.header__logo`
Se utiliza para el contenedor del logo en el header.

### Propiedades principales:
- `display: flex;` → Convierte el contenedor en un flexbox.
- `height: 100%;` → Ocupa toda la altura del header.
- `justify-content: space-between;` → Distribuye los elementos con espacio entre ellos.
- `margin-top: 25px;` → Separa el contenedor del borde superior del header.

### Personalización:
Para mover el logo hacia la izquierda:
```css
.header__logo {
    justify-content: flex-start; /* Alinea los elementos a la izquierda */
    margin-left: 10px; /* Ajusta el espacio desde el borde izquierdo */
}