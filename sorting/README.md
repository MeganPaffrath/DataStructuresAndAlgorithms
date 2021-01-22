# Sorting

[Return](../README.md)

# Sort Analysis

| Sort type      | Worst Case | Comments                                                              |
| -------------- | ---------- | --------------------------------------------------------------------- |
| Bubble Sort    | O(n^2)     | The most inefficient                                                  |
| Selection Sort | O(n^2)     | Better than bubble sort, running time is independent of element order |
| Insertion Sort | O(n^2)     | Good for small lists and partially sorted lists                       |

# Sorts

## Bubble Sort

- Time complexity: O(n^2)
- Pseudo code

```
for i=0 to arr.length-2
  for j=0 to arr.length-2-i
    if arr[j] > arr[j+1]
      temp = arr[j+1]
      arr[j+1] = arr[j]
      a[j] = temp
```

## Selection Sort:

- Time complexity: O(n^2)
- For each element, swap with the following smallest element
- Pseudo code

  ```
  for i=0 to array.length - 2
    minIndex = i
    for j=i to array.length - 2
      if (array[j] < array[minIndex])
        minIndex = j
    temp = array[i]
    array[i] = array[minIndex]
    array[minIndex] = temp

  ```

## Insertion Sort

- Time complexity: O(n^2)
- For each element, figure out what order it should be placed in in relation to the elements before that element
- Pseudo code
  ```
  for i=0 to arr.length-1
    curr = arr[i]
    j = i-1
    while j >= 0 && arr[j] > curr
      arr[j+1] = arr[j]
      j = j - 1
    arr[j+1] = curr
  ```
