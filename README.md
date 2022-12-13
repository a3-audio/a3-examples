# A3 Examples
A collection of ready to go examples in different setups

## A. Bitwig & Element on macOS

Requiered software to run this example:

---
#### 1. Bitwig Version 4.4.3

https://www.bitwig.com/previous_releases/

---

#### 2. Blackhole 16ch virtual audio driver

https://github.com/ExistentialAudio/BlackHole

If you use Homebrew you can install it via:
```bash
brew install blackhole-16ch
```
---

#### 3. IEM Plugin-Suite for Ambisonics

https://plugins.iem.at/

Install the **VST 2 Version**

---
#### 4. Kushview Element

https://kushview.net/element/

Make sure you scan your VST 2 plugin folder in the Element Plugin Manager in order to have the IEM Plugins available in Element

---

#### 5. Compiled VST 3 versions of OSC-Light plugin by DrLight

Copy & Paste the OSC Light Ch 1 - 4 Plugins into your VST3 folder

So copy the plugins from this path in the repository: 
```bash
/a3-examples/macOS/Plugins
```
into your local VST3 path, usually:
```bash
/Library/Audio/Plug-Ins/VST3
```

If you are curious about this OSC control plugins, check out: https://github.com/drlight-code/osccontrol-light

---
#### 6. Copy LaunchAgent iem.presetpath.plist

Copy it into 
```bash
/Users/YOURNAME/Library/LaunchAgents/iem.presetpath.plist
```

Restart your mac in order to activate the LaunchAgent.

This step will be deprecated in future versions, but we need to load the preset files at initialization of the plugins, so they start with the right settings. For now this is the only solution.

Setup Video follows soon..