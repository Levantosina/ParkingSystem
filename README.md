# Parking system 

## Components:
### Arduino MEGA: This is the main microcontroller that controls the entire system. It processes the input from sensors and controls the output devices.

### IR Proximity Sensor: These sensors are used to detect the presence of a car in a parking space. You might have placed them at strategic locations in your parking area.

### Servo Motor: The servo motor is responsible for controlling the movement of a physical barrier or gate. It is activated when a car is detected by the IR sensors, allowing or blocking access to the parking space.

### 16x2 LCD i2c Display: This display unit provides visual feedback to users, showing relevant information such as parking availability, warnings, or system status.

### Jumpers: These are used to make electrical connections between the components.

## Working Principle:

## https://github.com/Levantosina/Images/blob/main/scheme.png

### Car Detection: IR proximity sensors continuously monitor the presence of cars in parking spaces. When a car is detected, the sensor sends a signal to the Arduino.

### Arduino Logic: The Arduino, upon receiving the signal, processes the information and decides whether the parking space is occupied or vacant. It updates the LCD display with the current status.

### Servo Motor Control: If the parking space is vacant, the Arduino activates the servo motor to open the gate or barrier, allowing the car to enter. If the space is occupied, the gate remains closed.

### VIDEO

### https://github.com/Levantosina/Images/blob/main/parking.mp4