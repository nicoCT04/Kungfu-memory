# Kung Fu Panda Memory Game

## Descripción

Este proyecto es un juego de memoria inspirado en *Kung Fu Panda*. El objetivo del juego es emparejar todas las cartas en el menor número de movimientos posible. El juego está desarrollado en **React** y utiliza un solo archivo HTML con Babel para compilar JSX directamente en el navegador.

---

## Características

- **Grid de 4x4 cartas:** Las cartas están organizadas en una cuadrícula de 4x4.
- **Cartas aleatorias:** Las cartas se mezclan aleatoriamente cada vez que se inicia o reinicia el juego.
- **Animación de flip:** Las cartas tienen una animación suave al voltearse.
- **Contador de movimientos:** Muestra el número de movimientos realizados por el jugador.
- **Mensaje de victoria:** Aparece un mensaje cuando el jugador empareja todas las cartas.
- **Botón "Volver a jugar":** Permite reiniciar el juego con una nueva mezcla de cartas.
- **Botón "Regresar al inicio":** Permite regresar al menú principal.
- **Botón de GitHub:** Enlace al repositorio del proyecto.

---

## Tecnologías utilizadas

- **React:** Para la creación de componentes y manejo del estado.
- **Babel:** Para compilar JSX directamente en el navegador.
- **HTML y CSS:** Para la estructura y diseño del juego.

---

## Estructura del proyecto

El proyecto está contenido en un único archivo HTML que incluye:

1. **Estilos CSS:** Para el diseño del juego, animaciones y botones.
2. **Componentes React:**
   - `App`: Componente principal que controla si se muestra el menú o el juego.
   - `Menu`: Componente del menú principal con botones para iniciar el juego y acceder al repositorio de GitHub.
   - `Game`: Componente del juego que incluye la lógica de las cartas, el contador de movimientos y el mensaje de victoria.

---

## Cómo jugar

1. **Inicio:**
   - Al cargar la página, se muestra el menú principal con el título del juego y dos botones:
     - **Begin:** Inicia el juego.
     - **GitHub:** Abre el repositorio del proyecto en una nueva pestaña.

2. **Juego:**
   - Haz clic en las cartas para voltearlas.
   - Si las dos cartas seleccionadas coinciden, permanecen volteadas.
   - Si no coinciden, se voltean nuevamente después de 1 segundo.
   - El objetivo es emparejar todas las cartas en el menor número de movimientos posible.

3. **Victoria:**
   - Cuando todas las cartas están emparejadas, aparece un mensaje de victoria con un botón para reiniciar el juego.

4. **Opciones:**
   - **Volver a jugar:** Mezcla las cartas y reinicia el juego.
   - **Regresar al inicio:** Vuelve al menú principal.

---

## Cómo ejecutar el proyecto

1. Descarga el archivo HTML del proyecto.
2. Abre el archivo en cualquier navegador moderno (como Chrome o Firefox).
3. ¡Disfruta del juego!

---

## Enlace al repositorio

Puedes encontrar el código fuente del proyecto en el siguiente enlace:

[Kung Fu Panda Memory Game - GitHub](https://github.com/nicoCT04/Kungfu-memory.git)

---

## Capturas de pantalla

### Menú principal
![Menú principal](https://via.placeholder.com/600x300?text=Men%C3%BA+principal)

### Juego
![Juego](https://via.placeholder.com/600x300?text=Juego)

### Mensaje de victoria
![Mensaje de victoria](https://via.placeholder.com/600x300?text=Mensaje+de+victoria)

---

## Mejoras futuras

- Agregar niveles de dificultad con diferentes tamaños de grid (por ejemplo, 6x6 o 8x8).
- Implementar un temporizador para medir el tiempo que toma completar el juego.
- Guardar el puntaje más alto en el almacenamiento local del navegador.
- Agregar efectos de sonido al voltear las cartas o ganar el juego.

---

¡Gracias por jugar! 😊
