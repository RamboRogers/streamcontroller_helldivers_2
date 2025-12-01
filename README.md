# HELLDIVERS 2 StreamController Plugin

A StreamDeck plugin for Helldivers 2 that allows you to execute stratagems directly from your StreamDeck.

## Requirements

This plugin expects the following game configuration:
* **Stratagem Menu**: Home key set to tap/press to open the stratagem menu and select
* **Arrow Keys**: Up, Down, Left, Right mapped to stratagem directional inputs

## Usage

Press any stratagem button on your StreamDeck, and the plugin will:
1. Send a HOME key press to open the stratagem menu
2. Send the appropriate arrow key sequence for the selected stratagem
3. Menu automatically closes after sequence completes

## Supported Stratagems

The plugin supports **79 stratagems** including all primary weapons, equipment, sentries, orbital support, and stratagem perks. Each stratagem is represented by an icon and can be executed with a single StreamDeck button press.

### Weapons & Equipment (13 stratagems)
- Jump Pack, Supply Pack, Ballistic Shield, Guard Dog, Guard Dog Rover, Guard Dog K-9, Guard Dog Dog Breath, Directional Shield Backpack, Ballistic Shield Backpack, Shield Pack, Machine Gun, Anti-Material Rifle, Stalwart

### Heavy Weapons (11 stratagems)
- Expendable Anti-Tank, Recoilless Rifle, Flamethrower, Autocannon, Heavy Machine Gun, Railgun, SPEAR Launcher, Grenade Launcher, Laser Cannon, Arc Thrower, Quasar Cannon

### Airstrikes & Artillery (19 stratagems)
- Airburst Rocket Launcher, Orbital Gatling Barrage, Orbital Airburst Strike, Orbital 120MM HE Barrage, Orbital 380MM HE Barrage, Orbital Walking Barrage, Orbital Laser, Orbital Railcannon Strike, Orbital Precision Strike, Orbital Gas Strike, Orbital EMS Strike, Orbital Smoke Strike, Orbital Napalm Barrage, Eagle Strafing Run, Eagle Airstrike, Eagle Cluster Bomb, Eagle Napalm Airstrike, Eagle Smoke Strike, Eagle 110MM Rocket Pods, Eagle 500kg Bomb

### Vehicles & Exosuits (3 stratagems)
- Patriot Exosuit, Emancipator Exosuit, Fast Recon Vehicle

### Fortifications (7 stratagems)
- HMG Emplacement, Shield Generator, Tesla Tower, Anti-Personnel Minefield, Incendiary Mines, Machine Gun Sentry, Gatling Sentry

### Sentries & Automated Defense (8 stratagems)
- Mortar Sentry, Autocannon Sentry, Rocket Sentry, EMS Mortar Sentry, Grenadier Battlement, Shield Generator Relay, Anti-Tank Mines

### Support & Utilities (13 stratagems)
- Reinforce, SOS Beacon, Resupply, Hellbomb, SSD Delivery, Prospecting Drill, Hive Breaker Drill, Seismic Probe, Upload Data, Eagle Rearm, Illumination Flare, SEAF Artillery, Super Earth Flag

### New Additions (13 stratagems)
- B-100 Portable Hellbomb, LIFT-860 Hover Pack, CQC-1 One True Flag, AX/ARC-3 Guard Dog K-9, AX/TX-13 Guard Dog Dog Breath, SH-51 Directional Shield Backpack, SH-20 Ballistic Shield Backpack, MLS-4X Commando, StA-X3 W.A.S.P. Launcher, M-102 Fast Recon Vehicle, FX-12 Shield Generator Relay, E/GL-21 Grenadier Battlement, MD-17 Anti-Tank Mines

## Contributing
### Adding a new Stratagem
* Add a new key to `assets/data/stratagems.json` with the key combination.
* Add icon with matching keyname.png to `assets/icons`.
* Add matching `actions.keyname.name` to `locales` files.
* Add matching `actions.keyname.labels.*` to `locales` files.

## Credits

This plugin is a fork and enhancement of the original [streamcontroller_helldivers_2](https://github.com/jslay88/streamcontroller_helldivers_2) by [@jslay88](https://github.com/jslay88). Thank you for the foundation!

---

<div align="center">

## ⚖️ License

<p>
This project is licensed under the GNU General Public License v3.0 (GPLv3).<br>
<em>Free Software</em>
</p>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

### Connect With Me 🤝

[![GitHub](https://img.shields.io/badge/GitHub-RamboRogers-181717?style=for-the-badge&logo=github)](https://github.com/RamboRogers)
[![Twitter](https://img.shields.io/badge/Twitter-@matthewrogers-1DA1F2?style=for-the-badge&logo=twitter)](https://x.com/matthewrogers)
[![Website](https://img.shields.io/badge/Web-matthewrogers.org-00ADD8?style=for-the-badge&logo=google-chrome)](https://matthewrogers.org)

![RamboRogers](https://github.com/RamboRogers/cyberpamnow/raw/master/media/ramborogers.png)

</div>
