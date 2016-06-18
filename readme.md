# i2c-lcd

This is a set of LCD programs that drive a mini LCD type AQM0802 over the I2C bus of embedded systems. This includes popular devices like the BeagleBone Black, or the Raspberry Pi. The code is based  on a previous embedded C library for [HD44780-based character LCD](https://github.com/fm4dd/hd44780lcd-lib).

The AQM0802 2x7 character LCD is a downsized module that fits the scale of credit-card-sized boards, and can provide output of critical paramaters, such as the current WiFi DHCP address assignment.

Beaglebone Black example, using a prototype cape:

![](images/bbb-AQM0802.jpg)

See also http://blog.fm4dd.com/?p=896

Interfacing the AQM0802 LCD display with a Raspberry Pi:

![](images/raspi-AQM0802.jpg)
