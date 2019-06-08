# Grbl - Laser4DIY edition #


This is a GRBL fork based on the Mr Beam grbl 0.9 firmware.
This is a modified version of the grbl v0.9. 

### Changes (compared to the Mr Beam version)

* Increased laser pwm frquency to 62.5kHz (GRBL "spindle control")
* laser power range set to 0..255
  * M3 S0 sets minimum of (1/256) pwm duty cycle
  * M3 S255 set maximum, i.e. 100% pwm duty cycle
