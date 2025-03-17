# F1-Hype-Routine

A series of HA helpers, automations and scripts for F1 racing tracking.  
This uses HomeAssistant with the TeamTracker, Alexa Media Player and LIFX integrations to create a F1 race tracker based upon LIFX LED light strips (as of Jan 2025 I am using WLED but the LIFX code still works).

It gets data from the ESPN API for the top 3 race positions and converts it into driver name, team name, team color.

Then announces positions on Alexa devices and creates 3 "car-colored" lights that race around the strip in race order.

1/2025 - Created a custom Chase effect in WLED (replacing Chase) that works for F1.  It is a BIN file for ESP32 only based upon WLED 15.1 beta.  I have to figure the process to integrate with the WLED project.
2/2025 - Submitted Chase Race effect to WLED project for approval and inclusion.  Waiting...

