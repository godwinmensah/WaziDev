include ../../../WaziDev.mk

ARDUINO_LIBS += SX1272 AES-128_V10 CayenneLPP

include /usr/share/arduino/Arduino.mk

monitor:
	stty -F $(MONITOR_PORT) raw $(MONITOR_BAUDRATE)
	cat $(MONITOR_PORT)
