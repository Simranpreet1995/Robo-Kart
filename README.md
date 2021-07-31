# Robo-Kart
This repository contains the embedded C code to build and implement a robotic trolley system using an ESP-32 Cam microcontroller. 
This readme will guide you on how to implement a smartphone/laptop controlled robotic trolley system. The tutorial assume basic knowledge of working with microcontroller circuits listed below.

Components Used:
1. ESP32-Cam module 
2. L298 Motor Driver
3. 2 High power motors
4. 12V 6000Mah battery
5. Any smartphone

Circuit Implementation:

1. Connect the ESP32-Cam microcontroller to a PC and upload the code files available in this repository. Details on how to upload code on ESP32-CAM are available here - https://randomnerdtutorials.com/program-upload-code-esp32-cam/
2. Connect the L298 motor driver module to this camera module on the following pins 
3. Connect the two heavy duty motors to the L298 module using the two motor connectors on the L298 chip

Controlling the trolley:
1. Connect to the Wifi Network "RoboKart" on your mobile device
2. Open the browser and access the IP address "192.168.4.1"
3. A webpage with a live camera stream and controls should be displayed
4. Use the arrow keys to control the trolley system

Video steps are as follows:
https://user-images.githubusercontent.com/24194354/127740261-193d65b3-9837-46d9-af1b-4c595efd0cf2.mov
https://user-images.githubusercontent.com/24194354/127739871-e004b98e-fc5c-4c4a-9837-fb0a6092308e.MOV

Demo of a real world robotic Trolley System created by me:
https://user-images.githubusercontent.com/24194354/127740268-f6eae9bd-fe3e-4a48-a2a9-fcae3eb0d0a0.mov




