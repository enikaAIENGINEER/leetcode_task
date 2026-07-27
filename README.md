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

----------------------------------------------------------------------------------------------------
## DAY 5
    PROBLEM TITLE:
        LONGEST COMMON PREFIX
    CODE EXPLANATION:
        -This code finds the longest common prefix among all the strings in the list by starting with the first string as the initial prefix.
        -It compares this prefix with each remaining string and keeps removing the last character until all strings start with the same prefix.
        -Finally, it returns the longest common prefix, or an empty string if no common prefix exists.

----------------------------------------------------------------------------------------------------
## DAY 6
    PROBLEM TITLE:
        VALID PARANTHESES
    CODE EXPLANATION:
        -This code checks whether the brackets in the given string are balanced and in the correct order by using a stack.
        -It pushes every opening bracket onto the stack, and whenever it finds a closing bracket, it compares it with the most recent opening bracket.
        -If they don't match or the stack is empty, it returns False; otherwise, if the stack is empty at the end, it returns True.

----------------------------------------------------------------------------------------------------
## DAY 7
    PROBLEM TITLE:
        MERGE TWO SORTED LISTS
    CODE EXPLANATION:
        -This code merges two sorted linked lists into a single sorted linked list by comparing the current nodes of both lists.
        -It attaches the smaller node to the new list, moves that list's pointer forward, and repeats the process until one of the lists is exhausted.

----------------------------------------------------------------------------------------------------