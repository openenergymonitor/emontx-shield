# emonTx Arduino Shield Firmware

# Upload

Either use:

* Platform IO: [see guide](https://guide.openenergymonitor.org/technical/compiling)
* Or Arduino IDE

## Full emonTx Shield Firmware Examples
* **Shield_CT1234** - RFM12B - Apparent Power Example - Use this example if only using CT sensors. Monitors AC current using one CT sensor and transmit data via wireless using RFM12B to emonBase.

* **Shield_CT1234_Voltage** - RFM12B - Real Power - Use this example if using an AC-AC adapter with as well as CT sensors. AC-AC plug-in adapter to monitors AC RMS voltage and give real power and current direction readings transmit data via wireless using RFM12B to emonBase

* **Shield_CT1234_Voltage_NanodeRF** - NO RF - Real Power - Use this example if using an AC-AC adapter with as well as CT sensors. AC-AC plug-in adapter to monitors AC RMS voltage and give real power and current direction readings. Designed for use with the emonTx Shield mounted on a nanode RF. No RF module is required on either shield or Nanode, the power readings are posted stright to emoncms.org via Etherent on the Nanode

* **Shield_CT1234_SerialOnly** - NO RF - Real Power - Use this example if using an AC-AC adapter with as well as CT sensors. AC-AC plug-in adapter to monitors AC RMS voltage and give real power. Prints out power readings via Arduino Serial port. No RF required.






## emonTx Code guide

The [EmonTx code guide](https://github.com/openenergymonitor/emontx2/tree/master/firmware/Guide) goes through main components required to put a full emontx firmware together. It's recommended that you work through these examples first so that you have a good understanding of how the full firmware's work.

* 01 - Single CT
* 02 - Second CT
* 03 - AC Voltage
* 04 - Temperature
* 05 - Pulse Counting
* 06 - Elster Meter
* 07 - Transmitting Data
* 08 - Watchdog



**Note:** CT must be clipped round either the Live or Neutral wire, NOT both!

When the example has been successfully uploaded the LED should blink quickly once every 10's


# License

The emonTx hardware designs (schematics and CAD files) are licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.

The emonTx firmware is released under the GNU GPL V3 license

The documentation is subject to GNU Free Documentation License

The emonTx hardware designs follow the terms of the OSHW (Open-source hardware) Statement of Principles 1.0.






 
