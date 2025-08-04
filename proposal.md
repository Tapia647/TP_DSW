# Propuesta TP DSW

## Grupo
### Integrantes
52060 - Albuerne, Celeste
52834 - Gonzalez, Milagros
52088 - Tapia, Elias

### Repositorios
* [Frontend app](https://github.com/Tapia647/TP_DSW/tree/main/src/frontend)
* [Backend app](https://github.com/Tapia647/TP_DSW/tree/main/src/backend)

## Tema
Fundacion de animales
### Descripción
Sistema para la gestión integral de adopciones en un refugio de animales.
Permite administrar animales heridos y disponibles para adopción, registrar a los interesados (adoptantes), y gestionar el proceso completo de adopción. Además, incluye funcionalidades para la aceptación y gestión de donaciones, y el registro/asignación de voluntarios para distintas tareas del refugio.

### Modelo
[falta imagen](https://app.diagrams.net/#G1lBC-9nAWmxUkkKFlTxdfDu5I6onGfyOg#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D)

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Adopcion<br>2. CRUD Situacion<br>3. CRUD Especie<br>4. CRUD Adminitrador|
|CRUD dependiente|1. CRUD Animal {depende de} CRUD ----<br>2. CRUD prof?? {depende de} CRUD ----|
|Listado<br>+<br>detalle| 1. Lista de animales disponibles filtrado por tamaño, muestra nombre, edad, estado, tiempo en el refugio => detalle CRUD Animal<br> 2. ------ => -------|
|CUU/Epic|1. Tratamiento<br>2. -----|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Donaciones<br>2. CRUD ----<br>3. CRUD ----<br>4. CRUD ----<br>5. CRUD -----<br>6. CRUD -----<br>7. CRUD ----|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. ----|
|CUU/Epic|1. Cancelar adopcion<br>2. ----|
|Otros|1. Envío de recordatorio para control de estado de animal por email|

