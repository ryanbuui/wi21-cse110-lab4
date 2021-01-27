1. Since 'i' was declared as a var it ignores the code block and acts as a funtion-scoped variable within the function discountPrices meaning it is capable of being called upon within the function's scope. On line 11, specifically, if we considered ([100, 200, 300], .5) to be the arguments of the function, then '3' will be printed out in console. This is because 'i' is utilized within the for loop in which after every iteration it is increased by one until i < prices.length is false, therefore, i will equal prices.length when the for loop stops running.   
2. Since 'discountedPrice' was declared as a var within the for loop, it ignores the code block and acts as a function-scoped variable within the function discountPrices meaning it can be called upon within the functions scope. On line 12, if we considered ([100, 200, 300], .5) to be the arguments of the function, then '150' will be printed out. This is because at the end of the for loop, 'discountedPrice' will be assigned the value of the last element of prices multiplied by '(1-discount)'.
3. In line 13, if we considered ([100, 200, 300], .5) to be the arguments of the function, then '150' will be printed out since 'finalPrice' is equal to 'discountedPrice' rounded to the hundredths place. It is capable of being called upon since it was declared within the function's scope.
4. The function will return an array with the same length as prices, whose elements are the same as the ones in prices but multiplied by '(1-discount)' and rounded to the hundredths place. So in the case where the arguments are ([100, 200, 300], .5), discountPrices would return [50, 100, 150].
5. Line 11 will produce a ReferenceError since 'i' is not defined within the relevant scope, this occurs because 'i' was declared as a let and is only available within the code block of the for loop.
6. Line 12 will produce a ReferenceError since 'discountedPrice' is not defined within the relevant scope, this occurs because 'discountedPrice' was declared as a let and is only available within the code block of the for loop.
7. In line 13, if we considered ([100, 200, 300], .5) to be the arguments of the function, then '150' will be printed out since 'finalPrice' is equal to 'discountedPrice' rounded to the hundredths place. Although 'finalPrice' is declared as let, since it was declared within the function's scope it can be called within the function.
8. The function will return an array with the same length as prices, whose elements are the same as the ones in prices but multiplied by '(1-discount)' and rounded to the hundredths place. So in the case where the arguments are ([100, 200, 300], .5), discountPrices would return [50, 100, 150].
9. Line 11 will produce a ReferenceError since 'i' is not defined within the relevant scope, this occurs because 'i' was declared as a let and is only available within the code block of the for loop.
10. If we assume the assignments for 'discountedPrice' were successful, then line 12 will produce a ReferenceError since 'discountedPrice' was declared as a const and is not defined in the relevant scope. However, in reality, a variable type error would occur first in the for loop when it tries to assign 'discountedPrice' a new value since it is of type const.
11. Assuming that the assignments of 'finalPrice' does not produce an error, line 13 will print out the value of 'finalPrice'. Even though it was declared as a const, since the variable was declared in the function's scope it can be called upon within the function.
12. Assuming that the assignments of variables did not produce any errors and were also successful, given the arguments of ([100, 200, 300], .5), the function discountPrices would return [50, 100, 150]. However, if we assumed instead that the assignments were unsuccessful, the function would produce a variable type error as it tried to alter a const variable. 
13. Object
- A. student.name
- B. student['Grad Year']
- C. student.greeting()
- D. student['Favorite Teacher'].name
- E. student.courseLoad[0]
14. Arithmetic
- A. '32'
- B. 1
- C. 3
- D. '3null'
- E. 4
- F. 0
- G. '3undefined'
- H. NaN
15. Comparison
- A. true
- B. false
- C. true
- D. false
- E. false
- F. true
16. The '==' operator checks equality with type conversion, '===' does not check equality with type conversion.   
17. The code snippet will output 'How are you?' because '2 == true' is false, however, a number that is not zero within a if statement will act as true. So, the first if statement is false and goes to the else if statement which is true.
18. part1-question18.js
19. The function, modifyArray, with the arguments ([1,2,3], doSomething) will return [6, 8, 10]. This is because the 'array' will be iterated through within the for loop and its elements will be used within the arguments of the call back function. The call back function, doSomething, will then add 2 to the element and use the result within its own call back function. The second call back function multipies the number by 2 and returns it which ends up getting pushed onto newArr.
20. part1-question20.js    
21. 1
    4
    3
    2
