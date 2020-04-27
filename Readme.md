# :book: estuDÍA

El objetivo de este proyecto es construir una Red Social, Single-Page Application (SPA), responsiva en la que podamos escribir, leer, actualizar y eliminar datos. Es el primer proyecto del track FrontEnd de Laboratoria.
  

### :bulb: SELECCIÓN DE IDEA

La temática elegida fue educación **estuDÍa** es una red social en la que los usuarios tengan interés ingresar a la educacion superior especificamente al Instituto Politécnico Nacional. 


### :girl: :boy: USUARIOS

**estuDÍa** va dirigida a todas aquellas personas sin importar, edad, sexo u ocupación que quieran cursar estudios de nivel superior en el Instituto Politécnico Nacional.

### :rotating_light: PROBLEMÁTICA

En el año 2019, de los 92 mil aspirantes que concursarón para obtener un lugar en el nivel superior del Instituto Politécnico Nacional (IPN), sólo 26%, equivalente a 24 mil jóvenes, tuvó la oportunidad de estudiar en una de sus 66 carreras, en la modalidad escolarizada o no escolarizada. 

En México la calidad educativa es deficiente y no se ecuentra estandarizada en las escuelas, en el caso de la eduación media superior los planes de estudio varian de una institución eduactiva a otra, por ejemplo el plan de estudio de un CONALEP y de un COBACH no son los mismos y la brecha educativa es aún más pronunciada en las escuelas del interior de la república. 

La UNAM y el IPN dos de las universidades más grandes del país cuentan con sus propias instituciones de nivel medio superior (CCH,ENP y CECYT) en las cuáles los planes de estudio están diseñados para que sus egresados sean capaces de realizar y aprobar sus respectivos examenes de admisión para la educación superior. Sin embargo muchos estudiantes procedentes del interior de la republica, o de instituciones con poca calidad educativa se enfrentan con un vedadero reto a la hora de estudiar y entender temarios de exámenes de ingreso al IPN o a la UNAM. 


### :computer: ¿QUÉ PROPONEMOS?

**estuDÍA** se crea con el objetivo de crear una red de apoyo para que llas personas interesadas en llevar a cabo el proceso de admisión al Instituto Politécnico Nacional, es un espacio dónde los usuarios por medio de publicaciones puedan compartir, tips, experiencias y cualquier cosa que crean que pueda ayudar a otros a realizar un exámen de selección e inciar la etapa universitaria y así el proceso sea más fácil y solidarido entre los aspirantes. 


### :hourglass_flowing_sand: ¡A TRABAJAR! 

Para poder tener una distribución homogénea sobre las tareas a realizar, estar informadas de las actividades, aportar ideas nos apoyamos de la herramienta "Pojects" de GitHub, así nuestro SCRUM podía ser consultado y modficado por cualquiera de la tres integrantes del equipo.
<img src="src/img/projects.png"> 


### :bust_in_silhouette: HISTORIAS DE USUARIO 

:one: 
**YO** como usuario nuevo.
**QUIERO** poder crear una cuenta con email y password válidos.
**PARA** para poder iniciar sesion e ingresar a la red social.

:two: 
**YO** como usuario nuevo
**QUIERO** poder tener la opción de iniciar sesión con mi cuenta de Google o Facebook
**PARA** para ingresar a la red social sin necesidad de crear una cuenta de email válido

:three: 
**YO** como usuario loggeado
**QUIERO** crear, guardar, modificar en el mismo lugar (in place) y eliminar una publicación (post) privada o pública, que puede ser una frase o una imagen

:four: 
**YO** Como usuario loggeado 
**QUIERO** poder ver todos los posts públicos y privados que he creado hasta ese momento, desde el más reciente hasta el más antiguo
**PARA** poder cambiar la configuración de privacidad de mis post.

:five: 
**YO** como usuario loggeado
**QUIERO** dar like y llevar un conteo de likes en mi publicación así como poder escribir, guardar, editar o eliminar un comentario en mi publicación

:six: 
**YO** como usuario loggeado 
**QUIERO** poder ingresar a la red social 
**PARA** para poder visualizar los datos de mi perfil creado o editarlo.


