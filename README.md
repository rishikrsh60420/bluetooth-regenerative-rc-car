# bluetooth-regenerative-rc-car
It is a Bluetooth controlled RC car which calculates the energy generated when motor acts as a generator when acceleration  stops 

The main concept of the project is regenerative braking. During acceleration, the motors run normally and the graph remains at zero. When the acceleration is stopped, the rotating motor continues spinning due to inertia and acts like a small generator. The generated voltage is passed through diodes and stored in a capacitor. This recovered energy is monitored in real time using the Arduino Serial Plotter.

The system also includes LED indicators:

Green LED blinks while the vehicle is moving
Red LED blinks during braking/regeneration
Components Used
Arduino Uno
L298N Motor Driver
HC-05 Bluetooth Module
DC Motors with Wheels
Capacitor
1N4007 Diodes
LEDs
7.4V Battery
Breadboard and Jumper Wires
