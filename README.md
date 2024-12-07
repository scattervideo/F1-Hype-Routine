# F1-Hype-Routine

A series of HA helpers, automations and scripts for F1 racing tracking.  
This uses HomeAssistant with the TeamTracker, Alexa Media Player and LIFX integrations to create a F1 race tracker based upon LIFX LED light strips.

It gets data from the ESPN API for the top 3 race positions and converts it into driver name, team name, team color.
Then announces positions on Alexa devices and creates 3 "car-colored" lights that race around the strip in race order.

I am trying to figure out a method to do this with WLED and industry standard LEDS with ESP32 but haven't quite gotten that yet.

