# My QMK/VIA/VIAL Keyboard Configurations
## Introduction
Welcome to my personal repository for keyboard configurations! This space serves as a centralized backup and documentation hub for the keymaps and settings I use across my various mechanical keyboards. As keyboards evolve and firmware gets updated, having a reliable place to store and track these configurations is essential.

The primary goal is to maintain a consistent and optimized typing experience across different hardware, leveraging the power of QMK firmware and its user-friendly configurators like VIA and VIAL.

## Repository Structure
This repository is organized by keyboard model. Each keyboard has its own dedicated directory containing the specific configuration files relevant to it.
```
├── keychron_k10_pro/
│   ├── k10_pro_definition.json     # K10 Pro VIA definition file
│   └── k10_pro_keymap.json         # Exported layout/keymap configuration from VIA/Keychron Launcher
│
├── keychron_v5_max/
│   ├── v5_max_definition.json      # K10 Pro VIA definition file
│   └── layout.json                 # Exported layout/keymap configuration from VIA/Keychron Launcher
│
├── akko_5075s_vial/
│   ├── 5075s_via_definition.json   # K10 Pro VIA definition file
│   └── layout.json                 # Exported layout/keymap configuration from VIAL
│
├── nuphy_air60_v2/
│   ├── air60v2_definition.json     # K10 Pro VIA definition file
│   └── layout.json                 # Exported layout/keymap configuration from VIA
│
├── macros.md                       # My macros as key-commands
└── README.md                       # This file
```

## My Keyboards and Configurations

Here's a summary of the keyboards I use and links to their configuration files:

| Keyboard | Layout | Configuration Software | Layout Config File | Definition JSON Source (Official Link) | Notes |
| :---------------------- | :------- | :---------------------------- | :----------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------- |
| Keychron V5 MAX | ANSI (Enc) | Keychron Launcher (VIA-based) | [`keychron_v5_max/layout.json`](keychron_v5_max/layout.json) | | Requires loading Definition JSON in VIA/Launcher Design Tab first. |
| Keychron K10 PRO | ISO-DE | Keychron Launcher (VIA-based) | [`keychron_k10_pro/layout.json`](keychron_k10_pro/layout.json) |  | Requires loading Definition JSON in VIA/Launcher Design Tab first. |
| AKKO 5075S | ANSI | VIAL |  | Not Required | VIAL firmware includes the definition; software should auto-detect. |
| Nuphy Air 60 v2 | ANSI | VIA | [`nuphy_air60_v2/layout.json`](nuphy_air60_v2/layout.json) |  | Requires loading Definition JSON in VIA Design Tab first.[1] |


## Disclaimer

These configurations are personalized for my workflow. Feel free to browse, fork, or adapt
