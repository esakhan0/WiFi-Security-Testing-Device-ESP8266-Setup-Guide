📢 Disclaimer:
This guide is for educational and cybersecurity research purposes only.
Ensure compliance with all applicable laws before using this software.
The author is not responsible for misuse of this information.

🔹 What is This?

This tutorial will show you how to flash your ESP8266 WiFi Security Testing Device using NodeMCU Flasher and a pre-compiled .bin firmware file.


This device allows you to:

✅ Test & analyze WiFi security (on networks you own)

✅ Learn about cybersecurity & ethical hacking

✅ Experiment with IoT and open-source firmware

📌 Note: This device does not come pre-flashed. Follow this guide to install the firmware.



🛠️ What You’ll Need:

✅ Our Wifi Security Testing Device

✅ USB-C Cable (or Micro-USB, depending on your board)

✅ Windows PC (Mac/Linux users can use esptool.py)

✅ NodeMCU Flasher (for flashing the firmware)

✅ Precompiled .bin Firmware File (Download below)


📥 Step 1: Download Required Files

🔹 Download NodeMCU Flasher (download above)

🔹 Download the Firmware (download above)


🔧 Step 2: Flashing the Firmware Using NodeMCU Flasher

1️⃣ Connect your ESP8266 to your PC via USB-C.

2️⃣ Run NodeMCU Flasher and select your COM Port.

3️⃣ Go to the Config tab and replace the default firmware with your .bin file.
 
4️⃣ Click Gear Icon → Select firmware.bin.

5️⃣ Go to the Advanced tab and set the baud rate to 115200.

6️⃣ Click Flash and wait for the process to complete.

Once finished, restart your ESP8266 (unplug & replug).


📌 Troubleshooting Tips:

If the flash fails, try a different USB port or cable.

Make sure you installed the correct drivers for your ESP8266.


🚀 Step 3: Testing Your Device

Once flashed, your ESP8266 should boot into the new firmware.

Follow the on-screen instructions on the OLED display (if applicable).

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

