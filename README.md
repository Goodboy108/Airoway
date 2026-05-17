# Airoway
This is an all comprehensive air quality sensor that uses and atmega328p and some logic gates to show you the output! I am using some advanced sensors such as the BMP280 and some MQ sensors as well. 
My main motivation for making this project was to learn more about hardware and I also need a air quality sensor for my house. I also have a love for logic gates and how they work so I made this little contraption.

## Sensors

| Sensor   | What this does!                   |
| -------- | --------------------------------- |
| MQ135    | Air quality (various gases)       |
| MQ7      | Carbon monoxide (CO)              |
| MQ2      | Combustible gas & smoke           |
| DHT22    | Temperature & humidity            |
| BMP280   | Barometric pressure & temperature |
| GP2Y1010 | Dust & fine particles             |

## Logic Chips

| Chip    | What this does!                                                                           |
| ------- | ----------------------------------------------------------------------------------------- |
| 74HC595 | 8-bit serial-in, parallel-out shift register (used to control many outputs with few pins) |
| 74HC00  | Quad 2-input NAND gates                                                                   |
| 74HC04  | Hex NOT gates (inverters)                                                                 |
| 74LS08  | Quad 2-input AND gates                                                                    |
| 74LS32  | Quad 2-input OR gates                                                                     |
| 74HC74  | Dual D-type positive-edge-triggered flip-flops (used for storing 1 bit of data)           |


Instructions on use- 

Just place this in your room and plug it in to the adaptor, and it will actively monitor your environment and give you accurate results on its inbuilt display!


