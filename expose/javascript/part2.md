## part 2:
1. Line 12 outputs 3 to the web console. This is because i increments to 3 and the scope of this variable is under the whole function `discountPrices`. 
2. Line 13 outputs 150 to the web consloe. This is because the final discounted price would be the last elemment, 300, which is 150.
3. Line 14 outputs 150 to the web console. This is because 150*100 / 100 = 150, which i the final price
4. This function will return an array of final price, whihc is [50, 100,150]. This is because push appends each calculated final price to the array. 
5. Line 12 will give us an error, since `i` is only defined in the for loop. the `console.log` statement is outside the for loop, so it can't access the variable `i`.
6. Line 13 gives us an errror. Since the scope of discounted price is only defined on the for loop.
7. Line 14 prints 150 to the web console. Since `finalPrice`'s scope is anywhere inside the `discountedPrices` function. Hence the console would be able to print the value calucualted inside the for loop.
8. The function returns the array [50,100,150], since the scope of discounted is defined under the function `discountedPrices`. Hence the function will still return an array with correctly calculated final prices.
9. Line 11 will give us an error; Since `i` is only defined in the for loop. the `console.log` statement is outside the for loop, so it can't access the variable `i`.
10. Line 12 prints 3 to the web console. Since the length variable is set to the length of the prices[], which is 3, at line 3 and was not modified since.
11. The function returns the array [50,100,150], this is because the const keyword only defines a constant reference to the array, but we can still modify the elements of the array.
12. a. `student.name`
    b. `student["grad year"]`
    c. `student.greeting()`
    d. `student["Favorite Teacher"].name`
    e. `student.courseLoad[0]`
13. a. 32. Since integer maps to their exact string representation.
    b. 1. Since - is an arithmatic operation so it calculates 3-2. 
    c. 3, since 3 is a type of integer
    d. 3null, since  + concatenates the string to null.
    e. 4, since true maps to 1
    f. 0, since false maps to 0
    g. 3undefined, since 3 and underfined are strings
    h. Nan, Since it is impossible to do arithmatic with 3 and undefined.
14. a. True, since '2' maps to the integer 2 and it is greater than 1
    b. false, since strings maps to integers under comparison hece 12 is larger than 2.
    c. True, since strings maps to integers and 2 is equal to 2.
    d. False, since there is a type different between 2 to '2'
    e. False, since true maps to 1, but 1 does not equal to 2
    f. True, since Boolean(2) evaluates to true, hence the whole expression evaluates to true.

15. == performs loose equality on two variables, which ignores the type of the object; === performs strit equality which requires matching types between two variables. 
16. See JS file
17. 