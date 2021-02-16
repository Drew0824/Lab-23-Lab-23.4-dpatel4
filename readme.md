## Processing temperatures in a partially filled array

Write a program that will input temperatures for consecutive days. It is similar to lab 22.4, except now **the user will input the number of temperatures to be read.** There will be no more than 50 temperatures. 

The program will store these values into an array and then average all the temperatures. It will also determine the highest temperature and the lowest temperature. The average should be displayed to two decimal places.

Don't forget Display 7-1 in the textbook has an example of finding a maximum value. Finding a minimum is similar.

_Sample Run:_
Please input the number of temperatures to be read
5
Input temperature 1:
68
Input temperature 2:
75
Input temperature 3:
36
Input temperature 4:
91
Input temperature 5:
84
The average temperature is 70.80
The highest temperature is 91.00
The lowest temperature is 36.00

## Optional Step

Because the array is declared to be size 50, the user should not be allowed to enter more than 50 numbers. Add an input validation loop to the program so that it will not allow the user to enter a number larger than 50 when prompted for the number of temperatures to be read.