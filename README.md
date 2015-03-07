# hhVI
A collection of LabVIEW VIs for FRC

## CAN Alarts.vi
Checks voltage of the PDV, roboRIO and all CAN Talon motor controllers. If the voltage on any of these it too low a dashboard message "Voltage Alerts" is sent.
## Check CAN Talon Voltage.vi
Checks voltage of a CAN Talon motor controller and returns a string error if the voltage is below 10 volts.
## Convert Joystick Throttle.vi
Converts a joystick axis range from [-1,1] to [0,1].
## Get 4 Motor Drive Refs.vi
Returns the motor references of a 4 motor drive.
## Get JoyStick Values.vi
Writes joystick values to a the dashboard.
## Get Joystick type.vi
Converts code to use both the Logitech Extreme 3D Pro Joystick and the Logitech Attack 3 Joystick
## Half Speed Converter.vi
Converts a robot motor speed range from [-1,1] to [-.5,.5].
## Motor Direction.vi
A boolean set motor controller for moving a motor forwards or backwards.
## Toggle Switch.vi
Converts a boolean running in a loop to a toggle switch.