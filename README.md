make a basic md github pages website for the houston meshtastic/meshcore community
12:57 PM
Read frontend design skill

Since this is a GitHub Pages site using Markdown, I'll create a clean index.md with appropriate Jekyll front matter, plus a _config.yml for the site configuration. GitHub Pages natively renders Markdown with Jekyll themes.
Created 3 files, read a file
Done

Here's your Houston Mesh Community GitHub Pages site — three files to drop into a repo:

Files:

    index.md — Main landing page with sections for what mesh networking is, Houston-specific context (Harvey prep angle), hardware/firmware guides, channels, and community links
    _config.yml — Jekyll config using the midnight dark theme (fits the radio/tech vibe well)
    placement.md — A bonus node placement tips page tailored to Houston's flat terrain and brutal heat/humidity

To publish:

    Create a new GitHub repo (e.g., houston-mesh)
    Drop these files in the root
    Go to Settings → Pages → Source: main branch / root
    GitHub will build and publish it automatically at https://yourusername.github.io/houston-mesh

Things to fill in before going live:

    Discord/Telegram invite links in the community table
    Your GitHub repo URL in the "Contributing" section
    A contact email if desired
    Optionally a custom domain

Want me to add more pages (FAQ, node map embed, event calendar, etc.) or swap to a different Jekyll theme?
Index
Document · MD 
config
YML 
Placement
Document · MD 


Claude is AI and can make mistakes. Please double-check responses.
Index · MD
# 📡 Houston Mesh Community
 
**Off-grid, encrypted, community-owned mesh networking — no internet, no cell signal required.**
 
We're a Houston-area group of radio enthusiasts, preppers, hackers, and everyday folks building a resilient peer-to-peer communication network using [Meshtastic](https://meshtastic.org) and [MeshCore](https://meshcore.co.uk) hardware.
 
---
 
## 🗺️ What Is Mesh Networking?
 
Mesh networking lets LoRa-equipped devices communicate directly with each other — and relay messages hop-by-hop — without any cellular towers, Wi-Fi, or internet infrastructure. Great for:
 
- Emergencies and natural disasters
- Hiking, camping, and outdoor adventures
- Events and festivals
- Building community-owned comms infrastructure
 
---
 
## 📻 Frequencies & Channels
 
We operate on the standard **US 915 MHz** LoRa band.
 
| Channel Preset | Use Case |
|---|---|
| `LongFast` | Default — best range, moderate throughput |
| `MediumSlow` | Balanced range/speed for urban areas |
| `ShortTurbo` | Short range, fast — events / high density |
 
> **Default channel name:** `HoustonMesh`
> **PSK:** Ask in Discord or the Telegram group for the shared key.
 
---
 
## 🛰️ The Houston Network
 
Our nodes are spread across the greater Houston metro — from The Woodlands to Sugar Land, Katy to Baytown.
 
**Want to add your node to the map?**
- Flash your device with the latest Meshtastic or MeshCore firmware
- Set your region to `US`
- Join the `HoustonMesh` channel
- Share your node ID in our community chat
 
📍 [View live node map on Meshtastic.org](https://meshtastic.org/map)
 
---
 
## 🔧 Getting Started
 
### Hardware
 
Popular devices used in our community:
 
- **LILYGO T-Beam** — GPS + LoRa, great all-rounder
- **Heltec V3** — Compact, affordable, USB-C
- **RAK WisBlock** — Modular, excellent for fixed nodes
- **Seeed SenseCAP Card Tracker** — Sleek form factor, plug-and-play
 
Most devices run **~$25–$60** and are available on Amazon, AliExpress, or direct from manufacturers.
 
### Firmware
 
- [Meshtastic Firmware](https://meshtastic.org/docs/getting-started/) — Large community, feature-rich, phone app support
- [MeshCore Firmware](https://meshcore.co.uk) — Lightweight, efficient, good for fixed infrastructure nodes
 
### Flash & Configure
 
1. Download the [Meshtastic Web Flasher](https://flasher.meshtastic.org) or use the CLI
2. Flash your device
3. Open the Meshtastic app (iOS / Android) or web client
4. Set **Region:** `US`, **Modem Preset:** `LongFast`
5. Add the `HoustonMesh` channel
6. You're on the mesh! 🎉
 
---
 
## 🌩️ Why This Matters in Houston
 
Houston knows hurricanes. When **Harvey** hit in 2017, cell networks were overwhelmed and many areas lost service for days. A community mesh network provides:
 
- **Neighborhood-level comms** when cell towers are down
- **No subscription or monthly fee** — ever
- **Encrypted messages** between nodes
- **GPS position sharing** for SAR and check-ins
 
We encourage everyone to keep a charged mesh device ready alongside other emergency supplies.
 
---
 
## 👥 Join the Community
 
| Platform | Link |
|---|---|
| 💬 Discord | *(Add your invite link)* |
| 📱 Telegram | *(Add your group link)* |
| 🗺️ Forum | *(Add forum/subreddit link)* |
| 📧 Email | *(Add contact email)* |
 
We hold occasional **in-person meetups** across Houston to help new members get set up, share hardware tips, and plan node placement. Watch the Discord for announcements.
 
---
 
## 🤝 Contributing
 
This is a volunteer, community-run project. Ways to help:
 
- **Host a node** — A solar-powered or plugged-in node at your home dramatically extends coverage
- **Donate hardware** — Help get devices into the hands of neighbors who need them
- **Document** — Write guides, tutorials, and node placement tips
- **Spread the word** — Tell your neighbors, your HAM club, your emergency prep group

 
---
 
## 📜 License & Legal
 
Meshtastic and MeshCore devices in the US operate under **FCC Part 15** rules on the 915 MHz ISM band — no license required.
 
If you're a licensed amateur radio operator, operating under your HAM license may allow higher transmit power. Check with your local club.
 
---
 
*Houston Mesh Community — built by neighbors, for neighbors.* 📡
 

