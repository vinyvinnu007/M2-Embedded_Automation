**REQUIREMENTS**

**Introduction** :

- **Principle**

The main objective of this system is to handle the temperature inside the vehicle(car).When the user gets into the car the button sensor gets activated and then the user gets access to turn on the heater. The temperature inside the car is controlled by the temperature sensor by giving out  the analog value to micro controller Atmega328.    

- **Simulation**
**
` `The operation of the heat control system is coded in embedded c and the working is demonstrated using a simulation software called \*\*\*Simul IDE\*\*\*.

This system is usually done in 3 tasks:

- When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
- Then the analog input from the temperature sensor is received and digitized using ADC.
- The digitized temperature input is visualized using Pulse Width Modulation.

- **High Level Requirements**

|`               `ID|`          `Description|
| - | - |
|HLR\_01|Atmega microcontroller|
|HLR\_02|Changing the temperature|
|HLR\_03|Heater|


- **Low Level Requirements**

|`                    `ID|`              `Description|
| - | - |
|LLR\_01	|Display the temperature|


