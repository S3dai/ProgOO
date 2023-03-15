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