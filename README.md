# Java Bootcamp Starter Kit

El Java Bootcamp Starter Kit es un material escrito que busca ser el punto de partida para que una persona interesada haga un Bootcamp con el objetivo de enseñar a programar usando Java. El material está escrito con una licencia UPL 1.0 https://oss.oracle.com/licenses/upl/

El material busca solucionar algunos inconvenientes con la gran mayoría de material didáctico que existe, sea digital o impreso, sea pago o gratuito:

* Incluye un extenso número de ejercicios. La cantidad de ejercicios busca que el estudiante tenga que usar el concepto aprendido en muchos contexto para realmente solidificarlo. Los ejercicios tienen niveles de dificultad, ejercicios sin tasas de café considerados esenciales, y ejercicios con una tasa y con dos tasas.
* Además de ejercicios, el material presenta una manera de saber si la implementación del ejercicio es correcta, presentando varios inputs y su output esperado, inspirado por competencias de programación. Después el material usa assertions de JUnit para este efecto.
* Incluye varios ejemplos de código. Complementario a los ejercicios, el material tiene un ejemplo de código por cada concepto para que cada tema sea más que solo sintaxis.
* Foco en los conceptos y no en sintaxis. Para aprender a programar no se necesita conocer toda la sintaxis, lo más importante es que los conceptos sean claros. Sin un buen ejemplo, el material no incluye toda la sintaxis de Java.
* Está escrito de una manera informal, como si fuera una conversación entre amigos, en parte inspirado por la serie Head First.
* Incluye consejos prácticos de una persona con experiencia trabajando en la industria de software desde 2008 porque nunca es demasiado temprano para enseñar sobre buenas prácticas.

## Herramientas

La herramienta inicial para escribir código es JShell. Esto permite que las personas puedan escribir funciones sin pensar en main(), en los modificadores public y static, y facilita la idea de cómo tomar input del usuario y el output de este y obtener un autocompletado de métodos que son parte del API de Java.

Antes de empezar con el tema de ciclos, se hace el salto a un IDE para que los estudiantes puedan usar un debugger y entender mejor lo que hacen los programas. Para ese entonces el concepto de funciones está muy claro y agregar la idea de clases, main(), public y static resulta natural.

## Temas

El orden de los temas fue escogido cuidadosamente para cumplir con ciertos objetivos:

* Para reforzar desde el inicio la importancia de las funciones, es el primer tema que se enseña. Igualmente, enseñar funciones tiene muchos beneficios adicionales
  - Todos los ejemplos de código se pueden hacer en el contexto de una función lo que hace que sea claro cómo usarlos en la "vida real"
  - Todos los ejercicios se pueden explicar muy sencillamente como implementaciones que logren que un input seleccionado genere el output esperado.
  - Como se mencionó anteriormente, el salto de JShell a clases, main(), public y static resulta menos traumático.
* Se empieza con funciones y termina con objetos. La discusión sobre si es más importante la programación orientada por objetos que la programación funcional debería ser cosa del pasado, p. ej. esta charla de Brian Goetz, Java Language Architect de Oracle "FP vs OOP: Pick Two" https://www.youtube.com/watch?v=HSk5fdKbd3o. Con esto en mente el paso de funciones, y la mayoría de formas de implementarlas a objetos también resulta natural gracias a ejemplos escogidos cuidadosamente como ver una función que calcula la distancia de 2 puntos inicialmente dados como 4 parámetros y luego como 2 objetos.
* Se presenta primero los ciclos y luego los condicionales, únicamente porque los ejercicios puros de condicionales son muy limitados, es mucho más versátil hacer ejercicios de ciclos cuando ya se conocen condicionales.
* Uno de los grandes temas en objetos es la inmutabilidad. Siendo algo tan importante en la industria actual y tan poco enseñado, parece obligatorio mencionarlo en un material aún para principiantes.

El índice de temas es:

