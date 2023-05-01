Part 2
1. It would log '3' because 'i' would stop incementing up once it wasn't less than prices.length, and the length of the prices array is 3.
2. It would log '150' since the last change to discountedPrice would be: prices[2] * (1 - 0.5) = 300 * 0.5 = 150
3. It would log '150' since the last change to finalPrice would be: Math.round(150 * 100)/100 = 15000/100 = 150
4. It would return [50, 100, 150], since discounted is an array that gets all of the finalPrices. We know the last one is 150 from above. The other 2 are 50 and 100, since 100 * 0.5 = 50 and 200 * 0.5 = 100
5. It would give an error since 'i' is initiated in the for-block with let, so it can't be acessed outside of the block (line 12).
6. It would give an error since 'discountedPrice' is initiated in the for-block with let, so it can't be acessed outside of the block (line 13).
7. It would log '150'. Similar to problem 3, but even with finalPrice initiated with 'let' instead of 'var', sinice the initiation is in the same block as line 14, the code can recognize finalPrice.
8. It would return [50, 100, 150], even though all the variables were initiated with 'let' since they are used within the blocks they were initiated in so they were all able to be accessed properly.
9. It would give an error, since 'i' is initiated in the for-block with let, so it can't be acessed outside of the block (line 11).
10. It would log '3' since length was initiated as a const to prices.length = 3. The value of length would stay the same.
11. It would return [50, 100, 150]. Even though discounted is initiated as a const, we can still manipulate it by pushing discountedPrice to it. We can't reassign it though.

Data Types

12. Student Object <br>
    A. student.name <br>
    B. student['Grad Year'] <br>
    C. student.greeting() <br>
    D. student['Favorite Teacher'].name <br>
    E. student.courseLoad[0] <br>

Basic Operators & Type Conversion

13. Arithmetic <br>
    A. Output: 32, since 2 get mapped to its string representation, then '3' and '2' are concatenated together<br>
    B. Output: 1, since '3' gets mapped to its integer representation, and 3 - 2 = 1<br>
    C. Output: 3, since the null integer conversion is 0, and 3 + 0 = 3<br>
    D. Output: 3null, since the null string conversion is 'null', and '3' concatenated with 'null' is '3null'<br>
    E. Output: 4, since the true integer conversion is 1, and 1 + 3 = 4<br>
    F. Output: 0, since the integer conversion for false and null is 0, and 0 + 0 = 0<br>
    G. Output: 3undefined, since the string conversion for undefined is 'undefined', and '3' concatenated with 'undefined' is '3undefined'<br>
    H. Output: NaN, since the integer conversion of '3' is 3 and the integer conversion for undefined is NaN. Since NaN is not a number, the calculation can't be done and returns NaN<br>
14. Comparison <br>
    A. Output: true, since the '2' gets converted to the integer represenation of 2, and since 2 > 1, it outputs true<br>
    B. Output: false, when the 2 strings are compared, it first compares the first character. Since '2' > '1', then the comparison says that '2' > '12', so it outputs false<br>
    C. Output: true, since '2' gets converted to its integer representation, and 2 == 2 so it returns true<br>
    D. Output: false, since === checks equality without type conversion, and since '2' is a string and 2 is an integer, they have different types and === returns false<br>
    E. Output: false, since the integer representation of true is 1 and since 1 != to 2, it outputs false<br>
    F. Output: true, Boolean(2) is true since 2 isn't an "empty" element. Since true === true, it would output true <br>
15. == compares 2 elements, and if they are different they will get converted to their integer representaions and get compared. === will never convert the type, so if the types are different, it will automatically output false. 

Loops

16. In file: part2-question16.js

Functions

17. It would result in the array: [1,2,3] to change into [2,4,6]. When modifyArray is called, it will go through a for-loop 3 times(length of array) and push the result from the doSomething function each time with the corresponding element. So each element gets multiplied by 2 and pushed into the newArr, giving [2,4,6]
18. In file: part2-question18.js
19. Output:
    > 1 <br>
    > 4 <br>
    > 3 <br>
    > 2 <br>
