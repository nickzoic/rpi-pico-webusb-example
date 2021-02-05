# RPI Pico WebUSB Example

This is really just the example code from
`pico-sdk/lib/tinyusb/examples/device/webusb_serial` 
made into its own project.

```
git clone https://github.com/nickzoic/rpi-pico-webusb.git
cd rpi-pico-webusb.git
git submodule update --init --recursive
make

# mount the device then copy the firmware
cp build/firmware.uf2 /media/$USER/RPI-RP2/
```
