# Atmega32 I2C Communication

This project showcases inter-communication between two Atmega32 microcontrollers (MCUs)<br>
utilizing the Inter-Integrated Circuit (I2C) or Two-wire Interface (TWI) protocol.<br>
One MCU acts as the master, transmitting data to the slave MCU.<br>
The slave MCU then drives two connected 7-segment displays to visualize the received data.

## **Project Overview:**

* **Hardware:**
    * Two Atmega32 development boards
    * Two 7-segment displays
* **Communication Protocol:**
    * I2C: Used for data transfer between MCUs

**Data Flow:**

1. User programed data to be sent (e.g., a number) on the master MCU.
2. Master MCU transmits the data to the slave MCU using I2C.
3. Slave MCU receives the data and interprets it as a digit to display.
4. Slave MCU drives the two connected 7-segment displays to show the received digit.

### **Features:**

* Master-slave I2C communication between two Atmega32 MCUs.
* Data transmission from master to slave for 7-segment display control.
* Ability to display various digits (depending on data programming).


### **Developed and Simulated in:**

* Proteus Design Suite


### **Getting Started:**

The project files (source code, schematics, etc.) are required to run this project. found in the Atmega32 Folder. 

## **Simulation**

![Atmega32 I2C Communication](https://github.com/ArsanyMounir/Atmega32_I2C_Communication/blob/main/Proteus.gif)
