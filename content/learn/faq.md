---
title: "FAQ"
description: "Frequently asked questions about HoustonMesh and Meshtastic"
---

## Getting Started

**Do I need a ham radio license?**
No. Meshtastic operates on the 915 MHz ISM band, which is unlicensed in the United States. Anyone can use it without any license or registration.

---

**How much does it cost to get started?**
A basic Meshtastic device costs $20–$50. Popular options like the Heltec V3 (~$20) or LILYGO T-Beam (~$45) are available on Amazon. There are no subscriptions, no fees, and no ongoing costs.

---

**What phone/app do I need?**
The official Meshtastic app is free on [Android](https://play.google.com/store/apps/details?id=com.geeksville.mesh) and [iOS](https://apps.apple.com/app/meshtastic/id1586432531). Your phone connects to the Meshtastic device via Bluetooth — no internet needed for the mesh itself.

---

**Does it work without my phone?**
Yes. Your Meshtastic node will relay messages from other nodes even when your phone is disconnected. You only need the phone to send/receive your own messages.

---

## The Network

**How far can messages travel?**
Range depends on terrain, elevation, and obstacles. Node to node, expect 1–15 miles depending on placement. With good elevation and clear line-of-sight, some nodes reach 20+ miles. Messages hop between nodes, so the total network reach is much larger than any single link.

---

**Can I send messages to someone not on the mesh?**
No — Meshtastic is a closed mesh. You can only communicate with other Meshtastic users on the same network. It's not connected to SMS, email, or the internet unless someone builds a special gateway node.

---

**Are messages encrypted?**
Yes. All Meshtastic messages are encrypted by default using AES-256. Public channel messages are encrypted with a shared channel key. Direct messages use additional encryption.

---

**Can I be tracked through the mesh?**
Only if you enable GPS/location sharing, which is optional. You can turn off location broadcasting in the app at any time.

---

## HoustonMesh Specific

**What channel/frequency should I use?**
Use the default Meshtastic channel (LongFast preset, 915 MHz) and ask in our Discord for the current HoustonMesh channel name and key to get on the local community channel.

---

**Where are the repeater nodes?**
Check our [Network Map](/nodes/) for current repeater locations. The Inner Loop has the most coverage. We're actively expanding south and west.

---

**How do I know if my node is connected?**
Open the Meshtastic app → Nodes tab. You should see at least one other node if you're in range of a repeater or another user. If you see nothing, check that your region is set to US and try a location with better line-of-sight to the sky.

---

**Can I host a repeater?**
Absolutely — that's how we grow. A solar-powered repeater can be built for $60–$100 and mounted on a rooftop or fence. Ask in our [Discord](https://discord.gg/3WB4zEDjre) for help planning your install.

---

**I have a question not answered here.**
Join the [HoustonMesh Discord](https://discord.gg/3WB4zEDjre) — the community is friendly and happy to help.
