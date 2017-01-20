CS110: Assignment 1
Problem 1: ​The value of double x is calculated as follows:
x = 0.75 * (a+c)
4*a + 0.5* (b*c)
Write a program, CalcX.java​ that uses int a = 2, int b = 5, and int c = 4. The program will then
print out the calculated value of x.
Sample Output:​ 4.0
You can use different values of a, b, and c to check the output of your code.
Problem 2: ​Easter Sunday is the first Sunday after the first full moon of spring. To compute the
date, you can use this algorithm, invented by the mathematician Carl Friedrich Gauss in 1800:
1. Let y​ be the year (such as 1800 or 2001).
2. Divide y​ by 19 and call the remainder a​. Ignore the quotient.
3. Divide y​ by 100 to get quotient b​ and remainder c​.
4. Divide b ​by 4 to get quotient d​ and remainder e​.
5. Divide 8 * b + 13 by 25​ to get quotient g​. Ignore the remainder.
6. Divide 19 * a + b - d - g + 15​ by 30 to get remainder h​. Ignore the quotient.
7. Divide c​ by 4 to get quotient j​ and remainder k​.
8. Divide a + 11 * h by 319​ to get quotient m​. Ignore the remainder.
9. Divide 2 * e + 2 * j - k - h + m + 32​ by 7 to get remainder r​. Ignore the quotient.
10. Divide h - m + r + 90 by 25​ to get quotient n​. Ignore the remainder.
11. Divide h - m + r + n + 19 by 32​ to get remainder p​. Ignore the quotient.
Then Easter falls on day p​ of month n​. For example, if y is 2001:
a = 6, b = 20, c = 1, d = 5, e = 0, g = 6, h = 18, j = 0, k = 1, m = 0, r = 6, n = 4, p = 15
Therefore, in 2001, Easter Sunday fell on April 15.
Write a program, WhenIsEaster.java​, that prints out the values of n and p for a given year.
Submitting: ​At the top of your .java file add the following comments and save it
 /**
* CS 110 Section No.
* Lab Assignment 1
* First and Last Name **/