# Analysis of Algorithm :

## Best, Worst, Expected Case :

Sometimes we get lucky in life. Exam cancelled when you were not prepared,surprise test when you were prepared etc. => **Best Case**

Sometimes we get unlucky.Questions you never prepared asked in exams, rain during cricket match etc. => **Worst Case**

---

Consider an array which is sorted in increasing order 

| 1 | 7 | 18 | 28 | 50 | 180 |

we have to search a given number in this array and report whether its present in the array or not.

### Algorithm 1 :
Start from first element untill an element greater than or equal to the number to be searched is found.

### Algorithm 2 :
Check whether the first or the last element is equal to the  number. If not find the number between these two elements(center of the array).If the center element is greater than the number to be searched, repeat the process for first half else repeat for second half until the number is found.

---
## Space Complexity :
Time is not the only thing we worry about while analyzing algorithms. Space is equally important.

> Greating an array of size n -> O(n) space......n is the size of input

If a function calls itself recursively n times its space complexity is O(n).

---
## Techniques to Calculate Time Complexity :

Once we are able to write the runtime in terms of size of the **input(n)**, we can find the time complexity.

For example,
> T(n) = n2 = O(n2)

> T(n) = log n = O(log n)

---
### Some tricks to calculate complexity :
* Drop the constants
* Drop the non dominant terms
* Consider all variables which are provided as input.