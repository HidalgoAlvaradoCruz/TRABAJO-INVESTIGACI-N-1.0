
PROGRAMA EN APPI NVENTOR PARA REALIZAR LA CONVERSIÓN DE UN NÚMERO DECIMAL A CÓDIGO BCD APLICABLE AUN DISPLAY DE SIETE SEGMENTOS

1.PLANTEAMIENTO DEL PROBLEMA
Se desconoce la interfaz de funcionamiento, control y conversión de un número decimal a código BCD en App Inventor para un display de siente segmentos, para lo cual se formularon las siguientes preguntas: 

•	¿Cómo se convierte un número decimal a código BCD

•	¿Cuál es el lenguaje de programación utilizado en App Inventor

•	¿Cómo funciona un display de siete segmentos?

2.OBJETIVOS

Objetivo general

Realizar la conversión de un número decimal a BCM en App Inventor aplicable a un display de siete segmentos.
Objetivos específicos

•	Comprender la estructura de control básica de App Inventor para la conversión de un número decimal a código BCD.

•	Identificar los principales parámetros de funcionamiento de un display de siente segmentos.

•	Implementar funciones en el diseño del código.


3.ESTADO DEL ARTE

En 2019, Thilanka Munasinghe, Evan W. Patton y Oshani  Seneviratne del Instituto Politécnico Rensselaer, Departamento de Tecnologías de la Información y Ciencia Cibernética en Estados Unidos, desarrollaron aplicaciones loT usando MIT App Inventor para recopilar y analizar datos de sensores de bajo costo, algoritmos de aprendizaje que han permitido la toma de decisiones basadas en sistemas a gran escala. La plataforma de desarrollo de MIT App Inventor permite crear aplicaciones utilizando varios sensores y plataformas de IoT como Raspberry Pi 2 y Android Things fáciles de programar con un enfoque en la recopilación de datos de sensores conectados en un solo ambiente (Munasinghe, 2019, p.1) [1].

Ruanqianqian Huang y Franklyn Turbak del Wellesley College, Department of Computer Science en 2019 implementaron un diseño para la conversión bidireccional entre bloques y texto para App Inventor mediante fragmentos de código visual que evitan errores semánticos sintácticos y estáticos y reducen la carga cognitiva para este fin diseñaron un sistema de modo dual para MIT App Inventor que admite representaciones textuales para bloques, espacios de trabajo, pantallas y proyectos completos que permiten la conversión bidireccional entre bloques isomórficos y representaciones de texto, permitiendo que individuos de varios niveles de experiencia en programación se relacionen con la interfaz (R. Huang,F. Turbak,2019)[2].

Lance A. Allison y Mohammad Muztaba Fuad del Departamento de Cienecias de la Computación de la Universidad Estatal de Salem en 2016, basaron su estudio en la comunicación entre aplicaciones de Android desarrolladas en App-Inventor y Android  Studio  para proporcionar diferentes funcionalidades específicas de cada plataforma al dispositivo, en Android pueden desarrollarse usando App Inventor 2 (AI) del MIT o usando IDEs como Android Studio (AS) con la ayuda del SDK de Android, la versión del App Inventor original de Google, que es un entorno de desarrollo basado en un navegador web para una forma más sencilla de desarrollar aplicaciones de Android. Con poco o ningún conocimiento de programación, uno puede desarrollar e implementar una aplicación de Android usando AI,  la mayoría de las aplicaciones desarrolladas en AI tienen que seguir una plantilla de diseño específica (Lance,2006,p.1) [3]. 

Para el trabajo de investigación presente, se utilizó el entorno de desarrollo de software MIT App Inventor dirigido a la Conversión de un "NÚMERO DECIMAL A CÓDIGO BCD" (Munasinghe,2019,p.1), el entorno de programación para el aplicativo se hizo sobre la base de MIT App Inventor (Lance,2006,p.1). El sistema tiene la capacidad de proyectar un número decimal de salida  en la pantalla del dispositivo android simulando la proyección de un display de 7 segmentos (R. Huang,F. Turbak,2019).


4.MARCO TEÓRICO

APP INVENTOR

