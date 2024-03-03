# adaptive-retro-pong

El proyecto consiste en una nueva versión del juego retro PONG lanzado por Atari en 1972. Esta nueva interpretación del juego hace uso de p5.js (una biblioteca de JavaScript para la programación creativa [1]), y tiene como propuesta la implementación de una dificultad adaptativa que busca siempre suponer un reto para el jugador, haciendo el juego más fácil o difícil de acuerdo a las habilidades del jugador durante el desarrollo de la partida.

**DEMO P5.js:** [https://editor.p5js.org/dafmontenegro/full/Cnx7DpEdd](https://editor.p5js.org/dafmontenegro/full/Cnx7DpEdd)

**DEMO:** [https://dafmontenegro.com/adaptive-retro-pong/](https://dafmontenegro.com/adaptive-retro-pong/)

## Proyecto Juego Retro - Computación Visual UN 2024-1
- Daniel Felipe Montenegro
- Camilo Andres Fierro
- Anderson Barrera

## Referencias
[1] p5.js. Tomado de: [https://p5js.org/](https://p5js.org/)

---

## Niveles

El juego cuenta con múltiples niveles de dificultad para adaptarse a las habilidades del jugador. Estos niveles se ajustan dinámicamente según el rendimiento del jugador, proporcionando una experiencia de juego desafiante pero accesible.

## ¿Cómo Jugar?

El juego se controla de las siguientes maneras:

- **Para Jugar:**
  - Tecla 1: Juega con el jugador 1 (izquierda).
  - Tecla 2: Juega con el jugador 2 (derecha).
  - Movimiento del Mouse: Controla la paleta de forma vertical.

- **Otros Controles:**
  - Tecla Enter: Pausa el juego.
  - Tecla I: Activa/Desactiva la visualización de la velocidad (Velocidad) y precisión (Precisión).

El objetivo del juego es golpear la pelota con las paletas y evitar que la pelota pase al lado opuesto de la pantalla.

## ¿Cómo lo Hicimos?

El juego se implementó utilizando el framework p5.js, que proporciona herramientas para la creación de gráficos y animaciones interactivas en el navegador web.

## Funcionamiento

El juego funciona mediante la detección de colisiones entre la pelota y las paletas. Cuando la pelota colisiona con una paleta, cambia de dirección y aumenta la velocidad. La puntuación se incrementa cada vez que la pelota pasa al lado opuesto de la pantalla sin ser golpeada por una paleta.

## Mejoras Futuras

Para futuras iteraciones del juego, se pueden considerar las siguientes mejoras:

- Implementación de efectos visuales y sonoros para una experiencia de juego más inmersiva.
- Integración de funciones de juego en red para permitir partidas multijugador en línea.
- Optimización del código para mejorar el rendimiento en dispositivos móviles y de baja potencia.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar el juego o encuentras algún error, no dudes en abrir un problema o enviar una solicitud de extracción en nuestro repositorio de GitHub.

---

¡Esperamos que disfrutes jugando al Pong Adaptativo! [¡Juega ahora en línea!](https://dafmontenegro.com/adaptive-retro-pong/)
