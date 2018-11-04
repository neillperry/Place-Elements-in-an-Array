# Whiteboard Problem

This is a whiteboard coding challenge that I recently attempted. The task is to sort a given array so that
certain nonunique elements are located at given indices in an array and then return that array. 

## set up
There are three input variables for this problem:
  * *Product Placements n* which appear randomly in the array *Suggested*
  * *Index* - an array of integers that designate at which index a *Product Placements n* needs to occupy in *Suggested*
  * *Suggested* - the array of objects which includes both *Product Placements n* and other objects

## problem
The problem is that the *Product Placements n* are not located in their proper places within the *Suggested* array. The problem is to reorganize *Suggested* array so that at each index listed in the *Index* array there is a *Product Placements n*.

## assumptions
 For purposes of this problem, we may assume that the number of n elements in the unsorted array is equal to len(index). 
 In other words, you don't need to worry about cases where there are too many n elements in the suggested array or not enough
 Also, the correct solution will minimize disruption to the unsorted array suggested. Move elements around as least as possible. 
 
 ## example
 To solve this problem, I created the following example.
 * Product Placements are n are represented by the string "B"
 * Index = [2, 5, 9, 13]
 * suggested = [ "1", "2", "4", "5", "B", "B", "7", "8", "B", "9", "10", "11", "B", "12"]
 
 The desired output should equal ["1", "2", "B", "4", "5", "B", "7", "8", "9", "B", "10", "11", "12", "B"]

## solution 
My solution is in the other file in this repository. There is a functioning Python function along with comments that explain my thought process. 
