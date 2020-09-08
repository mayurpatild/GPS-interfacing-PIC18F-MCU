# GPS-interfacing-PIC18F-MCU
A simple code to get current location coordinates achieved by interfacing GPS module with PIC18F- Micro Controller using USART (Serial) Communication


How to Calculate Latitude and Longitude in GPS coordinates form
We get Latitude and Longitude from GGA string which is in the form of ddmm.mmmm and dddmm.mmmm respectively.

Where,
D – degree
M – minutes

Now, we can convert received latitude and longitude string in DMS (Degree Minute Second) and Degree Decimal.

DMS – [dd] degree, [mm] minutes, [(.mmmm)*60] seconds

Degree Decimal– [dd] degree + (mm.mmmm/60)

E.g. We have following Lat/Long data in NMEA format
Latitude – 1840.9639
Longitude – 07347.6174

Now, convert them in the following format –

DMS – 18° degree 40 minutes 57.834 seconds

Degree -  18.499398
