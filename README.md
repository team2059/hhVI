# hhVI
A collection of LabVIEW VIs for FRC

## Actuators
#### Motor Direction.vi
A boolean set motor controller for moving a motor forwards or backwards tp a selected speed.
#### Set Motor Speed.vi
Sets a motor speed in the range [-1,1].
#### Set Reley.vi
Sets a reley in three states forwards, reverse and off.

## Controls
#### Convert Joystick Throttle.vi
Converts a joystick axis range from [-1,1] to [0,1].
#### Get JoyStick Values.vi
Writes joystick values to a the dashboard.
#### Get Joystick.vi
Converts code to use both the Logitech Extreme 3D Pro Joystick and the Logitech Attack 3 Joystick.
#### Half Speed Converter.vi
Converts a robot motor speed range from [-1,1] to [-.5,.5].
#### Joystick to Dashboard.vi
Sends values from the joystick to the dashboard.
#### Toggle Switch.vi
Converts a boolean running in a loop to a toggle switch.

## Dashboard
#### Get Demo Mode.vi
Returns if the robot needs to have less power for use at demos.
#### Get Joystick Type.vi
Returns the joystick type being used on the drive station computer.
#### Get Sensitivity.vi
Returns the control sensitivity setting that is set from the dashboard.

## Drive
#### Drive Forward Auto
A basic auto that drives forward and stops.
#### Get 4 Motor Drive Refs.vi
Returns the motor references of a 4 motor drive.
#### PID Drive.vi
Drives the robot based on a set distance or rotation.
#### Set Arcade Drive.vi
Sets x and y axis of arcade robot drive.

## Miscellaneous
#### Degree to Ratation.vi
Converts a desired turn amount in degrees based on robot dimensions to wheel rotations.

## Sensors
#### CAN Alerts.vi
Checks voltage of the PDV, roboRIO and all CAN Talon motor controllers. If the voltage on any of these it too low a dashboard message "Voltage Alerts" is sent.
#### Check CAN Talon Voltage.vi
Checks voltage of a CAN Talon motor controller and returns a string error if the voltage is below 10 volts.
#### Get Encoder Wheel Values.vi
Handles a rotational encoder attached to a wheel and returns wheel direction, distance, velocity, state and angle.
#### Limit Switches.vi
Stops motor based on hitting an upper and lower limit.
