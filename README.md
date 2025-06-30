# Java Bootcamp Starter Kit

El Java Bootcamp Starter Kit es un material escrito que busca ser el punto de partida para que una persona interesada haga un Bootcamp con el objetivo de enseñar a programar usando Java. El material está escrito con una licencia UPL 1.0 https://oss.oracle.com/licenses/upl/

El material busca solucionar algunos inconvenientes con la gran mayoría de material didáctico que existe, sea digital o impreso, sea pago o gratuito:

* Incluye un extenso número de ejercicios. La cantidad de ejercicios busca que el estudiante tenga que usar el concepto aprendido en muchos contexto para realmente solidificarlo. Los ejercicios tienen niveles de dificultad, ejercicios sin tasas de café considerados esenciales, y ejercicios con una tasa y con dos tasas.
* Además de ejercicios, el material presenta una manera de saber si la implementación del ejercicio es correcta, presentando varios inputs y su output esperado, inspirado por competencias de programación. Después el material usa assertions de JUnit para este efecto.
* Incluye varios ejemplos de código. Complementario a los ejercicios, el material tiene un ejemplo de código por cada concepto para que cada tema sea más que solo sintaxis.
* Foco en los conceptos y no en sintaxis. Para aprender a programar no se necesita conocer toda la sintaxis, lo más importante es que los conceptos sean claros. Sin un buen ejemplo, el mayterial no incluye toda la sintaxis de Java.
* Está escrito de una manera informal, como si fuera una conversación entre amigos, en parte inspirado por la serie Head First.
* Incluye consejos prácticos de una persona con experiencia trabajando en la industria de software desde 2008 porque nunca es demasiado temprano para enseñar sobre buenas prácticas.

## Herramientas

La herramienta inicial para escribir código es JShell. Esto permite que las personas puedan escribir funciones sin pensar en main(), en los modificadores public y static, y facilita la idea de cómo tomar input del usuario y el outpiut de este y obtener un autocompletado de métodos que son parte del API de Java.

Antes de empezar con el tema de ciclos, se hace el salto a un IDE para que los estudiantes puedan usar un debugger y entender mejor lo que hacen los programas. Para ese entonces el concepto de funciones está muy claro y agregar la idea de clases, main(), public y static resulta natural.

## Temas

El orden de los temas fue escogido cuidadosamente para cumplir con ciertos objetivos:

* Para reinforzar desde el inicio la importancia de las funciones, es el primer tema que se enseña. Igualmente, enseñar funciones tiene muchos beneficios adicionales
  - Todos los ejemplos de código se pueden hacer en el contexto de una función lo que hace sea claro cómo usarlos en la "vida real"
  - Todos los ejercicios se pueden explicar muy sencillamente como implementaciones que logren que un input seleccionado genere el output esperado.
  - Como se mencionó anteriormente, el salto de JShell a clases, main(), public y static resulta menos traumático.
* Se empieza con funciones y termina con objetos. La discusión sobre si es más importante la programación orientada por objetos que la programación funcional debería ser cosa del pasado, p.j. esta charla de Brian Goetz, Java Language Architect de Oracle "FP vs OOP: Pick Two" https://www.youtube.com/watch?v=HSk5fdKbd3o. Con esto en mente el paso de funciones, y la mayoría de formas de implementarlas a objetos también resulta natural gracias a ejemplos escogidos cuidadosamente como ver una función que calcula la distancia de 2 puntos inicialmente dados como 4 parámetros y luego como 2 objetos.
* Se presenta primero los ciclos y luego los condicionales, únicamente porque los ejercicios puros de condicionales son muy limitados, es mucho más versatil hacer ejercicios de ciclos cuando ya se conocen condicionales.
* Uno de los grandes temas en objetos es la inmutabilidad. Siendo algo tan importante en la industria actual y tan poco enseñado, parece obligatorio mencionarlo en un material aún para principiantes.

El índice de temas es:

1 Programación Funcional
1.1 Funciones
1.2 Operadores
1.3 Variables
1.4 String y StringBuilder
1.5 Programas en Java
1.6 Pruebas Unitarias
1.7 Ciclos
1.8 Condicionales
1.9 Arreglos y Arreglo Multidimensionales

2 Programación Orientada por Objetos
2.1 Tipos de Datos
2.2 Constructores
2.3 Referencias y NULL
2.4 Enums
2.5 Inmutabilidad

## Java

¿Por qué Java? La idea no fue caprichosa y fue pensada para ayudar el aprendizaje:

