# Whiteboard Problem

This is a whiteboard coding challenge that I recently attempted. The task is to sort a given array so that
certain nonunique elements are located at given indices in an array and then return that array. 

## set up
There are three input variables for this problem:
  * *product placement n* which appear randomly in the array *suggested*
  * *index* - an array of integers that designate at which index a *product placement n* needs to occupy in *suggested*
  * *suggested* - the array of objects which includes both *product placement n* and other objects

## problem
The problem is that the *product placements n* are not located in their proper places within the *suggested* array. The problem is to reorganize *suggested* array so that at each index listed in the *index* array there is a *product placement n*.

## assumptions
 For purposes of this problem, we may assume that the number of n elements in the unsorted array is equal to len(index). 
 In other words, you don't need to worry about cases where there are too many n elements in the suggested array or not enough
 Also, the correct solution will minimize disruption to the unsorted array suggested. Move elements around as least as possible. 
 
 ## example
 To solve this problem, I created the following example.
 * n is the string "B"
 * index = [2, 5, 9, 13]
 * suggested = [ "1", "2", "4", "5", "B", "B", "7", "8", "B", "9", "10", "11", "B", "12"]
 
 The desired output should equal ["1", "2", "B", "4", "5", "B", "7", "8", "9", "10", "11", "12", "B"]

## solution 
My solution is in the other file in this repository. There is a functioning Python function along with comments that explain my thought process. Best case runtime is O(n) and worst case runtime is O(n log n). 
