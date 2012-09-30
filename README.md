
 ============================================

 Korg Pandora PX5D Editor for Linux
 
 http://www.exp-media.com/px5d_editor_linux
 
 ============================================

A library and editor for the Korg Pandora PX5D on Linux.

The Pandora PX5D is a portable multi-effect for guitar and bass made by Korg. It
is an amazingly small and full-featured tool for guitar and bass players, has an
USB-Audio interface to use it as a sound card which works out-of-the-box on 
Linux, and a USB-MIDI interface for which support has been added in Linux 
Kernel 3.0.

Before Kernel 3.0, there was no possibility to build a preset editor for the 
device as it communicates with the computer via USB-MIDI. Since Kernel 3.0, the
USB-MIDI interface of the PX5D is detected by ALSA. A native editor became an
option instead of using the preset editor that Korg made for Windows, via Wine.

This Korg Pandora PX5D Editor for Linux is a simple, no-eye-candy preset editor
which allows to view all parameters of a preset on the PX5D and edit them in
real time.

This project is made of a small library, which can currently only be build 
with the accompanying QT GUI, but has no depency to it, and may allow to write
other editor or tools, e.g. a CLI preset dumper or batch updater.

This is a work in progress, a lot remain to be done, but preset edition is
fully functional. Have a look to the TODO file for more info on planned 
features and future ideas.

The project relies on the following libraries:
- QT
- ALSA
- pthread

which should allow easy compilation for most distributions.

Current Status of the project:

* Library & GUI set up
* Live editing of presets works.

TODO:

* handle saving/loading all presets to disk
* handle the drum machine
