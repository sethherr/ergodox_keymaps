# Keyboard layouts for ErgoDox

An easy explanation of loading keyboard maps on the ErgoDox

## Building your own layout

If you're looking to configure your ErgoDox, you definitely should check out the [keyboard-configurator from massdrop](https://keyboard-configurator.massdrop.com/ext/ergodox), which has a beautiful configuration tool.

Notes on that configuration tool: 

- the `~L1` key is layer-whilst-pressed


## Installing firmware

This is a step by step guide for installing firmware from the configuration tool. Before beginning, make sure:

* Your keyboard is plugged in

* You know what the "Teensy reset button" is ([on the ErgoDox EZ it's the hole in the upper right](tiny_reset_button.jpg)).

* Download the [firmware.eep](firmware.eep) from this repository

Then:

1. Download and run the [Teensy Loader app](http://www.pjrc.com/teensy/loader.html)

2. Click the "Auto" button on the upper right hand side of the Teensy-Loader window

3. Drag and drop the '.eep' file onto the Teensy loader window.

4. Press and release the Teensy reset button

5. Drag and drop the '.hex' file onto the Teensy loader window.

6. Press and release the Teensy reset button

Notes:

* If this process fails in the "Auto" button stage, try loading a .eep and a .hex file, then pressing auto and restarting the process from the beginning.

* Now that your firmware is loaded, there should be a keyboard shortcut you can press instead of the Teensy reset button, if you prefer

* For a more detailed account, check out the [https://github.com/benblazak/ergodox-firmware#load-firmware-onto-the-teensy)

## Keymaps

### Querty configuration from keyboard-configurator

![Qwerty keymap](qwerty/qwerty.png)


### Seth configuration

![@sethherr's keymap](seth/sethmap.png)

I'm on a mac. I use [emacs shortcuts for movement](https://www.hcs.harvard.edu/~jrus/site/system-bindings.html), so `Ctrl` is very important.

### Default ErgoDox EZ configuration:

![Default Firmware keymap ErgoDox](default_ergodox_ez/ergodox_ez_keymap.png)

Available at https://github.com/jackhumbert/qmk_firmware/tree/master/keyboard/ergodox_ez

A pull request with the right information would be spectacular.

## Contributing

Please do! Add your configuration. Let's share all the information

1. Take a screenshot of your configuration (from the configuration tool or wherever)
2. Add your configuration image to the Readme, add the hexfile as well
3. Pull request a branch with your map