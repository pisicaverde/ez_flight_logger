# ez_flight_logger
## yet another flight logger ##

A simple, panel-mounted, ultralight flight helper:
* Records **coordinates, altitude, ground speed, heading, temperature, humidity, acceleration (G-meter)** and others
* **RTC, Time recording & Flight hour meter**
* **Displays heading, distance and ETE to a target and depart airfield** 
* Electronic compass and accelerometer
* shows your position on map (via Google Maps -- API key is required).
* Data is saved on SD card AND sent via POST to a simple server side script through 2G
* 2 Buttons interface.
* configuration is done

Server side:
* the received data is saved on server
* the tracked position and sensor data  is shown in real time on map

Fail tolerant: if a hardware part or a software function does not work, it is skipped and the others should continue working.
