# dpf-monitor
DPF MONITOR for ALFA ROMEO - Arduino Nano ATmega328 + L9637D +  SH1106 OLED display

This is tool for read data in real time from the OBD-II port through the K-line pin using ISO 9141-2.
The L9637 is a monolithic integrated circuit containing standard ISO 9141 compatible interface functions.
Arduino Nano based on the ATmega328 processor provides support for sent and received messages from K-line, and displays the received data on the OLED display using the I2C protocol. 
The received data is displayed on the SH1106 OLED display.
To simplify the system, Arduino Nano power is supplied via the miniUSB port from the power bank. Of course, you can use an additional 7805 chip and power the entire system from the vehicle installation.
