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

Es un programa o software gratuito y online creado para el desarrollo y modelado de objetos en 3D de una manera sencilla, ofrece también una posibilidad realmente interesante de montar, programar y simular circuitos incluso con Arduino al disponer de una interfaz de trabajo simple y atractiva. TinkerCAD ha sido creado por la empresa AutoDesk. 
es un programa o software gratuito y online creado para el desarrollo y modelado de objetos en 3D de una manera sencilla, ofrece también una posibilidad realmente interesante de montar, programar y simular circuitos incluso con Arduino al disponer de una interfaz de trabajo simple y atractiva. TinkerCAD ha sido creado por la empresa AutoDesk. 
Como ventajas se podría destacar que es sencillo de usar, tiene un aspecto atractivo y con unas pocas horas de uso se puede adquirir mucha destreza. Por otro lado, como desventaja se puede señalar que es necesario tener una cuenta de correo para darse de alta como usuario y que sólo posee una versión online. 
Para esto se debe crear una cuenta de usuario y acceder seleccionando la opción “Circuits” para empezar a crear circuitos 

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img1.png)

**Multiplexores**

Son circuitos combinacionales que tienen varias entradas, una sola salida y varias líneas de selección. Su funcionamiento podría asemejarse a un conmutador de varias posiciones que simularían las entradas y el terminal común, la salida; la conmutación se realizaría por medio de la línea de selección, de tal modo que las señales presentes en las entradas aparecerán en la salida en el orden indicado por la línea de selección; es decir, un multiplexor permite el envío por una sola línea de los datos presentes en varias líneas.
@@ -89,20 +87,14 @@ Los tres componentes más importantes de un multiplexorson:

Las líneas de entrada de datos se determinan por 2 elevadoa a la (n) donde n es el número de entradas de selección de datos, es decir para dos entradas de selección de datosse puede tener = 4 líneas de entrada de datos.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img2.jpg)

**MULTIPLEXOR CI 74LS157** 


Contiene cuatro multiplexores con dos entradas de datos cada uno.La entrada de selección de datos es la misma para todoslos multiplexores que conforman este integrado, donde las 4 primeras entradas se activan a nivel bajo (0) y las 4 restantes se activan a nivel alto (1).La activación de los multiplexores en general se da mediante un terminal denominado “ENABLE” el cual debe encontrarse activo a nivel bajo (0).

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img3.png)

**SUMADOR CI 74LS83**


Es un sumador binario de 4-Bit donde las sumas (Σ) se proporcionan para cada bit y el acarreo resultante (C4) se obtiene a partir del cuarto bit. Estos agregadores cuentan con una mirada interna completa a través de los cuatro Bits  Cuenta con una implementación de ripple-carry. La lógica del sumador, incluido el carry, se implementa en su forma verdadera, lo que significa que el logrado sin necesidad de inversión lógica o de nivel.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img5.jpg)

Acarreo a lo largo de los cuatro bits

-Los sistemas logran un rendimiento de anticipación parcial con la economía de la ondulación de llevar
@@ -115,93 +107,10 @@ Acarreo a lo largo de los cuatro bits

-Disipación de potencia típica por sumador de 4 bits 95

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img4.jpg)

**COMPARADOR CI 74LS85**

Son circuitos integrados combinacionales con uno o más pares de entradas que tienen como función comparar dos magnitudes binarias para determinar su relación.

El comparador más básico, que determina si dos números son iguales, se consigue mediante una puerta XOR (or exclusiva), ya que su salida es 1 si los dos bits de entrada son diferentes y 0 si son iguales.

Muchos comparadores poseen además de la salida de igualdad, dos salidas más que indican cual de los números colocados a la entrada es mayor (M) que el otro, o bien es menor (m) que el otro.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img6.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img7.jpg)

**DECODIFICADOR CI 74HC4511**

Son circuitos combinacionales integrados que disponen de n entradas y un número de salidas igual o menor a 2n, actúan de modo que según cual sea la combinación de las variables de entrada se activa una única salida, permaneciendo el resto de ellas desactivada.

