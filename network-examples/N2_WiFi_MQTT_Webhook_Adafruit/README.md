# Using MQTT and Webhooks in Adaruit IO
This project is the code from [Adafruit IO (MQTT & Webhooks)](https://hackmd.io/@lnu-iot/r1yEtcs55) tutorial on Raspberry Pi Pico W MicroPython. It shows how to connect to the board to WiFi, then generate a random number between 0 - 100 and submit it to the Adafruit MQTT server to publish it in a Line Chart. If the submitted value is greater than 80 it triggers an alarm action and forwards the value to Discord. It also subscribes to an MQTT topic in Adafruit and by changing a toggle switch we can control the onboard led on Raspberry Pi Pico (on/off). All the keys can be set in lib/keys.py 