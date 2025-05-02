1. The final console.log(i) will log 3, which is the length of the prices array.
2. The output is the last value from the loop because discountedPrice is declared with var inside the loop and far is function scoped. Output should be 150
3. The output should also be '150' which is the last value held.
4. The function doesn't output anything into the terminal because return in JS sends the value back to where the function was called. However, if you were to put it into the console, it will output the correct output of '[50, 100, 250]'
5. There will be a reference error thrown ar line 12 because i is declared using let inside the for loop, and let has a block scope so i is not accessible outside the loop.
6. Line 13 will also throw a refrence error stating that the variable is not defined. This is because we used let, similar explination as 5.
7. Line 14 will output 150. This is because finalPrice is declared outside the for loop using let, so it is accessible both inside and after the loop.
8. The function returns `[50, 100, 150]`, which are the original prices with a 50% discount applied and rounded to two decimal places. It runs without errors but won’t display the result unless explicitly logged with `console.log()`.
9. At line 11, `console.log(i);` will cause a **`ReferenceError`** because `i` is declared using `let` inside the `for` loop, which gives it **block scope**. This means `i` only exists within the loop and is **not accessible outside** of it, so trying to log it after the loop ends results in an error.
10. At line 12, console.log(length); will successfully print 3 to the console. There will be no error as length is in the same scope as console.log.
11. This function returns [50, 100, 150]. It loops through the prices array, applies a 50% discount to each price, and stores the results in the discounted array.

12. a: student.name  b: student["Grad Year"]  c: student.greeting()  d: student["Favorite Teacher"].name  e: student.courseLoad[0]
13.
a. `'3' + 2`  
**Output:** `'32'` – String + number = string concatenation. 

b. `'3' - 2`  
**Output:** `1` – String is coerced to number, then subtraction.

c. `3 + null`  
**Output:** `3` – `null` becomes `0`.

d. `'3' + null`  
**Output:** `'3null'` – String + null = string concatenation.

e. `true + 3`  
**Output:** `4` – `true` becomes `1`.

f. `false + null`  
**Output:** `0` – Both become `0`.

g. `'3' + undefined`  
**Output:** `'3undefined'` – String + undefined = string concatenation.

h. `'3' - undefined`  
**Output:** `NaN` – `undefined` becomes NaN in numeric ops.


14.
a. `'2' > 1`  
**Output:** `true` – `'2'` is coerced to number `2`.

b. `'2' < '12'`  
**Output:** `false` – Compared as strings: `'2'` > `'1'`.

c. `2 == '2'`  
**Output:** `true` – Loose equality does type coercion.

d. `2 === '2'`  
**Output:** `false` – Strict equality checks type (number vs. string).

e. `true == 2`  
**Output:** `false` – `true` becomes `1`, not equal to `2`.

f. `true === Boolean(2)`  
**Output:** `true` – Both are `true` booleans.

15. == allows type conversion
    
=== requires both value and type to match
