1. `3` will be printed because we created a variable `i` in the loop we used previously that went from 0 to 3.
2. `150` will be printed because variable's last assignment was `300 * (1 - 0.5)`
3. `150` will be printed because variable's last assignment was `Math.round(150 * 100) / 100`
4. The function will return `[50, 100, 150]` because the function pushed the discounted prices to the array and then returned it.
5. There will be an error because variable `i` was declared in scope of the loop.
6. There will be an error because variable `dscountedPrice` was declared in scope of the loop.
7. `150` will be printed because variable's last assignment was `Math.round(150 * 100) / 100`
8. The function will return `[50, 100, 150]` because the function pushed the discounted prices to the array and then returned it.
9. There will be an error because variable `i` was declared in scope of the loop.
10. `3` will be printed because that is what it was assigned to.
11. The function will return `[50, 100, 150]` because the function pushed the discounted prices to the array and then returned it.
12. 
    A. `student.name`  
    B. `student['Grad Year']`  
    C. `student.greeting()`  
    D. `student['Favorite Teacher'].name`  
    E. `student.courseLoad[0]`  

13.  
    A. `32` as the number gets converted to string before addition.  
    B. `1`  as the string gets converted to the number before the subtraction.  
    C. `3` as the null gets converted to a number before addition, and thus results in zero added.  
    D. `3null` as null gets converted to string and thus becomes just a string that says null. 
    E. `4` as true gets converted to 1 before addition.  
    F. `0` as both false and null become numbers they both become zero.
    G. `3undefined` undefined is converted to string and becomes a string that says undefined.
    H. `NaN` as the string of 3 becomes a number, subtracting undefined from a number results in a NaN
  
14. 
    A. `true` as 2 gets converted to number and is thus more than 1  
    B. `false` as the dictionary order does not result in true  
    C. `true` as string gets converted to number 
    D. `false` as they are not the same type as required by ==  
    E. `false` true does not result in 2 when converted  
    F. `true` as Boolean function results in 2 being true

15. `===` is equality without type conversions, `==` is equality with possible type conversions.
17. `[2, 4, 6]` is the result. I see that the function goes through every item in given array, and applies `callback` function to it, and then returns the result. I see that the function provided doubles the input.
19. Immediate output will be `4`, then `3` right after, and then `2` after a second.