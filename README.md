# SBK BarMeter PCBs

Documentation and mechanical resources for the **SBK BarMeter** LED bargraph boards and their companion **SBK BarDrive** driver backpacks.

These boards support modular indicators for DIY electronics, animated props, dashboards, meters, and other projects.

## Current boards

| Product | Purpose | Connection / variant |
| --- | --- | --- |
| [SBK BarMeter Sx28](SBK%20BarMeter%20Sx28/) | 28-segment LED display PCBs | SA28 common-anode and SK28 common-cathode versions |
| [SBK BarDriveHT 28](SBK%20BarDriveHT%2028/) | Driver backpack for BarMeter SA28/SK28 | HT16K33A-based I²C interface |
| [SBK BarDriveMAX 28](SBK%20BarDriveMAX%2028/) | Driver backpack for BarMeter SA28/SK28 | MAX7219/MAX7221-based serial interface with chaining connections |

![BarMeter SK28 with a BarDriveHT 28 backpack](SBK%20BarMeter%20Sx28/Images/assembled-with-bardriveht-display-side.jpg)

*Example display and driver assembly. See each product README for compatibility, wiring, photos, and available files.*

## Repository layout

Each current product folder contains:

- **README.md** — product overview, connections or assembly guidance, and file links.
- **docs/** — specification drawings and manufacturer datasheets.
- **models/** — STEP models and, where available, STL assemblies.
- **Images/** — photographs and renders.
- **videos/** — preview video where available (BarDriveMAX 28).

Earlier revisions are preserved in their existing layout under [Deprecated](Deprecated/). Check revision-specific wiring and dimensions when working with an older board.

The repository provides PDF documentation and mechanical models. Native PCB design files, Gerber fabrication files, and firmware examples are not currently included.

## Availability and support

SBK BarMeter and BarDrive boards are available on demand, per unit or in small batches, either individually or as compatible **BarMeter + BarDrive bundles**. For availability, pricing, bare-board or assembled options, or custom quantities, please contact:

**[SmartBuildsKits@gmail.com](mailto:SmartBuildsKits@gmail.com)**

Boards are intended for hobbyists, educators, prototypes, and small-scale projects. Availability depends on component stock and production capacity.

## License

Schematic diagrams and mechanical board outlines shared in this repository are licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

You may copy and adapt these materials for non-commercial purposes with appropriate attribution. See [LICENSE](LICENSE) for the terms and link to the full license. Included manufacturer datasheets remain subject to their publishers' terms.
