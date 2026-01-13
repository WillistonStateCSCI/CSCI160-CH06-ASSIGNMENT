# CSCI160-CH06-EXERCISES
Programming Exercises From Java Illuminated Book by Anderson and Franceschi
## Q06_44 Instructions  
Write a program that expects a word containing the @ character as an input.  If the word does not contain an @ character, then your program should keep prompting the user for a word.  When the user types in a word containing an @ character, the program should simply print the word and terminate.  
### Q06_44 Test 1
**Input:**  
P@ssword  
**Output:**  
P@ssword contains an @
### Q06_44 Test 2
**Input:**  
Password  
Password  
P@ssword  
**Output:**  
P@ssword contains an @
## 0Q6_47 Instructions  
Write a program that uses a *for* loop to output the product of all the integers between 10 and 20, inclusive, that is 10 + 11 + 12 + ... + 19 + 20.  
### Q06_47 Test 
**Input:**  
*none*   
**Output:**  
The product of the integers from 3 to 7 is 2520  
## Q06_48 Instructions  
Write a program that uses a *for* loop t count how many multiples of 7 are between 33 and 97, inclusive.  
### Q06_48 Test 
**Input:**  
*none*   
**Output:**  
35 is a multiple of 7  
42 is a multiple of 7  
49 is a multiple of 7  
56 is a multiple of 7  
63 is a multiple of 7  
70 is a multiple of 7  
77 is a multiple of 7  
84 is a multiple of 7  
91 is a multiple of 7  
The number of multiples of 7 between 33 and 97 is 9  
## Q06_50 Instructions  
Write a program that takes a word as an input from the keyboard and outputs each character in the word, separated by a space.  
### Q06_50 Test 1  
**Input:**  
PaSsWoRd  
**Output:**  
P a S s W o R d  
### Q06_50 Test 2
**Input:**  
pAsSwOrD  
**Output:**  
p A s S w O r D  
## Q06_51 Instructions  
Write a program that takes a value as an input from the keyboard and outputs the factorial of that number.  For example, the factorial of 4 is 4 * 3 * 2 * 1, or 24.  
### Q06_51 Test 1  
**Input:**  
6  
**Output:**  
The factorial of 6 is 720  
### Q06_51 Test 2  
**Input:**  
12    
**Output:**  
The factorial of 12 is 479001600  
## Q06_53 Instructions  
Alter the code from Example 6.14 (the one that counts the tokens in a sentence), so that it prints each token and counts the number of tokens.  
### Q06_53 Test 1   
**Input:**  
It was the best of times, it was the worst of times.  
**Output:**  
It  
was  
the  
best  
of  
times,  
it  
was  
the  
worst  
of  
times.  
The sentence contains 12 tokens.  
### Q06_53 Test 2   
**Input:**  
Knock Knock, Neo!  
**Output:**  
Knock  
Knock,  
Neo!  
The sentence contains 3 tokens.  
## Q06_54 Instructions  
Write a program that inputs a word representing a binary number (0's and 1's). First your program should verify that it is indeed a binary number, that is, th enumber contains only 0's and 1's.  If that is not the case, your program should print a message that the number is not a valid binary number.  Then, your program should count how many 1's are in that word and output the count.  
### Q06_54 Test 1   
**Input:**  
12345  
**Output:**  
Invalid binary number  
### Q06_54 Test 2   
**Input:**  
10101  
**Output:**  
The count of 1's is 3  
### Q06_54 Test 3   
**Input:**  
00000  
**Output:**  
The count of 1's is 0  
## Q06_59 Instructions  
Write a program that inputs 7 double values from the provided file *dja.txt*.  Your program should output the lowest value for those 7 days and the number of the day on which the lowest value occurred.  For this program, instead of setting the initial minimum value to the first value in the file, use the maximum value for a *double*.  (Note: Do not change the numbers in dja.txt or you will fail the tests).  
### Q06_59 Test   
**Input:**  
*none*  
**Output:**  
The minimum value for the Dow Jones Average was 14253.0 and occurred on day 1.  