**Merge Sort** is a divide and conquer algorithm. It takes two steps:
```
1) splitting the original list into smaller sorted lists recursively until there is only 1 element in the list,
2) merging back the presorted 1-element lists into 2-element lists, 4-element lists, and so on recursively.

```

## Merge Sort Implementation in Python

We can implement the Merge Sort algorithm in Python using two functions **merge_sort(lst)**, the main function and **merge(left, right)**, a helper function.
