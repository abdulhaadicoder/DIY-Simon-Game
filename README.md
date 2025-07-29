# DIY Simon Game (Cardboard + Casein Plastic)

![Finished Project](images/final_box.jpg)

## What is This?
A handmade Simon memory game using an Arduino, cardboard box, and homemade plastic buttons. No soldering required!

## Arduino Connections

| Component      | Arduino Pin | Notes                |
|----------------|-------------|----------------------|
| Red LED        | D2          |                      |
| Green LED      | D3          |                      |
| Blue LED       | D4          |                      |
| Yellow LED     | D5          |                      |
| Red Button     | D7          | Player 2 Menu        |
| Green Button   | D9          | Confirm/Menu         |
| Blue Button    | D10         | Player 1 Menu        |
| Yellow Button  | D8          | (Unused/Menu)        |
| Buzzer         | D11         | Sounds               |
| OLED SCL       | A5          | I2C Display          |
| OLED SDA       | A4          | I2C Display          |

## How to Build
1. Make buttons from milk plastic (casein) using vinegar.
2. Cut holes in the cardboard box for buttons and display.
3. Connect buttons, LEDs, and other components as shown above.
4. Secure wires with tape or glue if no soldering.

## Code
Upload the `simon_game.ino` Arduino file.

## Images
![Top View](images/top_view.jpg)
![Inside Wiring](images/inside.jpg)

## (Optional) Demo Video
If you have one, upload or link it.

## License
(MIT License or Creative Commons recommended for sharing)
