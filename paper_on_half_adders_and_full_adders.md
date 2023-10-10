# Introduction to Half Adders and Full Adders
Half adders are logic circuits that use an X-OR and AND gate to add two 1-bit digits, which are either 0 or 1. Two numbers are inputted into half adders, and there are two results. 
However, full adders have three inputs, but only two outputs, or results. A full adder adds up three 1-bit numbers using two X-OR gates, two AND gates, as well as one OR gate. 
Both half adders and full adders have many features and nuances, but they have different aspects as well.

### Half Adders
Half adders add two binary digits and output two results, which are a sum and a carry. The sum is the last digit of the number, and the carry is the digit that is carried over when the sum hits 2. 
For example, inputs of 1 and 0 would result in a sum of 1 and a carry of 0, since no digits are carried over as 1+0 is less than 2. The carry changes from 0 only when the sum of the input is larger than 1 because binary only accepts 1’s and 0’s. 
For instance, inputs of 1 and 1 would result in the sum being 0 and the carry being 1. Half adders essentially perform addition in base 2 using this method.

### Full Adders
Full adders add three binary digits and also output two results. This change of adding an additional digit doubles the number of possibilities because the new digit has two possibilities: 0 and 1. 
For every possibility in the half-adder, such as 0 and 0, a new possibility emerges in a full adder, such as 0, 0, and 1, assuming the 1 is the extra digit. Full adders also have an output of 3 bits instead of the 2 bit outputs in half adders. 
This change creates many more possibilities and complexities, as well as the usages. 

### Half Adders vs Full Adders
Half adders can be seen as the less intelligent form of full adders; however, both are useful in their own rights. Half adders are very useful for calculators, computers, or digital measuring devices, which are all fairly rudimentary. 
On the other hand, full adders are used for digital processing, multiple bit addition, etc. Half adders are considered simpler than full adders are, which makes it more worthwhile to use. 
However, half adders can be substituted by full adders because it can be seen as a lesser form of a full adder. Full adders cannot be replaced by half adders. Full adders can be seen as two half adders added together, linked with an OR gate. 

### Recap
Ultimately, half adders and full adders are the very foundation of digital computing and processing, and each are very important. 
Half adders are mainly used when more complex calculations are not needed, while full adders can be used to replace half adders, as well as perform more complex calculations. 
The complexity of full adders is only possible with the foundations of the half adder, and neither should be overlooked as they both are essential to truth tables and logic gates. 

## Works Cited

Agrawal, P. (2022, December 21). Difference between half adder and full adder. GeeksforGeeks. https://www.geeksforgeeks.org/difference-between-half-adder-and-full-adder/ 

Saini, M. K. (n.d.). Difference between half adder and full adder. Online Courses and eBooks Library. https://www.tutorialspoint.com/difference-between-half-adder-and-full-adder#:~:text=Half%20adder%20is%20a%20combinational,forwarded%20from%20the%20previous%20output. 

YouTube. (2020, October 9). Half adders and full Adders Beginner’s tutorial. YouTube. https://www.youtube.com/watch?v=ecn-8iGDRSo 
