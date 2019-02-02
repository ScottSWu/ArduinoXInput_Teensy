# Teensy XInput USB Mode

The files in this repository will add an additional USB mode ("XInput") to your Teensy 3 board, allowing it to emulate an Xbox gamepad.
 
## Installation

You must have both [Arduino](https://www.arduino.cc/en/main/software) and [Teensyduino](https://www.pjrc.com/teensy/td_download.html) installed before proceeding. Double-check that your installed Teensyduino version matches the files provided in this repository. This repository is currently using version [**1.44**](https://www.pjrc.com/teensy/td_144). If you don't know your Teensyduino version, compile a blank sketch with a Teensy board selected and the Teensy Loader will open. In the Teensy Loader window select "Help->About" and it will tell you the version number. If your version does not match you will have to reinstall the Teensyduino software.

Navigate to your Arduino installation directory and open up the 'hardware' folder. It is recommended that you make a backup of this folder before proceeding in case something goes wrong or if you want to revert the installation.

To install, copy the files from the repository's "teensy" directory into the hardware folder and replace any pre-existing files. This will not affect your saved sketches.

To uninstall, restore your 'teensy' folder from a backup or reinstall Teensyduino.

## Supported Boards

* [Teensy 3.6](https://www.pjrc.com/store/teensy36.html)
* [Teensy 3.5](https://www.pjrc.com/store/teensy35.html)
* [Teensy 3.1](https://www.pjrc.com/store/teensy31.html) / [3.2](https://www.pjrc.com/store/teensy32.html)
* [Teensy LC](https://www.pjrc.com/teensy/teensyLC.html)

## Credits and Contributions

A massive thank you to Zach Littell, whose did all of the original legwork in putting this together. Check out some of his stuff at [zlittell.com](http://www.zlittell.com).

## License

The files in this repository are licensed under the permissive [MIT license](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for more information.
