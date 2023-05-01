# Zmk config for Lily58

 This is my personal configuration for the Lily58 split keyboard powered by two nice!nanos
 
_Uses an experimental zmk feature to [enable mouse keys](https://github.com/zmkfirmware/zmk/pull/1430)_

## Hardware

* 1x Lily58 Hotswap Kit [mechboards.co.uk](https://mechboards.co.uk/products/lily58-kit)
* 2x Nice!nano v2 wireless controller [42keebs.eu](https://42keebs.eu/shop/parts/controllers/nice-nano-v2-wireless-controller/)
* 2x 150mA Li-Po battery [aliexpress](https://es.aliexpress.com/af/302030-lithium-polymer-battery.html?spm=a2g0o.best.1000002.0&initiative_id=AS_20230224134604&origin=n&dida=y)
* 68x Gazzew Boba U4 silence tactile switch [aliexpress](https://es.aliexpress.com/item/1005001809357064.html?spm=a2g0o.order_list.order_list_main.10.f9c2194du0Q7VF&gatewayAdapt=glo2esp)
* 56x 1U DSA blank black keycaps [aliexpress](https://es.aliexpress.com/item/32832417476.html?spm=a2g0o.order_list.order_list_main.206.4bb8194dmCyLto&gatewayAdapt=glo2esp) 
* 2x 2U DSA blank black keycaps [aliexpress](https://es.aliexpress.com/item/32895127912.html?spm=a2g0o.order_list.order_list_main.205.4bb8194dmCyLto&gatewayAdapt=glo2esp)
* No OLEDs

## Others
* 5x Adhesive-backed lead tape [aliexpress](https://es.aliexpress.com/item/32825175785.html)
* 4x Aluminium standoffs M2 10mm [aliexpress](https://es.aliexpress.com/item/1005001711916538.html?spm=a2g0o.order_list.order_list_main.249.43b2194dOWseQE&gatewayAdapt=glo2esp)
* 15x Flat Screws M2 6mm [aliexpress](https://es.aliexpress.com/item/1005001596805523.html?spm=a2g0o.order_list.order_list_main.204.43b2194dOWseQE&gatewayAdapt=glo2esp)

 
## Configuration
* No displays
* Bluetooth
* Mouse keys enabled

## Keymap

### _main_
![layer0.png](resources%2Flayer0.png)

### _lower_
![layer1.png](resources%2Flayer1.png)

### _higher_
![layer2.png](resources%2Flayer2.png)

_*Images were taken from using the same keymap on [qmk configurator](https://config.qmk.fm/#/lily58/rev1/LAYOUT)_

### QMK configuration keymap
[qmk_lily58_rev1_layout_mouse.json](resources%2Fqmk_lily58_rev1_layout_mouse.json)
