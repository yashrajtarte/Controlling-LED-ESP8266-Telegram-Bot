# Controlling LED using ESP8266 and Telegram Bot - IoT Project

This project demonstrates how to control an LED connected to ESP8266 using a Telegram bot. By utilizing the Telegram messenger app, users can easily send commands to control the ESP8266 board. With the addition of relays or TRIAC, this project can be expanded into a home automation system.

## Components Required

- ESP8266
- LED
- 470Ω Resistor
- Breadboard
- USB Cable
- Connecting Wires

## Hardware Setup

1. Connect the components according to the provided circuit diagram.
2. Make sure to place the 470Ω resistor in series with the LED.
3. Connect the ESP8266 board to your computer using the USB cable.

## Software Setup

### Telegram Bot Configuration

1. Install Telegram on your laptop or phone.
2. Search for BotFather in Telegram and create a new bot.
3. Take note of the generated token, which will be used for interaction between the device and Telegram bot API.

### Programming ESP8266

1. Download the Telegram Bot library for Arduino.
2. Open Arduino IDE and navigate to "Sketch" > "Include Library" > "Add .ZIP Library" to add the downloaded library.
3. Copy the provided ESP8266 programming code into the Arduino IDE.
4. Replace `<Your WiFi Name or SSID>` with the name of your Wi-Fi network.
5. Replace `<Your WiFi Password>` with the password for your Wi-Fi network.
6. Replace `<Token you get while creating the bot>` with the token obtained from BotFather.

## Usage

1. Upload the code to the ESP8266 board using the Arduino IDE.
2. Open the Telegram app and search for your newly created bot.
3. Start the bot by sending the "/start" command.
4. To turn on the LED, send the "on" command to the bot. You will receive a reply confirming the LED is ON.
5. To turn off the LED, send the "off" command to the bot. You will receive a reply confirming the LED is OFF.

## License

This project is licensed under the MIT License [https://opensource.org/licenses/](LICENSE)

## Acknowledgments

- Basamma B for providing the original project idea and code.
- Telegram for their messaging platform and bot API.
- Arduino community for the ESP8266 library and development resources.
