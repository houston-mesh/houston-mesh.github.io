---
title: "Get on the Mesh"
description: "How to join HoustonMesh with a Meshtastic device"
---

Getting on HoustonMesh is easier than you think. You need one thing: a **Meshtastic-compatible device**. No license, no subscription, no account.

---

## Step 1 — Get a Device

Any Meshtastic-supported LoRa device will work. Popular choices:

| Device | Price | Best For |
|--------|-------|----------|
| [Heltec V3](https://heltec.org/project/wifi-lora-32-v3/) | ~$20 | Budget starter, has screen |
| [RAK WisBlock 19003](https://store.rakwireless.com) | ~$35 | Modular, great battery life |
| [LILYGO T-Beam Supreme](https://www.lilygo.cc) | ~$45 | Built-in GPS, popular all-rounder |
| [LILYGO T-Echo](https://www.lilygo.cc) | ~$50 | E-ink display, ultra low power |

All of these are available on Amazon, AliExpress, or directly from the manufacturers. Look for devices with **915 MHz** (US frequency band).

---

## Step 2 — Flash Meshtastic

Most devices come with generic firmware. You'll need to flash Meshtastic:

1. Go to [flasher.meshtastic.org](https://flasher.meshtastic.org) in Chrome or Edge
2. Plug in your device via USB
3. Select your device model and click **Flash**

That's it. No command line required.

---

## Step 3 — Configure Your Node

Install the **Meshtastic app** ([Android](https://play.google.com/store/apps/details?id=com.geeksville.mesh) / [iOS](https://apps.apple.com/app/meshtastic/id1586432531)) and pair via Bluetooth:

- Set your **region to US** (915 MHz)
- Set a **node name** so others can identify you
- Set **LoRa channel** to the HoustonMesh community channel *(details in our Discord)*

---

## Step 4 — You're On the Mesh

Once configured, your device will automatically discover nearby nodes and join the mesh. Open the app and say hello in the channel — someone will likely respond.

Check our [Network Map](/nodes/) to see where existing nodes and repeaters are located in Houston.

---

## Want to Put Up a Repeater?

Repeater nodes extend coverage for everyone. A basic solar repeater can be built for **$60–$100** and mounted on a rooftop, fence post, or tree. No special skills needed — just a good line of sight.

Ask in our Discord if you want help planning a repeater install.
