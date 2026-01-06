# EE102 Term Project: Door Security System

The project consists of two main parts. In the first part, a password is entered using hand detection implemented in Python with OpenCV. The detected input is transmitted to the FPGA via UART communication using PySerial.

In the second part, the received data is processed on the BASYS3 FPGA using VHDL. UART-based password verification, alarm control, seven-segment display output and door control logic are all implemented within the VHDL-based system using external hardware components.

📄 Further technical details are provided in the [project report](EEE102_Project_Report.pdf).  
🎥 [Project Demo Video](https://youtu.be/GS6-5niaZwo)
