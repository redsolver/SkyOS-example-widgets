# SkyOS example widgets

This repository contains some example widgets for SkyOS.

## How to deploy

1. Install SkyDeploy (https://github.com/redsolver/skydeploy)
2. Run `skydeploy web` in your terminal
3. Add the "directy access link" (shown last) to your Skynet Homescreen: https://homescreen.hns.siasky.net/#/
4. Refresh SkyOS and try to add one of the widgets

Important: you should update the `skylink` field in the `manifest.json` file after deploying for the first time and getting the `TXT record skylink`. Then deploy again.

## Widgets

### Simple battery widget

A simple widget that shows the current battery level with text and a visual indicator.

### Crypto price widget

A more complex widget which has adjustable width, can be configured to show a specific cryptocurrency and launches a SkyOS window when clicked.
