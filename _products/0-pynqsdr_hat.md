---
name: PYNQSDR HAT
description_markdown: >-
  The add-on that brings openwifi to PYNQ-Z1 with ultra low cost
description_markdown_full: |
  Now prelaunch on [Crowd Supply](TBD)! <br/>
  **Functions**: PlutoSDR firmware, iio-oscilloscope, GQRX, dump1090, GNURadio, openwifi firmware, etc. <br/>
  **Example usage**: Do whatever you can do with the [PlutoSDR](https://github.com/regymm/plutosdr-fw) firmware! Listen to the FM radio, catch flight ADS-B by dump1090, simulate GPS signals, run custom RF communication with GNURadio. Run [openwifi](https://github.com/open-sdr/openwifi) -- the full-stack IEEE802.11/Wi-Fi design based on SDR, run your hotspot with AD936X, capturing packets, go scientific. <br/>
  **Why this**: On usual ZYNQ + AD936X combinations, the two chips are tightly coupled on one board, making it hard if even possible to utilize the ZYNQ for general FPGA development. But here, with the extension removable, you still have a fully-functional PYNQ-Z1 ready for anything. So it's especially suitable for FPGA person who want to have a taste of SDR(like me), or vise versa. And, **this is probably the lowest cost openwifi-capable SDR!** <br/>
  **Specifications**: AD9361 70 MHz - 6 GHz, 1RX/1TX, bandwidth <200 kHz - 40 MHz (replacing 200 Ohm resistors on PYNQ-Z1 PMOD to 0 Ohm can enable the maximum bandwidth of 56 MHz). LVDS interface routed via two short HDMI cables. <br/>
  **Items included**: PYNQSDR HAT itself, HDMI cable x2, PMOD bridge x2, Antenna x2, SMA adapter x2. See picture below. <i>PYNQ-Z1 itself is NOT included!</i><br/>
  **Connection**: The 3 SMA connectors(2 used, one spare) on HAT are SMA-P(ordinary standard), the adapters are SMA-J to RP-SMA-P, the antennae are RP-SMA-J(WiFi standard). See picture below. <br/>
  **Setup guide and software support**: <a href="https://github.com/regymm/PYNQSDR">Schematics, PCBs, Start Guides and more</a> / <a href="https://drive.google.com/drive/folders/1i_VogEwf81xpMHjC2Ka72Fs2wmAIC12y?usp=sharing">ready-to-use SD card openwifi/PlutoSDR image</a> . <br/>
  ![](/xtalharttech/images/products/pynqsdr_hat/1.jpg)
  ![](/xtalharttech/images/products/pynqsdr_hat/2.jpg)

price: '125.00'
stock: 0
styles:
  - image: /images/products/pynqsdr_hat/0.jpg
---
