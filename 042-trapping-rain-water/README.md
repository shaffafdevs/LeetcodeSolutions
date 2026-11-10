# LC 42 - Trapping Rain Water

Problem: https://leetcode.com/problems/trapping-rain-water/

## About this solution
This is my first LeetCode problem, and I did not come up with this
solution on my own. It is the standard two-pointer approach, and I got
help from an AI assistant to understand it. I understand the problem
and the idea, and I've worked through the code line by line with dry runs.

## Approach
- Two pointers, `left` and `right`, start at the two ends.
- `leftMax` and `rightMax` track the tallest wall seen so far on each side.
- Each step, I handle the side with the shorter bar, because that side
  decides the water level.
- If the bar is shorter than its side's max, the water on it is
  `max - height`. Otherwise it becomes the new max.

## Complexity
- Time: O(n), each bar is visited once
- Space: O(1)

## What I learned
- How `main` lets me run Java code on my own computer
- Array indexing starts at 0, so the last position is `n-1`
