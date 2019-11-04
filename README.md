# ez_flight_logger
## yet another flight logger ##

A simple device for ultralight flight:
* Records **lat/long, msl altitude, speed & heading over ground, satellites used / in view, temperature, humidity, max total acceleration (G-meter), aircraft heading** and others
* **Clock & Flight hour meter**
* **Displays heading, distance and ETA to a target and depart (home) airfield** 
* Electronic compass and accelerometer

... and CHEAP! Since an aviation spherical compass is EUR 150, this setup will cost around EUR 70.

This version is a *no buttons* interface.

The save frequency is configurable (default: 10 seconds).
The logs are saved on SDCARD in a YYYYMMDD.CSV format

The home airfield coordinates are read automatically at take-off. *It happened once to get almost lost in air, at a few km distance from the airfield, so I'm considering this useful for the beginner pilot.*

The flight hour meter starts automatically after taking off.

The configuration file is a json stored on sd-card. All data is stored on SDCARD.

This early version has some issues at compass (magnetometer) math and acceleration noise (vibration) filtering.
