
# About
I'm Carsten Wulff, and I'm one of the engineers that worked on the
SAADC on nRF52. These examples are some of my barebone tricks and tips
on how SAADC can be used.

# To compile
Ideally it should be
```
make
make flash
```

But rarely that will suffice, you probably have to at least change 
SDKPATH in the Makefile

# To run
Connect using BLE UART application (i.e iOS Nordic UART app), and send commands

1. ex1_scan_multiple_channels
2. ex2_differentiation

# Origin
I've based this example on the ble_peripheral/ble_app_uart example in nRF5_SDK_11, so you
need to download that.

# Excuses
I'm not a professional embedded programmer (i.e I don't get paid to 
program embedded code), so I'm sorry if you find these examples a bit
messy.

Any concrete criticism/improvment requests are welcome. Send me a
private message on devzone.nordicsemi.com

# Disclamer
This is not an official Nordic Semiconductor release, it's examples
I've compiled in my "offline" time.





