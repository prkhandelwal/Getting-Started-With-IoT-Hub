# Getting-Started-With-IoT-Hub

This is a starter sample to Get Started with Azure IoT Hub. The project uses AMPQ protocol for communication by default. An Override function can be written to use alternate protocols like MQTT, HTTPS etc.

## CreateDeviceIdentity
In case you are simulating an IoT device on your PC, 
This is a .NET console app that creates a device identity in the identity registry in your IoT hub. A device cannot connect to IoT hub unless it has an entry in the identity registry.

## ReadDeviceToCloudMessages
This is a .NET console program to receive messages sent to IoT Hub by the IoT Device at realtime. The project calls for the values with Time Stamp after the program is started.

## SimulatedDevice
This is a .NET console application to simulate a temperature & Humidity sensor and send the simulated values to the IoT Hub.
