# rc4_6502
MOS 6502 implementation of the old RC4 stream cipher.


## Status
Completed. The code works as intended. But the cipher itself if broken.
**Do. NOT. Use.**


## Introduction
This is an assembler implementation of the [RC4 stream cipher](https://en.wikipedia.org/wiki/RC4) for the old
8-bit MOS 6502 CPU. The cipher itself actually works quite well on the
CPU. Compared to modern lightweight ciphers the state is quite
large. RC4 has been broken for many years and should be used in any
applications. But the code was actually used in the [Datastorm Invite
2017](https://csdb.dk/release/?id=157625) as a challenge.
