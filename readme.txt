THIS repository - is re-workin now to have:
1)Non-bloking device`s I/O fuctions,
2)Integrate TinyUSB library to a device
3)Integrate libUSB to a host
4)Change CDC to vendor USB class
---------OLD notes:----------------------------------
The software was written in the Code::Blocks IDE.
The "hid_converter_dll" folder - is the Windows DLL library with C source code.
The "hid_converter" folder - is an example of use of this Windows library.
******************************************************************
I use for this USB->I2C, SPI adaptor the STM32F103C8 microcontroller.
The software uses USB as a transport and Virtual COM port.
The API functions described inside C sources  in "hid_converter_dll" folder
I2C2 - The master, I2C1-the slave
SPI1 - Master full duplex mode
https://ejaaskel.dev/making-usb-device-with-stm32-tinyusb/
