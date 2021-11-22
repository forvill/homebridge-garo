# homebridge-garo

## About
Trying to make Homebridge support for Garo GLB. This i a test projet to make GARO GLB avaliable in Homebridge.

This is a plugin for [Homebridge](https://homebridge.io/), allowing you to control GARO GLB EV Charger.   

## Installation
### Plugin installation
1. Install [Homebridge](https://homebridge.io/) using: `npm install -g homebridge`
2. Install homebridge-garo using: `npm install -g homebridge-garo`
3. Configure homebridge-garo by editing your `~/.homebridge/config.json` file, or use [config-ui-x](https://www.npmjs.com/package/homebridge-config-ui-x). See example below:
## Configuration
### Configuration Example:
``` json
{
    "accessory": "GAROCharger",
    "name": "My Garo",
    "IP": "YOUR_GARO_IP",
    "debug": true,
}
```
### Configuration Parameters:
- `name`: Required string. Name of the accessory. Siri uses this parameter for identifying your GARO.
- `IP`: Required string. Your GARO ip address.
- `debug`: Optional boolean (default: `false`)


## Supported Device
- [GARO GLB](https://www.garo.se/sv/proffs/produkter/ladda-din-elbil/laddbox/kompletta-laddboxar/laddbox-glb-t2fc-22kw-m-w)

## Known issues / To Do list
### ToDo next
### Warning

## Acknowledgment
- Plugin based on [homebridge-wallbox](https://github.com/mrx007/homebridge-wallbox) which is based on [homebridge-http-lock-ultimate](https://github.com/TheRealSimonMlr/homebridge-http-lock-ultimate)
