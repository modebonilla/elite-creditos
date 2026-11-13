# Élite · Sitio de préstamos

Sitio de una sola página con cotizador interactivo y formulario de solicitud de crédito.

## Publicar en GitHub Pages
1. En GitHub crea un repositorio nuevo, público, llamado `elite-creditos`.
2. Arrastra **todo el contenido de esta carpeta** (`index.html`, `README.md` y la carpeta `assets`) y da clic en **Commit changes**.
3. Ve a **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** y **/ (root)** → **Save**.
4. En 1 o 2 minutos el sitio queda en `https://TU-USUARIO.github.io/elite-creditos/`.

## Recibir las solicitudes por correo (importante)
Las solicitudes se envían con **FormSubmit** (gratis, sin cuenta).
- El correo de destino se cambia al inicio de `index.html`, en `CONFIG.CORREO_DESTINO`.
- **La primera vez** que alguien envíe el formulario, llegará a ese correo un mensaje de FormSubmit para **activar** el formulario. Ábrelo y da clic en *Activate Form*. Desde entonces, cada solicitud llega como una tabla con todos los datos.
- Recomendación: después de activarlo, FormSubmit te da un código alias; puedes ponerlo en lugar del correo para que la dirección no quede visible en el código.

## Ajustes rápidos (en `CONFIG`, al inicio de `index.html`)
- `MONTO_MAX`: monto máximo del cotizador (hoy $500,000).
- `LIMITE_AVAL`: hasta qué monto se pide aval; arriba de ese monto se pide garantía (hoy $20,000).
