# Sorting
Sorting

Merge Sort:

In merge sort, The divide-and-conquer strategy uses division to separate a list of numbers into equal parts, and these are then recursively sorted before being recombined to generate a sorted list.

Sample Output:

![Screenshot (28)](https://user-images.githubusercontent.com/129615692/229309452-1679f23d-3be1-44fa-8da5-da27729bf8f7.png)

Selection sort:

In slection sort, Selection sort is a sorting algorithm that selects the smallest element from an unsorted list in each iteration and places that element at the beginning of the unsorted list.

Algorithm:

selectionSort(array, size)
  repeat (size - 1) times
  set the first unsorted element as the minimum
  for each of the unsorted elements
    if element < currentMinimum
      set element as new minimum
  swap minimum with first unsorted position
end selectionSort

Code:

![Screenshot (30)](https://user-images.githubusercontent.com/129615692/229309794-f030ecc4-5079-48b4-9b84-062b46d57466.png)

Sample Output:

![Screenshot (29)](https://user-images.githubusercontent.com/129615692/229309820-dc53eda8-c616-4cfb-8ad3-d1eb06b41909.png)

Insertion Sort:

In insertion sorting, Insertion sort is a sorting algorithm that places an unsorted element at its suitable place in each iteration.

Algorithm:

insertionSort(array)
  mark first element as sorted
  for each unsorted element X
    'extract' the element X
    for j <- lastSortedIndex down to 0
      if current element j > X
        move sorted element to the right by 1
    break loop and insert X here
end insertionSort

Code:

![Screenshot (31)](https://user-images.githubusercontent.com/129615692/229310052-6756294f-31b8-40e4-8598-50a23e53456c.png)

Sample Output:

![Screenshot (32)](https://user-images.githubusercontent.com/129615692/229310069-ebb84b75-b2df-4e90-8b37-d8c3e2452562.png)




