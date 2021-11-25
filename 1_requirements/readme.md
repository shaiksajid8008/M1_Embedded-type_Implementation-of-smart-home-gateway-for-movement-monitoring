# Requirements
## _IMPLEMENTATION OF SMART HOME IMPLEMENTATION OF SMART HOME GATEWAY FOR MOVEMENT MONITORING OF ELDER PEOPLE
## Introduction
The main aim is to recognize the fall detection of elder people. The
system is build making use of the motion detector accelerometer sensor.
Human activity recognition is one of the major concern in health care
environment as they are more prone to unexpected and unpredictable
activities. Such activities often lead to injury and death in elderly. 3-axis
accelerometer sensor is placed on the hands or chest of an elder person. In
case if the person is alone in the home and he suddenly falls down, then
immediately the accelerometer sensor gets an alert and can be informed to
near by hospitals as an emergency via alarm. The proposed work done
activity recognition for high level activities (i.e sitting, standing, walking,
climbing up and climbing down).
### Research
The problem of human activity recognition can be approached using spatiotemporal variations in successive video frames. In this paper, a new human
activity recognition technique is proposed using multi-view videos.Initially, a naive background subtraction using frame differencing between
adjacent frames of a video is performed. Then, the motion information of
each pixel is recorded in binary indicating existence/nonexistence of motion
in the frame. A pixel wise sum over all the difference images in a view gives
the frequency of motion in each pixel throughout the clip. The classification
performances are evaluated using these motion frequency features. Our
analysis shows that increasing number of views used for feature extraction
improves the performance as different views of an activity provide
complementary information. Experiments on the i3DPost and the INRIA
Xmas Motion Acquisition Sequences (IXMAS) multi-view human action
datasets provide significant classification accuracies.
## Cost And Features
## costs
The Cost for the IMPLEMENTATION OF SMART HOME
GATEWAY FOR MOVEMENT MONITORING
OF ELDER PEOPLE The running cost needs an working system with an the battery backsups.and we required some NodeMCU ESP8266 WiFi development board  MPU6050 Accelerometer and Gyroscope Sensor And it well cost more
## Features
802.11 b/g/n
Integrated low power 32-bit MCU Integrated 10-bit ADC Integrated TCP/IP protocol stack Integrated TR switch, balun, LNA, power amplifier and matching network Integrated PLL, regulators, and power management units Supports antenna diversity Wi-Fi 2.4 GHz, support WPA/WPA2 Support STA/AP/STA+AP operation modes Support Smart Link Function for bA, PWM, GPIO STBC,MIMO, 2x1 MIMO A-MPDU & _A-MSDU aggregation and 0.4s guard interval Deep sleep power < 5uA Wake up and transmit packets in < 2ms Standby power consumption of< 1.0mW (DTIM3) +20dBm output power in 802.11b mode
## Hardware Requirements
- NodeMCU ESP8266 WiFi development board
- MPU6050 Accelerometer and Gyroscope Sensor
- Jumper Wires
- Bread Board
### software requirements
- c
- Arduino IDE
## Defining our System
The system has been implemented using NodeMCU ESP8266 WiFi.The system has employed accelerometer of a human to find the fall detection status of elde people.According to the command given by microcontroller will send the message to authorized person. 3-axis accelerometer sensor is placed on the hands or chest of an elder person. In case if the person is alone in the home and he suddenly fall down,then immediately the accelerometer sensor gets an alert and can be informed to nearby hospitals as an emergency via SMS.
- To use the IFTTT,sign in to your IFTTT account if you already have one or create an account.
- Now, click on the documentation to get the key which will be used in our programming part
- After that click on create
- Next, search for webhooks and select it
- After clicking the webhooks now you want to select Receive a web request and give an event name as per your wish. In my case I have given fall detect
## SWOT Analysis
- this project is use full for elder people in emergency alert.
- The system detects the abnormal activity and sends immediately an emergency alert
- The main aim to recognize the human fall detection and their movements like walking, standing, sitting, lying down, falling, and the transitions between them.
## 4W's and 1'H
- What-This project is very use full for human fall activity for use of elder people.
- When-The system detects the abnormal activity and sends immediately an emergency alert
- Why-The tools organise this information in a way that makes it easy for you to find the entires again the data may also be searchable.
- How-it works simple and easily using Gyroscope Sensor
## Detail Requirements
_HIGH LEVEL REQUIREMENTS_
|   ID  |    Descripition   |        Status      |
| ----  |  ---------------- | ------------------ |
| HLR1  | DATA ACCESS       | user need to access |
| HLR2  | sim activation    | filter by princes abd product |

_LOW LEVEL REQUIREMENTS_

| ID  | Description | status |
| --- | ----------- | ------ |
| LLR1 | User Inputs | to check the option they choose |
| LLR2 | Basic operation | to generate message |
| LLR3 | Multifile Approach | To reduce the code structure |
