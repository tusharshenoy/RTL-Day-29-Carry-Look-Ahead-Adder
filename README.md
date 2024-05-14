# RTL-Day-29-Carry-Look-Ahead-Adder
### Problem Statement: Implementing Carry Look Ahead Adder.
### Theory:

A carry-look ahead adder (CLA) or fast adder is a type of electronics 
adder used in digital logic. A carry-look ahead adder improves speed by 
reducing the amount of time required to determine carry bits. It can be 
contrasted with the simpler, but usually slower, ripple-carry adder (RCA), for 
which the carry bit is calculated alongside the sum bit, and each stage must 
wait until the previous carry bit has been calculated to begin calculating its 
own sum bit and carry bit. The carry-look ahead adder calculates one or more 
carry bits before the sum, which reduces the wait time to calculate the result 
of the larger-value bits of the adder.


#### Advantages of Carry Look-ahead Adder

In this adder, the propagation delay is reduced. The carry output at any stage 
is dependent only on the initial carry bit of the beginning stage. Using this 
adder it is possible to calculate the intermediate results. This adder is the 
fastest adder used for computation.

#### Applications
High-speed Carry Look-ahead Adders are used as implemented as IC’s. 
Hence, it is easy to embed the adder in circuits. By combining two or more 
adders calculations of higher bit Boolean functions can be done easily. Here 
the increase in the number of gates is also moderate when used for higher bits.
For this Adder there is a trade-off between area and speed. When used for 
higher bit calculations, it provides high speed but the complexity of the circuit 
is also increased thereby increasing the area occupied by the circuit. This adder 
is usually implemented as 4-bit modules which are cascaded together when 
used for higher calculations. This adder is costlier compared to other adders.
For Boolean computation in computers, adders are being used regularly. 
Charles Babbage implemented a mechanism for anticipating the carry bit in 
computers, to reduce the delay caused by the ripple carry adders. While 
designing a system, the speed of computation is the highest deciding factor for 
a designer. In 1957, Gerald B. Rosenberger patented the modern Binary Carry 
Look-ahead Adder. Based on the analysis of gate delay and simulation, 
experiments are being conducted to modify the circuit of this adder to make it 
even faster.


#### Carry Look Ahead logic
![image](https://github.com/tusharshenoy/RTL-Day-29-Carry-Look-Ahead-Adder/assets/107348474/ce439017-b978-403d-ba4a-ab572d91e6d9)


![image](https://github.com/tusharshenoy/RTL-Day-29-Carry-Look-Ahead-Adder/assets/107348474/3d4c7ae7-1f3d-496a-982a-df8a7441865e)
#### FIG: Carry Look ahead Block


#### Schematic:

![image](https://github.com/tusharshenoy/RTL-Day-29-Carry-Look-Ahead-Adder/assets/107348474/a54890cb-25e7-49f3-aef7-71fcfd4702ed)
#### FIG Carry Look Ahead Adder


#### Simulation Output:
![image](https://github.com/tusharshenoy/RTL-Day-29-Carry-Look-Ahead-Adder/assets/107348474/d78737a5-3853-4502-b523-650f787ccada)
