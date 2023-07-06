# SunWEG

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

[![Black][black-shield]][black]

[![hacs][hacsbadge]][hacs]
[![Project Maintenance][maintenance-shield]][user_profile]


**This component will set up the following platforms.**

| Platform        | Description                |
| --------------- | -------------------------- |
| `sensor`        | Show info from SunWEG API. |

## Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
2. If you do not have a `custom_components` directory (folder) there, you need to create it.
3. In the `custom_components` directory (folder) create a new folder called `sunweg`.
4. Download _all_ the files from the `custom_components/sunweg/` directory (folder) in this repository.
5. Place the files you downloaded in the new directory (folder) you created.
6. Restart Home Assistant
7. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "SunWEG"


## Configuration is done in the UI

1. Type your SunWEG.net username and password.
2. If you have multiple plants, select the one you want to add.

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

## Credits

Code template was mainly taken from [@Ludeeus](https://github.com/ludeeus)'s [integration_blueprint][integration_blueprint] template

---

[integration_blueprint]: https://github.com/custom-components/integration_blueprint
[black]: https://github.com/psf/black
[black-shield]: https://img.shields.io/badge/code%20style-black-000000.svg?style=for-the-badge
[commits-shield]: https://img.shields.io/github/commit-activity/y/rokam/hass-sunweg.svg?style=for-the-badge
[commits]: https://github.com/rokam/hass-sunweg/commits/main
[hacs]: https://hacs.xyz
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/rokam/hass-sunweg.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-%40rokam-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/rokam/hass-sunweg.svg?style=for-the-badge
[releases]: https://github.com/rokam/hass-sunweg/releases
[user_profile]: https://github.com/rokam
