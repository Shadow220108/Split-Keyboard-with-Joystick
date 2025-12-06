
# Split-Keyboard-with-Joystick


Its a split keyboard custom designed for most effective use ( for me ) with an integrated joystick ( to be used as cursor) , maximizing productivity and ergonomics  
I am using XIAO NRF58240 rather than ESP32 cause the zmk firmware support is currently experimental/non-existent in the main branch, and the battery life of the keyboard which will be reduced to days rather than months in NRF58240

# HERE IS THE DESIGN OF SPLIT KEYBOARD

![CAD](CAD/Split\_Keyboard.png)



# HERE IS THE CASE ( WHICH WILL BE 3D PRINTED )
![CASE](CAD/Split\_Keyboard\_case.png)





# HERE IS THE PCB DESIGN
![PCB](PCB/split\_keeb\_pcb.png)



# HERE IS THE LEFT HALF SCHEMATIC

![LEFT](PCB/split\_sch\_left.png)



# HERE IS THE RIGHT HALF SCHEMATIC

![RIGHT](PCB/split\_sch\_right.png)



# Firmware
For firmware , i will be using ZMK the files used for them are in the folder i will be flashing it after the build

# BOM 
|ITEM                                 |DESCRIPTION    |QUANTITY                    |UNIT PRICE|TOTAL PRICE|URL                                                                                                                               |RUNNING TOTAL ( with tax )                |
|-------------------------------------|---------------|----------------------------|----------|-----------|----------------------------------------------------------------------------------------------------------------------------------|------------------------------------------|
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|PCB MANUFACTURE                      |PCB            |5(minimum on jlpcb)         |3.50$     |17.50$     |https://cart.jlcpcb.com/quote?stencilLayer=2&stencilWidth=100&stencilLength=100&stencilCounts=5&spm=Jlcpcb.Homepage.1010          |24.50$                                    |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|Seeed XIAO nRF52840                  |MICROCONTROLLER|2 ( one left and one right )|12.50$    |25$        |https://robocraze.com/products/seeed-studio-xiao-nrf52840-development-board-supports-bluetooth-5-0                                |49.50$                                    |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|Kailh MX Hotswap Sockets             |SWITCH SOCKETS |Set of 50                   |0.10$     |5$         |https://meckeys.com/shop/accessories/keyboard-accessories/key-switches/kailh-hot-swap-socket/                                     |54.50$                                    |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|Cherry MX Switches                   |SWITCH         |Set of 50                   |0.36$     |18$        |https://meckeys.com/shop/accessories/keyboard-accessories/key-switches/cherry-mx-rgb-switch/                                      |72.50$                                    |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|Blank Keycaps 1.0u                   |KEYCAPS        |Set of 50                   |0.20$     |10$        |https://meckeys.com/shop/accessories/keyboard-accessories/keycaps/blank-dsa-keycaps-1u/                                           |82.50$                                    |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|3.7V LiPo Batteries                  |BATTERIES      |2 ( one left and one right )|1$        |3$         |https://quartzcomponents.com/products/3-7v-1000mah-li-po-rechargeable-battery?variant=44131981295850                              |85.10$                                    |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|1N4148 - Fast Switching Diode SOD-323|DIODES         |48                          |0.02$     |1.10$      |https://quartzcomponents.com/products/1n4148ws-t4-switching-diode-sod-123-smd-package?variant=45540031627498                      |86$                                       |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|74HC165                              |SHIFT REGISTOR |1                           |0$        |0$         |https://quartzcomponents.com/products/74hc165-ic-8-bit-parallel-in-serial-out-shift-register-ic-smd-package?variant=44714752901354|86$                                       |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|SK16812 MINI                         |LED            |10                          |          |           |                                                                                                                                  |self sourced                              |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|Joystick and breakout board          |Joystick       |1                           |0.40$     |0.40$      |https://robu.in/product/joystick-module-ps2-breakout-sensor/                                                                      |87.00$                                    |
|                                     |               |                            |          |           |                                                                                                                                  |                                          |
|                                     |               |                            |          |           |TOTAL                                                                                                                             |90$ approximate with shipping and 3d parts|

