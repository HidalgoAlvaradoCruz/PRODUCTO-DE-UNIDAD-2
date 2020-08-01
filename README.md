# CALCULADORA-BÁSICA-PARA-SUMAR-Y-RESTAR-DOS-NÚMEROS-DE-8-BITS

**1.PLANTEAMIENTO DEL PROBLEMA**

Se desconoce el funcionamiento, diseño y conexión de un circuito para sumar y restar dos números de 8 bits implimentando el integrado 4511 y 7483 con un mecanismo para multiplexar las salidas de forma que permita seleccionar el resultado de la operación, que se visualice en un display implementado en Thinkercad, para lo cual se formularon las siguientes preguntas: 

•	¿Cómo se diseña un circuito para sumar y restar dos números de 8 bits?

•	¿Cómo se diseña un mecanismo para multiplexar la salida de forma que permita seleccionar el resultado de la operación, suma o resta?

•	¿Cómo funcionan los integrados 7483 y 4511?

**2.OBJETIVOS**

**Objetivo general**

Diseñar una calculadora básica para sumar y restar dos números de 8 bits.

**Objetivos específicos**

•	Comprender la estructura básica de funcionamiento del software de simulación Thinkercad.

•	Entender el funcionamiento del mecanismo para multiplexar las salidas del circuito .

•	Identificar los principales parámetros de funcionamiento del integrado 4511 y 7483. 


**3.ESTADO DEL ARTE**

**4.MARCO TEÓRICO**

**ThinkerCad** 

es un programa o software gratuito y online creado para el desarrollo y modelado de objetos en 3D de una manera sencilla, ofrece también una posibilidad realmente interesante de montar, programar y simular circuitos incluso con Arduino al disponer de una interfaz de trabajo simple y atractiva. TinkerCAD ha sido creado por la empresa AutoDesk. 
Como ventajas se podría destacar que es sencillo de usar, tiene un aspecto atractivo y con unas pocas horas de uso se puede adquirir mucha destreza. Por otro lado, como desventaja se puede señalar que es necesario tener una cuenta de correo para darse de alta como usuario y que sólo posee una versión online. 
Para esto se debe crear una cuenta de usuario y acceder seleccionando la opción “Circuits” para empezar a crear circuitos 

**Multiplexores**
Son circuitos combinacionales que tienen varias entradas, una sola salida y varias líneas de selección. Su funcionamiento podría asemejarse a un conmutador de varias posiciones que simularían las entradas y el terminal común, la salida; la conmutación se realizaría por medio de la línea de selección, de tal modo que las señales presentes en las entradas aparecerán en la salida en el orden indicado por la línea de selección; es decir, un multiplexor permite el envío por una sola línea de los datos presentes en varias líneas.

Se pueden hallar multiplexores de 2 a 1 líneas, de 4 a 1, de 8 a 1,etc.

MULTIPLEXOR de 2 a 1 líneas: circuito integrado TTL 74157, contiene cuatro multiplexores con sus dos entradas de datos y su salida cada uno. Tiene una entrada de inhibición (STROBE G) activa a nivel bajo (0V) y una entrada de selección (SELECT), comunes a los cuatro multiplexores.

Cuando STROBE está a nivel bajo, si la entrada SELECT está a nivel bajo, en la salida aparece el valor del dato A; y si la SELECT está a nivel alto aparece el dato B.

Los tres componentes más importantes de un multiplexorson:
1. Líneas de entrada de datos (al menos 2): estaslíneas contienen la información digital o señalesque se puede transmitir a la línea de salida.

2. Entrada de selección de datos: esta entradaselecciona una única línea de entrada de datospara ser transmitida, dejando sin efecto las otraslíneas de entrada de datos.

3. Línea de salida: contiene la señal de la línea deentrada de datos seleccionada por la entrada deselección de datos

Las líneas de entrada de datos se determinan por 2 elevadoa a la (n) donde n es el número de entradas de selección de datos, es decir para dos entradas de selección de datosse puede tener = 4 líneas de entrada de datos.

**CI 74LS157** 
Contiene cuatro multiplexores con dos entradas de datos cada uno.La entrada de selección de datos es la misma para todoslos multiplexores que conforman este integrado, donde las 4 primeras entradas se activan a nivel bajo (0) y las 4 restantes se activan a nivel alto (1).La activación de los multiplexores en general se da mediante un terminal denominado “ENABLE” el cual debe encontrarse activo a nivel bajo (0).

