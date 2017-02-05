# WePlanning </br>
## ¿Qué es WePlanning? </br>
Se trata de una web donde los usuarios pueden publicar planes que han realizado o proponer nuevos planes indicando el lugar, el precio, el tiempo, el número de personas, y dando una descripción en la que pueden aparecer fotografías. Cada usuario visualizará una página de inicio con planes personalizados, podrá valorar y comentar planes de otros usuarios y subir a la página web sus planes.

## Entidades principales </br>
**Usuario:** El usuario tendrá nombre, apellidos, ubicación y lista de amigos y podrá añadir planes y valorar y comentar planes de otros usuarios.</br>
**Patrocinador:** Se trata de un perfil de empresa que tendrá planes patrocinados, nombre, email, página web y seguidores.</br>
**Plan:** Los planes podrán ser experiencias pasadas o propuestas, contarán con una ubicación, una hora, usuarios que asisten o han asistido y una descripción. Estos planes podrán ser patrocinados por un patrocinador o ser un plan de usuario simple. </br>
**Categoría de planes:** Los planes se podrán clasificar en distintas categorías nocturnos, escapadas, deportes, gastronomía, cultural, ocio, etc...</br>
**Comentario/Valoración:** Los planes podrán tener valoraciones y comentarios con imágenes adjuntas.</br>

## Integrantes del equipo de desarrollo </br> 
Rubén Golderos Serrano, r.golderos@alumnos.urjc.es, rgolderos</br>
Guillermo Navas García, g.navasg@alumnos.urjc.es, westernsquad</br>
Jorge Sánchez Márquez, j.sanchezmarq@alumnos.urjc.es, jorge0594</br>
Alex Gómez Uceda, a.gomezuc@alumnos.urjc.es, alexgomezuceda</br>

## Trello  https://trello.com/b/eZYgeXfU/weplanning


## Capturas de pantalla </br>

### Index (Página principal) 3 Index-logged </br>

Página principal de la web.Se visualizarán los planes más votados por la comunidad y se podrán filtrar por categorias y regiones.</br>

Si nos encontramos logueados en la web lo único que sufrirá cambios será la barra de navegación(Estos cambios en la barra de navegación se aplicarán en todos los HTML correspondientes a usuarios logueados):</br>

![navbar-logged][img4]</br>


![index1][img1]</br>
![index2][img2]</br>
![index3][img3]</br>

[img1]:/IMG/index1.png
[img2]:/IMG/index2.png
[img3]:/IMG/index3.png
[img4]:/IMG/navbar-logged.png

### ProfileHTML y ProfileHTML-logged</br>

Html en el cual de mostrar los datos del perfil de un usuario , su ubicación(si la ha añadido), el avatar y la lista de sus amigos.</br>

![profile][img4]</br>

Si el usuario se encuentra logueado en el sistema podrá accedetr a su perfil, donde se aparecerá un botón de color azul para poder agregar amigos a su lista, como una serie de botones para podificar su perfil, su ubicación y  agregar o eliminar amigos.</br>

La barra de navegación en el caso de estar logueados se mostrará como hemos mostrado antes

![profile-buttom][img5] "Botones de modificación"</br>
![button-agregar][img6] "Botón de añadir amigo"</br>

[img4]:/IMG/profile.png
[img5]:/IMG/profile-button.png
[img6]:/IMG/button-agregar.png

### SponsorHTML y SponsorHTML-logged</br>

Html en el que se mostrar los datos el perfil de usuario el cual es una empresa.</br>

[img7][sponsor]</br>

Si la empresa se encuentra logueada y visita su perfil desaparecera el botón "Seguir sponsor" y podrá modificar los datos de su perfil.</br>

[img7]:/IMG/sponsor.png

### Plan y Plan-logged </br>

Se mostrará una imagen del plan, su valoración y los comentarios de los usuarios.</br>

![plan][img8]</br>

En el caso de que nos encontremos logueados, se nos dará la posibilidad de añadir comentarios. Aparecerá un botón con el que podremos confirmar nuestra asistencia al evento.</br>

![plan-logged][img9]</br>

[img8]:/IMG/plan.png
[img9]:/IMG/plan-logged.png

### Newplan</br>

Formulario en que crearemos un nuevo plan que aparecerá a los usuarios de la página </br>

![newPlan][img10]</br>

[img10]:/IMG/newPlan.png

### Aboutus y aboutus-logged</br>

Se mostrará una pequeña descripción sobre el contenido de la página y su temática.

![aboutus][img11]</br>

En el caso de estar logueados lo único que cambiará sera la barra de navegación.

[img11]:/IMG/aboutus.png

### Contact </br>

Formulario con el cual se podra enviar un e-mail con sugerencias, quejas, incidencias etc- a los desarrollladores de la web.</br>

![contact][img12]</br>

[img12]:/IMG/contact.png

### Register</br>

Formulario con los datos que debemos rellenar para poder crearnos una cuenta en la web.</br>

![register][img13]</br>

[img13]:/IMG/register.png

