<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This is a platform test with a full adder example.

## How to test

Apply all 8 possible binary combinations (000 through 111) to the three inputs (A, B, and Cin) and observe the two outputs (Sum and Cout):

0 active inputs (000): Sum = 0, Cout = 0

1 active input (001, 010, 100): Sum = 1, Cout = 0

2 active inputs (011, 101, 110): Sum = 0, Cout = 1

3 active inputs (111): Sum = 1, Cout = 1

## External hardware

You need a DIP switch and two LEDs.