App Inventor es un entorno de desarrollo de software creado por Google para la elaboración de aplicaciones destinadas al sistema operativo de Android. El lenguaje es gratuito y se puede acceder fácilmente de la web. Las aplicaciones creadas con App Inventor están limitadas por su simplicidad, aunque permiten cubrir un gran número de necesidades básicas en un dispositivo móvil.
Con App Inventor, se espera un incremento importante en el número de aplicaciones para Android debido a dos grandes factores: la simplicidad de uso, que facilitará la aparición de un gran número de nuevas aplicaciones; y Google Play, el centro de distribución de aplicaciones para Android donde cualquier usuario puede distribuir sus creaciones libremente.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img1.png)

Interfaz de App Inventor 
En esta nueva entrada os mostramos cómo está diseñada la interfaz de la plataforma App Inventor que nos permitirá crear nuestras propias aplicaciones para dispositivos móviles.
Los principales pasos que hemos de dar antes de arrancar con nuestra creación son:
pensar cuál es el objetivo que queremos alcanzar con nuestra aplicación.
tener claro cuál es el diseño que queremos darle a esta nueva App, para lo que podemos usar, por ejemplo, un boceto en papel del diseño deseado. Para poder acceder al servicio se necesita una cuenta de Google.
Para conseguir esto, App Inventor divide el desarrollo en tres fases:

•	Gestor de proyectos: Donde se guardan los proyectos.

•	Diseñador: Donde se diseña la interfaz de las aplicaciones.

•	Editor de bloques: Donde se programa las acciones que se realizaran con la interfaz anteriormente diseñada.

Mis Proyectos (My Projects)

La vista de los proyectos es la primera que se carga cuando se accede a App Inventor, en esta herramienta se puede realizar un seguimiento de todos nuestros proyectos


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img2.png)


Diseñador (Designer)

La herramienta de diseño permite seleccionar los componentes de la App y definir el interfaz de usuario de la misma(botones,cuadros de texto, etiquetas, etc.)


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img3.png)

Diseñador (Designer)
La herramienta de diseño permite seleccionar los componentes de una aplicación y definir el entorno de usuario de la misma.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img4.png)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img5.png)

Editor de Bloques (Blocks)
El comportamiento de la aplicación se programa mediante bloques en el editor de bloques.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img6.png)

Características y funciones

•	El editor de bloques de la plataforma App Inventor, utilizaba anteriormente la librería Open Blocks.Basado en [httpy Blockly] de JavaScript para crear un lenguaje visual. Estas librerías están distribuidas por el Massachusetts Institute of Technology bajo su licencia libre. El compilador que traduce el lenguaje visual de los bloques para la aplicación en Android, utiliza Kawa como lenguaje de programación, distribuido como parte del sistema operativo GNU de la Free Software Foundation

•	Permite crear una aplicación en menos tiempo que otros y se pueden programar aplicaciones más complejas en mucho menos tiempo que con los lenguajes más tradicionales, basados en texto.Inicialmente desarrollado por el profesor Hal Abelson y un equipo de Google Educación, mientras que Hal pasaba un año sabático en Google, App Inventor se ejecuta como un servicio web administrado por personal del Centro del MIT para el aprendizaje móvil –una colaboración de MIT de Ciencia Computacional e Inteligencia Artificial de laboratorio (CSAIL) y el Laboratorio de Medios del MIT–. El App Inventor contaba en 2015 con una comunidad mundial de casi dos millones de usuarios, que representaban a 195 países en todo el mundo. Más de 85 mil usuarios semanales activos de la herramienta han construido más de 4,7 millones de aplicaciones de Android. Una herramienta de código abierto que pretende realizar la programación y la creación de aplicaciones accesibles a una amplia gama de audiencias.

•	La interfaz gráfica: permite al usuario crear aplicaciones con muchas funcionalidades. Al alcance de unos cuantos clics, por lo tanto, se abre una gran puerta para muchas personas indiscriminadas que deseen crear aplicaciones sin necesidad de ser programador.

Ventajas 
•	Se pueden crear aplicaciones por medio de bloques de manera intuitiva y gráfica, sin necesidad de saber código de programación.

