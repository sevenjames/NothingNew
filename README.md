## NothingNew

This is a skin for Steam that removes the "What's New" section from the Library.

It's a totally harmless little CSS hack.

### Prerequisite
Know where your Steam folder is located.<br>
These are the default locations as far as I know.
* Windows: `\Program Files\Steam` or `\Program Files (x86)\Steam`
* Linux: `~/.steam/steam` or `~/.local/share/Steam`
* Mac: `~/Library/Application Support/Steam/Steam.AppBundle/Steam/Contents/MacOS`

### Installation
1. Download and unzip the [latest release](https://github.com/sevenjames/NothingNew/releases)
1. Copy the NothingNew-xxx folder into the `\Steam\skins\` folder.
1. Restart Steam.
1. Open Steam settings.
1. In the Interface section, select the NothingNew skin.
1. Click OK.
1. Restart Steam.
1. Observe the lack of news. :shipit:

### Uninstallation
1. Open Steam settings.
1. In the Interface section, select the default skin.
1. Click OK.
1. Restart Steam.
1. Delete the NothingNew folder from the `\Steam\skins\` folder.

### Manual Update
This skin necessarily includes a duplicate of the default style file.
<br>_If Steam ever updates that file then this skin would be out of sync with the default style._
<br>This is very easy to fix:
1. copy `\Steam\resource\styles\steam.styles`
1. into `\Steam\skins\NothingNew-xxx\resource\styles\`
1. overwrite = yes
