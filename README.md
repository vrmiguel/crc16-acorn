# `no-std` iterator-based CRC16/ACORN (aka XMODEM, ZMODEM) implementation


Rust port of the CRC-16/ACORN (also known as XMODEM or ZMODEM) checksum implementation by [Georges Menie and Salvatore Sanfilippo, 3-Clause BSD Licensed](https://github.com/antirez/rax/blob/master/crc16.c)

## Parameters

```
Name                       : "XMODEM", also known as "ZMODEM", "CRC-16/ACORN"
Width                      : 16 bit
Poly                       : 1021
Initialization             : 0000
Reflect Input byte         : False
Reflect Output CRC         : False
Xor constant to output CRC : 0000
Output for "123456789"     : 31C3
```