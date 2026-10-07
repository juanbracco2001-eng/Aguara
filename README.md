# Aguará

Olimpíadas entre amigos: salas con código, disciplinas a elección y una tabla compartida.

- La app es un solo archivo: `index.html`.
- Los datos viven en Firebase Firestore (proyecto `aguara-26448`).
- `firestore.rules` son las reglas de acceso para pegar en la consola de Firebase.

## Cachetazo

Juego 1 contra 1 a cachetazos, en la carpeta `cachetazo/` (un solo archivo: `cachetazo/index.html`).

- Usa el mismo proyecto de Firebase que Aguará para las salas online.
- Cada sala escribe en `salas/cachetazo-<código>/partidos`, que las reglas actuales ya permiten. No toca las salas de Aguará.
