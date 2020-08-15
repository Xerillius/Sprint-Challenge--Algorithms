#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - a is increasing at a rate of n^2 and while less than n^3, subtracting exponents you get n

b) O(n log n) - outer loop runs O(n) inner loop runs O(log n)

c) O(n) - decreasing at a rate of n

## Exercise II

def breaking_point(floors):
  bottom = 1
  top = floors
  current_floor = (bottom + top) // 2
  while bottom < top:
    if drop:
      bottom = current_floor
    else:
      top = current_floor
    current_floor = (bottom + top) // 2
  return current_floor


def drop():
  if breaks:
    return True
  else:
    return False