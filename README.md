# Airoway
This is an all comprehensive air quality sensor that uses and atmega328p and some logic gates to show you the output! I am using some advanced sensors such as the BMP280 and some MQ sensors as well. 
My main motivation for making this project was to learn more about hardware and I also need a air quality sensor for my house. I also have a love for logic gates and how they work so I made this little contraption.

The list of sensors I am using is-

MQ135: Air quality (various gases)

MQ7: Carbon monoxide (CO)

MQ2: Combustible gas & smoke

DHT22: Temperature & humidity

BMP280: Barometric pressure & temperature

GP2Y1010: Dust & fine particles


The logic chips I am using-

74HC595: 8-bit serial-in, parallel-out shift register (used to control many outputs with few pins).

74HC00: Quad 2-input NAND gates.

74HC04: Hex NOT gates (inverters).

74LS08: Quad 2-input AND gates.

74LS32: Quad 2-input OR gates.

74HC74: Dual D-type positive-edge-triggered flip-flops (used for storing 1 bit of data).
