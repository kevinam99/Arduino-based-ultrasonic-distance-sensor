# Arduino-based-ultrasonic-distance-sensor
This repo will have the programs used in the project.

Requirements:
1. One Arduino Uno board.
2. One USB cable to connect the Arduino to the computer.
3. One ultrasonic ranging module.
4. Some jumper cables.

Steps to follow:
1. Load the program in the folder "sketch_jun19a-arduino code" to the Arduino board. DO NOT CONNECT ANY OF THE MODULES!!
2. Connect the 'Vcc' pin on the ranging module to 5V on the Arduino.
3. Connect the 'trig' pin to port 8 on the Arduino.
4. Connect the 'echo' pin to port 7 on the Arduino.
5. Connect the 'gnd' pin on the ultrasonic ranging module to the ground port in the Arduino. Any of the two can be used.
6. Load the program in the file "sketch_180619a-processing" on the computer. This requires the usage of another program called Processing.    Download Processing from https://processing.org/download/. 
7. After loading the program, click on the 'play' button on the top right corner to run the Processing program. You will get the output.

This project is an application of SONAR. The ultrasonic ranging module will emit and receive ultrasonic waves. The distance will be the time take to receive the waves back by the receiver. The formula is 
            
                                distance=speed/time
Ultrasonic waves travel at the speed of light. So plug in the speed of light and the time taken to receive the waves into the equation and you'll get the distance.
