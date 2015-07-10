#Patchbay

##A Wireless Framework for Simple Connections

(original version for my masters thesis is now kept [here](https://github.com/andysigler/patchbay-thesis-2014))

Patchbay is a wireless framework for simple communications between Arduino projects. It's currently built of an Arduino library, radio breakout board, and mobile interface.

The library currently depends on LowPowerLab's [RFm69 library](https://github.com/lowpowerlab/rfm69), and Adafruit's Bluefruit LE [firmware](https://github.com/adafruit/Adafruit_BluefruitLE_Firmware) and [library](https://github.com/adafruit/Adafruit_BluefruitLE_nRF51).

The HTML5 interface uses [hammer.js](http://hammerjs.github.io/) for touch events, and connects over BLE using Sandeep Mistry's [node module](https://github.com/sandeepmistry/noble). After further testing, it will move to a mobile app using Phonegap and Don Coleman's [BLE plugin](https://github.com/don/cordova-plugin-ble-central).