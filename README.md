# Telegram Sticker plug-in for GIMP

This is a simple plug-in to ease creation of stickers for Telegram.

## Requirements
**Ubuntu:** `gimp-python`, **openSUSE:** `gimp-plugins-python`

## Installation
1. `chmod +x telegram-sticker.py`
2. `cp telegram-sticker.py ~/.config/GIMP/<version>/plug-ins`

## Usage
Load up an image in GIMP and if required, edit it to make the background transparent. Don't worry about size, cropping
or layer-merging, as the plug-in will take care of everything else. When the image is cleaned up, run the plug-in via
the filters menu **_Filters_** -> **_Generic_** -> **_Telegram Sticker_**.

After that, you just have to save it as `.png` or `.webp` file.

## Note
The plug-in currently relies on the image being RGBA (so an RGB image with alpha channel). Grayscale is not supported.
