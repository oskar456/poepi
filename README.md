PoEpi: a multi purpose shield for Raspberry Pi
==============================================

This is a peripheral board for [Raspberry Pi](http://www.raspberrypi.org) with
three separate functions:

* Power supply with 12-40&nbsp;Volt input and 5&nbsp;Volt, 0.75&nbsp;Amps output,
with short circuit protection and simple passive PoE extractor (utilizes unused
pairs in a Fast Ethernet UTP cable).
* [1-Wire](http://en.wikipedia.org/wiki/1-Wire) controller
[DS2482-100](http://www.maximintegrated.com/datasheet/index.mvp/id/4382)
connected to I2C bus of Raspberry Pi.
* Real time clock module
[PCF8583](http://www.nxp.com/products/interface_and_connectivity/i2c/rtcs_with_i2c_interface/series/PCF8583.html)
with backup battery.

All schematics and board layouts are created using [EAGLE 6.2.1 beta](http://www.cadsoftusa.com).

For more informations, please visit [PoEpi pages](http://oskar456.github.io/poepi/).

List of schematics and boards
-----------------------------

* **PoEpi_v2**: current board design
* **PoEpi_proto**: old prototype board design
* **PoE_injector**: simple injector, utilizing unused pairs in a Fast Ethernet UTP cable.


### Copyright

Copyright 2013 Ondřej Caletka  
This work is licensed under a [Creative Commons Attribution 3.0 Unported License][lic].  
[![Creative Commons License][licimg]][lic]

[lic]: http://creativecommons.org/licenses/by/3.0/
[licimg]: http://i.creativecommons.org/l/by/3.0/88x31.png
