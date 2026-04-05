---
created: 2026-03-24
tags:
  - study
---
Algorithm is a set of instructions and steps involved in order to create something or achieve a desired outcome.

The complexity of an algorithm depends on how many things are looped. In order to achieve obtimal  speed, one may remove as many aspects as possible from the loop and do things outside the loop instead. (somehow $log^2n$ is faster than n even as there is an additional calculation for it, absolutely stupid)

![[2026-03-24 1402]]

Algorithms are piped into something called [[Turing Machine]]. They are machines consisting of a pointer with 5 states (S01 -> S05), a set of boxes with the value of a bool (0 or 1) and a 5 set of instructions at a time to determine if and what the machine will do when the conditions are met, and the final box illustrating the direction that the pointer will move afterwards.

Translation layer:
{S0, 1, S2, 2, R}
is equivalent to:
```
If state = 0 and point = 1:
	set state = 2
	set point = 2
	move point Right
```

Thanks to this, the code of turing machines are incredibly simple to illustrate, making the usage easier