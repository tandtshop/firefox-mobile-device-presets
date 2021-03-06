# Firefox Mobile Device Presets
Mobile device presets for the Firefox [responsive design view](https://developer.mozilla.org/en-US/docs/Tools/Responsive_Design_View).

## Installation

In Firefox, open a new tab and navigate to `about:config`. In the search bar, search for `devtools.responsiveUI.presets`. Edit the entry (or create it if it doesn't exist yet) and replace the value with the contents of `mobile-device-presets.json`.

## Usage

Open the responsive design view through the developer tools dialog box, Firefox menu `Extra -> Web Developer -> Responsive Design View`, or by using the keyboard shortcut `Alt + Cmd + M` on Mac or `Ctrl + Shift + M` on Windows.

## Contributing

If you would like to help out with the project, we're looking for people to test the accuracy of the device presets. In order to test a device, please [open an issue for it](https://github.com/robneu/firefox-mobile-device-presets/issues/) if one doesn't already exist. Testing a device means comparing the visual representation of a website within the Firefox responsive design view to the actual display of a real, physical device.

For verification proof, please include a screenshot from the device you're testing as well as a screenshot of the same webpage in the Firefox responsive design view. If the results are inaccurate, please provide as much data as possible about the inaccuracies such as browser information, device version, screenshots, measurement data, and anything else you think will be helpful to getting a more accurate result.

If you would like to receive contributor credit on the repo, please submit a pull request against this readme file with the verification status added to the list of devices bellow. Please follow the same format used on other verified devices.

## Included Devices

All devices marked verified have been tested as accurate by someone with an actual device.

* Apple iPhone 6+
* Apple iPhone 6
* Apple iPhone 5
* Apple iPhone 3 & 4
* Google Nexus 6
* Google Nexus 5 - [Verified](https://github.com/robneu/firefox-mobile-device-presets/issues/6)
* Google Nexus 4
* Google Galaxy Nexus
* Samsung Galaxy Note Original
* Samsung Galaxy Note
* Samsung Galaxy S S2 & S3 Mini
* HTC One [Verified](https://github.com/robneu/firefox-mobile-device-presets/issues/12)
* HTC 8X
* HTC Evo 3D
* LG G3
* LG Optimus G
* Microsoft Lumia
* Microsoft Lumia 1520
* Sony Xperia Z3
* Sony Xperia Z S P
* Blackberry Q10
* Blackberry Z30
* Blackberry Z10
* Blackberry Torch
* ZTE Open - Firefox OS
* Apple iPad
* Google Nexus 10
* Google Nexus 9
* Google Nexus 7 v2 - [Verified](https://github.com/robneu/firefox-mobile-device-presets/issues/29)
* Google Nexus 7 v1 - [Verified](https://github.com/robneu/firefox-mobile-device-presets/issues/30)
* Samsung Galaxy Tab
* Samsung Galaxy Tab 2 7
* LG G Pad 8.3
* Amazon Kindle Fire HD 8.9
* Amazon Kindle Fire HD 7
* Amazon Kindle Fire
* Microsoft Surface Pro
* Microsoft Surface
* Blackberry Playbook
* Apple iPod Touch
* Google Glass

## Thanks

I'd like to say thanks to everyone who has helped improve these presets by taking the time to test them on their devices. Thank you!

- [Matt Zak](https://github.com/mzak)
- [Hans Swolfs](https://github.com/hansswolfs)

## Credits

Inspired by [Firefox Responsive Presets](https://github.com/nicwortel/firefox-responsive-presets) and built using data from [mydevice.io](http://mydevice.io/devices/).
