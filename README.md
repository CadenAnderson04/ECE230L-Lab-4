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

Summarize your learnings from the lab here.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
    * With K-maps, you view them as a cylinder where they loop from 00->01->11->10->00 repeating.
    * This allows the ability for 00 & 10 to 'go across edges' both left/right & up/down.

### Why are the names Sum of Products and Products of Sums?
    * SoP - The sum of Products is by adding the answers of the multiplied variables. (A&B)+(C&D)
    * PoS - The product of Sums is multiplying the answers of the added variables. (A+B)&(C+D)
### Open the test.v file – how are we able to check that the signals match using XOR?

