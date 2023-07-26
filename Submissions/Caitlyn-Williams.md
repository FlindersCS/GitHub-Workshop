# Caitlyn Williams

FAN: `pasc0106`
Repo: [Caitlyn Williams](https://github.com/DarkMagicSource/GitHub-Workshop)

> Hi **Zeccy** :purple_heart:

below is not a *Flinduino* virus I swear :)

```asm
#include <xc.h>

.set noreorder
.text
.globl main

main:
    li t0, 0xFF
    sw t0, TRISACLR
    sw t0, TRISBCLR
    sw t0, TRISCCLR

    li t0, 0x55
    sw t0, LATC
    li t0, 0x0000
    sw t0, LATB
    sw t0, LATA
```

`FUCS_SECRET_9853`