### :heavy_check_mark: CRITERIOS DE ACEPTACIÓN

-Si el mail o password no es válido, al momento de logearme, debo poder ver un mensaje de error.
-Debe ser visible si hay algún mensaje de error.
-Debo poder ver esta página de creación en Móviles y desktop (responsive).
-No debe necesitar recargar la página para crear una cuenta (SPA).
-Debo poder publicar texto e imagenes.
-El usuario debe poder filtrar, editar y eliminar sus publicaciones. 


### :heavy_check_mark: DEFINICIÓN DE TERMINADO 

-La funcionalidad cumple satisface los criterios de aceptación.
-La funcionalidad tiene test unitarios.
-El diseño visual corresponde al prototipo de alta fidelidad.-
-El código de esta funcionalidad recibió code review.
-La funcionalidad esta desplegada y pública para ser probada.
-La funcionalidad fue probada manualmente.
-Se hicieron pruebas de usuabilidad y se implementó el feedback si se consideró necesario.


### :vhs: PROTOTIPO DE BAJA FIDELIDAD
Durante esta etapa diseñamos con lápiz la interfaz de usuario, pensamos el nombre de nuestra aplicación web,la distribución de los elementos a consultar y cómo se vería en una pantalla de celular. 
<img src="src/img/init.jpg"> 
<img src="src/img/init0.jpg"> 

Buscamos el feedback en cinco ocasiones de nuestras compañeras de bootcamp.


### :iphone: PROTOTIPO DE ALTA FIDELIDAD

Para poder desarrollar esta parte aplicamos el feedback que nos dieron nuesros coach y nuestras compañeras, también tomamos en cuenta los colores oficiales del Instituto Politécnico Nacional: guinda y blanco. El prototipo de alta fidelidad se desarrolló en Figma.

<img src="src/img/inicioSesión.png"> 
<img src="src/img/noticias.png"> 
<img src="src/img/publicaciones.png"> 
<img src="src/img/modal.png"> 


### :pencil: OBJETIVOS DE APRENDIZAJE 

### HTML y CSS

* [ ] [HTML semántico](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
* [ ] [CSS `flexbox`](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [ ] Construir tu aplicación respetando el diseño realizado (maquetación).

### DOM y Web APIs

* [ ] [Manipulación dinámica del DOM](https://developer.mozilla.org/es/docs/Referencia_DOM_de_Gecko/Introducci%C3%B3n)
* [ ] [History API](https://developer.mozilla.org/es/docs/DOM/Manipulando_el_historial_del_navegador)
* [ ] [`localStorage`]

### Javascript

* [ ] [Uso de callbacks](https://developer.mozilla.org/es/docs/Glossary/Callback_function)
* [ ] [Consumo de Promesas](https://scotch.io/tutorials/javascript-promises-for-dummies#toc-consuming-promises)
* [ ] Uso ES modules
([`import`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
| [`export`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export))

### Firebase

* [ ] [Firestore](https://firebase.google.com/docs/firestore)
* [ ] [Firebase Auth](https://firebase.google.com/docs/auth/web/start)
* [ ] [Firebase security rules](https://firebase.google.com/docs/rules)
* [ ] [Uso de onSnapshot](https://firebase.google.com/docs/firestore/query-data/listen)
| [onAuthStateChanged](https://firebase.google.com/docs/auth/web/start#set_an_authentication_state_observer_and_get_user_data)

### Testing

* [ ] [Testeo de tus funciones](https://jestjs.io/docs/es-ES/getting-started)
* [ ] [Testeo asíncrono](https://jestjs.io/docs/es-ES/asynchronous)
* [ ] [Mocking](https://jestjs.io/docs/es-ES/manual-mocks)

### Colaboración en Github

* [ ] Branches
* [ ] Pull Requests
* [ ] Tags

### Organización en Github

* [ ] Projects
* [ ] Issues
* [ ] Labels
* [ ] Milestones

### Buenas prácticas de desarrollo

* [ ] Modularización
* [ ] Nomenclatura / Semántica
* [ ] Linting


