1. the value of i (index of the last item in prices) will be displayed in the terminal (3). Because var variables are in function scope it can be accessed outside the for loop.
2. the value of the last disctouned item price will be displayed in the terminal (150) because var variables are in function scope it can be accessed outside the for loop.
3. the value of the last disctouned item price will be displayed in the terminal (150) because var variables are in function scope it can be accessed outside the for loop.
4. this function returns a list of prices with 50% discount applied to each item in it ([ 50, 100, 150 ]). Because the function goes over each item in the prices list and applies 50% discount on them. Then the function stores the item in another list and return it.
5. error. Because "let i" is defined in the for loop block. it is inaccessible on line 12.
6. error. Because "let disctountedPrice" is defined in the for loop block. it is inaccessible on line 13.
7. 150 is printed to the console. Because "let finalPrice" is on line 3, which is in the function block and line 14 is in the same block. So the value of finalPrice is accessible.
8. this function returns a list of prices with 50% discount applied to each item in it ([ 50, 100, 150 ]). Because the function goes over each item in the prices list and applies 50% discount on them. Then the function stores the item in another list(discounted) and return it.
9. error. Because "let i" is defined in the for loop block. it is inaccessible on line 11
10. the length of the list "prices" will be printed to the console (3). Because "const length" is in line 4, which is in the function discountPrices block and line 12 is in the same block. So the value of length is accessible.
11. this function returns a list of prices with 50% discount applied to each item in it ([ 50, 100, 150 ]). Because the function goes over each item in the prices list and applies 50% discount on them. Then the function stores the item in another list and return it.
12. 
     1. student.name;
     2. student["Grad Year"];
     3. student.greeting();
     4. student["Favorite Teacher"].name;
     5. student.courseLoad[0];
13. 
    1.  "32" because the string "3" comes first, the "+" is recognized as string concatenation. So the int 2 is converted to string "2" and concatenated after 3.
    2.  1  Because a string cannot subtract anything and the int 2 comes after the "-", string "3" is converted to int 3 and then performed 3-2 = 1.
    3.  3 Because null is converted to int 0 and then performed 3+0 = 3
    4.  "3null" Because the string "3" comes first, the "+" is recognized as string concatenation. null is then converted to string "null" and then performed string concatenation.
    5.  4 Because true is converted to int 1 and then performed 1+3 = 4
    6.  0 Because false is converted to int 0 and null is converted to int 0. Then performed 0+0=0
    7.  "3undefined" Because the string "3" comes first, the "+" is recognized as string concatenation. Then undefined is converted to string "undefined" and then performed string concatenation.
    8.  NaN Because string "3" is converted to int 3 and undefined is converted to NaN. Any numeric calculation with NaN is NaN
14. 
    1.  true Because string "2" is converted to int 2 and then 2 > 1 is true.
    2.  false Because "2" is greater than the initial character of "12".
    3.  true Because string "2" is converted to int 2 and then 2 == 2 is true.
    4.  false Because this is strict equality. 2 and "2" have different datatypes.
    5.  false Because true is converted to int 1 and 1 == 2 is false.
    6.  true Because Boolean(2) is true and true === true
15. == converts operands of different types to numbers. === checks the equality without type conversion.
16. See part2-question16.js
17. [2,4,6] will be the result. The function doubles the current element in array. The for loop goes through each element in the array. So after iteration finished each element in the array gets doubled.
18. See part2-question18.js
19. 1 4 3 2 (each number in a new line)