# CMPS 2200 Assignment 3
## Answers

**Name:**Ethan Schaferkotter


Place all written answers from `assignment-03.md` here for easier grading.


- **b.**
Since iterate goes through every string in mylist,
W(n) = O(n)

Because iterate is sequential, there is no paralellism, so
S(n) = O(n)

- **d.**
Assuming that scan is efficient,
W(n) = (n/2) + O(n)
so W(n) = O(n)

Every element in the list is mapped and scan is used,
S(n) = S(n/2) + O(1)
S(n) = O(logn)

- **f.**
Assuming parallelism, and that merge is O(1)
W(n) = 2W(n/2) + O(1)
W(n) = O(n)
and
S(n) = S(n/2)+O(1)
S(n) = O(logn)