# Sudoku Pop

Un sudoku para jugar en el navegador, sin instalar nada. Funciona en móvil y en escritorio, con tema claro y oscuro.

**Jugar:** https://mxcl331-svg.github.io/sudoku-pop/ (se activa con GitHub Pages, ver más abajo)

## Qué incluye

- **Tableros:** Clásico 9×9, Mini 6×6 y Diagonal (las dos diagonales también llevan del 1 al 9).
- **Modos:** Relajado, Contrarreloj, Supervivencia (3 vidas) y Reto del día (el mismo tablero para todos ese día).
- **Dificultad:** cinco niveles, de Fácil a Maestro. Cada tablero tiene una única solución.
- **Ayudas:** notas, notas automáticas, 3 pistas, deshacer y borrar. Resalta fila, columna y números iguales.
- **Animaciones:** aparición del tablero, ondas al completar filas, columnas y cajas, partículas, textos de racha, trofeo con estrellas, confeti y fuegos artificiales al ganar.
- **Sonidos:** generados con Web Audio, sin archivos externos. Se pueden silenciar.
- **Guardado:** la partida se guarda sola y se puede continuar. También guarda tus mejores tiempos.

## Teclado

| Tecla | Acción |
| --- | --- |
| `1`–`9` | Poner número |
| `N` | Activar o desactivar notas |
| `H` | Pista |
| `Z` | Deshacer |
| `⌫` | Borrar |
| `P` | Pausa |
| Flechas | Mover la selección |

## Publicarlo con GitHub Pages

1. En el repositorio, entra en **Settings → Pages**.
2. En **Build and deployment**, elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
4. Espera uno o dos minutos. El enlace aparece arriba en esa misma pantalla.

## Cómo está hecho

Todo vive en un solo archivo, `index.html`, con HTML, CSS y JavaScript sin dependencias. Solo carga las tipografías Bricolage Grotesque y DM Sans desde Google Fonts; si no cargan, usa las del sistema.

El generador crea una solución completa con búsqueda y luego quita números uno a uno, comprobando después de cada cambio que el tablero siga teniendo una sola solución.

## Licencia

MIT. Consulta el archivo `LICENSE`.
