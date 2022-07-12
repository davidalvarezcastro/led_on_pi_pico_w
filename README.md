# Getting used to Raspberry Pi pico w

Simple project to turn on a led with a raspberry pi pico w.

### How to upload

You need:
 - a raspberry pi pico w with a usb to connect to your computer
 - add micropython firmware to the raspberry
 - install `rshell`


Process to upload code to the raspberry:
 - execute rshell in the same folder where the `main.py` is saved
 - list boards with `boards` command (note down the name)
 - execute `cp main.py /pyboard/main.py`
 - reset the raspberry (unplug & plug or simply press Ctrl+D in the repl teminal)



More info about the new raspberry pi pico w in the Raspberry Pi [Web Page](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html).

