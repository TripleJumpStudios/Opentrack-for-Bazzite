# Update 

This project is now depreciated. Recommend using the Opentrack Appimage provided here. [Opentrack](https://github.com/opentrack/opentrack) Note that if attempting to use with Star Citizen there is a potential bug with the wrapper. More information can be found on the [Star Citizen Lug Knowledge Base](https://wiki.starcitizen-lug.org/Head-Tracking)

Updates for Fedora 43 require Qt6. The current version of this script only supports Qt5. While investigating changes and updates, discovered the above mentioned Appimage which is a better solution. Feel free to reach out if you have any questions on setup and I will try to help.


Build and install OpenTrack on Bazzite OS using Distrobox. This script adapts the standard (Fedora script)[https://github.com/TripleJumpStudios/Opentrack-Install-Script] build process for Bazzite's immutable nature. It creates a Fedora container, installs dependencies (Qt, OpenCV, ONNX, Wine-devel), compiles OpenTrack from source, and uses `distrobox-export` to integrate it with the host. Specifically used for programs that need wine as an output like Star Citizen.

**Usage:** download the script from releases and run the script. Once finished, start OpenTrack from the Bazzite application menu `Run opentrack` or via `home/bazzite/opentrack-build-src/build/install/bin/opentrack`
