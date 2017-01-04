# My keyboard layout for the ErgoDox

Sergodox

Made with the **ErgoDox EZ Configurator** - [view/clone layout on the configurator](http://configure.ergodox-ez.com/keyboard_layouts/qwopgl/edit)

![@sethherr keymap](sethmap.png)

Mac user, [here are my shortcuts](https://gist.github.com/sethherr/094eb7e2261cff16afd0)

There are keys that I can't reach, don't use regularly and hence forget what they do. So I made them spacebar, because space never fucked anything up.

======================

### Installing firmware

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

[Read the ErgoDox EZ docs for more information](https://github.com/ErgoDox-EZ/docs)