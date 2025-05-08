# Propuesta TP DSW

## Grupo
### Integrantes
* Leg 53084 - Moretti Yrure, Pedro
* Leg 52222 - Bernard, Bruno

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Tema
### Descripción
*2 a 6 líneas describiendo el negocio (menos es más)*<br>
El Sistema es una plataforma de predicciónes de Fórmula 1, en donde cada usuario ingresa sus predicciones y compite con otros para intentar adivinar la mayor cantidad de resultados antes de que se corran las carreras. 


### Modelo
![image](https://github.com/user-attachments/assets/498550ae-5080-486e-a9c0-031d4cde2e1f)


*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario <br>2. CRUD Escuderia|
|CRUD dependiente|1. CRUD Piloto {depende de} CRUD Escuderia <br>|
|Listado<br>+<br>detalle| 1. Listado de Pilotos => detalle CRUD Piloto<br> |
|CUU/Epic|1. Registrar Usuario |


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Circuito <br>2. CRUD Carrera {depende de} CRUD Escuderia, CRUD Circuito y CRUD piloto |
|Listado<br>+<br>detalle| 1. Listado Carreras => detalle CRUD Carrera <br>2. Listado de Usuarios con mejores Predicciones => detalle CRUD Usuario |
|CUU/Epic|1. El usuario registra la prediccion de una carrera<br>2. El administrador registra los resultados de una Carrera <br>3. xxx|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Ranking de usuarios en un torneo privado |
|CUU/Epic|1. Ingresar los resultados automáticamente mediante una API <br>2.  Crear Torneo privado <br>3. Realizar un post|
|Otros| - |
