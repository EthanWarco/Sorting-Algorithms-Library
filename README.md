# Sorting-Algorithms-Library
This library includes Quicksort, Parallel Quicksort, Mergesort, Parallel Mergesort, MSD Radix Sort, Parallel MSD Radix Sort, Heapsort, Binary Insertion Sort, Introsort, and Timsort.

Some important things to keep in mind with this library are:
1. Use timsort whenever possible rather than Mergesort, as not only is it faster on random data, but has a massive advantage over real world data.
2. If possible, always use the parallel version of an algorithm if it has one, as this can dramatically reduce the time on large sets of data.
3. Due to not being a comparison sort, Radix Sort only works on 32 bit integers.
4. Insertion sort should only be used when working with extremely small data sets (less than 100), as the runtime of Insertion Sort grows with the square of the amount of data given.
