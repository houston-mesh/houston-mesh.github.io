---
title: "Learn"
description: "Understanding Meshtastic, MeshCore, and LoRa mesh networking"
---

New to mesh networking? Start here.

---

## Mesh Networking ELI5

Imagine you're in a classroom and want to pass a note to someone across the room. You can't throw it that far — but you can hand it to the person next to you, who passes it to the next person, and so on until it arrives.

Now imagine every person in that classroom makes a copy before passing it along. Even if some people are absent, the note still gets through via other routes. And if you want the note to be private, you write it in a secret code that only you and the recipient know.

**That's Meshtastic.** Except instead of paper notes, it's short radio packets. Instead of a classroom, it's Houston. And instead of people, it's little LoRa radio devices.

---

## What Is LoRa?

**LoRa** (Long Range) is a radio modulation technique designed for sending small amounts of data very far on very little power. A Meshtastic node can send a message **several miles** on a single charge.

In the US, Meshtastic uses the **915 MHz ISM band** — an unlicensed spectrum band, meaning **you don't need a ham radio license** to use it.

The tradeoff: LoRa is slow. It's not built for streaming or large files. It's built for short text messages, GPS coordinates, and sensor readings — exactly what you need in an emergency or off-grid scenario.

---

## What Is Meshtastic?

[Meshtastic](https://meshtastic.org) is open-source firmware for LoRa radio hardware. It turns a cheap radio module into a mesh network node that:

- Sends and receives encrypted text messages
- Shares GPS location with contacts
- Automatically relays messages from other nodes (it's a repeater by default)
- Pairs with your phone via Bluetooth for a simple app interface

It's community-built, constantly improving, and completely free.

---

## What Is MeshCore?

[MeshCore](https://meshcore.co.uk) is a newer alternative firmware/platform that takes a different approach to routing and infrastructure. Where Meshtastic uses a flooding protocol (everyone rebroadcasts everything), MeshCore uses more targeted routing to reduce channel congestion.

MeshCore is particularly interesting for **dedicated repeater infrastructure**. HoustonMesh runs MeshCore on some of our backbone repeaters to explore the tradeoffs.

Both platforms can coexist on the same radio frequency — they just can't talk directly to each other.

---

## Meshtastic vs. MeshCore — Which Should I Start With?

**Start with Meshtastic** if:
- You're new to mesh networking
- You want the largest community and most device support
- You want the easiest phone app experience

**Look into MeshCore** if:
- You're comfortable with more technical setup
- You want to run infrastructure/repeater nodes
- You're interested in different routing approaches

---

## Helpful Links

- [Meshtastic Docs](https://meshtastic.org/docs/)
- [MeshCore Docs](https://meshcore.co.uk/docs)
- [Meshtastic Flasher](https://flasher.meshtastic.org)
- [Meshtastic Discord](https://discord.com/invite/ktMAKGBnBs)
- [HoustonMesh Discord](#) *(link coming soon)*
