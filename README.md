# Leetcode 859. Buddy Strings (Easy)

# Problem 

Given two strings s and goal, return true if you can swap two letters in s so the result is equal to goal, otherwise, return false.

Swapping letters is defined as taking two indices i and j (0-indexed) such that i != j and swapping the characters at s[i] and s[j].

For example, swapping at indices 0 and 2 in "abcd" results in "cbad".

# Solution O(N)

First if the strings are different lengths then return False. Next iterate through the strings keeping track of any mismatched characters between the two strings. if there are exactly 2 differences of characters swapped then return true. Or return true if there are no differences, but there are duplicate characters which could be swapped but not change the strings.
