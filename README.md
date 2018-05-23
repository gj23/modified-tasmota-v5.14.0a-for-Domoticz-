# modified-tasmota-v5.14.0a-for-Domoticz-
get 4 DS18x20 Sensors in Domoticz

1. replace the files in your tasmota.
2. for german use de-DE.h or for english en-GB.h file.
3. in user_config.h include #define USE_DS18x20_LEGACY (delete "//" before at line 257) to use multi sensor
4. flash your device.
5. set your domoticz sensor idx values from your sensors in domoticz to the tasmota domoticz site on your device.
6. now you get all your 4 sensor values in domoticz from tasmota
