# CALCULADORA BÁSICA PARA SUMAR Y RESTAR DOS NÚMEROS DE 8 BITS

<br>

**1.PLANTEAMIENTO DEL PROBLEMA**

Se desconoce el funcionamiento, diseño y conexión de un circuito para sumar y restar dos números de 8 bits implimentando el integrado 4511 y 7483 con un mecanismo para multiplexar las salidas de forma que permita seleccionar el resultado de la operación, que se visualice en un display implementado en Thinkercad, para lo cual se formularon las siguientes preguntas: 

•	¿Cómo se diseña un circuito para sumar y restar dos números de 8 bits?

•	¿Cómo se diseña un mecanismo para multiplexar la salida de forma que permita seleccionar el resultado de la operación, suma o resta?

•	¿Cómo funcionan los integrados 7483 y 4511?

<br>

**2.OBJETIVOS**

**Objetivo general**

Diseñar una calculadora básica para sumar y restar dos números de 8 bits.

**Objetivos específicos**

•	Comprender la estructura básica de funcionamiento del software de simulación Thinkercad.

•	Entender el funcionamiento del mecanismo para multiplexar las salidas del circuito .

•	Identificar los principales parámetros de funcionamiento del integrado 4511 y 7483. 

<br>

**3.ESTADO DEL ARTE**

<br>

En 2018, Palash Kailash Rai, Shivoy Srivastava y Ayoush Johri del Departamento de Electrónica y Comunicación
Lakshmi Narain College of Technology & Science Bhopal, India implementaron un diseño y simulación de un marco de almohadilla de circuitos lógicos y aritméticos de 8 bits utilizando el proceso C5 para CMOS submicrónicos profundos su estudio, se basa en implementar circuitos aritméticos y lógicos comprenden la lógica combinatoria que implementa operaciones lógicas como AND y OR, y operaciones aritméticas como la suma, la resta y la multiplicación. El circuito lógico aritmético de 8 bits se diseña, implementa y simula utilizando el software Electric CAD y SPICE, dicho circuito aritmético y lógico de 8 bits que puede realizar: A Y B, A OR B, A + B (suma) y A - B (resta) y todas las posibles operaciones aritméticas y lógicas (Rai, PK, Srivastava, S. y Johri, A, 2018, p.1) [1].

<br>

Syamala, Y. y Tilak del Departamento de ECE Colegio de Ingeniería Gudlavalleru Gudlavalleru, Indiaen en 2011 centraron su investigación en el diseño de una Unidad de lógica aritmética reversible, esta tecnología es de creciente importancia para muchas tecnologías informáticas futuras, el diseño de una Unidad de lógica aritmética (ALU) reversible utilizando la unidad multiplexora y las señales de control. En la ALU basada en multiplexor, las operaciones se realizan según la línea de selección. La ALU basada en la unidad de control se desarrolla con 9n puertas reversibles elementales para cuatro operaciones lógicas aritméticas básicas en dos operandos de n bits. La investigación de Syamala y Tilak basaron el diseño en una serie de operaciones realizadas en la misma línea dependiendo de las señales de control, en lugar de seleccionar el resultado deseado por un multiplexor (Syamala, Y. y Tilak, 2011, p.1) [2].

<br>

En 2018, Mahmoud Aymen Ahmed y M. A. Abdelghany investigadores del Departamento de electronica Facultad de Educación Industrial, Universidad de Sohag. Sohag, EGIPTO implemnetaron una Unidad lógica aritmética de 4 bits de baja potencia que utiliza la técnica GDI de giro completo su análisis sobre la disipación de energía y el área del circuito son los problemas principales en la industria electrónica, este documento proporciona un diseño de Unidad de lógica aritmética (ALU) de 4 bits utilizando la técnica GDI de giro completo, que consideró un método eficaz para el diseño digital de baja potencia al tiempo que reduce el área del circuito en comparación con otros estilos lógicos (Ahmed MA, Abdelghany MA, 2018, p.1) [3].

<br>

Cortés Barrón, Reyes Barranca, L. M. Flores-Nava, A. Medina Santiago del Instituto Tecnológico de Tuxtla Gutiérrez, Chiapas, México en 2012 implementaron una Unidad de lógica aritmética (ALU) de 4 bits basada en transistores Neuron MOS. Esta configuración es reconfigurable modificando solo los voltajes externos aplicados a una etapa intermedia de inversores CMOS programables, sin ningún cambio de circuito, en contraste con las implementaciones digitales convencionales basado en un método gráfico llamado Diagrama de potencial de puerta flotante (FPD), se diseñó y simuló una ALU de 4 bits muy básica para un par de funciones aritméticas y lógicas, aprovechando la suma ponderada realizada en la puerta flotante del neu-MOS (Cortes Barron, Reyes Barranca, 2018, p.1) [4].

<br>

