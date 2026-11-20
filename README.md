# Reparto Secreto

Página para repartir cartas de roles ocultos (dos habitaciones y una bomba) a los celulares de los jugadores.

- `index.html`: toda la página. La configuración de Firebase está al inicio del archivo.
- Se publica con GitHub Pages desde la rama `main` (carpeta raíz): https://hmcc1310.github.io/reparto-secreto/ . El archivo `.nojekyll` hace que GitHub publique los archivos tal cual. (`netlify.toml` queda de la publicación anterior en Netlify.)
- Datos en Firebase Firestore (proyecto `r1b-94a8f`): colecciones `games`, `games/{código}/players` y `templates`.

## Probar sin gente (simulador)
En la sala del anfitrión, sección «🤖 Simulador»: «Agregar bots» crea jugadores de prueba. «Jugar como» abre una pestaña con la pantalla de ese bot (`?code=XXXX&as=<id>`). El «Piloto automático» hace que los bots elijan rehenes, acepten el liderazgo y respondan el final.
