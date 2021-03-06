All units should be numbered and the order is very important.
But how do we deal with and measure irregularities?

In computer science and discrete mathematics,
an [inversion](http://en.wikipedia.org/wiki/Inversion_\(discrete_mathematics\))
is a pair of places in a sequence where the elements in these places are out of their natural order.
So if we use ascending order for a group of numbers, 
then an inversion is when the order is reversed and larger numbers appear before lower number in a sequence.

Check out this example sequence: (1, 2, 5, 3, 4, 7, 6) and we can see here three inversions:
- 5 and 3;
- 5 and 4;
- 7 and 6.

You are given a sequence of unique numbers and you should count the number of inversions in this sequence.

**Input:** A sequence as a tuple of integers. 

**Output:** The inversion number as an integer.

**Example:**

```python
count_inversion((1, 2, 5, 3, 4, 7, 6)) == 3
count_inversion((0, 1, 2, 3)) == 0
```
**How it is used:**

In this mission you will experience the wonder of nested loops, 
that is of course supposing you don't use advanced algorithms or black magic.


**Precondition:**

```python
2 < len(sequence) < 200
len(sequence) == len(set(sequence))
all(-100 < x < 100 for x in sequence)
```

