##Sorting take three!

Are there faster sortying algorithms? 
Yes we can! But not by making comparisons.

Here's a link if you'd like to leanr more about why this is mathmatically.

https://en.wikipedia.org/wiki/Comparison_sort

### Radix Sort 
- Special sorting algorithm that works on numbers.
- Exploits the fact that information about the sixe of a number is encoded in the number of digits.
- More digets means a bigger number

## Radix sort helpers
In order to implement implement radix sort, it's helpful to build a few helper functions 
first:
mostDigits(nums) - Given an array of numbers, returns the number of digits in the largest numbers in the list
'example of this in the console'

# Radix sort Pseudocode
- Define a funtion that accepts a list of numbers
- Figure out how many digits the largest number has 
- Loop from k = 0 up to this largest number of digits 
- For each iteration of the loop:
	- Create nuckets for each digit (0 to 9)
	- Place each numnber in the corresponding bucket based on its kth digit
-  Replace our existing array with the values in our buckets, starting with 0 and going up to 9
-  Return list at the end!
-  






### Bucket Sort



