# Reparto Secreto

Página para repartir cartas de roles ocultos (dos habitaciones y una bomba) a los celulares de los jugadores.

- `index.html`: toda la página. La configuración de Firebase está al inicio del archivo.
- Netlify publica la carpeta tal cual (ver `netlify.toml`).
- Datos en Firebase Firestore (proyecto `r1b-94a8f`): colecciones `games`, `games/{código}/players` y `templates`.
