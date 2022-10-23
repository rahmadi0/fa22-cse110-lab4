1. 20 is printed by line 9
2. 20 is printed by line 9
3. the program crash when we access it outside the block scope. The result is type let and it is only visible inside the if block. 
4. the code return an error because the result is type let and it is only visible inside the if block and is not accessible out side the if block. The result is undefined thus it gives us the error.
5. the program crash when we reassign a constant variable. the variable result is not changing.
6. error becasue of reassigning the const variable result.
   
#part2.

1. 3 is printed. this the number of iteration of i in the for loop. i iterates over the prices.length, i iterates 3 times.
2. 150 is printed is the discountPrice amount. that is the amount computed for the last iteration for price 300. so the last index in the price[2] is 300 * (1 -0.5) = 150. 
3. 150 is printed because the finalPrice gets updated the last time when the discount value is 150 so that is what get printed.
4. the function returns the discounted array with the values 50, 100, 150 we pushed into it. But it does not print anything because no function call for console.log made.
5. reference error i is not defined. Since i is type let and we access it outside the block scope.
6. reference error discountedPrice is not defined in this scope and we attempt to access it but it is type let so error occurs.
7. 150 printed, no error. finalPrice is defined at the top of the function and it is accessible anywhere inside the function scope.
8. the function returns the discounted array with the values 50, 100, 150. But it does not print anything because no function call for console.log made.
9. reference error i is not defined. Since i is type let and we access it outside the block scope.
10. 3 is printed. this the prices.length. We get no error becasue the lenght is defined and accessed in side the block scope. 
11. the function returns the discounted array with the values 50, 100, 150. But it does not print anything because no function call for console.log made. even the array is type constant but we don't get an error because you can change the elements of a const array or push into it. example discounted.push(1) or discounted[2] = 333. this does not throw and error.
