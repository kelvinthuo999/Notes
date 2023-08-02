# TIME COMPLEXITY
## Introduction

- Necessary concept in competitive programming.
- An algorithm is a step by step procedure to solve computational problem.
- Algorithm are written at design time.
- Writing a good algorith requires domain knowledge.
- Any language can be used to write an algorithm(if capable, use mathematical notation).
- An algorithm is H/W and S/W independent.
- Analyze an algorithm to see if it achieves the objectives set.
- Priori analysis is done on algorithms.

## Characteristics of algorithm

- Can take 0 or more input.
- Must generate atleast one output.
- Must be definite.
- Must be finite.
- Must be effective.

## How to analyze an Algorithm

- Time. Should be time efficient.
- Space. 
- Network.
- Power consumption.
- CPU registers.

## Frequency count method

- Each statement takes one unit of time.
- Two nested loops take Order(n^2) time.

## Tracing

- You can use tracing the execution of code to find time complexity.
- Some code that used tracing to determine time complexity:
	1. for (i = 0; i < n; i++) 		= O(n)
	2. for (i = 0; i < n; i = i + 2) 	= O(n)
	3. for (i = n; i > 1; i--)		= O(n)
	4. for (i = 1; i < n; i = i * 2)	= O(log n) base 2
	5. for (i = 1; i < n; i = i * 3) 	= O(log n) base 3
	6. for (i = n; i > 1; i = i / 2) 	= O(log n) base 2

## if and while loop
- Simple loop takes O(n).
- while (a < b) will take log n.

## Types of time functions

- O(1) refers to constant time.
- O(log n) time complexity is logritemic.
- O(n) is linear.
- O(n squared) quadratic.
- O(n cubed) cubic.
- O(2 ^n^) exponential.
A ^2^


