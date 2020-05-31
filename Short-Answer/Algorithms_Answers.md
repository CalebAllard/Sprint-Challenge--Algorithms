#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n), Since it is just one while loop. 


b)O(n^2), The for loop, and itteration through the range, as well as the second while loop. git it the n^2


c)O(1), this is just taking a value checking and returning it, with an addition to it. The value will have to be incredibly large to start making it go slower, with how math is computed

## Exercise II

Split the building in half and start at the middle floor
Drop egg, if egg brakes split lower half of building and repeat
    if egg does not brake do the same with upper half split the building
rinse and repeat untill you find highest floor were the egg does not break.

This would be a O(n log n) because after each itteration the amount of opperations is cut in half.
