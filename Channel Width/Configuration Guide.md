== Configuration Guide ==

⚓ Small Channel Width = Small Bandwidth
Examples:
- 80 MHz can support up to approximately ±866 Mbps (at 802.11ac).
- 40 MHz drops to about ±400 Mbps.
- 20 MHz drops further to around ±200 Mbps (depending on MIMO & modulation).

⚓ Small Channel Width Reduces Interference
- Smaller channels are less likely to conflict with other access points.
- This is especially useful in environments with many access points (universities, apartments, malls).
- Although speed decreases due to smaller channel width, stability and signal quality improve, making it suitable for devices that require a stable connection (IoT devices, light browsing).

⚖️ When to Reduce Channel Width?

High interference (neighboring APs) -> 20 MHz or 40 MHz
Dense device environment -> 20 MHz
Need high throughput (file sharing, 4K video, etc.)	-> 80 MHz
Outdoor use or long range	-> 20 MHz (more stable and resistant to interference)

📌 Tips on UniFi Controller:
- Don't auto for channel width. Select manual 20/40/80 MHz depending on need.
- Use 20 MHz in the 2.4 GHz band (always recommended because it is crowded).
- Use 40 or 80 MHz at 5 GHz if interference is low and requires high throughput.
