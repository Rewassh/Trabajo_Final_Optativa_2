# Proyecto de Juego de Laberinto

## Descripción General

Este proyecto consiste en un juego tipo laberinto donde el jugador debe encontrar la habitación correcta antes de ser alcanzado por un enemigo que lo persigue constantemente. Debido al enfoque de la evaluación, se priorizó el diseño y funcionamiento de las interfaces de usuario (HUD) sobre las mecánicas del juego.

---

## Funcionalidades Implementadas

### 1. Enemy Bar

Barra de vida del enemigo.

- Se diseñó una barra para mostrar la cantidad de vida del enemigo.
- La intención era colocarla sobre la cabeza del personaje enemigo.
- Por limitaciones de tiempo, no se logró implementar su posición final dentro del juego.

### 2. Pantalla de Game Over

Pantalla mostrada cuando el jugador pierde.

- Se activa cuando la vida del personaje llega a cero.
- Informa al jugador que ha sido derrotado y finaliza la partida.

### 3. Pantalla de Victoria (Ganaste)

Pantalla de victoria del juego.

- Fue diseñada para mostrarse cuando el jugador alcanzara el objetivo final.
- La mecánica de activación no fue implementada.
- Su función sería indicar que el jugador encontró la habitación correcta y completó el juego.

### 4. Menú Principal

Interfaz inicial del juego.

- Se creó el diseño visual del menú principal.
- Actualmente no está integrado funcionalmente al proyecto.

### 5. Interacciones

Sistema de mensajes interactivos.

- Muestra un mensaje en pantalla cuando el jugador se acerca a una puerta.
- Sirve como indicación para que el jugador interactúe con el objeto.

### 6. Menú de Pausa

Interfaz de pausa del juego.

- Permite mostrar opciones mientras el juego está detenido.
- Diseñado como parte de los elementos de interfaz requeridos.

### 7. HUD del Personaje

Interfaz principal del jugador.

- Muestra la vida actual del personaje.
- Permite al jugador monitorear su estado durante la partida.

---

## Mecánica Principal

El jugador debe recorrer un laberinto mientras es perseguido por un enemigo. El objetivo es encontrar la habitación correcta antes de ser alcanzado.

- Si el enemigo logra atrapar al jugador y su vida llega a cero, se mostrará la pantalla de **Game Over**.
- Si el jugador alcanza el punto objetivo, se activaría la pantalla de **Victoria**.

---

## Observaciones

Debido a que la evaluación se centraba principalmente en la creación de interfaces (HUDs), gran parte del trabajo se enfocó en el diseño visual de las pantallas y elementos de interacción. Algunas mecánicas planeadas quedaron incompletas o sin integrar completamente al proyecto final.

---

## Tecnologías Utilizadas

- Unreal Engine
- Blueprints
- UMG (Unreal Motion Graphics)
- Git y GitHub

---

## Autor

Proyecto desarrollado como trabajo final para la asignatura **Optativa II**.
