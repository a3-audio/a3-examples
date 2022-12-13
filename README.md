# A3 Examples
A collection of ready to go examples in different setups

# A. Bitwig & Element on macOS

### Requiered software to run this example:
---
##### 1. Bitwig Version 4.4.3

https://www.bitwig.com/previous_releases/

---

##### 2. Blackhole 16ch virtual audio driver

https://github.com/ExistentialAudio/BlackHole

If you use Homebrew you can install it via:
```bash
brew install blackhole-16ch
```
---



Download Element

https://kushview.net/element/

Download IEM Plugin Suite: https://plugins.iem.at/

Install VST 2 Version

Copy & Paste the OSC Light Ch 1 - 4 Plugins in your VST3 folder

/Library/Audio/Plug-Ins/VST3

Copy LaunchAgent iem.presetpath.plist into /Users/YOURNAME/Library/LaunchAgents/iem.presetpath.plist

Restart your mac in order to activate the LaunchAgent.

This step will be avoided in future versions, but we need to load the preset files at initialization of the plugins, so they start with the right settings.

Follow the video