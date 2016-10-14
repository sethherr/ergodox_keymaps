# My keyboard layout for the ErgoDox

Read the [ErgoDox EZ docs](https://github.com/ErgoDox-EZ/docs) or the official [ErgoDox EZ website](https://ergodox-ez.com) for more information.

ErgoDox EZ released a graphical configurator that looks fleet - [ErgoDox EZ graphical configurator](http://configure.ergodox-ez.com/keyboard_layouts/new).

I made my layout before it existed and hence used the [keyboard-configurator from massdrop](https://keyboard-configurator.massdrop.com/ext/ergodox) (the ~L1 key is layer-whilst-pressed/hold-key-for-layer). You can [load my current configuration](https://keyboard-configurator.massdrop.com/ext/ergodox/?referer=JG8K58&hash=e629711e92cb52bd6d19840716e7f497) on the massdrop configurator.

## Installing firmware

([from the ErgoDox docs](https://github.com/ErgoDox-EZ/docs))

First, make sure:

* Your keyboard is plugged in
* You know what the "Teensy reset button" is ([the tiny hole in the upper right](https://github.com/ErgoDox-EZ/docs/blob/master/tiny_reset_button.jpg)). Alternatively, you can use the "teensy" key if it's in your keymap.

Then:

1. Download and run the [Teensy Loader app](http://www.pjrc.com/teensy/loader.html)
2. Press and release the Teensy reset button
3. Click the "Auto" button on the upper right hand side of the Teensy-Loader window
4. Drag and drop the '.hex' file onto the Teensy loader window.
5. Press and release the Teensy reset button

Notes:

* If this process fails in the "Auto" button stage, try dragging in the [firmware.eep](firmware.eep) file (from this repository) and a .hex file, then pressing auto and restarting the process from the beginning.
* For a more detailed account, check out the [ergodox-firmware repository](https://github.com/benblazak/ergodox-firmware#load-firmware-onto-the-teensy)


## My keymap

![@sethherr keymap](sethmap.png)

mac user, [here are my shortcuts](https://gist.github.com/sethherr/094eb7e2261cff16afd0)

There are keys that I can't reach, don't use regulary and hence forget what they do. So I made them spacebar, because space never fucked anything up.
