# HTML-CSS
Entrenamiento en Free Code Camp

***** PROYECTO 1 FORMULARIO DE ENCUESTA *****

Crea un formulario de encuesta
Objetivo: Crea una aplicación que sea funcionalmente similar a https://survey-form.freecodecamp.rocks
Historias de usuario:
1.	Debes tener un título de página en un elemento h1 con un id de title
2.	Debes tener una corta explicación en el elemento p con un id de descripcion
3.	Debes tener un elemento form con un id de survey-form
4.	Dentro del elemento form, debe ser required (requerido) ingresar tu nombre en un campo de input que tenga un id de name y un type de text
5.	Dentro del elemento form required (requerido) ingresar tu nombre en un campo de input que tenga un id de email
6.	Si ingresas un email que no tenga el formato correcto, verás un error de validación HTML5
7.	Dentro del formulario, puedes ingresar un número en un campo de input que tenga un id de number
8.	La entrada de números no debe aceptar caracteres no numéricos, ya sea impidiendo que los escribas o mostrando un error de validación HTML5 (dependiendo del navegador).
9.	Si ingresas un número que esté fuera del rango de números permitido, que es definido por los atributos min y max, verás un error de validación de HTML5
10.	Para los campos de entrada de nombre, email y número, puedes ver los correspondientes elementos label en el formulario, que describen el propósito de cada campo con los siguientes id: id="name-label", id="email-label" y id="number-label"
11.	Para los campos de entrada de nombre, email y número, podrás ver un texto provisional que da una descripción o instrucciones para cada campo
12.	Dentro del elemento form, debes tener un elemento desplegable select con un id de dropdown con al menos dos opciones para elegir
13.	Dentro del elemento form, puedes seleccionar una opción de un grupo de al menos dos botones de radio que son agrupado utilizando el atributo name
14.	Dentro del elemento form, puedes seleccionar varios campos en una serie de casillas de verificación, cada una debe tener un atributo value
15.	Dentro del elemento form, se te presenta un textarea para comentarios adicionales
16.	Dentro del elemento form, se te presenta un botón con un id de submit para enviar todas las entradas
Completa las historias de usuario y pasa todas las pruebas a continuación para completar este proyecto. Dale tu propio estilo personal. ¡Feliz día programando!
Nota: Asegurate de agregar <link rel="stylesheet" href="styles.css"> en tu HTML para enlazar tu hoja de estilos y aplicar tu CSS
Pruebas
•	Debes tener un elemento h1 con un id de title.
•	Tu #title no debe estar vacío.
•	Debes tener un elemento p con un id de description.
•	Tu #description no debe estar vacío.
•	Debes tener un elemento form con un id de survey-form.
•	Debes tener un elemento input con un id de name.
•	Esperando:Tu #name debe tener un type de text.
•	Tu #name debe requerir una entrada.
•	Tu #name debe ser descendiente de #survey-form.
•	Debes tener un elemento input con un id de email.
•	Tu #email debe tener un type de email.
•	Tu #email debe requerir una entrada.
•	Tú #email debe ser descendiente de #survey-form.
•	Debes tener un elemento input con un id de number.
•	Tu #number debe ser descendiente de #survey-form.
•	Tu #number debe tner un typede number.
•	Tu #number debe tener un atributo min con un valor numérico.
•	Tu #number debe tener un atributo max con un valor numérico.
•	Debes tener un elemento label con un id de name-label.
•	Debes tener un elemento label con un id de email-label.
•	Debes tener un elemento label con un id de number-label.
•	Tu #name-label debe contener un texto que describa la entrada.
•	Tu #email-label debe contener un texto que describa la entrada.
•	Tu #number-label debe contener un texto que describa la entrada.
•	Tu #name-label debe ser descendiente de #survey-form.
•	Tu #email-label debe ser descendiente de #survey-form.
•	Tu #number-label debe ser descendiente de #survey-form.
•	Tu #name debe tener el atributo placeholder y un valor.
•	Tu #email debe tener un atributo placeholder y un valor.
•	Tu #number debe tener un atributo placeholder y un valor.
•	Debes tener un campo select con un id de dropdown.
•	Tu #dropdown debe tener al menos dos elementos option seleccionables (no deshabilitados).
•	Tu #dropdown debe ser descendiente de #survey-form.
•	Debes tener al menos dos elementos input con un type de radio (botones de radio).
•	Debes tener al menos dos botones de radio que sean descendientes de #survey-form.
•	Todos tus botones de radio deben tener un atributo value y un valor.
•	Todos tus botones de radio deben tener un atributo name y un valor.
•	Cada grupo de botón de radio debe tener al menos 2 botones de radio.
•	Debes tener al menos dos elementos input con un type de checkbox (casillas de verificación) que sean descendientes de #survey-form.
•	Todos tus casillas de verificación dentro de #survey-form deben tener un atributo value y un valor.
•	Debes tener al menos un elemento de textarea que sea descendiente de #survey-form.
•	Debes tener un elemento input o button con un id de submit.
•	Tu #submit debe tener un type de submit.
•	Tu #submit debe ser descendiente de #survey-form.

