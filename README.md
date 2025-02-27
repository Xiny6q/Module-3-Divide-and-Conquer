Download link :https://programming.engineering/product/module-3-divide-and-conquer/

# Module-3-Divide-and-Conquer
Module 3: Divide and Conquer
This homework will ask you to think about Divide and Conquer Algorithms with a focus on recurrence relations. Please try to follow the guidelines below when writing up your solutions to these problems:

Algorithm descriptions should be about 1 paragraph long. If you are writing more than one paragraph to describe your algorithm, then it is TOO long.

There should be enough detail that I could implement the algorithm if I wanted to, but we don’t need to see code. If you want to add pseudo-code for clarity, that would be fine.

For the recurrence relation problems below, make sure to show your work clearly!

You are a hacker, trying to gain information on a secret array of size n. This array contains n 1 ones and exactly 1 two; you want to determine the index of the two in the array.

Unfortunately, you don’t have access to the array directly; instead, you have access to a function f(l1; l2) that compares the sum of the elements of the secret array whose indices are in l1 to those in l2. This function returns 1 if the l1 sum is larger, 0 if they are equal, and 1 if the sum corresponding to l2 is larger.

For example, if the array is a = [1; 1; 1; 2; 1; 1] and you call f([0; 2; 4]; [1; 3; 5]) then the re-turn value is 1 because a[0] + a[2] + a[4] = 3 < 4 = a[1] + a[3] + a[5]. Design an algorithm to find the index of the 2 in the array using the least number of calls to f(). Then, answer the following questions:

Describe your algorithm clearly (in a paragraph or so)

Give the recurrence relation for the runtime of your algorithm. Make sure to write this in terms of fr, which we will use to represent the runtime of f().

Suppose you discover that f() runs in (max(jl1j; jl2j)), what is the overall runtime of your algorithm in this case?

Directly solve, by unrolling the recurrence, the following relation to find its exact solution. Make sure to show your work.

2. T (n) = T (n 1) + n

Use induction to show bounds on the following recurrence relation.

Show that T (n) = 4T (n3 ) + n 2 O(nlog3(4)). You’ll need to subtract off a lower-order term to make the induction work here.

CS 3100: DSA2 Page 2 of 2 Fall 2022

Use the master theorem to solve the following recurrence relations. State which case of the theorem you are using and why.

T (n) = 2T (n4 ) + 1

p

5. T (n) = 2T (n ) + n

4

6. T (n) = 2T (n4 ) + n

7. T (n) = 2T (n4 ) + n2
