# ParqueArena

Landing de ParqueArena, centro de eventos y convenciones en Temuco.

## Estructura

- `main-site/`: landing principal, imágenes y videos promocionales.
- `dist/`: página de presentación de los espacios del recinto.

## Vista local y publicación

El sitio es estático y no necesita instalación ni compilación. Para ver la landing, abrir `main-site/index.html` o servir la carpeta `main-site/` con un servidor estático.

Al configurar un servicio de hosting para la landing principal, usar `main-site` como directorio de publicación y dejar vacío el comando de compilación.

Algunas fotografías, fuentes y videos se cargan desde servicios externos y requieren conexión a Internet.

## Netlify

El archivo `netlify.toml` configura la publicación de `main-site/` sin compilación.
Vincular este repositorio y seleccionar la rama `main`. Si se configura manualmente:

- Base directory: raíz del repositorio (`.`).
- Build command: vacío.
- Publish directory: `main-site`.

Después de cambiar la configuración, iniciar un nuevo deploy desde Netlify.
