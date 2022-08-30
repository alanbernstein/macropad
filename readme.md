# programming
https://learn.adafruit.com/adafruit-macropad-rp2040/circuitpython

https://circuitpython.org/board/adafruit_macropad_rp2040/

started with v7.3.3 on 2022/08/29

https://learn.adafruit.com/adafruit-macropad-rp2040/keypad


# keys
https://www.adafruit.com/product/5114

https://splitkb.com/products/kailh-choc-transparent-keycaps?variant=32171264213069


# lib
https://github.com/adafruit/Adafruit_CircuitPython_Display_Text

# plan

keys:
A B C
D E F
G H I
J K L

## idea 1

A: USB -> megapanda        (illuminate when active)
B: USB -> macbook          ("")
C: USB -> thinkstation     ("")

D: monitor -> megapanda    (illuminate when active)
E: monitor -> macbook      ("")
F: monitor -> thinkstation ("")

G: press yubikey           (outputs to the machine selected in ABC row)
H: 
I: beep test

J: uplift -> sit
K: uplift -> stand
L:


display
- text indicator for USB switch
- text indicator for monitor
- text indicator for desk state
- text indicator for sitting timer


## keycap ideas

for the UHK first party module:

- padlock? key?
- keymap switcher - ? (translucent)
- audio mute - microphone (translucent)
- video mute - camera (translucent)
- audio/video mute - microphone on top, camera on front (translucent)
- audio/video mute - camera on top, microphone on front (translucent)

for the custom module:

- yubikey - yubikey logo? key with y logo?
- input switcher - ? (translucent)
- video switcher - monitor (translucent)
- standing desk raise,lower
- standing desk mem1,2,3,4
- video physical cover - aperture or something
