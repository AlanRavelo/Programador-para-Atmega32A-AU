En ejecución: 90%

Programador para Atmega32A-AU
================================

![Programador_Atmega32A-AU](https://user-images.githubusercontent.com/88397949/128286223-6b919616-76cc-4cbf-b822-399edab42264.png)

## Descripción:
Diseño de una placa que distribuye los 44 pines del Atmega32A-AU. El microcontrolador (uC) es ubicado sobre una placa independiente de forma que, si se presentarán posibles fallas en el uC, su extracción no efectará a la placa principal.
La placa incorpora 12 pulsadores: 10 teclado principal (PB 0-7), 1 reset y 1 endorer PD4. El puerto A (PortA) destinado para un display LCD.

Un encoder rotacional (A : PD5 y B : PD6). Salidas y entradas de comunicación I2C (SCL : PC0 / SDA : PC1 ), UART (Rx : PD0 / Tx : PD1).

Una entrada USBasp para realizar la programación a través del puerto USB (Miso, Sck, Reset, Mosi, +5 V, GND).

Posee la instalación de regulares de tensión: +3.3 V (LD33), +5 V (78L05 - 7805), +9 V (7809), +12 V (7812).
## Atmel:

