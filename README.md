# Finding-Zero-Point-of-Function

Here I define a function to find the zero point of f(x). In this function, there is a lambda function f(x), with initial value of x0, constant δ, and �. The stop condition of this function is |wn+1 − wn| < �. The function is tested at x0 = −5 and x0 = 0

Here I find a x*, let f(x*) = 0, we say x* is the zero point of this function. I have used the Euler method to find the zero point of function.

The forward Euler algorithm is described as wn+1 = wn − δ · f(wn)

With increase in n, we observe that |wn+1−wn| < �, here we define � = 0.001. Thus, we say wn is converged, and x* = wn or f(x*) = 0

function f f(x) = 2x + 4 (2)

function g: g(x) = x · sin(x) − 1

The zero point of g(x),with x ∈ [−4; 4] was found. Function g(x) was plotted inx ∈ [−4; 4].
