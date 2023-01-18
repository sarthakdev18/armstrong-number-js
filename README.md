# armstrong-number-js
20 days of JavaScript coding streak - day 10

The above program takes an input from the user. Then,

1. The number entered by the user is stored in a temporary variable temp.
2. A while loop is used to iterate a three-digit value.
   a. The modulus operator % is used to obtain each digit number. When a number is divided by 10, the remainder is the last digit. In the first iteration, 153 % 10 gives 
   b. The remainder digit's cube is calculated by multiplying the digit three times. And the cube is added to the sum variable.
   c. The digit is divided by 10 to remove the last digit.
   d. The while loop continues iterating and dividing the number by 10 until the number is 0.
3. Finally, the sum is compared with the number entered by the user. If the sum and the number are equal, the number is an Armstrong number.
