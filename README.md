# DGC Epoch (Previous name: MicroTime) - [Demo](https://kamu.jp/dgc-epoch/)

## How
This is a new way of expressing time that can represent very long periods of time.

It's very simple:
1. Measure the number of milliseconds since January 1, 2000 (UTC)
2. Convert to binary (Unsigned Integer)

## About LICENSE
DGC Epoch is licensed under the MIT License, but no copyright notice is required if you are only using DGC Epoch to display time.

## Logo
Anyone can use the DGC Epoch Logo for free.

You may use the image data in `./assets/` directory without attribution, as long as you follow these guidelines:
- Do not change the colors or make any modifications that significantly reduce visibility.
- Do not change the text in the DGC Epoch logo to a different font or characters.

## Versions

### DGC Epoch 48
- DGC Epoch 48 is the first DGC Epoch notation.
- It represents DGC Epoch with 48 digits.
- It can be used up to about the year 10925.

### DGC Epoch 64
- DGC Epoch 64 is the second DGC Epoch notation.
- It represents DGC Epoch with 64 digits.
- It can be used up to about the year 584944417.

### DGC Epoch XXX
At the time of creating DGC Epoch, 48 bits was more than enough, and we believe that 64 bits is very reliable.

However, the "UNIX Epoch", which was the standard at the time, was originally 32 bits, and was a notation method that would soon run out of space.

If you run out of digits in DGC Epoch, please see below:
- Feel free to also use DGC Epoch 96 or DGC Epoch 128.
- However, make sure that the number part is the "number of digits in binary form".
