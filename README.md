:::writing{variant=“standard” id=“73418”}

<div align="center">


Redox FT Dongle Edition

Wireless ergonomic split keyboard with dedicated USB dongle support powered by ZMK.

<img src="https://raw.githubusercontent.com/zmkfirmware/zmk/main/docs/static/img/zmk-logo.png" width="140">


</div>



⸻

Overview

This repository contains firmware for the FalbaTech Redox FT Dongle Edition.

Configuration:
	•	Left half → BLE Peripheral
	•	Right half → BLE Peripheral
	•	Dongle → BLE Central + USB HID

The dongle connects to both keyboard halves over Bluetooth and sends all key events to the computer through USB.

⸻

Features
	•	ZMK Firmware
	•	Wireless split keyboard
	•	USB dongle support
	•	ZMK Studio compatible
	•	nice!nano v2 compatible
	•	BLE profile support
	•	RGB support
	•	OLED / nice!view support
	•	USB HID through dongle

⸻

Hardware

Keyboard halves
	•	nice!nano v2 compatible controllers
	•	Bluetooth split communication
	•	Rechargeable battery powered

Dongle
	•	nice!nano v2
	•	USB connected to computer
	•	BLE central device

⸻

First Flashing

⚠ IMPORTANT ⚠

Before flashing firmware for the first time:
	1.	Flash settings_reset.uf2
	2.	Flash final firmware

Repeat this for:
	•	left half
	•	right half
	•	dongle

This prevents old BLE pairing problems.

⸻

Build Outputs

GitHub Actions generates firmware for:

Device	Type
Redox FT Left	BLE Peripheral
Redox FT Right	BLE Peripheral
Redox FT Dongle	BLE Central + USB


⸻

Pairing
	1.	Turn on both keyboard halves
	2.	Connect dongle through USB
	3.	Wait a few seconds
	4.	Devices should pair automatically

⸻

Repository Structure

boards/
config/
.github/workflows/


⸻

Powered By
	•	ZMK Firmware
	•	nice!nano v2
	•	FalbaTech Redox FT

⸻


<div align="center">


Made in Poland by FalbaTech

</div>
:::
