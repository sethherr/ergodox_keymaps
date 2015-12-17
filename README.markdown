 # Keyboard layouts for ErgoDox

An easy explanation of loading keyboard maps on the ErgoDox

## Building your own layout

If you're looking to configure your ErgoDox, you definitely should check 
out the [keyboard-configurator from massdrop](https://keyboard-configurator.massdrop.com/ext/ergodox), which has a beautiful configuration tool.

Notes on that configuration tool: 

- the `~L1` key is layer-whilst-pressed


## Installing firmware

Make sure:

* Your keyboard is plugged in
* You know what the "Teensy reset button" is ([on the ErgoDox EZ it's the hole in the upper right](tiny_reset_button.jpg)). Instead of pressing the reset button, you can press the "teensy" key on your keyboard.
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

## Keymaps

#### Querty configuration from keyboard-configurator

[Qwerty keymap](qwerty/qwerty.png)

#### Seth configuration

[@sethherr's keymap](seth/sethmap.png) - mac-user. Ever evolving configuration

#### Default ErgoDox EZ configuration:

[Default Firmware keymap for ErgoDox EZ](default_ergodox_ez/ergodox_ez_keymap.png)

Source code is available at https://github.com/jackhumbert/qmk_firmware/tree/master/keyboard/ergodox_ez

## Contributing

Please do! Add your configuration. Let's share all the information

1. Take a screenshot of your configuration (from the configuration tool or wherever)
2. Add your configuration image to the Readme, add the hexfile as well
3. Pull request a branch with your map