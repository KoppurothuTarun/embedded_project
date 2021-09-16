# Requirements

## Introduction
The System will check whether the person is sitted on the seat or not if person is detected then it will check whether the temperature nobe is on or not and after checking both the condition if both are true then and only then it will turn on the heater and according to perticular value it will create temperature. The Seat Heating and Monitoring System is capable of maintaining the required heat for vehicle seats.In our project the button sensor checks whether the passenger is seated or not and after the passenger is seated the passenger have to set the temperature according to his/her requirement and then the seat starts heating and the corrsponding temperature is displayed on LCD. In our project the main aim is to design and develop the system which is capable of monitoring the presence of the passenger and heat monitoring and displaying the corresponding value.

## Features
- The System will sense is driver or passenger seated or not.
- Driver or Passenger has the access to modify the temperature in the vehicle.
- As per Drivers request, Heater will generate the heat accordingly.
- It is best for European Countries.
- Low cost and robust system.
- Modular Approach.

## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
- User Friendly
- Easy to alter the temperature inside the vehicles.
- Modular Approach
- Low cost and Robust system.

### Weakness
- Its only applicable for those countries which are having low temperature.
### Opportunities
- It can be implemented by having both Heater and AC.
### Threats
- Not suitable for average or high temperature places.

## 4W's and 1'H
### **WHAT** : STEPin_Seat_Temperature_Monitoring_System
### **WHERE** : Used in Automotive Industries
### **WHEN** : At low Temperature

## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | Temperature Sensor|
| HLR3   | Heat Generation|
| HLR4   | Display|
| HLR5   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1      | ATmega328     |
| HLR2_LLR1   | LM35 and ADC|
| HLR2_LLR2   | ADC with PWM-fast|
| HLR3_LLR1   | Thermoelectric module|
| HLR4_LLR1   |LCD and LED|
| HLR5_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |
