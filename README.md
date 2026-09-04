# Amazon Device Support Matrix

A high-performance hardware database and interactive dashboard for Amazon Fire OS and Vega OS devices — Fire TV streaming sticks/cubes, Fire tablets, Fire TV Edition smart TVs, and Echo Show smart displays. Designed specifically for Unity developers to manage memory budgets and prevent OOM (Out of Memory) crashes.

66 devices tracked, cross-referenced against Amazon's official [developer.amazon.com device-specs](https://developer.amazon.com/docs/device-specs/) pages where available (devices without an official spec page are flagged `†` on the site and sourced from teardown/community data instead).

Live Dashboard

### Access the interactive matrix here: 👉 https://sinlessdevil.github.io/Amazon-Device-Support-Matrix/

---

Tier Available RAM Strategy
- Ultra > 2.0 GB High-res textures (2K), complex shaders, no limitations.
- High 1.5 - 2.0 GB Stable performance, standard 1K textures.
- Mid 0.85 - 1.5 GB Balanced tier, use ASTC compression, monitor draw calls.
- Low < 850 MB Legacy/entry-level hardware. Aggressive asset streaming and texture downscaling required.

**Note on "available RAM":** Amazon only publishes total RAM per device, not an app-available figure. The site models free RAM as total RAM × a per-OS-generation overhead ratio (documented in `index.html`) — treat it as a directional estimate, not a measured value. Likewise, the "Priority" column is a qualitative signal (device age, generation continuity, price tier), not an Amazon sales figure — Amazon does not disclose per-model unit sales.

<img width="2132" height="1261" alt="image" src="https://github.com/user-attachments/assets/54b2c43a-1b21-43f3-925c-99c9ce96e066" />
