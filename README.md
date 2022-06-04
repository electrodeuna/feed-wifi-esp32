# Alimentador de mascotas con Esp32

Proyecto IoT para alimentar mascotas con el celular a través de la aplicación Telegram, usando el microcontrolador Nodemcu Esp32 que se conecta por WiFi y controla un servomotor.

Video: https://www.youtube.com/watch?v=szKZNcq5x4Y&t=36s

## Componentes

- Nodemcu Esp32
- Servomotor (SG90)
- Cables
- Recipiente

## Librerías

Las librerías utilizadas para este proyecto son "ArduinoJson" y "UniversalTelegramBot", se instalan desde el gestor de librería del Arduino IDE. También se pueden descargar directamente e instalarlas en Arduino IDE desde Programa -> Incluir Librería -> Añadir biblioteca .ZIP

UniversalTelegramBot: https://github.com/witnessmenow/Universal-Arduino-Telegram-Bot

## Errores

> ATENCIÓN: la librería Servo pretende ejecutarse sobre arquitectura(s) avr, megaavr, sam, samd, nrf52, stm32f4, mbed, mbed_nano, mbed_portenta, mbed_rp2040 y puede ser > incompatible con tu actual tarjeta la cual corre sobre arquitectura(s) esp32.
> #error "This library only supports boards with an AVR, SAM, SAMD, NRF52 or STM32F4 processor."
 
1. Haga clic aquí para descargar ESP32_Arduino_Servo_Library . Debe tener una carpeta .zip en su carpeta de Descargas
2. Descomprima la carpeta .zip y debería obtener la carpeta   ESP32 -Arduino-Servo-Library-Master
3. Renombra tu carpeta de ServoESP32-Master a ESP32_Arduino_Servo_Library
4. Mueva la carpeta ESP32_Arduino_Servo_Library a la carpeta de bibliotecas de instalación de Arduino IDE
5. Finalmente, vuelva a abrir su Arduino IDE

https://github.com/RoboticsBrno/ServoESP32/archive/refs/heads/master.zip
