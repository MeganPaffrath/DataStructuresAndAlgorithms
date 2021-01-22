# Searching

- Searching in unordered array : O(n)
  - iterate through until item found = o(n)
- Searching in ordered array : O(log(n))
  - first look at an item in middle of array
    - floor( [ maxIndex + minIndex ] / 2 )
  - if item should be to the right
    - floor( [maxIndex + minIndex ] / 2 ), where max and min are right of the last checked item
  - if item should be to the left
    - floor( [maxIndex + minIndex ] / 2 ), where max and min are left of the last checked item
  - keep searching left and right until item either found or not found
