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
El Sistema es una plataforma de pronósticos de Fórmula 1, en donde cada usuario ingresa sus pronósticos y compite con otros, en un ranking general o en torneos privados


### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario <br>2. CRUD Escuderia <br>3. CRUD Circuito|
|CRUD dependiente|1. CRUD Piloto {depende de} CRUD Escuderia <br>2. CRUD Carrera {depende de} CRUD Escuderia, CRUD Circuito y CRUD piloto |
|Listado<br>+<br>detalle| 1. Listado de Pilotos => detalle CRUD Piloto<br> 2. xxx|
|CUU/Epic|1. |


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Carrera {depende de} CRUD Escuderia, CRUD Circuito y CRUD piloto |
|Listado<br>+<br>detalle| 1. Listado de Usuarios con mejores Usuarios => detalle CRUD Jugador 2. Listado Carreras => detalle CRUD Carrera|
|CUU/Epic|1. El administrador registra los resultados de una Carrera <br>2. El usuario registra la prediccion de una carrera<br>3. xxx|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1.  <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Crear Torneo privado <br>2. xxx|
|Otros|1. Envío de recordatorio de reserva por email|
