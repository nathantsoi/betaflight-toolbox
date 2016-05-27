# Betaflight Configurator

Ok... this needs a new name "Configurator" isn't even a word. I propose the name "Betaflight ToolBox."

## Development setup

Go to [chrome://extensions/](chrome://extensions/) and check the box for `Developer mode`.

Choose `Load unpacked extension...` and pick the folder to which you cloned this repo.

Click `Launch` under the app name.

Protips:

  - Keep the [chrome://extensions/](chrome://extensions/) window open and after a change hit `CTRL-R` in this window to reload the app.

  - In [js/gui.js#L6](js/gui.js#L6), set `this.dev_mode = !('update_url' in chrome.runtime.getManifest());` to show all the tabs and content when the extension is loaded unpacked, even when disconnected from a flight controller

## Authors

Betaflight Configurator was originally a [fork](#credits) of the CleanFlight Configurator which was a BaseFlight configurator fork with support for Betaflight instead of Baseflight.