* Tener un robusto conjunto de herramientas
  - Un REPL como JShell para empezar con una curva muy suave la escritura de código
  - Una variedad de IDE que puedan ejecutarse aún en computadores con pocos recursos de RAM y procesador
  - Una herramienta simple y con mucho apoyo para pruebas unitarias
* Tener una comunidad vibrante en Internet para poder conseguir ayuda de ser necesario
* Tener una comunidad vibrante con una alta posibilidad de encontrar una comunidad local sin importar el lugar del mundo para poder conseguir ayuda de ser necesario
* Tener una alta posibilidad de conocer a alguien que ya sepa el lenguaje para poder conseguir ayuda de ser necesario

Después de la experiencia con el material, Java ha mostrado ser un lenguaje bastante oportuno para ser usado como un primer lenguaje de programación.

## ¿Cómo llevar a cabo un Bootcamp?

La manera recomendada para llevar el Bootcamp es:

1. dos sesiones a la semana, una sesión teórica el lunes y una sesión práctica el miércoles.
2. la sesión teórica no debe durar más de 2 horas.
3. la sesión práctica de ser más o menos de 1 hora y media.
4. cuatro días de estudio autónomo por parte de los participantes.
   - Sábado y Domingo: antes de la sesión anterior: el estudiante lee el material, mira el video de acompañamiento y contrasta con otros materiales (opcionalmente) al tiempo que escribe los ejemplos y toma notas. Esta actividad debe tomar.
   - Lunes: participante atiende sesión teórica y puede preguntar aclaraciones.
   - Martes: participante empieza a hacer los ejercicios y en la medida en que se encuentre con dudas, repasa el material. El estudiante debe hacer el intento de avanzar en los ejercicios.
   - Miércoles: el grupo se divide en grupos de no más de 4 personas. Cada grupo discute hasta que ejercicio pudieron avanzar y discuten en grupo el primer ejercicio que no hayan podido resolver todos. Luego siguen con el siguiente, hasta completar la hora y media.
   - Jueves: el participante es responsable de avanzar lo más que pueda en todos los ejercicios esenciales. Para hacerlo puede apoyarse en cualquier recurso siempre y cuando entregue código escrito por él.
   - Viernes: ninguna actividad recomendada.
   - Sábado y Domingo: el participante revisa el siguiente tema.
6. el uso de IA generativa es alentado, hay 2 situaciones que se deberían evitar:
   - un estudiante no puede avanzar en un ejercicio, intenta pedir ayuda a los encargados del Bootcamp o a los demás participantes pero nadie le responde a tiempo. Finalmente alguien le contesta, pero el participante ya no está pendiente de los canales de ayuda. Un tiempo después, lee la respuesta que le dieron pero en ese momento ya no está frente a un computador. Cuando se sienta, avanza un poco más pero nuevamente necesita ayuda con algo y el ciclo se repite. Esto no permite que los participantes ganen confianza. La contraparte es que los organizadores estén muy pendientes de los canales de ayuda para contestar lo antes posible lo que es injusto con su tiempo libre si el grupo de participantes es medianamente grande.
   - un estudiante pregunta algo y recibe ayuda. Nuevamente pregunta algo y recibe ayude. En algún momento antes de hacer una nueva pregunta, duda y siente que otra pregunta lo expondrá demasiado. Prefiere guardar silencio y golpearse con la pared tratando de encontrar su respuesta.
   El problema de la IA generativa es que el participante pida que la IA escriba el código, pero preguntar por un error de compilación o por un error de implementación puede ayudar con las 2 situaciones anteriores.
   Se recomienda a los participantes que si definitivamente no saben como comenzar, pueden preguntar a la IA, copiar el código verlo funcionar y eliminarlo inmediatamente para que el participante intente escribirlo. Si el participante se encuentra estancado una vez más, puede ver la respuesta nuevamente. Una vez que compruebe que funciona, volver a eliminarlo. La idea es que el participante no continúe hasta que sea capaz de escribir el código sin leer la respuesta.
7. las sesiones pueden ser virtuales, pero se recomienza al menos hacer 3 sesiones presenciales: la sesión inicial para hablar de la metodología del Bootcamp y la instalación de Java, una sesión intermedia probablemente para ayudarles a instalar un IDE y la sesión de cierre del Bootcamp. Esto ayuda a que el grupo se sienta un poco más cercano.

## Material

* [Materual Escrito](https://github.com/gaijinco/gaijinco.github.io/blob/main/Fundamentos%20de%20Programacio%CC%81n%20v2024.12.07.pdf)
* [Material en Video](https://www.youtube.com/watch?v=p3pKNBp0uZs&list=PLnoPakspmPo7ewFioN-CWY2weX7Djuhdy)
