# Smart-Home-Energy-Management-System
Project Objective
The objective of this project is to develop a smart home management system that allows users to control home devices such as lights, fans, and thermostats. The system enables turning devices on or off, setting temperatures, and monitoring energy consumption. Additionally, it provides email notifications for energy consumption and temperature settings.

Project Working
Components
Device Class:

Represents a generic smart device with basic functionalities such as turning on/off and tracking energy consumption.
Sends email notifications for energy consumption.
Light, Fan, Thermostat Classes:

Inherit from the Device class, each representing specific smart home devices with additional functionalities (e.g., setting temperature for the Thermostat).
Functionality
Turning Devices On/Off:

Users can turn lights and fans on or off using specific commands.
Setting Temperature:

Users can set the temperature of the thermostat, and an email notification will be sent with the new temperature.
Energy Consumption Tracking:

Each device tracks its energy consumption, which is updated every 5 seconds when the device is on.
Users can check the current energy consumption of all devices and receive an email summary.
Email Notifications:

Uses the smtplib library to send email notifications for energy consumption and temperature settings.
Email server configuration is included within the send_energy_message and send_temperature_message methods.
