# Hitler Sort / Führer Sort
a joke sorting algorithm based on hitler's logic (beacuse i was bored)
> [!IMPORTANT]
> this is just for joke and you should not take it seriously

## How it works?
the algorith invades or rather iterates through the array and for each element checks if element value is equal to its index append it to the sorted
array otherwise dominate it

```python
def hitler_sort(arr):

    # 1. Invasion Phase: Assume all elements are potential threats
    sorted_arr = []
    for i in range(len(arr)):

        # 2. Purge and Dominate: Check each element
        if i == arr[i]:
            sorted_arr.append(arr[i])

    return sorted_arr
```
and to use it:

```
>>> hitler_sort([3,1,5,7,4,0,-10,6])
[1, 4]
>>> 
```

the output array is always sorted even without any comparison between array elemnts but it cant sort nagtive values since index values are not nagtive at all (and the fürher is happy about it)
