# NRF51822-ADC-over-BLE-link
Project file is located at: examples/ble_peripheral/ble_app_uart/pca10028/s130/arm5_no_packs

Sends ADC data over BLE link.
Connect to "CNK TECH Labs" Bluetooth device.

Inside:
https://github.com/attacker145/NRF51822-ADC-over-BLE-link/blob/master/components/drivers_nrf/spi_master/nrf_drv_spi.h
file there is:
#include "E:\Projects\ADC over BLE Rev01\examples\ble_peripheral\ble_app_uart\nrf_drv_config.h"
which you will have to change to your file location.
I was not able to include this file the normal way.