Suelen disponer de una entrada adicional denominada de inhibición o strobe de modo que cuando esta entrada se encuentra activada, pone todas las salidas a 0.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img8.jpg)



**COMPUERTA XOR – Compuerta O Exclusiva CI 74HC86**

En la electrónica digital hay compuertas que no son comunes. Una de ellas es la compuerta XOR ó compuerta O exclusiva ó compuerta O excluyente. El diagrama inferior muestra el símbolo de una compuerta XOR (O exclusiva) de 2 entradas.
Comprender el funcionamiento de esta compuerta digital es muy importante para después poder implementar lo que se llama un comparador digital.

La puerta lógica OR-exclusiva, más conocida por su nombre en inglés XOR, realiza la función booleana A'B+AB'. Su símbolo es el más (+) inscrito en un círculo. En la figura de la derecha pueden observarse sus símbolos en electrónica.


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img15.png)

El circuito integrado que contiene la compuerta XOR, es el 74LS86, el cual posee internamente 4 compuertas XOR, como se muestra en la figura, hay que tener en cuenta que el pin 7 debe estar conectado a Tierra (GND) y el pin 14 a Positivo (Vcc),

**4HC86** 


4 compuertas XOR  74HC86 de dos entradas. CMOS

Una puerta lógica, o compuerta lógica, es un dispositivo electrónico con una función booleana. Suman, multiplican, niegan o afirman, incluyen o excluyen según sus propiedades lógicas. Se pueden aplicar a tecnología electrónica, eléctrica, mecánica, hidráulica y neumática. Son circuitos de conmutación integrados en un chip.

Características:

4 compuertas XOR de dos entradas c/u

Tecnología: High Speed CMOS (HC)

Funcionamiento lógico y organización de pines compatible con la familia LS-TTL

Alta inmunidad al ruido

Muy bajo consumo de potencia, similar a los C.I. CMOS estándar

Alta velocidad

Voltaje de alimentación: 2V a 6V

Encapsulado: DIP 14 pines

**COMPUERTA NAND CI 74HC00**

La puerta lógica NO-Y, más conocida por su nombre en inglés NAND, realiza la operación de producto lógico negado.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img12.png)

El circuito integrado que contiene la compuerta NAND, es el 74LS00, el cual posee internamente 4 compuertas NAND, como se muestra en la figura, hay que tener en cuenta que el pin 7 debe estar conectado a Tierra (GND) y el pin 14 a Positivo (Vcc),

**COMPUERTA AND CI 74HC00**

La puerta lógica Y, más conocida por su nombre en inglés AND (AND \equiv Y \equiv \and  ), realiza la función booleana de producto lógico. Su símbolo es un punto (·), aunque se suele omitir. Así, el producto lógico de las variables A y B se indica como AB, y se lee A y B o simplemente A por B.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img13.png)


El circuito integrado que contiene la compuerta AND, es el 74LS08, el cual posee internamente 4 compuertas AND, como se muestra en la figura, hay que tener en cuenta que el pin 7 debe estar conectado a Tierra (GND) y el pin 14 a Positivo (Vcc).


**COMPUERTA OR CI 74HC32**

La puerta lógica O, más conocida por su nombre en inglés OR (OR \equiv O \equiv \or ), realiza la operación de suma lógica.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img14.png)
<br>

El circuito integrado que contiene la compuerta OR, es el 74LS32, el cual posee internamente 4 compuertas OR, como se muestra en la figura, hay que tener en cuenta que el pin 7 debe estar conectado a Tierra (GND) y el pin 14 a Positivo (Vcc),


**5. DIAGRAMAS**

<br>

**A. DIAGRAMA ELÉCTRICO**

<br>



<br>

**B. DIAGRAMA DE BLOQUES**

<br>

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/db1.jpg)

<br>

**6. MAPA DE VARIABLES**

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img16.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img17.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img18.png)

**7.EXPLICACIÓN DEL CIRCUITO**

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img31.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img32.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img33.jpeg)

**Ingreso de números en BCD**

Para el ingreso de números en BCD se tiene 2 dip switch de 8 interruptores cada uno, en la parte superior, el primer dip switch representa el número A y el segundo dip switch el número denotado por B.

