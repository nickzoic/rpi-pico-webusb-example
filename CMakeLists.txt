cmake_minimum_required(VERSION 3.13)

include(pico-sdk/pico_sdk_init.cmake)
project(rpi-pico-webusb)
pico_sdk_init()
include_directories(.)
add_executable(firmware main.c usb_descriptors.c pico-sdk/lib/tinyusb/hw/bsp/raspberry_pi_pico/board_raspberry_pi_pico.c) 
target_link_libraries(firmware pico_stdlib tinyusb_device)


pico_add_extra_outputs(firmware)
