# i2cEXT
MBlock extension for manage i2c devices

There are some extensions for manage some especific i2c devices but if your device is some diferent from standard or you need any raw or simple contact mode i can't find anything which helps.

I 'cant find enough information for complete a extension that can play in mblock online mode so i left it in arduino mode only and if someone else wants complete it, please tell me and i´ll give all help as i'll be able.

Descripción de funcionamiento:

Function description:

Writing block:

Its parameters are the i2c address of the device (in decimal coding, eg: for a device with hexadecimal address "0x0D" it will be necessary to put "13"). The address or record byte in which we want to write (also in decimal) and then the full decimal byte value of the data we want to send.

Reading block:

You only have to enter the i2c address of the device in decimal and the record number or byte you want to read. It will return the value in decimal byte required.
