---
title: 
author:
partner:
date:
---
Embed math equations into Github Markdown file using a [web service](https://www.codecogs.com/latex/eqneditor.php)

# (5 pts)
Perform the following number-system conversions (show your work):

- a. <a href="https://www.codecogs.com/eqnedit.php?latex={129}_{10}&space;=&space;{?}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{129}_{10}&space;=&space;{?}_{2}" title="{129}_{10} = {?}_{2}" /></a>  

129/2 = 64 remainder 1. 64/2 = 32 remainder 0. 32/2 = 16 remainder 0. 16/2 = 8 remainder 0. 8/2 =4  remainder 0. 4/2 = 2 remainder 0. 2/2 = 1 remainder 0. 1/2= remainder 1.

Flip and put in order: 10000001_{2}

- b. <a href="https://www.codecogs.com/eqnedit.php?latex={0011010}_{2}&space;=&space;{?}_{10}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{0011010}_{2}&space;=&space;{?}_{10}" title="{0011010}_{2} = {?}_{10}" /></a>  

= 0*(2^0) + 1*(2^1) + 0*(2^2) + 1*(2^3) + 1*(2^4) + 0*(2^5) + 0*(2^6) = 2 + 8 + 16 = 26_{10}

- c. <a href="https://www.codecogs.com/eqnedit.php?latex={0F100}_{16}&space;=&space;{?}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{0F100}_{16}&space;=&space;{?}_{2}" title="{0F100}_{16} = {?}_{2}" /></a>  

Each hexadecimal is 4 binary digits, F = 15 (base 10) = 1111 (base 2)
	0000 1111 0001 0000 0000_{2}

- d. <a href="https://www.codecogs.com/eqnedit.php?latex={1001101101101}_{2}&space;=&space;{?}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{1001101101101}_{2}&space;=&space;{?}_{16}" title="{1001101101101}_{2} = {?}_{16}" /></a> 

1001101101101 : this has 13 digits,k but  need to be a factor of 4 digits so add zeros:
0001 0011 0110 1101 = 136D_{16}

# (5 pts)
Evaluate the Boolean equation F = a AND (NOT b OR (c AND d)) for the given values
of variables a, b, c, and d:  

- a. a=1, b=1, c=0, d=1  
- b. a=0, b=0, c=0, d=1  

a. F = 1 AND (NOT 1 OR (0 AND 1)) = 1 AND (0 OR 0) = 1 AND 0 = 0
b. F = 0 AND (NOT 0 OR (0 AND 1)) = 0 AND (1 OR 0) = 0 AND 1 = 0  


# (5 pts)
Draw the NAND(x,y) gate CMOS transistor circuit. Show the conduction path and output
value when: 

- a. x = 1 and y = 0
- b. x = 1 and y = 1

# (5 pts)
Convert the following equation directly to gate-level circuits: F = a + bcd’ + a'e + f’

![](PictureP.PNG)

# (5 pts)
Expand F(w,y,z) = wy to 
- a. sum-of-minterms form
- b. product-of-maxterms form

# (5 pts)
A car has a fuel-level detector that outputs the current fuel-level as a 3-bit binary number, with 000 meaning empty and 111 meaning full. Create a circuit that illuminates a “low fuel” indicator light (by setting an output L to 1) when the fuel level drops below level 3.

# (5 pts)
Convert the function F shown in the truth table in Table below to an *product-of-sum* equation. Don’t minimize the equation.

![Truth table](figures/problem_6.png)

# (5 pts)
Implement the function above in *Dataflow Modeling* style Verilog and test its functionality via the testbench in [codes/exam/problem_7](../../codes/exam/problem_7). Include the waveform in the report.

# (5 pts) 
Use the theorems of boolean algebra to simplify the following logic function: F = m·n·o + q’·p’·n’ + p·r·m + q’·o·m·p’ + m·r (hint, the result has three terms. Don't spend too much time on this one. If stuck, move on first)


## **beyond this place there be dragons**

# (5 pts)
Implement a 4-to-2 priority encoder using only NOR gates.

- a. Derive the truth table.
- b. Derive the sum-of-product expression.
- c. Derive the product-of-sum expression.
- d. Convert the product-of-sum circuit into NOR gate implementation.

![1-bit 2-to-1 multiplexor](figures/problem_9.png)

# (5 pts)
Analyze the CMOS circuit below. 

- a. Draw the conduction paths for
    - A = 0, B = 0
    - A = 1, B = 0
    - A = 0, B = 1
    - A = 1, B = 1
- b. Write the truth table.
- c. What gate is it?

![Unknown gate](figures/problem_a.png)
