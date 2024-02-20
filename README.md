Here is the pin configuration and components:

L298N motor drive 
  ENA -> ~11
  IN1 -> 13
  IN2 -> 12

  ENB -> ~5
  IN3 -> 7
  IN4 -> 6

HC-06 (You can also use HC-05)
  RX -> TX
  TX -> RX
  VCC/+5V -> 5V
  GND -> GND

HC-SR04 Ultrasonic Sensor
  Trig -> 3
  Echo -> 2
  VCC -> 5V
  GND -> GND

HG90  Servo Motor
  Red -> +5V
  Brown -> GND
  Orange -> 4

Servo library disables some pins temporary. 
So, If you making this robot using different pin configuration sometimes some commponents might not work. 
To get over it and add more components and functionalities to this robot you can use a Arduino mega board.
Keep that in mind.

I used a 3 cell(11.1v) lipo battery you can go below it such as 2 18650 batteries or 2 cell(7.4v) lipo battery.
You have to give direct power to the Arduino board through the power port and to the motor drive. 
You can use a Bread board in order to expand GND pins.You can do the same to 5V and 3v power outputs.

You should use a two wheel chassi, because we can control only two motors using L298N motor drive.

If you have any doubt, leave a comment in the youtube.
YouTube link - https://youtu.be/Bd7SAde_IHc
