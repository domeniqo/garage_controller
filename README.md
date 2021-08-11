# garage_controller
Project containing PCB design and software to support 2 types of external connection to ESP32 boards. This project was part of the subject PV191 during my studies at Masaryk University, Brno.

## Hardware:
The main goal is to demonstrate integration of existing PCB board with ESP32 for your own purpose. Main parts interacting with environment: 2 relays, 2 optocouplers, 2 inputs, 2 buttons, integrated thermoresistor which is able to measure temperature. The main board is powered by 12V/1A power source and can also provide power to external source via connector on the board.

## Software:
Communication with user is realized by MQTT protocol. Firmware is still under development, but now it works in LAN using Mosquito as MQTT broker in combination with any other MQTT client which can control the functions of the board via MQTT.
