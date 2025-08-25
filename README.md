# Sistemas-Embebidos-2025-2
Repositorio que contiene los archivos  correspondientes a la materia de sistemas embebidos 2025-2

# Proyecto Robot IoT con Raspberry Pi Pico 2W / ESP32-CAM

## Introducción

Este proyecto consiste en el desarrollo de un robot controlado mediante IoT, utilizando como base una Raspberry Pi Pico 2W o una ESP32-CAM. El robot se maneja en tiempo real a través de una aplicación móvil o web, integrando sensores para monitorear la velocidad y la distancia respecto a obstáculos, así como una cámara para transmisión de video en vivo. Además, incluye un brazo robótico controlable remotamente y un sistema de acoplamiento magnético que permite conectar múltiples robots para trabajo colaborativo.

## Objetivos

### Objetivo General  
Desarrollar un robot IoT controlado en tiempo real desde una aplicación, que integre sensores, cámara, control remoto del brazo robótico y acoplamiento magnético entre robots.

### Objetivos Específicos  
- Implementar sensores para control de velocidad y detección de obstáculos.  
- Integrar cámara para transmisión en tiempo real.  
- Controlar remotamente el brazo robótico.  
- Desarrollar interfaz IoT para control en tiempo real vía aplicación.  
- Diseñar sistema magnético para acoplar múltiples robots.

## Marco Teórico

El Internet de las Cosas (IoT) conecta dispositivos físicos a redes digitales para su control remoto. Las microcontroladoras Raspberry Pi Pico 2W y ESP32-CAM destacan por su bajo costo y conectividad inalámbrica, ideales para proyectos IoT. Sensores ultrasónicos y de velocidad permiten navegación autónoma evitando obstáculos. La cámara integrada facilita supervisión visual. El acoplamiento magnético es una solución sencilla para unir varios robots y permitir tareas colaborativas.

## Metodología

1. Selección y configuración del hardware: Raspberry Pi Pico 2W o ESP32-CAM.  
2. Integración y calibración de sensores de velocidad y distancia.  
3. Configuración de la cámara para transmisión en tiempo real.  
4. Desarrollo del control remoto para el brazo robótico con MicroPython.  
5. Creación de la aplicación IoT para control vía WiFi.  
6. Instalación del sistema de acoplamiento magnético.  
7. Pruebas de funcionamiento y ajustes finales.



## Tabla de Costos

| Componente                        | Cantidad | Precio Unitario (USD) | Costo Total (USD) |
|----------------------------------|----------|----------------------|-------------------|
| Raspberry Pi Pico 2W / ESP32-CAM | 1        | 10 - 15              | 10 - 15           |
| Sensor de Distancia de Ultrasonido HC-SR04            | 1        | 5                    | 10                |
| MeArm + tornillos   | 1        | 15                   | 15                |
| Servo motor SG90        | 2        | 2                    | 8                 |
|Motores DC | 2    | 10                   | 10                |
|Baterias Recargables | 2    | 10                   | 10                |
|Electro Iman | 1    | 10                   | 10                |
|Control Remoto IR + receptor IR| 1    | 10                   | 10                |
| **Total estimado**                |          |                      | **53 - 58 USD**   |

## Software

El desarrollo del software se realiza en **MicroPython**, lenguaje ligero y eficiente para microcontroladores, que facilita la gestión de sensores, comunicación WiFi, control del brazo robótico y transmisión de video.


