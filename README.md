nRF Connect SDK Projects
========================

A collection of various starting-point-style projects as I mess with the nRF Connect SDK.

Tested with the seeed XIAO BLE board. Custom board definition provided to configure QSPI flash. To build with this
board:

```
west build -b xiao_ble/nrf52840/flash -- -DBOARD_ROOT=../
```
