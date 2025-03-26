# Find-the-Longest-Consecutive-Sequence-in-an-Array
Given an unsorted array of integers, find the length of the longest consecutive sequence of numbers.  Constraints:
Explanation:
Store all numbers in a HashSet for O(1) lookups.

Iterate through the numbers and check if num - 1 exists.

If num - 1 doesn't exist, this means num is the start of a new sequence.

Expand the sequence forward (num + 1, num + 2, ...) and keep track of its length.

Update the longestStreak whenever a longer sequence is found.

Time Complexity: O(n), since each number is visited once.
Space Complexity: O(n), for storing elements in a HashSet.
