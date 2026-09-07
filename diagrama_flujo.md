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
(Pegar aca la imagen del diagrama hecho de Dray.io o la foto del papel)
