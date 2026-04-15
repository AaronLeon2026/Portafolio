# 🚗 Carro Bluetooth con HC-05

## 📌 Descripción
Este proyecto consiste en un carro controlado por Bluetooth usando Arduino y el módulo HC-05.

## 🎯 Objetivo
Controlar un carro desde el celular mediante comandos Bluetooth.

## 🔧 Componentes
- Arduino (Mega o Uno)
- Módulo HC-05
- Driver L298N
- Motores DC
- Batería
- Chasis de 3 o 4 ruedas
- Porta bateria
- Cables jumper

## ⚙️ Funcionamiento
El módulo HC-05 recibe señales desde el celular y el Arduino controla los motores según los comandos.

## 🎮 Controles

- F → Adelante
- B → Atrás
- L → Izquierda
- R → Derecha
- S → Stop

- G → Adelante izquierda
- H → Adelante derecha
- I → Atrás izquierda
- J → Atrás derecha

- Y → Bocina
  
- ## 📱 Aplicación usada

Para controlar el carro se utilizó la aplicación **BT Car Controller**, la cual permite enviar comandos por Bluetooth desde el celular.
La aplicación se conecta al módulo HC-05 mediante Bluetooth y envía los comandos al Arduino.
La clave de vinculacion es **1234** o **0000**

### 📷 Interfaz de la app
![App](app-bt-controller.jpeg)

## 📷 Evidencia
![Carro](Programacion.jpeg)
![Carro](HC-05.jpeg)
![Carro](Final.jpeg)



## 🧠 Aprendizaje
- Comunicación Bluetooth
- Control de motores
- Programación en Arduino
