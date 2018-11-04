# Whiteboard Problem

This is a whiteboard coding challenge that I recently attempted. The task is to sort a given array so that
certain nonunique elements are located at given indices in an array and then return that array. 

## set up
There are three input variables for this problem:
  * *Product Placements* which appear randomly in the array *Suggested*
  * *Index* - an array of integers that designate at which index a *Product Placements* needs to occupy in *Suggested*
  * *Suggested* - the array of objects which includes both *Product Placements n* and other objects

## problem
The problem is that the *Product Placements* are not located in their proper places within the *Suggested* array. The problem is to reorganize *Suggested* array so that at each index listed in the *Index* array there is a *Product Placements*.

## assumptions
 For purposes of this problem, we may assume that the number of n elements in the unsorted array is equal to len(index). 
 In other words, you don't need to worry about cases where there are too many n elements in the suggested array or not enough
 Also, the correct solution will minimize disruption to the unsorted array suggested. Move elements around as least as possible. 
 
 ## example
 To solve this problem, I created the following test cases.
 * Product Placements are represented in the Suggested array by the string "B"
 * Index = [2, 5, 9, 13]
 
 And three different arrays:
 * Suggested Array 1 = [ "1", "2", "4", "5", "B", "B", "7", "8", "B", "9", "10", "11", "B", "12"]
 * Suggested Array 2 = [ "1", "2", "4", "5", "7", "8", "9", "10", "11", "12", "B", "B", "B", "B"]
 * Suggested Array 3 = [ "B", "B", "B", "B", "1", "2", "4", "5", "7", "8", "9", "10", "11", "12"]
 
 For each of the three test cases, the output should equal ["1", "2", "B", "4", "5", "B", "7", "8", "9", "B", "10", "11", "12", "B"] The Product Placements are successfully moved to the indices of 2, 5, 9, and 13, and the rest of the elements are kept in order relative to one another.

## solution 
My solution is in the other file in this repository. There is a functioning Python function along with comments that explain my thought process. 
