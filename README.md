# cis165-lab2
CIS-165 Lab 2 c+++ exercises on variables, arithmetic, output,testing and AI-assisted learning.

## Initial Plans

### Program1 - Sum of Two Numbers
I will store 50 and 100 in integer variables.I will add the two values and store the result in a variable named total. I will then display total with a clear label.

### Program 2 - Miles Per Gallon
I will store 312 miles and 16 gallons in variable. I will divide the miles by the gallons to calculate miles per gallon and store the result in a variable. I will use a data type that preserves the fractional result and display the result with MPG units.

## Testing

### Test 1 - Sum
-Values: 50 and 100
-Expected results: 150
-Actual output: Total: 150
-Match: Yes

### Test 2 - Sum
-Values: 25 and 75
-Expected result: 100
-Actual output: Total: 100
-Match: Yes

### Test 3 - Miles Per Gallon
- Values: 312 miles and 16 gallons
- Expected result : 19.5
- Actual output: Miles per gallon: 19.5 MPG
- Match Yes

### Test 4 - Miles Per Gallon
- Values: 250 miles and 12 gallons
- Expected result: 20.8333... MPG
- Actual output: 20.8333 MPG
- Match: Yes

## How to Compile and Run 
To compile the programs, I used the c++ compiler in Terminal.

For sum-3.cpp:
g++ -std=c++17 -Wall -Wextra sum-3.cpp -o sum [ I used sum-3.cpp because the first two I downloaded I made a mistake.after the third try of downloading I got this one right]
./sum
For mpg.cpp:
g++ -std=c++17 -Wall -Wextra mpg.cpp -o mpg
./mpg
### sum-3.cpp
The program stores 50 and 100 in integer variable.It adds the two values and stores the result in the variable total. The program then displays the total with a clear label.
### mpg.cpp
The program stores 312 miles and 16 gallons in double variables. It divides miles by gallons and stores the result in the mpg variable. The double data type preserve the decimal portion of the MPG result. The program then displays the MPG with its units.

# Final Verification 
-sum-3.cpp: 50 and 100
-mpg.cpp: 312 miles and 16 gallons
I reran both programs and verified the final results.
- sum-3.cpp: Total: 150
- mpg.cpp: Miles per gallon: 19.5 MPG

For sum-4.cpp:
g++ -std=c++17 -Wall -Wextra sum-4.cpp -o sum [ I used fourth try for the second tests.]
./sum
For mpg-2.cpp: [ second try for the second tests]
g++ -std=c++17 -Wall -Wextra mpg-2.cpp -o mpg
./mpg
### sum-3.cpp
The program stores 75 and 25 in integer variable.It adds the two values and stores the result in the variable total. The program then displays the total with a clear label.
### mpg.cpp
The program stores 250 miles and 12 gallons in double variables. It divides miles by gallons and stores the result in the mpg variable. The double data type preserve the decimal portion of the MPG result. The program then displays the MPG with its units.

# Final Verification 
-sum-3.cpp: 25 and 50
-mpg.cpp: 250 miles and 12 gallons
I reran both programs and verified the final results.
- sum-4.cpp: Total: 100
- mpg.cpp: Miles per gallon: 20.8333 MPG

I performed two tests for each program. The first test used the values assigned in the, and the second test used different values to verify that the calculations worked correctly.







