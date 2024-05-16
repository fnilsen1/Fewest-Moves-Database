# Scramble 1

`R' U' F U2 F' L2 D2 L2 B' L2 D2 B F2 D2 R' D U' L U L F D R U2 R' U' F`

## Solution

found the last insertion just after 1 hour so it is a DNF.

```
(L B R U2 F)                // eo       (5/5)
(D') F2 L B2 L' B2 R' D'    // dr       (8/13)
R B2 U2 R2 + B2 L' U2 L     // htr      (8/21)
D2 * L2                     // 2e2e2e2e (2/23)

* D2 F2 B2 U2 F2 B2         // 2e2e     (6-2/27)
+ R2 U2 B2 R2 U2 R2 B2 U2   // 2e2e     (8-7/28)
```

`F2 L B2 L' B2 R' D' R' U2 R2 B2 U2 B2 L' U2 L F2 B2 U2 F2 B2 L2 D F' U2 R' B' L' (28)`

Insertion finder gives possible 27 with insertions adding 16 and cancelling 12 moves...
