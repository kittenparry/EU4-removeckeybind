# Remove C keybind from military interface
This Europa Universalis IV mod enables you to confirm pop-ups with C keybind when a military unit is selected.

Compatible with **v1.30**

[Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=1733443438)

* Not that it needed its own repo for simple 2 lines (heck, 2 characters) of change, but here we go.
* Search the code for `#### REMOVECKEYBIND` to see where it differs.

### Manual Installation
* Download [EU4-1.30-removeckeybind.zip](https://github.com/kittenparry/EU4-removeckeybind/releases/latest).
* Extract contents of the zip into your mod directory. See [footnote](#mod-directory-path) for its location & resulting directory structure.
* Turn it on in launcher's Mods tab, if it doesn't work try turning it on and off a few times.

![](https://raw.githubusercontent.com/kittenparry/EU4-removeckeybind/master/extras/screenshot.jpg)

### Mod directory path
Windows: `~\Documents\Paradox Interactive\Europa Universalis IV\mod\`  
GNU/Linux: `~/.local/share/Paradox Interactive/Europa Universalis IV/mod/`  
Mac: `~/Documents/Paradox Interactive/Europa Universalis IV/mod/`

Your mod directory structure should be like the following after the extraction:
```
mod/
  removeckeybind.mod
  removeckeybind/
    descriptor.mod
    interface/
      unitpanel_card.gui
```
