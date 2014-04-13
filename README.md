JoystickMouseControl-on-Arduino-Leonardo
========================================

 
 Controla el mouse desde un joystick Shield en una Arduino Leonardo.
 Use el pulsador C para activar o desactivar el control del mause, el
 pulsador A para Click Izquierdo y el pulsador B para click derecho.
 (Controls the mause from a Joystick Shield on an Arduino Leonardo.
 Uses pushbutton C to turn on and off mouse control, the  
 pushbutton A to click the left mouse button and pushbutton B to
 click right)

 
 Hardware:
 * JoyStick shield iteadstudio http://imall.iteadstudio.com/im120417014.html
 
 The mouse movement is always relative. This sketch reads 
 two analog inputs that range from 0 to 1023 (or less on either end)
 and translates them into ranges of -6 to 6. 
 The sketch assumes that the joystick resting values are around the 
 middle of the range, but that they vary within a threshold.
 
 WARNING:  When you use the Mouse.move() command, the Arduino takes
 over your mouse!  Make sure you have control before you use the command.
 This sketch includes a pushbutton to toggle the mouse control state, so
 you can turn on and off mouse control.
 
 created 15 Sept 2011
 updated 28 Mar 2012
 by Tom Igoe
 
 Modificado por(modification by)
 por Jose Augusto Pujato
 8 Abr 2014
 
 this code is in the public domain
 
 
