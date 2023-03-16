# Paradigma
## ***Definicion***
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

## ***Definicion de Programacion Orientada a Objetos***
----------------------------------------------------------------------------------------------------------------------------
La programación orientada a objetos (POO, en español); es un paradigma de programación que parte del concepto de "objetos" como base, los cuales contienen información en forma de campos (a veces también referidos como atributos o propiedades) y código en forma de métodos.

Los objetos son capaces de interactuar y modificar los valores contenidos en sus campos o atributos (estado) a través de sus métodos (comportamiento).

Muchos de los objetos prediseñados de los lenguajes de programación actuales permiten la agrupación en bibliotecas o librerías, sin embargo, muchos de estos lenguajes permiten al usuario la creación de sus propias bibliotecas.

Algunas características clave de la programación orientada a objetos son herencia, cohesión, abstracción, polimorfismo, acoplamiento y encapsulamiento.

Su uso se popularizó a principios de la década de 1990. En la actualidad, existe una gran variedad de lenguajes de programación que soportan la orientación a objetos, estando la mayoría de éstos basados en el concepto de clases e instancias.

### *Origen*

Los conceptos de la POO tienen origen en Simula 67, un lenguaje diseñado para hacer simulaciones, creado por Ole-Johan Dahl y Kristen Nygaard, del Centro de Cómputo Noruego en Oslo. En este centro se trabajaba en simulaciones de naves, que fueron confundidas por la explosión combinatoria de cómo las diversas cualidades de diferentes naves podían afectar unas a las otras. La idea surgió al agrupar los diversos tipos de naves en diversas clases de objetos, siendo responsable cada clase de objetos de definir sus "propios" datos y comportamientos. Fueron refinados más tarde en Smalltalk, desarrollado en Simula en Xerox PARC (cuya primera versión fue escrita sobre Basic) pero diseñado para ser un sistema completamente dinámico en el cual los objetos se podrían crear y modificar "sobre la marcha" (en tiempo de ejecución) en lugar de tener un sistema basado en programas estáticos.

La POO se fue convirtiendo en el estilo de programación dominante a mediados de los años 1980, en gran parte debido a la influencia de C++, una extensión del lenguaje de programación C. Su dominación fue consolidada gracias al auge de las interfaces gráficas de usuario, para las cuales la POO está particularmente bien adaptada. En este caso, se habla también de programación dirigida por eventos.

Las características de orientación a objetos fueron agregadas a muchos lenguajes existentes durante ese tiempo, incluyendo Ada, BASIC, Lisp más Pascal, entre otros. La adición de estas características a los lenguajes que no fueron diseñados inicialmente para ellas condujo a menudo a problemas de compatibilidad y en la capacidad de mantenimiento del código. Los lenguajes orientados a objetos "puros", por su parte, carecían de las características de las cuales muchos programadores habían venido a depender. Para saltar este obstáculo, se hicieron muchas tentativas para crear nuevos lenguajes basados en métodos orientados a objetos, pero permitiendo algunas características imperativas de maneras "seguras". El lenguaje de programación Eiffel de Bertrand Meyer fue un temprano y moderadamente acertado lenguaje con esos objetivos, pero ahora ha sido esencialmente reemplazado por Java, en gran parte debido a la aparición de Internet y a la implementación de la máquina virtual Java en la mayoría de navegadores web. PHP en su versión 5 se ha modificado; soporta una orientación completa a objetos, cumpliendo todas las características propias de la orientación a objetos.

## ***Abstraccion***
----------------------------------------------------------------------------------------------------------------------------
El término abstracción consiste en solo utilizar características esenciales de un objeto, eliminando características que no son fundamentales para su representación.

Por ejemplo, si queremos hacer un programa que muestre características de una persona, para esto utilizaremos sus características propias, tales como su nombre, apellido, edad, dirección, etc.

## ***Encapsulamiento***
----------------------------------------------------------------------------------------------------------------------------
El encapsulamiento es un mecanismo que consiste en organizar datos y métodos de una estructura, conciliando el modo en que el objeto se implementa, es decir, evitando el acceso a datos por cualquier otro medio distinto a los especificados. Por lo tanto, la encapsulación garantiza la integridad de los datos que contiene un objeto.

Consiste en unir en la Clase las características y comportamientos, esto es, las variables y métodos. Es tener todo esto es una sola entidad.

