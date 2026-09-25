# Day-108-Sorted-Descending
# Python Day 108 - Sorted Descending

This program uses the `sorted()` function with `reverse=True` to arrange a list of numbers in descending order.

## Example

Original list:

```text
[20, 50, 10, 40, 30]
```

Descending list:

```text
[50, 40, 30, 20, 10]
```

The original list remains unchanged.

## Concepts Used

* List
* `sorted()` function
* `reverse=True`
* Variables
* Descending order

## How It Works

1. A list of numbers is created.
2. The original list is displayed.
3. `sorted()` creates a new sorted list.
4. `reverse=True` arranges the numbers from largest to smallest.
5. The sorted list is displayed.
6. The original list remains unchanged.

## Python Code

```python
numbers = [20, 50, 10, 40, 30]

print("Original list:", numbers)

sorted_numbers = sorted(numbers, reverse=True)

print("Descending list:", sorted_numbers)
print("Original list:", numbers)
```

## Output

```text
Original list: [20, 50, 10, 40, 30]
Descending list: [50, 40, 30, 20, 10]
Original list: [20, 50, 10, 40, 30]
```

## Goal

The goal of this project is to understand how `sorted()` and `reverse=True` can be used to create a descending sorted list without changing the original list.
