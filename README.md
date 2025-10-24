# Full_adder_and_Subtractor

**Theory**

Full Adder:
A full adder is a combinational logic circuit that adds three binary digits: two significant bits (A and B) and a carry input (Cin) from the previous stage. It produces two outputs: Sum (S) and Carry out (Cout).

The Sum (S) is the XOR of the three inputs:

S
=
A
⊕
B
⊕
C
i
n
S=A⊕B⊕C 
in
 
The Carry out (Cout) is generated when two or more inputs are HIGH:

C
o
u
t
=
A
B
+
B
C
i
n
+
A
C
i
n
C 
out
 =AB+BC 
in
 +AC 
in
 
The full adder is useful for adding multi-bit binary numbers by cascading multiple full adders. It is implemented using XOR, AND, and OR gates. The full adder extends the half adder by considering the carry input from the previous bit addition.

Full Subtractor:
A full subtractor is a combinational circuit that subtracts three bits: minuend (A), subtrahend (B), and borrow in (Bin) from the previous lower bit subtraction. It produces two outputs: Difference (D) and Borrow out (Bout).

The Difference (D) is calculated as:

D
=
A
⊕
B
⊕
B
i
n
D=A⊕B⊕B 
in
 
The Borrow out (Bout) indicates if a borrow is needed for the next higher bit and is given by:

B
o
u
t
=
A
′
B
+
B
i
n
(
A
⊕
B
)
′
B 
out
 =A 
′
 B+B 
in
 (A⊕B) 
′
 
The full subtractor is used in multi-bit subtraction where borrows may propagate between bits. It is often implemented using XOR, AND, and OR gates.

