# RPI Pico WebUSB Example

```
git clone https://github.com/nickzoic/rpi-pico-webusb.git
cd rpi-pico-webusb.git
git submodule update --init --recursive
mkdir build
cd build
cmake ..
make

# mount the device then copy the firmware
cp main.uf2 /media/$USER/RPI-RP2/
```
