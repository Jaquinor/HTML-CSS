***** DOCUMENTACIÓN TÉCNICA *****

# HTML_CSS
Entrenamiento en Free Code Camp
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

***** ENCUESTA *****

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

