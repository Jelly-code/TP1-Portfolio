### Comentarios Generales

Javiera, en primer lugar tengo que felicitarte por un un excelente trabajo. Me maravilla la cantidad de detalles que abundan a cada paso en tu TP y hacen un efecto maravilloso. Los colores, la eleccion de imagenes, detalles como el subrayado en tu nombre y la sombra de la nav, habla maravillas de tu capacidad de aprendizaje, tu curiosidad y tus ganas de aprender.

A nivel estructura tu página web en general cumple los requisitos pedidos. Si bien no puedo evaluar el aspecto visual, ya que no es parte del programa ni una habilidad requerida para una desarrolladora front end, sí quiero comentar lo linda que se ve tu web. En ambas secciones de tarjetas no se cumple tan bien la consigna, ya que no quedaron acomodadas de la manera que esperamos. Te comento mas en detalle como solucionar eso. 

- En las resoluciones menores a 1100px tu titulo principal se ve diferente al modelo, ya que tu nombre se acomoda al centro y el resto del texto a la izquierda. 
- En tablet, tus tarjetas de Proyectos quedan muy grandes, y tiradas hacia la izquierda, cuando quedaria mejor y seguiria mejor la consigna que fuesen dos en fila. 
- En todas tus resoluciones las tarjetas de proyectos estan alineadas hacia la izquierda cuando deberian verse centradas. 
- En cualquier resolucion de celulares tenes un scroll horizontal (lo vas a identificar como una barra blanca a la derecha) provocado por elementos en especifico que rebalsan su contenedor al ser mas anchos que el total del body. (Quiza no lo veas desde la compu, pero si entrando desde un celular). La culpable en tu trabajo es la imagen de la seccion principal, que tiene un width fijo de 600px, y obviamente esa medida es mayor que cualquier celular. Si le damos al div .imagen, solo en celulares, un width del 100%, este problema se soluciona. 

Para que las tarjetas de Mis Proyectos se vean centradas debemos hacer dos cosas:
- Agregar a .seccion3 la orden display: flex; flex-direction: column; align-items: center. Tambien quitarle el padding a los costados. 
- Darle a .contenedor-proyectos, en cada media query, una max-width distinta que permita que se entren respectivamente tres, dos y una tarjeta. En desktop, 1200px. En medidas menores a 1200px, 800px. En medidas menores a 800px, 400px. 
Esa es una posible solucion, obviamente se pueden encarar otras. 

Tus nombres de clases, cuando los pensas y los haces a conciencia, son muy buenos. Cumplis bien el requisito de que sean descriptivos en un sentido funcional: describir que es un elemento y qué hace, no necesariamente como se ve. Entiendo que a veces es muy dificil pensarlos todos y te quedas sin ideas, lo que se refleja en algunos que no estan bien, pero tomate el trabajo de retomarlos al final y recorrerlos para ver si se pueden mejorar. Si mañana decidis agregar una seccion nueva entre tu seccion-presentacion y tu seccion-2, todos tus nombres de secciones van a dejar de tener sentido. seccion2, 3, ya no reflejaran tu pagina y habra que cambiarlos tanto en HTML como en CSS, y en cualquier JS que eventualmente tengas. Si esta fuera una web profesional, que tiene cambios a cada momento, te podras imaginar que pesadilla seria hacer ese mantenimiento. Pero "seccion-presentacion" siempre sera la seccion presentacion, aunque este arriba de todo o al final, aunque cambie por completo su estructura. Por eso, ese es un mejor nombre que "Seccion 3". 

Se nota el esfuerzo por reutilizar codigo, el uso correcto de etiquetas semanticas y el correcto orden de jerarquias entre secciones, titulos, etc. Gran trabajo en ese sentido. 

Menciono lo bien ordenado de tu proyecto en github, y lo prolija que fuiste commit a commit agregando los cambios de a poco y describiendolos bien en tus mensajes.

Tengo que destacar la increible prolijidad de tu HTML y tu CSS; lo maravillosamente tabulado y ordenado que esta todo. Las poquisimas cosas innecesarias. Me costó bastante encontrar cosas a corregir en esos archivos; espero que estes muy orgullosa, porque se nota que hiciste este trabajo a conciencia y con mucho esfuerzo. 

Sé que puedo ser un poco quisquillosa en las correcciones. No es la intención que sientas que hiciste un mal trabajo, porque no es así: tu trabajo es fantástico. Mi tarea es comentarte todo lo que vea para que sea más fantástico aún. 


### Nota final: 8

Nota desagregada: 
✅ Estructura correcta de documento HTML.
✅ Respeta la consigna 
✔️ Respeta el diseño dado --> con observaciones
✔️ Responsive funciona correctamente --> con observaciones
✅ Código bien indentado. 
✅ Comentarios que permiten mejorar la legibilidad del código.
✅ Uso correcto de etiquetas semánticas.
✔️ Buenos nombres de clases --> con observaciones
✅ Reutilización de estilos.
✅ Código CSS ordenado.
✅ Commits con mensajes adecuados.
