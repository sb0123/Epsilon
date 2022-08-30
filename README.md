# Projects

EPSILON V0.1:

*The Schematics, pcb design and code uploaded are of the initial proof of concept
of the device and will be subject to many changes.I am currently working on developing and testing  the code for the device on this initial prototype.*

*Please note that the pcb is designed in a way to make it possible for it to be prototyped by toner transfer etching method.*


Epsilon is a ESP32 based Remote Control Transmitter primarily designed to be able to control manual Robots
and can also be configured to control devices and send data over long distances.

It uses the ESP-NOW protocol to transmit data between the transmitting ESP microcontroller
and receiving ESP microcontroller.

ESP-NOW is a kind of connectionless Wi-Fi communication protocol that is defined by Espressif. 
Different from traditional Wi-Fi protocols, the first five upper layers in OSI are 
simplified to one layer in ESP-NOW, so the data does not need to go through the physical layer, 
data link layer, network layer, transport layer in turn, which reduces the delay caused by packet 
loss under congested network, and leads to quickly response time.
