# Whiteboard Problem

This is a whiteboard coding challenge that I recently attempted. The task is to sort a given array so that
certain nonunique elements are located at predetermined indices in the array and then return that array. 

## set up
There are three input variables for this problem:
  * element n which appear randomly in the unsorted array *suggested*
  * index - an array of integers that designate at which index each element n needs to occupy in the suggested array
  * suggested - the unsorted array of objects which includes both the elements n and the other objects

## assumptions
 For purposes of this problem, you may assume that the number of n elements in the unsorted array is equal to len(index). 
 In other words, you don't need to worry about cases where there are too many n elements in the suggested array or not enough
 Also, the correct solution will minimize disruption to the unsorted array suggested. Move elements around as least as possible. 
 
 ## example
 To solve this problem, I created the following example.
 n is the string "B"
 index = [2, 5, 9, 13]
 suggested = [ "1", "2", "4", "5", "B", "B", "7", "8", "B", "9", "10", "11", "B", "12"]
 
 The desired output should equal ["1", "2", "B", "4", "5", "B", "7", "8", "9", "10", "11", "12", "B"]