Para el producto de unidad presente, se utilizó el entorno de simulación Tinkercad para implemnetar un circuito SUMADOR/RESTADOR 8 Bits diseñando un mecanismo para multiplexar las salidas a manera de un selector de operación (Rai, PK, Srivastava, S. y Johri, A, 2018, p.1), el ingreso de los 8 bits de datos se realiza manualmente mediante dips switch, el circuito básicamente tiene la configuración de una ALU (unidad lógica aritmética) (Syamala, Y. y Tilak, 2011, p.1). El sistema tiene la capacidad de proyectar un número decimal de salida en la pantalla del dispositivo android simulando la proyección de un display de 7 segmentos (Cortes Barron, Reyes Barranca, 2018, p.1).

<br>

<br>

**4.MARCO TEÓRICO**

<br>

**ThinkerCad** 

es un programa o software gratuito y online creado para el desarrollo y modelado de objetos en 3D de una manera sencilla, ofrece también una posibilidad realmente interesante de montar, programar y simular circuitos incluso con Arduino al disponer de una interfaz de trabajo simple y atractiva. TinkerCAD ha sido creado por la empresa AutoDesk. 
Como ventajas se podría destacar que es sencillo de usar, tiene un aspecto atractivo y con unas pocas horas de uso se puede adquirir mucha destreza. Por otro lado, como desventaja se puede señalar que es necesario tener una cuenta de correo para darse de alta como usuario y que sólo posee una versión online. 
Para esto se debe crear una cuenta de usuario y acceder seleccionando la opción “Circuits” para empezar a crear circuitos 

**Multiplexores**

Son circuitos combinacionales que tienen varias entradas, una sola salida y varias líneas de selección. Su funcionamiento podría asemejarse a un conmutador de varias posiciones que simularían las entradas y el terminal común, la salida; la conmutación se realizaría por medio de la línea de selección, de tal modo que las señales presentes en las entradas aparecerán en la salida en el orden indicado por la línea de selección; es decir, un multiplexor permite el envío por una sola línea de los datos presentes en varias líneas.

Se pueden hallar multiplexores de 2 a 1 líneas, de 4 a 1, de 8 a 1,etc.

Multiplexor de 2 a 1 líneas: circuito integrado TTL 74157, contiene cuatro multiplexores con sus dos entradas de datos y su salida cada uno. Tiene una entrada de inhibición (STROBE G) activa a nivel bajo (0V) y una entrada de selección (SELECT), comunes a los cuatro multiplexores.

Cuando STROBE está a nivel bajo, si la entrada SELECT está a nivel bajo, en la salida aparece el valor del dato A; y si la SELECT está a nivel alto aparece el dato B.

Los tres componentes más importantes de un multiplexorson:

1. Líneas de entrada de datos (al menos 2): estaslíneas contienen la información digital o señalesque se puede transmitir a la línea de salida.

2. Entrada de selección de datos: esta entradaselecciona una única línea de entrada de datospara ser transmitida, dejando sin efecto las otraslíneas de entrada de datos.

3. Línea de salida: contiene la señal de la línea deentrada de datos seleccionada por la entrada deselección de datos

Las líneas de entrada de datos se determinan por 2 elevadoa a la (n) donde n es el número de entradas de selección de datos, es decir para dos entradas de selección de datosse puede tener = 4 líneas de entrada de datos.

**CI 74LS157** 

Contiene cuatro multiplexores con dos entradas de datos cada uno.La entrada de selección de datos es la misma para todoslos multiplexores que conforman este integrado, donde las 4 primeras entradas se activan a nivel bajo (0) y las 4 restantes se activan a nivel alto (1).La activación de los multiplexores en general se da mediante un terminal denominado “ENABLE” el cual debe encontrarse activo a nivel bajo (0).

**CI 74LS83**

Es un sumador binario de 4-Bit donde las sumas (Σ) se proporcionan para cada bit y el acarreo resultante (C4) se obtiene a partir del cuarto bit. Estos agregadores cuentan con una mirada interna completa a través de los cuatro Bits  Cuenta con una implementación de ripple-carry. La lógica del sumador, incluido el carry, se implementa en su forma verdadera, lo que significa que el logrado sin necesidad de inversión lógica o de nivel.

Acarreo a lo largo de los cuatro bits

-Los sistemas logran un rendimiento de anticipación parcial con la economía de la ondulación de llevar

-Tiempos de adición típicos

-Dos palabras de 8 bits 25 ns

-Dos palabras de 16 bits 45 ns

-Disipación de potencia típica por sumador de 4 bits 95



**5. DIAGRAMAS**

<br>

**A. DIAGRAMA ELÉCTRICO**

<br>



<br>

**B. DIAGRAMA DE BLOQUES**

<br>




<br>

**6. DESARROLLO Y SIMLACIÓN**

<br>

<br>

**7. MAPA DE VARIABLES**

<br>


<br>

**8.EXPLICACIÓN DEL CÓDIGO FUENTE**

<br>

<br>

**9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN**

<br>




<br>

**10. APORTACIONES**

<br>



**11. CONCLUSIONES**

