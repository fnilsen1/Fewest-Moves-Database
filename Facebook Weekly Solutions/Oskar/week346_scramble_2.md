## Scramble 2

```
R' U' F U' F D2 F2 R2 F' R2 F' D2 F' U2 R U2 B U2 R D' L R' D2 F R' U' F
```

### Attempt

stuff I found that I wrote down during the attempt.

eo:

```
2.  D' R' B
3.  B2 L B
4.  L U R B
5.  (F2 U2 R' B)
6.  (B2 D2 L B)
7.  (R L2 B2 U2 F)
8.  F2 R U2 B' L
9.  F2 R B' U2 L
10. R L B' L
11. R (F L D L)
12. R U' L2 F' D
13. R' D (B2 D)
1.  (D R2 U)
```

working towards dr:

```
eo  DRM         moves to dr                     moves   case

1.  (U2 R)      L2 B' R2 F' B' U2 F R           12      4q2cXe
                B F' D2 F' L2 F2 R2 B R         13      4q2cXe
2.  B2 L        U D' R2 D2 F2 B2 U' R           12      4q2cXe
    B2 L'       R2 F2 U D' F2 B2 D L
    L2 D        L' U2 R2 U2 L U' R U            13      3q2cXe      // worth trying this one?
3.  R'
2.  (R' U)      (F2 L2 F2 R L' F2 L R2 U)               3q4cXe
                (D2 L' R  U2 L' R' B2 L R2 U)
3.  (U)
2.  L2 D        (D2 R2 D L D')                          3q4cXe      // for some reason I wrote this. idk how..
```

working towards htr. started with the 13 moves 3q2cXe dr.

```
D' R' B                     // eo
L2 D L' U2 R2 U2 L U' R U   // dr

R                           // reduced to 2q4c4e, but there were no pairs so I switched
(F2 D2 L U2 L')             // htr

(F2 R2)                     // 2e2e2e2e in 21 moves. Had this as a backup skeleton.
```

then I went back to the DRM I had on eo 2 and switched.

```
D' R' B                     // eo
L2 D (D2 R2 D L D')         // 3q4c
```

I wrote this somehow, but it does not work. I have no idea how I found 3q4c from this.

I then returned to the 2e2e2e2e skeleton

```
D' R' B                     // eo       (3/3)
L2 D L' U2 R2 U2 L U' R U   // dr       (10/13)
R (F2 D2 L U2 L')           // htr      (6/19)
(F2 R2)                     // 2e2e2e2e (2/21)

The insertions I used added 14 and cancelled 8 so the final result was 27.
```

### Solution

```
D' R' B                         // eo       (3/3)
L2 D L' U2 R2 U2 L U' R U       // dr       (10/13)
R (F2 D2 L U2 L')               // htr      (6/19)
(F2 * R2)                       // 2e2e2e2e (2/21)

* F2 U2 R2 F2 R2 U2 F2 + R2     // 2e2e     (8-4/25)
+ F2 U2 D2 B2 U2 D2             // 2e2e     (6-4/27)

D' R' B L2 D L' U2 R2 U2 L U' R U R D2 U2 B2 D2 R2 F2 R2 U2 L U2 L' D2 F2 (27)
```

### In hindseight
- finding a decent skeleton early is nice
- there were four 3-move eos, but I only found three. That is not good.
- there were 33 <=4-move eos. Only writing down eight of them is too few.
- on eo nr. 1 I should have checked normal. `(D R2 U) B2 R' F U2 F' L` was a obvious dr in 9. Jay found 23 from this.
- on eo nr. 3 I did not find a 10 move dr after DRM `R`: `B2 L B R B2 L U F2 U R`. this is a good subset as well.
- my htr solution was optimal. good.
- *nissy* gives 26 moves as optimal from the dr. 27 is pretty good.
