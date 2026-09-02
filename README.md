# A. Arda Uzan

Proprietary volatility desk, [CMZN Consulting](https://github.com/CMZN-Consulting).
Crypto derivatives.

I run the options book. Automation I built hedges the residual and quotes a
synthetic market around the same underlyings. It does not trade an option.
Models, risk, and the software that carries them are built here — nothing in
the critical path is rented.

The interesting pieces stay closed. What we can strip of alpha, we publish.

**[black76-zig](https://github.com/CMZN-Consulting/black76-zig)** is the first
of those: a Black-76 pricer in Zig, and 3,516 golden vectors that pin every bit
of its output. Bit-identical on x86-64 and aarch64. There is no tolerance band.

*Receipts, not support.*
