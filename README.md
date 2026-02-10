# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary
* In this lab we learned and applied our knowledge in order to derive a min term function 
* from a truth table. Additionally we applied KMaps to derive minimizations of min
* and max term function which exemplified the difference in efficiency of a
* a minimization function. We then were able to implement such functions onto a
* Basys3 board that exemplified the functionality of all three functions.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
    * With K-maps, you view them as a cylinder where they loop from 00->01->11->10->00 repeating.
    * This allows the ability for 00 & 10 to 'go across edges' both left/right & up/down.

### Why are the names Sum of Products and Products of Sums?
    * SoP - The sum of Products is by adding the answers of the multiplied variables. (A&B)+(C&D)
    * PoS - The product of Sums is multiplying the answers of the added variables. (A+B)&(C+D)
### Open the test.v file – how are we able to check that the signals match using XOR?
* When an XOR is used on two terms, a 1 is the output when the terms are not equivalent,
* a 0 is output when the terms are equivalent. Applying XORs to the signals checks whether
* they are equivalent. If they are not equivalent the test case catches and outputs a failure.

