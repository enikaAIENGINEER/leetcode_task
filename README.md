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
## DAY 8
    PROBLEM TITLE:
        REVERSE STRING
    CODE EXPLANATION:
        -The reverseString() function reverses the given list of characters using Python's built-in reverse() method.
        -The reverse() method changes the original list directly (in-place), so no new list is created.
        -Since it modifies the input itself, the function does not need to return any value.

----------------------------------------------------------------------------------------------------
## DAY 9
    PROMBLEM TITLE:
        REMOVE DUPLICATES FROM SORTED ARRAY
    CODE EXPLANATION:
        -The removeDuplicates() function removes duplicate elements from a sorted list by keeping only the unique values at the beginning of the same list.
        -It uses the variable k to track the position where the next unique element should be placed.
        -As it scans the list, each new unique element is copied to the correct position, and finally k is returned as the total number of unique elements.

----------------------------------------------------------------------------------------------------
## DAY 10
    PROBLEM TITLE:
        REMOVE ELEMENT
    CODE EXPLANATION:
        -The removeElement() function removes all occurrences of the given value val from the list by shifting the remaining elements to the front of the same list.
        -It uses the variable k to keep track of the position where the next valid element should be placed.
        -As the list is traversed, only the elements that are not equal to val are copied, and finally k is returned as the number of remaining elements.

----------------------------------------------------------------------------------------------------
## DAY 11
    PROBLEM TITLE:
        FIND THE INDEX OF THE FIRST OCCURRENCE IN A STRING
    CODE EXPLANATION:
        -The removeElement() function removes all occurrences of the given value val from the list by moving the remaining elements to the front of the same list.
        -It uses the variable k to track the position of valid elements and returns k as the number of elements left after removal.

----------------------------------------------------------------------------------------------------
## DAY 12
    PROBLEM TITLE:
        SEARCH INSERT POSITION
    CODE EXPLANATION:
        -The searchInsert() function uses the binary search technique to find the position of the target element in a sorted list.
        -If the target is found, it returns its index; otherwise, it returns the position where the target should be inserted to keep the list sorted.

----------------------------------------------------------------------------------------------------