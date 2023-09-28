# Build Guide

![bally_main01](/images/bally_01.jpg)

This is the build guide for bally PCB. To build this board, you need [bully](https://www.cbkbd.com/product/bully) keyboard case.


### PCB Check
Make sure the PCB is recognized as bally with [vial](https://vial.rocks/).


### Key Switch
Solder key switches depending on your preferrable layout. The layout compatibility can be confirmed with [KLE](http://www.keyboard-layout-editor.com/#/gists/894ef2fe3e99eaf345a3c4bc84bd3d9b).


### Mouse Sensor
Sensor is already soldered on PCB. You just need to remove kapton tape from the sensor.

![bally_bg_01](/images/bally_bg_01.jpg)

![bally_bg_02](/images/bally_bg_02.jpg)


### Ball case
Once all key switches are soldered, assemble ball case. Ball case is composed of two parts, bottom and top. Fix the bottom ball case with two screws and two nuts onto your PCB.

![bally_bg_03](/images/bally_bg_03.jpg)

![bally_bg_04](/images/bally_bg_04.jpg)

Ball case top & bottom connect with magnets inserted in the top case. Personally the magnetic force is enough with the pre-installed two magnets, but in case you would like stronger magnetic force, you can install additional magnets (Φ6mm x 2mm) to both top and bottom case. Make sure you install them in the correct direction. If they are loose, you can use glue.

![bally_bg_05](/images/bally_bg_05.jpg)

### Assemble
Connect JST cable, insert tad poles, and put the PCB onto your bully case. Then put your favorite keycaps on it!

### Custom Key Codes

  You can set several custom key codes for trackball operation.

  Keycode |Description
  ---------|-----------
  `CPI_SW`  |Changes the CPI of the trackball. The default firmware changes the CPI in the order 200 -> 400 -> 800 -> 1600 -> 3200 -> 200... each time it is pressed.
  `SCRL_SW` |Changes the sensitivity of the sensor in scroll mode. The higher the value, the smaller the amount of scrolling.
  `ROT_R15` |Turns the Y axis of the mouse sensor 15 degrees clockwise.
  `ROT_L15` |Rotate the Y axis of the mouse sensor 15 degrees counterclockwise.
  `SCRL_MO` |Enables scroll mode for as long as it is pressed.
  `SCRL_TO` |Toggles between scroll mode and mouse mode each time it is pressed.
  `SCRL_IN` |Inverts the scroll direction.

  To set a custom key code in [vial](https://vial.rocks/), you can select it from "User" tab.

  ![bally_bg_06](/images/bally_bg_06.jpg)
