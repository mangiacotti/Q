# Q
Servo-Controlled, Light-Tracking Solar Panel Platform
Scott Mangiacotti
Tucson, Arizona USA
May 2018


Uses:
Arduino Uno
Two 180 degree servos
Four photo resistors
Misc electrical components
Small solar panel
Mechanical assembly


Description:
This is another implementation of using two 180 degree servos and four photo-resistors to be able to track a small solar panel to align to the area of most light intensity.

The motors make small movements to try and point the solar panel to the brightest light.

There is also a multi-color LED to indicate if the system is enabled or not. And two push buttons to enable/disable the motors.

There are a few routines that can be used for moving the motors to commanded positions. The commands are via the serial port interface and a series of numeric codes/commands that can be sent to the Arduino Uno.

The independent move commands are programmed in a way to provide (somewhat) smooth motions instead of immediate position commands that cause the mechanical mechanism to move violently.
