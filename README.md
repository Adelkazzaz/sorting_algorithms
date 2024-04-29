# Sorting Algorithms

This repository contains implementations of various sorting algorithms in C. Each algorithm is implemented as a function that sorts an array of integers in ascending order.

## Table of Contents

- [Bubble Sort](#bubble-sort)
- [Insertion Sort](#insertion-sort)
- [Selection Sort](#selection-sort)
- [Quick Sort](#quick-sort)
- [Shell Sort - Knuth Sequence](#shell-sort---knuth-sequence)
- [Cocktail Shaker Sort](#cocktail-shaker-sort)
- [Counting Sort](#counting-sort)
- [Merge Sort](#merge-sort)
- [Heap Sort](#heap-sort)
- [Radix Sort](#radix-sort)
- [Bitonic Sort](#bitonic-sort)
- [Quick Sort - Hoare Partition Scheme](#quick-sort---hoare-partition-scheme)
- [Dealer](#dealer)

## Bubble Sort

- Prototype: `void bubble_sort(int *array, size_t size);`
- Implementation: [0-bubble_sort.c](0-bubble_sort.c)
- Time Complexity:
  - Best Case: O(n)
  - Average Case: O(n^2)
  - Worst Case: O(n^2)

## Insertion Sort

- Prototype: `void insertion_sort_list(listint_t **list);`
- Implementation: [1-insertion_sort_list.c](1-insertion_sort_list.c)
- Time Complexity:
  - Best Case: O(n)
  - Average Case: O(n^2)
  - Worst Case: O(n^2)

## Selection Sort

- Prototype: `void selection_sort(int *array, size_t size);`
- Implementation: [2-selection_sort.c](2-selection_sort.c)
- Time Complexity:
  - Best Case: O(n^2)
  - Average Case: O(n^2)
  - Worst Case: O(n^2)

## Quick Sort

- Prototype: `void quick_sort(int *array, size_t size);`
- Implementation: [3-quick_sort.c](3-quick_sort.c)
- Time Complexity:
  - Best Case: O(n log n)
  - Average Case: O(n log n)
  - Worst Case: O(n^2)

## Shell Sort - Knuth Sequence

- Prototype: `void shell_sort(int *array, size_t size);`
- Implementation: [100-shell_sort.c](100-shell_sort.c)
- Time Complexity: Dependent on array size and gap

## Cocktail Shaker Sort

- Prototype: `void cocktail_sort_list(listint_t **list);`
- Implementation: [101-cocktail_sort_list.c](101-cocktail_sort_list.c)
- Time Complexity:
  - Best Case: O(n)
  - Average Case: O(n^2)
  - Worst Case: O(n^2)

## Counting Sort

- Prototype: `void counting_sort(int *array, size_t size);`
- Implementation: [102-counting_sort.c](102-counting_sort.c)
- Time Complexity:
  - Best Case: O(n + k)
  - Average Case: O(n + k)
  - Worst Case: O(n + k)

## Merge Sort

- Prototype: `void merge_sort(int *array, size_t size);`
- Implementation: [103-merge_sort.c](103-merge_sort.c)
- Time Complexity:
  - Best Case: O(n log n)
  - Average Case: O(n log n)
  - Worst Case: O(n log n)

## Heap Sort

- Prototype: `void heap_sort(int *array, size_t size);`
- Implementation: [104-heap_sort.c](104-heap_sort.c)
- Time Complexity:
  - Best Case: O(n log n)
  - Average Case: O(n log n)
  - Worst Case: O(n log n)

## Radix Sort

- Prototype: `void radix_sort(int *array, size_t size);`
- Implementation: [105-radix_sort.c](105-radix_sort.c)
- Time Complexity: Dependent on the number of digits and range of input

## Bitonic Sort

- Prototype: `void bitonic_sort(int *array, size_t size);`
- Implementation: [106-bitonic_sort.c](106-bitonic_sort.c)
- Time Complexity: O(n log^2 n)

## Quick Sort - Hoare Partition Scheme

- Prototype: `void quick_sort_hoare(int *array, size_t size);`
- Implementation: [107-quick_sort_hoare.c](107-quick_sort_hoare.c)
- Time Complexity:
  - Best Case: O(n log n)
  - Average Case: O(n log n)
  - Worst Case: O(n^2)

## Dealer

- Prototype: `void sort_deck(deck_node_t **deck);`
- Implementation: [108-deck_sort.c](108-deck_sort.c)
- Sorts a deck of cards using the C standard library function `qsort`.
