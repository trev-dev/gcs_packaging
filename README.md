
# Table of Contents

1.  [Linux Bundlers for GURPS Character Sheet](#org6845f1c)
    1.  [AppImage Recipe](#org8b704bb)
    2.  [Flatpak](#org5c8a6db)


<a id="org6845f1c"></a>

# Linux Bundlers for GURPS Character Sheet

If you're a fan of GURPS and Linux/MacOSX, and you're not already aware of [GCS](https://gurpscharactersheet.com/) please go check it out. It's an invaluable tool for people who want a digital editor for character sheets but doesn't want to be stuck with Steve Jackson's dinosaur Windows only GURPS Character Aid.

The purpose of this repository is to assist with bundling GCS for any Linux distribution and may be used for personal use.


<a id="org8b704bb"></a>

## AppImage Recipe

This repository contains an [AppImage recipe](./AppImage) that will fetch the latest release of GCS from github releases and build an AppImage from that. It requires the use of [pkg2appimage](https://github.com/AppImage/pkg2appimage/releases) so make sure you grab that and put it on your path as an executable, or run it from the project directory with `./pkg2appimage.AppImage gcs_recipe.yml`

This recipe currently does not support auto-updating but hopefully will in the future.


<a id="org5c8a6db"></a>

## Flatpak

Currently being worked on. Check back later

