# Distribution Sort Pt. 2 – Radix Sort

Are there faster sortying algorithms? Yes, but not by making comparisons.

Radix sort is a special sorting algorithm that only works on integers, evaluating a single digit at a time. This exploits the nature of integers, knowing that more digits means a greater number.

## Radix Sort in Action

In action, radix sort proceeds by: 

1. Starting with the original array.
1. Figuring out how many digits the largest number has.
1. Looping from K = 0 up to this largest number of digits.
1. For each iteration of the loop, creating buckets for each digit (0 to 9) and place each numnber in the corresponding bucket based on its Kth digit.
1.  Replace our existing array with the values in our buckets, starting with 0 and going up to 9.
1.  Return list at the end!

Let's visualize this:

https://www.cs.usfca.edu/~galles/visualization/RadixSort.html

## Big O Complexity

### Worst Case Complexity: `O(nk)`

### Best Case Complexity: `O(nk)`

Radix sort actually has the same best, average, and worst time complexities– `O(nk)`– but a *space* complexity of `O(n + k)`

> *The topic of the efficiency of radix sort compared to other sorting algorithms is somewhat tricky and subject to quite a lot of misunderstandings.*
> For more, check out this thread:
> https://stackoverflow.com/questions/48451734/radix-sort-on-log-n-efficiency

Theaoritically, radix sort should work better than any of the other comparison sorts, but because of the limitations on the way that computers store numbers in memory, that may not actually be the case. If you'd like to learn more about why this is mathematically possible, check this out: https://en.wikipedia.org/wiki/Comparison_sort
