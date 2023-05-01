1. Working with the following set of Integers S = {0,1,2,3,4,5,6}
What is
a) 4 + 4
b) 3 x 5
c) what is the inverse of 3 ?

Answer:
The length of the set S is 7. 

a) 4 + 4 = 8 which is not in in S, so we need to do 8 mod 7 = 1 => 4 + 4 = 1 with respect to set S.
b) 3 x 5 = 15 not in S => 15 mod 7 = 1 => 3 x 5 = 1 with respect to set S.
c) The inverse of 3 (mod 7) is an integer x such that 3x is congruent to 1 modulo 7 
so 3𝑥 ≡ 1(mod 7)

The Euclidean algorithm applied: 
7 = 3 x 2 + 1
3 = 1 x 2 + 1

continue
1 = 7 - 3 x 2
1 = 3 - 2 x 1

Substitute for 1 
=> 1 = 3 - 2 x (7 - 3 x 2) 
=> 1 = 3 - 2 x 7 + 2 x 3 x 2
=> 1 =  3 x (1 + 4) - 7 x 2
=> 1 = 3 x 5 - 7 x 2
therefore x = 5 

Theory: 
- (Extended Euclidean algorithm)[https://en.wikipedia.org/wiki/Extended_Euclidean_algorithm]
- https://math.stackexchange.com/a/747393/1093681

2. For S = {0,1,2,3,4,5,6}
Can we consider 'S' and the operation '+' to be a group ? => yes
- Closure: the sum of any two numbers in S is always in S. For instance, 2 + 4 = 6 belongs to S
- Associativity: for any a, b, and c in S, (a + b) + c = a + (b + c).
- Identity element: There exists an element e in S such that for any a in S, a + e = e + a = a. This element is 0 since 0 + a = a + 0 = a for any a in S.
- Inverse element: For any a in S, there exists an element b in S such that a + b = b + a = e. We can find the inverse of any element a in S by subtracting a from 7. For example, the inverse of 3 is 4 since 3 + 4 = 4 + 3 = 7, which is the identity element of S.

3. What is -13 mod 5 ?
-13 = (-3) x 5 + 2 => -13 mod 5 = 2


4. Polynomials
For the polynomial x^3 - x^2 + 4x - 12 
Find a the positive root ?
--
What is the degree of this polynomial ?
The degree is 3 which is the highest power of the variable x