La abstracción y la encapsulación no son lo mismo, pero si están relacionadas porque sin encapsulación no hay abstracción, ya que si no se encapsulan los componentes no podríamos dar una abstracción alta del objeto al cual nos estamos refiriendo.

### *Ejemplo de Encapsulamiento*

![Encapsulamiento](https://3.bp.blogspot.com/-ZnaeA0MP7wc/UFby5OpRjYI/AAAAAAAAAQQ/U5QunC_bdL4/s1600/Encapsulamiento3.jpg "Encapsulamiento") 

### *Ejemplo de Abstraccion*

![Abstraccion](https://th.bing.com/th/id/R.6560becf8c4ba7842db72f613a46365b?rik=swVeHVr8azkYeg&riu=http%3a%2f%2frootear.com%2ffiles%2f2014%2f10%2fclasesabstractasinterface.jpg&ehk=7LN9lNkFsivioAGK52jKryA3tkw1swn66wft8RB9Oc4%3d&risl=&pid=ImgRaw&r=0 "Abstraccion")

## ***Herencia***
----------------------------------------------------------------------------------------------------------------------------
La herencia en el sistema de programación orientada a objetos es una forma de organizar los objetos en una jerarquía, desde lo más general hasta lo más específico. Se trata del método utilizado para extender una clase en otra, manteniendo una ejecución similar.

En la mayoría de los lenguajes orientados a objetos basados en clases, un objeto creado a través de la herencia, llamado objeto hijo, obtiene todas las propiedades y comportamientos del objeto paterno.

![Herencia](https://www.lifeder.com/wp-content/uploads/2020/04/Herencia-en-programaci%C3%B3n-Pluke-CC0-Creative-Commons-CC0-1.0-Universal-Public-Domain.jpg "Herencia")

# UML: Diagrama de Clases
## ***Descripcion***
----------------------------------------------------------------------------------------------------------------------------
El lenguaje unificado de modelado (UML, por sus siglas en inglés, Unified Modeling Language) es el lenguaje de modelado de sistemas de software más conocido y utilizado en la actualidad, respaldado por el Object Management Group (OMG).

Es un lenguaje gráfico para visualizar, especificar, construir y documentar un sistema. UML ofrece un estándar para describir un "plano" del sistema (modelo), incluyendo aspectos conceptuales tales como procesos, funciones del sistema, y aspectos concretos como expresiones de lenguajes de programación, esquemas de bases de datos y compuestos reciclados.

Es importante remarcar que UML es un "lenguaje de modelado" para especificar o describir métodos o procesos. Se utiliza para definir un sistema, para detallar los artefactos en el sistema y para documentar y construirlo. En otras palabras, es el lenguaje en el que está descrito el modelo.

Se puede aplicar en el desarrollo de software, gran variedad de metodologías de desarrollo de software (tal como el Proceso Unificado Racional, Rational Unified Process o RUP), pero no especifica en sí mismo qué metodología o proceso usar.

UML no puede compararse con la programación estructurada, pues UML significa Lenguaje Unificado de Modelado, no es programación, solo se diagrama la realidad de una utilización en un requerimiento. Mientras que la programación estructurada es una forma de programar como lo es la programación orientada a objetos (POO), la POO ha sido un complemento perfecto de UML, pero no por eso se utiliza UML solo para lenguajes orientados a objetos.

UML cuenta con varios tipos de diagramas, los cuales muestran diferentes aspectos de las entidades representadas.

## ***Historia***
---------------------------------------------------------------------------------------------------------------------------=
### *Antecedentes*
Después de que la Rational Software Corporation contratara a James Rumbaugh de General Electric, en 1994, la compañía se convirtió en la fuente de los dos esquemas de modelado orientado a objetos más populares de la época: Object-Modeling Technique (OMT) de Rumbaugh, que era mejor para análisis orientado a objetos, y el Método Booch (de Grady Booch) que era mejor para el diseño orientado a objetos. Poco después se les unió Ivar Jacobson, el creador del método de ingeniería de software orientado a objetos. Jacobson se unió a Rational, en 1995, después de que su compañía Objectory AB fuera comprada por Rational. Los tres metodologistas eran conocidos como los Tres Amigos, porque se sabía de sus constantes discusiones sobre las prácticas metodológicas.

En 1996 Rational concluyó que la abundancia de lenguajes de modelado estaba alentando la adopción de la tecnología de objetos, y para orientarse hacia un método unificado, encargaron a los Tres Amigos que desarrollaran un "lenguaje unificado de modelado" abierto. Se consultó con representantes de compañías competidoras en el área de la tecnología de objetos durante la OOPSLA '96; eligieron "cajas" para representar clases en lugar de la notación de Booch que utilizaba símbolos de "nubes".

Bajo la dirección técnica de los Tres Amigos (Rumbaugh, Jacobson y Booch) fue organizado un consorcio internacional llamado UML Partners en 1996 para completar las especificaciones del UML, y para proponerlo como una respuesta al OMG RFP. El borrador de la especificación UML 1.0 de UML Partners fue propuesto a la OMG en enero de 1997. Durante el mismo mes, la UML Partners formó una Fuerza de Tarea Semántica, encabezada por Cris Kobryn y administrada por Ed Eykholt, para finalizar las semánticas de la especificación y para integrarla con otros esfuerzos de estandarización. El resultado de este trabajo, el UML 1.1, fue presentado ante la OMG en agosto de 1997 y adoptado por la OMG en noviembre de 1997.

### *UML 1.x*
Como notación de modelado, la influencia de la OMT domina UML (por ejemplo, el uso de rectángulos para clases y objetos). Aunque se quitó la notación de "nubes" de Booch, sí se adoptó la capacidad de Booch para especificar detalles de diseño en los niveles inferiores. La notación de "Casos de Uso" del Objectory y la notación de componentes de Booch fueron integrados al resto de la notación, pero la integración semántica era relativamente débil en UML 1.1, y no se arregló realmente hasta la revisión mayor de UML 2.0.

Conceptos de muchos otros métodos orientados a objetos (MOO) fueron integrados superficialmente en UML con el propósito de hacerlo compatible con todos los MOO. Además, el grupo tomó en cuenta muchos otros métodos de la época, con el objetivo de asegurar amplia cobertura en el dominio de los sistemas en tiempo real. Como resultado, UML es útil en una gran variedad de problemas de ingeniería, desde procesos sencillos y aplicaciones de solamente un usuario a sistemas concurrentes y distribuidos.

### *UML 2.x*
UML ha madurado considerablemente desde UML 1.1, varias revisiones menores (UML 1.3, 1.4 y 1.5) han corregido defectos y errores de la primera versión de UML. A estas le ha seguido la revisión mayor UML 2.0 que fue adoptada por el OMG en 2005.

Aunque UML 2.1 nunca fue lanzado como una especificación formal, las versiones 2.1.1 y 2.1.2, aparecieron en 2007, seguidas por UML 2.2 en febrero de 2009. UML 2.3 fue lanzado oficialmente en mayo de 2010. UML 2.4.1 fue lanzado oficialmente en agosto de 2011. UML 2.5.1 fue lanzado en octubre de 2012 como una versión "En proceso" que fue formalmente liberada en junio de 2015.

## ***Sistemas donde se utilizan***
UML se utiliza principalmente en el desarrollo de software orientado a objetos. Al ampliar el estándar en la versión 2.0, también es adecuado para visualizar procesos empresariales.

## ***Utilidad actual***
Hoy en día, UML esta consolidado como el lenguaje estándar en el análisis y diseño de sistemas de computo. Mediante UML es posible establecer la serie de requerimientos y estructuras necesarias para plasmar un sistema de software previo al proceso intensivo de escribir código.

## ***Herramientas para el modelado de UML***
Algunas herramientas para poder crear estos diagramas son GitMInd, Gliffy, MagicDraw, Lucidchart, Microsoft Visio, IBM Rational Rhapsody, etc...

Aqui presentamos una comparacion entre estas

|Herramienta|Tipo|Plataforma|Lenguaje|Trabajo en equipo|Versiones compatibles|Adecuado para...|Precio|
|-----------|----|----------|--------|-----------------|---------------------|----------------|------|
|GitMInd|Online Mind Map Tool|Navegador|??|Si|??|Principiantes, bocetos|Gratuita o premium|
|Gliffy|Software de gráficos basado en web|Navegador, plugin para Confluence o Jira|JavaScript, HTML5, VDX, gXML|Si|UML 2.5|Principiantes, bocetos|Gratuita o premium|