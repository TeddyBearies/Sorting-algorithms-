# Sorting-algorithms-
Bubble Sort
This method keeps comparing two numbers next to each other and switches them if they’re in the wrong order. After every full pass, more numbers end up in the right place. It’s one of the easiest sorting algorithms to understand, but not very fast when there are many elements.
Best case: O(n) when the list is already sorted.
Worst case: O(n²) when everything is reversed.

Insertion Sort
Insertion sort builds the sorted list step by step. It takes one number at a time and places it where it belongs among the previous ones. It works well when the list is already almost sorted, but it can be slow for large data sets.
Best case: O(n) when the list is mostly sorted.
Worst case: O(n²) when it’s in the opposite order.

Selection Sort
This method looks through the list, finds the smallest number, and puts it at the beginning. Then it repeats the same thing for the rest of the list until everything is sorted. It’s simple and easy to follow, but it also takes a lot of comparisons.
Best case: O(n²).
Worst case: O(n²) — it’s the same no matter what.

Quick Sort
Quick sort chooses one number as a pivot and splits the list into two parts — smaller numbers on one side and larger ones on the other. Then it sorts both sides in the same way until the whole list is in order. It’s usually faster than the others, especially for big lists.
Best case: O(n log n) when the pivot splits the list evenly.
Worst case: O(n²) when the pivot picks are bad and the list is already sorted or reversed.
