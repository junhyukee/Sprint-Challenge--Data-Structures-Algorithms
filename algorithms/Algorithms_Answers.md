Add your answers to the Algorithms exercises here.

## E1
1. O(n), a increments by n^2, break condition is n^3

2. O(n^3), the first three for loops depend on n, but the last for loop depends on k, but really only runs 9 times. So, the last loop is constant

3. O(n), need to run the function on the bunnies variable until it reaches 0

## E2
1. We can perform a binary search, which will limit the broken eggs to log n, where n is the amount of floors in the building.

pseudocode:

```
while True:
  n = n//2
  if egg_survives():
    # egg_survives() should return true if egg survives
    return n
```