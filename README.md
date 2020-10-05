# dpf-monitor
DPF MONITOR for ALFA ROMEO - Arduino Nano ATmega328 + L9637D +  SH1106 OLED display

This is device for read data in real time from the OBD-II port through the K-line pin using ISO 9141-2.
The device is connected with three wires: + 12V power supply, ground, K-line port.
The device is plugged directly into the OBD-II diagnostic connector. An ELM interface is not required or needed.
The L9637 is a monolithic integrated circuit containing standard ISO 9141 compatible interface functions.
Arduino Nano based on the ATmega328 processor provides support for sent and received messages from K-line, and displays the received data on the OLED display using the I2C protocol. 
The received data is displayed on the SH1106 OLED display.
To simplify the system, Arduino Nano power is supplied via the miniUSB port from the power bank. Of course, you can use an additional 7805 chip and power the entire system from the vehicle installation.

Compatibile ECU and cars with this tool:

Bosch EDC16C39 CF4/EOBD (engine 1.9/2.4)

ALFA, 147, 1.9 JTD
ALFA, 147, 1.9 JTD 16V
ALFA, 156 '02, 1.9 JTD 16V
ALFA, 159, 1.9 MJET 16V
ALFA, 159, 1.9 MJET 8V
ALFA, 159, 2.4 MJET 20V
ALFA, 166, '03 2.4 JTD 20V
ALFA, BRERA, 2.4 MJET 20V
ALFA, GT, 1.9 JTD 16V
FIAT, BRAVO '07, 1.9 MJET 16V
FIAT, BRAVO '07, 1.9 MJET 8V
FIAT, CROMA '05, 1.9 MJET 16V
FIAT, CROMA '05, 1.9 MJET 8V
FIAT, CROMA '05, 2.4 MJET 20V
FIAT, DOBLO', 1.9 JTD
FIAT, MULTIPLA, '02 1.9 JTD
FIAT, STILO, 1.9 JTD
FIAT, STILO, 1.9 JTD 16V
LANCIA, THESIS, 2.4 JTD 20V

MONITOR DPF dla ALFA ROMEO - Arduino Nano ATmega328 + L9637D + SH1106 wyświetlacz OLED

Jest to urządzenie do odczytu danych w czasie rzeczywistym z portu OBD-II przez pin K-line przy użyciu ISO 9141-2.
Urządzenie podłącza się trzema przewodami: zasilanie + 12V, masa, port K-line.
Urządzenie wpinane jest bezpośrednio w złącze diagnostyczne OBD-II. Interfejs ELM nie jest wymagany ani potrzebny.
L9637 to monolityczny układ scalony zawierający funkcje interfejsu zgodne ze standardem ISO 9141.
Arduino Nano oparty na procesorze ATmega328 zapewnia obsługę wysyłanych i odbieranych wiadomości z linii K oraz wyświetla otrzymane dane na wyświetlaczu OLED za pomocą protokołu I2C.
Odebrane dane są wyświetlane na wyświetlaczu OLED SH1106.
Aby uprościć system, zasilanie Arduino Nano jest dostarczane przez port miniUSB z powerbanku. Oczywiście można użyć dodatkowego układu 7805 i zasilić cały system z instalacji pojazdu.
