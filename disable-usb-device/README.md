# Desactivar usb 

Listar dispositivos usb: 
`lsusb` 

``` 
Bus 002 Device 002: ID 0bda:0316 Realtek Semiconductor Corp. Card Reader
Bus 002 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hub
Bus 001 Device 009: ID 138a:0097 Validity Sensors, Inc. 
Bus 001 Device 007: ID 13d3:5619 IMC Networks Integrated Camera
Bus 001 Device 003: ID 046d:0a8f Logitech, Inc. Logitech USB Headset
Bus 001 Device 008: ID 040d:340a VIA Technologies, Inc. USB Audio Device
Bus 001 Device 006: ID 046d:c08e Logitech, Inc. MX518 Gaming Mouse
Bus 001 Device 004: ID 046d:c33c Logitech, Inc. G513 RGB MECHANICAL GAMING KEYBOARD
Bus 001 Device 002: ID 1a40:0101 Terminus Technology Inc. Hub
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
``` 

`... ID VENDOR:PRODUCT ...`


cp `00-via-kvm-usb-audio.rules` => /etc/udev/rules.d/
