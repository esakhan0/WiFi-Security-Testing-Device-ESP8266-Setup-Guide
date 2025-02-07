📢 Disclaimer:
This guide is for educational and cybersecurity research purposes only.
Ensure compliance with all applicable laws before using this software.
The author is not responsible for misuse of this information.

About This Project : This device is designed as an ESP8266-based WiFi Security Testing and Research Tool. It allows users to analyze, monitor, and improve their own network security.

✅ Supports ESP8266-based boards (NodeMCU, Wemos D1 Mini, etc.)

✅ Open-source firmware for educational cybersecurity research

✅ OLED Display + Button control for on-device interaction

📌 No software is preinstalled. Users must flash firmware manually.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Hardware Requirements
Before proceeding, ensure you have:

ESP8266 board (NodeMCU, Wemos D1 Mini, etc.)

USB cable (for flashing)

Computer (Windows, Mac, or Linux)

Flashing software (ESPTool or NodeMCU PyFlasher)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

HOW TO FLASH FIRMWARE :

This guide will show you how to install WiFi security research software onto your ESP8266. Look Below
There is also a gui installation below these steps. (Beginners)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1️⃣ Install Required Tools
To flash firmware, install:
ESPTool (Python-based)
"pip install esptool"


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2️⃣ Download the Open-Source Firmware
For software installation, visit:

📌 Official Firmware Repository : https://github.com/spacehuhn/esp8266_deauther

👉 Do not download or use this software on unauthorized networks.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


3️⃣ Flashing the Firmware
Using ESPTool, run:
esptool.py --port COMx --baud 115200 write_flash 0x00000 firmware.bin

(Replace COMx with your actual port, e.g., COM3 on Windows or /dev/ttyUSB0 on Linux.)

Using NodeMCU PyFlasher:

Select the ESP8266 board and COM port.

Choose the firmware.bin file.

Set baud rate to 115200.

Click Flash.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4️⃣ Restart and Test Your Device

Unplug and replug the ESP8266.

The software should now be running.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔹 How to Flash Firmware Using ESPFlasher.exe (Windows)

1️⃣ Download & Install ESPFlasher

📌 Download ESPFlasher.exe from:

🔗 Official Download Link : https://github.com/Jason2866/ESP_Flasher/releases

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2️⃣ Download the Open-Source Firmware

For software installation, visit: https://github.com/spacehuhn/esp8266_deauther


👉 Do not download or use this software on unauthorized networks.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3️⃣ Flash the Firmware

SUB 1: Open ESPFlasher.exe

SUB 2: Select the correct COM Port (Check Device Manager for Windows)

SUB 3: Click Browse and select your firmware.bin file

SUB 4: Click Flash and wait for completion

SUB 5: Once done, restart your ESP8266

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4️⃣ Restart and Test Your Device

Unplug and replug the ESP8266.

The software should now be running.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📜 Legal & Ethical Use

This software is intended for educational purposes only.
Unauthorized use on networks you do not own is illegal.
The developer and contributors are not responsible for misuse.

📌 By following this guide, you accept full responsibility for compliance with local laws.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🔗 Additional Resources

Official Firmware Repo : https://github.com/spacehuhn/esp8266_deauther

Cybersecurity Research & Ethical Hacking : https://www.cybersecurityguide.org/

