# Engineering functions to fit mathematical models

Specify a continuous and differentiable function that satisfies the following:

f(x) is decreasing at 6 f(x) 

has a local minimum at x=-3

f(x) has a local maximum at x=3.

## Find the first derivative

setting f(-3) and f(3)= 0 we find (3+x)(3-x) leads to critical points at 3 and 3. So the derivative is 9-x^2. 

## Integration to find the equation of the function 

Since we know the antiderivative of a number is (x^(n+1))/(n+1) + C: we know that the antiderivative of 9-x^ 2 is 9x - (x^3/3) + C. 

Finding the antiderivative of 9-x^ 2 So, the antiderivative of 9-x^ 2 is 9x- (x^3)/3 and so f(x)= 9x - (x^3)/3 + C is our function's equation f(x).

<p align="left">
    <img width="300" height="300" src="https://user-images.githubusercontent.com/110789514/223252956-3499a89c-a948-4752-817f-679c5002bc30.png">
</p>    
*Graph of f(x)= 9x - (x^3)/3

## Intervals of Increase and Decrease

Plugging in values of -6, 0 and 4 into the first derivative, f'(x), we see that the function is decreasing at 6, increasing at 0, and decreasing again at 4. 

9-x^ 2 9 - (-6)^2 = -27 < 0 therefore so decreasing 

9 - (0)^2= 9 = 9 therefore + so increasing 

9 - (4)^2= -7 < 0 therefore - so decreasing 

The function decreases at intervals ( infinity, -3) and (3, infinity). It increases at the interval ( 3,3). 

Plugging in 3 and 3 into our function f(x), we find the critical points are at (3,18) (-3,-18). Since the function is decreasing at 6 and increasing at 0, we know that (3, 18) is a local maximum and (-3, -18) is a local minimum. We can confirm this by finding the concavity intervals from the second derivative. 

## Additional Characteristics/ Find the Second Derivative:

From our derivative equation, we can find the second derivative. 

f''(x)= -2x is our Second Derivative.

We know that the second derivative gives inflection points and concavity intervals. Since we know that x=-3 is a minimum, this means that f(x) should be concave upward at this point. Plugging in values smaller than 3 and larger than 3 to verify the signs of the intervals. Likewise, since we know that x=3 is a maximum, f(x) should be concave downward at this point, and we would need to verify this with the signs of the intervals plugged into the second derivative. 

-2(-6) = +12 therefore + and concave up 

-2(0)=0 

-2(4) = -8 therefore - and concave down

Now we have verified that F(x) is concave up at (-infinity, 0) and concave down at (0, infinity) this makes sense with what we know about x=3 as a maximum and x=-3 as a minimum.

## Summary

There are other functions that would fit the criteria given for this problem. Any equation that fits the following condition 9x - (x^3)/3 + C would work. This means that 9x-x^3/3 +1, or 9x-x^3/3 +2, or 9x-x^3/3 +3, or 9x-x^3/3 +4... etc, would work. Any positive constant multiplied by (f') also works. f' divided by a positive constant works. Also, an f' to an odd power will fit this function.

<p align="left">
    <img width="300" height="300" src="https://user-images.githubusercontent.com/110789514/223253217-e617190d-a8b2-43fb-a253-ea16315e5da0.png">
</p>   
* an example of one of many other graphs that satisfies the requirements. 



# Definitions

DERIVATIVE:
the sum and difference rules (f+-g)' = f'+-g', differentiate each term.
the power rule: the derivative of any x^n is  nx^n-1 
the derivative of any c*x is c
the derivative of a constant is zero 

## Equations

DERIVATIVE EQUATIONS:

the product rule: (u*v)'= u'v+uv'

the quotient rule: (f/g)'= gf'=fg'/g^2

the chain rule: f(g(x))'= f'(g(x))g'(x)


POINT SLOPE EQUATIONS:

the equation for a line y= mx+b

the equation for a point on a line y1-y2= m(x1-x2)


ANTIDERIVATIVE
antiderivative of x^n(dx)= (1/(n+1))(x)^n+1+C


MEAN VALUE THEOREM:
f'c = f(b)-f(a)/b-a


LINEAR APPROXIMATION
L(x)= f(a)-f’(a)(x-a) and is accurate for values close to x=a


ERROR IN APPROXIMATION
Delta Y = f(x+delta X)- f(x)  (delta y is called propagated error) represents actual change in y

Dy= f’(x)dx  differential of y represents the change in y and estimates change in y

Dx or Delta X is the measurement error

## Sketching

FIRST DERIVATIVE

We use the first derivative of  f(x)  to find the critical points and intervals of increase and decrease. 

CRITICAL POINTS

Find cp by setting the derivative to 0.  To find exact points, plug into original equation

INTERVALS

find intervals of increase/decrease by selecting intervals and plugging into derivative to find the sign + or -.

SECOND DERIVATIVE

We use the second derivative of  f(x)  to find the points of inflection and intervals concavity 

IINFLECTION POINTS

Find inflection points by setting the second derivative to 0. Plug into original equation  to find exact points of inflection.

CONCAVITY

find concavity intervals by selecting arbitrary intervals and plugging into second derivative to find the sign + or -

Horizonal assymptotes

if degree numerator = denominator HA = degree

if degree numerator < denominator HA = 0

if degree numerator > denominator no HA

Vertical assymptotes

set denominator = 0, if no denominator, no HA
