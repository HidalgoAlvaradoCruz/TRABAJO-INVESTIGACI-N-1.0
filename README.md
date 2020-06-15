
PROGRAMA EN APPI NVENTOR PARA REALIZAR LA CONVERSIÓN DE UN NÚMERO DECIMAL A CÓDIGO BCD APLICABLE AUN DISPLAY DE SIETE SEGMENTOS

PLANTEAMIENTO DEL PROBLEMA
Se desconoce la interfaz de funcionamiento, control y conversión de un número decimal a código BCD en App Inventor para un display de siente segmentos, para lo cual se formularon las siguientes preguntas: 

•	¿Cómo se convierte un número decimal a código BCD

•	¿Cuál es el lenguaje de programación utilizado en App Inventor

•	¿Cómo funciona un display de siete segmentos?

OBJETIVOS

Objetivo general

Realizar la conversión de un número decimal a BCM en App Inventor aplicable a un display de siete segmentos.
Objetivos específicos

•	Comprender la estructura de control básica de App Inventor para la conversión de un número decimal a código BCD.

•	Identificar los principales parámetros de funcionamiento de un display de siente segmentos.

•	Implementar funciones en el diseño del código.


ESTADO DEL ARTE

MARCO TEÓRICO

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

IMG3

Diseñador (Designer)
La herramienta de diseño permite seleccionar los componentes de una aplicación y definir el entorno de usuario de la misma.


IMG4 IMG5

Editor de Bloques (Blocks)
El comportamiento de la aplicación se programa mediante bloques en el editor de bloques.

IMG6

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

IMG7


La principal ventaja del código decimal codificado en binario es que permite la conversión fácil entre el formato decimal (base-10) y binario (base-2). Sin embargo, la desventaja es que el código BCD es inútil ya que los estados entre 1010 (decimal 10) y 1111 (decimal 15) no se utilizan. Sin embargo, el decimal codificado en binario tiene muchas aplicaciones importantes, especialmente el uso de pantallas digitales.

En el sistema de numeración BCD, un número decimal se separa en cuatro bits por cada dígito decimal dentro del número. Cada dígito decimal está representado por su valor binario ponderado que realiza una traducción directa del número. Por lo tanto, un grupo de 4 bits representa cada dígito decimal visualizado desde 0000 para un cero hasta 1001 para un nueve, por ejemplo, 357 10 (trescientos cincuenta y siete) en decimal se presentarían en decimal codificado en binario como:

357 10 = 0011 0101 0111 (BCD)


Se puede ver que BCD usa codificación ponderada, porque el bit binario de cada grupo de 4 bits representa un peso dado del valor final. En otras palabras, el BCD es un código ponderado y los pesos utilizados en el código decimal codificado en binario son 8 , 4 , 2 , 1 , comúnmente llamado el código 8421, ya que forma la representación binaria de 4 bits del dígito decimal relevante.

Representación decimal codificada en binario de un número decimal

IMG8

El peso decimal de cada dígito decimal a la izquierda aumenta en un factor de 10. En el sistema numérico BCD, el peso binario de cada dígito aumenta en un factor de   2 como se muestra. Luego, el primer dígito tiene un peso de   1 (2 0), el segundo dígito tiene un peso de   2 (2 1), el tercero un peso de   4 (2 2), el cuarto un peso de   8 (2 3).
El código binario puro se basa en una regla (potencias de 2), mientras que los códigos BCD se basan en una tabla en la que salen los números decimales del 0 al 9 y las correspondientes “traducciones” en BCD. Hay varios tipos de BCD:

•	BCD puro: Binary Code Digit, decimal o decimal codificado en binario es un estándar para representar números decimales en el sistema binario, en donde cada dígito decimal es codificado con una secuencia de 4 bits.

•	BCDS XS3: La conversión se produce sumando 3 unidades al decimal que queramos transformar en binario.

•	Aiken: Código similar al código BCD natural con los "pesos" o "valores" distribuidos de manera diferente. En el código BCD natural, los pesos son: 8-4-2-1, en el código Aiken la distribución es: 2-4-2-1.

Si los anteriores códigos se basaban en una regla, éstos se basan en una tabla. El método consiste en sustituir cada dígito decimal por los cuatro bits correspondientes.

IMG9

DISPLAY DE 7 SEGMENTOS

El display de 7 segmentos es un dispositivo electrónico que se utiliza para representar visualmente números y algunos caracteres. Este display es muy popular debido a su gran efectividad y simplicidad al momento de utilizarlo.

Partes de un display de 7 segmentos

Se le conoce como 7 segmentos por que cuenta con siete diodos led principales y uno extra para representar un punto. También cuenta con una carcasa para cubrirlos y 10 terminales: 2 son de alimentación (2 de Vcd o 2 de Gnd), 1 es para visualizar un punto y  7 son para representar cada uno de los números según la combinación que se le ponga, estos están representados por una letra del abecedario desde la “A” hasta la letra “G”.

IMG10

Funcionamiento de un display

Para poder representar los números o caracteres con este dispositivo solo basta con saber la configuración de cada una de sus leds y combinarlos.

Ejemplos:

Para representar el numero 3 debemos encender las letras A, B, G, C y D, para representar el numero 6 tenemos que combinar las letras A, F, E, D, C y G.

IMG11

Tipos de display de 7 segmentos 

Al ser un dispositivo muy simple no existe mucha variedad, solo podemos encontrar de:

Ánodo común 

Se llama así porque todos los leds están unidos en su terminal positiva (ánodo), para encenderlos tenemos que poner tierra en la terminal de la letra que se desee.

IMG12

Cátodo común 

Este display es el opuesto del ánodo común ya que los leds están unidos en la terminal negativa (cátodo). Para encender los leds tenemos que poner voltaje en las terminales de las letras.

IMG13

Display múltiple

Dentro de este tipo podemos encontrar de ánodo o cátodo común, la única diferencia es que son 2, 4 y hasta 6 displays unidos. Estos son ideales para cuando se necesitan representar cifras de más de un dígito.

IMG14

Por tamaño 

En este tipo también podemos encontrar de ánodo o cátodo común, la única variación es el tamaño del display, ya que los podemos encontrar de 2.3 y 4 pulgadas.


IMG15

Aplicaciones del display 7 segmentos

Las principales aplicaciones de los displays 7 segmentos son como contadores, relojes de tiempo real, para desplegar marcadores o algún tipo de cuenta regresiva o incremental. 



