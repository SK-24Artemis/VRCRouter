# VRCRouter
Lightweight and configurable OSC router for VRChat PCVR.

## Features
* Configuration interface.
* Low CPU & RAM footprint.
* Start with SteamVR.
* OSC Message routing from VRChat to specified address:port.
* Application autostarting and autoclosing.

## Download
[If i ever release this fixed thing..](https://github.com/SK3Artemis/VRCRouter/releases/)

## Building release
Run the compile-release-all-netf.sh script on cygwin.
Msbuild path is hard-coded into the script.
Clang must be accessible on the PATH.

Final binaries will be placed in staging/ship/

For a proper release, the final package should contain the following files/folders:
  * manifest.vrmanifest
  * openvr_api.dll
  * route presets
