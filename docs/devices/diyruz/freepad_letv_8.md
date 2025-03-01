---
title: "DIYRuZ FreePad_LeTV_8 Homebridge/HomeKit integration"
description: "Add HomeKit support to your DIYRuZ FreePad_LeTV_8, using Homebridge, Zigbee2MQTT and homebridge-z2m."
---
<!---
This file has been GENERATED using src/docgen/docgen.ts
DO NOT EDIT THIS FILE MANUALLY!
-->
# DIYRuZ FreePad_LeTV_8
> [LeTV 8key FreePad mod](https://modkam.ru/?p=1791)


# Services and characteristics
The following HomeKit Services and Characteristics are exposed by
the DIYRuZ FreePad_LeTV_8

* [Battery](../../battery.md)
  * Battery Level
  * Charging State
  * Status Low Battery



## Exposes

This is the information provided by Zigbee2MQTT for this device:

```json
[
  {
    "type": "numeric",
    "name": "battery",
    "property": "battery",
    "access": 1,
    "unit": "%",
    "description": "Remaining battery in %, can take up to 24 hours before reported.",
    "value_min": 0,
    "value_max": 100
  },
  {
    "type": "enum",
    "name": "action",
    "property": "action",
    "access": 1,
    "values": [
      "*_single",
      "*_double",
      "*_triple",
      "*_quadruple",
      "*_release"
    ],
    "description": "Triggered action (e.g. a button click)"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_1",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_1"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_1",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_1"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_2",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_2"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_2",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_2"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_3",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_3"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_3",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_3"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_4",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_4"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_4",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_4"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_5",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_5"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_5",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_5"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_6",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_6"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_6",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_6"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_7",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_7"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_7",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_7"
  },
  {
    "type": "enum",
    "name": "switch_type",
    "property": "switch_type_button_8",
    "access": 7,
    "values": [
      "toggle",
      "momentary",
      "multifunction"
    ],
    "endpoint": "button_8"
  },
  {
    "type": "enum",
    "name": "switch_actions",
    "property": "switch_actions_button_8",
    "access": 7,
    "values": [
      "on",
      "off",
      "toggle"
    ],
    "endpoint": "button_8"
  },
  {
    "type": "numeric",
    "name": "linkquality",
    "property": "linkquality",
    "access": 1,
    "unit": "lqi",
    "description": "Link quality (signal strength)",
    "value_min": 0,
    "value_max": 255
  }
]
```

# Related
* [Other devices from DIYRuZ](../index.md#diyruz)
* [Zigbee2MQTT documentation for this device](https://www.zigbee2mqtt.io/devices/FreePad_LeTV_8.html)