***** PROYECTO 2 PÁGINA DE HOMENAJE *****

Construye una página de homenaje
Objetivo: Crea una aplicación que sea funcionalmente similar a https://tribute-page.freecodecamp.rocks
Instrucciones:
1.	Tu página de homenaje debe tener un elemento main con un id correspondiente de main, que contiene los demás elementos
2.	La página debe tener un elemento id de title, el cual contendrá una cadena de caracteres (p. ej. texto), que describe el tema de la página de homenaje (p. ej. "Dr. Norman Borlaug")
3.	La página debe tener tanto un elemento figure o un elemento div con un id de img-div
4.	Dentro del elemento #img-div debe tener un elemento img con su correspondiente id="image"
5.	Dentro del elemento #img-div, debes ver un elemento con un id="img-caption" correspondiente que contiene contenido textual describiendo la imagen mostrada en #img-div
6.	Debe tener su correspondiente elemento id="tribute-info", que contendrá una descripción textual del sujeto de la página tributo
7.	Debes ver un elemento a con su id="tribute-link" correspondiente, que contiene información adicional sobre el tema de la página de homenaje. CONSEJO: Debes dar al elemento un atributo target y establecerlo como _blank para que tu enlace se abra en una nueva pestaña
8.	Tú #image debe usar las propiedades max-width y height para redimensionarse en función de la anchura de su elemento padre, sin sobrepasar su tamaño original
9.	Tu elemento img debe estar centrado con respecto al elemento que lo contiene
Completa las historias de usuario y pasa todas las pruebas a continuación para completar este proyecto. Dale tu propio estilo. ¡Feliz día programando!
Nota: Asegúrate de agregar <link rel="stylesheet" href="styles.css"> en tu HTML para enlazar tu hoja de estilos y aplicar tu CSS
Pruebas
•  Debes tener un elemento main con un id de main.
• Tu #img-div, #image, #img-caption, #tribute-info, y #tribute-link deben ser descendientes de #main.
•	Debes tener un elemento con un id de title.
•	Tu #title no debe estar vacío.
•	Debes tener un elemento figure o div con un id de img-div.
•	Debes tener un elemento img con un id de image.
•	Tu #image debe ser descendiente de #img-div.
•	Deberías tener un elemento figcaption o div con un id de img-caption.
•	Tu #img-caption debe ser descendiente de #img-div.
•	Tu #img-caption no debe estar vacío.
•	Debes tener un elemento con un id de tribute-info.
•	Tu #tribute-info no debe estar vacío.
•	Debes tener un elemento a con un id de tribute-link.
•	Tu #tribute-link debe tener un atributo href con un enlace.
•	Tu #tribute-link debe tener un atributo target establecido en _blank.
•	Tu elemento img debe tener un display de block.
•	Tu #image debe tener un max-width de 100%.
•	Tu #image debe tener un height de auto.
•	Tu #image debe estar centrado con respecto al elemento que lo contiene.

***** PROYECTO 3 DOCUMENTACIÓN TÉCNICA *****