•	Se puede acceder en cualquier momento y cualquier lugar siempre que estemos conectados a internet.

•	Nos ofrece varias formas de conectivad: directa, o wi fi o por medio del emulador.

•	Nos permite descargar la aplicación mediante el .apk a nuestro pc.

Inconvenientes 

•	No genera código Java para desarrollos más profundos.

•	Solo se puede desarrollar para Android.

SISTEMA DE NUMERACIÓN DECIMAL CODIFICADO EN BINARIO O BCD

El decimal codificado en binario, o BCD, es otro proceso para convertir números decimales en sus equivalentes binarios, hay muchos códigos binarios diferentes utilizados en circuitos digitales y electrónicos, cada uno con su propio uso específico.

Naturalmente se vive en un mundo decimal (base-10) y de alguna forma se necesita convertir estos números decimales en un entorno binario (base-2) que las computadoras y los dispositivos electrónicos digitales entiendan, y el código decimal codificado en binario permite hacerlo.
Un  código binario de n bits es un grupo de "n" bits que asumen hasta 2 n combinaciones distintas de 1 y 0. La ventaja del sistema decimal codificado en binario es que cada dígito decimal está representado por un grupo de 4 dígitos binarios o bits de forma muy similar a la de Hexadecimal. Así que para los 10 dígitos decimales (0 a 9) se necesita un código binario de 4 bits.

Los números decimales codificados en binario se detienen en 9 binario 1001 2. Esto significa que, aunque se pueden representar 16 números (2 4) con cuatro dígitos binarios, en el sistema de numeración BCD las seis combinaciones de códigos binarios de: 1010 (decimal 10), 1011 (decimal 11), 1100 (decimal 12), 1101 (decimal 13), 1110 (decimal 14) y 1111 (decimal 15) se clasifican como números prohibidos y no se pueden utilizar.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img7.png)


La principal ventaja del código decimal codificado en binario es que permite la conversión fácil entre el formato decimal (base-10) y binario (base-2). Sin embargo, la desventaja es que el código BCD es inútil ya que los estados entre 1010 (decimal 10) y 1111 (decimal 15) no se utilizan. Sin embargo, el decimal codificado en binario tiene muchas aplicaciones importantes, especialmente el uso de pantallas digitales.

En el sistema de numeración BCD, un número decimal se separa en cuatro bits por cada dígito decimal dentro del número. Cada dígito decimal está representado por su valor binario ponderado que realiza una traducción directa del número. Por lo tanto, un grupo de 4 bits representa cada dígito decimal visualizado desde 0000 para un cero hasta 1001 para un nueve, por ejemplo, 357 10 (trescientos cincuenta y siete) en decimal se presentarían en decimal codificado en binario como:

357 10 = 0011 0101 0111 (BCD)


Se puede ver que BCD usa codificación ponderada, porque el bit binario de cada grupo de 4 bits representa un peso dado del valor final. En otras palabras, el BCD es un código ponderado y los pesos utilizados en el código decimal codificado en binario son 8 , 4 , 2 , 1 , comúnmente llamado el código 8421, ya que forma la representación binaria de 4 bits del dígito decimal relevante.

Representación decimal codificada en binario de un número decimal


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img8.jpg)

El peso decimal de cada dígito decimal a la izquierda aumenta en un factor de 10. En el sistema numérico BCD, el peso binario de cada dígito aumenta en un factor de   2 como se muestra. Luego, el primer dígito tiene un peso de   1 (2 0), el segundo dígito tiene un peso de   2 (2 1), el tercero un peso de   4 (2 2), el cuarto un peso de   8 (2 3).
El código binario puro se basa en una regla (potencias de 2), mientras que los códigos BCD se basan en una tabla en la que salen los números decimales del 0 al 9 y las correspondientes “traducciones” en BCD. Hay varios tipos de BCD:

•	BCD puro: Binary Code Digit, decimal o decimal codificado en binario es un estándar para representar números decimales en el sistema binario, en donde cada dígito decimal es codificado con una secuencia de 4 bits.