Hay que tomar en cuenta que los dip switch tomandoles en cuenta de abajo hacia arriba, [abajo- bits menos significativo] y [arriba-bits más significativo]. Es necesario comprender lo anteriormente explicado para el correcto ingreso de números BCD. Al momento de realizar las conexiones de los dip switch se conectó a + Vcc (5 V) los dígitos activados en 0 y a tierra los dígitos activados en 1

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img19.png)

Para sumar o restar números en BCD por medio de un dip switch extra donde [Up-Resta] y [Low-Suma].

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img20.png)

Se conecta las  8 salidas de los dip switch de los bits menos significativos tanto del número A como del B a un sumador 7483  con el acarreo de entrada a tierra y este sumador en cascada a otro sumador 7483 conectado al acarreo de entrada las 8 salidas de los dip switch de los bits más significativos tanto del número A como del B.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img21.png)

**Complemento A1**

Para realizar la resta es necesario negar los 8 bits de salida tanto del número A como del número B y conectar a los sumadores conectados en cascada, algo a tomar en cuenta el acarreo de entrada del primer sumador va a conectado a VCC que representa implícitamente más uno.

Exiten dos casos:

A>B 

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img22.png)

B>A

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img23.png)

**Signo de la resta caso A<B **

Para el caso de la resta hay que tomar en cuenta que va a exitir un signo menos[-] en el caso A<B para esto hay que utilizar dos integrados 7485 que se encargan de comparar tanto el número A como el B .

Hay que tomar en cuenta que el primer integrado compara los bits menos significativos tanto del número A como del número B y el segundo integrado compara los bits mas significativos tando del número A como del B.

Para finalmente obtener el signo de la resta es necesario conectar los circuitos comparadores a la función [(A<B).(A=C)]+(A.1<B.1) ya que sis sus entradas estan en un nivel alto el resultado será un nivel bajo es decir el signo menos.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img24.png)

**Selección del caso de la resta:**

Ya obtenido el signo como una salida ,junto con las salidas de los dos comparadores, iran conectadas a dos multiplexores en cascada 74157 circuito que  contiene cuatro multiplexores con sus dos entradas de datos y su salida cada uno, esta es la razón por la que se usará dos de ellos ya que el circuito cuenta con 8 bits y como exiten dos entradas de datos completarian los 16 bits.
Se debe tomar en cuenta que en el primer integrado se conectan los bits menos significativos tanto del número A como del B y en el segundo integrado se conectan los bits más significativos tanto del número A como del B.

La entrada de inhibición (STROBE G o A'/B) activa a nivel bajo (0V) es decir la salida que representa el signo y la entrada de selección (SELECT), comunes a los cuatro multiplexores,  es la que va conectada en común con el segundo multiplexor.

Algo importante a tomar en cuenta es que STROBE está a nivel bajo, si la entrada SELECT está a nivel bajo por lo tanto irán a tierra.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img25.png)

**Selección de la operación suma o resta:**

Para la selección de la operación se utiliza 3 multiplexores en cascada.El primer y segundo integrado van conectados las salidas de los dos primeros sumadores (sin negar) junto con la salida del switch que indica la operación a realizarse ya sea la suma o la resta.

Es importante saber que el primer integrado va conectado a los bits menos significativos tanto del A como del B y el segundo integrado a los bits más significativos tanto del número A como del B.

La entrada de inhibición (STROBE G o A'/B) activa a nivel bajo (0V) es decir la salida que representa el signo y la entrada de selección (SELECT), comunes a los cuatro multiplexores, que es la que va conectada en común con el segundo y tercer multiplexor, ya que que STROBE está a nivel bajo, si la entrada SELECT está a nivel bajo, por lo tanto irán a tierra.

El tercer integrado indica tanto el signo de la resta o el acarreo de la suma por lo que está conectado al acarreo de la salida del segundo sumador (sin negar) y a la salida del comparador que indica el signo de la resta en el caso A<B junto con la salida del switch que indica la operación a realizarse ya sea la suma o la resta.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img26.png)

**Sincronización de los de los números a sumar o restar y la respuesta**

