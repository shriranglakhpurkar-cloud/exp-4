NAME-SHRIRANG LAKHPURKAR 

PRN-25070123108

CLASS-ENTC B2




Python Sets & Frozenseta
1. What is a Set?

A set is a built-in Python data structure used to store multiple unique elements in a single variable.

Key characteristics:

Unordered – elements do not have a fixed position

Unindexed – elements cannot be accessed using index numbers

Mutable – elements can be added or removed

No duplicates allowed – repeated values are stored only once

Because sets are unordered, the output order may differ every time.

2. Why Sets Are Not Subscriptable

Sets do not support indexing because:

They do not maintain element order

There is no concept of “first” or “second” element

Hence, accessing elements using an index is not allowed and results in an error.

3. Duplicate Handling in Sets

When duplicate elements are added:

Only one instance of the value is stored

This applies to values that are logically equal (for example, True and 1 are considered the same)

This makes sets useful for removing duplicates from data.

4. Mixed Data Types in Sets

A set can store:

Strings

Numbers

Boolean values

However:

Duplicate or equivalent values are automatically eliminated

Order is still not guaranteed

5. Adding Elements to a Set

Sets allow elements to be added after creation.

Important points:

Only one element can be added at a time

If the element already exists, the set remains unchanged

6. Removing Elements from a Set

There are two main ways to remove elements:

Remove: Raises an error if the element is not present

Discard: Does not raise an error if the element is missing

This makes discard safer when you are unsure whether the element exists.

7. Set Operations

Sets support powerful mathematical operations:

Union

Combines elements from both sets

Removes duplicates automatically

Intersection

Returns elements common to all sets involved

Difference

Returns elements present in one set but not the other

Symmetric Difference

Returns elements that are in only one of the sets, not both

These operations are widely used in comparisons, filtering, and data analysis.

8. Frozenset

A frozenset is an immutable version of a set.

Characteristics:

Unordered

No duplicates

Immutable (cannot add or remove elements)

Supports all set operations like union and intersection

Because it is immutable, it does not support methods like adding or removing elements.

9. Converting Other Collections to Sets

Sets are often used to:

Convert lists or tuples into sets

Remove duplicate entries efficiently

This is especially useful in attendance lists, participant lists, or data cleanup tasks.

10. Practical Use Cases of Sets

Sets are commonly used for:

Finding unique participants

Identifying common subjects among students

Comparing memberships (clubs, groups, teams)

Finding absent or present elements

Performing fast membership tests

11. Algorithm: Removing Duplicates from a List

Steps:

Take a list containing repeated elements

Convert the list into a set

The set automatically removes duplicates

Use the result as unique data

12. Algorithm: Finding Common Elements Between Multiple Sets

Steps:

Store data for each group in separate sets

Apply intersection operation

The result contains only common elements

13. Algorithm: Finding Exclusive Members

Steps:

Create sets for each group

Use difference to find exclusive members

Use symmetric difference to find elements present in only one group
