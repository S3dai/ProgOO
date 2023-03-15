# Paradigma
## Definicion:
----------------------------------------------------------------------------------------------------------------------------
Se denominan paradigmas de programación a las formas de clasificar los lenguajes de programación en función de sus características. Los idiomas se pueden clasificar en múltiples paradigmas.

Algunos paradigmas se ocupan principalmente de las implicancias para el modelo de ejecución del lenguaje, como permitir efectos secundarios o si la secuencia de operaciones está definida por el modelo de ejecución. Otros paradigmas se refieren principalmente a la forma en que se organiza el código, como agrupar un código en unidades junto con el estado que modifica el código. Sin embargo, otros se preocupan principalmente por el estilo de la sintaxis y la gramática.

Los paradigmas de programación comunes incluyen:

+ Imperativo en el que el programador instruye a la máquina cómo cambiar su estado,
    + Procedimental que agrupa las instrucciones en procedimientos,
    + Orientado a objetos que agrupa las instrucciones con la parte del estado en el que operan,
+ Declarativo en el que el programador simplemente declara las propiedades del resultado deseado, pero no cómo calcularlo
    + Funcional en el que el resultado deseado se declara como el valor de una serie de aplicaciones de función,
    + Lógico en la que el resultado deseado se declara como la respuesta a una pregunta sobre un sistema de hechos y reglas,
    + Matemático en el que el resultado deseado se declara como la solución de un problema de optimización
    + Reactivo en el que se declara el resultado deseado con flujos de datos y la propagación del cambio

Las técnicas simbólicas como la reflexión, que permiten que el programa se refiera a sí mismo, también pueden ser consideradas como un paradigma de programación. Sin embargo, esto es compatible con los principales paradigmas y, por lo tanto, no es un paradigma real por derecho propio.

Por ejemplo, los lenguajes que caen en el paradigma imperativo tienen dos características principales: establecen el orden en el que ocurren las operaciones, con construcciones que controlan explícitamente ese orden, y permiten efectos secundarios, en los que el estado puede modificarse en un momento determinado, dentro de una unidad de código, y luego leer en un momento diferente dentro de una unidad de código diferente. La comunicación entre las unidades de código no es explícita. Mientras tanto, en la programación orientada a objetos, el código se organiza en objetos que contienen un estado que solo es modificado por el código que forma parte del objeto. La mayoría de los lenguajes orientados a objetos también son lenguajes imperativos. Por el contrario, los lenguajes que se ajustan al paradigma declarativo no indican el orden en el que ejecutar las operaciones. En su lugar, proporcionan una serie de operaciones disponibles en el sistema, junto con las condiciones en las que se permite que se ejecute cada una. La implementación del modelo de ejecución del lenguaje rastrea qué operaciones son libres de ejecutar y elige el orden en forma independiente. Más en Comparación de lenguajes de programación de múltiples paradigmas.

## Definicion de Programacion Orientada a Objetos
----------------------------------------------------------------------------------------------------------------------------
La programación orientada a objetos (POO, en español); es un paradigma de programación que parte del concepto de "objetos" como base, los cuales contienen información en forma de campos (a veces también referidos como atributos o propiedades) y código en forma de métodos.

Los objetos son capaces de interactuar y modificar los valores contenidos en sus campos o atributos (estado) a través de sus métodos (comportamiento).1​

Muchos de los objetos prediseñados de los lenguajes de programación actuales permiten la agrupación en bibliotecas o librerías, sin embargo, muchos de estos lenguajes permiten al usuario la creación de sus propias bibliotecas.

Algunas características clave de la programación orientada a objetos son herencia, cohesión, abstracción, polimorfismo, acoplamiento y encapsulamiento.

Su uso se popularizó a principios de la década de 1990. En la actualidad, existe una gran variedad de lenguajes de programación que soportan la orientación a objetos, estando la mayoría de éstos basados en el concepto de clases e instancias.

### Origen

Los conceptos de la POO tienen origen en Simula 67, un lenguaje diseñado para hacer simulaciones, creado por Ole-Johan Dahl y Kristen Nygaard, del Centro de Cómputo Noruego en Oslo. En este centro se trabajaba en simulaciones de naves, que fueron confundidas por la explosión combinatoria de cómo las diversas cualidades de diferentes naves podían afectar unas a las otras. La idea surgió al agrupar los diversos tipos de naves en diversas clases de objetos, siendo responsable cada clase de objetos de definir sus "propios" datos y comportamientos. Fueron refinados más tarde en Smalltalk, desarrollado en Simula en Xerox PARC (cuya primera versión fue escrita sobre Basic) pero diseñado para ser un sistema completamente dinámico en el cual los objetos se podrían crear y modificar "sobre la marcha" (en tiempo de ejecución) en lugar de tener un sistema basado en programas estáticos.

La POO se fue convirtiendo en el estilo de programación dominante a mediados de los años 1980, en gran parte debido a la influencia de C++, una extensión del lenguaje de programación C. Su dominación fue consolidada gracias al auge de las interfaces gráficas de usuario, para las cuales la POO está particularmente bien adaptada. En este caso, se habla también de programación dirigida por eventos.

Las características de orientación a objetos fueron agregadas a muchos lenguajes existentes durante ese tiempo, incluyendo Ada, BASIC, Lisp más Pascal, entre otros. La adición de estas características a los lenguajes que no fueron diseñados inicialmente para ellas condujo a menudo a problemas de compatibilidad y en la capacidad de mantenimiento del código. Los lenguajes orientados a objetos "puros", por su parte, carecían de las características de las cuales muchos programadores habían venido a depender. Para saltar este obstáculo, se hicieron muchas tentativas para crear nuevos lenguajes basados en métodos orientados a objetos, pero permitiendo algunas características imperativas de maneras "seguras". El lenguaje de programación Eiffel de Bertrand Meyer fue un temprano y moderadamente acertado lenguaje con esos objetivos, pero ahora ha sido esencialmente reemplazado por Java, en gran parte debido a la aparición de Internet y a la implementación de la máquina virtual Java en la mayoría de navegadores web. PHP en su versión 5 se ha modificado; soporta una orientación completa a objetos, cumpliendo todas las características propias de la orientación a objetos.