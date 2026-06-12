# deskradar
Flightradar display using ESP8266 (Wemos D1 mini) and 1.28 inch TFT  Screen (240x240 , IC:GC9A01)

I ran into some issues using the original code. My version uses a different library for the screen. Also other code components were adjusted to work with an esp8266.
Don't forget to set your wifi cridentials, api details and coordinates.

Register at: https://opensky-network.org/
get the api from there.

Pinout:
| Screen | Wemos D1 |
| ------ | -------- |
| VCC    | 3.3 V    |
| GND    | GND      |
| SCL    | D5       |
| SDA    | D7       |
| DC     | D2       |
| CS     | D8       |
| RST    | D4       |
