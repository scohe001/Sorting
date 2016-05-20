Sorting
=======

Sorting is the most common operation run on sets of data. Whether we're sorting by priority of processes for the processor to run, or sorting relevance of results in a Google search of millions of items.

There are many MANY sorting algorithms out there, ranging from `O(n^2)` algorithms to `O(nlog(n))` to even `O(n)` as you'll see today. So let's get to programming!


Insertion Sort
--------------

Let's start with the basics. Insertion sort is the go to sort for small sets of data since it'll only take `O(n)` time on an already sorted list. That being said, on a set that's in reverse order, it'll be as bad as `O(n^2)`.

For a great visualization if you don't understand the algorithm, please see [this page](https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html).

*(Note: please don't look at zybooks for this one as I know they have all of the code already written for you)*

Shell Sort
----------

Now that you understand how Insertion Sort works, let's step it up a notch for this next one. Shell Sort is the evolved cousin of Insertion Sort. The algorithm is very similar (so similar that you could probably reuse some of your code here). However, Shell Sort manages to be a LOT faster.

For a visualization of Shell Sort, again please see [this page](https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html).

Counting Sort
-----------

Assume for this problem that you have a set of Midterm scores for a class (where the midterm was out of 100 and there were no partial points so everything is integers). Write a function to sort the scores using Bucket Sort.

*Hint: Make an array of length 100 for this sort*

