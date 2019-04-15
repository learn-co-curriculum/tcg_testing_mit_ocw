# Principles of Testing

## Learning Goals

- Explain the value of testing
- Design a test suite for a method by partitioning its input and output space
- Judge a test suite by measuring its code coverage
- Decide when to use blackbox vs. whitebox testing, unit tests vs. integration tests, and automated regression testing

## Introduction

Like the rest of programming, to effectively test code you need to learn both the syntax and the strategy. Testing strategy - what to test, how to test it, how to know when you've tested enough - is the subject of lots of disagreement in the programming community.

The [Chapter on Testing](https://ocw.mit.edu/ans7870/6/6.005/s16/classes/03-testing/) from MIT's Software Construction open course covers the basics of thinking as a tester. In particular, it emphasizes focusing on finding situations where the code will _break_ rather than ones where it will _work_, and on splitting the space of all the possible cases to test into _partitions_ to get the most value you can get from a limited number of tests.

Reading the chapter should take about 30 minutes of focused time.

## Post-check

- What is the difference between unit testing and integration testing?
- Why is thinking about boundaries important to choosing test cases?
- In what ways do we use tests in the Flatiron curriculum? How is the same as writing tests for a 'real' software application, and how is it different?
