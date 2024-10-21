# wazo-calld-new-line-status-plugin

Fix line status after creation.

## Installation

```sh
wazo-plugind-cli -c "install git https://github.com/wazo-communication/wazo-calld-new-line-status-plugin"
```

Installing this plugin will restart `wazo-calld`, impacting call processing.

After installing this plugin, line status will be correctly updated after the line is created.

This plugin is only useful for Wazo servers 24.10.

## Uninstallation

```sh
wazo-plugind-cli -c "uninstall wazocommunication/wazo-calld-new-line-status"
```
