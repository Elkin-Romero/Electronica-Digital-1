# Protocolo de comuncicaciòn UART
## ¿Què es el UART?
El protocolo UART (Transmisor Receptor Asíncrono Universal) se encarga de la transmisión y recepción de datos a través de sus puertos Tx y Rx. Funciona bajo el principio de comunicación serie, es decir, transmite los datos bit a bit a través de una sola línea. Para lograr comunicación bidireccional, se emplean dos líneas: una para transmitir y otra para recibir.

## Interfaz fìsica 
Cada dispositivo UART tiene dos lìneas:
- Tx (Transmisor: Envìa datos 
- Rx (Receptor): Recibe datos
La conexiòn se realiza punto a punto, el Tx de un dispositivo se conecta al Rx del otro (lìneas cruzadas), y viceversa, ademàs de una tierra comùn (GND). El UART transmisor recibe los datos en forma paralela desde un bus de datos interno, los convierte a forma serial para enviarlos bit por bit por la lìnea Tx, y el UART receptor hace le proceso inverso, convierte la serial recibida de vuelta a paralelo.