Programación Funcional
1. Funciones
2. Operadores
3. Variables
4. String y StringBuilder
5. Programas en Java
6. Pruebas Unitarias
7. Ciclos
8. Condicionales
9. Arreglos y Arreglos Multidimensionales

Programación Orientada por Objetos
1. Tipos de Datos
2. Constructores
3. Referencias y NULL
4. Enums
5. Inmutabilidad

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

1. Los estudiantes tienen acceso al material completo por escrito y en video desde antes de iniciar.
2. Dos sesiones a la semana, una sesión teórica al inicio de la semana y una sesión práctica a la mitad.
   - La sesión teórica debe durar entre 1 y 2 horas y consiste en explicar en vivo los temas principales del siguiente capítulo del material.
   - La sesión práctica debería durar más o menos 1 hora y consiste en que grupos de no más de 4 personas se apoyen para resolver algunos de los ejercicios propuestos.
3. Además de las sesiones del Bootcamp el participante se compromete a 4 días de estudio autónomo
   - Antes de la sesión práctica el estudiante ya ha leído y/o visto el material correspondiente.
   - Entre la sesión práctica y la teórica repasa e intenta hacer algunos ejercicios.
   - Después de la sesión práctica termina todos los ejercicios esenciales.
4. Solo los estudiantes que hayan entregado todos los ejercicios esenciales pueden asistir a las siguientes sesiones.

Las sesiones pueden ser virtuales pero se recomienda tratar de hacer al menos tres presenciales en el curso del Bootcamp: la sesión inicial, una sesión intermedia posiblemente para ayudar con la instalación de un IDE y la sesión de cierre.

## Preguntas Frecuentes

1. ¿No es un Bootcamp muy intesivo?
   - El Bootcamp ha demostrado ser eficiente teniendo un balance entre el tiempo que deben dedicar el equipo organizador y su tiempo voluntario, y un tiempo prudente para que los participantes sean exitosos.
2. ¿Vale la pena estudiar programación hoy en día?
   - La programación es una herramienta útil aún si no se trabaja en la industria. Igualmente, la evidencia actual sugiere que la industria aún necesita programdores de todos los niveles.
3. ¿Cómo evitar que los estudiantes entreguen ejercicios hechos por IA?
   - La labor del equipo organizador no debe ser evitar que los participantes hagan trampa, lo que deben hacer es acompañar el aprendizaje de los participantes que quieren aprender.
4. ¿Se debe impedir el uso de IA?
   - El Bootcamp debería ser un reflejo de la industria. Hay que enseñar y aconsejar en su uso correcto.

## Referencias
- JShell: Es una herramienta que corre en la terminal del computador y funciona como un REPL un entorno interactivo que permite a los usuarios escribir código, ejecutarlo y ver los resultados de forma inmediata. Viene con todas las versiones posteriores a la 10.
- JUnit: Es un framework para ejecutar [pruebas unitarias](https://es.wikipedia.org/wiki/Prueba_unitaria) en Java. Si bien hay otras herramientas para pruebas unitarias, JUnit es el estándar de facto en la industria con excelente soporte en el ecosistema.
- IDE: Ambiente Integrado de Desarrolo, IDE por sus siglas en inglés. Es un programa que permite tener todas las herramientas necesarias para el desarrollo de un programa como escritura, manejo de dependencias, ejecución, validación, despliege, etc. Hay varias opciones pero la opción que consume menos recursos es [Eclipse](https://eclipseide.org/)

## Contribuciones
Las contribuciones son bienvenidas y muy apreciadas. Puedes hacerlo de dos maneras:
1. Crear un _pull request_
2. Crear un _issue_ y usar el _tag_ de _enhancement_

## Material

* [Material Escrito](https://github.com/gaijinco/gaijinco.github.io/blob/main/Fundamentos%20de%20Programacio%CC%81n%20v2024.12.07.pdf)
* [Material en Video](https://www.youtube.com/watch?v=p3pKNBp0uZs&list=PLnoPakspmPo7ewFioN-CWY2weX7Djuhdy)
