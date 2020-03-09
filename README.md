# Amiga-Keyboard

## Summary

**These files are NOT intended for use in PCB design. These are used as a visual mapping and layout aide to help troubleshoot and fix keyboard issues.**

This repository is here to host the files used to map the various Amiga keyboard membranes and matrix layouts.

Currently the mapping is done using **GraphML** files produced using yEd Editor which can be downloaded from:

https://www.yworks.com/products/yed

The GraphML files are best viewed in yEd as it allows you to select nodes and edges which will get highlighted so that you can easily follow the traces and path.

**Note:** Ideally, I would have liked the mapping and layouts to be available in amigapcb.org - this would be ideal. Alternatively, this mapping and layout should be really done in something like KiCad. In the future I may look at converting these in to KiCad once I learn how to use it.

See the [Wiki](../../wiki) for information on how to best use yEd on these GaphML keyboard mappings.

## Supported keyboard membranes

The following keyboard membranes have been mapped so far:

* A500 / Mitsumi A619A (Large ENTER key)
* A500 / Mitsumi A619B (Small ENTER key, Left/Right Euro keys)
* A500 / Samsung 312502-12 (Dual membrane)
* A1200 / QWERTY A1200-A 56C774A (Reproduction)
* A600 / 8770-0056 REV E (Blue)

Other Amiga keyboard membranes will be added over time.

## To Do

The following Amiga keyboards are on the to do list and will be done as when I acquire them:

* A1200 - original membrane
* A600 - Green membrane
* A500 - Hi-Tek (Space Invaders) board
* Any of the big box Amiga keyboards

If you would like to donate an Amiga keyboard (or just the membrane/board) for mapping then it would be gratefully received!

## Thank you!

A big thank you to **BleuLlama** for the A500 keyboard schematics, which helped me alot when working on these mappings:

https://github.com/BleuLlama/AmigaSchematics

And to **nocash** on the EAB forums for starting the schematics of the Mitsumi keyboard at the following thread:

http://eab.abime.net/showthread.php?t=81893
