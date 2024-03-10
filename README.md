# Merge Sort In-Place

This C++ program implements an in-place merge sort algorithm, specifically focusing on the implementation of the base merge function `mergeBaseInPlace()`. The goal is to sort an array of integers efficiently while minimizing memory usage.

## Instructions

1. Complete the implementation of the `mergeBaseInPlace()` function provided in the code.
2. Use the `compare()` function to keep track of comparisons and the `myswap()` function to keep track of swaps.
3. Ensure that the merged sections of the array remain sorted in descending order.
4. Submit your results using the provided Google Spreadsheet link.

## Code Structure

### Functions Provided

- **compare(a, b)**: Compares two integers and increments the comparison count.
- **myswap(arr, i, j)**: Swaps elements at indices `i` and `j` in the array `arr` and increments the swap count.
- **printSubArr(arr, start, end)**: Prints a subsection of the array from index `start` to `end`.
- **isSortedDescending(arr, start, end)**: Checks if the subsection of the array from index `start` to `end` is sorted in descending order.

### Functions to Implement

- **mergeBaseInPlace(arr, start, mid, end)**: This function merges two sorted halves of the array in-place. It must utilize the `compare()` and `myswap()` functions to maintain the sorting order.

### Main Function

The `main()` function initializes an array of integers, performs the merge sort operation, and outputs the sorted array. It also calculates and displays various statistics such as the number of comparisons, swaps, and the number of times the base merge function is called.

## Running the Code

Compile and run the provided code. It will perform the merge sort operation on a randomly generated array of integers. You can adjust the size of the array and the number of samples to test different scenarios.

## Results

After running the program, it will display statistics including the number of elements, log(N), NLog(N), and various counts related to the sorting process. Use these results to analyze the efficiency and correctness of your merge sort implementation.
