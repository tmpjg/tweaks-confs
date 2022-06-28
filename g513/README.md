# g513 configs linux 

`sudo apt install g810-led` 

`g810-led --list-keyboards`
```
Device: Logitech - G513 Carbon Linear
Vendor ID: 046d
Product ID: c33c
```

`sudo g810-led -dv 046d -dp c33c -tuk 1 -a 909090`

info: https://delightlylinux.wordpress.com/2020/05/21/programming-the-logitech-g513-rgb-keyboard-lights-in-linux-with-g810-led/
