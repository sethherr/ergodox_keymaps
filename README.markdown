# My keyboard layout for the ErgoDox

[Read the ErgoDox EZ docs for more information](https://github.com/ErgoDox-EZ/docs)

There is an upcoming tool which you could contribute to - [fusion](https://github.com/ErgoDox-EZ/fusion). 

For now, check out the [keyboard-configurator from massdrop](https://keyboard-configurator.massdrop.com/ext/ergodox) (the ~L1 key is layer-whilst-pressed/hold-key-for-layer). 

You can [load my current configuration](https://keyboard-configurator.massdrop.com/ext/ergodox/?referer=JG8K58&hash=01e500269b961cdf91d4d07bf5b89dc9) on the massdrop configurator.

## Installing firmware

([from the ErgoDox docs](https://github.com/ErgoDox-EZ/docs))

First, make sure:

* Your keyboard is plugged in
* You know what the "Teensy reset button" is ([the tiny hole in the upper right](tiny_reset_button.jpg)). Alternatively, you can use the "teensy" key if it's in your keymap.

Then:

1. Download and run the [Teensy Loader app](http://www.pjrc.com/teensy/loader.html)
2. Press and release the Teensy reset button
3. Click the "Auto" button on the upper right hand side of the Teensy-Loader window
4. Drag and drop the '.hex' file onto the Teensy loader window.
5. Press and release the Teensy reset button

Notes:

* If this process fails in the "Auto" button stage, try dragging in a the [firmware.eep](firmware.eep) file (from this repository) and a .hex file, then pressing auto and restarting the process from the beginning.
* For a more detailed account, check out the [ergodox-firmware repository](https://github.com/benblazak/ergodox-firmware#load-firmware-onto-the-teensy)


## My keymap

![@sethherr keymap](sethmap.png) 

mac user. Ever evolving configuration.

There are certain keys that I can't reach and hence don't use regulary and forget what they do. So I've turned them mostly into spacebar, because that never fucked anything up.