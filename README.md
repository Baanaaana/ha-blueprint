# Home Assistant Blueprints

A collection of blueprints for Home Assistant automations.

## Blueprints

### Switch - IKEA STYRBAR - four button remote

This blueprint allows you to control your home with an IKEA STYRBAR remote (model E2001/E2002) using the ZHA integration. Each button on the remote (up, down, left, and right) can be configured with both short press and long press actions.

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
- Requires the ZHA (Zigbee Home Automation) integration
- Compatible with IKEA STYRBAR remote model E2001/E2002 (Remote Control N2)

## Support

If you find any issues or have suggestions for improvements, please open an issue on GitHub.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 