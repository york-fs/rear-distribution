# Rear Distribution Board

![Revision](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Frear-distribution%2Finfo.json&query=%24.revision&label=Revision)
![Pad Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Frear-distribution%2Finfo.json&query=%24.pad_count&label=Pad%20Count)
![Via Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Frear-distribution%2Finfo.json&query=%24.via_count&label=Via%20Count)
![ERC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Frear-distribution%2Ferc.json)
![DRC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Frear-distribution%2Fdrc.json)

The rear distribution board is the central board of the LVS. It provides fusing for all other LVS components and
interfaces with the front, TSAC, and TS box distribution boards, as well as the inverter via AMPSEAL connections.

[Latest Release](https://github.com/york-fs/rear-distribution/releases/latest)
[Interactive BOM](https://york-fs.github.io/rear-distribution/ibom.html)

## Features

* **Blade Fuse Holders for All Other LVS components**
* **Fused 12 V and Shutdown Monitoring**
* **On-board microSD Slot**
* **UART Output for Radio Communication**

![Render Preview](https://york-fs.github.io/rear-distribution/render.jpg)

## Cloning

A recursive clone must be used to download the `kicad-library` repository:

    git clone --recursive https://github.com/york-fs/rear-distribution.git
