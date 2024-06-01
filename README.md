# Arbiter-MQTT
Tire-kicking Sandbox to test MQTT as a transport for next-gen lighting control protocols.

## Design Goal
Create a Controller, Arbiter, and Device Process that can simulate a prototype control paradigm.

### MVP
Controller, via the Arbiter, sets the end device's dataSource property to a URL string that points back to the controller.