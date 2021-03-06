
# Pico [![CodeQL](https://github.com/Li-amK/pico/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/Li-amK/pico/actions/workflows/codeql-analysis.yml)
USB Rubber Ducky like device with a Raspberry PI Pico 

The files that are on the board are located in the [Pico Board](https://github.com/Li-amK/pico/tree/main/Pico%20Board) Folder.

Board Firmware is [Circuitpython](https://circuitpython.org/board/raspberry_pi_pico/).

# Payloads
For Different Payloads see [the Wiki](https://github.com/Li-amK/pico/wiki) of this Repository.

# Setup Mode

To edit the payload, enter setup mode by connecting the pin 1 `(GP0)` to pin 3 `(GND)`, this will stop the pico-ducky from injecting the payload in your own machine. The easiest way to so is by using a jumper wire between those pins before pluging it into your own machine.

# USB disable mode

If you need the pico-ducky to not show up as a USB mass storage device for stealth, connect a jumper wire between pin `18` and pin `20`. This will prevent the pico-ducky from showing up as a USB drive when plugged into the target computer.
Remove the jumper and the default mode is USB mass storage enabled.
