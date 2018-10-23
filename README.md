# GPS geolocation using TinyGPS

Code to interface with the GPS module and extract geolocation information (latitude and longitude) if sufficient satellites are available. Please do not test indoors as the GPS may not detect any satellites, thus no geolocation information will be printed.

- [Wiring](#wiring)
- [Required libraries](#required-libraries)
- [Additional resources](#additional-resources)

Code devloped by Sheffield Eco Motorsports.

# Wiring
 * Arduino 5V to GPS `VDD`
 * Arduino GND to GPS `GND`
 * Arduino digital pin 3 to GPS `TX`
 * Arduino digital pin 4 to GPS `RX`

# Required libraries
 * `SoftwareSerial`
 * `TinyGPS`

These libraries are included in the repository.

# Additional resources
 * [Interfacing](https://create.arduino.cc/projecthub/ruchir1674/how-to-interface-gps-module-neo-6m-with-arduino-8f90ad)
 * [Wiring](http://www.ayomaonline.com/iot/gy-gps6mv2-neo6mv2-neo-6m-gps-module-with-arduino-usb-ttl/)
