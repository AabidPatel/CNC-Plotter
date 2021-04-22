# CNC-2D-Plotter

CNC 2D Plotter is controlled by two stepper motors, one which controlled the movement along y-direction which moved the central limb. The second stepper controlled the movement along x-direction by moving the pen holding plate. It is controlled by GRBL controller. GRLB is the open source firmware freely available for every one, GRBL is used as firmware for CNC machine. GRBL CNC Shield is used as controller for CNC machine, GRBL shield and GRBL firmware is very best for 3 axis stepper CNC machine.

![CNC 2D Plotter cropped](https://user-images.githubusercontent.com/73630123/115726845-b7e0f400-a3a0-11eb-9b8f-9738981e9e7a.jpg)

STEPS TO PLOT:
1. Uploading MIGRBL library code to Arduino Uno.

![CNC shield plus Arduino](https://user-images.githubusercontent.com/73630123/115726389-515bd600-a3a0-11eb-88c0-c97657db9bed.jpg)

2. Connecting Servo motor to GRBL CNC shield.
 
![GRBL CNC Shield](https://user-images.githubusercontent.com/73630123/115726462-60428880-a3a0-11eb-81be-7cf44f758b49.jpg)

3. Generating G-code using Inkscape.
4. Running the code from controller.

![GRBL controller](https://user-images.githubusercontent.com/73630123/115726494-66d10000-a3a0-11eb-8147-5a36360afa41.jpg)

LINKS: 

GRBL - https://github.com/grbl/grbl

Arduino - https://www.arduino.cc/
