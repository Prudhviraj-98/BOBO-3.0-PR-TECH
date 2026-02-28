1. Required Components
To complete this build, you will need the following hardware:
ESP32 Development Board  
1.3 inch SH1106 OLED Display (I2C, 128x64)  
Buzzer  
Touch Sensor or Push Button  
Jumper Wires  
Power Supply (5V USB)  
2. Wiring Connections
Ensure the components are wired correctly to the ESP32:
OLED VCC: Connect to 3.3V or 5V (depending on your specific module).  
OLED GND: Connect to ESP32 GND.  
OLED SDA: Connect to GPIO 4.  
OLED SCL: Connect to GPIO 5.  
Buzzer: Connect positive to GPIO 6 and negative to GND.  
Touch/Button: Connect output to GPIO 3 and GND appropriately.5. First Boot & Configuration
Upon the first boot, the device will enter Setup Mode:
WiFi Network: Connect to the SSID BOBO_SETUP.  
Password: 12345678.  
Configuration Interface: Open a web browser and navigate to 192.168.4.1.  
Credentials: Enter your home WiFi details and your OpenWeatherMap API key.  
Finalize: Save the settings and reboot the device.  
Project Features
Once configured, the BOBO Smart Display includes:
Animated Emoji Eyes  
Digital Clock with NTP Synchronization  
Weather Display including Forecasts  
World Clock  
Alarm with Sound  
Web-based Configuration
