# Assignment 1 - Data Structures (Lists & Tuples, Sets, Dictionaries, Operations)

## Overview
This notebook covers fundamental Python data structures including Lists, Tuples, Sets, and Dictionaries, along with practical operations on each data type. A practical use case involving an electronics product catalog is used throughout to demonstrate real-world applications.

## Tasks Breakdown

### Task 1: Product Collections (Lists & Tuples)
Learn how to work with Lists and Tuples through a product inventory example.

**Topics Covered:**
- Creating a list of product names
- Creating tuples for product details (name, price, category)
- Accessing list elements by index and negative indexing
- Appending new products to a list
- Converting between tuples and lists
- Data type identification using `type()`

**Key Concepts:**
- Lists are mutable (can be modified)
- Tuples are immutable (cannot be modified after creation)
- Indexing: 0-based for first element, -1 for last element
- Slicing and element access

---

### Task 2: Sets
Understand Sets and their operations for managing unique categories.

**Topics Covered:**
- Creating a set from a list
- Adding elements to a set using `.add()`
- Checking membership with `in` operator
- Getting the count of unique elements
- Set properties: unordered, no duplicates

**Key Concepts:**
- Sets automatically exclude duplicate values
- Sets are useful for membership tests
- No indexing in sets (unordered collection)

---

### Task 3: Dictionary
Work with Dictionaries for key-value pair storage and manipulation.

**Topics Covered:**
- Creating a dictionary with product names as keys and prices as values
- Updating dictionary values
- Adding new key-value pairs
- Deleting entries from a dictionary
- Computing aggregate values (average, min, max)
- Using `.values()` and dictionary methods

**Key Concepts:**
- Dictionaries store key-value pairs
- Keys must be unique and immutable
- Fast lookup by key
- Useful for storing related data

---

### Task 4: Combined Data Structures
Integrate multiple data structures into a practical catalog system.

**Topics Covered:**
- Creating a list of tuples using `zip()`
- Building mappings between categories and products
- Counting occurrences in a dataset
- Finding the category with the maximum number of products
- Modifying tuples in a list

**Key Concepts:**
- `zip()` combines multiple iterables element-by-element
- Nested data structures for complex data organization
- Counting and aggregation operations
- Using `max()` with custom key functions