# Week 6 Quiz

## All questions carry equal weightage. All Python code is assumed to be executed using Python3. You may submit as many times as you like within the deadline. Your final submission will be graded.

# Note:

- If the question asks about a value of type string, remember to enclose your answer in single or double quotes.
- If the question asks about a value of type list, remember to enclose your answer in square brackets and use commas to separate list items.

## Suppose u and v both denote sets in Python. What is the most general condition that guarantees that u - (v - u) == u?

- The sets u and v should be disjoint. 
- The set u should be a subset of the set v. (correct)
- The set v should be a subset of the set u.
- This is true for any u and v.

### Explanation: If v is a subset of u, then v - u is an empty set. Hence, u - (v - u) equals u - ∅, which equals u.

<!-- Feedback:
At statement 7, w[1] is the string "mimsy", which cannot be updated in place.

Accepted Answers:
(Type: Numeric) 7 -->

## Suppose u and v both denote sets in Python. What is the most general condition that guarantees that u|v == u^v?

- The sets u and v should be disjoint. (correct)
- The set u should be a subset of the set v. 
- The set v should be a subset of the set u.
- This is true for any u and v.

### Explanation: If u and v are disjoint, then their union (u|v) equals their symmetric difference (u^v), because there are no common elements.

## Suppose we insert 19 into the min heap [17,25,42,67,38,89,54,98,89]. What is the resulting heap?

### [17,19,25,42,67,38,89,54,98,89]

Explanation: The inserted element 19 is placed in the correct position to maintain the heap property.


## Suppose we execute delete-min twice on the min-heap [13,29,24,67,52,89,45,98,79,58]. What is the resulting heap?

### [24,67,52,89,45,98,79,58]

Explanation: After removing the minimum element 13, the heap is [24,29,45,67,52,89,58,98,79]. Then, removing the new minimum 24 results in the given heap.

## Note: The heap property requires the parent node to be smaller (or larger) than its child nodes. The exact ordering of elements at the same level is not specified.
