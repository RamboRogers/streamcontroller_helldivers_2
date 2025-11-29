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

![RamboRogers](media/ramborogers.png)

</div>
