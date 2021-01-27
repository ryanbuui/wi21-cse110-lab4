# Part 1
## What was the bug?
The problem with the code was that the inputs to num1 and num2 were considered as text instead of numbers. So, when calculateSum was called on with the arguments of (num1, num2), instead of arithmetically adding the two numbers it concated them as if they were strings resulting in "num1num2".
## How would you fix it?
To fix this problem I would go into the calculateSum function and parse the arguments to ints first, before performing any arithmetic.
# Part 2
1. citylots.json
2. part2.js 
3. 11.7 MB
4. 1.29 seconds
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.141 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData @ part2.js:2