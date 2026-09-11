# Propuesta TP DSW

## Grupo
### Integrantes
* 52834 - Gonzalez, Milagros Magali
* 52088 - Tapia, Elias 

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Tema
### Descripción
En T&M ayudamos a las personas a encontrar su lugar ideal de una forma sencilla y cercana. A través de la página web se pueden ver propiedades, pedir tasaciones para vender con mayor seguridad y también organizar contratos sin tantas complicaciones. Además, con el apoyo en garantías y trámites, buscamos que alquilar o vender sea más fácil, claro y sin problemas.

### Modelo
<img width="1622" height="1231" alt="der drawio" src="https://github.com/user-attachments/assets/48f9fe05-26ff-477e-9701-e4c55124a04e" />
https://drive.google.com/file/d/1WcXHiGiRD_MX17PG10kQL8Yz_I6BbfgU/view?usp=sharing


## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Provincia<br>2. CRUD Tipo Inmueble|
|CRUD dependiente|1. CRUD Localidad {depende de} CRUD Provincia|
|Listado<br>+<br>detalle| 1. Listado de Inmuebles filtrado por Tipo de Inmueble y Localidad, muestra descripción, estado y tipo => detalle muestra datos completos del inmueble, ubicación GPS, tamaño, propietario y sus habitaciones.|
|CUU/Epic|1. 1. Agendar y registrar el resultado de una Visita a un Inmueble (vincula Cliente, Corredor, Inmueble, con fecha, hora y comentarios).|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Localidad<br>2. CRUD Tipo Habitacion<br>3. CRUD tipos garantia<br>4. CRUD Usuarios(Cliente, Corredor, Propietario)<br>5. CRUD Inmuebles<br>6. CRUD Habitacion<br>7. CRUD Garante<br>7. CRUD Contratos<br>7. CRUD Pago|
|CUU/Epic|1. Confeccionar un Contrato (vincula Inmueble, Cliente, Corredor y Garante, estableciendo las condiciones del alquiler/venta)<br>2. Registrar el Pago mensual de un Contrato|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados ||
|CUU/Epic||
|Otros|1. Envío de recordatorio de reserva por email|

