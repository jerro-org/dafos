# DAFOS - DAta Flow Object System

## Implementation on Linux
* X11: take root window and be a window manager or just run in a window.
* OpenGl
* ALSA / Jack Audio
* FFmpeg
* Video4Linux2

## Module/Type Tree
Language predefined types:
* SYS
* RT
* MEM
* MODULE
    * Mutator

* Module
    * Meta
    * EventStack

* io: dynamically created hardware device stubs
    * audio
* store: dynamically created hardware block storage devices
    * nand
    * nor
    * nvme
    * usb