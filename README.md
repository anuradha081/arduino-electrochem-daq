Arduino based  Data Aquisition using ElectrochemicalSensor/Potentiometer. This repository presents an Arduino-based data acquisition system tailored for electrochemical sensors, enabling real-time monitoring and recording of sensor outputs. The system supports applications in analytical chemistry, envronmental sensing, and low-cost instrumentation.

This repository presents a low-cost, Arduino-based data acquisition (DAQ) system specifically designed for interfacing with electrochemical sensors. The setup enables real-time data collection, processing, and logging for applications in analytical chemistry, environmental monitoring, and bio-sensing.

 Overview

Electrochemical sensors are widely used in chemical and biological analysis. However, the high cost of traditional DAQ systems limits their accessibility. This project offers an affordable and customizable alternative using Arduino hardware to interface with electrochemical setups.

 Features

- Real-time data acquisition from electrochemical sensors  
- Support for voltammetric techniques (e.g., cyclic voltammetry)  
- Analog signal conditioning (amplification, filtering)  
- Serial communication with PC for data logging and visualization  
- Modular and customizable hardware and software
  
 Hardware Requirements

- Arduino Uno/Nano (or compatible board)  
- Operational amplifiers (e.g., TL072, LM358)  
- Resistors, capacitors for signal conditioning  
- Electrochemical sensor/electrode system  
- USB cable for data transfer  
- Breadboard or custom PCB (optional)

Software Requirements

- Arduino IDE  
- Serial monitor or Python-based serial logger 
-  Python + Matplotlib for plotting
  
 How to Use

1. Assemble the circuit as per the schematic.
2. Upload the Arduino sketch from the `code/` directory.
3. Open the serial monitor (or use the Python script) to read and log data.
4. (Optional) Plot the data using tools like Python, Excel, or MATLAB.





