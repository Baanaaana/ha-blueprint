# Home Assistant Blueprints

A collection of blueprints for Home Assistant.

## Available Blueprints

### IKEA Remotes

- [IKEA RODRET Two Button Remote](./switch-ikea-rodret-two-button-remote.yaml)
  - Compatible with IKEA RODRET dimmer/power switch (E2201)
  - Supports short press, double press, long press and release after long press for both buttons
  - Optional battery level warning actions
  
  ![IKEA RODRET Remote](./images/ikea-rodret.jpg)
  
  [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-rodret-two-button-remote.yaml)

- [IKEA SOMRIG Two Button Remote](./switch-ikea-somrig-two-button-remote.yaml)
  - Compatible with IKEA SOMRIG shortcut button (E2213)
  - Supports short press, double press, long press and release after long press for both buttons
  - Optional battery level warning actions
  
  ![IKEA SOMRIG Remote](./images/ikea-somrig.jpg)
  
  [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-somrig-two-button-remote.yaml)

- [IKEA STYRBAR Four Button Remote](./switch-ikea-styrbar-four-button-remote.yaml)
  - Compatible with IKEA STYRBAR remote (E2001/E2002)
  - Supports short press and long press for all four buttons
  - Optional battery level warning actions
  
  ![IKEA STYRBAR Remote](./images/ikea-styrbar.jpg)
  
  [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-styrbar-four-button-remote.yaml)

### Philips Remotes

- [Philips Hue Dimmer Switch](./switch-hue-dimmer-switch.yaml)
  - Compatible with Philips Hue Dimmer Switch RWL020 (US) and RWL021 (EU)
  - Supports short press, long press, and double press for all buttons
  - Configurable actions for all four buttons
  
  ![Philips Hue Dimmer Switch](./images/hue-dimmer.jpg)
  
  [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-hue-dimmer-switch.yaml)

### IKEA Sensors

- [IKEA PARASOLL Door/Window Sensor](./switch-ikea-parasoll-door-window-sensor.yaml)
  - Compatible with IKEA PARASOLL door/window sensor (E2013)
  - Triggers actions on opening and closing events
  - Optional battery level warning actions
  
  ![IKEA PARASOLL Sensor](./images/ikea-parasoll.jpg)
  
  [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-parasoll-door-window-sensor.yaml)

- [IKEA VALLHORN Motion Sensor](./switch-ikea-vallhorn-motion-sensor.yaml)
  - Compatible with IKEA VALLHORN motion sensor (E2134)
  - Triggers actions on motion detection
  - Configurable no-motion delay
  - Optional battery level warning actions
  
  ![IKEA VALLHORN Sensor](./images/ikea-vallhorn.jpg)
  
  [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-vallhorn-motion-sensor.yaml)

- [IKEA BADRING Water Leak Sensor](./switch-ikea-badring-water-leak-sensor.yaml)
  - Compatible with IKEA BADRING water leak sensor (E2202)
  - Triggers actions on water leak detection
  - Triggers actions when water leak is cleared
  - Optional battery level warning actions
  
  ![IKEA BADRING Sensor](./images/ikea-badring.jpg)
  
  [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-badring-water-leak-sensor.yaml)

## Installation

1. Click on the blueprint you want to use
2. Click the "Raw" button
3. Copy the URL
4. Open Home Assistant
5. Go to Configuration > Blueprints
6. Click the "Import Blueprint" button
7. Paste the URL and click "Preview"
8. Click "Import Blueprint"

## Usage

After importing a blueprint:

1. Create a new automation
2. Choose the imported blueprint
3. Select your remote device
4. Configure the actions for each button press type
5. Save the automation

## Support

If you find any issues or have suggestions for improvements, please open an issue on GitHub.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 