Las compuertas and y or  juntas funcionan como un generador de pulsos, a manera de un reloj tanto para los sumadores como para los decodificadores 4511 determinando tanto la velocidad con la que se actualizaran los datos en el display y el instante en la que se hará esa actulización.

La compuerta OR juega en el circuito un papel muy importante ya que en el proceso del conteo los pines de los bits menos significativos pueden activarse y desactivarse varias veces y lo que se necesita en este circuito es solo la última activación es decir los últimos tres bits más significativos.

Cuando la salida de la operación realizada por los multiplexores sea mayor que cero se estará ejecutando los display de manera estable pero cuando sea cero o esté en estado bajo es necesario una compuerta AND para  detener la generación de mas pulsos de lo necesario en este caso solo para 8 bits.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img28.png)

Entonces partiendo de estas características generales del circuito  se empieza con la sincronización del circuito para poder proyectar los números en los display partiendo de las 3 señales principales a utilizarse similares en su función a un diagrama de tiempo.Simplemente haciendo las comparaciones restantes con los bits restantes es decir (solo 7 bits )sin llegar al bit menos significativo que será conectado directamente al decodificador.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img29.png)

Todo esto conectando en cascada tanto compuertas AND, OR, SUMADORES y DECODDIFICADORES.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img30.png)

Es importante notar que a partir del primer sumador implimentado para esta sincronización si se necesita un nuevo dígito simplemente se aumenta más sumadores, los cuáles tendrán las mismas conexiones que el primero al igual que en los decodificadores.


**Visualización en los diplay de 7 segmentos de los números a sumar o restar y la respuesta**

Para finalizar se conecta directamente las salidas de los decodificadores 4511 a cada uno de los display cátodo común.

El display que indica el signo en la resta  y el acarreo en la suma  todas sus entradas vana conectadas a la salida del tercer multiplexor que justamente nos indica lo dicho anteriormente.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img27.png)

**8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN**

<br>

Para utilizar el entorno de simulación Tinkercad es necesario tener una cuenta de Google o una cuenta institucional en este caso la cuenta de Mi ESPE, para la realizar la verificación y creación de la cuenta en Tinkercad.

Es esencial tener una conexión estable a internet, debido a que la creación y simulación del circuito solo lo realiza en línea. 
Los sistemas operativos de los computadores en los cuales funciona Tinkercad son: 

•	Macintosh (con procesador Intel): Mac OS X 10.5, 10.6

•	Windows: Windows XP, Windows Vista, Windows 7 y versiones superiores

•	GNU / Linux: Ubuntu 8 +, 5 + Debian

<br>

Tener un computador con todas las actualizaciones necesarias, como también nuestro navegador deberá tener las siguientes especificaciones: 

•	Mozilla Firefox 3.6 o superior

•	Apple Safari 5.0 o superior

•	Google Chrome 4.0 o superior

•	Microsoft Internet Explorer 7 o superior

<br>

El circuito creado en Tinkercad puede funcionar en cualquier servidor si se le da el atributo de público y se comparte el enlace que se genera, dicho enlace será la única forma en la que se pueda acceder y editar el diseño del circuito.

<br>

**10. APORTACIONES**

Implementación de 6 display de 7 segmentos cátodo común y focos led que vizualicen los dos números ingresados A y B a sumar o a restar en el circuito. 

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img37.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img38.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img39.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img40.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img41.png)

**11. CONCLUSIONES**

En conclusión:

<br>

• Para implementar el circuito SUMADOR /RESTADOR DE 8 bits  inicialmente se utiliza sumadores 	7483 de 4 bits en cascada para lograr una interacción de 8 bits por número, como resultado a la salida se genera un numero de 9 bits siendo el noveno bit el de acarreo, mediante este proceso se pudo concluir que en el caso de la suma el bit de acarreo representa el bit más significativo del resultado para aquellos números decimales que sobrepasen los 8 bits en su representación binaria, mientras que en la resta el bit de acarreo representa el SIGNO en el caso que el resultado sea un número negativo.

