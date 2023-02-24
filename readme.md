# Zmk config for Lily58

 This is my personal configuration for the Lily58 split keyboard powered by two nice!nanos
 
_Uses an experimental zmk feature to [enable mouse keys](https://github.com/zmkfirmware/zmk/pull/1430)_

## Hardware

* 1x Lily58 Hotswap Kit ([mechboards.co.uk](https://mechboards.co.uk/products/lily58-kit)) 
* 2x Nice!nano v2 wireless controller ([42keebs.eu](https://42keebs.eu/shop/parts/controllers/nice-nano-v2-wireless-controller/))
* 2x 150mA [Li-Po Battery](https://es.aliexpress.com/af/302030-lithium-polymer-battery.html?spm=a2g0o.best.1000002.0&initiative_id=AS_20230224134604&origin=n&dida=y)
* 0x OLEDs
* 56x [1U DSA Blank](https://es.aliexpress.com/item/32832417476.html?spm=a2g0o.order_list.order_list_main.206.4bb8194dmCyLto&gatewayAdapt=glo2esp) black keycaps
* 2x [2U DSA Blank](https://es.aliexpress.com/item/32895127912.html?spm=a2g0o.order_list.order_list_main.205.4bb8194dmCyLto&gatewayAdapt=glo2esp) black keycaps
 
## Configuration
* No dislpays
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