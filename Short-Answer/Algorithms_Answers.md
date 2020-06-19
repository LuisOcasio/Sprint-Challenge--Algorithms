#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)o(n), linear

b)o(n2), 2x loops

c)o(n), recursive

## Exercise II

#step 1
#we have a building
#floor = n
#we have plenty of eggs
#egg breaks when thrown from floor 'f' or higher
#will not break if thrown from lower than floor 'f' or lower

#step 2
#given a 'starting point'
#given 2 distinct values
#keep those values seperate

#step 3
#one approach that comes to mind is a binary search tree
#we have the floor we are on which represents the parent node
#left node == eggs broken from < 'f'
#right node == eggs broken from > 'f'

#step 4
#this approach will have a runtime complexity of Θ(log(n))
