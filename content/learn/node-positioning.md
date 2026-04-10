---
title: "How to Position a Meshtastic Node for Maximum Range"
description: "Learn where to place your Meshtastic node for the best range and coverage. Covers elevation, line of sight, antenna orientation, indoor vs outdoor mounting, and Houston-specific tips."
keywords: ["Meshtastic node placement", "LoRa antenna positioning", "Meshtastic range tips", "how to improve Meshtastic range", "LoRa line of sight"]
date: 2026-01-15
---

The single biggest factor in how well your node performs isn't the hardware — it's **where you put it**. LoRa radio travels in straight lines. Anything between your node and another node reduces range. Getting elevation and clear line-of-sight is everything.

---

## The Golden Rule: Height Wins

Radio signals don't bend around buildings, hills, or trees. Every meter of elevation you gain dramatically extends your range. A node sitting on a windowsill might reach a few blocks. The same node on a rooftop might reach 5–15 miles.

**Practical examples:**
- Ground floor indoors → 0.5–1 mile typical
- Second story window → 1–3 miles
- Rooftop with clear sky → 5–15+ miles
- Elevated water tower or antenna mast → 20+ miles (with good conditions)

---

## Line of Sight (LOS)

**Line of sight** means an unobstructed straight line between two nodes. In Houston's flat terrain, the main obstacles are:

- **Buildings** — especially dense Midtown/Downtown corridors
- **Trees** — wet leaves absorb RF, dry trees less so
- **Your own house** — a node inside loses a lot of signal through walls and roofing

Even if you can't get perfect LOS, **near-LOS** (a clear view of the sky even if not directly at the other node) is much better than being surrounded by walls.

---

## Antenna Orientation

Meshtastic devices ship with small whip antennas. These antennas radiate signal outward in a donut pattern — strongest horizontally, weakest directly above/below.

**Tips:**
- Mount the node so the antenna points **straight up** for best horizontal coverage
- Avoid laying the device on its side — you'll aim signal up and down instead of outward
- Aftermarket antennas (longer, higher-gain) can significantly improve range — look for 915 MHz LoRa antennas

---

## Indoor vs. Outdoor Mounting

| Location | Range | Notes |
|----------|-------|-------|
| Indoor, ground floor | Low | Walls absorb 10–20 dB of signal |
| Indoor, upper floor, near window | Medium | Better, aim antenna at window |
| Outdoor, ground level | Medium | Good if open field, poor in urban areas |
| Outdoor, rooftop | High | Best for most situations |
| Outdoor, elevated structure | Very High | Ideal for repeater nodes |

For **personal/carry nodes** on your body, don't worry too much — you're mobile and will connect to the mesh as you move near nodes. For **fixed home or repeater nodes**, spend time thinking about placement.

---

## Checking Your Coverage

After you place a node:

1. Open the Meshtastic app and check **Neighbor Info** — you'll see which nearby nodes your node can hear
2. Walk around your neighborhood with a second device and watch the signal quality
3. Post in the HoustonMesh Discord — members can tell you which repeaters are closest to you

---

## Houston-Specific Tips

Houston is flat — that's good news for LoRa. The main challenges are:

- **Tree canopy** in residential neighborhoods (Heights, Montrose, Midtown) absorbs signal, especially after rain
- **Building density** downtown and in dense corridors blocks LOS
- **Distance to repeaters** — check our [Network Map](/nodes/) to see where the nearest backbone node is and aim your antenna roughly toward it

If you're on the second floor or higher with a south/southwest-facing window toward a repeater, you may be surprised how well an indoor node performs.
