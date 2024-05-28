# Scramble 1

`R' U' F L2 F L' F' R2 F' R D F U' B L2 B2 U2 R2 U2 F D2 L2 B2 R' U' F`

## Solution

**DNF**

## In hindsight

Found this, but after an hour had passed.
Inserting slice moves is pretty cool, but I need to be able to find the insertions faster.

```
(L2 F L U)                      // eo       (4/4)
(R' F' L2 B' R2 B' F R)         // dr       (8/12)
F (B2 D2 F' [3] D2 L2 F [2])    // htr      (7/19)
(L2 U2 R2 L2 F2 [1] L2 F2)      // slice    (7-1/25)

[1] S2                          //          (0/25)
[2] S                           //          (0/25)
[3] S                           //          (1/26)
```

`F' L2 B2 R2 L2 D2 R2 B' D2 R2 F2 B' D2 B2 R' F' B R2 B L2 F R2 U' L' F' L2 (26)`
