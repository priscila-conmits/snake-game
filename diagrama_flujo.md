# Diagrama de Flujo - [snake-game]

# Descripcion 

Este programa muestra las pantallas del juego y las transiciones entre ellas.

## Pantallas 
| Pantalla | Descripcion | Como se juega |
|---|---|---|
| Inicio | Muestra titulo y boton "Jugar" | Al abrir el programa |
|Juego | La accion principal del juego | Al hacer clic en "Jugar" |
| Game Over | Muestra puntaje final | Cuando el jugador pierde |
| Ranking | Muestra top 5 puntajes | Despues del Game Over |

# Transiciones 
| Desde | Evento | Hacia |
|---|---|---|
| Inicio | Clic en "Jugar" | Juego |
| Juego | El jugador pierde | Game Over |
| Game Over | Automatico (guarda puntaje) | Rankig |
| Rankig | Clic en "Juegar de nuevo" | Juego |
| Rankig | Clic en "Salir" | Se cierra el programa | 

## Diagrama visual
<img width="791" height="156" alt="image" src="https://github.com/user-attachments/assets/ea0c4b0c-e0ac-4978-b2b6-8f2706bc9fdf" />
