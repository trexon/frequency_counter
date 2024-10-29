<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

"A simple frequency counter that should work up to close to clock frequency/2 with an 8-digit LED display 7-segment drive"

## How to test

"Connect an 8-digit common anode LED display to the digit drive and sev_segment ports. Both are active low drive so 
PNP transistors or P-channel MOSFETs are required to drive each digit (max 8) 
Apply a clock, ideally 50MHz, but if TT4 can't support that, then 10MHz, input n10_50 selects (low for 10MHz clock, high for 50MHz)
Apply a signal to be measured and the multiplexed display should show the frequency "

## External Hardware

8 digit LED display and digit drivers
