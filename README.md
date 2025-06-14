# UART - Universal Asynchronous Receiver/Transmitter 
  Una UART (Universal Asynchronous Receiver/Transmitter) es un
componente electrónico que se utiliza para establecer
comunicaciones serie entre dispositivos.
En la actualidad las UARTs siguen siendo relevantes en
aplicaciones industriales debido a su simplicidad y robustez. Dada
la utilización los usb.

## UART (Universal Asynchronous Receiver/Transmitter):
- La UART es un dispositivo que permite la comunicación
asíncrona entre dos dispositivos electrónicos.
- Funciona como un intermediario entre distintos dispositivos.
- La comunicación es "asíncrona" porque no se basa en una
señal de reloj compartida entre los dispositivos.
En cambio, utiliza señales de inicio y parada para sincronizar los
datos.

- **La UART tiene dos componentes principales**:
  - el transmisor (TX).
  - el receptor (RX).
    
- **Transmisión de Datos**:
- El subsistema transmisor (TX) es responsable de enviar datos
desde el dispositivo de entrada hacia otro dispositivo.
- La transmisión se realiza en forma de "tramas" que contienen
bits de datos, un bit de paridad (depende el formato en el que se
transmita) y un bit de parada.
La construcción del subsistema transmisor de una UART implica
diseñar un circuito capaz de generar las tramas de datos
especificadas (8 bits, paridad par y un bit de parada) y transmitirlas a través de
una conexión RS-232. Este proceso es fundamental para
establecer comunicaciones serie confiables entre dispositivos electrónicos.
