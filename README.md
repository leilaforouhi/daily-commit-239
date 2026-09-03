def remove_duplicates(items):
    unique_items = []

    for item in items:
        if item not in unique_items:
            unique_items.append(item)

    return unique_items


if __name__ == "__main__":
    numbers = [4, 2, 4, 7, 2, 9, 7, 1]
    print("Original:", numbers)
    print("Without duplicates:", remove_duplicates(numbers))
