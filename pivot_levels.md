Here is the formula on which this lib / package is working.

# Classic Pivot Points

```
R4 = R3 + RANGE (same as: PP + RANGE * 3)
R3 = R2 + RANGE (same as: PP + RANGE * 2)
R2 = PP + RANGE
R1 = (2 * PP) - LOW
PP = (HIGH + LOW + CLOSE) / 3
S1 = (2 * PP) - HIGH
S2 = PP - RANGE
S3 = S2 - RANGE (same as: PP - RANGE * 2)
S4 = S3 - RANGE (same as: PP - RANGE * 3)
```

# Fibonacci Pivot Points

```
R3 = PP + ((High – Low) x 1.000)
R2 = PP + ((High – Low) x .618)
R1 = PP + ((High – Low) x .382)
PP = (H + L + C) / 3
S1 = PP – ((High – Low) x .382)
S2 = PP – ((High – Low) x .618)
S3 = PP – ((High – Low) x 1.000)
```

# Woodie's Pivot Points

```
R1: (2 x pivot) – previous low
R2: Pivot + high - low
R3: High + 2 x (Pivot – low)
S1: (2 x pivot) – Previous high
S2: Current pivot – (R1 – S1)
S3: Low – 2 x (High – pivot)
```

# Camarilla Pivot Points

```
R4 = C + ((H-L) x 1.5000)
R3 = C + ((H-L) x 1.2500)
R2 = C + ((H-L) x 1.1666)
R1 = C + ((H-L) x 1.0833)
PP = (H + L + C) / 3
S1 = C – ((H-L) x 1.0833)
S2 = C – ((H-L) x 1.1666)
S3 = C – ((H-L) x 1.2500)
S4 = C – ((H-L) x 1.5000)
```

# DDeMark Pivot Points

```
The formula used in the calculation of the Tom DeMark "Pivot Points" are:
The value of X in the formula below depends on where the Close of the market is.
If Close < Open then X = (H + (L * 2) + C)
If Close > Open then X = ((H * 2) + L + C)
If Close = Open then X = (H + L + (C * 2))
R1 = X / 2 - L
PP = X / 4 (this is not an official DeMark number but merely a reference point based on the calculation of X)
S1 = X / 2 - H
Where R1 is the upper Resistance level, PP is the Pivot Point, S1 is the lower support level.
```
