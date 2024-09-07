# Interview_Coding
Interview Coding Test
1. write a function that takes a string and return the same string with no duplicate characters while parsing from left to right . Retain the order of character from left to right for example input string "aaa bb accbd"should return "abcd". do not use inbuild function


2. you are given a list of integer representing stock prices over a series of day. Write a function in C# to find the maximum profit you could have retrospectively from buying and selling this stock, given below rules:
A buy should be followed by a sell before you can rebuy from next day onwards
Unlimited number of transaction are allowed, but only single buy or sell on a day is allowed 
for example, daily stock prices for 10 days are {7, 3, 2, 5, 6, 3, 7, 4, 1, 10} , what will be transaction and the resuling maz profits ?



3. you are given two arrays of integer who are relates to each other as:
   
  i). First array contains employee ids of all the organiztion
  ii). second array contains employee ids of their managers at the same index of the first array
     for each index in the first employee array, the corresponding index in the second array given that employees manager id

guarantees
  1. Each Employee has a single manager
  2. Each manager is also an employee
  3. each manager can have zero or more employee under 
  4. Only one employee does not have a manager. for that employee the corresponding index in the second array contains-1

your task is to print the hierarchy of the organization
  1. Second row prints all the employee ids whose manager is the CEO, separated by whitespace
  2. Thrird row prints all employee ids whoes manager are the employees of the second row

so on and so forth

example

Employee ids [1, 49, 29, 95, 90, 10, 24, 84, 17,19,6]
 Manager Id [-1, 17, 6, 49, 29, 1, 6, 29, 10,6,1]

write a function in C# that will print employee hierarchy as
1
10 6
17 29 24 19
49 90 84
etc

solve by using arrays of numbers and no other data structure or inbuild function




4. 
If M encountered replace the M with previous character
If N encountered remove the N and next character
Some Examples:    INput: abcNdgM      Output: abcgg
                  Input: MrtyNNg      Output: rtyg


5.
