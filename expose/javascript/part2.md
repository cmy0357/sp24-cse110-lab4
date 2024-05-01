1. 3, because the length of prices is 3, so the loop ends when i is incremented to 3. 
2. 150, because the last time it's assigned is when i = 2, so the value is 300 * (1 - 0.5) = 150.
3. 150, because the last time it's assigned is when i = 2, so discountedPrice = 150, which gives it the value 150.
4. [50, 100, 150], because the function multiplies each number in prices by (1 - discount) and returns a list with those values.
5. Error because line 12 is outside the block that i was defined.
6. Error because line 13 is outside the block that discountedPrice was defined.
7. 150 because finalPrice is defined in the function block, so we can access it anywhere inside the function.
8. [50, 100, 150], because we didn't try to access any variables outside of their scope, so it works as we expect.
9. Error because line 12 is outside the block that i was defined.
10. 3, because length is defined within the function block, and we didn't try to reassign it.
11. [50, 100, 150], because we didn't try to access any variables outside of their scope or reassign any const variables, so it works as we expect.
12. 
    - A: student.name
    - B: student['Grad Year']
    - C: student.greeting()
    - D: student['Favorite Teacher'].name
    - E: student.courseLoad[0]
13. 
    - A: '32', in addition, we convert both value to string if either of them is string. So we convert 2 to string '2', and concatenate them which gives '32'.
    - B: 1, in subtraction, we convert both value to number if either of them is not number. So we convert '3' to 3, and subtract them which gives 1.
    - C: 3, since 3 in a number, we convert null to the number 0, so adding them gives 3.
    - D: '3null', since '3' is a string, we convert null to the string 'null', so concatenating them gives '3null'.
    - E: 4, since 3 is a number, we convert true to the number 1, so adding them gives 4.
    - F: 0, since both false and null convert to the number 0, adding them gives 0.
    - G: '3undefined', since '3' is a string, we convert undefined to the string 'undefined', so concatenating them gives '3undefined'.
    - H: NaN, since it's subtraction, we convert '3' to 3 and undefined to NaN, so subtracting them gives NaN.
14. 
    - A: true, since '2' and 1 are of different types, we convert '2' to the number 2, so 2 > 1 gives true.
    - B: false, since both '2' and '12' are strings, we compare them by dictionary order, so '2' > '12'.
    - C: true, since 2 and '2' are of different types, we convert '2' to the number 2, so the equality holds.
    - D: false, since 2 and '2' are of different types, the strict equality returns false.
    - E: false, since true and 2 are of different types, we convert true to the number 1, so 1 != 2.
    - F: true, the boolean of 2 is true, so the strict equality holds.
15. == converts variables to the same types before comparing them, while === compares without type conversion.
16. 
17. [2,4,6], in modifyArray, we use a for loop so that each element in array is passed as an argument to the callback function doSomething, which multiplies a number by 2. A new array with these modified elements is returned.
18. 
19. 1 4 3 2