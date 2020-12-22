# Win-Terminal-Retro
Retro styled json settings files for the Windows Terminal

A retro styled theme for the [Windows Terminal](https://docs.microsoft.com/en-us/windows/terminal/), this is a slightly altered configuration of the config Microsoft has created from [here](https://docs.microsoft.com/en-us/windows/terminal/custom-terminal-gallery/retro-command-prompt). I've simply cleaned up some effects, made it look a bit more modern, and altered the fonts a bit. 

Check out the "Profiles.json" file to see what changes need to be made to the settins.json file to use the Retro color scheme by default. I personally have left the *experimental.retroTerminalEffect* off as I dislike the text distortion it produces.

The reasoning for splitting the json across 2 files here was so that it's a bit easier to see what sections need to be placed into the file and where specifically. The Microsoft documentation doesn't exactly do a good job of explaining anything beyond that you need an IBM font.

To utilize this color style:

* Open Windows Terminal
* Press *CTRL , +* 
* Copy the Profiles.json content into the "profiles" field, keep in mind if you copy over the "list" field blank you may have issues, I've kept it there as the profiles field expects it.
* Copy and paste the Windows-Retro-Terminal-Settings.json content into the "schemes" field.
* Save settings.json

The terminal will hot-reload using the new settings. If you have any errors in your settings.json file, it'll tell you.

The MS Original:

![Image of Original Effects](https://docs.microsoft.com/en-us/windows/terminal/images/retro-command-prompt.png)

Modified:

![Image of Effects](https://i.imgur.com/fwF4ZEk.png)
