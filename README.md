# Caravel++

The idea is to develop a System on Module (SoM) on which the chip that is taped-out from MPW shuttles can be installed. Currently, Caravel chip is used to integrate the develop IP with external pins which can be used to control the IP. Carval++ is something like an upgraded version of this Caravel chip which enables chip designers to get more from their developed IP.

This idea is originated from Steve Casselman, CEO - Hotwright. ![Here](/Caravel%2B%2B.pptx) is the link to the presentation where Steve tries to visualize how the SoM could be.

The proposal includes -

1. 64-bit RISCV

2. DDR

3. A/D

4. D/A

5. MIPI

6. USB-JTAG

7. USB-UART

8. Ethernet

9. Network on chip

10. Quad SPI

11. 4-bit PCIe

12. HDMI in and out

This SoM rests on a baseboard which is customizable according to the requirements. But all baseboards accept the standard SoM caravel++ specs. 

![](/images/som_pcb.png)