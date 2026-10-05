# Blueprints

Home Assistant automation blueprints for Zigbee buttons controlled via
[Zigbee2MQTT](https://www.zigbee2mqtt.io/). They listen to the
`<base topic>/<friendly name>/action` MQTT topic, which Zigbee2MQTT publishes
when its Home Assistant integration is enabled.

Requires Home Assistant 2024.10 or newer.

## IKEA E2213 SOMRIG shortcut button

[`zigbee2mqtt_ikea_e2213_somrig_shortcut_button.yaml`](zigbee2mqtt_ikea_e2213_somrig_shortcut_button.yaml)

Single press, double press, hold (repeating) and release after hold for both
buttons (dots 1 and dots 2).

[![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FMoselmann%2Fhomeassistant%2Fblob%2Fmain%2Fblueprints%2Fzigbee2mqtt_ikea_e2213_somrig_shortcut_button.yaml)

## Tuya TS0041 1-button scene switch

[`zigbee2mqtt_smart_1_button_scene_switch_ts0041.yaml`](zigbee2mqtt_smart_1_button_scene_switch_ts0041.yaml)

Single press, double press and hold.

[![Open your Home Assistant instance and show the blueprint import dialog.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FMoselmann%2Fhomeassistant%2Fblob%2Fmain%2Fblueprints%2Fzigbee2mqtt_smart_1_button_scene_switch_ts0041.yaml)
