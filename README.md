# DGC Epoch (Previous name: MicroTime) - [Demo](https://diamondgotcat.github.io/DGC-Epoch/)

## How
DGC Epoch provides a simple, binary-based time format capable of representing extremely long durations.

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

### DGC Epoch ANY (dgceany)
- DGC Epoch ANY is a DGC Epoch with no fixed number of digits.

### DGC Epoch ANY Second (dgceanysec)
- This is a second-by-second version of DGC Epoch ANY.
- It can be used when precise time counting is not required.

### DGC Epoch ANY Extended (dgceanyext)
(Changes from DGC Epoch ANY)
- If the first digit is 0, it represents a positive number.
- If the first digit is 1, it represents a negative number.

### DGC Epoch 48 (dgce48)
- DGC Epoch 48 is the first DGC Epoch notation.
- It represents DGC Epoch with 48 digits binary.
- It can be used up to about the year 10925.

### DGC Epoch 48 Second (dgce48sec)
- This is a second-by-second version of DGC Epoch 48.
- It can be used when precise time counting is not required.

### DGC Epoch 48 Extended (dgce48ext)
(Changes from DGC Epoch 48)
To accommodate negative numbers, we'll make the first digit a parameter representing a negative number.
However, this would make the same mistake as the UNIX epoch, so we'll increment it by one digit instead.

### DGC Epoch 64 (dgce64)
- DGC Epoch 64 is the second DGC Epoch notation.
- It represents DGC Epoch with 64 digits binary.
- It can be used up to about the year 584944417.

### DGC Epoch 64 Second (dgce64sec)
- This is a second-by-second version of DGC Epoch 64.
- It can be used when precise time counting is not required.

### DGC Epoch 64 Extended (dgce64ext)
(Changes from DGC Epoch 64)
To accommodate negative numbers, we'll make the first digit a parameter representing a negative number.
However, this would make the same mistake as the UNIX epoch, so we'll increment it by one digit instead.

### DGC Epoch XXX
At the time of creating DGC Epoch, 48 bits was more than enough, and we believe that 64 bits is very reliable.

However, the "UNIX Epoch", which was the standard at the time, was originally 32 bits, and was a notation method that would soon run out of space.

If you run out of digits in DGC Epoch, please see below:
- Feel free to also use DGC Epoch 96 Second or DGC Epoch 128... or DGC Epoch 128 Extended
- However, make sure that the number part is the "number of digits in binary form".

