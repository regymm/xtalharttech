---
name: MUZY
description_markdown: >-
  The Zynq FPGA with 85K logic elements, SDRAM, and dual video out at a bargain, with RP2040 multifunctional JTAG adaptor
description_markdown_full: |
  **Now available at [Tindie](https://www.tindie.com/products/regymm/muzy/)!** <br/>
  One of the many FPGA boards, but with a unique design and purpose: 
  AMD/Xilinx Zynq 7020 with 85K logic elements at <$50 
  HDMI/VGA Video out
  USB host
  32MB SDRAM
  Pluggable RP2040 multifunction JTAG/USB adaptor
  Pluggable power supply module
  LED/Buttons/Switches
  2x standard PMODs
  Open-source toolchain ready<br/>
  **Why did I make it?**
  FPGA boards, especially AMD/Xilinx ones with large logic elements, are still not cheap. Wanna run a multi-core SoC? Want 1MB of block RAM? Want some CNN accelerators? You'll need a lot of logic elements.
  And an Artix 7 100T, with 100K logic elements, is easily above $100. A Lattice lfe5u-85f with 85K logic elements might even be more expensive.
  So I thought about ZYNQ. They have both ARM cores and FPGA fabric -- and I'm able to make a board that utilizes the FPGA part only -- 85K logic elements at less than $50.
  Another not-cheap thing is the JTAG adaptor. One official JTAG dongle costs more than this board. So I integrated an on-board RP2040-based JTAG adaptor. It can run dirtyJtag firmware for direct openFPGALoader access, and XVC firmware for seamless Vivado programming and ILA debugging. And, UART access at the same time for both firmware. Of course, a 2x5 JTAG header is also available.<br/>
  **What makes it special?**
  This is a No-DDR ZYNQ that has SDRAM for the FPGA. 32MB (256Mb) memory is easily accessible.
  One Type-C cable for power + JTAG + UART, that's my favorite.
  If one day you get tired of FPGA, the pluggable RP2040 and power supply module can surely benefit your other projects as well!<br/>
  **Other information**
  Some components are hand-soldered, expect some differences per board. Board only. Cables or SD Cards not included. <br/>
  **Links** <a href="https://github.com/regymm/muzy">Schematics, PCBs, Start Guides and more</a> / <a href="https://www.youtube.com/shorts/H9cZ7YbqNOI">Video demo of dual video out and Linux on softcore SoC</a> . <br/>
  ![](/xtalharttech/images/products/muzy/muzy4-2.png)
  ![](/xtalharttech/images/products/muzy/muzy4-3.png)

price: '49.00'
stock: 0
styles:
  - image: /images/products/muzy/muzy4-1.png
---
