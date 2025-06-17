# Sorting

## selectionSort.m ##

This code implements the Selection Sort algorithm to sort an array in ascending order.



How It Works:
For each position i in the array:

Assume arr(i) is the smallest (minIndex = i).

Search the rest of the array (j = i+1 to n) to find the actual smallest element.

Swap it with arr(i) using a temporary variable temp.

Repeat for all positions until the array is sorted.

![selectionSort](https://github.com/user-attachments/assets/60c6a95a-bf7d-4e3b-8f55-a7f16371d5ee)

## bubbleSort.m

This code implements the Bubble Sort algorithm to sort an array in ascending order.

### How Bubble Sort Works:

Repeatedly steps through the array.

Compares adjacent elements (arr(j) and arr(j+1)).

Swaps them if they are in the wrong order (i.e., the first is greater than the second).

After each outer loop iteration, the largest unsorted element "bubbles up" to its correct position.

![bubbleSort](https://github.com/user-attachments/assets/526e9f62-0363-4527-8e82-26c8f18e25fe)

## insertionSort.m

This code implements the Insertion Sort algorithm to sort the array arr in ascending order.

### How Insertion Sort Works:

Starts from the second element and assumes the first element is already sorted.

Stores the current element as key.

Compares key with the previous elements:

If any previous element is greater than key, shift it one position to the right.

Insert key into its correct position.

![insertionSort](https://github.com/user-attachments/assets/3c28d0aa-0264-42a2-9fcb-bb0687726a2e)

## MergeSort.m

This code implements the Merge Sort algorithm to sort an array in ascending order using recursion and merging.

### How Merge Sort Works:

Recursive Splitting:

The mergeSort function splits the array into two halves until each part has one or zero elements (base case).

Merging:

The merge function then combines the sorted halves into a single sorted array by comparing elements one by one.

![MergeSort](https://github.com/user-attachments/assets/3924fded-d40c-475d-8aaf-c3862c0aad6b)

## QuickSort.m

This code implements the Quick Sort algorithm to sort an array in ascending order using recursion and pivot-based partitioning.

![QuickSort](https://github.com/user-attachments/assets/edd238c0-a326-4acb-893e-4d3f2fe5d375)
