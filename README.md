# Home Assistant Blueprints

A collection of blueprints for Home Assistant automations.

## Quick Links
### Remote Controls
- [IKEA STYRBAR - four button remote](#switch---ikea-styrbar---four-button-remote)
- [IKEA SOMRIG - two button remote](#switch---ikea-somrig---two-button-remote)
- [IKEA RODRET - two button remote](#switch---ikea-rodret---two-button-remote)

## Remote Control Blueprints

### Switch - IKEA STYRBAR - four button remote

This blueprint allows you to control your home with an IKEA STYRBAR remote using ZHA integration. Each button on the remote (up, down, left, and right) can be configured with both short press and long press actions.

#### Features
- Configure actions for all 8 possible button combinations:
  - Up button: Short press and long press
  - Down button: Short press and long press
  - Left button: Short press and long press
  - Right button: Short press and long press
- Assign any type of action to each button press:
  - Turn lights on/off
  - Activate scenes
  - Run scripts
  - Call services
  - And more...

#### Installation
1. Add this blueprint repository to Home Assistant:

   [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-styrbar-four-button-remote.yaml)

2. Create a new automation using the blueprint
3. Select your IKEA STYRBAR remote
4. Configure the desired actions for each button press

#### Notes
- For the left and right buttons, the "on" event is triggered before the long press event
- Compatible with:
  - IKEA STYRBAR remote (E2001/E2002)
  - IKEA STYRBAR Remote control N2

### Switch - IKEA SOMRIG - two button remote

This blueprint allows you to control your home with an IKEA SOMRIG remote using ZHA integration. Each button (single dot and double dot) can be configured with short press, double press, long press, and release after long press actions.

#### Features
- Configure actions for all 8 possible button combinations:
  - Single dot button: Short press, double press, long press, and release
  - Double dot button: Short press, double press, long press, and release
- Assign any type of action to each button press:
  - Turn lights on/off
  - Activate scenes
  - Run scripts
  - Call services
  - And more...

#### Installation
1. Add this blueprint repository to Home Assistant:

   [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-somrig-two-button-remote.yaml)

2. Create a new automation using the blueprint
3. Select your IKEA SOMRIG remote
4. Configure the desired actions for each button press

#### Notes
- Compatible with:
  - IKEA SOMRIG shortcut button
  - IKEA SOMRIG shortcut button (E2213)

### Switch - IKEA RODRET - two button remote

This blueprint allows you to control your home with an IKEA RODRET remote using ZHA integration. Each button (top and bottom) can be configured with short press, long press, and release after long press actions.

#### Features
- Configure actions for all 6 possible button combinations:
  - Top button: Short press, long press, and release after long press
  - Bottom button: Short press, long press, and release after long press
- Assign any type of action to each button press:
  - Turn lights on/off
  - Activate scenes
  - Run scripts
  - Call services
  - And more...

#### Installation
1. Add this blueprint repository to Home Assistant:

   [![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Baanaaana/ha-blueprint/blob/main/switch-ikea-rodret-two-button-remote.yaml)

2. Create a new automation using the blueprint
3. Select your IKEA RODRET remote
4. Configure the desired actions for each button press

#### Notes
- Compatible with:
  - IKEA RODRET Dimmer
  - IKEA RODRET wireless dimmer/power switch (E2201)

## Support

If you find any issues or have suggestions for improvements, please open an issue on GitHub.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 