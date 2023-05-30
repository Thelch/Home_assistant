# Home_assistant
Automatisation Blueprints for Home Assistant 

Here do you find my Automatisation Blueprints for Home Assistant

To get them to work you will need:
- Home Assistant with mqtt
- Ulanzi Pixel Clock flashed with AWTRIX firmware
- Icons for Charging/ discharging


Changes needed in Batterie_loading_Awtrix :

- find and replace: input_number.batterie_test with your batterie sensor
- find and replace: sensor.victron_system_battery_state with your batterie sensor status
- find and replace: awtrix_a8f0d0 with your Pixelclock Name
