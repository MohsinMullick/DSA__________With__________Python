def sum_of_array(arr):
    """
    Problem: Find the sum of all elements in an array
    Approach: Traverse the array and add elements one by one
    Time Complexity: O(n)
    Space Complexity: O(1)
    """
    total = 0
    for num in arr:
        total += num
    return total

arr = [10, 20, 30]
print("Sum of array:", sum_of_array(arr))

