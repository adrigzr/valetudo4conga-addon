# Changelog

## 0.2.1

- Update base image to [Valetudo 2021.09.1](https://github.com/Hypfer/Valetudo/releases/tag/2021.09.1)

## 0.2.0

- BREAKING CHANGE: Valetudo configuration has been changed.
  You will need to setup again the `robot.implementation` in your `/config/valetudo.json` and restore your settings from `/config/valetudo.json.backup`.
  If your device shows up with different id, check the config in `mqtt.identity`.
- Update base image to [Valetudo 2021.09.0](https://github.com/Hypfer/Valetudo/releases/tag/2021.09.0)

## 0.1.8

- Update base image to [Valetudo 2021.08.1](https://github.com/Hypfer/Valetudo/releases/tag/2021.08.1)

## 0.1.7

- Update base image to [Valetudo 2021.08.0](https://github.com/Hypfer/Valetudo/releases/tag/2021.08.0)
- Fix battery min value

## 0.1.6

- Update base image to [Valetudo 2021.07.1](https://github.com/Hypfer/Valetudo/releases/tag/2021.07.1)

## 0.1.5

- Update base image to [Valetudo 2021.07.0](https://github.com/Hypfer/Valetudo/releases/tag/2021.07.0)
- Restore zones button in the UI
- Add PendingMapChangeHandlingCapability

## 0.1.4

- Due to a new Valetudo configuration validator tool, Fix ports in config file
- Swagger enabled

## 0.1.3

- Update base image to [Valetudo 2021.06.0](https://github.com/Hypfer/Valetudo/releases/tag/2021.06.0)

## 0.1.2

- Add `debug` configuration option

## 0.1.1

- Add auto configurator

## 0.1.0

- Initial release
