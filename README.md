# Bare Minimum PWA

This project is meant to show what is the bare minimum work needed to turn a site into a installable PWA

## manifest.webmanifest

This file is responsible for making the site installable, when it has valid JSON and the keys currently present in the file, the button to install will work, in Chrome at least.

## icon.svg

It is required to link an image in the **manifest.webmanifest** file

## index.html

This is the site entrypoint it tell the browser to download the manifest and sets a script that enables the install button if everything is set correctly.
