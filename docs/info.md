<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This is a 1-bit full adder that takes 3 single bit inputs [A, B, Cin] that outputs the sum [S, Cout]

## How to test

Use the  truth table below for functionality testing.

| Cin     | A       | B      | S      | Cout   |
|---------|---------|--------|--------|--------|
| 0       | 0       | 0      | 0      | 0      |
| 0       | 0       | 1      | 1      | 0      |
| 0       | 1       | 0      | 1      | 0      |
| 0       | 1       | 1      | 0      | 1      |
| 1       | 0       | 0      | 1      | 0      |
| 1       | 0       | 1      | 0      | 1      |
| 1       | 1       | 0      | 0      | 1      |
| 1       | 1       | 1      | 1      | 1      |

## External hardware

Input and Output LED can be used for display.