Construye una página de documentación técnica
Objetivo: Crea una aplicación que sea funcionalmente similar a https://technical-documentation-page.freecodecamp.rocks
Historias de Usuario:
1.	Puedes ver un elemento main con su correspondiente id="main-doc", el cual abarcará el contenido principal de la página (documentación técnica)
2.	Dentro del elemento #main-doc, se pueden ver varios elementos section, cada uno con la clase main-section. Debe haber un mínimo de cinco
3.	El primer elemento dentro de cada .main-section debería ser un elemento header, el cual contendrá texto que describa el tema de esa sección.
4.	Cada elemento section con la clase main-section debería tener también un id que corresponda al texto de cada header contenido dentro de él. Cualquier espacio debe ser reemplazado por guiones bajos ( Ejemplo: La sección que contiene el encabezado "JavaScript and Java" debe tener un id="JavaScript_and_Java")
5.	Los elementos .main-section deberán tener al menos diez elementos p en total (no cada uno)
6.	Los elementos .main-section deberán tener al menos cinco elementos code en total (no cada uno)
7.	Los elementos .main-section deberán tener al menos cinco items li en total (no cada uno)
8.	Puedes ver un elemento nav con su correspondiente id="navbar"
9.	La barra de navegación deberá contener un elemento header, el cual contendrá texto que describa el tema de la documentación técnica
10.	Además, la barra de navegación deberá contener elementos de enlace (a) con la clase nav-link. Debe haber uno para cada elemento con la clase main-section
11.	El elemento header dentro de la #navbar debería ir antes que los elementos (a) de la barra de navegación
12.	Cada elemento con la clase nav-link debería tener texto que corresponda al texto del header de cada section (Ejemplo: Si tienes una seccion/encabezado "Hello world", tu barra de navegación debería tener un elemento que contenga el texto "Hello world")
13.	Al hacer click en un elemento de tu barra de navegación, la página debería dirigirse a la sección correspondiente del elemento #main-doc (Ejemplo: Si haces click en el elemento .nav-link que contiene el texto "Hello world", la página debería dirigirse al elemento section que tenga ese id y contenga el encabezado correspondiente)
14.	En dispositivos de tamaño normal (portatiles, computadoras de escritorio), el elemento con id="navbar" debe mostrarse en el lado izquierdo de la pantalla y siempre ser visible para el usuario
15.	Tu documentación técnica debe usar al menos una media query
Completa las historias de usuario y pasa todas las pruebas a continuación para completar este proyecto. Dale tu propio estilo personal. ¡Feliz día programando!
Nota: Asegúrate de agregar <link rel="stylesheet" href="styles.css"> en tu HTML para enlazar tu hoja de estilos y aplicar tu CSS

***** PROYECTO 4 PÁGINA DE PRODUCTO *****