•	BCDS XS3: La conversión se produce sumando 3 unidades al decimal que queramos transformar en binario.

•	Aiken: Código similar al código BCD natural con los "pesos" o "valores" distribuidos de manera diferente. En el código BCD natural, los pesos son: 8-4-2-1, en el código Aiken la distribución es: 2-4-2-1.

Si los anteriores códigos se basaban en una regla, éstos se basan en una tabla. El método consiste en sustituir cada dígito decimal por los cuatro bits correspondientes.


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img9.jpg)

DISPLAY DE 7 SEGMENTOS

El display de 7 segmentos es un dispositivo electrónico que se utiliza para representar visualmente números y algunos caracteres. Este display es muy popular debido a su gran efectividad y simplicidad al momento de utilizarlo.

Partes de un display de 7 segmentos

Se le conoce como 7 segmentos por que cuenta con siete diodos led principales y uno extra para representar un punto. También cuenta con una carcasa para cubrirlos y 10 terminales: 2 son de alimentación (2 de Vcd o 2 de Gnd), 1 es para visualizar un punto y  7 son para representar cada uno de los números según la combinación que se le ponga, estos están representados por una letra del abecedario desde la “A” hasta la letra “G”.


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img10.png)

Funcionamiento de un display

Para poder representar los números o caracteres con este dispositivo solo basta con saber la configuración de cada una de sus leds y combinarlos.

Ejemplos:

Para representar el numero 3 debemos encender las letras A, B, G, C y D, para representar el numero 6 tenemos que combinar las letras A, F, E, D, C y G.


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img11.jpg)

Tipos de display de 7 segmentos 

Al ser un dispositivo muy simple no existe mucha variedad, solo podemos encontrar de:

Ánodo común 

Se llama así porque todos los leds están unidos en su terminal positiva (ánodo), para encenderlos tenemos que poner tierra en la terminal de la letra que se desee.


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img12.jpg)

Cátodo común 

Este display es el opuesto del ánodo común ya que los leds están unidos en la terminal negativa (cátodo). Para encender los leds tenemos que poner voltaje en las terminales de las letras.


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img13.jpg)

Display múltiple

Dentro de este tipo podemos encontrar de ánodo o cátodo común, la única diferencia es que son 2, 4 y hasta 6 displays unidos. Estos son ideales para cuando se necesitan representar cifras de más de un dígito.


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img14.jpg)

Por tamaño 

En este tipo también podemos encontrar de ánodo o cátodo común, la única variación es el tamaño del display, ya que los podemos encontrar de 2.3 y 4 pulgadas.



![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img15.jpg)

Aplicaciones del display 7 segmentos

Las principales aplicaciones de los displays 7 segmentos son como contadores, relojes de tiempo real, para desplegar marcadores o algún tipo de cuenta regresiva o incremental. 

5.DIAGRAMAS

Diagramas Esquemático

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img17.png)

Diagramas Eléctrico

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img18.png)

Diagrama de bloques

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img40.png)

6.LISTA DE COMPONENTES

•	Laptop 

Procesador: Intel Core i5-7200U CPU @ 2.50Ghz

Memoria instalada (Ram): 8 Gb 

Tipo de sistema: 64 bits. 

Sistema operativo: Windows 8.0 en adelante. 

•	Smartphone. 

Sistema operativo: Android 

•	App Inventor 

Link: http://ai2.appinventor.mit.edu/?locale=es_ES

•	MIT AI2 

7.MAPA DE VARIABLES

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img30.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img31.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img32.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img33.jpeg)

8.EXPLICACIÓN CÓDIGO FUENTE

En la pestaña Diseñador colocamos todas las variables que van a intervenir en la ejecución del programa al mismo tiempo que se crea la interfaz gráfica de la aplicación, una vez inicializadas todas las variables en la pestaña Diseñador pasamos a la pestaña Bloques para diseñar el código de ejecución.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img48.png)

Pestañas bloques:

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img42.jpeg)

a.cuando convertir. Clic 
ejecutar	
Este botón guarda una serie de instrucciones para realizar la conversión de decimal a binario, las mismas que se ejecutarán siempre y cuando le demos un clic.

