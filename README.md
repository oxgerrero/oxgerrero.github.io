# oxgerrero.github.io

Mi portafolio personal: **https://oxgerrero.github.io**

Sitio estático (HTML + CSS, sin frameworks ni build) servido con GitHub Pages.

- Bilingüe español / inglés, con el idioma detectado del navegador y botón para cambiarlo.
- Modo claro y oscuro, según el sistema o elegido a mano.
- Responsive desde 320 px.

## Ejecutar en local

```bash
# cualquier servidor estático sirve, por ejemplo:
npx serve .
```

## Estructura

```
index.html    contenido (bloques con data-l="es" / data-l="en")
styles.css    estilos y temas
assets/       imágenes
```

Para editar un texto, cambia los dos bloques (`data-l="es"` y `data-l="en"`) para que los idiomas no se desincronicen.