Construye una página de inicio de producto
Objetivo: Crea una aplicación que sea funcionalmente similar a https://product-landing-page.freecodecamp.rocks
Historias de usuario:
1.	Tu página de inicio de producto debe tener un elemento header con un correspondiente id="header"
2.	Puedes ver una imagen dentro del elemento header con un correspondiente id="header-img" (Un logotipo sería una buena imagen aquí)
3.	Dentro el elemento #header, puedes ver un elemento nav con su correspondiente id="nav-bar"
4.	Puedes ver al menos tres elementos cliqueables dentro del elemento nav, cafda una con la clase nav-link
5.	Cuando hagas click en un botón .nav-link en el elemento nav, serás redireccionado a la sección correspondiente de la página de inicio
6.	Puedes ver un vídeo del producto incrustado con id="video"
7.	Tu página de inicio tiene un elemento form con un correspondiente id="form"
8.	Dentro del formulario, hay un campo input con id="email", donde puedes ingresar tu dirección de email
9.	El campo de entrada #email debe tener un marcador de texto para que los usuarios sepan para que sirve este campo
10.	El campo de entrada #email usa validación HTML5 para confirmar que el texto ingresado es una dirección de email
11.	Dentro del formulario, hay un input de tipo submit (enviar) con su correspondiente id="submit"
12.	Cuendo haces click en el elemento #submit, el email es enviado a una página web (Utiliza esta URL de pruebas: https://www.freecodecamp.com/email-submit)
13.	La barra de navegación siempre debe estar en la parte superior de la vista
14.	La página de inicio de tu producto debe tener al menos una consulta de medios
15.	Tu página de inicio del producto debe utillizar el flexbox CSS al menos una vez
Completa las instrucciones y pasa todas las pruebas a continuación para completar este proyecto. Dale tu propio estilo estilo personal. ¡Feliz día programando!
Nota: Asegúrate de agregar <link rel="stylesheet" href="styles.css"> en tu HTML para enlazar tu hoja de estilos y aplicar tu CSS
Pruebas
•	Aprobado:Debes tener un elemento header con un id de header.
•	Aprobado:Debes tener un elemento img con un id de header-img.
•	Aprobado:Tu #header-img debe ser descendiente de #header.
•	Aprobado:Tu #header-img debe tener un atributo src.
•	Aprobado:El valor del src de #header-img debe ser una URL válida (inicia con http).
•	Aprobado:Debes tener un elemento nav con un id de nav-bar.
•	Aprobado:Tu #nav-bar debe ser descendiente de #header.
•	Aprobado:Debes tener al menos 3 elementos .nav-link dentro del #nav-bar.
•	Aprobado:Cada elemento .nav-link debe tener un atributo href.
•	Aprobado:Cada elemento .nav-link debe estar enlazado a su elemento correspondiente en la página de aterrizaje (el valor que tiene el href es el id de otro elemento, por ejemplo, #footer).
•	Aprobado:Debes tener un elemento video o iframe con un id de video.
•	Aprobado:Tu #video debe tener un atributo src.
•	Aprobado:Debes tener un elemento form con un id de form.
•	Aprobado:Debes tener un elemento input con un id de email.
•	Aprobado:Tu #email debe ser descendiente de #form.
•	Aprobado:Tu #email debe tener el atributo placeholder con un texto marcador de posición.
•	Aprobado:Tu #email debe usar la validación HTML5 estableciendo su type a email.
•	Aprobado:Debes tener un elemento input con un id de submit.
•	Aprobado:Tu #submit debe ser descendiente de #form.
•	Aprobado:Tu #submit debe tener un type de submit.
•	Aprobado:Tu #form debe tener un atributo action de https://www.freecodecamp.com/email-submit.
•	Aprobado:Tu #email debe tener un atributo name de email.
•	Falló:Tu #nav-bar siempre debe estar en la parte superior de la ventana gráfica.
•	Falló:Tu página de aterrizaje de un producto debe usar por lo menos una consulta de medios.
•	Falló:Tu página de aterrizaje de un producto debe usar CSS Flexbox por lo menos una vez.


***** PROYECTO 5 PORTAFOLIO PERSONAL *****

Construye una página portafolio personal
Objetivo: Crea una aplicación que sea funcionalmente similar a https://personal-portfolio.freecodecamp.rocks
Historias de usuario:
1.	Tu portafolio debe tener una sección de bienvenida con un id de welcome-section
2.	La sección de bienvenida debe tener un elemento h1 que contenga texto
3.	Tu portafolio debe tener una sección de proyectos con un id de projects
4.	La sección de proyectos debe tener al menos un elemento con una class de project-tile para tener un proyecto
5.	La sección de proyectos debe tener al menos un enlace a un proyecto
6.	Tu portafolio debe tener una barra de navegación con un id de navbar
7.	La barra de navegación debe tener al menos un enlace donde puedas hacer clic para navegar a diferentes secciones de la página
8.	Tu portafolio debe tener un enlace con un id de profile-link, el cual abra tu GitHub o perfil de freeCodeCamp en una pestaña nueva
9.	Tu portafolio debe tener al menos una consulta de medios
10.	La altura de la sección de bienvenida debe ser igual a la altura de viewport
11.	La barra de navegación siempre debe estar en la parte superior del viewport
Completa las instrucciones y pasa todas las pruebas a continuación para completar este proyecto. Dale tu propio estilo personal. ¡Feliz día programando!
Nota: Asegúrate de agregar <link rel="stylesheet" href="styles.css"> en tu HTML para enlazar tu hoja de estilos y aplicar tu CSS
Pruebas
•	Esperando:Tu portafolio debe tener una sección "Welcome" con un id de welcome-section.
•	Esperando:Tu elemento #welcome-section debe contener un elemento h1.
•	Esperando:No debes tener ningún elemento h1 vacío dentro del elemento #welcome-section.
•	Esperando:Debes tener una sección "Projects" con un id de projects.
•	Esperando:Tu portafolio debe contener al menos un elemento con una clase project-tile.
•	Esperando:Tu elemento #projects debe contener al menos un elemento a.
•	Esperando:Tu portafolio debe tener una barra de navegación con un id de navbar.
•	Esperando:Tu elemento #navbar debe contener al menos un elemento a cuyo atributo href empiece con #.
•	Esperando:Tu portafolio debe tener un elemento a con un id de profile-link.
•	Esperando:Tu elemento #profile-link debe tener un atributo target de _blank.
•	Esperando:Tu portafolio debe usar al menos una consulta de medios.
•	Esperando:Tu elemento #navbar siempre debe estar en la parte superior del viewport






