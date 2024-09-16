# List-manipulation
# Script that perform various list operations

def list_operations(numbers):
    sorted_ascending = sorted(numbers)
    print(f"Sorted List (Ascending): {sorted_ascending}")

    sorted_descending = sorted(numbers, reverse=True)
    print(f"Sorted List (Descending): {sorted_descending}")

    largest = max(numbers)
    print(f"Largest Number: {largest}")

    smallest = min(numbers)
    print(f"Smallest Number: {smallest}")

    total_sum = sum(numbers)
    print(f"Sum of Numbers: {total_sum}")


user_input = input("Enter your numbers separated by spaces: ")

numbers = list(map(int, user_input.split()))

list_operations(numbers)


