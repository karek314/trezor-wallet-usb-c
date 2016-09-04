# Trezor Wallet USB-C
USB-C version of trezor hardware wallet designed to a bigger case

This is hardware project of forked <a href="https://github.com/trezor/trezor-hw">trezor-hw repository</a> redesigned to work with USB-C and a little bigger case.

Please be kindly advised that people behind original Trezor hardware wallet on purpose published non-working bootloader code in order to prevent people from building devices on their own.
Please take a look on my forked repository https://github.com/karek314/trezor-mcu which is free of this easter egg.

https://github.com/karek314/trezor-mcu/commit/34a081e032af5fc5d0f006adb6f7bec5c789feb8
Function random32() caused infinite loop preventing device from starting.
