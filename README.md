# Win-Terminal-Retro
Retro styled json settings file for the Windows Terminal

A retro styled theme for the [Windows Terminal](https://docs.microsoft.com/en-us/windows/terminal/), this is a slightly altered configuration of the config Microsoft has created from [here](https://docs.microsoft.com/en-us/windows/terminal/custom-terminal-gallery/retro-command-prompt). I've simply cleaned up some effects, made it look a bit more modern, and altered the fonts a bit. 

Check out the "Profiles.json" file to see what changes need to be made to the settins.json file to use the Retro color scheme by default. I personally have left the experimental.retroTerminalEffect off as I dislike the text distortion it produces.

To utilize this color style:

* Open Windows Terminal
* Press *CTRL , +*  - all at the same time.
* Copy the Profiles.json content into the "profiles" field, keep in mind if you copy over the "list" field blank you may have issues, I've kept it there as the profiles.json file expects it.
* Copy and paste the Windows-Retro-Terminal-Settings.json content into the "schemes" field.
* Save settings.json

The terminal will hot-reload using the new settings. If you have any errors in your settings.json file, it'll tell you.

![Image of Effects](https://i.imgur.com/fwF4ZEk.png)
