![Mapa](http://www.digitalsurgeons.com/wp-content/uploads/2010/12/geolocation.png)

# Mapa turístico

Proyecto creado para y por los alumnos de Mejorandola. El objetivo de este proyecto es crear una aplicación donde todos los que deseemos participemos para crear una aplicación. Una aplicación creada para demostrar qué hemos aprendido y ganar una nueva experiencia colaborando en equipo. Si no sabes o piensas que tienes poco que aportar no te preocupes, otro de los objetivos es que todos aprendamos y nos apoyemos los alumnos.

Todos estáis invitados a participar en este miniproyecto. ¡Animo!

## La idea

Una aplicación web donde mostrar los lugares de tu ciudad o cualquier sitio del que estés orgulloso, pudiendo subir una foto y hacer un comentario. De momento sólo eso, ya se extenderá con un sistema de puntuaciones y comentarios de otros usuarios y otras ideas que se os ocurra.

## Cómo colaborar

Este miniproyecto en realidad es una extensión a la ponencia del día 9 de abril '[Geolocalización en NodeJS](https://www.youtube.com/watch?v=b3nvLvKnLyw&feature=c4-feed-u)', donde explicamos la base del código y cómo trabajar con mapas, recomiendo echarle un ojo si no has trabajado antes con mapas y geolocalización.

¿Qué necesitamos? ¡A todos vosotros! Seas diseñador, front end, back end o comunicador. Como dice el dicho, muchos granitos de arena hace una montaña.

**Si quieres colaborar tan sólo tienes que hacer un "Fork" del código y solicitar un "Pull Request" para añadir tu aportación al proyecto**.

A los que más colaboren o desean participar activamente con el proyecto se les dará acceso al gestor de tareas (Do.com) para desarrollar el proyecto de una forma más eficiente. Dado que en Twitter no es fácil mantener mensajes privados, el primer contacto lo haremos por mail. Entonces, si quieres participar en el proyecto envíamos un correo a [undakel@gmail.com](mailto:undakel@gmail.com). De esta forma se crearía un pequeño equipo.

Si sólo quieres dar una opinión, comentario o sugerencia puedes enviar un correo a la dirección del párrafo anterior o puedes usar la pestañita de Issues de Github (preferentemente).

## Recomendaciones antes de empezar

No son normas pero si nos ayudará a trabajar en equipo.

* **Comenten el código que hacen**. No hace falta comentar cada linea que hacen pero si explicar brevemente y en español.
* **Siempre comentar los commits**. No dejen commits con mensajes vacíos o con información vaga como 'cambio en menu', poner algo como 'cambio de color del menu'.

## El desarrollo (v1.0)

Para esta primera versión la aplicación será soportada sobre Node Js y se ha pensado hacer el desarrollo en 3 fases:

### Fase 1 - Modelo de datos y gestión de usuarios

En esta primera fase vamos a definir cómo va ser nuestra base de datos para guardar usuarios, lugares y comentarios. Por último terminaremos por incoporar un sistema para gestionar registros y acceso de usuarios.


### Fase 2 - Mapa, introducción de lugares y sistema de comentarios

En esta fase vamos a hacer el formulario para agregar lugares, imágenes y un pequeño comentario, además de mostrarlo en el mapa en tiempo real.


### Fase 3 - Maquetación de la aplicación y adaptación a dispositivos móviles

Puliremos nuestra aplicación para hacerlo más hermosa y además que se vea bien incluso desde un cepillo de dientes con pantalla y conexión a internet.

## Cómo empezar

Recuerden que deben tener **instalado Node Js**.

Antes de arrancar por primera vez la aplicación debemos instalar primero las librerías:

	npm install
	
Y para iniciar la aplicación podemos hacerlo simplemente tecleando:

	node app
	
Si teneís dudas podeís revisar las instrucciones de [mapa-tiempo-real](https://github.com/davidsingal/mapa-tiempo-real), escribirnos o abrir un ticket en el apartado de Issues de Github (preferentemente).


## Recursos

* [Cómo hacer un fork](http://aprendegit.com/fork-de-repositorios-para-que-sirve/?goback=%2Egde_3956944_member_214176162)
* [Mantener tu fork al día](http://aprendegit.com/mantener-tu-fork-al-dia/)
* [Qué es un pull request](http://aprendegit.com/que-es-un-pull-request/)

---

#### Créditos y agradecimientos

Iniciativa creada por @mikenieva y @davidsingal, gracias a @mejorandola por el curso de Diseño y desarrollo Web online