BOM-
| Name | Unit | Price (INR) | Total Price (INR) | Link | Total (USD) | Total | Total (USD) | Shipping |
|---|---:|---:|---:|---|---:|---:|---:|---:|
| Capacitor (100nf) | 6 | 18 | 108 | https://robu.in/product/upw1v101mpd-nichicon-aluminium-electrolyte-capacitor-100uf-35v | 1.13 | 4623 | $49 | $10.00 |
| Capacitor (22pf) | 2 | 99 | 198 | https://robu.in/product/22pf-mica-capacitor-500v-dc-%c2%b10-5pf-tolerance | 2.07 |  |  |  |
| Capacitor (22uf) | 1 | 2 | 2 | https://robu.in/product/22-uf-50v-through-hole-electrolytic-capacitor-pack-of-40 | 0.02 |  |  |  |
| Capacitor (220uf) | 1 | 2.11 | 2.11 | https://robu.in/product/220-uf-10v-through-hole-electrolytic-capacitor-pack-of-20 | 0.02 |  |  |  |
| LED | 8 | 1.54 | 12.32 | https://robu.in/product/5mm-green-dip-led-pack-of-50 | 0.13 |  |  |  |
| Connector_02*03, odd-even | 1 | 21 | 21 | https://robu.in/product/1-27mm-2x40-pin-male-double-row-header-strip-pack-of-3/ | 0.22 |  |  |  |
| Barreljack Connecter | 1 | 18 | 18 | https://robu.in/product/dc-005-female-dc-power-jack-supply-socket-5-5x2-1mm/ | 0.19 |  |  |  |
| MQ135 | 1 | 113 | 113 | https://robu.in/product/mq-135-air-quality-gas-detector-sensor-module-for-arduino | 1.18 |  |  |  |
| MQ7 | 1 | 110 | 110 | https://robu.in/product/mq-7-co-carbon-monoxide-coal-gas-sensor-module/ | 1.15 |  |  |  |
| MQ2 | 1 | 85 | 85 | https://robu.in/product/mq-2-mq2-smoke-gas-lpg-butane-hydrogen-gas-sensor-detector-module/ | 0.89 |  |  |  |
| DHT22 | 1 | 146 | 146 | https://robu.in/product/dht22-am2302-digital-temperature-humidity-sensor/ | 1.53 |  |  |  |
| BMP280 | 1 | 85 | 85 | https://robu.in/product/gy-bmp280-5v-temperature-and-humidity-sensor/ | 0.89 |  |  |  |
| GP2Y1010 | 1 | 416 | 416 | https://robu.in/product/dfrobot-gravity-dust-sensor-adapter-plug-play-gp2y1010au/ | 4.36 |  |  |  |
| TFT_DISPLAY | 1 | 964 | 964 | https://robu.in/product/smartelex-3-5-tft-display-320x480/ | 10.1 |  |  |  |
| Resistor (10k) | 4 | 2.28 | 9.12 | https://robu.in/product/cfr-25jb-52-10k-yageo-through-hole-resistor-10-kohm-cfr-series-250-mw-%c2%b1-5-axial-leaded-250-v/ | 0.1 |  |  |  |
| Resistor (150) | 1 | 1.75 | 1.75 | https://robu.in/product/cfr-25jt-52-150r-yageo-through-hole-resistor-150-ohm-cfr-series-250-mw-%c2%b1-5-axial-leaded-250-v/ | 0.02 |  |  |  |
| Resistor (470) | 8 | 0.89 | 7.12 | https://robu.in/product/cfr-25jt-52-470r-yageo-through-hole-resistor-470-ohm-cfr-series-250-mw-%c2%b1-5-axial-leaded-250-v/ | 0.07 |  |  |  |
| Push Switch | 1 | 150 | 150 | https://robu.in/product/125pcs-25-kinds-of-light-touch-switch-button-kit/ | 1.57 |  |  |  |
| Slide Switch | 1 | 150 | 150 | https://robu.in/product/125pcs-25-kinds-of-light-touch-switch-button-kit/ | 1.57 |  |  |  |
| Atmega328p | 1 | 402 | 402 | https://robu.in/product/atmega328p-pu-microchip-8-bit-mcu-avr-atmega-family-atmega328-series-microcontrollers-avr-20-mhz-32-kb-28-pins-dip/ | 4.21 |  |  |  |
| AMS1117- 3.3V | 1 | 6 | 6 | https://robu.in/product/ams1117-3-3-xblw-1a-fixed-3-3v-positive-electrode-15v-sot-89-voltage-regulators-linear-low-drop-out-ldo-regulators-rohs/ | 0.06 |  |  |  |
| 74HC595 | 1 | 21 | 21 | https://robu.in/product/1-month-warranty-1354/ | 0.22 |  |  |  |
| 74HC00 | 1 | 23 | 23 | https://robu.in/product/74hc00-quad-2-input-nand-gate-ic-through-hole-dip/ | 0.24 |  |  |  |
| 74HC04 | 1 | 23 | 23 | https://robu.in/product/74hc00-quad-2-input-nand-gate-ic-through-hole-dip/ | 0.24 |  |  |  |
| 74LS08 | 1 | 60 | 60 | https://robu.in/product/sn74ls08n-texas-instruments-logic-ic-and-gate-quad-2-inputs-14-pins-dip-74ls08/ | 0.63 |  |  |  |
| 74LS32 | 1 | 55 | 55 | https://robu.in/product/74ls32-quad-2-input-or-gate-ic-7432-ic-dip-14-package/ | 0.58 |  |  |  |
| 74HC74 | 1 | 43 | 43 | https://robu.in/product/sn74hc74n-texas-instruments-flip-flop-74hc74-d-15-ns-60-mhz-5-2-ma-dip/ | 0.45 |  |  |  |
| LM393 | 1 | 21 | 21 | https://robu.in/product/lm393-smd-smt-low-power-low-offset-voltage-dual-comparator/ | 0.22 |  |  |  |
| Crystal | 1 | 8 | 8 | https://robu.in/product/hc49-s-16mhz-crystal-oscillator-pack-of-5/ | 0.08 |  |  |  |
| Barreljack Adaptor | 1 | 20 | 20 | https://robu.in/product/male-2-15-5mm-for-dc-power-jack-adapter-connector-plug-for-cctv-camera-pack-of-2/ | 0.21 |  |  |  |
| PCB | 5 | 210 | 1050 | jlcpcb | 11 |  |  |  |
| isp connector | 1 | 65 | 65 | https://robu.in/product/usb-rs232-pl2303-ttl-converter-adapter-aurdino-nano-raspberry-pi/ | 0.68 |  |  |  |
| cable red | 1 | 160 | 160 | https://robu.in/product/22awg-solid-core-insulated-wire-pvc-red/ | 1.68 |  |  |  |
| cable black | 1 | 160 | 160 | http://robu.in/product/22awg-solid-core-insulated-wire-pvc-black/ | 1.68 |  |  |  |


This is my onshape CAD link-

