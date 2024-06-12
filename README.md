# Radar-System

Detect any object that comes in the range of this radar with ultrasonic sensor and Arduino.
This project involves creating a radar using an ultrasonic sensor and Arduino, with the radar display in the Processing IDE.

<h3>Components and supplies<h3/>

1. SG90 Micro-servo motor
2. Ultrasonic Sensor - HC-SR04 (Generic)
3. Arduino UNO

<h3>Apps and platforms<h3/>

1. Processing
2. Arduino IDE

<h3>How It Works:<h3/>
  
<h3>Ultrasonic Sensor and Servo Motor Setup:<h3/>

1. The ultrasonic sensor is mounted on a servo motor.
2. The sensor scans the area within its range (up to 200cm).
3. If no object is detected within a specified range (e.g., 40cm), green lines are displayed on the radar.
4. If an object is detected within this range, red lines are displayed.
   
<h3>Building the Project:<h3/>
  
<h3>Hardware Connections:<h3/>

<h3>Ultrasonic Sensor to Arduino:<h3/>
  
1. VCC to 5V
2. GND to GND
3. TRIG to Pin 2
4. ECHO to Pin 3
  
<h3>Servo Motor to Arduino:<h3/>
  
1. RED wire to 5V
2. BROWN wire to GND
3. ORANGE wire to Pin 4

<h3>Mount the ultrasonic sensor on the servo motor using a glue gun for temporary attachment.<h3/>
  
<h3>Coding:<h3/>

1. Create a function to measure the distance from the sensor.
2. In a loop, rotate the servo motor from left to right.

<h3>Processing IDE:<h3/>

1. Open the radar code.
2. Specify the PORT name and run the program.
3. Observe the radar pattern change when an object is brought near the sensor.

(Note: A video demonstration is available, but photos of the process were not taken.)
