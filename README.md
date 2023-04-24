Programador para Atmega32A-AU
================================

![Programador_Atmega32A-AU_5](https://user-images.githubusercontent.com/88397949/129969175-90fae21a-e60c-4ffb-a119-ba28c528795d.png)



## Descripción:

El programador para el Atmega32A es un dispositivo que se utiliza para cargar el programa generado en un computador en la memoria flash programable del microcontrolador Atmega32A. Es similar al programador para el Atmega8, pero con algunas diferencias específicas para este microcontrolador.

El programador para el Atmega32A puede ser un hardware comercial o construido por el usuario, y se conecta al microcontrolador a través de un conector específico. Utiliza un protocolo de comunicación serial para transferir los datos del programa al microcontrolador.

El Atmega32A es un microcontrolador de 8 bits de la familia AVR fabricado por la empresa Microchip Technology. Tiene una velocidad de reloj de hasta 16 MHz, 32 KB de memoria flash programable, 2 KB de memoria EEPROM y 2 KB de memoria SRAM. Además, cuenta con una serie de periféricos integrados, como convertidores analógico-digitales, temporizadores, interfaces de comunicación serie y paralelo, entre otros.

El proceso de programación del microcontrolador Atmega32A es muy importante en el desarrollo de proyectos electrónicos que utilicen este microcontrolador, ya que permite cargar el software necesario para el funcionamiento del sistema. Una vez que el programa ha sido cargado en la memoria del microcontrolador, este puede ejecutar las instrucciones programadas y controlar los periféricos conectados a él. 

Diseño de una placa que distribuye los 44 pines del Atmega32A-AU. El microcontrolador (uC) es ubicado sobre una placa independiente de forma que, si se presentarán posibles fallas en el uC, su extracción no efectará a la placa principal.
La placa incorpora 12 pulsadores: 10 teclado principal (PB 0-7), 1 reset y 1 endorer PD4. El puerto A (PortA) destinado para un display LCD.

Un encoder rotacional (A : PD5 y B : PD6). Salidas y entradas de comunicación I2C (SCL : PC0 / SDA : PC1 ), UART (Rx : PD0 / Tx : PD1).

Una entrada USBasp para realizar la programación a través del puerto USB (Miso, Sck, Reset, Mosi, +5 V, GND).

Posee la instalación de regulares de tensión: +3.3 V (LD33), +5 V (78L05 - 7805), +9 V (7809), +12 V (7812).
## Atmel:

