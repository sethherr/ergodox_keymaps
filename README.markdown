# My keyboard layout for the ErgoDox

[Read the ErgoDox EZ docs for more information](https://github.com/ErgoDox-EZ/docs)

There is an upcoming tool which you could contribute to - [fusion](https://github.com/ErgoDox-EZ/fusion). 

For now, check out the [keyboard-configurator from massdrop](https://keyboard-configurator.massdrop.com/ext/ergodox) (the ~L1 key is layer-whilst-pressed/hold-key-for-layer). 

You can [load my current configuration](https://keyboard-configurator.massdrop.com/ext/ergodox/?referer=JG8K58&hash=01e500269b961cdf91d4d07bf5b89dc9) on the massdrop configurator.

## Installing firmware

Make sure:

* Your keyboard is plugged in
* You know what the "Teensy reset button" is ([on the ErgoDox EZ it's the hole in the upper right](https://github.com/ErgoDox-EZ/docs/blob/master/tiny_reset_button.jpg)), or, alternatively, you know where the "teensy" key is on your keyboard.
* Download the [firmware.eep](firmware.eep) from this repository

Then:

1. Download and run the [Teensy Loader app](http://www.pjrc.com/teensy/loader.html)

2. Press and release the Teensy reset button

3. Click the "Auto" button on the upper right hand side of the Teensy-Loader window

4. Drag and drop the '.eep' file onto the Teensy loader window. 

5. Drag and drop the '.hex' file onto the Teensy loader window.

6. Press and release the Teensy reset button

Notes:

* If this process fails in the "Auto" button stage, try dragging in a .eep and a .hex file, then pressing auto and restarting the process from the beginning.
* For a more detailed account, check out the [ergodox-firmware repository](https://github.com/benblazak/ergodox-firmware#load-firmware-onto-the-teensy)

## My keymap

![@sethherr keymap](sethmap.png) 

mac user. Ever evolving configuration.

There are certain keys that I can't reach and hence don't use. Which is why they are dumb