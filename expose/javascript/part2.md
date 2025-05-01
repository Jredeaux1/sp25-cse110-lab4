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
