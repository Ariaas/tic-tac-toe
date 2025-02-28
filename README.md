# Tres en línea con React

## Descripción
Este proyecto es un juego de Tres en línea (Tic-tac-toe) desarrollado con React. Tres en línea es un juego clásico donde dos jugadores se turnan para marcar X y O en una cuadrícula de 3x3. El primer jugador que logre alinear tres de sus símbolos horizontal, vertical o diagonalmente, gana la partida.

Esta implementación es completamente interactiva y se puede jugar directamente en el navegador web. ¡Desafía a un amigo y demuestra tus habilidades estratégicas!

## Características
- Interfaz de usuario intuitiva y atractiva
- Turnos alternados entre jugadores X y O
- Detección automática del ganador
- Historial de movimientos
- Posibilidad de retroceder a movimientos anteriores
- Diseño responsive que se adapta a diferentes dispositivos

## Cómo jugar
1. El juego comienza con un tablero vacío de 3x3.
2. El primer jugador marca una X en cualquier casilla vacía.
3. El segundo jugador marca una O en cualquier casilla vacía.
4. Los jugadores continúan alternando turnos.
5. El primer jugador que consiga alinear tres de sus símbolos (X u O) horizontal, vertical o diagonalmente gana.
6. Si todas las casillas se llenan sin que haya un ganador, el juego termina en empate.

## React + Vite

Esta plantilla proporciona una configuración mínima para hacer funcionar React en Vite con HMR y algunas reglas de ESLint.

Actualmente, hay dos plugins oficiales disponibles:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) usa [Babel](https://babeljs.io/) para Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) usa [SWC](https://swc.rs/) para Fast Refresh

## Ampliación de la configuración de ESLint

Si estás desarrollando una aplicación para producción, recomendamos usar TypeScript y habilitar reglas de lint con reconocimiento de tipos. Consulta la [plantilla TS](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) para integrar TypeScript y [`typescript-eslint`](https://typescript-eslint.io) en tu proyecto.
