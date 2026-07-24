## DAY 1
    PROBLEM TITLE:
        TWO SUM
    CODE EXPLANATION:
        -I used a dictionary to store the numbers along with their indexes while checking each element in the list.  
        -I used the `enumerate()` function to get both index and value, and calculated the complement using `target - num`.  
        -If the complement is already available in the dictionary, I return the indexes of both numbers. Otherwise, I store the current number and its index and continue checking.  
        -If no pair is found, the code returns an empty list.

------------------------------------------------------------------------------------------
## DAY 2
PROBLEM TITLE:
    ADD TWO NUMBERS
CODE EXPLANATION:
    -This code adds two numbers stored as linked lists by going through each node one by one.
    -It adds the corresponding values along with any carry from the previous addition, creates a new node for the result digit, and moves to the next nodes.
    -Finally, it returns the new linked list, which represents the sum of the two numbers.

-------------------------------------------------------------------------------------------
## DAY 3
PROBLEM TITLE:
    PALINDROME NUMBER
CODE EXPLANATION:
    -This code checks whether a given number is a palindrome by reversing its digits and comparing the reversed number with the original.
    -It first rejects negative numbers and numbers ending in 0 (except 0 itself), as they cannot be palindromes.
    -If both numbers are equal after reversing, it returns True; otherwise, it returns False.

----------------------------------------------------------------------------------------------------
## DAY 4
PROBLEM TITLE:
    ROMAN TO INTEGER
CODE EXPLANATION:
    -This code converts a Roman numeral into an integer by reading the characters from right to left and finding their values using a dictionary.
    -If the current Roman numeral is smaller than the previous one, it subtracts its value; otherwise, it adds it to the total.
    -Finally, it returns the calculated integer value.