# anyon_e 15

A higher end, more gaming focused, open source laptop fork inspired by the anyon_e 13. 

Please check out the original repo, and tip the original creator! I'm just modifying this out of inspiration.

_aka project 'Arctic Wolf'_
#
#### Features (including added ones):

- RK3588 SoC Motherboard
  - CM3588-based
  - USB-C USB3.1 Gen 1
  - Supports up to 32GB LPDDR5 or 16gb LPDDR4X
  - **I really reccomend a version with eMMC flash for the boot image**
- Powertrain
  - ESP32-S3 embedded controller
  - ~60Wh Li-ion battery pack (maybe x2 if money/space allows)
- Peripherals
  - Glass-topped multi-touch trackpad
  - HD AMOLED 15.6" display
  - Anodized aluminum CNC chassis (i hope, most likely will end up being 304 grade aluminum)
- Additions to original project:
  - EasyEDA files for all schematics and PCBs so they're directly orderable. Additionally gonna include another repo for the Autodesk Inventor files, and blobs if needed.
  - modified boards to be cheaper to order - at least the test adapter so far (4layer -> 2layer pcb)
  - RJ45 jack for the on SOM 2.5g ethernet, an MXM slot for a GPU, USB2.0 hub with outside port and connections for wired keyboard(s).
  - revised boards for more features
  - beefier modular cooler for the SOM and MXM module (tba, haven't began anything aside from sketches)
#

Total end cost will be added here, including options and configurations i've bought;
So far the running total is:
 ## 772.37

For:
- Display adapter PCB x 5 (min order, JLCPCB, assembled (i don't have a reflow station)) .......... 116.34
- Azoteq PXM0057-501-S (from Mouser) ............................................................... 66.29
- CM3588 Plus (32GB LPDDR5, + 64gb eMMC) module, NAS board (for testing) and 12v 4A power supply .. 259.60
- MISC development boards and converters on amazon (MXM, E key adapter, SSD) ...................... 164.28*
- Sonnet GPU-RX55-TB3-S eGPU puck for the MXM 5500XT inside ....................................... 165.86

Theorized total (for a complete laptop, sans development boards):
 ## 1580.73 (USD, excluding chassis)
For:
- CM3588 Plus (32GB LPDDR5, + 64gb eMMC) module, NAS board (for testing) and 12v 4A power supply .. 210.00 (it's expected you get this entirely for loading the eMMC boot stuff)
- (MB) Custom 6 layer PCB (130mm x 215mm rough estimate), options detailed at final ordering ...... 155.23 (not including assembly!!!)
- Radeon 5500XT MXM 3.0 Module .................................................................... 165.86 (taken from a "broken" eGPU puck since the main distributor for MXM gpus appears to be away)
- Battery (x4, with lead time) .................................................................... 146.81
- Battery charging management PCB .................................................................  43.75 (not including assembly!!!)
- Samsung ATNA56YX03-0 Panel, adhesive strips, and connecting ribbon .............................. 241.47
- Mousepad old stock + generic backlit ribbon keyboard (Dell or Lenovo) ........................... 104.29
- Misc Connectors, a sum of all BoMs .............................................................. 327.89 (from a few sites,aggregated. this price will go up over time!!!)
- Webcamera, pair of shottky diodes, and a cable ..................................................  16.29 (ebay!)
- Chassis, CNC milled, with ABS or resin bezels ................................................... unknown at this time

#

Hypothetically to cut costs you could choose a base model CM3588 (8gb with 64gb eMMC), choose a cheaper monitor, skip the MXM card, and get the costs down to under 900$ US but i'm making this with no expenses spared as much as possible.

#

I've started to include .epro "nightly" revisions for this project as well, in case you wanna see progress over time.

#
