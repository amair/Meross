# Meross utilities
Tools to help configure the Meross devices for purpose of utilising our <a href="https://github.com/bytespider/Meross/wiki/MQTT">own MQTT servers</a>.

Before you can use the tool to setup your device you need to put it into paring mode and connect to it's Access Point. It's IP address is known as the `--gateway` parameter and is typically `10.10.10.1`.

## NEW - Home Assistant
With a bit of fiddling it's possible to get these devices to work with Home Assistant (HASSIO).
<a href="https://github.com/bytespider/Meross/wiki/Home-Assistant-(HASSIO)">Setup Home Assistant MQTT</a>

## Tools
### Info
`npx meross info [--inclide-wifi]`
Gets information from the device you are connected to in setup mode and optionally the WIFI SSID's it can see.

### Setup
`npx meross setup [options]`
Setup device you are connected to in setup mode
