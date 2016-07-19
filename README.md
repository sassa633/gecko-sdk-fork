Gecko SDK fork
==============

This is a fork of some of the Gecko SDK components from Silicon Laboratories.
It includes fixes and new features that can be useful for everyone in the
community.

Silicon Laboratories and its employees are encouraged to use these patches
and include them in their own releases.

Change log
----------

### UARTDRV

* Fix various issues regarding building with C++ compilers
* Fix `UARTDRV_Abort`, previously UARTDRV was unable to perform any
more transmit or receive operations because `UARTDRV_Abort` did not
clean up after itself.
* Add ability to work with half-duplex mode, when the trasmitter
and receiver are on a single pin.
* Fix LEUART clock source selection issue
* Various minor improvements

