## SYNOPSIS 

1. Objective

2. Abstract

3. Existing method

4. Proposed method

5. Components

6. Working principle

8. Advantages

9. Applications

## OBJECTIVE

• To Develop a gas leakage monitoring system for air conditioners using MQ series 

sensors .

• To Implement an alert system comprising a buzzer, vibration motor, and water 

sprinkler module for immediate response.

• To Enhance safety by providing users with timely alerts, minimizing the risks 

associated with gas leaks in air conditioning systems.

## ABSTRACT

• It highlights the inadequacies in current air conditioning safety measures, 

particularly the absence of effective gas leak detection, leading to potential 

household dangers and fatalities.

• The proposed solution introduces an Arduino Uno microcontroller interfacing 

with sensors to address risks associated with minor gas leaks during sleep.

##EXISTING METHODS

• The existing model lacks gas leak detection in air conditioning systems, posing a 

significant safety risk.

• Gas leaks go undetected, resulting in potential dangers, including fatalities within 

households. 

• The absence of an alert system in the existing method makes it particularly 

hazardous, leading to severe consequences due to the unaddressed gas


## PROPOSED METHOD

• In this proposed method, Arduino uno microcontroller is used to interface with the 

sensors and to the communication devices.

• Focusing on potential hazards caused by small gas leakage during sleep, this 

project utilizes a gas sensor to detect the gas presence in the room.

• Arduino Uno processes the sensor input, activates the alarm system with a buzzer 

and vibration upon detecting the gas leakage.

• The water sprinkler module further aids in raising awareness of the potential 

hazard.

• Integrates IoT technology for real time transmission of sensor values when the 

gas is detected.

• Ensures remote monitoring and timely response promoting safety.


## COMPONENTS 

MQ Series Sensors (MQ-7, MQ-3, MQ-135):
These sensors are gas detectors capable of sensing various gases such as carbon monoxide (MQ-7), alcohol vapor (MQ-3), and various pollutants including ammonia, benzene, and CO2 (MQ-135).

Working Principle:
These sensors work on the principle of resistance changes in response to the presence of specific gases. When the target gas is present, it interacts with the sensor material, causing a change in its resistance, which can be measured and interpreted as gas concentration.

Arduino:
The Arduino is the central processing unit that receives input from the gas sensors and controls the output devices accordingly.
Working Principle: The Arduino reads the analog output of the sensors, processes this data, and triggers appropriate actions based on predefined thresholds or conditions.

Buzzer:
The buzzer is an audible alarm that activates when gas levels exceed safe limits, alerting occupants to the potential danger.
Working Principle: When activated by the Arduino, the buzzer emits a loud sound to attract attention and warn individuals in the vicinity.

Vibration Motor:
The vibration motor provides a tactile alert by vibrating when gas levels are detected above safe thresholds.
Working Principle: Similar to the buzzer, the Arduino triggers the vibration motor to produce vibrations when gas levels surpass predefined limits.
Motor Pump Motor:

This motor is responsible for activating a motorized pump to extract contaminated air from the environment.
Working Principle: When activated by the Arduino, the motor pump motor turns on, causing the pump to  sprinkle water.

LCD (Liquid Crystal Display):
The LCD provides a visual interface to display real-time gas concentrations and system status.
Working Principle: The Arduino sends data to the LCD, which then displays information such as gas concentrations, system status, and any alerts or warnings.

Relay and DC Fan:
The relay controls the operation of the DC fan, which helps to ventilate the indoor space by circulating air.
Working Principle: When activated by the Arduino, the relay switches on the DC fan, which then begins to operate, improving air circulation and aiding in the removal of pollutants.

Thermistor:
The thermistor measures ambient temperature, providing additional environmental data for system monitoring and control.
Working Principle: The thermistor's resistance varies with changes in temperature, allowing the Arduino to measure and monitor ambient temperature conditions.

Flame Sensor:
The flame sensor detects the presence of flames, providing an additional safety measure to prevent fire hazards.
Working Principle: The flame sensor typically contains an infrared receiver that detects the presence of infrared radiation emitted by flames. When flames are detected, the sensor sends a signal to the Arduino, triggering appropriate safety protocols.
Overall, this system integrates various components to monitor indoor air quality, detect gas leaks, provide alerts and warnings, and initiate actions to mitigate risks and maintain a safe environment.

## WORKING PRINCIPLE

• This project focuses on enhancing safety by detecting gas leaks in air conditioning systems. It utilizes an 

Arduino Uno microcontroller along with a gas sensor for detection. When gas leakage is detected, an 

alert system is activated, consisting of a buzzer, vibration, and water sprinkler module.

• In addition to gas detection, the system incorporates IoT capabilities for real-time monitoring and 

remote access to sensor data. This allows users to stay informed about the air conditioner's status even 

when they are not physically present.

• Furthermore, the project includes additional sensors such as the DHT11 sensor to monitor temperature 

and a flame sensor to detect fire accidents that may occur within the air conditioner.

• Overall, this comprehensive approach ensures prompt detection of gas leaks and timely alerts, thereby 

enhancing safety measures and enabling quick responses to potential hazards.
