Category: Forensics



- Tunn3l V1s10n


Description

We found this [file](https://mercury.picoctf.net/static/21c07c9dd20cd9f2459a0ae75d99af6e/tunn3l_v1s10n). Recover the flag.

Hints:

1. Weird that it won't display right...

2. Make sure to submit the flag as picoCTF{XXXXX}


Answer:

1. open file tunn3l v1s10n to https://hexed.it/

2. The first two characters are BM which indicates a BMP file

3. let change extension file to tunn3l v1s10n.bmp

5. open file with imageMagick and Height for a BMP file is at offset 0016h. I changed offset 0017h from 0x01 to 0x03




Flag: picoCTF{qu1t3_a_v13w_2020}