# Pressure Gauge Reader
Project to read an analogue pressure gauge using a Raspberry Pi and camera.
## Requirements
* Take picture of analogue pressure gauge.
* Process image to determine the angle of the pointer.
* Calculate the pressure in PSI and Bar using the angle of the pointer.
* Overlay markings on the captured image.
* Output: Pointer angle, pressure PSI, pressure Bar.
* Write data to a time series database (InfluxDB).

