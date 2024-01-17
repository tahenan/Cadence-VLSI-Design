# 8-bit Unsigned Floating-Point Multiplier

A VLSI architecture to multiply two unsigned floating-point operands
# Objective 
We propose an architecture that accepts two 2 × 2 matrices containing 11
bit floating point numbers as inputs and returns their product.
<br />

 ![alt text](https://github.com/tahenan/Cadence-VLSI-Design/blob/main/photos/vls1.png)

<br />

# Proposed Solution
Multiplication of floating point numbers in binary representation consists of two aspects:
 ○ Multiplication of the fractional part - called the mantissa.
 ○ Addition of the integral part - called the exponent.
<br />

 ![alt text](https://github.com/tahenan/Cadence-VLSI-Design/blob/main/photos/vls5.png)

<br />

# Cadence - Circuit Scheme 
<br />

 ![alt text](https://github.com/tahenan/Cadence-VLSI-Design/blob/main/photos/vls4.png)

<br />

# Completed Circuit Schematic Simulation 
For the inputs 10110011 and 01101001, the values are:
 ● Exponents
    ○ EA- 1011
    ○ EB- 0110
 ● Mantissae
    ○ MA- 0011
    ○ MB- 1001

<br />

 ![alt text](https://github.com/tahenan/Cadence-VLSI-Design/blob/main/photos/vls6.png)

<br />

# Layout of the complete circuit in the pad frame

<br />

 ![alt text](https://github.com/tahenan/Cadence-VLSI-Design/blob/main/photos/vls3.png)

<br />



