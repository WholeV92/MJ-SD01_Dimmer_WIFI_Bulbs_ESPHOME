# MJ-SD01_Dimmer_WIFI_Bulbs_ESPHOME
Martin Jerry SD01 Dimmer ESPHome file for control of Wifi bulbs with Home Assistant.
v0.1 - Port from mjoshd's ESPHome MJ SD01

Initial Port of the code from mjoshd's "esphome_martin-jerry-mj-sd01-dimmer".
  - Used for WIFI / Hue Bulbs that do not respond to the dimming function from the base code
  - Currently set up to use Home Assistant , MQTT and Node Red.
  - 6 MQTT topics are published from the 3 buttons depending on the time that the button is held down for [substitutions has dependencies for both long and short press].
  - the 4 dimming LEDs are controllable as switches on within Home Assistant [note that the first dimmer LED is tied to the Dimmer PWM and will be on when the dimmer is on].
  - Have left in the ability to to control  both the relay and the dimmer.  Relay to easily reset the lights if they drop from WiFi.  Left the dimmer as I am still trying to figure that out.
  
  
