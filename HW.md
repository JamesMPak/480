My homework is a function named gcd that accepts two inputs (a,b) and solves for the greatest common divisor.
I implemented this code in labs.Codeacademy.com's Python Text Editor.
The function, gcd(a,b), uses the Euclidean Algorithm to solve for the greatest common divisor.
The Euclidean Algorithm works by expressing the larger of the two numbers in the form of a = tb + r where t is some integer and r is the remainder.
If b divides a, which also implies that r=0, then the gcd(a,b)=b. If r =/= 0, then let a=b and b=r because gcd(a,b) = gcd(b,r).
The process continues until r=0 which then, as stated above, implies that b divides a and henceforth, the gcd = b.

Examples:
a=17
b=3

17 = 5*3 + 2
3 = 1*2 + 1
2 = 2*1 + 0
gcd = 1 # the last "b"



a=48
b=9

48 = 5*9 + 3
9 = 3*3 + 0
gcd = 3



a=81
b=18

81 = 4*18 + 9
18 = 2*9 + 0
gcd = 9
