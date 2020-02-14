# bsec_bme680_node-red

Use a Bosch BME680 sensor with BSEC library on Raspberry PI and log data to InfluxDB using Node-RED

Code is a copy of https://github.com/rstoermer/bsec_bme680_python updated and compiled with current BSEC library.

## Compile

Download the BSEC library:

https://www.bosch-sensortec.com/media/boschsensortec/downloads/bsec/bsec_1-4-7-4_generic_release.zip

unzip into ./src/BSEC_1.4.7.4_Generic_Release and run ./make.sh

## Node-RED

Copy bsec_bme680 to your home folder (/home/pi) and import the file flows.json into Node-RED

