# 10-Pin Phoenix Audio Adapter

A 10-pin Phoenix audio adapter designed for Extron CrossPoint matrix switchers.

## Why a 10-Pin Connector?

Conventional Phoenix audio adapters typically use 5-pin connectors intended for individual 5-pin receptacles. Extron CrossPoint units instead use 10-pin female Phoenix receptacles for their audio connections.

Extron's original 5-pin connectors were custom, slimmer parts designed to fit side by side in a 10-pin receptacle. Standard replacement 5-pin connectors are wider and often have to be trimmed or sanded to fit correctly.

This design uses a single 10-pin connector, so the connector sides do not need to be trimmed or sanded.

## Features

- Single 10-pin connector matching the receptacle format used by Extron CrossPoint units
- No trimming or sanding required
- Avoids the fit problems associated with two conventional 5-pin connectors
- Configurable for input or output use with solder jumpers
- Intended as a practical replacement for difficult-to-source Extron-style slim connectors

## Input and Output Configuration

The adapter includes a GND solder pad beside the negative-terminal pads.

- **Input use:** Bridge the GND pad to both negative terminals with solder.
- **Output use:** Leave both bridges open so the output negative terminals are not connected to ground.

> **Important:** Do not use the input configuration on an output. Shorting the negative terminals of a balanced output to ground may cause improper operation or damage, depending on the output circuit.

<img width="700" alt="Close-up rendering of the GND solder-jumper pad and adjacent negative-terminal pads" src="images/input-output-solder-jumper.png" />

*The GND pad can be bridged to the adjacent negative-terminal pads to configure the adapter for input use.*

## Project Status

> **Important:** The design and fabrication files provided in this repository have not been physically tested. Verify the dimensions, pinout, jumper configuration, and electrical connections before ordering boards, assembling the adapter, or connecting it to equipment.

## License

Unless otherwise stated, the hardware design, fabrication files, and documentation in this repository are licensed under the [CERN Open Hardware Licence Version 2 – Permissive](LICENSE) (`CERN-OHL-P-2.0`).

This permits use, modification, distribution, and manufacture—including commercial use—subject to the licence's notice requirements. The design is provided without warranty.

Copyright © 2026 ihategravel2.
