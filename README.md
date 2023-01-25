# Internet-Banking-System
***A system that offers users almost every service traditionally available through a local branch.***

## Problem Definition
  To device a code to access your bank account and carry out financial transactions through the internet, that enhances the normal banking experience as it is quick, free and allows us to carry out a number of tasks without actually having to visit your bank or ATM. It maintains a validated transaction tracking record and history. It reduces the chances of unwanted risk factor. Passwords are protected by using encryption.
  A user can create an account by providing the name of the account holder, account number, select amount type whether it’s Saving account or Current account and providing an initial amount. For certain purpose, he/she can also check for the balance inquiry which displays the account holder’s name with account number type and amount. He/she can also check for all the account holder’s list.

## Programming language
The code of this project is in C programming language.

## Tools and Techniques (Data Structures and Algorithms)

-	***File Data Structure*** is used to minimize the access time and the storage space. We used files to store details of account holders. File Handling helps in preserving the data or information generated after running the program. There are certain programs that require a lot of input from the user, considering ours which involves internet banking we can easily access any part of the code with the help of certain commands. You can easily transfer the contents of a file from one computer system to another without having to worry about the loss of data.

-	Sorting the account holder details based on account number in their increasing order using ***INSERTION SORT*** (called gambler’s invention). It is a stable algorithm. Run time of insertion sort in the best case is O(n) but in the worst case and avg. Case is O(n^2). So, insertion sort is simple and less time consuming and have less overhead. So, insertion is better in best and worst case.

-	Sorted user’s information based on the amount present in their bank account by using ***QUICK SORT***. Even though quick-sort has a worst case run time of O(n2), quicksort is considered the best sorting because it is very efficient on the average: its expected running time is O(nlogn) where the constants are VERY SMALL compared to other sorting algorithms.

-	Usage of ***BRUTE FORCE STRING SEARCH*** to search for the nearest banks available to the user’s location. For successful search the pattern found at first is the best case with O(m)no of comparisons and O(m*n) no of comparisons for worst case when the pattern is found at last. For unsuccessful search the best is when the pattern is not found with O(n) complexity and the worst case is when the pattern is found but it is compared with O(nm).
