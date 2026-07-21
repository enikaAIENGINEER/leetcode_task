## DAY 1
    PROBLEM TITLE:
        TWO SUM
    CODE EXPLANATION:
        -I used a dictionary to store the numbers along with their indexes while checking each element in the list.  
        -I used the `enumerate()` function to get both index and value, and calculated the complement using `target - num`.  
        -If the complement is already available in the dictionary, I return the indexes of both numbers. Otherwise, I store the current number and its index and continue checking.  
        -If no pair is found, the code returns an empty list.

------------------------------------------------------------------------------------------