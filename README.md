# remove-HyperSwitch-expired-dialog

[HyperSwitch](https://bahoom.com/hyperswitch) is a free Window Switcher App on macOS. I used it a few years ago and haven't found a perfect replacement yet. But the author stopped updating the software a few years ago.

Currently the app always pops up with the error "HyperSwitch Expired!" Dialog box, and cannot turn off the auto-check for updates option, you can change the popover by replacing the executable file masking in this repo.

![image](https://user-images.githubusercontent.com/16370772/170864323-6a959f16-782e-401a-a7a9-49f074fc5a40.png)


## Usage

```
sudo mv HyperSwitch /Applications/HyperSwitch.app/Contents/MacOS/
sudo chmod 755 /Applications/HyperSwitch.app/Contents/MacOS/HyperSwitch
```
Or download repackaged [dmg](https://github.com/qzz0518/remove-HyperSwitch-expired-dialog/releases/tag/v1.0) and reinstall the app

## Others
You can also try [alt-tab-macos](https://alt-tab-macos.netlify.app/), as suggested by [@ryankhart](https://github.com/qzz0518/remove-HyperSwitch-expired-dialog/issues/4)
