# WREN12S
DitroniX WREN 12S SDK v2
The WREN 12S SDK V2  example code below is used for Board Bring Up and Test Input / Output Ports.

This Arduino IDE example (Settings. Board: ESP8266 12S Dev Module), basically exercises the RGB LED, Temperature Sensor, Voltage Sensor, Safety Circuit, Inputs and DC Motor Outputs.

You can also refer to Wiki for ESP-12S GPIO and I2C GPIO Expander (MCP23017). for control and monitor of the board functionality.   WREN 12S SDK Connections

![Display-Type-B](https://ditronix.net/wp-content/uploads/2021/07/WREN-12S-SDK-V2-Component-Overview.jpg?raw=true)

Example UART Output
~~~c++

DitroniX WREN 12S SDK 2.0 Initialized

Scanning I2C	Found Devices:  (0x18)	 (0x20)	Found 2 Device(s).
Connected to Digital Temperature Sensor MCP9808	Test PCB Temp: 28.3750°C
Test RGB LEDs White Blue Green Red
Motor 1 Cycle Check, Motor 2 Cycle Check
Waiting for Controller Input

WREN Motor Driver 1A High
PCB Temp: 28.3750°C	ADC Raw Value: 535	 DC Input Voltage: 24.28 V

WREN Motor Driver 1B High
PCB Temp: 28.6250°C	ADC Raw Value: 536	 DC Input Voltage: 24.37 V

WREN Motor Driver 2A High
PCB Temp: 28.6875°C	ADC Raw Value: 535	 DC Input Voltage: 24.28 V

WREN Motor Driver 2B High
PCB Temp: 28.7500°C	ADC Raw Value: 536	 DC Input Voltage: 24.37 V


DitroniX WREN 12S SDK 2.0 Initialized

Scanning I2C	Found Devices:  (0x18)	 (0x20)	Found 2 Device(s).
Connected to Digital Temperature Sensor MCP9808	Test PCB Temp: 30.7500°C
Test RGB LEDs White Blue Green Red
Motor 1 Cycle Check, Motor 2 Cycle Check
Waiting for Controller Input

WREN Motor Driver Safety Fault Condition - DC Input (Low or High) or Back EMF Surge Voltage: 7.14 V
> RESTARTING ESP


DitroniX WREN 12S SDK 2.0 Initialized

Scanning I2C	Found Devices:  (0x18)	 (0x20)	Found 2 Device(s).
Connected to Digital Temperature Sensor MCP9808	Test PCB Temp: 30.8125°C
Test RGB LEDs White Blue Green Red
Motor 1 Cycle Check, Motor 2 Cycle Check
Waiting for Controller Input

Main DC Power Fail or Safety Fuse Blown.  Shutting Down ESP. Reset device to Wake Up
~~~