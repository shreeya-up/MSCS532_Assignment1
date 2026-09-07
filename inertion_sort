def insertion_sort(arr):
    """Divides the array into two parts: sorted and unsorted. 
    Compares a key with the sorted sublist from right to left"""
    for i in range (1, len(arr)):
        key = arr[i]
        j = i - 1
        while j >= 0 and arr[j] < key:
            arr[j + 1] = arr[j]
            j -= 1
        arr[j + 1] = key