# UD 1. Hardware de un sistema informático

## 1. Sistema Informático

La informática es la ciencia que se encarga de estudiar todo lo relacionado con los sistemas informáticos, incluyendo desde los temas relativos a su arquitectura y su fabricación, hasta los temas referidos a la organización y almacenamiento de la información, sin olvidar los relativos a la creación y uso del software, o a la formación del personal informático. Para ello se basa en múltiples ciencias como las matemáticas, la física, la electrónica, etc.

> **Para saber más:**
>
> Para empezar conviene visitar la siguiente dirección en la que hace un repaso a la evolución histórica de la creación de los ordenadores y otras cosas: [Evolución Histórica de los Ordenadores](https://es.wikiversity.org/wiki/Algoritmia_y_programaci%C3%B3n_b%C3%A1sica/Aspectos_introductorios).

> **Definición:**
>
> Se define **sistema informático** como un conjunto de elementos físicos \(hardware\) y de elementos lógicos \(software\) interconectados entre sí, destinados a gestionar el tratamiento automático y racional de la información, entendiendo por esto, su organización, su transmisión, su procesamiento y/o su almacenamiento.

Se incluye como parte fundamental del sistema informático al conjunto de personas que lo utiliza, ya sean usuarios, administradores, programadores, etc. El elemento humano es un componente imprescindible, ya que los sistemas informáticos son creados, desarrollados y utilizados por humanos para su propio provecho.

![Gr&#xE1;fico que representa la estructura de uns sistema inform&#xE1;tico gen&#xE9;rico](.gitbook/assets/si01_cont_r01_dibujosistemainformatico.jpg)

En un Sistema Informático se debe distinguir entre hardware y software:

* **Hardware** es todo lo que forma parte del ordenador, que puede ser tocado físicamente. Es decir; teclado, ratón, monitor, placa base, procesador, memoria, disco duro, cables, etc. Es la "maquinaria" necesaria utilizada para el tratamiento automático de la información.
* **Software** es el elemento lógico, es todo aquello que es "intangible". Es el conjunto de programas y datos que permiten manejar el hardware, controlando y coordinando su funcionamiento para que realice las tareas deseadas.
* El software lo integran tanto los programas como los datos:
  * **Los programas** están formados por un conjunto de órdenes o instrucciones que se utilizan para procesar los datos que se le introducen como información. Son necesarios para la gestión y el control de los equipos y de los trabajos de los usuarios.
  * **Los datos** son en sí la información que los programas deben procesar, utilizando para ello los diferentes elementos hardware que componen el sistema informático. Son, en definitiva, el objeto o razón de ser del sistema informático.

Los sistemas informáticos han evolucionado, desde que en principio todos sus componentes: físicos, lógicos y humanos estaban localizados en un mismo lugar, a estar formados por subsistemas interconectados a través de redes, que pueden llegar a estar a miles de kilómetros entre sí, integrando sistemas complejos de procesamiento de la información. Y estos subsistemas pueden estar compuestos tanto por un superordenador, como por un solo ordenador personal, o por redes locales de ordenadores, o por una combinación de todos ellos.

El sistema informático más simple estará formado por un sólo ordenador y por un usuario que ejecuta los programas instalados en él.

> **Definición:**
>
> Se define ordenador como una **máquina electrónica**, con algunas partes mecánicas, compuesta por, al menos, una unidad de proceso, y por equipos periféricos, controlada por programas que deben estar almacenados en su memoria central, destinada al tratamiento automático de la información que le es suministrada. Es una máquina de **propósito general** ya que puede realizar gran variedad de trabajos a gran velocidad y con gran precisión.

Existen muchos tipos de ordenadores, así que pueden ser clasificados en función de diversos criterios.

## 2. Arquitectura Hardware: Componentes funcionales

La arquitectura funcional vigente hoy día en la construcción de ordenadores fue concretada por John Von Neumann a mediados del siglo pasado. Está basada en los siguientes componentes que se interrelacionan entre sí a través del bus del sistema que actúa como canal de comunicación entre ellos:

* La Unidad Central de Proceso \(CPU, por sus iniciales en inglés\).
* La memoria principal.
* Los sistemas de Entrada/Salida.

![](.gitbook/assets/si01_cont_r02_01_dibujoarquitecturavonneumann.jpg)

> **Para saber más:**
>
>  Puedes ampliar información sobre esta arquitectura y su autor en el siguiente enlace de la Wikipedia. [Arquitectura Von-Neumann.](http://es.wikipedia.org/wiki/Arquitectura_de_von_Neumann)

### 2.1 Unidad Central de Proceso o CPU

La Unidad Central de Proceso es el componente que debe tener un ordenador para considerarse como tal. Viene a ser como un cerebro que debe controlar, dirigir y coordinar todas las operaciones que necesite realizar el ordenador. Todo ello lo hace siguiendo las instrucciones que recibe de los programas que esté ejecutando.

Para que la CPU pueda ejecutar un **programa** es necesario que esté alojado en su memoria central, desde donde va extrayendo en secuencia cada una de sus instrucciones, analizándolas y emitiendo las órdenes necesarias al resto de componentes que deban intervenir para completar su ejecución.

La Unidad Central de Proceso esta integrada en el Procesador Central o microprocesador y acompañada por una pequeña cantidad de **registros** de Memoria necesarios para su funcionamiento.

Por tanto en la Unidad Central de Proceso como parte integrante del Microprocesador, deben existir dos unidades:

* **La Unidad de Control**, que se encarga de ejecutar los programas, controlando su secuencia, interpretando y ejecutando sus instrucciones. Se encarga también de controlar al resto de componentes; como los periféricos, la memoria, la información que hay que procesar, etc., a tenor de lo que van necesitando las instrucciones.
*  **La Unidad Aritmético-Lógica** que hace los cálculos matemáticos y los cálculos lógicos necesarios para su funcionamiento.

La memoria central, conocida como RAM \(Random Access Memory\), es la encargada de almacenar los datos y las instrucciones de los programas que deben ejecutarse, así como toda aquella información que el sistema necesite para su funcionamiento. Está constituida por un grupo de registros capaces de retener información en su interior mientras el ordenador se encuentre encendido. Cuando el ordenador se apaga, se pierde su contenido.

Los sistemas de Entrada/Salida son circuitos electrónicos que permiten el intercambio de información entre la CPU y los periféricos. Las unidades de entrada se utilizan para cargar programas y datos en la memoria principal desde los periféricos de entrada, y las unidades de salida se utilizan para sacar los resultados de los procesos realizados a través de los periféricos de salida.

Los Buses del Sistema son el conjunto de circuitos eléctricos que conectan la CPU con el resto de unidades para comunicarse entre sí. Cada bus es un conjunto de cables o pistas de un circuito integrado, que permiten la transmisión en paralelo de la información entre los diferentes componentes del ordenador.

Hay tres clases distintas de buses:

* **El bus de instrucciones y datos**. Utilizado para trasladar tanto instrucciones como datos desde la memoria RAM al resto de componentes del ordenador y viceversa.
* **El bus de control**. La CPU transmite por él las órdenes \(microórdenes\) al resto de unidades. Y recibe de ellas señales indicando su estado.
* **El bus de direcciones.** Por él se transmiten las direcciones de destino de los datos que se envían por el bus de datos.

Veamos el siguiente ejemplo para entender su interacción: cuando la CPU tiene que obtener la información contenida en una posición de memoria, debe indicar su dirección mediante el bus de direcciones, pero también debe mandar una señal de lectura por el bus de control. Para recibir, a continuación, dicha información por el bus de datos.

