# DeBarrio
[link a Heroku](https://sheltered-hamlet-29880.herokuapp.com/)

Proyecto de integración de contenidos en Desafío Latam G28 Full Stack

El proyecto es un sistema de ventas web constriudo con Ruby on Rails 5.2.3 y base de datos Postgresql

El diagrama conceptual muestra las principales entidades con las que trabajará la aplicación:

![alt text][concept]

[concept]: /debarrio.png "Diagráma conceptual"

El tablero Trello con el backlog y las historias de usuario está disponible en el siguiente link:

[Tablero Trello](https://trello.com/b/GsLUXZJs/almacen-de-barrio)

El diseño inicial de la base de datos (no implementado aún) contempla las siguientes tablas/modelos con las relaciones indicadas.

![alt text][logic]

[logic]: /logic_diagram.png "Diagráma lógico"


## Pasos para levantar el proyecto

- Clonar el repo.
- rails db:create
- rails db:migrate
- rails db:seed
- rails s
- enjoy!