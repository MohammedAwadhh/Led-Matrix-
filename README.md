# Led-Matrix-
LED matrix A large, low-resolution dot-matrix display known as an LED matrix or LED display is suitable for both professional and consumer information displays as well as for hobbyist human-machine interfaces.
### Basic ingredients
| component | Description |
| ----------- | ----------- |
| Led | Light-emitting diode (LED) is a widely used standard source of light in electrical equipment. It has a wide range of applications ranging from your mobile phone to large advertising billboards. |
| Arduino | Arduino has a universal serial bus (USB) plug to connect to your computer, and a number of connection sockets that can be wired to external electronics such as motors, relays, light sensors,laser diodes,loudspeakers,microphones, and  more.
They can be powered through either the USB connection from the computer or from a 9V battery or from a power supply. |

### How to use

These displays have a lot of potential. You must link a matrix's rows and columns to your microcontroller in order to control it. A column must be LOW for any of the LEDs in that column to turn on since the columns are connected to the LEDs' cathodes. Since the rows are wired to the anodes of the LEDs, the row must be HIGH in order for a particular LED to turn on. No electricity goes through the LED and it remains off if the row and the column are both high or low.



You may control a single LED by setting its row to HIGH and its column to LOW. Set the row HIGH, take the column HIGH, then set the columns LOW or HIGH as necessary to control several LEDs in a row; a LOW column will turn the corresponding LED ON, while a HIGH column will turn it off.

set to OUTPUT using the PinMode command are set to LOW to LOW if not otherwise stated.