si
entonces
sino 
Este ciclo realiza la validación de las condiciones, mientras se cumpla la condición Inicial se ejecuta el proceso de conversión de decimal a código BCD caso contrario arroja el mensaje “El valor ingresado no es válido o se encuentra fuera de rango.”

num_ingresado  Texto (menor =  9)   y  num_ingresado Texto  (mayor = 0)
Es la condición inicial que rige el ciclo, nos indica que siempre que se ingrese un dato de tipo “Texto” siendo un número entre el “0” y el “9”, el programa ingresa a un nuevo ciclo “si entonces sino” donde después de una validación final se procede a definir las variables y a configurar los mensajes que se arrojarán como resultados.

num_ingresado TEXTO =  0 
Esta es la última validación que se realiza, aquí se controla si el número ingresado es igual a “0” entonces se definen las variables y se imprimen los resultados, caso contrario pasamos al siguiente número y realizamos el mismo proceso de validación siempre partiendo de un ciclo “si entonces sino”
 
poner codigo_BCD Texto como “0 0 0 0”  
Esta variable va ha imprimir el número “0 0 0 0” que es el equivalente en CÓDIGO BCD del “0”, según el valor que guarde num_ingresado se imprime un valor distinto, este proceso se realiza para los demás valores.
poner salidas_Display Texto como “1 1 1 1 1 1 0”
Esta variable imprime como resultado las SALIDAS que entrega el DISPLAY de 7 SEGMENTOS de ÁNODO COMÚN tomando como lógica de programación al “1” como ENCENDIDO y al “0” como APAGADO

poner seg_a Texto como “a: 1”
poner seg_b Texto como “b: 1”
poner seg_c Texto como “c: 1”		En este bloque de variables 
poner seg_d Texto como “d: 1”		imprime verticalmente los  
poner seg_e Texto como “e: 1”		segmentos del display indicando  
poner seg_f Texto como “f: 1”		“1 encendido” y “0 apagado”
poner seg_g Texto como “g: 1”
poner segmentos Foto como “ seg_0.png ”    
Esta variable permite imprimir la imagen que se va ha proyectar según el código BCD

Este proceso se realiza para todos los valores del “0” al “9”
 Imágenes Código 2 al código 6 

poner  ERROR Texto como  “El valor ingresado no es válido o se encuentra fuera de rango”

Con esta variable se manda a imprimir un mensaje de advertencia en el caso que los valores ingresados por el usuario no sean los correctos.   

b.cuando nuevo_cálculo .Presionar
	ejecutar

Este proceso reinicia todas las variables, limpiando la pantalla para un nuevo cálculo.

c.cuando salir. Clic
	ejecutar cerrar la aplicación 
Este proceso termina el programa y cierra la aplicación.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img43.jpeg)  

9.DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Tener una cuenta de Google, debido a que la verificación y creación de la cuenta en app inventor será a partir de esta. 
Es esencial tener una conexión estable a internet, debido que será necesario para la creación del programa en app inventor. 
Los sistemas operativos de los computadores en los cuales funciona app inventor son: 

•	Macintosh (con procesador Intel): Mac OS X 10.5, 10.6

•	Windows: Windows XP, Windows Vista, Windows 7

•	GNU / Linux: Ubuntu 8 +, 5 + Debian


Tener un computador con todas las actualizaciones necesarias, como también nuestro navegador deberá tener las siguientes especificaciones: 

•	Mozilla Firefox 3.6 o superior

•	Apple Safari 5.0 o superior

•	Google Chrome 4.0 o superior

•	Microsoft Internet Explorer 7 o superior


La aplicación creada con App Inventor puede funcionar en cualquier teléfono Android. El entorno de desarrollo y software de instalación se apoya directamente a los teléfonos siguientes: Los dispositivos adicionales requieren los controladores de Windows proporcionados por el fabricante del hardware.

Para realizar los test de nuestro programa en el móvil, será necesario descargarnos una app desde play store para Android. El nombre de la app es “MIT AI2 Companion”

10.APORTACIONES

