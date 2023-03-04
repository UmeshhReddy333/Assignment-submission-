# Assignments submission
def find_smallest_number(lst):
    smallest = lst[0] # Initialize the smallest number as the first element of the list
    for num in lst:
        if num < smallest:
            smallest = num
    return smallest

# Example usage:
list1 = [5, 7, 9, 14, 10, 20, 4]
print(find_smallest_number(list1)) # Output: 4