•	A partir del circuito SUMADOR se implementa el RESTADOR teóricamente se puede aplicar el complemento 1 o complemento 2 para efectuar la resta, en la práctica esto no ocurre así, a pesar que el método más fácil para hallar la resta es aplicar el complemento 1, surge la necesidad de utilizar integrados comparadores para identificar cada caso de la resta y seleccionar el resultado adecuado.


• Para implementar el sistema que permita elegir entre una opración u otra se debe multiplexar las salidas pero en vista que el simulador Tinkercad no cuenta con integrados multiplexores, este proceso se lo debe realizar diseñando un circuito que cumpla con esta función a partir de colocar puertas AND y XOR, pero el detalle más importante de dicho proceso está en que todo este sistema tiene que ir conectado a un dip switch o selector y el voltaje alto (H) o bajo (L), que llegue al dip será el que rija la operación "L" o "0" para la suma y "H" o "1" para la resta.


• Para analizar, diseñar e implementar el circuito lo más factible es dividirlo por etapas la mismas que van a describir cada parte importante del circuito como, el ingreso de los datos, la etapa del Sumador, la etapa del Restador , la del selector o Multiplexación y finalmente la etapa del decodificador BCD 4511 a 7 segmentos, en esta etapa para mostrar el resultado en un display se lo realiza según el valor máximo resultante de realizar la suma de los dos número de 8 bits en este caso el valor máximo que se puede obtener es 510 en número decimal con un acarreo, para representar esta cifra en un display de cátodo común se utilizan decodificadores 4511 conectados en cascada y para la proyección 4 display, uno para cada dígito del resultado y el cuarto display para el signo de la resta. A pesar que el circuito cuenta con diferentes etapas de análisis, el desarrollo del mismo tiene como principio fundamental la conexión de dispositivos en CASCADA.

<br>

**12. RECOMENDACIONES**

<br>

• Es recomendable al momento de realizar la implementación del circuito en Tinkercad conectar a tierra las todas las salidas de los integrados que no se ocupen, en algunos integrados esto no influye pero existen ciertos casos que al no realizar esta conexión a tierra afecta a los valores lógicos recibidos a las entradas.   

•	Antes de proyectar el resultado de la resta se deben analizar los tres casos en los que puede recaer, lo mejor es para controlar y seleccionar el caso es utilizar un comparador seguido de un multiplexor para elegir la respuesta.

• Al momento de cambiar de una etapa del circuito a otra, es de gran ayuda colocar focos led para verificar si los valores lógicos que ingresan o salen del de cada etapa son los correctos, puesto que una mala conexión desencadena una serie de errores en el circuito.


<br>

**13. CRONOGRAMA**


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img37.jpeg)


**14. BIBLIOGRAFÍA**

<br>

[1] Rai, PK, Srivastava, S. y Johri, A. (2018). Diseño, diseño y simulación de un marco de almohadilla de circuitos lógicos y aritméticos de 8 bits utilizando el proceso C5 para CMOS submicrónicos profundos. Conferencia Internacional de Computación y Telecomunicaciones Avanzadas de 2018 (ICACAT). doi: 10.1109 / icacat.2018.8933609 


[2] Syamala, Y. y Tilak, AVN (2011). Unidad de lógica aritmética reversible. 2011 III Congreso Internacional de Tecnología Informática Electrónica. doi: 10.1109 / icectech.2011.5941987 


[3] Ahmed, MA, y Abdelghany, MA (2018). Unidad lógica aritmética de 4 bits de baja potencia que utiliza la técnica GDI de giro completo. Conferencia internacional 2018 sobre tendencias innovadoras en ingeniería informática (ITCE). doi: 10.1109 / itce.2018.8316623 


[4] Cortes-Barron, EA, Reyes-Barranca, MA, Flores-Nava, LM y Medina-Santiago, A. (2012). Unidad de lógica aritmética (ALU) de 4 bits basada en transistores Neuron MOS. 2012 Novena Conferencia Internacional sobre Ingeniería Eléctrica, Ciencias de la Computación y Control Automático (CCE). doi: 10.1109 / iceee.2012.6421136 

<br>

**15. ANEXOS**

**15.1. MANUAL DE USUARIO**

<br>



**15.2. HOJAS TÉCNICAS**

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img34.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img35.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD-2/blob/master/img/img36.png)






