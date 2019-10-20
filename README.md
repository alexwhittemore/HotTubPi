HotTubPi
========

External heating controller for portable spas

Project details: https://hackaday.io/project/166528-smartsoak

### About

This flow implements data telemetry and temperature control for a hot tub using an external propane camp shower heater.

### Hardware Configuration

A Raspberry Pi runs this node-red flow as the central controller. The interface can be accessed via the web.

4 DS18B20 temperature sensors attach to 4 separate 1Wire busses These measure the water temperature, the enclosure temperature, and 2 external air temperatures. 
**TODO:** Add configuration guide for this. 

The Pi controls one external relay, that switches 12V to a high pressure demand pump to circulate water through the heater.

