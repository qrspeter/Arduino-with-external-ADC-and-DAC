# Arduino-with-external-ADC-and-DAC
Arduino Uno manages with external ADC MCP3424 and DAC MCP4725 under PC control for a current-sensing project.

Using Arduino 1.8.19 

5 COPs to communicate with PC:
•	sensor_reset
•	setDAC_Gate – set gate DAC,
•	setDAC_Drain – set drain DAC,
•	setADC – set ADC and start conversion,
•	getADC - get result of conversion
