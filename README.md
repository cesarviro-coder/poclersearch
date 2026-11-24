# PoclerSearch

Primera versión de PoclerSearch: una página de búsqueda adaptable a móviles y ordenadores, con categorías para web, imágenes, vídeos y noticias.

## Qué hace
- Interfaz propia para buscar.
- Envía las búsquedas a DuckDuckGo según la categoría elegida.
- No necesita servidor Python ni claves API.

## Limitación importante
Esta versión no es un motor de búsqueda independiente ni crea su propio índice de Internet. Los resultados los proporciona DuckDuckGo. Un buscador como Google necesita rastrear e indexar páginas web o conectar APIs de búsqueda, que pueden tener límites o costes.

## Publicar gratis con GitHub Pages
1. Crea un repositorio público llamado `poclersearch` en https://github.com/new
2. En el repositorio, pulsa **Add file → Upload files**.
3. Sube `index.html`, `style.css`, `app.js` y `README.md` (puedes extraerlos del ZIP primero).
4. Pulsa **Commit changes**.
5. Abre **Settings → Pages**.
6. En **Build and deployment**, elige **Deploy from a branch**.
7. Selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
8. Espera unos minutos. GitHub mostrará tu dirección pública, normalmente `https://TU-USUARIO.github.io/poclersearch/`.

GitHub Pages aloja el sitio estático gratis. Un dominio propio como `poclersearch.com` se registra por separado.
