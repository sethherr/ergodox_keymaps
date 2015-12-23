# Keyboard layouts for ErgoDox

An easy explanation of loading keyboard maps on the ErgoDox, particularly the [ErgoDox EZ](https://www.indiegogo.com/projects/ergodox-ez-an-incredible-mechanical-keyboard)

## Building your own layout

There is an upcoming tool which you could contribute to - [fusion](https://github.com/ErgoDox-EZ/fusion). 

For now, check out the [keyboard-configurator from massdrop](https://keyboard-configurator.massdrop.com/ext/ergodox) (the ~L1 key is layer-whilst-pressed/hold-key-for-layer)

## Installing firmware

Make sure:

* Your keyboard is plugged in
* You know what the "Teensy reset button" is ([on the ErgoDox EZ it's the hole in the upper right](tiny_reset_button.jpg)), or, alternatively, you know where the "teensy" key is on your keyboard.
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
