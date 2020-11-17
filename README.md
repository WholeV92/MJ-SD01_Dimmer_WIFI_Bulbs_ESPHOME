# MJ-SD01_Dimmer_WIFI_Bulbs_ESPHOME
Martin Jerry SD01 Dimmer ESPHome file for control of Wifi bulbs with Home Assistant.
v0.1 - Port from mjoshd's ESPHome MJ SD01

Initial Port of the code from mjoshd's "esphome_martin-jerry-mj-sd01-dimmer".
  - Used for WIFI / Hue Bulbs that do not respond to the dimming function from the base code
  - Currently set up to use Home Assistant , MQTT and Node Red.
  - 6 MQTT topics are published from the 3 buttons depending on the time that the button is held down for [substitutions has dependencies for both long and short press].
  - the 4 dimming LEDs are controllable as switches on within Home Assistant [note that the first dimmer LED is tied to the Dimmer PWM and will be on when the dimmer is on].
  - Have left in the ability to to control  both the relay and the dimmer.  Relay to easily reset the lights if they drop from WiFi.  Left the dimmer as I am still trying to figure that out.
  
  
Disclaimer
⚠️ DANGER OF ELECTROCUTION ⚠️

These devices are not toys. They use Mains AC so there is a danger of electrocution if not installed properly. If you don't know how to install it, please call an electrician. Remember: SAFETY FIRST. It is not worth to risk yourself, your family and your home if you don't know exactly what you are doing. Never try to connect a wire to flash a device while it is connected to MAINS AC.

We don't take any responsibility nor liability for using this software nor for the installation or any tips, advice, videos, etc. given by any member of this site or any related site.

Disclaimer borrowed from Tasmota github page.
