:::writing{variant=“standard” id=“58142”}

Redox FT Dongle Edition (ZMK)

This repository contains ZMK firmware for the FalbaTech Redox FT with USB dongle support.

Configuration
	•	Left half: BLE Peripheral
	•	Right half: BLE Peripheral
	•	Dongle: BLE Central + USB HID

The dongle connects to both keyboard halves over Bluetooth and sends key events to the computer through USB.

Hardware

Keyboard halves
	•	nice!nano v2 compatible controllers
	•	ZMK firmware
	•	Bluetooth split communication

Dongle
	•	nice!nano v2
	•	USB connection to computer
	•	Acts as BLE central device

First Flashing

IMPORTANT:

Before flashing firmware for the first time:
	1.	Flash settings_reset.uf2
	2.	Flash final firmware
	3.	Repeat for:
	•	left half
	•	right half
	•	dongle

This avoids old BLE pairing issues.

Build Targets

This repository builds:
	•	Redox FT Left
	•	Redox FT Right
	•	Redox FT Dongle

Pairing

After flashing:
	1.	Turn on both halves
	2.	Connect dongle through USB
	3.	Wait a few seconds
	4.	The halves should automatically connect to the dongle

Notes
	•	Dongle firmware does not contain a keyboard matrix
	•	Dongle acts only as USB/BLE bridge
	•	ZMK Studio support depends on current firmware configuration

Based on
	•	ZMK Firmware
	•	nice!nano v2
	•	FalbaTech Redox FT
:::