Como parte de la aportación se realizó la proyección física a un display de 7 segmentos, a partir del código BCD. 
Este circuito se realizó a partir del decodificador “SN74LS47N”, también se usaron otros materiales como resistencias, Dip Shitch, cables conectores, un protoboard y un Display 7 segmentos con ánodo común. Y como fuente de alimentación: una fuente de 5[V]


![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img19.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img20.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img21.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img22.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img23.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img24.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img28.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img26.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img27.png)

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img25.png)

11.CONCLUSIONES

En conclusión:

•	Crear una aplicación para convertir un número decimal a BCD en App Inventor 	se torna relativamente sencillo ya que tiene una interfaz muy intuitiva sobre todo en el diseño de la app donde simplemente se escoge bloques a modo de programación y se empaqueta la aplicación en un archivo APK para instalar en cualquier smartphone.

•	El display de siete segmentos funciona a partir de activar o desactivar cada led (“0” o “1”) para formar el número requerido. A partir de esta lógica, mediante el código BCD, el cual nos entrega una combinación diferente para las 10 opciones de números que se pueden generar en el display. Es importante mencionar que en la parte física existen diferentes tipos de display como el de ánodo común y cátodo común.

•	La lógica utilizada en la aplicación para convertir un número decimal a BCD es muy semejante a la aplicada en Java o C++, programas conocidos por la mayoría de estudiantes de ingeniería lo cual facilitó en gran medida la ejecución de la app.


12.RECOMENDACIONES

•	Se recomienda realizar la idea del programa en un diagrama de flujo, antes de empezar a programarlo en app inventor. 

•	No sé de debe asignar más de un proceso a un mismo botón, debido a que solo puede cumplir una función a la vez, si se incumple esto el botón quedara obsoleto. 

•	Antes de realizar los bloques de programación, primero se deberá colocar en la interfaz gráfica los botones, campos de texto e imágenes que sea necesarias para la ejecución de la aplicación. Ya que al momento de invocar las variables no se generen errores en el bucle establecido. 

•	Definir las variables de acuerdo a la función que van a desempeñar dentro del programa, para tener una mejor percepción del mismo.  

•	Al momento de realizar nuestro circuito de aportación, se recomienda colocar resistencias de protección tanto al Display de 7 segmentos como al integrado “SN74LS47”. Como también es importante mantener un orden en los cables de conexión.

13.CRONOGRAMA

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img29.jpeg)

14.BIBLIOGRAFÍA

[1] Munasinghe, T., Patton, EW y Seneviratne, O. (2019). Desarrollo de aplicaciones IoT usando MIT App Inventor para recopilar y analizar datos de sensores. Conferencia internacional IEEE 2019 sobre Big  Data (Big Data). doi: 10.1109 / bigdata47090.2019.9006203 
[2] Huang, R. y Turbak, F. (2019). Un diseño para la conversión bidireccional entre bloques y texto para App Inventor. 2019 IEEE Blocks and Beyond Workshop (B&B). doi: 10.1109 / bb48857.2019.8941197 

[3] Lance A. Allison, Mohammad Muztaba Fuad. (2016). Comunicación entre aplicaciones entre aplicaciones de Android desarrolladas en App-Inventor y Android Studio. Conferencia 2016 IEEE / ACM International Conference on Mobile Software  Engineering and Systems (MOBILESoft). doi: 10.1109 / MobileSoft.2016.018

[4] Gonzales,Erick,(2018). Display 7 Segmentos ánodo y cátodo común.Recuperado de:
https://hetpro-store.com/TUTORIALES/display-7-segmentos-anodo-catodo-comun/

[5]Posada.Fernando,(2019). Creando aplicaciones para móviles Android con MIT App Inventor 2. DOI (web) 104438/2695-4176_OTE_2019_847-19-121-5. https://intef.es/wp-content/uploads/2019/03/MIT-App-Inventor-2.pdf

15.ANEXOS

15.1MANUAL DE USUARIO

15.2HOJAS TÉCNICAS

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img38.png)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img39.png)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img44.png)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img45.png)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img46.png)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-INVESTIGACION-1.0/blob/master/img/img47.png)
