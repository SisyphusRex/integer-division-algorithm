# integer-division-algorithm
Implementation of the Integer Division Algorithm.

## What Is
n: dividend, an integer  
d: divisor, positive integer  
q: quotient, integer  
r: remainder, 0 ≤ r ≤ d-1  

n = qd + r  

q = n div d (integer division)  
r = n mod d (modulo)  

## Pseudocode
Input: n, and d > 0  
Output: q, r  

If n ≥ 0  
  q = 0  
  r = n  
  while r ≥ d  
    q = q + 1  
    r = r - d  
if n < 0  
  q = 0  
  r = n  
  while r < 0  
    q = q - 1  
    r = r + d  