<br>
En conclusión:

<br>

• Para implementar el circuito SUMADOR /RESTADOR DE 8 bits  inicialmente se utiliza sumadores 	7483 de 4 bits en cascada para lograr una interacción de 8 bits por número, como resultado a la salida se genera un numero de 9 bits siendo el noveno bit el de acarreo, mediante este proceso se pudo concluir que en el caso de la suma el bit de acarreo representa el bit más significativo del resultado para aquellos números decimales que sobrepasen los 8 bits en su representación binaria, mientras que en la resta el bit de acarreo representa el SIGNO en el caso que el resultado sea un número negativo.

•	A partir del circuito SUMADOR se implementa el RESTADOR teóricamente se puede aplicar el complemento 1 o complemento 2 para efectuar la resta, en la práctica esto no ocurre así, a pesar que el método más fácil para hallar la resta es aplicar el complemento 1, surge la necesidad de utilizar integrados comparadores para identificar cada caso de la resta y seleccionar el resultado adecuado.


• Para implementar el sistema que permita elegir entre una opración u otra se debe multiplexar las salidas pero en vista que el simulador Tinkercad no cuenta con integrados multiplexores, este proceso se lo debe realizar diseñando un circuito que cumpla con esta función a partir de colocar puertas AND y XOR, pero el detalle más importante de dicho proceso está en que todo este sistema tiene que ir conectado a un dip switch o selector y el voltaje alto (H) o bajo (L), que llegue al dip será el que rija la operación "L" o "0" para la suma y "H" o "1" para la resta.


• Para analizar, diseñar e implementar el circuito lo más factible es dividirlo por etapas la mismas que van a describir cada parte importante del circuito como, el ingreso de los datos, la etapa del Sumador, la etapa del Restador , la del selector o Multiplexación y finalmente la etapa del decodificador BCD 4511 a 7 segmentos, en esta etapa para mostrar el resultado en un display se lo realiza según el valor máximo resultante de realizar la suma de los dos número de 8 bits en este caso el valor máximo que se puede obtener es 510 en número decimal con un acarreo, para representar esta cifra en un display de cátodo común se utilizan decodificadores 4511 conectados en cascada y para la proyección 4 display, uno para cada dígito del resultado y el cuarto display para el signo de la resta. A pesar que el circuito cuenta con diferentes etapas de análisis, el desarrollo del mismo tiene como principio fundamental la conexión de dispositivos en CASCADA.

<br>

**12. RECOMENDACIONES**

<br>

•	Se recomienda utilizar sumadores 74LS283 para circuitos de esta magnitud, esto debido a que, con el circuito integrado 74LS83 se tiene un FAN OUT de 10 (número máximo de compuertas de salida permitidas conectadas a este circuito integrado), si se excede este valor las entradas de los circuitos integrados conectados a este sumador recibirán niveles lógicos distintos a los requeridos.

•	En el proceso de construcción físico del circuito en un protoboard se recomienda que, a medida que se realiza una conexión, se vaya comprobando los niveles de activación con un diodo emisor de luz o multímetro conjuntamente con la simulación, esto facilitará la detección y solución de posibles errores de montaje.

•	Antes de conectar la alimentación del circuito, comprobar que los integrados tienen correctamente conectados los terminales de alimentación y que el circuito se encuentra correctamente montado.



<br>

**13. CRONOGRAMA**

<br>


**14. BIBLIOGRAFÍA**

<br>

[1] Rai, PK, Srivastava, S. y Johri, A. (2018). Diseño, diseño y simulación de un marco de almohadilla de circuitos lógicos y aritméticos de 8 bits utilizando el proceso C5 para CMOS submicrónicos profundos. Conferencia Internacional de Computación y Telecomunicaciones Avanzadas de 2018 (ICACAT). doi: 10.1109 / icacat.2018.8933609 


[2] Syamala, Y. y Tilak, AVN (2011). Unidad de lógica aritmética reversible. 2011 III Congreso Internacional de Tecnología Informática Electrónica. doi: 10.1109 / icectech.2011.5941987 


[3] Ahmed, MA, y Abdelghany, MA (2018). Unidad lógica aritmética de 4 bits de baja potencia que utiliza la técnica GDI de giro completo. Conferencia internacional 2018 sobre tendencias innovadoras en ingeniería informática (ITCE). doi: 10.1109 / itce.2018.8316623 


[4] Cortes-Barron, EA, Reyes-Barranca, MA, Flores-Nava, LM y Medina-Santiago, A. (2012). Unidad de lógica aritmética (ALU) de 4 bits basada en transistores Neuron MOS. 2012 Novena Conferencia Internacional sobre Ingeniería Eléctrica, Ciencias de la Computación y Control Automático (CCE). doi: 10.1109 / iceee.2012.6421136 

<br>

**15. ANEXOS**

<br>



<br>

**15.1. MANUAL DE USUARIO**

<br>



**15.2. HOJAS TÉCNICAS**

<br>

<br>










