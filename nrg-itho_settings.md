# Relevant/customized settings on NRG-ITHO-B298

## Wifi setup

- SSID: `DeadDave`
- Password: ***
- Use DHCP: on
- Hostname: `nrg-itho-b298`
- ...


## System settings

- ...
- Itho RF remote support: on


## RF devices

```
index   id          name        remfunc         remtype
0       96,CF,3B    office      Monitor Only    RFT CO2
1       96,CF,2C    kitchen     Monitor Only    RFT CO2
2       96,B2,B3    bedroom     Monitor Only    RFT CO2
3       97,ED,CF    bathroom    Monitor Only    RFT RV
```

## MQTT

- MQTT Active: on
- Server: `192.168.1.107`
- Username: `mqttuser`
- Password: ***
- Port: `1883`
- MQTT base topic: `itho`
- Home Assistant MQTT Discovery: on
- Home Assistant Discovery topic prefix: `homeassistant`
- Domoticz MQTT: off
