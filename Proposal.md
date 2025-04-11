# Propuesta TP DSW

## Grupo
### Integrantes
* Leg - Moretti Yrure, Pedro
* Leg - Bernard, Bruno

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Tema
### Descripción
*2 a 6 líneas describiendo el negocio (menos es más)*
El Sistema es una plataforma de juegos basados en turnos qv1, con la temática de harry potter.
En cada turno, los jugadores elegirán un movimiento de cada personaje en su equipo.
Cuando la vida de todos los personajes de un jugador llega a 0, este pierde.


### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Hechizo <br>2. CRUD Jugador <br>3. CRUD Nivel|
|CRUD dependiente|1. CRUD Mago {depende de} CRUD Hechizo <br>2. CRUD Partida {depende de} CRUD Jugador y CRUD mago <br> CRUD Turno depende de Partida <br> CRUD Estado|
|Listado<br>+<br>detalle| 1. Listado de mejores jugadores => detalle CRUD Jugador<br> 2. Listado de Magos más usados => detalle CRUD Mago|
|CUU/Epic|1. Jugar una Partida|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
